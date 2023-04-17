---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
css: unocss
title: Visual debugging experience for your frontend tests
download: true
---

# Visual debugging experience for your frontend tests


Techie Story x Dwarves Foundation x WeBuild

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>


<div class="pt-13 relative">
  <div class="absolute px-2 py-1 rounded cursor-pointer right-0" hover="bg-white bg-opacity-10">
    <a href="https://twitter.com/hung_dev" target="_blank">https://twitter.com/hung_dev</a>
    <br />
    <a href="https://github.com/nvh95" target="_blank">https://github.com/nvh95</a>
    <br />
    <a href="https://facebook.com/hungdotdev" target="_blank">https://facebook.com/hungdotdev</a>
  </div>
  
</div>


--- 

<img src="/logo/jest-preview.png" width="300" class="mx-auto" />
<img src="/logo/vitest-preview.png" width="200" class="mx-auto" />


---
layout: center
class: text-center
---

# 🙌 Do you write tests for your frontend app?

<v-click>

If you haven't, I hope you will after my talk 😝.

</v-click>


---
layout: image-right
image: /hung.jpg
---

# Hi, My name is Hung 👋

- Senior Frontend Engineer at Filum
- Ex - Lead Frontend Engineer @ Got It Inc.
- Open Source contributor Enthusiast
- Creator of <a href="https://github.com/nvh95/jest-preview">Jest Preview</a> and <a href="https://github.com/nvh95/vitest-preview">Vitest Preview</a>
- Core member of <a href="https://www.bestofjs.org">bestofjs.org</a>
- Obsession with DX
- Connect with me:
  - <carbon-logo-twitter />: <a href="https://twitter.com/hung_dev" target="_blank">@hung_dev</a>
  - <carbon-logo-github />: <a href="https://github.com/nvh95" target="_blank">@nvh95</a>
  - 🔗: <a href="https://hung.dev" target="_blank">hung.dev</a>
  - <carbon-logo-facebook />: <a href="https://github.com/hungdotdev" target="_blank">@hungdotdev</a>
  - 📧: hi@hung.dev

---

# Table of Contents
- Why writing tests?
- What type of tests should we choose?
- Write and debug your tests faster with Jest Preview/ Vitest Preview
- Some thoughts on Open Source


---

# Why writing tests?

<v-click>

- Catching bugs early

</v-click>

<v-click>

- Confident when add new features

</v-click>

<v-click>

- Confident when refactor code

</v-click>

<v-click>

- Save time in the long run

</v-click>


<v-click>

=> It's like an investment

</v-click>

---

# Why engineers don't usually write tests?


<v-click>

- Boring tasks

</v-click>

<v-click>

- No immediate value

</v-click>

<v-click>

- Low ROI in a short term

</v-click>

<v-click>

- Hard to debug

</v-click>

---

# What type of tests should we choose?

<https://kentcdodds.com/blog/the-testing-trophy-and-testing-classifications>

<img src="/pyramid.jpg" width="600" class="mx-auto" />

--- 

# What type of tests should we choose?
Unit tests

<Tweet id="1148986961207730176" scale="0.45" />

---

# What type of tests should we choose?
E2E tests

<img src="/wait.jpeg" width="300" class="mx-auto" />

---

# What type of tests should we choose?
Integration tests with "e2e" style
<img src="/e2e-like.png" width="400" class="mx-auto" />


---

# Write and debug your tests faster with Jest Preview/ Vitest Preview

---

# What is Jest Preview and why I built it?

## Problem:
<div grid="~ cols-2 gap-4">
<div class="text-sm">

<v-click>

- When you run a test, you only see the result in the terminal

</v-click>

<v-click>

- You don't know what your app looks like when the test is running

</v-click>

<v-click>

- It's very hard to debug a failed test: Very Longgg HTML

</v-click>

<v-click>


<details><summary>Have you ever tried to click on a button, but there is no button, it's just the spinner is loading?
</summary>
  <video width="320" height="240" controls autoplay muted loop>
    <source src="/problem-with-current-tests.mp4" type="video/mp4">
  </video>
  </details>
  
</v-click>

<v-click>

=> Question: If `jest` can print out the HTML, can we render it on a browser?

</v-click>

<v-click>

=> Yes. We can!!

</v-click>
</div>
  <div>
    <img src="/debug-terminal.png" width="600" class="mx-auto" />
  </div>

</div>


---

# What is Jest Preview and why I built it?


<img src="/jest-preview-demo.gif" width="600" class="mx-auto" />


---

# What is Jest Preview and why I built it?

## Benefits of Jest Preview

<div grid="~ cols-2 gap-4">
<div>
<v-click>

- Debug a failed test easier

</v-click>

<v-click>

- We can see what our app looks like, so the next testing steps are easily predictable => write test faster

</v-click>

<v-click>

