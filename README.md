<p align="center"><img src="assets/banner.svg" alt="VEDA — Vedic astrology — Kundli, Dasha, Panchang & AI guidance" width="100%"/></p>
<p align="center"><img src="https://img.shields.io/badge/status-launching_soon_on_Google_Play-38bdf8?style=flat-square" alt="status"/> <img src="https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android"/> <img src="https://img.shields.io/badge/source-private-555?style=flat-square&logo=github" alt="source private"/> <img src="https://img.shields.io/badge/by-AJAY_LABs-111?style=flat-square" alt="AJAY LABs"/></p>
---

## ✨ Overview

VEDA is an Android-first Vedic astrology app. It generates a full **Kundli** (birth chart with D1/D9 and divisional charts), Navagraha and **Vimshottari Dasha** timelines, a daily **Panchang**, Kundli matching (Guna Milan), and **Ask Veda** — an AI chat that explains your chart in plain language. Available in **24 Indian languages**. The app is complete and **launching soon on Google Play**.

## 🚀 Features

<table>
<tr>
<td width="50%" valign="top"><h3>🪐 Kundli</h3>D1 / D9 and divisional charts, North-Indian chart rendering</td>
<td width="50%" valign="top"><h3>⏳ Vimshottari Dasha</h3>Current phase and life timeline</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>🌙 Daily Panchang</h3>Tithi, nakshatra and daily insights</td>
<td width="50%" valign="top"><h3>💑 Kundli matching</h3>Guna Milan compatibility</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>🤖 Ask Veda</h3>AI chat grounded in your birth chart</td>
<td width="50%" valign="top"><h3>🔮 Predictions</h3>Love, career, marriage and money insights</td>
</tr>
<tr>
<td width="50%" valign="top"><h3>🎵 Devotional audio</h3>Built-in player for aartis and mantras</td>
<td width="50%" valign="top"><h3>🌐 24 languages</h3>Indian-language translation across the app</td>
</tr>
</table>

## 📱 UI designs

<p align="center">
  <img src="assets/screens/01.jpg" width="200" alt="VEDA screenshot 1"/>
  <img src="assets/screens/02.jpg" width="200" alt="VEDA screenshot 2"/>
  <img src="assets/screens/03.jpg" width="200" alt="VEDA screenshot 3"/>
  <br/>
  <img src="assets/screens/04.jpg" width="200" alt="VEDA screenshot 4"/>
  <img src="assets/screens/05.jpg" width="200" alt="VEDA screenshot 5"/>
  <img src="assets/screens/06.jpg" width="200" alt="VEDA screenshot 6"/>
</p>

## 🧱 Tech stack

<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Riverpod-0553B1?style=for-the-badge" alt="Riverpod"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase"/>
  <img src="https://img.shields.io/badge/Deno-000000?style=for-the-badge&logo=deno&logoColor=white" alt="Deno"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare Workers"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
</p>

## 🏗️ Architecture

<p align="center"><img src="assets/architecture.svg" alt="VEDA architecture diagram" width="100%"/></p>

## 🔍 Engineering highlights

- **276 automated tests** passing; ~1 test line for every 3 lines of app code (~26k lines, feature-first architecture)
- Edge functions fully verify Firebase JWTs (signature, issuer, audience, expiry) and stream-cap request sizes
- All secrets server-side; owner-only Firestore rules with strict schema validation
- **Cost controls**: daily AI quota with refund on failure, per-account caps on paid astrology calls, Postgres cache with atomic leases
- Translation into 24 Indian languages through a Cloudflare Worker running IndicTrans2

## 🔒 About this repository

This is a **product showcase**. The source code, credentials and signing keys are private. Happy to walk through the architecture and code in an interview — reach out below.

---

<p align="center">
  Designed & built by <a href="https://github.com/theajay17"><b>Ajay Kumar Saw</b></a> · AJAY LABs<br/><br/>
  <a href="https://www.linkedin.com/in/ajay-kumar-saw-775aa832a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sawajay303@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://play.google.com/store/apps/dev?id=4822433550844528613"><img src="https://img.shields.io/badge/All_apps-Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play"/></a>
</p>
