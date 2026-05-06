# JavaScript Learning Projects

This repository was created to organize the main projects I developed throughout my JavaScript learning journey in Jonas Schmedtmann's JavaScript course.

The goal is not only to showcase finished applications, but also to show my progression as I learned new JavaScript concepts step by step. Each project represents a different moment of the course and focuses on specific skills, from basic DOM manipulation to object-oriented programming, geolocation, local storage, dates, timers, and more complex application logic.

## Projects

### 1. [Guess My Number](https://guessmynumber-rodrigo.netlify.app/)

Guess My Number was one of my first JavaScript projects. It was developed using basic DOM manipulation and JavaScript fundamentals such as variables, conditionals, functions, event listeners, and simple manual UI updates.

This project is intentionally simple because it represents the beginning of my learning process, when I was still getting comfortable with how JavaScript interacts with the browser.

### 2. [Pig Game](https://piggame-rodrigo.netlify.app/)

Pig Game was a step forward in complexity. In this project, I practiced working with game state, multiple players, dice rolls, score tracking, DOM updates, and event-driven logic.

Compared to Guess My Number, this project required more organization because the interface changes constantly depending on the player turn, current score, total score, and winner state.

### 3. [Bankist App](https://bankistapp-rodrigo.netlify.app/)

Bankist App is a fictional banking application built to practice JavaScript array methods and more advanced data manipulation. It includes features such as logging in, viewing transactions, transferring money, requesting loans, closing an account, sorting movements, formatting values, working with dates, and handling a logout timer.

This project was especially important because it helped me understand how methods like `map`, `filter`, `reduce`, `find`, `findIndex`, `some`, `forEach`, and `sort` can be used to transform, search, filter, and display real application data.

### 4. [Bankist Site](https://bankistsite-rodrigo.netlify.app/)

Bankist Site is a fictional landing page that focuses on advanced DOM manipulation and browser events. It includes interactive interface patterns such as a modal window, smooth scrolling, event delegation, tabbed content, sticky navigation, section reveal animations, lazy loading images, and a slider component.

This project was an important step because it moved beyond basic DOM updates and helped me understand how JavaScript can be used to create smoother, more dynamic user experiences in a real website layout.

### 5. [Mapty](https://mapty-rodrigo.netlify.app/)

Mapty is a workout tracking application built with object-oriented programming, geolocation, the Leaflet map library, and local storage. It allows the user to register running and cycling workouts directly on a map.

This project introduced a more structured way of thinking about applications, using classes, inheritance, private fields, event handling, browser APIs, and data persistence. It also included more planning before coding, which made it feel closer to a real front-end project.

## Next project: Forkify

I am still developing the final project of the course, Forkify. It should be completed soon and will combine many of the concepts learned throughout the course, including asynchronous JavaScript, API calls, modules, application architecture, rendering, state management, and a more complete project structure.

Once Forkify is finished, I plan to add it to this repository as the final and most advanced project in this learning path.

## Technologies used across the projects

- HTML
- CSS
- JavaScript
- DOM Manipulation
- JavaScript Arrays and Objects
- JavaScript Numbers, Dates, and Timers
- Object-Oriented Programming
- Geolocation API
- Local Storage
- Leaflet
- Parcel

## Running a project locally

Each project has its own folder and its own `package.json`. To run one of them locally, open the project folder in the terminal and run:

```bash
npm install
npm run start
```

To create a production build:

```bash
npm run build
```

For Netlify, the usual configuration for each project is:

```txt
Build command: npm run build
Publish directory: dist
```

---

# Projetos de Aprendizado em JavaScript

Este repositório foi criado para organizar os principais projetos que desenvolvi ao longo da minha jornada de aprendizado em JavaScript no curso de JavaScript do Jonas Schmedtmann.

O objetivo não é apenas mostrar aplicações finalizadas, mas também demonstrar minha evolução conforme fui aprendendo novos conceitos de JavaScript passo a passo. Cada projeto representa um momento diferente do curso e foca em habilidades específicas, desde manipulação básica do DOM até programação orientada a objetos, geolocalização, local storage, datas, timers e lógicas de aplicação mais complexas.

