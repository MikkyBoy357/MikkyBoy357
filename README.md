<h1 align="center">Hi there, I'm Michael 👋🏾</h1>

<p align="center">
  <b>Senior Mobile &amp; Web Engineer</b><br/>
  Flutter · React Native · React · Next.js · TypeScript
</p>

<p align="center">
  📍 Cotonou, Benin (UTC+1) &nbsp;·&nbsp; 🌍 Remote, overlapping EMEA &amp; US hours &nbsp;·&nbsp; 🗣️ English &amp; French
</p>

<p align="center">
  <a href="https://wa.me/2290199249702?text=Hello%20Michael">
    <img src="https://img.shields.io/badge/whatsapp-%2325D366.svg?&style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>&nbsp;
  <a href="mailto:michaelolusegun357@gmail.com">
    <img src="https://img.shields.io/badge/email%20me-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>&nbsp;
  <a href="https://medium.com/@MikkyBoy357">
    <img src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" alt="Medium" />
  </a>
</p>

---

## 🚀 Products I've shipped

I build and ship complete products — mobile, web, backend, and the payment rails underneath.

### 🎟️ [Fidela](https://fidela.app) — digital loyalty cards for small businesses

A multi-tenant B2B SaaS I designed and built solo: a business dashboard, one-tap stamping, and public customer card pages that need no login. Every tenant is isolated with Postgres row-level security, and the stamping rules live in database triggers so the app layer can't over-stamp a card or miss a completion. Freemium plans, mobile-money billing by webhook, fully bilingual **English/French**.

`Next.js` `TypeScript` `Tailwind` `Supabase` `Vercel`

### 🎮 [BlockPlay](https://blockplay.live) — play games, climb leaderboards, win cash

A consumer gaming platform with **17 browser games written directly against the Canvas 2D API** — no game engine — plus tournaments, live leaderboards, and cash prize payouts.

The interesting part is trust. Every score is validated server-side: sessions are HMAC-SHA256 signed at game start, and the end-of-game route rejects tampered checksums, expired sessions, and impossible scores, so standings and payouts rest on results the backend can verify rather than numbers a modified client reports. Standings stream over Postgres change events, and payouts route by player country across **USD, XOF, and NGN**.

`Next.js` `TypeScript` `Supabase` `Stripe Connect` `Canvas 2D` `545 unit tests`

---

## 🧰 What I work with

<table>
<tr>
<td valign="top" width="50%">

**📱 Mobile**

<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" /> <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" /> <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" /> <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" alt="Swift" /> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" /> <img src="https://img.shields.io/badge/Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Compose" />

</td>
<td valign="top" width="50%">

**🌐 Web**

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" /> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind" />

</td>
</tr>
<tr>
<td valign="top" width="50%">

**⚙️ Backend & data**

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" /> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" /> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" /> <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />

</td>
<td valign="top" width="50%">

**💳 Payments & platform**

<img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe" /> <img src="https://img.shields.io/badge/Flutterwave-F5A623?style=for-the-badge&logoColor=white" alt="Flutterwave" /> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" /> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />

</td>
</tr>
</table>

---

## 🛠️ A bit more about the work

- **Payments at the edges of the phone.** NFC tap-to-pay and ticketing running in live venues, and voice-assistant purchasing through **SiriKit** and **Google Assistant** — including recurring intents, so a standing instruction like "buy my usual coffee every weekday morning" runs on its own.
- **Cross-platform, properly.** One Flutter codebase shipped to iOS, Android, and web at feature parity, on Clean Architecture with a Melos-managed monorepo.
- **Built for people who don't use software.** As founding engineer on a B2B FMCG platform in the Middle East, my users were shop owners and sales reps, many of them older and non-technical. That set the design bar. The business was later acquired.
- **Remote since 2021** across UK, EU, and MENA teams.

---

## 📂 Selected public repos

Fidela and BlockPlay are private, but here's a sample of what's open:

| Repo | What it is | Stack |
| --- | --- | --- |
| [cats_backend_dart](https://github.com/MikkyBoy357/cats_backend_dart) | REST API with real-time WebSocket support | Dart · DartFrog · MongoDB |
| [ticket_app](https://github.com/MikkyBoy357/ticket_app) | Event ticketing app | Flutter · Dart |
| [task-manager](https://github.com/MikkyBoy357/task-manager) | Todo app built on BLoC, Hive and go_router | Flutter · Dart |
| [teeha_fabrics](https://github.com/MikkyBoy357/teeha_fabrics) | Landing page and online store for a fabrics brand | Next.js · TypeScript |
| [voyage-landing-page](https://github.com/MikkyBoy357/voyage-landing-page) | Tourism product landing page | Next.js · TypeScript |

---

> [!NOTE]
> **Open to senior remote roles — mobile, web, or both.**
> The fastest way to reach me is [WhatsApp](https://wa.me/2290199249702?text=Hello%20Michael); [email](mailto:michaelolusegun357@gmail.com) works too.
