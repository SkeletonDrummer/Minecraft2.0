# Minecraft 2.0 Modpack – Instalace

## Požadavky
- Windows
- Java JDK 25 (Adoptium Temurin viz níže)
- Doporučeno alespoň **8 GB RAM**

---

## 1. Stažení souborů
Stáhni následující soubory:
- `SKlauncher-3.2.18_Setup.exe`
- `.minecraft.rar`
- `OpenJDK25U-jdk_x64_windows_hotspot_25.0.1_8.msi`

---

## 2A Instalace speciální Java JDK 25
- Nainstaluj **OpenJDK25U-jdk_x64_windows_hotspot_25.0.1_8.msi**
- **Důležité:** V sekci stromového členění komponentů k instalaci → klikni na vrchní JDK with Hotspot → Entire feature (aby se všechny komponenty aktivovaly)

---

## 2B Instalace SKLauncheru
- Nainstaluj **SKlauncher-3.2.18_Setup.exe**
- Spusť launcher

---

## 3. Nastavení účtu
- Dole vyber **Warez (Offline mode)**
- Zadej **libovolný nickname**
- Spusť

---

## 4. Vytvoření Fabric release
4A. V levém seznamu *Správce instalací (Releases)* klikni na **+**
4B. Přidej nový release:
   - **Verze (Loader):** Fabric  
   - **Minecraft verze (vlevo):** `1.21.11`  
   - **Fabric verze (vpravo):** `0.18.4`
4C. Rozbal **Více (Advanced)** a nastav Max RAM:
Jak zjistím kolik má můj počítač RAM? - Otevři spráce úloh (L.Ctrl+L.Shift+Esc) → záložka výkon → Paměť → to 2. číslo (XX/XX GB) = max RAM
   - **16 GB RAM počítač** → `12 GB`
   - **Více než 16 GB RAM počítač** → `16 GB`
   - **8 GB RAM počítač** → `6.5 GB`  
     *(pokud máš jen 8 GB RAM, viz poznámka níže)*

---

## 5. První spuštění Minecraftu
- Klikni na **Hrát**
- Nech Minecraft **plně naběhnout**
- V hlavním menu klikni na **Continue** ⚠️ *(důležité)*
- Až poté Minecraft **vypni**

---

## 6. Nahrazení složky `.minecraft`
6A. Otevři: Start → napiš: *%appdata%* → Enter
6B. Otevři složku **.minecraft**
6C. Otevři stažený `.minecraft.rar` (WinRAR / 7-Zip)
6D. ⚠️ **NEDĚLEJ přímý drag & drop přes existující soubory**
6E. **Nejdříve smaž** ve své `.minecraft` složce **všechny složky, které mají stejný název jako ty v archivu `.minecraft.rar`**
6F. Poté **drag & drop složky z archivu** do tvojí složky `.minecraft`

---

## 7. Druhé spuštění
- Znovu v SK Launcheru klikni **Hrát**
- Nech Minecraft naběhnout až do hlavního menu
- Minecraft vypni

---

## 8. Opětovné nahrazení configů
⚠️ Nutné kvůli *prvnímu spuštění*, který může přepsat konfiguraci zpět na default

- Znovu otevři Start → `%appdata%` → složka *.minecraft*
- Znovu **smaž složky**, které jsou obsažené v `.minecraft.rar`
- Znovu je **nahraď verzí z archivu**
- ⚠️ **NEDĚLEJ drag & drop, protože tam zůstanou zbytky co to rozbijí**

---

## 9. Dokončení
Modpack by měl být nyní funkční 🎉

---

## Důležité Poznámky

### Singleplayer
Pro hraní Singleplayer Modpack **není kompletní** – některé moduly (worldgenerování, optimalizace, funkcionalita) jsou **server-side only** = tento Modpack je pro hraní na serveru

➡️ Pro **singleplayer** je nutné stáhnout a nainstalovat `extras.rar` (tady stačí jen drag & drop + případně nechat přepsat duplikace)

---

## ZeroTier One – LAN / Server (POVINNÉ PRO HRANÍ NA SERVERU)
(pokud chceš jen Singleplayer = možné vynechat - *Je ale nutné dostáhnout extras.rar viz výše)*

### 1. Registrace
- Jdi na https://www.zerotier.com/
- Přihlas se vpravo nahoře (**New Central – NE Legacy**)
- Stačí Google login

---

### 2. Vytvoření sítě (jen kvůli tutorialu)
- Proklikni tutorial vytvoření **1. networku**  
- Network **nebudeš používat**
- Jakmile se dostaneš do dashboardu, zavři záložku a pokračuj dál

---

### 3. Instalace klienta
- Stáhni:
https://download.zerotier.com/dist/ZeroTier%20One.msi
- Nainstaluj
- **Restartuj PC**

---

### 4. Připojení do sítě
- Po startu PC:
- Vpravo dole u ikon internetu, hlasitosti apod. (případně šipka nahoru) najdi **oranžovou ikonu ZeroTier**
- Pravým tlačítkem → **Join Network**
- Vlož Network ID:
  ```
  8d1c312afa1d2c0e
  ```
- **Musíš mi dát vědět že se snažíš Joinout**, abych tě autorizoval v síti

---

## Připojení na server
- Spusť Minecraft
- Připoj se na server:
*IP: 10.52.121.248*
