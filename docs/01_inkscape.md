---
layout: default
title: Návrh Inkscape
nav_order: 2
---

# Krok 1: Vytvoření PCB art v Inkscape

V tomto kroku se naučíme, jak v programu **Inkscape** vytvořit **PCB art** – což je grafika, která bude sloužit pro vytvoření obrysu desky, zlatých plošek a silk screen. Inkscape je bezplatný program pro vektorovou grafiku, který nám umožní jednoduše nakreslit všechny potřebné součásti pro náš plošný spoj.

## Co potřebujeme:
- Počítač s nainstalovaným **Inkscape** (můžete si ho stáhnout z [oficiálních stránek Inkscape](https://inkscape.org/))
- Představu o rozložení desky (pokud máte nějaký návrh nebo schéma obvodu, bude to výhoda)

## 1. Příprava prostředí v Inkscape

Nejprve otevřeme Inkscape a vytvoříme nový soubor.

1. **Otevřete Inkscape** a klikněte na **Soubor** > **Nový**.
2. Pro práci s plošným spojem je dobré změnit rozměry pracovní plochy, aby odpovídaly rozměrům vaší desky. Klikněte na **Soubor** > **Vlastnosti dokumentu**, a nastavte vhodnou velikost stránky, např. 100 mm x 100 mm nebo podle velikosti vaší desky.
3. Vytvořte si 3 vrstvy:
   1. Cut - pro obrys desky (Board Outline)
   2. Silk - pro bílou barvu (Silk)
   3. Gold - pro zlatou (Solder mask)

## 2. Vytvoření obrysu desky

Obrys desky je základní tvar plošného spoje.

1. **Nakreslete obrys desky**:
    - Vektorové křivky
    - Vektorizace obrázku.

2. **Nastavte tloušťku čáry na 1 mm**:
    

## 3. Vytvoření tvaru pro pájivou masku (zlatá)

Zlaté plošky jsou místa, na které se připojují součástky. Takové plochy nemají nepájivou povrchovou úpravu a je vidět základní materiál PCB - měď. 
> S tímto tvarem opatrně, tam, kde necháme koukat měď, nemůžeme umístit součástky - zkratovaly by se navzájem.

## 4. Vytvoření tvaru pro sítotisk (bílá)

Silk screen je grafika, která obsahuje označení pro jednotlivé součástky (například "R1" pro rezistor nebo "C1" pro kondenzátor). Tato grafika slouží k označení, kde mají být součástky umístěny na desce. Dělá se buď černá pro bílé desky nebo bílá pro všechny ostatní. V našem případě bude vždy bílá.

> Někteří výrobci dnes nabízejí UV silk screen, kdy na desku přenesou barevný obrázek.