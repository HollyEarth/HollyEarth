<div align="center">

# HOLLYEARTH

### VIENA SISTĒMA. DAUDZAS PASAULES.

**Pilsēta · Politika · Sports · Sociālā joma · Izmeklēšana · Analītika · Pieredze**

Reālas vietas, publiski ieraksti, avoti, pierādījumi un atklāti jautājumi — kā viena sistēma. Sākam ar Rīgu.

`v0.1.0` · tikai dokumentācija un mediji · nav atvērtā koda projekts

[English](../README.md) · [Русский](README_RU.md) · **Latviešu**

</div>

![HollyEarth sākuma ekrāns](../media/screenshots/01-start.png)

<sub>Īsts v0.1.0 ekrānuzņēmums. Sākuma ekrāns: piecas jomas, katrai norādīts gatavības līmenis un datu izcelsme.</sub>

## Kas ir HollyEarth

HollyEarth ir platforma telpiskai, pilsētvides un izmeklēšanas analītikai, kas veidota darbam ar mākslīgo intelektu. Tā apvieno pilsētu, tās iestādes un organizācijas, politiskos lēmumus, publisko naudu, sociālos pakalpojumus, sportu, dokumentus, avotus un pierādījumus — un ļauj tos pētīt kartē, kā grafu, kā izmeklēšanu vai kā stāstu.

Virziens ir viena ķēde:

**Realitāte → Pierādījumi → Analītika → Pieredze → Rīcība**

„Rīcība” ir **nākotne**: versijā v0.1.0 sistēma neko neieraksta atpakaļ pasaulē.

> **Vīzija un šodiena ir nošķirtas.**
> Mērķis ir viens savienots pilsētas modelis: viena vieta, viena organizācija, viens lēmums — no visām pusēm.
> **Šodien HollyEarth ir viens produkts pār vairākiem savienotiem datu modeļiem, nevis vienots realitātes grafs.** Politikas un sporta dati atrodas vienā kanoniskajā grafā, bet vēl nav savstarpēji saistīti; sociālo pakalpojumu reģistram ir savs modelis; katrai izmeklēšanai ir savs pierādījumu grafs; Rīgas digitālais dvīnis rāda vairākus modeļus vienā kartē. Saites starp tiem ir īstas, bet daļējas.

## HollyEarth pasaules

| Pasaule | Kas tā ir | Statuss |
|---|---|---|
| **Pilsēta — Riga Twin** | Rīga 3D: apkaimes, domes lēmumi, sports, sociālo pakalpojumu ēkas | `WORKING` |
| **Politika** | Rīgas dome: sēdes, lēmumi, deputāti, partijas, vēlēšanas, budžets | `BETA` |
| **Sports — HollySport** | Latvijas klubi, sportisti, pasākumi un norises vietas no federācijām un protokoliem | `WORKING`, spēles slānis `DEMO` |
| **Social Intelligence** | Rīgas reģistrētie sociālie pakalpojumi interaktīvā kartē | `SHOWCASE_READY` |
| **Izmeklēšana** | Lietas: apgalvojumi, avoti, citāti, nauda pa veidiem, atklāti jautājumi | `WORKING` |
| **Analītika** | Deterministiska analīze, Holly, avotu uzraudzība, valodas modelis — pēc izvēles | `BETA` |
| **Pieredze** | Stāsts trīs valodās, pases, dosjē, ieeja Holly Eye | `WORKING` |

Detalizēta statusu matrica (angliski): [FEATURE_STATUS.md](FEATURE_STATUS.md).

## Riga Twin

> 3D pilsētas ekrānuzņēmumi tiks pievienoti, kad būs apstiprināti Rīgas 3D modeļa izmantošanas noteikumi.

