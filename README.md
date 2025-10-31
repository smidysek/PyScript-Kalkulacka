# A 🧮 Pokročilá PyScript Kalkulačka

Moderní webová kalkulačka postavená na PyScriptu, která kombinuje výkon Pythonu s jednoduchostí webového rozhraní.
Kalkulačka běží přímo v prohlížeči – není potřeba žádná instalace Pythonu!

## A 🚀 Funkce

✅ Základní operace

Sčítání, odčítání, násobení, dělení
Práce se závorkami () – respektuje prioritu operací

✅ Rozšířené matematické funkce

Mocniny ^, odmocniny √ nebo sqrt(x)
Procenta %
Logaritmus log(x)
Exponenciála exp(x)

✅ Trigonometrické funkce

sin(x), cos(x), tan(x)
Přepínání mezi stupni (°) a radiány (rad)

✅ Převody čísel

Do dvojkové, osmičkové a šestnáctkové soustavy
Samostatné tlačítko „Převést“ pro bezpečné zobrazení výsledku

✅ Historie výpočtů

Automatické ukládání provedených operací
Možnost vložit zpět předchozí výraz nebo výsledek

✅ Bezpečnost

Všechny výpočty jsou zpracovávány pomocí ast – nelze provádět škodlivý kód
Ošetření dělení nulou, neplatných znaků, více desetinných teček apod.

## A 🖼️ Ukázka

🧩 Struktura projektu
pyscript-calculator/
├── index.html        # hlavní HTML stránka s GUI
├── main.py           # logika kalkulačky (Python přes PyScript)
├── README.md         # dokumentace projektu

⚙️ Spuštění

1. Naklonuj nebo stáhni projekt:
git clone https://github.com/<tvuj-username>/pyscript-calculator.git
cd pyscript-calculator
2. Spusť jednoduchý server (nutné pro PyScript):
python -m http.server
3.Otevři v prohlížeči:
http://localhost:8000

🧠 Technologie

PyScript
Python 3.11+
HTML5 + CSS3
AST-based safe evaluator (bezpečné vyhodnocení výrazů)

## A 💡 Autoři a licence

Projekt vytvořen jako demonstrační příklad pro školní úlohu v rámci výuky Pythonu a PyScriptu.

Autor: Tomáš Šmíd
Licence: MIT
