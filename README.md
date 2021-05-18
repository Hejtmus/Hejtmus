# Hello

My name is Filip Holčík, and I’m a full-stack student web developer. I finished high school as an “IT specialist” at SPŠE Karola Adlera (electrical engineering) in Bratislava, Slovakia. Now I'll be studying the IT degree program at FIT VUT in Brno, Czech Republic.

## Tech I work with

- JavaScript

- Node.js

- Electron.js

- Svelte

- Linux

- C language

- Firebase

## BTW, I use

- Arch (JK Pop!OS)

- VIM (IdeaVIM in WebStorm)

- Firefox

## How my IT passion started

Since I was 12 years old, I was a gamer, but I was gaming on an All-In-One computer with notebook performance. To play games comfortably on that HW, I had to tinker with software; at that point, I started hating Windows. Although I hated Windows, I was using it because I didn’t know there were alternatives. I was gaming like this until I moved into my father's.

After I moved to my father's, I couldn’t play games because my AIO stayed in my mother’s house, and the only computer I had was an Acer Aspire ONE. Because I moved, I also changed my school, and there I met my friend Simon (@simonSlamka) from my childhood. With Simon, we were mostly talking about physics, but once he trash-talked Windows, and I trash-talked as well, and then I asked him what can we do with it, he said, 'Use Linux.' My mind was blown by the fact that there is an alternative to Windows.

### Mint chapter

The next day I visited my friend, Simon, to get Linux Mint installed on my Acer Aspire One. Since then, I was busy tweaking my system and learning how it works. I got familiar with the thought that once I could be a programmer. Circa after one year, I started demanding a PC from my father. I wanted a desktop, but I couldn’t find one I could afford with my HW requirements, so I changed my mind and bought a notebook.

### Ubuntu chapter

I decided to dual-boot my new NTB: Ubuntu for school and Windows for gaming. I reconfigured my bios, installed Ubuntu (16.04 LTS (newly released)) alongside Windows, installed apps I wanted, games, and that was it. After a week, I realized that Windows is bloated with ads and software I didn't want, so I deleted all Windows partitions and extended my Linux partitions.

But when I wanted to play GTA 5, I had to install Windows back. Meanwhile, I finished elementary school and started attending high school (SPŠE Karola Adlera). I started programming in Python 3 in my free time. At the end of the 1st half of the academic year, we got homework - make a responsive website. I decided to code it on Windows, just to give it one last try, and I found out that Windows is a terrible choice for productivity; it just slows me down in my developer journey (BTW, for some reason, my Windows boot time was 45 minutes, while Linux boot time was just 2 minutes). After this experience, I decided to remove Windows from my life.

### Python development

After I went full-time Linux (December 2017), I decided to make my very first program, a real program, with an installation script and a desktop entry - I made SmartCalc. It was a simple CLI program, just one python script that prompts the user what mathematical operation shall be done, and then redirects to another script that prompts a user value and outputs a computed value.

During the development of this app, I heard somewhere, “Doing installers is difficult” and “GUI is extremely technically difficult.” Because I was a programmer for less than a year, I wanted to prove to myself that I’m good. I decided to pack SmartCalc into a Debian package.

### Making Debian packages

Now, this was a challenge, with pathetic Debian documentation and one good but deprecated video on YT. I was still adding features into SmartCalc, but I invested a significant amount of time into the DEB package. It was two months (but felt like four) of searching the web, watching videos, guessing how Debian packages work, and reading dpkg, DH, and other manuals. I consider that time investment to have been well made (February 2018) because I successfully packaged my app into the DEB installer. Most importantly, I have developed solid problem-solving skills. For the next two months, I dedicated myself to the optimization of the packaging app. 

### Snap packages

I was aware of the fact that not every Linux user uses a Debian-based system. This fact motivated me to make a Snap package out of my existing DEB package. This process was a lot simpler; it just required a YAML config file, an existing app package, and snapcraft (a CLI tool). That was it.

### GUI

Now I’m half of a good programmer, but I want to be all good (that's like a boolean, there is just a true programmer and a false programmer, nothing in the middle :D). I guess now I have to make a GUI for SmartCalc.

There was one critical choice I had to make: which framework to use. Based on my previous experience with GUI in Python, I will not use TKinter or PYQT. I wanted to use GTK+, but when I tried importing GTK libs into Python, I broke my GTK systemwide (ouch). I could give it another shot, but I really wanted to try out Electron.js because it uses web technology (I knew the basics from school), but to make an Electron app, I had to rewrite the entire app from scratch. I did it, and actually, I never returned to Python. And I know exactly why: primarily because of debugging. Anyway, JS is a superior language (not just because of V8).

I feel like a true developer at this point (June 2018) - I distribute my own app with GUI.

Distributing Electron apps is extremely simple with the help of tools like electron-packager and electron-builder. I packed it into both DEB and Snap. Actually, you can find [SmartCalc](https://snapcraft.io/smartcalc) on the Snap store to this day (today, I am not proud of it).

### GIT

The almost whole development of SmartCalc was managed using Git and stored on GitHub, but at that time, I was unable to commit, push, and pull changes using the CLI, so I used a web browser for it. At the end of my 1st class, we got second homework - do a website indistinguishable from professional sites. I used this repo and GitHub pages to host my website. 

### Profesional career

My father runs a family business: decorating buildings (painting interior).

My dialogue with my father:

```
Me: ““How do you do pricing?””

My father: ““I use Excel.””

Me: ““How long does it take?””

My father: ““Several hours.””

Me: “OMG, that that's a huge amount of time. Can you show me some sheets?””

My father: ““Of course.””
```

We found a typo that cost us a few bucks and made me think about replacing Excel with another tool. I was looking for some tools online and found some, tried them, but no tool could satisfy our needs.

I offered my father a solution - I will make an Electron app for our enterprise for pricing our work. He agreed, and that's when the FIM Trade Pricing Tool was born. I dived into the development, and after three months, we had a working piece of software. Unfortunately, I did not have enough time for SmartCalc development.

FIM Trade Pricing Tool is a proprietary program, but I use Git and Github for its development, so every change is tracked.

From the beginning (September 2019), it was basically a combination of Electron and jQuery. After half of the year of development, jQuery has been replaced with Svelte.

#### Tailor-made solutions

Our enterprise started offering and developing tailor-made solutions for small and medium businesses.

We make apps for computers, mobile phones, and servers. However, our apps have to be connected (in most cases); we use the cloud.

### Covid era

I used the time the corona lockdown brought me for refactoring FPT and starting two open-source projects ([svelte-fullpage](https://github.com/Hejtmus/svelte-fullpage) and [svelte-lightbox](https://github.com/Hejtmus/svelte-lightbox)) that I need for my client's website.

I applied to FIT VUT in Brno.

Somewhere around this time, I took part in a high school competition (SOČ) and got 3rd place in the Bratislava round, which is enough to be accepted to most technical colleges in Slovakia and the Czech Republic. I attached my SOČ results to my application form, and I got accepted for daily study.

I finished high school as an IT specialist, so now I have time for business until I start attending FIT VUT.




### Other non-interesting facts

- 🔭 I'm currently working on my business

- 🌱 I'm currently learning to be competitive as an enterprise

- 🤔 I'm looking for help with CSS in svelte-lightbox

- 📫 How to reach me: filip.holcik.official@gmail.com

- 😄 Pronouns: He/Him

- ⚡ Fun fact: I play WarThunder