Rīga 3D: 58 apkaimes no atvērtajiem datiem, 428 domes lēmumi ar adresi, 14 sporta teritorijas, 177 sociālo pakalpojumu ēkas, apkaimju ziņas, domes panelis un pārejas uz pārējām pasaulēm.
**Vēl nav:** kopējas telpiskās identitātes (sports un sociālā joma atver savas kartes), lietu kartē un strādājoša režīma „jautā pilsētai”. „Wellbeing” vērtējumi ir `DEMO`, nevis mērījumi.

## Politika

![Partijas un vara](../media/screenshots/17-politics-parties-and-power.png)

175 sēdes, 456 lēmumi, 113 deputāti, 7 partijas, 2025. gada vēlēšanu oficiālie rezultāti (60 vietas). **Political Holly OS** — 12 moduļi: daļa strādā ar reāliem datiem (Network, Deputies, Parties & Power), daļa ir beta versijā (Political OS, Live Sessions, Decisions, City Budget, Evidence Ledger), AI Analyzer ir prototips, District Impact un Smart City Lenses ir `DEMO`, Integral City ir pētījums. **Political Workspace** ir iekšējs pētniecības rīks ar 8 skatiem, `PROTOTYPE`.
Modulis City Budget izmanto atsevišķu atvērto datu kopu par pašvaldības izdevumiem; kā tās ieraksti attiecas uz konkrētiem maksājumiem, vēl tiek noskaidrots.

## HollySport

<table>
<tr>
<td width="50%"><img src="../media/screenshots/09-event-passport.png" alt="Pasākuma pase"><br><sub>Pasākuma pase pēc oficiālajiem protokoliem: „norises vieta nav reģistrēta” pateikts tieši.</sub></td>
<td width="50%"><img src="../media/screenshots/08-club-passport.png" alt="Kluba pase"><br><sub>Kluba pase: sports, vieta, avots un ieeja kluba lietā.</sub></td>
</tr>
</table>

18 143 sportisti, 227 pasākumi, 1 326 cīņas, 297 klubi un federācijas, 133 norises vietas. Darbojas Sport City, arhīvs, klubu, sportistu, pasākumu un norises vietu pases, karte, grafs; reitings aprēķināts no arhīva cīņām un skaidri apzīmēts „nav federācijas reitings”. Netiek glabāti rezultāti nevienam, kurš sacensību dienā varēja būt jaunāks par 18 gadiem.
`DEMO` — sezona, misijas, XP, prognozes. `PROTOTYPE` — Event OS (pasākuma plāns glabājas tikai pārlūkā, tas nav pasākumu reģistrācijas pakalpojums), Creator, partnerības. `FUTURE` — tirgus, maks, līgas, žetoni, biļetes.

## Social Intelligence

<table>
<tr>
<td width="50%"><img src="../media/screenshots/10-social-stage.png" alt="Social Intelligence"><br><sub>Rīgas sociālā sistēma pēc oficiālā reģistra.</sub></td>
<td width="50%"><img src="../media/screenshots/11-social-dossier.png" alt="Pakalpojuma dosjē"><br><sub>Pakalpojuma dosjē: „kas nav zināms”.</sub></td>
</tr>
</table>

Labklājības ministrijas Sociālo pakalpojumu sniedzēju reģistrs (dati uz 14.09.2026.): **256 pakalpojumi · 106 sniedzēji · 177 ēkas · 28 pakalpojumi dzīvesvietā**. Katalogs, karte, filtri, pakalpojuma un organizācijas dosjē, deleģēšanas līgumi, nauda, plānošana („nav fakts”).
**Reģistrēts ≠ sniegts.** Cik cilvēku pakalpojumu faktiski saņēma, cik faktiski izmaksāts un kāda ir kvalitāte — nav zināms nevienam no 256 pakalpojumiem, un sistēma to pasaka tieši. Sniedzēji vēl nav saistīti ar galveno grafu.

## Izmeklēšana un pierādījumi

