+++
title = "Human ID - wygrana w hackathonie ETH Warsaw ($2,000)"
description = "Jak zbudowaliśmy system weryfikacji oparty o DNA i wygraliśmy na ETH Warsaw 2025"
date = 2025-09-05T12:00:00+02:00
type = ["posts","post"]
toc = true
tags = ["tech", "hackathon", "web3", "blockchain", "ethwarsaw"
]
categories = [
]
[ author ]
  name = "Wiktor Pinkwart"
+++

Podczas ETH Warsaw 2025 wziąłem udział w hackathonie razem z Maxem Kokocomem i Rahimem Unlu. Nasz projekt, Human ID, zdobył dwie nagrody oraz $2,000, a samo doświadczenie było dla mnie bardzo znaczące.

Pomysł, nad którym pracowaliśmy, wyrósł z problemu, który coraz trudniej ignorować: weryfikacji człowieka w erze AI.

---

## Problem, który adresowaliśmy

Tradycyjne metody uwierzytelniania szybko przestają być wiarygodne. Voice ID można klonować. Face ID oraz weryfikacja oparta o obraz mogą być spoofowane. Nawet rozwiązania wieloskładnikowe coraz częściej opierają się na sygnałach, które systemy AI potrafią imitować lub odtwarzać.

W kontekstach wysokiego ryzyka, takich jak KYC, dostęp do infrastruktury krytycznej czy wrażliwe operacje, tworzy to realną lukę. Pytanie nie brzmi już, jak uczynić uwierzytelnianie wygodniejszym, lecz jak sprawić, by było wysoko odporne na manipulację w świecie generatywnej AI.

Jedna kategoria sygnałów pozostaje znacznie trudniejsza do sfałszowania: dowody biologiczne, takie jak ślina czy krew, połączone z kryptograficzną weryfikacją.

---

## Idea stojąca za Human ID

Human ID badało, w jaki sposób weryfikacja oparta o DNA może zostać połączona z kryptografią oraz infrastrukturą Web3, aby stworzyć silniejszą formę dowodu „człowieczeństwa".

W naszym prototypie:

* Wykorzystywaliśmy wyniki sekwencjonowania DNA, przetwarzane do postaci sygnału weryfikacyjnego
* Dwa niezależne wyniki były porównywane w celu zasymulowania procesu uwierzytelniania
* Powstały dowód był zapisywany w GolemDB, bazie danych opartej na blockchainie
* Użytkownik mógł podłączyć portfel dzięki integracjom BuidlGuidl
* Użyliśmy także Web3Pi do symulacji części środowiska wykonawczego
* Dowód weryfikacji był powiązany z portfelem i utrwalony on-chain

Praca z GolemDB okazała się bardzo naturalnym wyborem dla tego typu problemu. Dobrze pokazała, że blockchainowe bazy danych najlepiej sprawdzają się w obszarach weryfikacji, dowodów i integralności krytycznych rekordów, a nie w zastosowaniach spekulacyjnych.

---

## Moja rola

Moja praca w projekcie koncentrowała się na integracjach i infrastrukturze:

* Budowie endpointów nasłuchujących wyników weryfikacji
* Obsłudze zapisów i odczytów z GolemDB
* Integracji portfela i przepływu tożsamości przy użyciu narzędzi BuidlGuidl
* Komponentach front-endowych

Projekt jest open-source: **[github.com/rahimunlu/humanID](https://github.com/rahimunlu/humanID)**

---

## Refleksje

Dowód „człowieczeństwa" staje się problemem fundamentalnym. Wraz z rozwojem systemów AI koszt podszywania się spada, a koszt zaufania rośnie. Rozwiązania tego typu mogą mieć zastosowanie daleko poza cyfrowym KYC. Przykłady to dostęp do obiektów jądrowych, systemów sterowania, operacji finansowych o wysokiej wartości czy wszędzie tam, gdzie błąd uwierzytelnienia niesie poważne konsekwencje.

Podsumowując, był to bardzo dobrze spędzony czas. Nauczyłem się dużo, poznałem ciekawych ludzi i wyszedłem z tego doświadczenia z dużą motywacją do budowania kolejnych projektów.

---

## Zdjęcia z ETH Warsaw 2025

{{< image src="/images/ethwarsaw/ETHWarsaw1.jpeg" alt="ETH Warsaw 2025" position="center" style="border-radius: 8px; max-width: 100%; margin: 1rem 0;" >}}

{{< image src="/images/ethwarsaw/ETHWarsaw2.jpeg" alt="ETH Warsaw 2025 Hackathon" position="center" style="border-radius: 8px; max-width: 100%; margin: 1rem 0;" >}}

{{< image src="/images/ethwarsaw/ETHWarsaw3.jpeg" alt="Human ID Team" position="center" style="border-radius: 8px; max-width: 100%; margin: 1rem 0;" >}}

{{< image src="/images/ethwarsaw/ETHWarsaw4.jpeg" alt="ETH Warsaw 2025 Award" position="center" style="border-radius: 8px; max-width: 100%; margin: 1rem 0;" >}}


