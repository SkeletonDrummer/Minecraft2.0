# Minecraft 2.0 Modpack – Instalace

## Požadavky
- Windows
- Java JDK 25 (Adoptium Temurin viz níže)
- Doporučeno alespoň **8 GB RAM počítač**

---

## 1. Stažení souborů
Stáhni následující soubory:
- `SKlauncher-3.2.18_Setup.exe`
- `.minecraft.rar`
- `OpenJDK25U-jdk_x64_windows_hotspot_25.0.1_8.msi`

---

## 2A Instalace speciální Java JDK 25
- Nainstaluj **OpenJDK25U-jdk_x64_windows_hotspot_25.0.1_8.msi**
- **Důležité:** V sekci stromového členění komponentů k instalaci (obr.) → klikni na vrchní JDK with Hotspot → Entire feature (aby se všechny komponenty aktivovaly)
<img width="496" height="387" alt="1" src="https://github.com/user-attachments/assets/7d1f40ff-cc27-403d-9903-37246e8e897c" />
<img width="451" height="352" alt="2" src="https://github.com/user-attachments/assets/452f15a9-479b-431e-8c1c-f273b28290db" />
<img width="496" height="389" alt="3" src="https://github.com/user-attachments/assets/fa5f30e3-4bf5-4818-ac18-89470068ceee" />

---

## 2B. **Důležité!** čištění staré složky `.minecraft`
- Otevři: Start → napiš: *%appdata%* → Enter (obr.)
<img width="747" height="608" alt="start" src="https://github.com/user-attachments/assets/c7116a9c-6f19-4981-9ee3-27169e0e03d1" />

- Smaž (neřešíš starý MC) nebo přejmenuj (backup) složku **.minecraft**
<img width="757" height="572" alt="roaming" src="https://github.com/user-attachments/assets/70eaa082-57fc-4402-ac38-2f77d3bcb74b" />

---

## 2B Instalace SKLauncheru
- Nainstaluj **SKlauncher-3.2.18_Setup.exe**
- Spusť launcher

---

## 3. Nastavení účtu
- Dole vyber **Warez (Offline mode)** (obr.)
- Zadej **libovolný nickname**
- Spusť
<img width="1019" height="673" alt="4" src="https://github.com/user-attachments/assets/4088277a-6894-45cb-855a-b24e32fb153d" />
<img width="1019" height="673" alt="5" src="https://github.com/user-attachments/assets/df937724-bd15-40fa-935f-60b1127bb275" />

---

## 4. Vytvoření Fabric release
- V levém seznamu *Správce instalací (Releases)* klikni na **+** (obr.)
- Přidej nový release: (obr.)
<img width="1018" height="676" alt="6" src="https://github.com/user-attachments/assets/66b69eec-9ad8-4268-90ff-3fbc598295c4" />

   - **Verze (Loader):** Fabric
   - **Minecraft verze (vlevo):** `1.21.11`
   - **Fabric verze (vpravo):** `0.18.4`
- Rozbal **Více (Advanced)** a nastav Max RAM: (obr.)
<img width="1020" height="676" alt="7" src="https://github.com/user-attachments/assets/437de11e-1b56-4d27-a150-d27852814c3f" />

Jak zjistím kolik má můj počítač RAM? (obr.) - Otevři spráce úloh (L.Ctrl+L.Shift+Esc) → záložka výkon → Paměť → to 2. číslo (XX/XX GB) = max RAM
<img width="1317" height="769" alt="spr" src="https://github.com/user-attachments/assets/31209c02-ed5a-48d7-a3b1-6d0df92462c6" />

   - **16 GB RAM počítač** → `12 GB`
   - **Více než 16 GB RAM počítač** → `16 GB`
   - **8 GB RAM počítač** → `6.5 GB`  
     *(pokud máš jen 8 GB RAM, bude třeba in-game nastavit pár věcí, aby vše běželo plynule)*
     <img width="1017" height="670" alt="8" src="https://github.com/user-attachments/assets/79ee5943-3b41-48e7-884a-8550f964f6a4" />

---

## 5. První spuštění Minecraftu
- Klikni na **Hrát** (obr.)
<img width="1018" height="676" alt="6" src="https://github.com/user-attachments/assets/2b682884-ee15-40d2-bb88-4d01245d5618" />

