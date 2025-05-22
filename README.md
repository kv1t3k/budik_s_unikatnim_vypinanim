# Chytrý budík s unikátním vypínáním

Tento projekt vznikl v rámci soutěže organizované ve spolupráci se **ZŠ Židlochovice** a **FabLabem**. Naším cílem bylo vytvořit **moderní zařízení**, které propojí technologie jako **3D tisk, gravírování a programování** – výsledkem je **chytrý budík s unikátním způsobem vypínání pomocí otázek**.

## 🔧 Popis funkce

Budík se automaticky připojí k Wi-Fi a zobrazuje aktuální čas. Uživatel si přes **webovou aplikaci** nastaví:

- Čas buzení
- Otázky pro vypnutí budíku
- Vypnutí

Při buzení je nutné správně zodpovědět zvolenou otázku v aplikaci, jinak budík **nepřestane zvonit**.

## 🌐 Ovládání přes aplikaci

1. Přiložením telefonu k **NFC tagu** nebo použitím zkratky se otevře webová aplikace.
2. V aplikaci je možné:
   - Nastavit čas buzení
   - Přidat vlastní otázky (např. matematické nebo znalostní)

## 🛠️ Použité technologie

- **ESP32-S3 Pico**
- **8x32 LED displej**
- **Vlastní návrh a výroba desky plošných spojů (PCB)**
- **NFC technologie**
- **Gravírovaný a 3D tištěný design**
- **Webová aplikace běžící lokálně na ESP32-S3**

## ⚙️ Jak budík zapnout

1. Připojte budík k elektrické zásuvce přes USB-C.
2. Automaticky se připojí k přednastavené Wi-Fi síti.
3. Na displeji se zobrazí aktuální čas.
4. Ovládejte pomocí telefonu – přes NFC nebo zkratku.

## 💡 Proč je náš budík jiný?

| Náš budík 🧠               | Běžné budíky 😴               |
|---------------------------|-------------------------------|
| Ručně vyrobený            | Sériová výroba                |
| Vypínání pomocí otázek    | Jednoduché tlačítko          |
| Aktivní probuzení         | Minimální interakce          |

## 🎥 Demo a prezentace

> Video a ukázka z provozu jsou součástí školní prezentace a budou přidány i sem později.

## 📦 Rozpočet a srovnání

Projekt byl sestaven z komponent dostupných v ČR, kvůli pravidlům soutěže. Pro srovnání jsme testovali i ceny z Aliexpressu.

*(viz podrobnosti v přiloženém souboru `rozpočet AL x CZ.xlsx`)*

## 👨‍💻 Autoři projektu

Tým žáků ZŠ Židlochovice, Jiří Vítek, Jonáš Krejčiřík kaso-0, Matěj Marek, Patrik Hoff (2025)  
Mentor: jiri.vitek@zszidlochovice.cz

---

> V budoucnu plánujeme rozšířit funkce, přidat více typů otázek a možnost aktualizace přes internet.
> Do budoucna plánujeme také přidat do budíku nabíjecí baterii, aby Vás budík v případě výpadku proudu nepřestal fungovat a spolehlivě Vás ráno vzbudil.



