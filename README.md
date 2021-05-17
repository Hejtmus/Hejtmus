# Hello

My name is Filip Holčík and I'am a student full-stack web developer. I finished high school as "IT specialist" at SPŠE Karola Adlera (electrical engineering) in Bratislava, Slovakia. And now I'll be studying IT degree program at VUT FIT in Brno, Czech Republic.

## Tech I work with

- JavaScript

- Node.js

- Electron.js

- Svelte

- Linux

- C language

- Firebase

## BTW I use

- Arch (JK Pop!OS)

- VIM (IdeaVIM in WebStorm)

- Firefox

## How my IT passion started

I was gamer since I was 12 year old, but I was gaming on All-In-One computer with notebook performance, to be able to play games comfortably on that HW, I had to tinker with software, at that point I started hating Windows. Despite I hated Windows, I was using it, because I didn't know, there was alternatives. I was gaming like this until I moved to my father.

After I moved to my father, I coludn't play games, because my AIO stayed in my mother's house, and only computer I had was Acer Aspire ONE. Because I moved, I also changed my school, and there I met my friend Simon from my childhood. With Simon we were mostly talking about physics, but once he trashtalked Windows, and I trashtalked as well and then I asked him, what can we do with it. I got answer, use Linux. My mind was blown by the fact, that there is alternative to Windows.

### Mint chapter

Next day I visited my friend Simon, to get Linux Mint installed on my Acer Aspire one. Since then I was busy with tweaking my system and lerning, how it works. I got familiar with thought that once I could be a programmer. Circa after one year I started demanding PC from my father. I wanted desktop, but with my HW requirements I couldn't find one I could afford, so I changed my mind and bought a notebook.

### Ubuntu chapter

I decided to dualboot my new NTB, Ubuntu for school and Windows for gaming. I reconfigured my bios, installed Ubuntu (16.04 LTS (newly released)) alongside Windows, isntalled apps I wanted, games and that was it. After week I relized, that Windows is bloated with ads and software I don't want, so I deleted Windows partitions and extended Linux partitions.

But I once I wanted play GTA 5, in order to play it I had to install Windows back. Meanwhile I finished elementary school and started attending high school (SPŠE Karola Adlera). I started programming in Python 3 in my free time. At the end of 1st half of school year we got homework - do responsive website. I decided to code it on Windows, just to give it one last try, and I found out, that Windows is terrible choice for productivity, it just slows me down in my developer journey (BTW for some reason my Windows boot time was 45 minutes, FYI Linux boot time was just 2 minutes). After this experience I decided to remove Windows from my life.

### Python development

After I went full-time Linux (December 2017), I have decided to make my very first program, but real program, with installation script and desktop entry - I made SmartCalc. It was simple CLI program, just one python script that prompts user what mathematical operation shall be done, and then redirects to another script that prompts user value and outputs computed value.

During development of this app, I heard somewhere "Doing installers is difficult" and "GUI is extremely technically difficult". Because I was programmer less than year, I wanted to prove to myself, that I'm good. I decided to pack SmartCalc into debian package.

### Making Debian packages

Now this was a challage, with pathetic Debian documentation and 1 good, but deprecated video on YT. I was still adding features into SmartCalc, but significant amount of time I invested into DEB package. It took 2 months (but felt like 4) of searching web, watching videos, guessing how debian packages work and reading dpkg, dh and other manuals. I consider that time investment as worth (February 2018), because I successfully packaged my app into DEB installer and most importantly I have developed problem solving skills. Next 2 months I dedicated to optimalisation of packaging app. 

### Snap packages

I was aware of the fact, that not every Linux user uses Debian based system. This fact motivated me into making Snap package out of my existing DEB package. This process was by a lot simpler, it just required yaml config file, existing app package and snapcraft (CLI tool), that was it.

### GUI

Now I'am half of good programmer, but I want to be all good (that's like boolean, there ist just true programmer and false programmer, nothing in the middle) :D, I guess now I have to make GUI for SmartCalc.

There was one really important choice up to me - Which framework to use. Based on my previous experience with GUI in Python I know, I will not use TKinter or PYQT. I wanted to use GTK+, but when I tried importing GTK libs into Python I broke my GTK systemwide, ouch. I could give it another shot, but I really wanted to try out Electron.js, because it uses web technology (I knew basics from school), but in order to make Electron app, I had to rewrite entire app from scratch. I did it, and actually I never returned back to Python, and I know exactly why, mostly because debugging, anyway JS is superior language (not just because V8).

At this point (June 2018) I feel like a true developer - I distribute my own app with GUI.

Distributing Electron apps is extremely simple with help of tools like electron-packager and electron-builder. I packed it into both DEB and Snap. Actually you can find [SmartCalc](https://snapcraft.io/smartcalc) on Snapstore to this day (today I am not proud of it).

### GIT

Almost whole development of SmartCalc was managed using Git and stored on GitHub, but at that time I was unable of commiting, pushing, pulling changes from CLI so I used browser for it. At the end of my 1st class we got second homework - do website indistinguishable from profesional sites. I used this repo and github pages to host my website. 

### Profesional career

My father runs family business, decorating buildings (painting interior).

My dialogue with my father:

```
Me: "How do you do pricing?"

My father: "I use Excel."

Me: "How long does it take?"

My father: "Several hours."

Me: "OMG, that's huge amount of time, can you show me some sheet?"

My father: "Off course."
```

We have found typo that cost us few bucks, and made me thinking about replacing Excel with other tool. I was looking for some tools online and found some, tried them, but there was no tool that satisfy our needs.

I offered my father solution - I will do Electron app for our enterprise for pricing our work, he agreed an FIM Trade Pricing Tool was born. I dived into development and after 3 months we had working pice of software. Unfortunately I did not have enough time for SmartCalc development.

FIM Trade Pricing Tool is proprietary program, but for its development I use Git and Github, so every change is tracked.

From the beginning (September 2019) it was basically combination of Electron and jQuery. After half of year of development jQuery has been replaced with Svelte.

#### Tailor-made solutions

Our enterprise started offering and developing tailor-made solutions for small and medium businesses.

We make apps for computers, mobile phones, servers. But our apps has to be connected (in most cases), for that we use cloud.

### Covid era

Time corona lockdown borught to me I used for refactioring FPT and starting 2 opensource projects ([svelte-fullpage](https://github.com/Hejtmus/svelte-fullpage) and [svelte-lightbox](https://github.com/Hejtmus/svelte-lightbox)), that I need for my client's website.

I applied to VUT FIT in Brno.

Somewhere around this time I took part in high school competition (ŠOČ) and placed 3rd in Bratislava round, which is enough to be accepted to most of technical colleges in Slovakia and Czech Republic. I attached SOČ results to my application form and I got accepted for daily study.

I finished high school as IT specialist, so now I have time for business, until I start attending VUT FIT.




### Other non-interesting facts

- 🔭 I’m currently working on business

- 🌱 I’m currently learning being competitive as enterprise

- 🤔 I’m looking for help with CSS in svelte-lightbox

- 📫 How to reach me: filip.holcik.official@gmail.com

- 😄 Pronouns: He/Him

- ⚡ Fun fact: I play WarThunder

