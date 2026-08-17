
<h1 align="center">Hi there! 👋 I'm Thomas!</h1>

<p align="center">
  🚀 Full Stack Developer | Mobile Lead | Flutter | AI & FastAPI
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/thomas-franke-32596639/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://wakatime.com/@81ee337c-1e3d-460c-9004-b1ee1d921524">
    <img src="https://wakatime.com/badge/user/81ee337c-1e3d-460c-9004-b1ee1d921524.svg?style=for-the-badge"/>
  </a>
  <a href="https://frankeapps.com">
    <img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=internet-explorer&logoColor=white"/>
  </a>
</p>

---

### About Me

🔹 **Full Stack Developer** with 10+ years of experience, specialized in mobile development  
🔹 **Current Stack:** Flutter + Python (FastAPI), integrating AI solutions with real-time performance  
🔹 **Software Architecture Specialist:** MVC, MVVC, DDD, Clean Architecture, Testing  
🔹 **Mobile Lead at Versotech:** Leading the development of ERP-integrated apps processing $1B+ annually  
🔹 **Creator of House of Clashers** 15M+ downloads, 200k daily users, PHP backend with real-time Clash of Clans stats  
🔹 **AI & Privacy Advocate:** Running LLMs locally with FastAPI for private, edge-based data processing  
🔹 **Thesis (2026, UNISINOS — graded with distinction):** An empirical comparison of Clean Architecture vs. unstructured code in Flutter — [read it here](https://github.com/thomasfranke/flutter-clean-vs-spaghetti)  
🔹 **Flutter Ecosystem Expertise:**  
  - **State Management:** `Riverpod`, `MobX`, `Bloc`  
  - **Architecture & DI:** `AutoRoute`, `Modular`, `GetIt`, `AutoInjector`  
  - **Storage:** `SQFlite`, `Hive`, `SecureStorage`  
  - **Codegen & Modeling:** `Freezed`, `dartz`, `JsonAnnotation`, `Result`, `Result Dart` 
  - **Testing:** `Unit`, `Widget`, `Integration`, `E2E` | `Mocktail`  

---

### Featured Open Source

🔹 [**Flutter Clean Architecture + Riverpod**](https://github.com/thomasfranke/flutter-clean-arch-riverpod)  
  - My reference implementation of Clean Architecture + DDD in Flutter: `domain` (entities and contracts) at the center, `application` use cases around it, `data` and `infrastructure` reached only through explicit interfaces — with Riverpod as the DI mechanism for the whole app, wired next to each implementation instead of in a separate bootstrap layer.
  - **Four levels of tests** — unit, widget, narrow integration and on-device E2E against the live Binance API — reaching **100% line coverage**, with the scope and limits of each level documented rather than assumed.
  - Crypto tracker: live quotes with filtering and pull-to-refresh, candlestick charts, favorites, and persisted preferences (theme, font scale, EN/ES/PT).
  - Documents its own tradeoffs, including where it deliberately deviates from a strict reading of the Dependency Rule — and why.
  - 🔧 **Tech Used:** `Riverpod`, `AutoRoute`, `Dio`, `SharedPreferences`, `Freezed`, `dartz` (`Either`-based failures), `fl_chart`, `Mocktail`

🔹 [**TOM — Team-Oriented Markdown**](https://github.com/thomasfranke/tom) *(pre-alpha, built in public)*  
  - A Git client built for documentation instead of code: **rendered markdown diffs**, branching without ceremony, section blame, assisted conflict resolution. Local-first, MIT, no proprietary format.
  - Architecture-first by design — the package layer graph, the roadmap and every architectural decision record were written and reviewed *before* the first line of implementation.
  - 🔧 **Tech Used:** Dart / Flutter desktop (Windows, macOS, Linux)

🔹 [**Clean Architecture vs. Spaghetti Code in Flutter**](https://github.com/thomasfranke/flutter-clean-vs-spaghetti) — *undergraduate thesis, graded with distinction*  
  - Two Flutter apps with **identical features and identical dependencies**, built with opposite architectures — a controlled experiment where the only variable left is how the code is organized. The clean side is a scope-matched cut of the Riverpod app above.
  - Measured instead of argued: static analysis, import coupling, cyclomatic complexity and testability. The clean side reached **41 test files and 100% line coverage** of the code under test; the spaghetti side has none, and reaches into third-party packages ~3× more often per file.
  - Honest about the cost too: ~3× the files and ~2× the lines of code. Full thesis (PT) and defense slides (EN/PT) included.
  - 🔧 **Tech Used:** Flutter, Provider, AutoRoute, Dio, fl_chart, `dart_code_linter`

🔹 [**TomLog**](https://github.com/thomasfranke/tomlog)  
  - Dart logging library: categorized and color-coded logs, automatic file/class capture, bounded history, JSON export and hooks for monitoring systems.
  - 🔧 **Tech Used:** Dart

---

### Earlier Architecture Demos

🔹 [**Flutter Crypto DDD: v1**](https://github.com/thomasfranke/flutter-ddd)  
  - A simple app with a complete DDD architecture to fetch crypto quotes, demonstrating Clean Architecture and DDD principles using `MobX` and `Modular`.  

🔹 [**Simple FastAPI Crypto DDD**](https://github.com/thomasfranke/fastapi-ddd)  
  - A lightweight API showcasing integration with the Binance API using DDD.  


---

### Tech Stack & Specialties

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/CI/CD-0A192F?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>


🔹 **Mobile:** Flutter (last 5 years), transitioning from Objective-C/Swift and Java/Kotlin  
🔹 **Back-end:** PHP, FastAPI  
🔹 **DevOps:** CI/CD, Bitbucket Pipelines, Codemagic   
🔹 **Testing:** Unit, Integration, E2E   
🔹 **Architecture:** Clean Architecture, DDD, Offline-first   
🔹 **Error Monitoring:** Sentry, Google Crashlytics  

---

### Featured Projects

- **House of Clashers** ([iOS](https://apps.apple.com/us/app/house-of-clashers-clash-guide/id653987498) | [Android](https://play.google.com/store/apps/details?id=com.frankeaplicativos.houseofclashers&hl=pt_BR))
  - 📌 Leading Clash of Clans guide app with **15M+ downloads** and **200k daily users**
  - 🔧 **Tech Used:** Flutter, PHP, SQL, Firebase

- **ERP Mobile Solution at [Versotech](https://versotech.com.br)** *(Private)*
  - 🤓 **Mobile Lead Developer:** Architecting large-scale mobile apps using Flutter
  - 📌 **ERP-integrated:** Flutter applications processing over **$1B annually**
  - 🔧 **Tech Used:** Flutter, Offline-first strategies, DDD, CI/CD, Automated tests (E2E, integration, unit), Error Monitoring

---

### GitHub Stats

<p align="center">
    <a href="https://github.com/thomasfranke">
        <img title="Get streak stats for your profile at git.io/streak-stats" alt="Thomas Franke Streak" src="https://github-readme-streak-stats.herokuapp.com?user=thomasfranke&theme=react&hide_border=true&stroke=0000&background=060A0CD0"/>
    </a>
</p>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=thomasfranke&show_icons=true&theme=react&hide_border=true&bg_color=0D1117)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=thomasfranke&langs_count=8&count_private=true&layout=compact&theme=react&hide_border=true&bg_color=0D1117)
