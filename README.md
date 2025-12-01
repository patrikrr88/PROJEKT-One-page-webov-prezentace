# VPN Protector – Dokumentace projektu

**Autor:** Patrik Rohlena  

---

## 1. Úvod

Tento projekt představuje jednostránkový web propagující fiktivní VPN službu *VPN Protector*. Web se zaměřuje na bezpečnost, anonymitu a rychlé šifrované připojení. Jednotlivé části stránky budou naplněny daty z externích JSON souborů pomocí AJAXu. Cílem je vytvořit moderní, responzivní a technicky čistou prezentaci služby s jednoduchou serverovou komunikací.

---

## 2. Cílová skupina

Web je určen uživatelům, kteří chtějí zvýšit úroveň svého online soukromí, obejít geografická omezení nebo bezpečně používat veřejné Wi-Fi sítě.

---

## 3. Struktura webu

### • Proč VPN?
Vysvětlení přínosů VPN, nejčastější využití a hlavní bezpečnostní rizika internetu.

### • Funkce služby
Hlavní vlastnosti: šifrování, kill-switch, zásada „no-logs“, stabilní a rychlé servery.

### • Servery a lokality
Přehled dostupných VPN serverů načítaný z JSON, včetně zemí a typu připojení.

### • Cenové tarify
Porovnání plánů, výhody jednotlivých balíčků a přehledná prezentace cen.

### • Podporovaná zařízení
Windows, Linux, Android, iOS – stručný popis kompatibility.

### • Kontakt / Podpora
Formulář odesílaný na jednoduchý PHP backend, základní informace pro uživatele.

---

## 4. Design a vizuální koncept

- tmavé barevné téma (modré a černé odstíny)  
- akcentní tyrkysové prvky  
- čisté blokové rozložení obsahu  
- Tailwind CSS pro moderní vzhled  
- gridové zobrazení serverů (2–4 sloupce podle šířky obrazovky)  

---

## 5. Použité technologie

- **Frontend:** HTML, Tailwind CSS, JavaScript  
- **Data:** JSON (sekce webu, seznam serverů, tarify)  
- **AJAX:** dynamické načítání dat do stránky  
- **Backend:** PHP skript pro odeslání formuláře  
- **Verzování:** Git + GitHub  

---

## 6. Očekávaný přínos

- práce s JSON a dynamickými daty  
- pochopení struktury one-page webů  
- zkušenosti s AJAX komunikací  
- tvorba responzivního designu  
- základ backendu v PHP  
- verzování projektu pomocí GitHubu  
