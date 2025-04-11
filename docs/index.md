---
layout: default
title: Úvod
nav_order: 1
---

# Jak se vyrábí plošný spoj

V tomto projektu se seznámíme s celým procesem výroby plošného spoje (DPS - deska plošných spojů nebo PCB - printed circuit board). Podíváme se na to, jak se vytváří design, co všechno umí software pro návrh PCB a ce se všechno musí v továrně stát, abychom desku mohli osadit. Nakonec si PCB osadíme a oživíme.


## Krok 1: Nakreslení motivu v Inkscape

V prvním kroku si vytvoříme motiv pro náš plošný spoj. K tomu využijeme **Inkscape**, což je otevřený program pro vektorovou grafiku. Pomocí tohoto programu si nakreslíme pouze "uměleckou část" - tvar desky a grafické prvky.

1. **Vytvoření návrhu** - Technologie pro výrobu PCB má omezené možnosti a můžeme použít jenom tři barvy.
2. **Export do formátu** - Výstupy jsou potřeba ve formátu png.

## Krok 2: Vytvoření návrhu PCB v EasyEDA

V dalším kroku použijeme program **EasyEDA**, který je zaměřený na návrh plošných spojů. Programy pro návrh PCB fungují podobně. V prvním kroku je potřeba nakreslit elektrotechnické schéma, přiřadit k němu součástky a jejich "footprinty" a nakonec je rozmístit a propojit.

1. **Vytvoření schématu** - schéma máte již připravené, jenom si ho prohlédme a popíšeme
2. **Import do EasyEDA:** Importujeme náš soubor z Inkscape do EasyEDA a vytvoříme tak základní návrh našeho PCB.
3. **Návrh PCB:** Vytvoříme skutečný návrh plošného spoje s přesnými rozměry, umístěním součástek a propojením.
4. **Kontrola:** Zkontrolujeme návrh, abychom se ujistili, že vše funguje správně, a že není žádné chyby v návrhu (např. zkraty nebo nesprávné propojení).
5. **Objednání** Nic objednávat zatím nebudeme, jenom si ukážeme, jak jednoduché to je.

## Krok 3: Výroba v Číně

Po dokončení návrhu pošleme náš projekt na výrobu. Využíváme službu, která nám umožní poslat náš návrh do továren v Číně, kde nám vyrobí skutečný plošný spoj.

> Tip: Důležité je, že některé společnosti nabízejí levné prototypy PCB, což nám umožňuje testovat náš design před výrobou většího množství.

## Krok 4: Osazení součástek

Jakmile máme plošný spoj, můžeme začít s jeho osazováním. To znamená, že na desku připevníme všechny potřebné součástky, jako jsou rezistory, kondenzátory, LED diody, čipy a další.

1. **Příprava součástek:** Na začátku si připravíme všechny součástky, které budeme potřebovat k osazení.
2. **Osazování:** Postupně připojujeme součástky na desku pomocí páječky nebo automatizovaných osazovacích strojů.
3. **Kontrola:** Po osazení všech součástek je potřeba desku pečlivě zkontrolovat, zda jsou všechny součástky správně připojeny.

## Krok 5: Oživení plošného spoje

Po osazení součástek přichází poslední krok, kterým je **oživení plošného spoje**. To znamená, že připojíme naši desku k napájení a ověříme, zda vše funguje, jak má.

1. **Napájení:** Připojíme desku k napájení a zapneme ji.
2. **Testování:** Otestujeme, zda všechny obvody fungují správně. Pokud ne, hledáme chyby v návrhu nebo ve spájení.
3. **Úpravy:** Pokud objevíme nějaké problémy, provedeme úpravy a znovu otestujeme.

