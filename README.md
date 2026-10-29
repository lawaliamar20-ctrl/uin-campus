# UIN-Campus

Système de gestion académique de l'UIN (projet fil rouge, TP 2).

## Versions des outils

- g++ : g++ (Ubuntu 15.2.0-16ubuntu1) 15.2.0
- clang++ : Ubuntu clang version 21.1.8 (6ubuntu1)
- cmake : cmake version 4.2.3
- ninja : 1.13.2
- gdb : GNU gdb (Ubuntu 17.1-2ubuntu1) 17.1
- git : git version 2.53.0

## Construction

    cmake --preset debug
    cmake --build --preset debug
    ./build/debug/uin-campus

Le preset debug active AddressSanitizer et UBSan.

## Version Release

    cmake --preset release
    cmake --build --preset release
    ./build/release/uin-campus
