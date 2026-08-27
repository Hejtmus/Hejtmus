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

I decided to dual-boot my new NTB: Ubuntu for school and Windows for gaming. I reconfigured my bios, installed Ubuntu (16.04 LTS (newly released)) alongside Windows, installed apps I wanted, games, and that was it. After a week, I realized that Windows is bloated with ads and software I didn't want, so I deleted all Windows partitions and extended my Linux partitions.

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

The almost whole development of SmartCalc was managed using Git and stored on GitHub, but at that time, I was unable to commit, push, and pull changes using the CLI, so I used a web browser for it. At the end of my 1st class, we got second homework - do a website indistinguishable from professional sites. I used this repo and GitHub pages to host my website. 

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

Me: “OMG, that that's a huge amount of time. Can you show me some sheets?”

My father: “Of course.”
```

We found a typo that cost us a few bucks and made me think about replacing Excel with another tool. I was looking for some tools online and found some, tried them, but no tool could satisfy our needs.

I offered my father a solution - I will make an Electron app for our enterprise for pricing our work. He agreed, and that's when the FIM Trade Pricing Tool was born. I dived into the development, and after three months, we had a working piece of software. Unfortunately, I did not have enough time for SmartCalc development.

FIM Trade Pricing Tool is a proprietary program, but I use Git and Github for its development, so every change is tracked.

From the beginning (September 2019), it was basically a combination of Electron and jQuery. After half of the year of development, jQuery has been replaced with Svelte.

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

The whole contract was for a mere €2,000 — €1,000 for me, €1,000 for him. I was responsible for the backend, data synchronization, and the manager's desktop Electron app, while Alex built the Flutter mobile app. The barcode scanner was the beating heart of the entire solution from day one: clients walked their warehouse aisles, scanned product barcodes with their cameras, and submitted replenishment orders that landed directly in FALADRO’s system with zero human intervention.

The hardest part at the start wasn't the technical complexity, but the human factor. Just getting an API out of FALADRO’s legacy business ERP software (EcoSun) took an exhausting 8 months of back-and-forth communication with their staff. Between that massive delay and school, it took us about a year to deliver the MVP and onboard our first customers.

From 2021 through 2023, we went through a solid era of improvements — polishing order workflows, improving scanner quality-of-life, and adding features. But eventually, a slow decay set in. Alex began ignoring maintenance requests from FALADRO and stalled mobile updates. By 2024, the app fell behind Google Play Store policy requirements and was taken down. We entered a painful, frustrating phase where we had to manually sideload APKs directly onto customers' phones just to keep their ordering operational.

Fast-forward to 2026 — years later, as AI coding agents became genuinely capable, I decided to tackle the problem properly. For my first project written with AI agents, I scrapped the abandoned Flutter codebase entirely and rewrote the client from scratch into a modern, lightweight Svelte PWA. The customers loved the change, and we were finally able to expand our user base. Today, I still keep their entire digital infrastructure running — they have since expanded the system into the Czech Republic, and at an international industry conference, companies from other countries openly envied their seamless ordering setup.

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




### Other non-interesting facts

- 🔭 I'm currently working on my business

- 🌱 I'm currently learning to be competitive as an enterprise

- 🤔 I'm looking for help with CSS in svelte-lightbox

- 📫 How to reach me: filip.holcik.official@gmail.com

- 😄 Pronouns: He/Him

- ⚡ Fun fact: I play WarThunder
