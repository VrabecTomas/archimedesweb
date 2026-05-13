# Archimedes Physics Lab 2026

Webová aplikace pro interaktivní simulaci Archimedova zákona. Program vizualizuje chování těles v různých kapalinách na základě jejich hustoty.

## Funkce
*   **Fyzikální engine**: Simulace vztlakové síly v reálném čase.
*   **Variabilita materiálů**: Možnost volby mezi kovy, dřevem a plyny.
*   **Různá prostředí**: Simulace v kapalinách o různých hustotách (voda, rtuť, láva).
*   **Badge systém**: Logování dosažených výsledků a fyzikálních limitů.

## Technické parametry
*   **Jazyk**: HTML5, CSS3 (Tailwind CSS framework).
*   **Logika**: Vanilla JavaScript.
*   **Animace**: GSAP (GreenSock Animation Platform) pro přesné modelování pádů a nadlehčování.

## Instalace a spuštění
1. Stáhněte soubor `index.html`.
2. Otevřete jej v jakémkoliv moderním webovém prohlížeči.
3. Vyberte objekt a kapalinu a klikněte na "Analyse Physics".

## Princip výpočtu
Aplikace pracuje se vztahem hustoty tělesa ($\rho_s$) a kapaliny ($\rho_l$):
- $\rho_s > \rho_l \implies$ těleso klesá.
- $\rho_s < \rho_l \implies$ těleso plave.
- Vztlaková síla je modelována vzorcem $F_{vz} = V \cdot \rho_l \cdot g$.
