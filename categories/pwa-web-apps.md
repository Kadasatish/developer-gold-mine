# PWA & Web App Starters

A curated catalogue of 30 real GitHub repositories for building installable web apps, offline-first experiences, PWA tooling and framework integrations.

**Catalogue checked:** 2026-10-05  
**Important:** Not every entry is a complete starter template. Some are build tools, service-worker libraries, framework adapters, examples or reference applications. Read the upstream README before choosing one.

## Quick recommendations

| Need | Start by reviewing |
|---|---|
| General PWA starter | [PWABuilder PWA Starter](https://github.com/pwa-builder/pwa-starter) |
| React + Vite + TypeScript | [ADORSYS React-PWA](https://github.com/ADORSYS-GIS/react-pwa) |
| React local-first / offline | [PhuCG PWA Starter Kit](https://github.com/PhuCG/pwa-starter-kit) |
| Create a Vite PWA for different frameworks | [create-pwa](https://github.com/vite-pwa/create-pwa) |
| Vite PWA integration | [vite-plugin-pwa](https://github.com/vite-pwa/vite-plugin-pwa) |
| Next.js PWA | [Serwist](https://github.com/serwist/serwist) or [next-pwa](https://github.com/shadowwalker/next-pwa) |
| Offline caching | [Workbox](https://github.com/GoogleChrome/workbox) |
| PWA assets / icons | [PWA Asset Generator](https://github.com/onderceylan/pwa-asset-generator) |

## A. Ready-made starters and boilerplates

### 1. PWABuilder PWA Starter
- Repository: https://github.com/pwa-builder/pwa-starter
- Technology: Lit / web components, TypeScript, Vite, Workbox.
- Use case: Production-oriented baseline for installable PWAs; includes service-worker setup and app-store packaging path.
- License: MIT (upstream `LICENSE.txt`).
- Maintenance: Not archived in GitHub metadata checked on 2026-10-05; recent repository activity was visible during review. Check current issues/releases before adopting.

### 2. PWABuilder
- Repository: https://github.com/pwa-builder/pwabuilder
- Technology: TypeScript/JavaScript and .NET components across the PWABuilder tool family.
- Use case: PWA Builder website, tooling and packaging PWAs for supported app stores/platforms. This is a tool suite, not a simple app starter.
- License: MIT (upstream `LICENSE.txt`).
- Maintenance: Not archived in GitHub metadata checked on 2026-10-05; inspect individual subprojects and releases.

### 3. ADORSYS React-PWA
- Repository: https://github.com/ADORSYS-GIS/react-pwa
- Technology: React 18, Vite 5, TypeScript, MUI 5, React Router 6, Recoil, Vitest and Playwright.
- Use case: Structured React PWA starter with routing, state management, theming, notifications, tests and developer tooling.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; stack versions are older than current React/Vite releases. Treat as a reference or upgrade deliberately before client production use.

### 4. PhuCG PWA Starter Kit
- Repository: https://github.com/PhuCG/pwa-starter-kit
- Technology: React 18, Vite 6, TypeScript, vite-plugin-pwa, Dexie / IndexedDB, Vitest.
- Use case: Local-first, offline-capable PWA where user data can stay on-device without requiring a backend.
- License: No root `LICENSE` file was found at the checked path. Treat reuse rights as unconfirmed; ask the author or inspect all repository terms before copying.
- Maintenance: Not archived in GitHub metadata checked on 2026-10-05; recent activity was visible during review. Confirm the latest commit and dependency status.

### 5. create-pwa-boilerplate
- Repository: https://github.com/fadilnatakusumah/create-pwa-boilerplate
- Technology: Node.js CLI; generates React, Vue 3 or Svelte projects using Vite and TypeScript; optional Tailwind CSS; vite-plugin-pwa.
- Use case: Scaffold a new PWA with a framework choice and sample browser capabilities.
- License: No root `LICENSE` or `LICENSE.md` was found at the checked paths. Reuse rights are unconfirmed; do not assume an open-source license.
- Maintenance: Not archived in GitHub metadata checked on 2026-10-05; recent activity was visible during review. Check releases and generated output before using.

### 6. Minimal Vite PWA Template
- Repository: https://github.com/eugenevve/pwa-template
- Technology: Vite, TypeScript, native PWA manifest and service-worker setup.
- Use case: Minimal PWA shell with installability, offline fallback, icons and light/dark theme assets.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; repository showed recent activity during review. Confirm compatibility with the current Vite version.

### 7. Svelte PWA
- Repository: https://github.com/tretapey/svelte-pwa
- Technology: Svelte, Rollup, JavaScript, service worker and web app manifest.
- Use case: Older Svelte PWA starter demonstrating installability and offline fallback.
- License: No root `LICENSE` or `LICENSE.md` was found at the checked paths. Reuse rights are unconfirmed.
- Maintenance: Legacy starter; not archived in GitHub metadata, but review commit history and modernize dependencies before production use.

### 8. Vue PWA Template (Vue CLI)
- Repository: https://github.com/vuejs-templates/pwa
- Technology: Vue.js / Vue CLI-era webpack tooling and service-worker setup.
- Use case: Historical Vue PWA scaffold; useful for understanding older Vue PWA structure.
- License: No root `LICENSE` file was found at the checked path. Reuse rights are unconfirmed.
- Maintenance: Legacy Vue CLI-era template. Prefer a current Vite + Vue + vite-plugin-pwa setup for new client projects.

### 9. React-PWA by Suren Atoyan
- Repository: https://github.com/suren-atoyan/react-pwa
- Technology: React and JavaScript ecosystem.
- Use case: React PWA starter/reference project.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived in GitHub metadata; treat as an older starter and inspect dependency versions, recent commits and open issues before reuse.

### 10. Ionic PWA Toolkit
- Repository: https://github.com/ionic-team/ionic-pwa-toolkit
- Technology: Stencil, TypeScript and web components.
- Use case: Historical Ionic/Stencil PWA starter and examples.
- License: MIT (upstream `LICENSE`).
- Maintenance: **Archived** in GitHub metadata checked on 2026-10-05. Reference only; do not choose as the foundation for a new production app.

### 11. Polymer PWA Starter Kit
- Repository: https://github.com/Polymer/pwa-starter-kit
- Technology: Polymer 3, LitElement-era web components and Polymer tooling.
- Use case: Historical app-shell PWA architecture and web-component patterns.
- License: No root `LICENSE` or `LICENSE.md` was found at the checked paths. Reuse rights are unconfirmed.
- Maintenance: **Archived** in GitHub metadata checked on 2026-10-05. Historical reference only.

## B. PWA framework integrations and service-worker foundations

### 12. vite-plugin-pwa
- Repository: https://github.com/vite-pwa/vite-plugin-pwa
- Technology: TypeScript, Vite, Workbox and service workers.
- Use case: Add manifest, service worker, precaching and runtime caching to Vite apps (React, Vue, Svelte and other Vite frameworks).
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; active project with current documentation. Check its compatibility table before upgrading Vite.

### 13. create-pwa (Vite PWA)
- Repository: https://github.com/vite-pwa/create-pwa
- Technology: TypeScript, Vite and framework-specific starter templates.
- Use case: Scaffold PWA-ready projects for supported frameworks instead of configuring every part manually.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; maintained in the Vite PWA project family. Review available templates and release notes.

### 14. Workbox
- Repository: https://github.com/GoogleChrome/workbox
- Technology: JavaScript / TypeScript service-worker libraries and build tooling.
- Use case: Offline caching strategies, precaching, runtime caching, background sync and service-worker workflows.
- License: MIT (upstream root license text).
- Maintenance: Not archived; established GoogleChrome project. Follow current Workbox documentation and version guidance.

### 15. Serwist
- Repository: https://github.com/serwist/serwist
- Technology: TypeScript, service workers, Workbox-derived tooling and framework integrations.
- Use case: Modern service-worker tooling, including Next.js-oriented PWA implementations.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; inspect release compatibility for your Next.js and framework versions.

### 16. next-pwa
- Repository: https://github.com/shadowwalker/next-pwa
- Technology: Next.js, React, JavaScript and Workbox.
- Use case: Add PWA/service-worker capabilities to Next.js applications.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived in GitHub metadata checked on 2026-10-05; verify compatibility with your exact Next.js version. Compare with Serwist before selecting it for a new app.

### 17. Astro PWA Integration
- Repository: https://github.com/vite-pwa/astro
- Technology: Astro, Vite, TypeScript and vite-plugin-pwa.
- Use case: Add PWA manifest and service-worker support to Astro sites.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; check compatibility with the installed Astro and Vite versions.

### 18. Nuxt PWA Integration
- Repository: https://github.com/vite-pwa/nuxt
- Technology: Nuxt, Vite and vite-plugin-pwa.
- Use case: PWA support for Nuxt applications.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; verify Nuxt module compatibility and current setup documentation.

### 19. SvelteKit PWA Integration
- Repository: https://github.com/vite-pwa/sveltekit
- Technology: SvelteKit, Vite and vite-plugin-pwa.
- Use case: Add PWA capabilities to SvelteKit projects.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; verify compatibility with your SvelteKit/Vite versions.

### 20. VitePress PWA Integration
- Repository: https://github.com/vite-pwa/vitepress
- Technology: VitePress, Vite and vite-plugin-pwa.
- Use case: Make VitePress documentation sites installable and provide offline support.
- License: MIT (upstream `LICENSE`).
- Maintenance: Not archived; verify current VitePress compatibility.

## C. PWA assets, navigation and compatibility tools

### 21. PWA Asset Generator
- Repository: https://github.com/onderceylan/pwa-asset-generator
- Technology: Node.js / JavaScript and image-processing tooling.
- Use case: Generate PWA icons, splash-screen assets and related platform images from source artwork.
- License: No root `LICENSE` or `LICENSE.md` was found at the checked paths. Reuse rights are unconfirmed.
- Maintenance: Not archived in GitHub metadata; verify current Node.js compatibility and activity before adding it to a build pipeline.

### 22. Quicklink
- Repository: https://github.com/GoogleChromeLabs/quicklink
- Technology: JavaScript, browser APIs, Intersection Observer and requestIdleCallback.
- Use case: Prefetch likely next-page navigation targets to improve perceived navigation speed. It is a performance helper, not a PWA framework.
- License: Apache-2.0 (upstream `LICENSE`).
- Maintenance: Not archived; check recent commits and browser support before production adoption.

### 23. PWABuilder PWA Compat
- Repository: https://github.com/GoogleChromeLabs/pwacompat
- Technology: JavaScript browser compatibility helper.
- Use case: Historical compatibility support for PWA install metadata and browser/platform behavior.
- License: Apache-2.0 (upstream `LICENSE`).
- Maintenance: **Archived** in GitHub metadata checked on 2026-10-05. Historical reference only; prefer current browser capabilities and maintained tooling.

### 24. Google Chrome Samples
- Repository: https://github.com/GoogleChrome/samples
- Technology: HTML, CSS and JavaScript browser API examples.
- Use case: Reference implementations for web platform capabilities that can be useful when building app-like web experiences.
- License: Apache-2.0 (upstream `LICENSE`).
- Maintenance: Not archived; this is a broad samples collection, not a single PWA starter. Check the individual sample's current status.

## D. PWA examples and reference applications

### 25. MDN PWA Examples
- Repository: https://github.com/mdn/pwa-examples
- Technology: HTML, CSS and JavaScript.
- Use case: Small Progressive Web App examples for learning manifests, service workers and PWA behavior.
- License: CC0-1.0 (upstream `LICENSE`).
- Maintenance: Not archived; useful educational reference. Check individual example age and browser compatibility.

### 26. MDN DOM Examples
- Repository: https://github.com/mdn/dom-examples
- Technology: HTML, CSS and JavaScript browser APIs.
- Use case: DOM and web-platform examples that can be reused as learning references inside web apps; not a PWA starter itself.
- License: CC0-1.0 (upstream `LICENSE`).
- Maintenance: Not archived; inspect the specific example before integrating it.

### 27. Your First Progressive Web App
- Repository: https://github.com/googlecodelabs/your-first-pwapp
- Technology: HTML, CSS and JavaScript; historical PWA codelab code.
- Use case: Learn the fundamentals of a basic installable/offline web app.
- License: Apache-2.0 (upstream `LICENSE`).
- Maintenance: **Archived** in GitHub metadata checked on 2026-10-05. Use as a learning reference, not a current production starter.

### 28. Airhorn
- Repository: https://github.com/GoogleChromeLabs/airhorn
- Technology: Web platform APIs, JavaScript, HTML and audio assets.
- Use case: Historical demonstration of app-like PWA behavior and browser capabilities.
- License: Mixed/asset-specific terms: the upstream license file states separate terms for image/audio assets. Review all notices before reusing any asset or code.
- Maintenance: Not archived in GitHub metadata; old demo. Reference only and verify browser behavior before reuse.

### 29. Squoosh
- Repository: https://github.com/GoogleChromeLabs/squoosh
- Technology: TypeScript, web workers and WebAssembly-based image codecs.
- Use case: Full-featured browser image optimization application; useful to study a sophisticated web app architecture, workers and client-side processing.
- License: Apache-2.0 (upstream `LICENSE`).
- Maintenance: Not archived in GitHub metadata; check latest releases, codec support and build instructions before forking.

### 30. Polymer Shop
- Repository: https://github.com/Polymer/shop
- Technology: Polymer and web components; historical app-shell PWA architecture.
- Use case: Reference e-commerce PWA demonstrating product listing, cart and app-shell patterns.
- License: No root `LICENSE` or `LICENSE.md` was found at the checked paths. Reuse rights are unconfirmed.
- Maintenance: Legacy Polymer-era sample. Not archived in GitHub metadata, but do not use as a new production base without a full modernization and license review.

## Selection guide for our client PWA work

For our React + Vite + Firebase projects, start with these:

1. **Base template:** PWABuilder PWA Starter or ADORSYS React-PWA.
2. **PWA integration:** vite-plugin-pwa.
3. **Offline data:** PhuCG PWA Starter Kit as an architecture reference; adapt IndexedDB patterns to the app's data model.
4. **Service-worker caching:** Workbox (usually through vite-plugin-pwa).
5. **Icons and splash assets:** PWA Asset Generator, after confirming its reuse terms.
6. **Framework-specific app:** Use the relevant Vite PWA integration for Astro, Nuxt, SvelteKit or VitePress.

### Android/mobile and production checks

- Test installability and update flow in Android Chrome on a real device.
- Test offline behavior after a fresh install and after an app update.
- Do not cache private API responses or authenticated Firebase data with broad cache rules.
- Verify push-notification support and permissions on each target browser/platform.
- Confirm HTTPS, manifest icons, app name, start URL, display mode and theme colors.
- Check bundle size, Lighthouse, accessibility and slow-network behavior.
- Review upstream issues, latest commit, release history, dependencies and security advisories before using any starter for a client.

## License and maintenance policy for this catalogue

- A GitHub repository being public does not grant permission to copy or sell its code.
- A listed MIT, Apache-2.0 or CC0 license applies only where the upstream license file was inspected. "No root LICENSE found" means reuse permission is **not confirmed**; it does not mean the project is public domain.
- Some projects contain separately licensed assets or dependencies. Review those notices too.
- "Not archived" is not the same as "actively maintained". Check the latest commit date, releases, open issues and dependency health again when selecting a project.
- This catalogue was checked on 2026-10-05; repository ownership, branches, licenses and maintenance status can change.
