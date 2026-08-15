# Story_Reader 

Shot EN desc: JavaScript applicication for reading EN stories from JSON configuration files

Interaktivní webová aplikace vytvořená pro studenty k zábavnému procvičování čtení a poslechu anlického jazyka. Aplikace spojuje textový příběh s mluveným slovem a dalšími zvukovými efekty, což pomáhá k udržení pozornosti při NEnudné výuce jazyka.

## ✨ Hlavní funkce
* **Výběr příběhů:** Roletkové menu pro snadné přepínání mezi různými pohádkami.
* **Audio přehrávač:** Každý řádek má vlastní namluvený hlas (postavy) a zvukové efekty na pozadí.
* **Zvýraznění textu:** Právě čtený řádek se automaticky graficky zvýrazní a vycentruje na obrazovce.
* **Bilingvní text:** Možnost skrýt/zobrazit český překlad pod původním textem kliknutím na tlačítko.
* **Responzivní design:** Aplikace je plně přizpůsobena pro pohodlné čtení na mobilních telefonech i tabletech.
* **Ochrana proti překlikům:** Během přehrávání se ovládací prvky uzamknou, aby se zamezilo nechtěnému přerušení.

## 🚀 Jak aplikaci spustit
Aplikace běží jako statický web, takže není potřeba nic instalovat. 
Stačí kliknout na tento odkaz: **[DOPLŇ SVŮJ ODKAZ NA GITHUB PAGES]**

## 🛠️ Použité technologie
* **HTML5**,* **CSS3**,* **JavaScript**
* **JSON** pro uchovávání textů příběhů a mapování zvukových stop

## 📂 Struktura dat
Příběhy se načítají dynamicky ze souboru `library_web.json`. Každý příběh má pak svůj vlastní JSON soubor obsahující časovou osu (timeline) a odkazy na konkrétní  `.mp3` soubory pro hlasy a zvukové efekty (SFX).
