# pygame-template

# 🐍 Minu Pygame'i projekt (GitHub Codespaces)

Tere tulemast! Selles projektis saad luua oma esimese Pygame'i mängu otse brauseris. Midagi ei pea arvutisse installima – kõik vajalik toimub pilves.

---

## 🚀 Kiirjuhend

Kui oled juba kogenum, järgi neid samme:

1. **Use this template** → **Create repository**
2. **Create Codespace** (roheline nupp "Code" > "Codespaces")
3. Oota, kuni VS Code avaneb
4. Ava **Ports** sakk (all servas) → **6080 (Desktop)** → **Open in Browser**
5. Käivita terminalis: `python main.py`

---

## 📖 Samm-sammuline juhend

### 1. Projekti seadistamine
See repo on *template*. Pead tegema sellest endale isikliku koopia:
* Vajuta üleval rohelist nuppu **Use this template**.
* Vali **Create a new repository**.
* Pane projektile nimi (nt `minu-esimene-mang`).
* Vali **Public** ja vajuta **Create repository**.

### 2. Käivita pilvearvuti (Codespaces)
* Vajuta rohelisele nupule **Code**.
* Vali sakk **Codespaces**.
* Vajuta **Create codespace on main**.
* *Oota 1–3 minutit*, kuni keskkond käivitub. 
> **Märkus:** Kui GitHub küsib "Rebuild / Reopen in Container", vali alati **Rebuild**.

### 3. Ava mänguaken (Desktop)
> **⚠️ Väga oluline:** Pygame'i aken ei ilmu VS Code'i sisse, vaid eraldi "aknas" kood "vscode".

* Leia VS Code'i allservast sakk **Ports**.
* Leia port **6080** (Desktop / noVNC).
* Vajuta **Open in Browser**.
* Avaneb uus brauseri tab – see ongi sinu mänguaken! **Jäta see tab kindlasti lahti.**

