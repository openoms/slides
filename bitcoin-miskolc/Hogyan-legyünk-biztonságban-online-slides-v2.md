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

# Hogyan legyünk biztonságban online

## 🔐 Bitcoin vásárlás biztonságosan

---
## Mitől védekezünk?
**threat modelling / fenyegetésmodellezés**

### 🎭 Fő veszélyek

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; font-size: 24px;">

<div>

🎣 **Phishing** (adatok kicsalása)
🦠 **Malware** (rosszindulatú szoftverek)
🔨 **Fizikai támadás** ($5 wrench attack)

</div>

<div>

💥 **Tőzsde csődök**
🆔 **adatszivárgás** (KYC, marketing adatbázisok)
📱 **Közösségi média** (social engineering)

</div>

</div>

---

### 💥 Tőzsde csődök

| Esemény | Év | Veszteség |
|---------|-----|-----------|
| **Mt. Gox** | 2014 | 850,000 BTC |
| **FTX** | 2022 | USD milliárdok |
| **Celsius** | 2022 | Csőd |

### ⚠️ "Nem a te kulcsod, nem a te coinod."

---

### 🆔 KYC Veszélyei

<div style="background: #4d0000; padding: 30px; border-left: 5px solid #ff0000; font-size: 24px;">

💥 **Adatbázis feltörések** (Ledger 2020)
🎯 **Célzott fizikai támadások**
👁️ **Teljes privacy elvesztése**
📊 **Adatbrókerek, kormány, adóhatóság**

</div>

---

<!-- _class: lead -->

## 🛡️ Operational Security 
**(OpSec / Működési Biztonság)**

---

### 🤐 ~~Arany~~ ₿itcoin szabály

<div style="background: #4d0000; padding: 50px; border-left: 5px solid #ff0000; font-size: 32px; text-align: center;">

**Ne mondd el senkinek,**
**mennyi Bitcoinod van!**

</div>

### "Hallgatni ~~arany~~ Bitcoin!"

---


### 🚫 Mit NE tegyél

<div style="font-size: 26px;">

📱 Ne posztolj **Bitcoin vásárlásról**
💰 Ne mondd el, **mennyi van**
📍 Ne mondd el, **hol tárolod**
🖼️ Ne használj **Bitcoin profilképet**
🎁 Ne kattints **giveaway-ekre** (SCAM!)
👕 Ne hordj magadon **Bitcoin logókat**

</div>

---

<!-- _class: lead -->

## 🔧 Ajánlott Eszközök

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
✅ **Self-hosted opció**

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

![bg fit](images/passphrase-strength-table.png)

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
💾 Ha a tőzsde **adatbázisa szivárog**, nem a valódi email-ed
🗑️ **Könnyű leiratkozás** (alias törlése)
🚫 **Spam csökkentés**

</div>

<div style="background: #2d2d2d; padding: 20px; margin-top: 20px; font-size: 22px;">

**Példa:**
`kraken-2024@duck.com` → `felhasznalonev@gmail.com`

</div>

---

### 🔒 VPN

<div style="font-size: 24px;">

**Miért fontos Bitcoin vásárlásnál?**

🌐 **IP cím elrejtése**
📍 **Földrajzi hely elrejtése**
🔒 **ISP nem látja**, hogy Bitcoin tőzsdét használsz
📶 **Védelem nyilvános WiFi-n**

</div>

---

### 🔒 Ajánlott VPN-ek

| VPN | Jellemzők | Weboldal |
|-----|-----------|--------|
| **Mullvad** | Bitcoin Lightning fizetés, no-log | mullvad.net |
| **IVPN** | Bitcoin Lightning fizetés, no-log | ivpn.net |


<div style="background: #4d0000; padding: 20px; margin-top: 20px; font-size: 24px;">

⚠️ **Az Ingyenes VPN-ek NEM biztonságosak!**

</div>

---

<!-- _class: lead -->

## ✅ ₿itcoin Vásárlás Biztonsági Lista

---

### 🔐 Vásárlás ELŐTT

<div style="font-size: 26px;">

1. ✅ **Brave/Firefox** telepítése
2. ✅ **uBlock Origin** telepítése
3. ✅ **Bitwarden** beállítása
4. ✅ **Email alias** létrehozása
5. ✅ **VPN** előfizetés
6. ✅ **TOTP app** telepítése (Aegis/2FAS)

</div>

---

### 💰 Vásárlás KÖZBEN

<div style="font-size: 26px;">

1. ✅ **VPN bekapcsolása**
2. ✅ **Tőzsde URL ellenőrzése** (phishing!)
3. ✅ **Email alias** használata regisztrációhoz
4. ✅ **Erős jelszó** (Bitwarden generálja)
5. ✅ **2FA bekapcsolása** (TOTP)
6. ✅ **KYC minimalizálása**

</div>

---

### 🔒 Vásárlás UTÁN

<div style="background: #4d0000; padding: 40px; border-left: 5px solid #ff0000; font-size: 28px;">

⚡ **AZONNAL vidd ki a Bitcoin-t saját wallet-be!**

❌ **Ne tárolj Bitcoin-t a tőzsdén!**

</div>

### "Nem a te kulcsod, nem a te coinod."

---

### 🛡️ Hosszú távú biztonság

<div style="font-size: 26px;">

1. ✅ **Ne mondd el**, mennyi Bitcoin-od van
2. ✅ **Ne posztolj** róla közösségi médiában
3. ✅ **Rendszeres szoftver frissítések**
4. ✅ **Jelszavak cseréje** (ha adatszivárgás)
5. ✅ **2FA backup kódok** biztonságos helyen

</div>

---

### 🔑 5 ₿itcoin Szabály

<div style="font-size: 28px; line-height: 2;">

1. **"Nem a te kulcsod, nem a te coinod."**
2. **"Ne bízz, ellenőrizz."**
3. **"Hallgatni arany."**
4. **Egyedi jelszó + 2FA mindenhez**
5. **Email alias mindenhol**

</div>

---

### ⚠️ SOHA ne tedd

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; font-size: 24px;">

<div>

❌ Bitcoin tárolása tőzsdén
❌ SMS 2FA
❌ Jelszó újrahasználat
❌ Nyilvános WiFi VPN nélkül

</div>

<div>

❌ Giveaway-ekre kattintás
❌ Bitcoin birtoklás megosztása
❌ Saját névhez kötött email használata
❌ Gyenge jelszavak

</div>

</div>

---

**Böngészők:**
- Brave: https://brave.com
- Firefox: https://mozilla.org/firefox

**Eszközök:**
- Bitwarden: https://bitwarden.com
- uBlock Origin: https://ublockorigin.com
- DuckDuckGo Email: https://duckduckgo.com/email
- SimpleLogin: https://simplelogin.io

**VPN:**
- Mullvad: https://mullvad.net
- IVPN: https://ivpn.ne

---

<!-- _class: lead -->

# Köszönöm a figyelmet!

## Kérdések?

**huszonegy.world**
