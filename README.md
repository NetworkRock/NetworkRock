<style>
  header {
    left: -10em;
    display: flex;
    flex: 1;
    align-items: center;
    justify-content: center;
    margin-bottom: 1em;
    position: relative;
    animation: swoosh ease-in-out 0.8s;
    animation-fill-mode: forwards;
  }

  #aboutMe, footer {
    display: flex;
    flex: 1;
    flex-direction: column
  }

  main {
    display: flex;
    flex-direction: row;
    left: -100em;
    padding: 1em;
    position: relative;
    animation: swoosh 0.8s ease-in-out;
    animation-delay: 0.8s;
    animation-fill-mode: forwards;
  }

  #projects {
    flex: 1;
  }
  
  #learn {
    flex: 1;
  }

  @keyframes swoosh {
    0% {
      left: -100em;
    }

    100% {
      left: 0em;
    }
  }

  h1 {
    font-size: 50px;
    text-transform: uppercase;
  }

  p {
    font-size: 20px;
    text-shadow: 0 1px 0 #efefef;
  }
</style>

<header>
  <img height='300em'
    src="https://sdk.bitmoji.com/render/panel/e0c8b93f-c246-46e8-9db2-ec0cb01ec9eb-8ca98e33-a1e4-44a8-820d-1d5bf7bf6d30-v1.png?transparent=1&palette=1">
  <div id='aboutMe'>
    <h1>About me!</h1>
    <span>
      I am a fullstack developer who is specialized in mobile, web and enterprise applications. Agile software
      development, analysis and design, system architecture, coding/programming, implementation and testing describe my
      daily work!
    </span>
  </div>
</header>

<main>
  <section id='projects'>
    <h2>Private projects 💻</h2>
    <ul>
      <li>Poker Poll</li>
      <li>Personal website</li>
      <li>Stockmanager (secret repo)</li>
    </ul>
  </section>
  <section id='learn'>
    <h2>I’m interested in 👀</h2>
    <ul>
      <li>How to code really good and clean</li>
      <li>Typescript</li>
      <li>React</li>
      <li>React-Native</li>
      <li>Redux</li>
      <li>ESLint</li>
      <li>Firebase</li>
      <li>GraphQL</li>
      <li>Node</li>
    </ul>
  </section>
    <footer>
    <h2>🌱 I’m currently learning</h2>
    <li>How to type really fast</li>
    <li>Socket.io</li>

  <h2>📫 How to reach me</h2> https://www.linkedin.com/in/robin-leeb-838746208/
  </footer>
</main>

