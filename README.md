# BKG

UWAGA!
Od wersji v0.0.1e gra jest publikowana na itch.io. Link do gry na itch.io: https://xaviush.itch.io/bkg.

CHANGELOG

v0.0.0a
Dodano 2 bloki: kamień i blok trawy
Dodano podstawowe sterowanie kamerą (rotacja kamerą przesuwając myszą, chodzenie WASD, Q oznacza zejście w dół dla trybu kreatywnego i obserwatora, E oznacza wejście w górę dla trybu kreatywnego i obserwatora (nie, nie, nie jest to skok)
Dodano tryb obserwatora
Mapa jest wielkości 32 bloków na 64 bloki na 32 bloki typu superpłaskiego

Znalezione błędy:
$0.0 Rotacja kamerą obejmuje też 3 oś, co powoduje, że operacja ta na kamerze przypomina imersją podróż przez ocean

v0.0.0b
Naprawiono błąd $0.0

v0.0.1a
Dodano blok ziemi
Dodano możliwość zapauzowania gry i jej wznowienia
Zmieniono reprezentację gry z pełnego ekranu na okienko
Przeskalowano prędkość poruszania się i czułości myszy

v0.0.1b
Dodano blok powietrza
Dodano fizyczną postać gracza
Zmieniono system tworzenia się bloków (w tym dodano mapę bloków)

Znalezione błędy:
$1.0 Jeśli kamera nie jest ustawiona prostopadle do podłoża, to poruszanie się gracza jest nieprawidłowe

v0.0.1c
Wprowadzono mechaniki budowania i niszczenia w grze
Dodano opcję powrotu gracza na miejsce spawnu (pod klawiszem K) oraz resetu mapy (pod klawiszem R)
Zmieniono tworzenie się mapy bloków
Zmieniono id wszystkich bloków poza powietrzem (id kamienia zmieniło się z 10 na 20, ziemi, z 21 na 31, a bloku trawy z 20 na 30)
Podwyższono mapę z wysokości 64 na 128

Znalezione błędy:
$1.1 Reset mapy nie resetuje mapy
$1.2 Budowanie jest trochę zbugowane

v0.0.1d
Naprawiono błędy $1.0 i $1.2
Tymczasowo zlikwidowano możliwość resetu mapy.

v0.0.1e
Przywrócono reset mapy
Naprawiono błąd $1.1
Dodano skałę macierzystą

v0.0.2a
Tekstury są niejednolite.
Dodano kruszony kamień.
Dodano wewnętrzny kursor.
Dodano zaznaczenie bloków.
Dodano cieniowanie.

Znalezione błędy:
$2.0 Nie widać wewnętrznego kursora

v0.0.3a
Dodaje menu pauzy wraz z interaktywnymi przyciskami wznowienia gry, resetu mapy oraz wyjścia z gry oraz z niewłączonym jeszcze przyciskiem włączającym menu ustawień sterowania.
Usunięto na stałe możliwość resetu mapy przy użyciu klawisza R (zastąpiono go przyciskiem resetu mapy w menu pauzy).
Naprawiono błąd $2.0
Dodano pasek szybkiego wyboru (na razie wyłącznie jako grafika, bo są jakieś problemy z znalezieniem elementów tego paska przez skrypt w trakcie budowy oraz przesuwania scrollem myszy po nim)

Znalezione błędy:
$3.0 Nie działa przycisk wyjścia z gry

v0.0.3b
Naprawiono błąd $3.0 oraz pasek szybkiego wyboru (jest już w pełni funkcjonalna)
Jest możliwość wyboru bloku, którym się buduje
Zepsuto menu pauzy oraz sterowania (które dodano w tej wersji)
Dodano bloki: cegieł oraz szkła
