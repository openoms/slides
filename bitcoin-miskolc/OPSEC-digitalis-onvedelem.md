---
marp: true
theme: gaia
class: invert
paginate: true
backgroundColor: #1a1a1a
color: #ffffff
style: |
  section {
    font-size: 28px;
  }
  h1 {
    color: #f7931a;
    font-size: 60px;
    text-align: center;
  }
  h2 {
    color: #f7931a;
    font-size: 48px;
  }
  h3 {
    color: #ffa500;
    font-size: 36px;
  }
  strong {
    color: #f7931a;
  }
  a {
    color: #4da6ff;
  }
  ul, ol {
    font-size: 26px;
    line-height: 1.6;
  }
  section {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
---

<!-- _class: lead -->

# OPSEC / digitális önvédelem

## 🔐 Hogyan legyünk biztonságban online

---
## Mitől védekezünk?
**threat modelling / fenyegetésmodellezés**

### 🎭 Fő veszélyek

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; font-size: 24px;">

<div>

🎣 **Phishing** (adatok kicsalása)
🦠 **Malware** (rosszindulatú szoftverek)
🤖 **AI Scamek** (deepfake, hang klónozás)

</div>

<div>

🆔 **Adatszivárgás** (céges adatbázisok)
📱 **Közösségi média** (social engineering)
🔨 **Fizikai támadás** (zsarolás)

</div>

</div>

---

### 🤖 Új fenyegetés: AI Scamek

<div style="font-size: 24px;">

A mesterséges intelligencia új szintre emelte a csalásokat:

* 🗣️ **Hang klónozás**: Családtagok hangjának lemásolása 10 másodpercnyi minta alapján (pl. kamu baleset miatti sürgős pénzkérés).
* 🎥 **Deepfake videók**: Ismert emberek (pl. Elon Musk) arcával és hangjával hirdetett átverések, befektetési "lehetőségek".
* 🎣 **AI által generált adathalászat**: Tökéletes nyelvtanú, személyre szabott emailek (spear phishing), amelyek a közösségi média profilod alapján íródnak.

</div>

### ⚠️ "Ne higgy a szemednek és a fülednek sem automatikusan."

---

### 🆔 Adatszivárgás Veszélyei

<div style="background: #4d0000; padding: 30px; border-left: 5px solid #ff0000; font-size: 24px;">

💥 **Adatbázis feltörések** (Webshopok, szolgáltatók)
🎯 **Célzott támadások és zsarolás**
👁️ **Teljes privacy elvesztése**
📊 **Adatbrókerek profilozása**

</div>

---

<!-- _class: lead -->

## 🛡️ Operational Security 
**(OpSec / Működési Biztonság)**

---

### 🤐 Az aranyszabály

<div style="background: #4d0000; padding: 50px; border-left: 5px solid #ff0000; font-size: 32px; text-align: center;">

**Minimalizáld a digitális lábnyomod!**
**Ne oszd meg az életed minden részletét online!**

</div>

---

### 🚫 Mit NE tegyél

<div style="font-size: 26px;">

📱 Ne posztolj **valós idejű helyzetedről** (pl. nyaralás)
💰 Ne villogj **vagyontárgyakkal, pénzügyekkel**
📍 Ne oszd meg, **hol laksz, vagy hol tanul a gyerek**
🖼️ Ne használd ugyanazt a **profilképet** mindenhol
🎁 Ne dőlj be a **sürgető kéréseknek** (scam gyanú!)
🗣️ Rögzítsenek minél kevesebb **hang- és videóanyagot** rólad nyilvánosan

</div>

---
<!-- _class: lead -->

## 🤖 Privát AI Szolgáltatók
**Biztonságos mesterséges intelligencia**

---

### Miért problémás a ChatGPT/Claude/Gemini?

<div style="font-size: 26px;">

❌ A beszélgetéseidet **felhasználják a modell tanítására**
❌ Hozzákötik a **valódi identitásodhoz** (email, telefonszám, bankkártya)
❌ Centralizált adatbázisban tárolják a legféltettebb kérdéseidet (adatvédelmi kockázat)
❌ **Cenzúrázott** vagy korlátozott válaszok

</div>

---

### 🔒 Alternatívák: Privát AI szolgáltatók

<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px; font-size: 22px;">

<div style="background: #2d2d2d; padding: 15px; border-radius: 10px;">

**ppq.ai**
Gyors és privát AI LLM hozzáférés, regisztráció nélkül.

</div>

<div style="background: #2d2d2d; padding: 15px; border-radius: 10px;">

**trymaple.ai**
LLM modellek, privacy fókusszal, nyílt forráskóddal.

</div>

<div style="background: #2d2d2d; padding: 15px; border-radius: 10px;">

**venice.ai**
Permisszionális, AI eszközök, cenzúra nélkül.

</div>

</div>

### Miért jók ezek?
✅ **E2E (végpontok közötti) titkosítás** - senki nem olvassa a promptjaidat
✅ **Nincs KYC** - nem kell megadni személyes adatokat
✅ **Lightning Network (Bitcoin) fizetés** - teljesen anonim mikrotranzakciók
✅ **Nem használják fel** a kérdéseidet a modellek tanítására

---

<!-- _class: lead -->

## 🔧 Ajánlott Eszközök
Alapvető digitális higiénia

---

### 🌐 Böngészők - Asztali gépen és Mobilon

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px;">

<div style="background: #2d2d2d; padding: 20px; border-radius: 10px;">

### 🦁 Brave

✅ Beépített adblocker
✅ Tor integráció
✅ Fingerprinting védelem

</div>

<div style="background: #2d2d2d; padding: 20px; border-radius: 10px;">

### 🦊 Firefox

✅ Nyílt forráskódú
✅ uBlock Origin
✅ Container tabs

</div>

### 🧅 Tor Browser
✅ Lassabb, de megbízhatóan elrejti az IP címedet
✅ .onion domaineket támogat

</div>

---

### 🛡️ Adblocker

<div style="background: #004d00; padding: 30px; border-left: 5px solid #00ff00; font-size: 26px;">

**uBlock Origin** (Firefox, Chrome)

✅ Blokkolja a **hirdetéseket**
✅ Blokkolja a **trackereket**
✅ Blokkolja a **malware** oldalakat
✅ **Nyílt forráskódú**

</div>

**Telepítsd:** https://ublockorigin.com

---

### 🔐 Jelszókezelő: Bitwarden

<div style="background: #004d00; padding: 30px; border-left: 5px solid #00ff00; font-size: 24px;">

✅ **Nyílt forráskódú**
✅ **Végponti (end-to-end) titkosítás**
✅ **Ingyenes verzió**
✅ **Jelszó / jelmondat generátor** (20+ karakter)
✅ **Több eszközön szinkronizál**

</div>

**https://bitwarden.com**

---

### 🔑 Jelszó biztonság

<div style="font-size: 26px;">

✅ **Egyedi jelszó** minden fiókhoz
✅ **20+ karakter**, vegyes karakterek vagy **4 szavas jelmondat**
✅ **Bitwarden** generálja
❌ **SOHA ne használd újra** a jelszavakat

</div>

<div style="background: #2d2d2d; padding: 20px; margin-top: 20px;">

**Példa erős jelszó:**
`K9#mP2$vL8@nQ5!xR7&wT3`

**Példa passphrase:**
 `correct horse battery staple`

</div>

---

![bg fit](images/password-xkcd.png)

---

![bg fit](images/password-strength-table.png)

---

### 🔐 Kétfaktoros Hitelesítés / Autentikáció (2FA)

<div style="background: #004d00; padding: 30px; border-left: 5px solid #00ff00; font-size: 26px;">

**TOTP (Time-based One-Time Password)**

✅ **Aegis Authenticator** (Android, nyílt forráskódú)
✅ **2FAS OTP** (iOS + Android)

</div>

<div style="background: #4d0000; padding: 20px; margin-top: 20px; font-size: 24px;">

❌ **SOHA ne SMS 2FA** (SIM swap támadás!)

</div>

---

### 📧 Email Aliasok

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px; font-size: 22px;">

<div style="background: #2d2d2d; padding: 20px; border-radius: 10px;">

### 🦆 DuckDuckGo

✅ Ingyenes
✅ Spam szűrés
✅ Tracker eltávolítás

**duckduckgo.com/email**

</div>

<div style="background: #2d2d2d; padding: 20px; border-radius: 10px;">

### 📧 SimpleLogin

✅ Korlátlan aliasok
✅ Egyéni domain
✅ Nyílt forráskódú

**simplelogin.io**

</div>

---

### 📧 Miért email alias?

<div style="font-size: 26px;">

🎭 **Valódi email cím rejtése**
💾 Ha egy szolgáltató **adatbázisa szivárog**, nem a valódi email-ed kerül ki
🗑️ **Könnyű leiratkozás** (alias törlése)
🚫 **Spam csökkentés**

</div>

<div style="background: #2d2d2d; padding: 20px; margin-top: 20px; font-size: 22px;">

**Példa:**
`webshop-2024@duck.com` → `felhasznalonev@gmail.com`

</div>

---

### 🔒 VPN

<div style="font-size: 24px;">

**Mikor és miért fontos?**

🌐 **IP cím és földrajzi hely elrejtése**
🔒 **ISP (internetszolgáltató) nem látja**, miket böngészel
📶 **Védelem nyilvános WiFi-n** (kávézók, repterek)

</div>

---

### 🔒 Ajánlott VPN-ek

| VPN | Jellemzők | Weboldal |
|-----|-----------|--------|
| **Mullvad** | Nincs fiók, Lightning fizetés, no-log | mullvad.net |
| **IVPN** | Nincs fiók, Lightning fizetés, no-log | ivpn.net |


<div style="background: #4d0000; padding: 20px; margin-top: 20px; font-size: 24px;">

⚠️ **Az Ingyenes VPN-ek NEM biztonságosak! Cserébe az adataiddal fizetsz.**

</div>

---

<!-- _class: lead -->

## ✅ OPSEC Alapszabályok Összefoglalása

---

### 🔑 5 Digitális Önvédelem Szabály

<div style="font-size: 28px; line-height: 2;">

1. **"Ne bízz, ellenőrizz."** (Főleg az AI világban!)
2. **Minimalizáld a megosztott adataidat.**
3. **Egyedi jelszó + 2FA mindenhez.**
4. **Használj email aliasokat gyanús helyeken.**
5. **Fizess privát módon** (Lightning) ahol csak lehet.

</div>

---

### ⚠️ SOHA ne tedd

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; font-size: 24px;">

<div>

❌ SMS 2FA használata
❌ Jelszó újrahasználat
❌ Nyilvános WiFi VPN nélkül
❌ Gép előtt hagyott feloldott telefon/laptop

</div>

<div>

❌ Gyanús linkekre kattintás (email/SMS)
❌ Túl sok infó posztolása nyilvánosan
❌ Saját névhez kötött email használata (mindenhol)
❌ Pénzkérésre azonnali utalás telefonos bemondásra

</div>

</div>

---

**Eszközök:**
- Bitwarden: https://bitwarden.com
- uBlock Origin: https://ublockorigin.com
- DuckDuckGo Email: https://duckduckgo.com/email
- SimpleLogin: https://simplelogin.io

**Privát AI:**
- ppq.ai, trymaple.ai, venice.ai

**VPN:**
- Mullvad: https://mullvad.net
- IVPN: https://ivpn.net

---

<!-- _class: lead -->

# Köszönöm a figyelmet!

## Kérdések?
