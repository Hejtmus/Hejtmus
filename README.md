# Hello

My name is Filip Holčík, and I’m a full-stack student web developer. I finished high school as an “IT specialist” at SPŠE Karola Adlera (electrical engineering) in Bratislava, Slovakia. I finished CS minor at [FIT BUT](https://www.fit.vut.cz/.en), Czech Republic. Now I study information security masters programme at [FEEC BUT](https://www.fekt.vut.cz/en), Czech Republic.

## Tech I work with

### Languages & Runtimes
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

### Frameworks & Tools
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Electron.js](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

### BTW, I use

![Fedora](https://img.shields.io/badge/Fedora-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=firefox-browser&logoColor=white)

---

> 💡 **A quick note for readers:**  
> If you're a recruiter pressed for time, feel free to let an LLM extract a swift summary of my technical skills.  
> 
> *However, if you cherish authentic stories of how a kid tinkering with memory hacks grew into an architect of systems — grab your favorite comfort food, pull up a chair, and embark on my journey.*

## How my IT passion started
<sub>*2013*</sub>

Since I was 12 years old, I've been a gamer, but back then, I was gaming on an All-In-One computer with notebook performance. To play games comfortably on that HW, I had to tinker with software, at which point, I started hating Windows. Although I hated Windows, I was using it because I didn’t know there were any alternatives. I was gaming like this until I moved to my father's.

<sub>*2016*</sub>

After I moved to my father's, I couldn’t play games because my AIO stayed at my mother’s house, and the only computer I had was an Acer Aspire ONE. Because I moved, I also changed my school, and there I met my friend Simon ([@simonSlamka](https://github.com/simonSlamka)) from my childhood. With Simon, we were mostly talking about physics. However later on he started trash-talking Windows, so I started as well. Then, I asked him what could be done with it, and he said: 'Use Linux.' My mind was blown away by the fact that there is an alternative to the mighty Windows.

### Mint chapter
<sub>*2016*</sub>

The next day I visited my friend, Simon, to get Linux Mint installed on my Acer Aspire One. Since then, I was busy tweaking my system and learning how it works. I got familiar with the thought that once I could be a programmer. Circa after one year, I started demanding a PC from my father. I wanted a desktop, but I couldn’t find one I could afford with my HW requirements, so I changed my mind and bought a notebook.

### Android & memory hacking
<sub>*2016*</sub>

Around that time, I was also messing with Android. I built my very first Android app using Sketchware, rooted my phone, and started poking around under the hood. Naturally, like any curious kid with root access, I used memory manipulation tools to give myself unlimited currencies in games like *Subway Surfers*, *Shadow Fight 2*, and *Angry Birds Epic* — right up until I got banned in *Need for Speed*. Looking back, that was my very first hands-on encounter with reverse engineering and how software actually manages memory.

### Ubuntu chapter
<sub>*Early – Mid 2017*</sub>

I decided to dual-boot my new laptop: Ubuntu for school and Windows for gaming. I reconfigured my BIOS, installed Ubuntu (16.04 LTS (newly released)) alongside Windows, installed apps I wanted, games, and that was it. After a week, I realized that Windows is bloated with ads and software I didn't want, so I deleted all Windows partitions and extended my Linux partitions.

But when I wanted to play GTA 5, I had to install Windows back. Meanwhile, I finished elementary school and started attending high school (SPŠE Karola Adlera). I started programming in Python 3 in my free time. At the end of the 1st half of the academic year, we got homework - make a responsive website. I decided to code it on Windows, just to give it one last try, and I found out that Windows is a terrible choice for productivity; it just slows me down in my developer journey (BTW, for some reason, my Windows boot time was 45 minutes, while Linux boot time was just 2 minutes). After this experience, I decided to remove Windows from my life.

### Python development
<sub>*Late 2017*</sub>

After I went full-time Linux (December 2017), I decided to make my very first program, a real program, with an installation script and a desktop entry - I made SmartCalc. It was a simple CLI program, just one python script that prompts the user what mathematical operation shall be done, and then redirects to another script that prompts a user value and outputs a computed value.

During the development of this app, I heard somewhere, “Doing installers is difficult” and “GUI is extremely technically difficult.” Because I was a programmer for less than a year, I wanted to prove to myself that I’m good. I decided to pack SmartCalc into a Debian package.

### Making Debian packages
<sub>*Early 2018*</sub>

Now, this was a challenge, with pathetic Debian documentation and one good but deprecated video on YT. I was still adding features into SmartCalc, but I invested a significant amount of time into the DEB package. It was two months (but felt like four) of searching the web, watching videos, guessing how Debian packages work, and reading dpkg, DH, and other manuals. I consider that time investment to have been well made (February 2018) because I successfully packaged my app into the DEB installer. Most importantly, I have developed solid problem-solving skills. For the next two months, I dedicated myself to the optimization of the packaging app. 

### Snap packages
<sub>*Early 2018*</sub>

I was aware of the fact that not every Linux user uses a Debian-based system. This fact motivated me to make a Snap package out of my existing DEB package. This process was a lot simpler; it just required a YAML config file, an existing app package, and snapcraft (a CLI tool). That was it.

### GUI
<sub>*Mid 2018*</sub>

Now I’m half of a good programmer, but I want to be all good (that's like a boolean, there is just a true programmer and a false programmer, nothing in the middle :D). I guess now I have to make a GUI for SmartCalc.

There was one critical choice I had to make: which framework to use. Based on my previous experience with GUI in Python, I will not use TKinter or PYQT. I wanted to use GTK+, but when I tried importing GTK libs into Python, I broke my GTK systemwide (ouch). I could give it another shot, but I really wanted to try out Electron.js because it uses web technology (I knew the basics from school), but to make an Electron app, I had to rewrite the entire app from scratch. I did it, and actually, I never returned to Python. And I know exactly why: primarily because of debugging. Anyway, JS is a superior language (not just because of V8).

I feel like a true developer at this point (June 2018) - I distribute my own app with GUI.

Distributing Electron apps is extremely simple with the help of tools like electron-packager and electron-builder. I packed it into both DEB and Snap. Actually, you can find [SmartCalc](https://snapcraft.io/smartcalc) on the Snap store to this day (today, I am not proud of it).

### GIT
<sub>*Early 2018*</sub>

Almost the entire development of SmartCalc was managed using Git and stored on GitHub, but at that time, I was unable to commit, push, and pull changes using the CLI, so I used a web browser for it. At the end of my 1st class, we got second homework - do a website indistinguishable from professional sites. I used this repo and GitHub pages to host my website. 

### First money from coding & script-kiddie era
<sub>*Early 2018*</sub>

After learning basic web development from school homework, I realized I could monetize it — so I started charging my classmates to build their semester project websites. That was my first real money made from writing code.

Around the same time, I went through an "innocent hacker" phase. I spent evenings cracking Wi-Fi passwords, building trojans with Metasploit, manipulating RFID cards, and sniffing RF signals when unlocking cars. It was mostly for the thrill, but it gave me a solid appreciation for security, protocols, and networking early on. 

### Professional career
<sub>*Late 2019*</sub>

My father runs a family business: decorating buildings (painting interior).

My dialogue with my father:

```
Me: “How do you do pricing?”

My father: “I use Excel.”

Me: “How long does it take?”

My father: “Several hours.”

Me: “OMG, that's a huge amount of time. Can you show me some sheets?”

My father: “Of course.”
```

We found a typo that cost us a few bucks and made me think about replacing Excel with another tool. I was looking for some tools online and found some, tried them, but no tool could satisfy our needs.

I offered my father a solution - I will make an Electron app for our enterprise for pricing our work. He agreed, and that's when the FIM Trade Pricing Tool was born. I dived into the development, and after three months, we had a working piece of software. Unfortunately, I did not have enough time for SmartCalc development.

FIM Trade Pricing Tool is a proprietary program, but I use Git and Github for its development, so every change is tracked.

From the beginning (September 2019), it was basically a combination of Electron and jQuery. After six months of development, jQuery has been replaced with Svelte.

### First real B2B client: FALADRO
<sub>*Early 2020*</sub>

In early 2020, I got an unexpected phone call from a salesman at [FALADRO](https://faladro.sk/) (a company running both B2B and B2C stores with paints, varnishes, and drugstore goods).

```
Salesman: “Do you think it’s possible to make a system where our B2B customers just walk around their warehouse, scan the EAN barcodes of items they need to replenish, and order directly from us?”

Me: “How are they doing it now?”

Salesman: “They make orders over the phone using paper notes. Items constantly get forgotten, and the whole system is a mess.”

Me: “It’s definitely possible. It’s a demanding project, and I’d be happy to take it on, but I'll need some help — luckily, I know someone who might be interested.”
```

I called my friend Alex, who was doing Flutter:

```
Me: “Hey, I have a client who needs a mobile B2B ordering app. Want to do this project with me?”

Alex: “Sure, let's do it.”
```

The whole initial contract was for a mere €2,000 — €1,000 for me, €1,000 for him. We promised the client a complete cross-platform ordering system available on both Google Play and the Apple App Store. I was responsible for the backend, EcoSun ERP synchronization, and the manager's desktop Electron app, while Alex built the Flutter mobile app. The barcode scanner was the beating heart of the entire solution from day one: clients walked warehouse aisles, scanned product barcodes with their phone cameras, and submitted replenishment orders directly into FALADRO’s system without human intervention.

The hardest part at the start wasn't the technical complexity, but the human factor. Just getting an API out of FALADRO’s legacy ERP software (EcoSun) took an exhausting 8 months of back-and-forth communication with their staff. Between that massive delay and school, it took us about a year to deliver the MVP and onboard our first customers.

We delivered the Android app early, but Alex hit a complete wall with iOS. Whenever the client or I asked about the App Store release, the answer was always the same: *“It’ll be ready next month.”*

That “next month” dragged on for an entire year. During this time, I found myself in the worst possible position — looking like an idiot to both sides:
* **To the client**, I looked incompetent for failing to deliver the complete solution we had promised.
* **To Alex**, I was the unreasonable guy expecting him to grind through the friction of the Apple ecosystem for pocket money.

Realizing that underpricing the project was the root cause of the deadlock, I swallowed my pride and opened an embarrassing renegotiation with the client. I laid out the reality, asked for more money, and requested that they pay us for the work we had completed so far. To my relief, they agreed. I paid Alex his share and presented him with better terms to motivate him.

For a moment, it seemed to work: Alex created a publisher profile for FALADRO, pushed some minor Android improvements, and promised the iOS app was finally right around the corner. But soon enough, the exact same cycle returned. Even with more money on the table, his motivation evaporated. Every time I confronted him, he gave me the same hollow reassurance that he was just about to finish it.

Because the initial contract was never officially fulfilled, we couldn't transition the client into a standard paid annual maintenance agreement. Instead, I spent the next several years maintaining the server, the sync bridge, and the desktop infrastructure entirely for free, constantly staying in active contact with the client to keep their business afloat.

By 2024, decay set in completely. Alex stopped maintaining Android as well, the app fell behind Google Play Store policy requirements, and it was taken down. We entered a frustrating era where we had to manually sideload APKs directly onto customers' phones just to keep their ordering operational.

In 2026, we finally reached the breaking point. The client insisted on cutting ties with Alex, and I couldn't disagree. I fired him and took the responsibility entirely onto my own shoulders to finish my end of the bargain. With the help of AI coding agents, I scrapped the abandoned Flutter codebase and rewrote the client from scratch into a modern Svelte PWA.

Because it runs directly in the browser as an installable app, it instantly solved the missing iOS client without App Store friction, replaced the broken Android app, and finally settled the years-old contractual debt. The customers loved it, our user base expanded, and today I maintain their entire digital infrastructure — they have since expanded into the Czech Republic, and at an international industry conference, companies from other countries openly envied their seamless ordering setup.

### Covid era
<sub>*2020 – 2021*</sub>

I used the time the corona lockdown brought me for refactoring FPT and starting two open-source projects ([svelte-fullpage](https://github.com/Hejtmus/svelte-fullpage) and [svelte-lightbox](https://github.com/Hejtmus/svelte-lightbox)) that I need for my client's website.

I applied to FIT VUT in Brno.

Somewhere around this time, I took part in a high school competition (SOČ) and got 3rd place in the Bratislava round, which is enough to be accepted to most technical colleges in Slovakia and the Czech Republic. I attached my SOČ results to my application form, and I got accepted for daily study.

I finished high school as an IT specialist, so now I have time for business until I start attending FIT VUT.

### First employment: Objectify
<sub>*Early 2021*</sub>

In early 2021, right before finishing high school, I took my first job as an employee outside of my own freelancing and family business work: I joined **Objectify**, a software development agency of around 50 developers.

I was assigned to a project called **Woodfinder** — a marketplace designed to connect timber and wood producers directly to consumers, cutting out middlemen to make prices cheaper. I worked primarily on the frontend using Vue 2 (building out the product catalog and customer portal), paired with responsive email templates built in MJML and a somewhat eccentric Slovak backend framework called Total.js.

Beyond coding UI, my lead quickly noticed a strength in my workflow: technical research and tool evaluation. Whenever the project hit a specialized requirement — like determining the best way to handle responsive transactional emails (which led to MJML) or calculating real driving distances between timber warehouses and client delivery addresses — I was trusted to investigate available solutions, weigh the trade-offs, and select the tools we would integrate.

I stayed there for six months, and we successfully delivered the project to production. Even though the platform later had to restructure its business model, the experience was a great milestone: it gave me my first taste of formal Scrum sprints and team code reviews, confirming I could step into an established developer team and contribute effectively from day one.

### College begins & Leaving Objectify
<sub>*Late 2021*</sub>

In the autumn of 2021, I moved to Brno to start my computer science degree at FIT BUT. It didn't take long to realize that the combination of demanding university coursework and agency deadlines at Objectify was unsustainable. Because Woodfinder was already stable in production, I initially dialed back my hours, and soon after decided to hand in my resignation to focus fully on school and selective freelance work.

### Supercolor: Custom E-shop & Physical Store Infrastructure
<sub>*Mid 2021*</sub>

During summer breaks and alongside my studies, I took on a project for **Supercolor** (a retail store specializing in paints and varnishes).

This was a dual-sided engagement: on the web side, I built their custom B2C e-commerce platform from scratch using SvelteKit, Firebase, Stripe, and Algolia search. On the physical side, I took over managing the digital infrastructure in their retail store — setting up the local network, maintaining their store computers, and handling basic OS configurations for their automated paint-mixing machines (which I still keep running in maintenance mode).

### Deep Dive into Systems & Writing a Compiler in C
<sub>*Late 2022*</sub>

I generally don't like bragging about university assignments, but compiler development was something that genuinely fascinated me. The project was designed for a four-person team spanning an entire semester, but half of our team lacked the necessary low-level skills for such a demanding task. Rather than letting the project sink, another teammate and I took on the workload and wrote the entire compiler ourselves in pure C — just the two of us.

Building the lexical analyzer, recursive-descent parser, semantic analysis, and intermediate code generation from scratch completely demystified what actually happens under the hood when high-level code translates down to machine instructions.

Semantic analysis and optimization were easily the most exciting parts for me. Even though an optimizer wasn't mandatory for the assignment, I couldn't resist implementing basic optimizations like pre-evaluation of constant expressions, dead-code elimination, and basic tree shaking.

### The CMS Evolution & GenoaCMS
<sub>*2022 – 2024*</sub>

Across almost every project I had built — from FALADRO to Supercolor — my end users were non-technical staff. They didn't care about the underlying backend; they just needed a straightforward UI to manage products, orders, and content. In fact, nearly half of the team's entire work on Woodfinder at Objectify was spent building out custom admin dashboards and CMS interfaces.

This led to a recurring frustration: the moment you build on a non-standard or modern cloud stack (like SvelteKit, Firebase, or custom cloud APIs), off-the-shelf monolithic CMS options don't fit. You find yourself constantly trapped in the cycle of reinventing the wheel and writing a custom admin interface from scratch for every single client.

At first, I started building a dedicated CMS specifically tailored for my favorite stack: SvelteKit and Firebase. But halfway through, I had an epiphany:

> *“Am I actually doing anything different from every other CMS creator who locks developers into their own rigid stack? No, I'm just repeating the exact same mistake.”*

That realization changed everything. Instead of building another opinionated CMS, I set out to architect a truly **universal, adapter-based headless CMS** — one capable of adapting to any cloud infrastructure (GCP, AWS), any database (Firestore, Postgres, MinIO), and any frontend framework. That became the foundation of **GenoaCMS**.

Because I genuinely needed this architecture for my client work, I chose GenoaCMS as my [Bachelor's thesis](https://www.vut.cz/studenti/zav-prace/detail/166024?zp_id=166024) at FIT BUT. I built the entire ecosystem from scratch — the core engine, a cloud abstraction layer, pluggable storage/auth adapters, a dedicated CLI, and custom Cloud Run deployment adapters. I defended the thesis and immediately put GenoaCMS into production, powering live client platforms like [SGS Expo](https://expo.sk/).

Academically, however, the thesis reviewers largely overlooked the architectural scope and real-world multi-cloud vision, giving the work an underwhelming grade of **D**. 

While frustrating, I didn't let a letter grade discourage me from software that was already solving real problems in production. Instead, it fueled my determination: I decided to make GenoaCMS the core focus of my Master’s diploma thesis as well — taking the system to the next level by focusing on security hardening, static analysis, and runtime guard injection for secure dynamic components.

Working through the marathon of my Bachelor's thesis also permanently changed my daily editor setup. Up until that point, I had been coding in WebStorm with the IdeaVim extension. But while watching a lot of ThePrimeagen’s videos, I fell in love with the pure harmony, smoothness, and the joy of never having to reach for a mouse. I decided to make the switch: I didn't start with heavy custom Lua tinkering right away, but kept it simple by adopting NvChad with a few personal plugins and minor configuration tweaks. It completely redefined my flow, and WebStorm was left behind for good.

### International contract: The AI surveillance tracker
<sub>*Mid 2024*</sub>

Right after GPT-4 launched and the massive AI hype wave kicked off, my childhood friend Simon ([@simonSlamka](https://github.com/simonSlamka)) — the same friend who introduced me to Linux years prior — was working freelance on Upwork. When I was looking for contract work, he brought me in to collaborate on a project for a US client.

The client managed a large, distributed workforce across multiple countries (including the Philippines) and wanted an extreme time-tracking system powered by AI to ensure workers weren't slacking off. It was designed to capture virtually every possible telemetry point: periodic screenshots, mouse movement, keystroke frequency, active open files, and live network socket connections — all fed into LLM prompts for automated productivity analysis.

The architecture was split between us:
* Simon wrote the low-level **C backend** that tapped into OS APIs to collect the system telemetry and activity hooks.
* I wired the low-level data into a desktop **Electron app** to handle the client-side telemetry pipeline, and built the **monitoring dashboard** for the business owner to review AI productivity summaries and employee activity.

I wasn't particularly proud of the product itself — more than a few people pointed out it felt straight out of *1984*. But as a student who needed income facing an urgent client deadline, it was an undeniable reality check. Technically, it was an intense crash course in real-time desktop telemetry, integrating generative AI pipelines, and collaborating within a fast-paced international team spanning the US, Slovakia, and the Philippines.

### My first SaaS: Automated receipts & accounting (`receipts-framework`)
<sub>*Spring 2025 – Present*</sub>

In early 2025, the accountant for my family’s business approached me with a problem: his clients were drowning in paper receipts and invoices. The existing market tools (like Doklado) charged around €0.20 per scanned document — to the point where one of his clients was spending several hundred euros a year just on document scanning fees.

I realized I could build something substantially better and cheaper:
* For Slovak receipts, I tapped directly into the official **eKasa** system: scanning the receipt’s QR code with the phone camera and fetching authenticated transaction data with 100% accuracy.
* For foreign receipts and invoices, I built an extraction pipeline combining local computer vision (OpenCV edge detection) with **Cloud AI (Google Gemini)** to extract structured line items, VAT rates, and supplier data.

The framework generated both structured raw data exports for accounting software and a pixel-accurate visual PDF reconstruction of the original receipt. Through aggressive pre-processing and pipeline optimization, I pushed the extraction cost down to **less than €0.001 per document**. Instead of charging predatory pay-per-document rates, I launched it as a subscription SaaS — a flat, transparent annual tier with unlimited usage.

The tool was deployed to the accountant’s client base and operated in production throughout the year. Until that first tax office inspection arrived, I genuinely had occasional nightmares about a rounding error or calculation discrepancy causing havoc for our clients. Thankfully, both the raw data exports and PDF receipt reconstructions passed the tax audit with zero issues, proving the legal and technical robustness of the solution.

### The AI mindset shift & `business-framework`
<sub>*Late 2025 – Present*</sub>

For the first year of building the SaaS, I wrote every line of code myself. Up until late 2025, I was an "AI conservative" — I acknowledged AI might become useful eventually, but found existing code generators unreliable for serious production software.

Toward the end of 2025 and into 2026, I started working deeply with autonomous AI coding agents (especially Claude). Seeing their reasoning capabilities in a properly structured architectural environment completely flipped my perspective.

Accepting that writing raw code by hand would no longer be my primary daily activity was genuinely difficult to swallow — especially with the cruel irony that I had *just* truly mastered my Neovim setup and Vim motions, only to realize agents could write the syntax faster. Typing code had been my craft and identity for over a decade. But it helped me realize a deeper truth:

> *Writing raw syntax is no longer the bottleneck. True software engineering is about system architecture, domain modeling, and robust guardrails.*

I put this into practice immediately: I took the rock-solid in-browser camera and scanner engine that I had painstakingly perfected for `receipts-framework`, and using AI agents, I recycled and adapted the entire architecture into the new Svelte PWA for [FALADRO](#first-real-b2b-client-faladro) — completely replacing the abandoned Flutter app in record time.

Armed with this new paradigm, my accountant and I decided to expand the document scanner into a full **autonomous accounting and business suite** (`business-framework`):
1. **Intelligent Ingestion & Reconciliation:** The system takes raw bank statements and documents, classifies transactions against the chart of accounts, and automatically matches payments to invoices with human-in-the-loop checkpoints for both the business owner and the accountant.
2. **Automated Tax Filings:** Automatically prepares ledger balances, period closures, and corporate tax filings (DPPO).
3. **PEPPOL & e-Invoicing Ready:** With Slovakia mandating digital invoicing via **PEPPOL** starting in 2027, I integrated the **ePošťák** network directly into the engine — supporting secure PKCE OAuth consent, automated outbound Peppol delivery, and instant inbound invoice capture.

Today, the receipt extraction SaaS is mature and running in production, while the autonomous business and accounting engine is in active daily development.

### Academic Pivot: Information Security & Quantum Curiosity
<sub>*September 2025 – Present*</sub>

In September 2025, I transitioned to **FEEC BUT** to pursue my Master’s degree in **Information Security**. 

The programme gave me solid, hands-on exposure to advanced cryptography and machine learning (including neural networks and reinforcement learning). But the biggest spark came from studying **Quantum Cryptography** (the physical, photon-based protocols). Strangely enough, it wasn't just the cryptography that fascinated me — it ignited a deep curiosity in **quantum computing itself**.

That exposure led me to start casually exploring quantum computing principles and the Standard Model of particle physics in my spare time. As a longtime *Star Trek* fan, diving into physics and quantum mechanics felt like an entirely natural progression. 

While I'm definitely still a beginner when it comes to quantum systems, stepping outside traditional software stacks to understand the physical and theoretical limits of computation is exciting — and a great way to differentiate my thinking from the typical developer crowd.




### Other non-interesting facts

- 🔭 **Currently building:** Autonomous accounting & AI business software (`business-framework`)
- 🎓 **Currently studying:** Master’s in Information Security at FEEC BUT
- 🏍️ **On two wheels:** Passionate motorcyclist (riding a Honda CB650R)
- ⛵ **At sea:** Licensed skipper (International Maritime License Cat. C & Maritime VHF Radiotelephone operator)
- 🤸 **Calisthenics:** Dedicated to bodyweight strength (proudest milestones: 90° push-up and full front lever)
- 🖖 **Sci-Fi:** Huge *Star Trek* fan (favorite captain: Jonathan Archer — though Sisko is a very close second)
- ⚡ **Fun fact:** I play *War Thunder*
- 📫 **How to reach me:** filip.holcik.official@gmail.com
- 😄 **Pronouns:** He/Him
