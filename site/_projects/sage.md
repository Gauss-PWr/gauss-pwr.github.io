---
layout: single
title: Statystka i Sage
date: 2024-02-26 19:57 +0100
---
Projekt **_Statystyka i Sage_** jest jednym z naszych pierwszych projektów. Projekt ten ma na celu rozbudowę darmowego pakietu matematycznego [Sage](http://sagemath.org/) o możliwości statystyczne.

Pakiet Sage cechuje się bardzo modularną budową. Nowe elementy w pakiecie Sage mogą pojawić się dzięki jednej z dwóch dróg. Pierwszą z nich jest implementacja całej funkcjonalności od podstaw. Dzieje się tak często, gdy pakiet zawiera pewne metody jako pierwszy. Inną drogą jest droga integracji. Sage integruje w sobie ponad sto innych darmowych pakietów specjalistycznych. Integracja przebiega stopniowo. Oprócz samego włączenia pakietu, konieczne jest stworzenie warstwy komunikacji dodanego kodu z pozostałymi elementami pakietu. Statystyka w pakiecie Sage jest właśnie we wczesnej fazie takiej integracji, tzn. z Sagem zintegrowany został pakiet R oraz SciPy (zawierający moduł statystyczny). Istnieje też prosta implementacja szeregów czasowych w module finansowym oraz podstawowe statystyki opisowe w module statystycznym. Niestety, obecnie nikt nie prowadzi dalszego rozwoju pakietu w tym kierunku, co było inspiracją dla powstania tego projektu.

Projekt podzielony jest na cztery etapy. Opis ich wszystkich, wraz z zadaniami oraz wymaganiami stawianymi członkom zespołów podczas każdego etapu znajduje się poniżej. Aktualnie jesteśmy w trakcie realizacji pierwszego etapu projektu. Obecnie projekt realizowany jest jedynie przez członków naszego koła, jednak w dalszych etapach projektu nie wykluczamy współpracy z innymi kołami naukowymi.

1.  Etap projektowy
    1.  Zadania
        *   Analiza istniejących implementacji metod statystycznych w pakietach matematycznych, takich jak Mathematica, Maple, Magma.
        *   Analiza istniejących implementacji metod statystycznych w pakietach statystycznych, takich jak Statistica, R, SAS, SPSS.
        *   Wyodrębnienie wymaganej funkcjonalności, stanowiącej rozsądną bazę dla przyszłego rozwoju pakietu, pozwalającej jednocześnie zrealizować statystyczne laboratoria do zajęć znajdujących się w programie studiów na kierunkach matematycznych i informatycznych.
        *   Zaprojektowanie interfejsu programistycznego dla wybranej funkcjonalności, gwarantującego szybki i łatwy dostęp do metod statystycznych.
        *   Zaprojektowanie interfejsu manipulacji danymi w obrębie pakietu Sage.
    2.  Wymagania stawiane członkom zespołu na tym etapie
        *   Znajomość podstaw statystyki.
        *   Przynajmniej podstawowa znajomość jednego pakietu statystycznego bądź matematycznego.
        *   Mile widziana znajomość zasad projektowania ergonomii użytkowania.
2.  Etap algorytmiczny
    1.  Zadania
        *   Analiza zaproponowanej na etapie projektowym funkcjonalności oraz ustalenie jakich metod należy użyć do implementacji.
        *   Udokumentowanie algorytmów.
    2.  Wymagania stawiane członkom zespołu na tym etapie
        *   Znajomość technik projektowania algorytmów i metod numerycznych.
        *   Znajomość języka angielskiego pozwalająca na łatwe przeszukiwanie źródeł oraz pisanie dokumentacji.
        *   Mile widziana znajomość podstaw statystyki obliczeniowej.
3.  Etap implementacyjny
    1.  Zadania
        *   Optymalna implementacja opisanych algorytmów.
    2.  Wymagania stawiane członkom zespołu na tym etapie
        *   Dobra znajomość języków C oraz Python.
        *   Dostęp do komputera wyposażonego w system Linux, Solaris, FreeBSD lub MacOS X i umiejętność swobodnego poruszania się w nim.
        *   Mile widziane doświadczenie w pracy z rozproszonymi systemami kontroli wersji jak Mercurial oraz umiejętność posługiwania się protokołem SSH.
4.  Etap tworzenia interakcji
    1.  Zadania
        *   Przygotowanie interfejsu manipulacji danymi.
        *   Przygotowanie demonstracji metod przy użyciu techniki „interact”.
    2.  Wymagania stawiane członkom zespołu na tym etapie
        *   Dobra znajomość technologii internetowych takich jak HTML, CSS, JavaScript, AJAX oraz JQuerry.
        *   Podstawowa znajomość języka Python.
        *   Mile widziane doświadczenie w pracy z technologiami Twisted, Sphinx, Jinja oraz SQLAlchemy.