- Nech Minecraft **plně naběhnout**
- V hlavním menu klikni na **Continue** ⚠️ *(důležité)*
- AŽ POTÉ Minecraft **vypni**

---

## 6. Nahrazení složky `.minecraft`
- Otevři: Start → napiš: *%appdata%* → Enter (obr.)
<img width="747" height="608" alt="start" src="https://github.com/user-attachments/assets/c7116a9c-6f19-4981-9ee3-27169e0e03d1" />

- Otevři složku **.minecraft**
<img width="757" height="572" alt="roaming" src="https://github.com/user-attachments/assets/70eaa082-57fc-4402-ac38-2f77d3bcb74b" />

- Otevři stažený `.minecraft.rar` (WinRAR / 7-Zip)
- **Nejdříve smaž** ve své `.minecraft` složce **všechny složky, které mají stejný název jako ty v archivu `.minecraft.rar`**
- ⚠️ **NEDĚLEJ přímý drag & drop přes existující soubory** (obr.
<img width="738" height="539" alt="9" src="https://github.com/user-attachments/assets/e0396099-f7a5-48ee-91f9-a96a73786cf3" />

6F. Poté **drag & drop složky z archivu** do tvojí složky `.minecraft` (obr.)
<img width="1002" height="595" alt="drag" src="https://github.com/user-attachments/assets/7c0614a1-409b-4061-9f91-1376a832c7d8" />

---

## 7. Druhé spuštění
- Znovu v SK Launcheru klikni **Hrát**
- Nech Minecraft naběhnout až do hlavního menu
- Minecraft vypni

---

## 8. Opětovné nahrazení configů
⚠️ Nutné kvůli *prvnímu spuštění*, který může přepsat konfiguraci zpět na default

- Znovu otevři Start → `%appdata%` → složka *.minecraft*
- <img width="747" height="608" alt="start" src="https://github.com/user-attachments/assets/81e37e1f-2dea-4731-acd5-59b8718222ec" />
<img width="757" height="572" alt="roaming" src="https://github.com/user-attachments/assets/9e412b50-aea0-464f-9629-085fb3f07935" />

- Znovu **smaž složky**, které jsou obsažené v `.minecraft.rar` (obr.)
<img width="738" height="539" alt="9" src="https://github.com/user-attachments/assets/ef073f1b-3608-44a3-ace4-f799d07f2687" />

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
- Přihlas se vpravo nahoře (**New Central – NE Legacy**) (obr.)
<img width="1920" height="1041" alt="10" src="https://github.com/user-attachments/assets/62ed8f97-ba07-4db0-8c91-81ab56808cd6" />
<img width="1920" height="998" alt="11" src="https://github.com/user-attachments/assets/dd47704d-e5b8-49a7-8fc0-4e381a721a73" />

- Stačí Google login

---

### 2. Vytvoření sítě (jen kvůli tutorialu)
- Proklikni tutorial vytvoření **1. networku**
- Network **nebudeš používat**
- Jakmile se dostaneš do dashboardu (obr.), zavři záložku a pokračuj dál
<img width="1919" height="994" alt="dash" src="https://github.com/user-attachments/assets/ae0fe12b-71f9-4552-a58f-c6e11a709154" />

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
- Pravým tlačítkem → **Join Network** (obr.)
<img width="189" height="148" alt="12" src="https://github.com/user-attachments/assets/887370fb-7204-40fa-b494-2b7d852ccca8" />
<img width="566" height="248" alt="13" src="https://github.com/user-attachments/assets/ef2b52d8-3f90-4743-b263-4f9b168fa3fa" />

- Vlož Network ID:
  ```
  8d1c312afa1d2c0e
  ```
- **Musíš mi dát vědět že se snažíš Joinout**, abych tě autorizoval v síti

---

## Připojení na server
- Spusť Minecraft → Multiplayer
- Připoj se na server: (obr.)
<img width="1367" height="830" alt="14" src="https://github.com/user-attachments/assets/9f8bfbc6-21ce-4aca-859c-f1a647b64df0" />
<img width="1369" height="834" alt="15" src="https://github.com/user-attachments/assets/1e3c0700-d8bb-495a-97d8-36e591c24e3c" />

*IP: 10.52.121.248*