### 4. Käivita mäng
* Mine tagasi VS Code'i aknasse.
* Ava terminal (kui sa seda ei näe, vali menüüst `Terminal` → `New Terminal`).
* Kirjuta terminali:
  ```bash
  python main.py


## 🤝 Koostöö paarilisega (Live Share)

Et saaksite samal ajal koodi kirjutada ilma konflikte tekitamata, kasutage Live Share'i:

*Kui sa ei näe vasakul Live Share ikooni, mine **Extensions** sakki (neli ruutu), otsi "Live Share" ja vajuta **Install**.*

1. **Juhataja:** Vajuta VS Code'i vasakus menüüs **Live Share** ikooni (sarnaneb kahe inimesega kujutisele) ja vali "Start collaboration session".
2. **Kutse:** Kopeeri link ja saada paarilisele.
3. **Külaline:** Kopeeri juhataja antud link ja kleebi see oma VS Code'i terminali või Live Share'i aknasse või jätkab web vsCode'is. 
4. **Töötage koos:** Nüüd näete mõlemad sama koodi!
   * *Märkus:* Ainult juhataja peaks tegema `Commit & Push` või `Sync Changes` muudatusi, et vältida segadust.
   
### 👤 Juhend paarilisele (Külaline)

Sinu paariline on "Juhataja" (Kapten), kes on juba mängu käivitanud. Sinu ülesanne on lihtsalt "laevale" hüpata ja appi tulla. Sa ei pea midagi installima ega seadistama!

        #### 1. Vali, kuidas soovid töötada
        Külalisena saad liituda kahel viisil. **Vali see, mis sulle rohkem sobib:**

        * **Variant A: Brauseris (Kõige lihtsam)**
            * Sa ei pea midagi arvutisse tõmbama.
            * Lihtsalt ava link (mille paariline sulle saadab) oma internetibrauseris.
        * **Variant B: VS Code programmis (Kui see on arvutis olemas)**
            * Kui sul on arvutis VS Code programm juba olemas, võid kasutada seda.
            * Kui linki avades küsitakse, kas avada see VS Code'is, vajuta **"Open"**.

        #### 2. Kuidas liituda? (Samm-sammult)

        1.  **Küsi linki:** Palu paariliselt Live Share linki (see on pikk aadress, mille tema sulle saadab).
        2.  **Ava link:** Kopeeri link oma brauserisse ja vajuta Enter.
        3.  **Logi sisse:** Kui arvuti küsib, vali **"Continue with GitHub"** ja vajuta rohelist nuppu "Authorize".
        4.  **Hakka kirjutama:** Nüüd näed oma ekraanil sama koodi, mida paariline. Sinu kursor on teist värvi – see tähendab, et oled sees!

        ---

        #### ⚠️ Reeglid külalisele (Et töö sujuks)

        * **Ära näpi "Source Control" nuppe:** Sina ei pea midagi salvestama, *commit*-ima ega *push*-ima. Juhataja teeb seda ise.
        * **Ole kooskõlas:** Kirjutage koodi nii, et te ei hakka samal ajal ühte ja sama rida muutma (see teeb koodi segaseks).
        * **Kui tekib probleem:** Kui koodi kirjutamine ei tööta või pilt hangub, siis lihtsalt sulge brauseriaknad ja küsi paariliselt uus kutse.



## 🛠 Kuidas tööd teha?

Siin on sinu töötsükkel, mida peaksid järgima iga kord, kui teed muudatusi. See hoiab sinu töö korras ja kindlustab, et su kood on alati varundatud.


1. **Muuda koodi** – tee oma muudatused `main.py` failis ja või loo faile juurde.
2. **Salvesta kõik:** Veendu, et kõik failid on salvestatud (`CTRL + S`).
3. **Käivita:** Kirjuta terminalis `python main.py` ja vaata tulemust brauseri aknas.
4. **Salvesta pilve (GitHubi):** Kui töö on tehtud:
    * Vajuta vasakul menüüs **Source Control** (kolme punktiga ikoon).
    * Kirjuta sõnum (nt "Lisasin hüppamise").
    * Vajuta **Commit** ja siis **Sync Changes**.
    * *See on kriitiline samm – kui sa seda ei tee, lähevad muudatused kaotsi!*

> ⚠️ **Tähelepanu:** Kui sa ei tee `Commit & Push`/ *Sync Changes*, lähevad su muudatused kaotsi!


## 🏁 Töö esitamine

1. Veendu, et viimane `Sync Changes` on tehtud (Source Controlis ei tohi olla ootel muudatusi).
2. **Esitamine:** Ava GitHubis oma repo ja kopeeri link brauseri aadressirealt.
3. **Teavita:** Saada see link õpetajale (nt meiliga).
4. **Sulgemine:** Nüüd võid brauseriaknad julgelt kinni panna.


---



## 🧯 Probleemide lahendamine

Kui tekib muresid, vaata esmalt siia tabelisse – enamik probleeme on kiiresti lahendatavad:

| Probleem | Lahendus |
| :--- | :--- |
| **Ei näe mängu** | Kontrolli, kas sul on lahti `Ports` → `6080` (Open in Browser). |
| **Pushimine ebaõnnestub** | Kirjuta terminali `rm .git/hooks/pre-push`. |
| **Ports sakki ei ole** | Vali menüüst `View` → `Terminal`, see toob pordi uuesti nähtavale. |
| **Error terminalis** | Kopeeri terminalis olev punane veateade ja saada see chatGPT'sse/õpetajale. |
| **Mäng jooksis kinni** | Vajuta VS Code'i terminalis `CTRL + C`, et protsess lõpetada ja käivita uuesti. |

---

## 🎮 Mis edasi?

Kui mäng töötab, proovi midagi uut juurde ehitada:

* 📏 **Akna seaded:** Muuda akna suurust või tausta värvi.
* 🟦 **Objektid:** Lisa mängija (ruut) ja pane see nooleklahvidega liikuma.
* 🚧 **Takistused:** Lisa mängu takistusi, mida vältida.
* 🏆 **Skoor:** Lisa loogika, mis arvestab kogutud punkte.

🎉 **Palju edu mängu arendamisel!**