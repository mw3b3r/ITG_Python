# 📂 Výukové materiály

Tento repozitář slouží jako centrální úložiště kódů, úkolů a materiálů z našich lekcí.

---

## 📅 Obsah kurzu

### L1: Input, počty a textové řetězce (17.9. – 18.9.)
Základy práce s interaktivním vstupem a zpracováním dat v programu:
* **`input()`:** Načítání uživatelských vstupů za běhu programu.
* **Aritmetické operace:** Využití programu jako kalkulačky, práce s čísly a proměnnými.
* **Textové řetězce (Strings):** Manipulace s textem, spojování řetězců (konkatenace) a základní metody.

### L2: Práce s textem, porovnávání a seznamy (24.9. - 25.9.)
Pokročilejší práce s textem, logické podmínky a první datová struktura:
* **Metody textových řetězců:** `upper()`, `lower()`, `replace()`, `find()`, `split()` a `join()`.
* **Indexování a výřezy (slicing):** Přístup k jednotlivým znakům přes `text[0]` a výřezy typu `text[:3]`, `text[2:]` nebo `text[3:6]`. Indexuje se od nuly.
* **Formátování v f-stringu:** Zaokrouhlení přímo ve výpisu, např. `{cislo:.2f}`.
* **Porovnávání:** Operátory `==`, `!=`, `>`, `<`, `>=`, `<=`, výsledek je vždy `True` nebo `False` a dá se uložit do proměnné.
* **Logické operátory:** Spojování podmínek pomocí `and` a `or`, hledání textu pomocí `in`.
* **Seznamy (Lists):** Vytvoření seznamu, přístup k položkám přes index (včetně `[-1]` pro poslední položku), přidávání (`append()`, `insert()`), odebírání (`remove()`), hledání (`in`), délka (`len()`) a řazení (`sorted()`).

### L3: Podmínky a cykly
Program se učí rozhodovat a opakovat činnost:
* **Podmínky:** `if`, `elif` a `else`. Větve se vyhodnocují shora dolů a provede se jen první, která platí. Kód patřící k podmínce se odsazuje o 4 mezery.
* **Vnořené podmínky:** Podmínka uvnitř podmínky, hodí se, když se na druhou věc má smysl ptát až po splnění první (např. heslo až po správném jménu).
* **Cyklus `for` a `range()`:** Opakování kódu pro čísla od-do. `range(1, 6)` dává 1 až 5, poslední číslo se nezahrnuje.
* **`for` přes seznam a přes text:** Procházení položek seznamu nebo jednotlivých písmen.
* **Počítadlo a součet v cyklu:** Proměnná založená na 0 před cyklem a přičítání v cyklu (`soucet += x`, `pocet += 1`), případně s `if` uvnitř cyklu.
* **Výběr do nového seznamu:** Prázdný seznam `[]` a přidávání vyhovujících prvků přes `append()`.
* **Zbytek po dělení `%`:** Například test na sudé číslo `c % 2 == 0`.

### L4: Cyklus while a funkce
Opakování s předem neznámým počtem kol a vlastní znovupoužitelné funkce:
* **Cyklus `while`:** Opakuje kód, dokud platí podmínka. Hodí se, když předem nevíme, kolik kol bude potřeba. Pozor na nekonečný cyklus, když se hodnota v podmínce nemění.
* **`while True` a `break`:** Cyklus, který běží, dokud ho příkaz `break` neukončí (např. zadávání známek do slova „konec“).
* **Modul `random`:** `random.randint(1, 10)` pro náhodné celé číslo (včetně obou mezí) a `random.choice(seznam)` pro náhodnou položku. Příklad: hra Hádej číslo.
* **Omezený počet pokusů:** Počítadlo v podmínce cyklu, ověření hesla se třemi pokusy.
* **Funkce:** Definice přes `def`, parametry a volání. Funkce se provede až po zavolání.
* **`return`:** Funkce vrací hodnotu, kterou lze uložit do proměnné nebo vypsat. Rozdíl oproti `print()` uvnitř funkce.
* **Více parametrů a spolupráce s cyklem:** Hodnoty se dosazují podle pořadí. Funkce kombinovaná s podmínkou, `for` cyklem a hledáním největší hodnoty.


---

## 🛠️ Tahák pro práce s Gitem a GitHubem

Pokud pracuješ s Gitem poprvé, nemusíš mít obavy. GitHub funguje v zásadě jako **verzionovaný cloudový disk**, kde máš přehled o všech změnách v kódu.
Pokud si nechceš zatím Gitem komplikovat život, klikni na soubor který chceš získat a prostě si ho stáhni k sobě. 

Zde je pár základních pojmů, se kterými budeme pracovat:

1. **Repozitář (Repo):** Projektová složka, která má v sobě uloženou kompletní historii změn.
2. **Klonování / Stahování:** Způsob, jak dostat soubory z GitHubu k sobě do počítače (do lokálního prostředí).
3. **Commit & Push:** Ukládání změn (commit) a jejich odeslání zpět do sdíleného úložiště na GitHub (push).