<table>
<tr>
<td width="50%"><img src="../media/screenshots/03-case-overview.png" alt="Lieta"><br><sub>Domes lēmums kā lieta: kas ir noskaidrots, kas nav zināms, nauda pa veidiem.</sub></td>
<td width="50%"><img src="../media/screenshots/04-evidence.png" alt="Summas izcelsme"><br><sub>No kurienes šī summa: avots, citāts un summas veids — plāns, nevis izmaksa.</sub></td>
</tr>
</table>

9 lietas (7 par sporta klubiem, 2 par domes lēmumiem). Apgalvojumi, avoti, precīzi citāti, lietas grafs, nauda pa veidiem, atklāti jautājumi, izmeklēšanas gaita, analīze, stāsts, uzraudzība, Holly.
**Apgalvojums ≠ pārbaudīts fakts.** Visiem 111 apgalvojumiem ir statuss „apgalvots”; katram ir citāts un avots; 106 tieši apstiprina citāts, 4 — daļēji, 1 — neapstiprina. **Neviens nav pārbaudīts cilvēka.** „Apstiprināts” saskarnē nozīmē „tieši apstiprināts ar citātu”.
**Nauda pa veidiem** nekad netiek saskaitīta kopā. Lietās un sociālajā jomā nav ierakstu par faktiskiem maksājumiem; ieraksta trūkums nenozīmē naudas trūkumu.

## Holly AI, stāsts un uzraudzība

- **Holly** — deterministiski palīgi, asistents lietas ietvaros, valodas modelis — tikai pēc izvēles. Modelis nevar rakstīt kanoniskajā grafā un piešķirt statusu „pārbaudīts”. Globāla Holly asistenta un autonomu aģentu versijā v0.1.0 nav.
- **Stāsts** — lietas stāsts krievu, latviešu un angļu valodā, salikts no lietas ierakstiem. Ne katra nodaļa vēl ir piesaistīta konkrētiem apgalvojumiem.
- **Uzraudzība** — 18 novērojumi oficiāliem avotiem, 26 palaidieni. Pārbaudes tiek palaistas manuāli; automātiska grafika nav.

## Holly Eye

Ieeja „Pasaule” atver Holly Eye — planētas 3D skatu. Tā ir **trešās puses lietotne** God's Eye View (autors — Bilawal Sidhu), integrēta HollyEarth, nevis **HollyEarth pašu tehnoloģija**.

## Pētījumi

HEIO (HollyEarth Integral Ontology, v0.1) un HEIM (HollyEarth Integrative Metatheory & Context System, v0.2) ir iekšēji pētniecības dokumenti — **konceptuāla arhitektūra, nevis ieviestas funkcijas**. AQAL, Spiral Dynamics un Integral City ir pētniecības ietekmes; tās nekad netiek izmantotas cilvēku, partiju vai apkaimju vērtēšanai. Sīkāk: [research.md](research.md).

## Kas tālāk

| Ir šodien | Izstrādē | Pētījumi | Nākotne |
|---|---|---|---|
| Riga Twin · lietas un pierādījumi · HollySport · Social Intelligence · politikas dati · manuāla uzraudzība · RU / LV / EN | Kopēja identitāte starp jomām · sociālā joma galvenajā grafā · naudas semantika (plāns → līgums → piešķirts → izmaksāts) · uzraudzības grafiks · pārbaude, ko veic cilvēks · izmēģinājuma mitināšana | HEIO · HEIM · Integral / AQAL · Spiral Dynamics (tikai konteksts) · Integral City | Pārvaldīta rīcība un pārsūdzības · HollyWorlds · MetaSport ekonomika · publiska mitināšana · citas pilsētas |

## Autori

**HollyEarth** veido **Stanislav Petrovsky** un **Irina Petrovskaya**, Rīga, Latvija.

© 2026 Lab Da Riga. Visas tiesības aizsargātas. Repozitorijā ir tikai dokumentācija un mediji, tas nav atvērtā koda projekts — sk. [LICENSE.md](../LICENSE.md).
