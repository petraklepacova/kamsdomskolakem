# Kam s domškolákem

Zdrojové soubory webu kamsdomskolakem.cz — výběr akcí, výletů a online zdrojů
pro domškoláky (děti 6–15 let, Praha a střední Čechy).

- `index.html` — celá stránka (obsah, styly i skript v jednom souboru)
- Obsah se aktualizuje jednou týdně, v neděli večer.

Autorka: Petra Sládková

## Ručně přidané akce

Akce, kterou Petra dodá sama (mimo nedělní sběr), se do pole `WEEKS` v `index.html` zapisuje se dvěma poli navíc:

- `m:true` – ručně přidaná položka
- `e:"RRRR-MM-DD"` – poslední den akce

Nedělní úkol „Kam vyrazit“ takové položky při přepisu pole `WEEKS` zachovává, dokud datum `e` neuplyne. Bez těchto polí by ručně přidaná akce při dalším běhu zmizela.