## Projetos

### 1. [Guess My Number](https://guessmynumber-rodrigo.netlify.app/)

Guess My Number foi um dos meus primeiros projetos em JavaScript. Ele foi desenvolvido utilizando manipulação básica do DOM e fundamentos da linguagem, como variáveis, condicionais, funções, event listeners e atualizações manuais simples na interface.

Este projeto é intencionalmente simples, pois representa o início do meu processo de aprendizado, quando eu ainda estava me familiarizando com a forma como o JavaScript interage com o navegador.

### 2. [Pig Game](https://piggame-rodrigo.netlify.app/)

Pig Game foi um passo adiante em complexidade. Neste projeto, pratiquei o controle de estado do jogo, múltiplos jogadores, rolagem de dados, contagem de pontos, atualizações no DOM e lógica baseada em eventos.

Comparado ao Guess My Number, este projeto exigiu mais organização, pois a interface muda constantemente dependendo da vez do jogador, da pontuação atual, da pontuação total e do estado de vitória.

### 3. [Bankist App](https://bankistapp-rodrigo.netlify.app/)

Bankist App é uma aplicação bancária fictícia criada para praticar métodos de arrays e manipulação de dados mais avançada em JavaScript. O projeto inclui funcionalidades como login, visualização de transações, transferência de dinheiro, solicitação de empréstimo, encerramento de conta, ordenação de movimentações, formatação de valores, trabalho com datas e um timer de logout.

Este projeto foi especialmente importante porque me ajudou a entender como métodos como `map`, `filter`, `reduce`, `find`, `findIndex`, `some`, `forEach` e `sort` podem ser usados para transformar, buscar, filtrar e exibir dados reais de uma aplicação.

### 4. [Bankist Site](https://bankistsite-rodrigo.netlify.app/)

Bankist Site é uma landing page fictícia focada em manipulação avançada do DOM e eventos do navegador. O projeto inclui padrões de interface interativos, como janela modal, smooth scrolling, event delegation, conteúdo em abas, navegação sticky, animações de revelação de seções, lazy loading de imagens e um componente de slider.

Este projeto foi uma etapa importante porque foi além das atualizações básicas no DOM e me ajudou a entender como o JavaScript pode ser usado para criar experiências mais fluidas e dinâmicas em um layout real de website.

### 5. [Mapty](https://mapty-rodrigo.netlify.app/)

Mapty é uma aplicação de registro de treinos desenvolvida com programação orientada a objetos, geolocalização, a biblioteca Leaflet e local storage. Ela permite que o usuário registre treinos de corrida e ciclismo diretamente em um mapa.

Este projeto introduziu uma forma mais estruturada de pensar em aplicações, utilizando classes, herança, campos privados, event handling, APIs do navegador e persistência de dados. Ele também envolveu mais planejamento antes da codificação, fazendo com que o projeto se aproximasse mais de uma aplicação front-end real.

## Próximo projeto: Forkify

Ainda estou desenvolvendo o projeto final do curso, o Forkify. Ele deve ser concluído em breve e combinará muitos dos conceitos aprendidos ao longo do curso, incluindo JavaScript assíncrono, chamadas de API, módulos, arquitetura de aplicação, renderização, gerenciamento de estado e uma estrutura de projeto mais completa.

Assim que o Forkify estiver finalizado, pretendo adicioná-lo a este repositório como o projeto final e mais avançado desta jornada de aprendizado.

## Tecnologias utilizadas nos projetos

- HTML
- CSS
- JavaScript
- Manipulação do DOM
- Arrays e objetos em JavaScript
- Numbers, Dates e Timers em JavaScript
- Programação Orientada a Objetos
- Geolocation API
- Local Storage
- Leaflet
- Parcel

## Rodando um projeto localmente

Cada projeto possui sua própria pasta e seu próprio `package.json`. Para rodar um deles localmente, abra a pasta do projeto no terminal e execute:

```bash
npm install
npm run start
```

Para criar uma build de produção:

```bash
npm run build
```

Para o Netlify, a configuração usual de cada projeto é:

```txt
Build command: npm run build
Publish directory: dist
```
