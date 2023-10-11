---
layout: cover
mdc: true
download: true
title: What's like to use Postman to visualise data
transition: slide-left
lineNumbers: false
highlighter: shiki
info: |
  ## What's like to use Postman to visualise data
  Infobip Devs Talk

  Learn more at [infobip](https://www.infobip.com/)
drawings:
  presenterOnly: true
---

# What's like to use Postman to visualise data

<p class='text-2xl'>Teri Eyenike</p>

<div class='absolute bottom-0'>
  <span class='text-orange-500'>Infobip Devs Talk</span>
  <p class='text-slate-400'>Oct. 12, 2023</p>
</div>

<!--
Ask the audience, how many of them use Postman.

But today, I'll show you how to use Postman to visualise data from sending a request.
-->

---

<div class='grid grid-cols-2 gap-4 place-items-center'>
<div>
  <h2 class='text-4xl font-bold'>Teri Eyenike</h2>

  <p style='margin-top: 3rem' class='text-orange-500'>Software Developer / Technical Writer</p>

  - Postman Supernova

<div class='my-10 grid grid-cols-[40px_1fr] w-min gap-y-4'>
  <svg class="slidev-icon opacity-50" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path fill="currentColor" d="M5.884 18.653c-.3-.2-.558-.456-.86-.816a50.59 50.59 0 0 1-.466-.579c-.463-.575-.755-.841-1.056-.95a1 1 0 1 1 .675-1.882c.752.27 1.261.735 1.947 1.588c-.094-.117.34.427.433.539c.19.227.33.365.44.438c.204.137.588.196 1.15.14c.024-.382.094-.753.202-1.096c-2.968-.725-4.648-2.64-4.648-6.396c0-1.238.37-2.355 1.058-3.291c-.218-.894-.185-1.975.302-3.192a1 1 0 0 1 .63-.583c.081-.024.127-.034.208-.047c.803-.123 1.937.17 3.415 1.097a11.731 11.731 0 0 1 2.687-.308c.912 0 1.819.103 2.684.308c1.477-.933 2.614-1.227 3.422-1.097c.085.014.158.032.218.051a1 1 0 0 1 .616.58c.487 1.215.52 2.296.302 3.19c.691.936 1.058 2.045 1.058 3.292c0 3.758-1.674 5.666-4.642 6.393c.125.415.19.878.19 1.38c0 .664-.002 1.299-.007 2.01c0 .19-.002.394-.005.706a1 1 0 0 1-.018 1.957c-1.14.228-1.984-.532-1.984-1.524l.002-.447l.005-.705c.005-.707.008-1.338.008-1.997c0-.697-.184-1.152-.426-1.361c-.661-.57-.326-1.654.541-1.751c2.966-.334 4.336-1.483 4.336-4.66c0-.955-.312-1.745-.913-2.405a1 1 0 0 1-.189-1.044c.166-.415.236-.957.095-1.614l-.01.002c-.491.14-1.11.44-1.858.95a1 1 0 0 1-.833.135a9.626 9.626 0 0 0-2.592-.35c-.89 0-1.772.12-2.592.35a1 1 0 0 1-.829-.133c-.753-.507-1.374-.807-1.87-.947c-.143.653-.072 1.194.093 1.607a1 1 0 0 1-.189 1.044c-.597.656-.913 1.459-.913 2.404c0 3.172 1.371 4.33 4.322 4.66c.865.098 1.202 1.178.545 1.749c-.193.167-.43.732-.43 1.364v3.149c0 .986-.834 1.726-1.96 1.529a1 1 0 0 1-.04-1.963v-.99c-.91.062-1.661-.087-2.254-.484Z"></path></svg>
  <div>
    <a href='https://github.com/terieyenike' target='_blank'>terieyenike</a>
  </div>
  <svg class="slidev-icon opacity-50" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path fill="currentColor" d="M15.35 5.55a2.9 2.9 0 0 0-2.9 2.846l-.028 1.575a.6.6 0 0 1-.68.584l-1.562-.213c-2.053-.28-4.021-1.225-5.91-2.798c-.597 3.31.57 5.603 3.383 7.372L9.4 16.014a.6.6 0 0 1 .035.992L7.843 18.17c.947.06 1.846.018 2.592-.13c4.718-.942 7.855-4.492 7.855-10.348c0-.478-1.013-2.141-2.94-2.141Zm-4.9 2.81a4.9 4.9 0 0 1 8.385-3.355c.711-.005 1.316.175 2.668-.646c-.334 1.64-.5 2.353-1.213 3.332c0 7.641-4.697 11.358-9.464 12.309c-3.267.652-8.02-.419-9.38-1.842c.693-.053 3.513-.356 5.143-1.55c-1.38-.91-6.868-4.14-3.261-12.822c1.693 1.977 3.41 3.322 5.15 4.037c1.157.475 1.442.465 1.973.538Z"></path></svg>
  <div><a href="https://twitter.com/terieyenike" target="_blank">terieyenike</a></div>
  <svg class="slidev-icon opacity-50" viewBox="0 0 24 24" width="1.2em" height="1.2em"><path fill="currentColor" d="M20 22h-2v-2a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3v2H4v-2a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v2Zm-8-9a6 6 0 1 1 0-12a6 6 0 0 1 0 12Zm0-2a4 4 0 1 0 0-8a4 4 0 0 0 0 8Z"></path></svg>
  <div><a href="https://iamteri.tech" target="_blank">iamteri.tech</a></div>
</div>
</div>

<div>
  <img src='https://res.cloudinary.com/terieyenike/image/upload/c_scale,w_500/v1666716203/teri.jpg' class='rounded-full border-x-8 border-orange-600 border-solid grayscale object-contain w-9/12' />
</div>
</div>

---
layout: center
---

<div>
  <p class='text-7xl font-bold' style='margin-bottom: 1.5rem'>What is Postman?</p>
</div>

<p style='color: orange'>Postman is a collaborative API platform that simplifies creating, using, and testing APIs with a UI</p>

<ul>
  <li v-click>Build</li>
  <li v-click>Test</li>
  <li v-click>Debug</li>
  <li v-click>Monitor</li>
  <li v-click>Publish</li>
  <li v-click>Document APIs</li>
</ul>

<!--
Postman is a collaborative HTTP client which allows you to create requests to get data from an API. In essence, Postman is a API platform used by developers to create, test, and build APIs.

There’s over 20 million folks already and 500,000 organisations using Postman, so chances are pretty high that you’re going to need to interact with it at some point on your journey as you work alongside tech professionals. Uber, Paypal, etc
-->

---

<h2>APIs are not just for developers</h2>

 <img src='https://everpath-course-content.s3-accelerate.amazonaws.com/instructor%2Fc3jrngphf22ys6kxwfiw0g9kk%2Fpublic%2F1664232653%2Fwho_works_with_apis.1664232652967.png' />


---
transition: fade-out
---

# Reasons why you need to learn how to visualise data


<ul style='margin-top: 2rem'>
  <li>Present the insights to other people</li>
  <li>Hard to look at the raw data in JSON objects from the server, and understand it with some frontend code</li>
</ul>

<img v-click src='https://github-production-user-asset-6210df.s3.amazonaws.com/25850598/274324448-a9c38291-9e93-4f00-b718-9e28b406323e.jpg' class='object-contain w-3/4' />


<style>
h1 {
  color: orange
}
</style>

<!--
present quick insights at standups or to the team during meetings from the data.

Sometimes, you want to present the data in a visual way for better understanding.
-->

---

# Use case

<Tweet id='1709885519755112632' scale='0.70' />


---
layout: default
---

# Postman Visualizer

The major components in Postman Visualizer are:

- The template - Rendering the HTML with the handlebar template syntax {{}}
- [pm.visualizer.set()]{style='color:orange'} :inline-component{props='value'}
- [pm.getData()]{style='color:orange'} :inline-component{props='value'}

<div class='absolute bottom-20'>
  <a href='https://www.postman.com/api-visualizer/' target='_blank'>Learn more</a>
</div>

<style>
.footnotes-sep {
  @apply mt-20 opacity-10;
}
.footnotes {
  @apply text-sm opacity-75;
}
.footnote-backref {
  display: none;
}
</style>

<!--
Postman Visualizer is built to help you act on data and not just look at it. Postman Visualizer is your API visualization companion.

In our string template, we use the handlebars templating engine syntax with the two curly braces to dynamically render the data from the API wrapped around the handlebars expression.
-->

---

# Handlebars

Template Engines that lets you inject its syntax within the html template using the curly braces `{{}}` that is its expressions.

```js {2|5-6|8-9|13-15|17|21}
<div class='mt-5 grid gap-10 grid-cols-1 md:grid-cols-3'>
        {{#each response}}
            <div class='flex justify-center items-end bg-slate-50 shadow-lg relative'>
                <div class='p-8 w-full flex items-center flex flex-col'>
                    <img src={{image_url}} class='w-64 h-64 object-contain' />
                    <h3 class='text-3xl my-5 font-bold'>{{name}}</h3>
                    <span class='flex justify-between w-full'>
                        <span>ABV: {{abv}}%</span>
                        <span>IBU: {{ibu}}%</span>
                    </span>
                </div>
                <div class='absolute top-0 left-0 p-10 bg-slate-50 overflow-auto cursor-pointer w-full h-full opacity-0 transition duration-150 ease-out hover:opacity-90 leading-normal'>
                    <div class='text-4xl md:text-5xl tracking-tight leading-relaxed font-bold'>{{name}}</div>
                    <div class='pb-2 italic border-b-[2px] border-blue-500'>{{tagline}}</div>
                    <div class='my-6'>{{description}}</div>
                    <div>
                        Pair with: {{food_pairing}}
                    </div>
                </div>
            </div>
        {{/each}}
    </div>
```

<style>
h1 {
  font-size: 3rem;
  font-weight: 700;
  margin-bottom: 0.5em
}
</style>

---

# Demo time

<button class='bg-orange-500 text-white font-bold px-2 py-1'>
  <a href='https://www.postman.com/codedaily/workspace/my-workspace/collection/6619165-78feb494-9bde-4b6b-937c-3d27cb39ac3e?action=share&creator=6619165' target='_blank' style='text-decoration: none;'>Run in Postman</a>
</button>


<div class='flex justify-between'>
<ul style='margin-top: 2em'>
  <li v-click>Display the data as rows of cards</li>
  <li v-click>Turn API data into charts and graphs with Postman Visualizer</li>
  <li v-click>Using Postbot - Postman AI companion to generate code snippets</li>
</ul>
<img src='https://res.cloudinary.com/terieyenike/image/upload/v1696766172/punk_api_dllh3w.gif' v-click class='w-2/4' style='margin-right: 1rem' />
</div>



---

# Resources
- Postman Academy

  👉🏻 https://academy.postman.com

- The future is API-first

  👉🏻 https://api-first-world.com

<Tweet id='1711848096005607875' scale='0.5' />

---
layout: center
---

# Thank you

<div class='absolute bottom-8 left-8 right-8 text-slate-400 text-sm flex justify-between items-center px-5 py-5'>
  <span>
    <a href='https://twitter.com/terieyenike' target='_blank'>@terieyenike</a>
  </span>
  <span>
    <a href='https://www.postman.com/codedaily/workspace/my-workspace/collection/6619165-78feb494-9bde-4b6b-937c-3d27cb39ac3e?action=share&creator=6619165' target='_blank'>Run in Postman</a>
  </span>
</div>
