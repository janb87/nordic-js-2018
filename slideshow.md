class: left, bottom, slide-main
background-image: url(./images/main.jpg)

# Nordic.js 2018

Jan Bevers

---

# Agenda

1. Browser stuff
2. Node.js stuff
3. Probably too early, but interesting
4. Other stuff I picked up
5. Discussions / questions

<iframe src="https://giphy.com/embed/uXVEhtcVDD7q0" width="480" height="362" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Fast but not furious: debugging user interaction performance issues (Anna Migas)

1. Demo of chrome dev tools (rendering tab, layers tab, paint flashing, fps)
2. Takeaways:
    1. ([from slide 58](https://www.slideshare.net/AnnaMigas1/nordicjs-fast-but-not-furious-debugging-user-interaction-performance-issues))
    2. Passive event listeners (polyfill available)
    3. Use "will-change" for things that change a lot (creates a separate layer)
    4. Try to animate using only transform or opacity

<iframe src="https://giphy.com/embed/10KL1QSQNsyEZa" width="480" height="200" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Building a Design System in React (Dominic McPhee)

1. Key benefits of a design system:
    1. Unified experience
    2. Better collaboration between teams
    3. Makes it easier to improve things like accessability, performance...
2. Tools that make life easier
    1. React (component based)
    2. TypeScript (developer experience)
    3. Markdown (documentation, examples)
    4. Design tokens (colors, spacing, fonts, typography, ...)
3. [Slides](https://speakerdeck.com/dfmcphee/building-a-design-system-with-react)

<iframe src="https://giphy.com/embed/kr0OMSLiyKUF2" style="position: absolute; left: 50%; bottom: 0;" width="360" height="300" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Accessible by law! Generating colors with JS and CSS Custom Properties (Ingvild Indrebø)

1. It’s illegal to have an inaccessible website in Norway
2. [Blogpost](https://medium.com/confrere/its-illegal-to-have-an-inaccessible-website-in-norway-and-that-s-good-news-for-all-of-us-b59a9e929d54)
3. [Accessible palette color generator](https://confrere.com/a11y/test/)
4. [Automate it!](https://medium.com/confrere/automatically-creating-an-accessible-color-palette-from-any-color-sure-e735c3f2f45e)

<iframe src="https://giphy.com/embed/ZKW68Qo3vvxss" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Headers for Hackers (Andrew Betts Hallen)

1. `Clear-Site-Data` - Clear the cache for an entire site (only partially supported in Chrome)
2. `Feature-Policy` - Turn off some bad features (eg sync http requests)
3. Don't use `X-Frame-Options`, instead use `Content-Security-Policy: frame-ancestors, 'self'`
4. Use `<link rel='preload' as='script'/>` for loading css/fonts

<iframe src="https://giphy.com/embed/eCqFYAVjjDksg" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Why we built another framework (Tomas Della Vedova)

1. Talk about why [Fastify](https://www.fastify.io) was created.
2. Fastify is a web framework for node.js
3. Focused on:
    1. Being as fast as possible, making optimale usage of the resources of your server
    2. Being as lightweight as possible to reduce overhead
    3. Being extensibile through a plugins architecture
4. [Benchmarks](https://www.fastify.io/benchmarks/)
5. Did you know that  <br /> JSON.stringify can be  <br /> made 2x faster? <br /> Checkout <br /> [fast-json-stringify](https://github.com/fastify/fast-json-stringify)

<iframe src="https://giphy.com/embed/7XsFGzfP6WmC4" style="position: absolute; right: 20px; bottom: 50px;" width="480" height="298" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Can you tell me if your Node app is healthy? (Alejandro Oviedo García)

1. Use tools to get metrics
    1. [Promethuis](https://prometheus.io/)
    2. [nodejs-dashboard](https://github.com/FormidableLabs/nodejs-dashboard)
2. Identify 'Event loop lag' using [blocked](https://www.npmjs.com/package/blocked)
3. [Examples](https://github.com/a0viedo/can-you-tell-if-your-node-app-is-healthy/)

<iframe src="https://giphy.com/embed/xFhB9bDqZngvC" style="position: absolute; bottom: 20px;" width="480" height="373" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Probably too early, but interesting

1. CSS/Houdini - Lower-level CSS DOM API
2. [Assembly Script](https://github.com/AssemblyScript/assemblyscript) - A TypeScript to WebAssembly compiler
3. [Node.js worker threads](https://nodejs.org/api/worker_threads.html) - Available from Node 10
4. [Epoc.js](https://github.com/charliegerard/Epoc.js) - JavaScript framework for the Emotiv

<iframe src="https://giphy.com/embed/3o6ZtnQ4zq5zerJDri" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Other stuff I picked up

1. [Ligthouse](https://developers.google.com/web/tools/lighthouse/) - Lighthouse is an open-source, automated tool for improving the quality of web pages
2. [Zeplin](https://zeplin.io/) - Handoff designs and styleguides with accurate specs, assets, code snippets—automatically
3. [FontFaceObserver](https://fontfaceobserver.com/) - Font Face Observer is a fast and simple web font loader. You can use it to load fonts and customise your browser’s font loading behaviour.
4. [Variable fonts](https://caniuse.com/#feat=variable-fonts)
5. Use placeholders instead of loaders (eg [react placeholder](https://github.com/buildo/react-placeholder))

*Keep experimenting, don't be scared to take some risk*

<iframe src="https://giphy.com/embed/PlnQNcQ4RYOhG" width="240" height="240" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

---

# Discussions / Questions

Still awake?

<iframe src="https://giphy.com/embed/eBCnpuRGBhQGY" width="480" height="409" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>
