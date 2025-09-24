# Coding Convention Wiki

Velkommen til VS Automatic A/S coding convention. Her finder du retningslinjer og eksempler for god kodepraksis.

<h1 align="center">🧾 De Ti Bud for Kodekonventioner</h1>

<h2 align="center"> 1️⃣ Du skal navngive din kode med klarhed og konsistens </h2> 
Brug `PascalCase` til klasser og metoder, `camelCase` til variabler og parametre, og `snake_case` til SQL-tabeller og kolonner.

---

<h2 align="center"> 2️⃣ Du skal kun kommentere, når det er nødvendigt  </h2>
Skriv kommentarer der øger forståelsen. Brug XML-docs i C#, JSDoc i JS/TS og blokkommentarer i CSS.

---

<h2 align="center">3️⃣ Du skal strukturere dit projekt med formål  </h2>
Organisér mapper som `src/`, `tests/`, `docs/`, `public/` og `migrations/`. Hold din `.gitignore` opdateret og relevant.

---

<h2 align="center">4️⃣ Du skal committe med mening  </h2>
Brug tydelige commit-beskeder:  
`feat:`, `fix:`, `refactor:`, `docs:` – og følg en branching-strategi der fremmer klarhed og kontrol.

---

<h2 align="center">5️⃣ Du må ikke afsløre credentials  </h2>
Gem adgangskoder og API-nøgler i Bitwarden. Commiter aldrig hemmeligheder til dit repository.

---

<h2 align="center">6️⃣ Du skal lint’e og formatere din kode  </h2>
Brug ESLint, Prettier, Stylelint, SQLFluff og `.editorconfig`. Automatisér formatering før commits.

---

<h2 align="center">7️⃣ Du skal teste din kode grundigt  </h2>
Skriv unit- og integrationstests. Sørg for at al kode består CI/CD pipelines før den merges.

---

<h2 align="center">8️⃣ Du skal håndtere fejl med ynde  </h2>
Fang exceptions, log dem meningsfuldt, og undgå tomme `catch`-blokke.

---

<h2 align="center">9️⃣ Du skal dokumentere og onboarde med omhu  </h2>
Vedligehold en klar `README.md`, onboarding-guide og intern wiki. Hjælp nye udviklere godt i gang.

---

<h2 align="center"> 🔟 Du skal undgå synden af dårlig kode  </h2>
Undgå magiske tal, duplikeret logik og “God Classes”. Refaktorer ofte og review med venlighed.

## Indhold

- [01 - Kodeformat og navngivning](01‐Kodeformat‐og‐navngivning)
- [02 - Github og projektstruktur](02-Github-og-projektstruktur)
- [03 - Credentials og Bitwarden](03-Credentials-og-Bitwarden.)
- [04 - Linters og formattering](04-Linters-og-formattering)
- [05 - Testing og CI/CD](05-Testing-og-CI/CD)
- [06 - Fejlhåndtering og logging](06-Fejlhåndtering-og-logging)
- [07 - Dependency Injection og arkitektur](07-Dependency-Injection-og-arkitektur)
- [08 - Sikkerhed og best practices](08-Sikkerhed-og-best-practices)
- [09 - Performance og async](09-Performance-og-async)
- [10 - Dokumentation og onboarding](10-Dokumentation-og-onboarding)
- [11 - Code review og feedback](11-Codereview-og-feedback)
- [12 - Versionsstyring og releases](12-Versionsstyring-og-releases)
- [13 - Frontend konventioner](13-Frontend-konventioner)
- [14 - Backend konventioner](14-Backend-konventioner)
- [15 - Anti-patterns](15-Anti-patterns)