- Shorten the gap between unit/ integration tests and e2e tests, but still fast in execution time

</v-click>

<v-click>

=> My personal experience: I write tests 200-300% faster, thanks to jest-preview

</v-click>
</div>
<div>
  <img src="/jest-preview-demo.gif" width="600" class="mx-auto" />
</div>

</div>


---
layout: iframe
url: >-
  https://stackblitz.com/edit/jest-preview?embed=1&ctl=1&file=src%2FApp.test.tsx,README.md
---

layout: center
class: text-center


---

# What did I receive from doing open source software?


- **Knowledge. A lot of knowledge.**

<img src="/meme/knowledge.jpg" width="300" />


<v-click>

- Read open source code a lot => code reading/ debugging skills improved
- Understand how the tools you use everyday work under the hood => Better programmer



- Rabbit hole: Jest, Vite core, CRA core, Websocket, chokidar, shebang, PostCSS, Babel...

</v-click>


---

# What did I receive from doing open source software?


- **Opportunities:**



<v-click>

- Nominated for the Most Exciting Use of Technology, React Open Source Awards, React Summit
<img src="/jest-preview-nominee.png" width="300" class="mx-auto"/>

</v-click>

<v-click>

- Jobs: Companies reach out

</v-click>

<v-click>

- Conferences/ Tech events

</v-click>


---

# What did I receive from doing open source software?


**Know great developers:**

- Twitter
<div class="flex gap-1 m-b-2">
<img src="/nw1.png" />
<img src="/nw2.png" />
</div>
<div class="flex gap-1 m-b-2">
<img src="/nw3.png" />
<img src="/nw4.png" />
</div>
<img src="/nw5.png" />


---

# What did I receive from doing open source software?


Know great developers:


- In-person (CityJS Singapore 2022)

<div class="flex gap-1 m-b-2">
  <img src="/network/maya.jpg" class="object-cover" width="200" />
  <img src="/network/evan.jpg" class="object-cover" width="200" />
  <img src="/network/tan.jpg" class="object-cover" width="300" />
</div>


---

# What did I receive from doing open source software?


**Know great developers:**

- In-person (JSConf Korea 2022)
<div class="flex gap-1 m-b-2 h-40">
  <img src="/network/jsconf/erick.jpeg" class="object-cover" width="100" />
  <img src="/network/jsconf/dwane.jpeg" class="object-cover" width="100" />
  <img src="/network/jsconf/jeremy.jpeg" class="object-cover" width="100" />
  <img src="/network/jsconf/chuiyoung.jpg" class="object-cover" width="100" />
  <img src="/network/jsconf/jane.jpeg" class="object-cover" width="100" />
  <img src="/network/jsconf/anna.jpeg" class="object-cover" width="100" />
</div>

<div class="flex gap-1 m-b-2 h-40">
  <img src="/network/jsconf/nicolo.jpeg" class="object-cover" width="100" />
  <img src="/network/jsconf/hj.jpeg" class="object-cover" width="100" />
  <img src="/network/jsconf/sosun.jpg" class="object-cover" width="100" />
  <img src="/network/jsconf/anu.jpeg" class="object-cover" width="100" />
  <img src="/network/jsconf/ellie.jpeg" class="object-cover" width="100" />
  <img src="/network/jsconf/sona.jpg" class="object-cover" width="100" />
</div>

<!--
You might recognize some of them
- Erick Wendel
- Jeremy Wagner
- Dwane Hemmings
- Jeong Eun Lee
- Nicolò
- Hui Jing
- Anu
- Ellie
- Sona
- Shin Young
- Sosun
-->

---

# What did I receive from doing open source software?


I received a lot of thanks:
<div class="flex gap-1 m-b-2">
  <img src="/thanks/thanks1.jpg" class="object-contain" width="300" />
  <img src="/thanks/thanks2.jpg" class="object-contain" width="200" />
  <img src="/thanks/thanks5.png" class="object-contain" width="300" />
</div>
<div class="flex gap-1 m-b-2">
  <img src="/thanks/thanks3.jpg" class="object-contain" width="250" />
  <img src="/thanks/thanks4.jpg" class="object-contain" width="250" />
  <img src="/thanks/thanks6.png" class="object-contain" width="280" />
</div>

<!--
=> Motivation for me to keep doing it . 9-5
-->


---
layout: center
class: text-center
---

# Thanks for your attention!

Q&A
<div>
<img src="/qr-jest-preview.png" width="200" class="mx-auto" />
</div>

<p class="text-xs">Try <a href="https://github.com/nvh95/jest-preview" target="_blank">Jest Preview</a> and <a href="https://github.com/nvh95/vitest-preview" target="_blank">Vitest Preview</a> and give it a star since it's free 😝</p>

<small>Slides available (and open source) at <a href="https://talkwithdf.hung.dev" target="_blank">https://talkwithdf.hung.dev</a></small>
