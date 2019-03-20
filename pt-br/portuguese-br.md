<p align="center">
  <img alt="#100DaysOfCode Front-End Development" src="https://i.imgur.com/dwYOP0B.jpg" />
</p>

---

Esse é um currículo um pouco opinativo para o aprendizado de desenvolvimento front-end durante #100DaysOfCode. Como esse currículo cobre uma vasta quantidade de tópicos de front-end, pode ser pensado mais como um curso de "pesquisa" que um mergulho profundo em qualquer área. Idealmente, o que você levará após completar esse currículo será uma certa familiaridade com cada tópico e a habilidade de, se necessário, facilmente mergulhar mais fundo em qualquer área no futuro.

Esse currículo foi significativamente influenciado pelo roteiro do [Desenvolvedor Frontend Moderno](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c). Por favor dê uma olhada--é ótimo.

**Nota**: Eu sei que desenvolvimento front-end pode significar muitas coisas diferentes para várias pessoas! Se você é um desenvolvedor front-end e acredita que esse guia pode ser melhorado, por favor me avise abrindo uma issue como descrito na seção de [contribuição](#contribuindo). Obrigado!

# :calendar: Currículo

O princípio fundamental desse repositório é o [timeboxing](https://en.wikipedia.org/wiki/Timeboxing). Se você algum dia tentou aprender desenvolvimento web ou qualquer outra habilidade, você deve ter passado por um momento de grande dificuldade em um tópico em particular. Esse repositório visa atribuir um certo número de dias para cada tecnologia e encoraja você a seguir em frente assim que aquele número de dias acabar.

É esperado que todos estejam em níveis diferentes de proeficiência quando começar esse desafio, e está tudo bem. Desenvolvedores front-end iniciantes e especialistas podem se beneficiar da prática timeboxed em cada uma dessas áreas.

As atividades recomendadas dia a dia são as seguintes:

- Dias 1-8: [HTML](#html)
- Dias 9-16: [CSS](#css)
- Dias 17-24: [JavaScript Básico](#javascript)
- Dias 25-27: [jQuery](#jquery)
- Dias 28-33: [Web Design Responsivo](#rwd)
- Dias 34-36: [Acessibilidade](#accessibility)
- Dias 37-39: [Git](#git)
- Dias 40-44: [Node and NPM](#node)
- Dias 45-50: [Sass](#sass)
- Dias 51-54: [Bootstrap](#bootstrap)
- Dia 55: [BEM](#bem)
- Dias 57-61: [Gulp](#gulp)
- Dias 62-65: [Webpack](#webpack)
- Dia 66: [ESLint](#eslint)
- Dias 68-83: [React](#react)
- Dias 84-89: [Redux](#redux)
- Dias 90-94: [Jest](#jest)
- Dias 95-97: [TypeScript](#typescript)
- Dias 98-100: [NextJS](#nextjs)

# :mag_right: Os Detalhes

Abaixo você encontrará um pouco de informação sobre cada tópico nesse currículo e também algumas ideias do que fazer em cada um. Para inspiração nos projetos a serem feitos juntos com esse currículo, veja [a seção de ideias de projetos](#project-ideas). 

Como parte do princípio do timeboxing, está tudo bem se você não passar por todos os tópicos presentes na seção de "Áreas e ideias de aprendizado". Você, ao invés disso, focar em tirar o melhor do número dos dias atribuídos para aquela área e então seguir em frente.

<a name="html"></a>
![HTML](https://i.imgur.com/O0F5XSR.jpg)

Hypertext Markup Language (HTML) é a linguagem de marcação padrão para criar páginas e aplicações web. Com Cascading Style Sheets (CSS) e JavaScript, é formada a tríade de tecnologias para a World Wide Web. Os navegadores recebem documentos HTML de um servidor web ou do armazenamento local e os renderiza em páginas web multimídia. HTML descreve semânticamente a estrutura de uma página e originalmente inclue sugestões para a aparência do documento. (Fonte: [Wikipedia](https://en.wikipedia.org/wiki/HTML))

### :bulb: Concluindo

HTML realmente é a base do desenvolvimento web. Até mesmo em frameworks JavaScript você acabará, de alguma forma, escrevendo HTML.

### :book: Ideias e áreas de aprendizado

- Faça a seção de [HTML e HTML5 básico](https://learn.freecodecamp.org/) na freeCodeCamp (em inglês)
- Estrutura de uma página HTML
- Elementos HTML
- Aninhando elementos HTML
- Markup semântico
- Links / multipla páginas
- Imagens
- Audio/video media
- Formulários e elementos form
- Cria um site com multiplas páginas! (Veja [Ideias de projetos](#project-ideas) se você precisar de inspiração).

<a name="css"></a>
![CSS](https://i.imgur.com/028GOR0.jpg)

Cascading Style Sheets (CSS) é uma linguagem de folha de estilo usada para descrever a apresentação de um documento escrito em uma linguagem de marcação como HTML. CSS é uma tecnologia que faz parte da tríade da World Wide Web, juntamente com HTML e JavaScript. CSS é projetado para permitir a separação de apresentação e conteúdo, incluindo layout, cores e fontes. Essa separação pode melhorar a acessibilidade de conteúdo, fornecer mais flexibilidade e controle na especificação de características de apresentação, além de permitir que várias páginas da Web compartilhem formatação especificando o CSS relevante em um arquivo .css separado e reduzir a complexidade e a repetição no conteúdo estrutural. (Fonte: [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets))

### :bulb: Concluindo

CSS é outro componente essencial do desenvolvimento web. Enquanto é usado principalmente para estilizar e posicionar elementos HTML, vem se tornando cada vez mais capaz de realizar tarefas mais dinâmicas (por exemplo, animações) que seriam feitas através do JavaScript. 

### :book: Ideias e áreas de aprendizado

- Faça as seções de [CSS básico, CSS flexbox e CSS grid](https://learn.freecodecamp.org/) na freeCodeCamp (em inglês)
- CSS in-line 
- `<style>` tags
- CSS externo usando `<link>`
- Estilizando componentes
- Seletores
- Floats, limpando floats
- Layouts (grid, flexbox)
- Fontes, fontes customizadas
- Estilize a sua página HTML que você fez quando aprendeu HTML!

<a name="javascript"></a>
![JavaScript](https://i.imgur.com/oHdD86j.jpg)

JavaScript, frequentemente abreviada como JS, é uma linguagem interpretada de alto nível que segue as especificações do ECMAScript. É uma linguagem também caracterizada como dinâmica, fracamente tipada, baseada em prototype e multi paradigmas. Juntamente com HTML e CSS, JavaScript é uma das três tecnologias que formam a tríade da World Wide Web. JavaScript permite desenvolver páginas interativas e assim é uma parte essencial no desenvolvimento de aplicações web. A grande maioria dos sites usa JS e a maior parte tem um mecanismo dedicado a executá-lo. (Fonte: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### :bulb: Concluindo

JavaScript has become increasingly important in the front-end world. While it was once used mainly to make pages dynamic, it is now the foundation of many front-end frameworks. These frameworks handle a lot of the tasks that were formerly handled by the back-end (e.g., routing and displaying different views).

### :book: Ideias e áreas de aprendizado

- Take the [Basic JavaScript and ES6 sections](https://learn.freecodecamp.org/) on freeCodeCamp.
- Too many language fundamentals to list here!
- `<script>` tag and placement
- Accessing HTML elements
- The event loop, call stack, and event queue
- Prototypal Inheritance
- Reference vs. value
- Add some dynamic elements or logic to your HTML/CSS page(s) developed earlier!

<a name="jquery"></a>
![jQuery](https://i.imgur.com/m9j02Fo.jpg)

jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript. (Source: [jQuery.com](https://jquery.com/))

### :bulb: Concluindo

After you have spent some time with plain (also called "vanilla") javascript, you may find some tasks a bit cumbersome, especially those related to accessing and manipulating HTML elements. For quite a while, jQuery was the go-to library for making these kinds of tasks easier and consistent across different browsers. Nowadays, jQuery isn't necessarily "mandatory" learning because of advancements in vanilla javascript, CSS, and newer javascript frameworks (we'll look at frameworks later). Still, it would be beneficial to take a little time to learn some jQuery and apply it to a small project.

### :book: Ideias e áreas de aprendizado

- Take the [jQuery section](https://learn.freecodecamp.org/) on freeCodeCamp.
- Document ready
- Selectors
- Toggle classes
- Animation
- Add or move HTML elements
- Add jQuery to your site!

<a name="rwd"></a>
![Responsive Web Design](https://i.imgur.com/Bt1zWwq.jpg)

Responsive web design (RWD) is an approach to web design that makes web pages render well on a variety of devices and window or screen sizes. Recent work also considers the viewer proximity as part of the viewing context as an extension for RWD. Content, design and performance are necessary across all devices to ensure usability and satisfaction. A site designed with RWD adapts the layout to the viewing environment by using fluid, proportion-based grids, flexible images, and CSS3 media queries, an extension of the @media rule. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: Concluindo

Responsive web design is all about making web applications look and function properly on all types of advice. A quick-and-dirty example would be that a website should look and function properly both in a desktop web browser and on a mobile phone browser. An understanding of responsive design is crucial for any front-end developer!

### :book: Ideias e áreas de aprendizado

- Take the [Responsive Web Design Principles section](https://learn.freecodecamp.org/) on freeCodeCamp.
- Media queries, breakpoints
- Responsive images
- Make your website responsive!
- Use Chrome DevTools to view your site on different devices/viewports.

<a name="accessibility"></a>
![Accessibility](https://i.imgur.com/ayioMQw.jpg)

Web accessibility is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with disabilities. When sites are correctly designed, developed and edited, generally all users have equal access to information and functionality. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: Concluindo

Accessibility, often written as a11y, is one of the most important topics in front-end web development, yet it seems to often get short shrift. Creating accessible web applications is not only ethically sound, but also makes a lot of business sense considering the additional audience that will be able to view your applications when they are accessible.

### :book: Ideias e áreas de aprendizado

- Take the [Applied Accessibility section](https://learn.freecodecamp.org/) on freeCodeCamp.
- Read some content on [The A11Y Project](https://a11yproject.com/about)
- Review their [checklist](https://a11yproject.com/checklist)
- Update your site(s) for accessibility based on this checklist

<a name="git"></a>
![Git](https://i.imgur.com/5QoNJqs.jpg)

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. (Source: [git-scm.com](https://git-scm.com/))

### :bulb: Concluindo

Version/code control is an essential part of any web developer's toolkit. There are a number of different version control systems, but Git is by far the most prevalent at the moment. You can (and should!) use it to track your projects as you learn!

### :book: Ideias e áreas de aprendizado

- [Git Tutorial for Beginners (Video)](https://www.youtube.com/watch?v=HVsySz-h9r4)
- Install git
- Set up a [github](https://github.com) account
- Learn the most-used git commands:
  - init
  - clone
  - add
  - commit
  - push
  - pull
  - merge
  - rebase
- Add your existing projects to github!

<a name="node"></a>
![Node and NPM](https://i.imgur.com/8ik2alD.jpg)

Node.js is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser. JavaScript is used primarily for client-side scripting, in which scripts written in JavaScript are embedded in a webpage's HTML and run client-side by a JavaScript engine in the user's web browser. Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser. Consequently, Node.js represents a "JavaScript everywhere" paradigm, unifying web application development around a single programming language, rather than different languages for server side and client side scripts. (Source: [Wikipedia](https://en.wikipedia.org/wiki/Node.js))

### :bulb: Concluindo

While nodejs is typically known as a back-end solution, it is used quite frequently to support front-end development. It does this in a number of ways, including things like running build tools, testing, and linting (all to be covered soon!). Node Package Manager (npm) is another great feature of node and can be used to manage dependencies of your project (i.e., code libraries your project might rely on -- jQuery is an example!).

### :book: Ideias e áreas de aprendizado

- Research node and how it is different than the browser
- Install node (npm comes with it)
- Create a simple javascript file and run it with node
- Use NPM to manage any dependencies in your existing project(s) (e.g., jQuery!)

<a name="sass"></a>
![Sass](https://i.imgur.com/ZRedLge.jpg)

Sass is an extension of CSS that adds power and elegance to the basic language. It allows you to use variables, nested rules, mixins, inline imports, and more, all with a fully CSS-compatible syntax. Sass helps keep large stylesheets well-organized, and get small stylesheets up and running quickly, particularly with the help of the Compass style library. (Source: [sass-lang.com](https://sass-lang.com/documentation/file.SASS_REFERENCE.html))

### :bulb: Concluindo

Sass allows you to write CSS in a more programmatic way. If you've done some CSS, you might have noticed that you end up repeating a lot of information--for example, specifying the same color code. In Sass, you can use things like variables, loops, and nesting to reduce redundancy and increase readability. After writing your code in Sass, you can quickly and easily compile it to regular CSS.

### :book: Ideias e áreas de aprendizado

- [Install Sass](https://sass-lang.com/install) globally with npm!
- [Sass Crash Course Video](https://www.youtube.com/watch?v=roywYSEPSvc)
- Follow the [Learn Sass](https://sass-lang.com/guide) tutorial and/or [freeCodeCamp](https://learn.freecodecamp.org/) Sass tutorial.
- Update your existing site to generate your CSS using Sass!

<a name="bootstrap"></a>
![Bootstrap](https://i.imgur.com/cJ21eH2.jpg)

\* Some alternatives: Foundation, Bulma, Materialize

Bootstrap is a free and open-source front-end framework for developing websites and web applications. It contains HTML and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. (Source: [Wikipedia](<https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)>))

### :bulb: Concluindo

There are many options for laying out, styling, and making your web application dynamic, but you'll find that starting with a framework helps you tremendously in getting a head start. Bootstrap is one such framework, but it is definitely far from the only option! I recommend getting familiar with one framework like this, but it's far more important to grasp HTML, CSS, and JavaScript fundamentals than it is to get caught up in any one framework.

### :book: Ideias e áreas de aprendizado

- Learn what Bootstrap is and why you would want to use it
- [Bootstrap 4 Crash Course (Video)](https://www.youtube.com/watch?v=hnCmSXCZEpU)
- Complete the Bootstrap section on [freeCodeCamp](https://learn.freecodecamp.org/)
- Refactor your site using bootstrap!

<a name="bem"></a>
![BEM](https://i.imgur.com/MCvMRQl.jpg)

The Block, Element, Modifier methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex, its goal is to help developers better understand the relationship between the HTML and CSS in a given project. (Source: [css-tricks.com](https://css-tricks.com/bem-101/))

### :bulb: Concluindo

It's important to know naming and organization systems like BEM exist and why they are used. Do some research here, but at a beginner level I wouldn't recommend devoting too much time to the subject.

### :book: Ideias e áreas de aprendizado

- Read the [BEM introduction](http://getbem.com/introduction/)
- [Why I Use BEM (Video)](https://www.youtube.com/watch?v=SLjHSVwXYq4)
- Create a simple webpage using BEM conventions.

<a name="gulp"></a>
![Gulp](https://i.imgur.com/KQrByqq.jpg)

Gulp is a toolkit for automating painful or time-consuming tasks in your development workflow, so you can stop messing around and build something. (Source: [gulpjs.com](https://gulpjs.com/))

### :bulb: Concluindo

In modern front-end development, you'll often find yourself needing to automate tasks like bundling, moving files, and injecting references into HTML files. Gulp is one tool that can help you do these things!

### :book: Ideias e áreas de aprendizado

- Install gulp with npm
- Follow the [gulp for beginners tutorial](https://css-tricks.com/gulp-for-beginners/) on CSS-Tricks
- In your website, set up gulp to:
  - Compile Sass for you
  - Put the generated CSS file in `build` subdirectory
  - Move your web pages to the build directory
  - Inject a reference to your generated CSS file into your web pages

<a name="webpack"></a>
![Webpack](https://i.imgur.com/0rx82Kl.jpg)

At its core, webpack is a static module bundler for modern JavaScript applications. When webpack processes your application, it internally builds a dependency graph which maps every module your project needs and generates one or more bundles. (Source: [webpack.js.org](https://webpack.js.org/concepts/))

### :bulb: Concluindo

Imagine that you have a large web development project with a number of different developers working on a lot of different tasks. Rather than all working in the same files, you might want to modularize them as much as possible. Webpack helps enable this by letting your team work modularly and then, come time to build the application, Webpack will stick it all together: HTML, CSS/Sass, JavasScript, images, etc. Webpack isn't the only module bundler, but it seems to be the front-runner at the moment.

### :book: Ideias e áreas de aprendizado

- Read [webpack concepts](https://webpack.js.org/concepts/)
- [What is Webpack, How does it work? (Video)](https://www.youtube.com/watch?v=GU-2T7k9NfI)
- [This webpack tutorial](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1)

<a name="eslint"></a>
![ESLint](https://i.imgur.com/CJb6ZnL.jpg)

ESLint is an open source JavaScript linting utility originally created by Nicholas C. Zakas in June 2013. Code linting is a type of static analysis that is frequently used to find problematic patterns or code that doesn’t adhere to certain style guidelines. There are code linters for most programming languages, and compilers sometimes incorporate linting into the compilation process. (Source: [eslint.org](https://eslint.org/docs/about/))

### :bulb: Concluindo

Linting is a fantastic tool for code quality, readability, and consistency. Using a linter will help you catch syntax and formatting mistakes before they go to production. You can run linters manually or include them in your build/deployment process.

### :book: Ideias e áreas de aprendizado

- Install eslint using npm
- [How to Setup VS Code + Prettier + ESLint (Video)](https://www.youtube.com/watch?v=YIvjKId9m2c)
- Lint your JavaScript

<a name="react"></a>
![React](https://i.imgur.com/uLYz15W.jpg)

\* Some alternatives: Vue, Angular, Ember

React (also known as React.js or ReactJS) is a JavaScript library for building user interfaces. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications. Complex React applications usually require the use of additional libraries for state management, routing, and interaction with an API. (source: [Wikipedia](<https://en.wikipedia.org/wiki/React_(JavaScript_library)>))

### :bulb: Concluindo

Front-end JavaScript frameworks are at the forefront of modern front-end development. One important takeaway here is that React, despite being incredibly popular, is only a library for building user interfaces whereas frameworks like Vue and Angular aim to be more full-featured. For example, if you build an application with in React that needs to route to different views, you'll need to bring in something like `react-router`.

### :book: Ideias e áreas de aprendizado

- Take the [React tutorial](https://reactjs.org/tutorial/tutorial.html)
- [Learn React with Mosh](https://www.youtube.com/watch?v=Ke90Tje7VS0)
- Refactor your website as a React app!
- Note: `create-react-app` is a convenient tool to scaffold new React projects.

<a name="redux"></a>
![Redux](https://i.imgur.com/S9H2Dbp.jpg)

Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. On top of that, it provides a great developer experience, such as live code editing combined with a time traveling debugger. (Source: [redux.js.org](https://redux.js.org/introduction/getting-started))

### :bulb: Concluindo

As you build bigger and bigger front-end applications, you start realizing that it's hard to maintain application state: things like the if the user is logged in, who the user is, and generally what's going on in the application. Redux is a great library that helps you maintain a single source of state on which your application can base its logic.

### :book: Ideias e áreas de aprendizado

- This [Redux video tutorial](https://www.youtube.com/watch?v=93p3LxR9xfM)
- This [Redux video series](https://egghead.io/courses/getting-started-with-redux) by Dan Abramov, creator of Redux
- Take note of the [Redux three principles](https://redux.js.org/introduction/three-principles)
  - Single source of truth
  - State is read-only
  - Changes are made with pure functions
- Add Redux state management to your app!

<a name="jest"></a>
![Jest](https://i.imgur.com/Cr39axw.jpg)

Jest is a delightful JavaScript Testing Framework with a focus on simplicity. It works with projects using: Babel, TypeScript, Node, React, Angular, Vue and more! (Source: [jestjs.io](https://jestjs.io))

### :bulb: Concluindo

It is very important to set up automated testing for your front-end projects. Setting up automated testing will allow you to make future changes with confidence--if you make changes and your tests still pass, you will be fairly comfortable you didn't break any existing functionality. There are too many testing frameworks to list; Jest is simply one of my favorties.

### :book: Ideias e áreas de aprendizado

- Learn [Jest basics](https://jestjs.io/docs/en/getting-started)
- If you used `create-react-app`, [Jest is already configured](https://facebook.github.io/create-react-app/docs/running-tests).
- Add tests to your application!

<a name="typescript"></a>
![TypeScript](https://i.imgur.com/BZROJNs.jpg)

\* Alternative: Flow

TypeScript is an open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing to the language. TypeScript is designed for development of large applications and transcompiles to JavaScript. As TypeScript is a superset of JavaScript, existing JavaScript programs are also valid TypeScript programs. TypeScript may be used to develop JavaScript applications for both client-side and server-side (Node.js) execution. (Source: [Wikipedia](https://en.wikipedia.org/wiki/TypeScript))

### :bulb: Concluindo

JavaScript is dynamically typed. However, it is a common belief that static typing (i.e., specifying variable types, classes, interfaces ahead of time) is both clearer and reduces the likelihood of defects/bugs. Regardless of how you feel on the topic, it's important to at least get a feel for a statically-typed version of JavaScript like TypeScript. Note that TypeScript compiles down to JavaScript so it can be interpreted by browsers (i.e., browsers don't natively interpret TypeScript).

### :book: Ideias e áreas de aprendizado

- [Learn TypeScript in 5 minutes](https://medium.freecodecamp.org/learn-typescript-in-5-minutes-13eda868daeb)
- [Learn TypeScript in 50 minutes (Video)](https://www.youtube.com/watch?v=WBPrJSw7yQA)
- Optionally [create a React app with TypeScript](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4)

<a name="nextjs"></a>
![NextJS](https://i.imgur.com/YNtW38J.jpg)

Next.js is a minimalistic framework for server-rendered React applications. (Source: [Next.js — React Server Side Rendering Done Right](https://hackernoon.com/next-js-react-server-side-rendering-done-right-f9700078a3b6))

### :bulb: Concluindo

Now we're getting advanced! By now you've built a React (or Vue or Angular) application that does quite a bit of work in the browser. For various reasons (e.g., SEO, concerns over client performance), you might actually want your front-end application to be rendered on the server rather than the client. That's where a framework like next.js comes in.

### :book: Ideias e áreas de aprendizado

- Next.js [Getting Started](https://nextjs.org/learn/)
- [Next.js Crash Course (Video)](https://www.youtube.com/watch?v=IkOVe40Sy0U)
- Create a Next.js app or migrate your existing app to Next.js

# Mas, e sobre X?

Essa lista deverá te dar uma ampla exposição ao ecossitema do front-end, mas é simplesmente impossível atingir todos os tópicos, sem contar a infinidade de ferramentas em cada área! Se você acredita que eu esqueci algo muito importante, por favor veja na seção de [contribuição](#contribuindo) como ajudar a melhorar esse guia.

# Ideias de Projetos

A medida que você progredir no #100DaysOfCode, você irá querer fazer vários projetos nos quais você possa aplicar os seus novos conhecimentos. Nessa seção, eu tentarei prover algumas ideias de projeto que você possa usar. Alternativamente, você é encorajado a ter as suas próprias ideias de projetos e essas ideias poderão te interessar e motivar ainda mais.

- Ideias para iniciantes:
  - Construa um portfolio
- Ideias intermediárias/avançadas:
  - Construa um app de análise de tweet (Se você já sabe back-end e integrações com API)
  
# Precisa de ajuda?

Geralmente, eu acredito que as seguintes fontes são de grande valor no aprendizado de desenvolvimento de software:

- Pesquise o problema no Google
- [StackOverflow](http://www.stackoverflow.com) (Tem uma boa chance que a sua questão já tenha sido perguntada e terá um ranking alto quando pesquisada no Google).
- [Mozilla MDN Web Docs](https://developer.mozilla.org/en-US/)
- [freeCodeCamp](https://www.freecodecamp.org/)
- Meetups de desenvolvimento na sua cidade! A maioria é bem amigável com todos os níveis de experiência.

Se você precisar da minha ajuda, sinta-se livre para [conectar-se comigo no Twitter](http://www.twitter.com/nas5w) e eu tentarei o meu melhor para oferecer alguma assistência. Se você acredita que tem algum problema no currículo ou quer fazer uma recomendação, veja a [seção de contribuição](#contribuindo) abaixo.

# Contribuindo

## Espalhe por aí

Se você gostar do trabalho que está sendo feito aqui, você pode contribuir significativamente compartilhando esse repositório, das seguintes formas:

- Favoritando e fazendo o fork desse repositório
- Compartilhando esse repositório nas redes sociais

## Contribua com esse repositório

Esse é um trabalho em progresso e eu agradeço qualquer ajuda para manter essa base de conhecimento!

Quando for contribuir com esse repositório primeiro abra uma issue propondo fazer uma mudança antes de realmente fazê-la. Senão, será muito difícil entender a sua mudança e poderá acontecer de você ter muito trabalho para fazer uma mudança que não será mergeada.

Por favor note que todos envolvidos neste projeto estão ou aprendendo ou tentando ajudar--Por favor seja legal!

## Processo de Pull Request

1. Crie uma issue outlining the proposed pull request.
2. Obtenha aprovação do dono do projeto para fazer a modificação proposta.
3. Crie o pull request.
