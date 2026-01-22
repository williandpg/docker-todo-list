<h1><strong>Docker Todo List</strong></h1>

<h2><strong>Descrição</strong></h2>
<p align="justify">
  Projeto focado em conteinerização e orquestração de uma aplicação full stack de tarefas.
  O objetivo é criar imagens para Front end, Back end e um serviço de testes, conectando tudo via docker compose para garantir comunicação entre os containers e funcionamento integrado da aplicação.
</p>

<h2><strong>Funcionalidades</strong></h2>
<ul>
  <li align="justify"><strong>Front end</strong> e <strong>Back end</strong> executando em containers separados.</li>
  <li align="justify"><strong>Rede e serviços orquestrados</strong> via <code>docker-compose.yml</code>, garantindo comunicação entre as partes.</li>
  <li align="justify"><strong>Serviço de testes</strong> em container para validar integração e comunicação entre aplicações.</li>
  <li align="justify"><strong>Comandos Docker documentados</strong> em arquivos individuais <code>commandNN.dc</code>.</li>
</ul>

<h2><strong>Demonstração do Projeto</strong></h2>
<p align="center">
  <em>Projeto sem demonstração visual, pois o foco está na conteinerização e orquestração via Docker.</em>
  <br>
  <a href="https://github.com/williandpg/docker-todo-list" target="_blank"><strong>Acesse o repositório</strong></a>
</p>

<h2><strong>Tecnologias Utilizadas</strong></h2>
<ul>
  <li align="justify">
    <a href="https://www.docker.com/" target="_blank"><strong>Docker</strong></a>:
    criação de imagens, execução de containers e uso de redes e volumes.
  </li>
  <li align="justify">
    <a href="https://docs.docker.com/compose/" target="_blank"><strong>Docker Compose</strong></a>:
    orquestração de múltiplos serviços (front end, back end e testes) em um ambiente único.
  </li>
  <li align="justify">
    <a href="https://docs.docker.com/engine/reference/commandline/cli/" target="_blank"><strong>Docker CLI</strong></a>:
    comandos para inspecionar, construir, executar e gerenciar recursos Docker.
  </li>
</ul>

<h2><strong>Estrutura do Projeto</strong></h2>
<p align="justify">A estrutura base do repositório segue este padrão:</p>
<pre><code>
/
├── docker/
│   ├── docker-commands/    # Arquivos com comandos Docker
│   │   ├── command01.dc
│   │   ├── command02.dc
│   │   └── ...
│   ├── todo-app/           # Aplicação full stack
│   │   ├── back-end/       # Código do back end
│   │   ├── front-end/      # Código do front end
│   │   └── tests/          # Código dos testes automatizados
│   ├── docker-compose.yml
│   └── docker-compose.yml.example
├── jest.config.js
├── package.json
├── package-lock.json
└── README.md
</code></pre>

<h2><strong>Contato</strong></h2>
<p>
  <strong>Willian Gonçalves</strong> |
  <a href="https://www.linkedin.com/in/williandpg/" target="_blank"><strong>LinkedIn</strong></a> |
  <a href="https://github.com/williandpg" target="_blank"><strong>GitHub</strong></a> |
  <a href="https://williandpg.github.io/" target="_blank"><strong>Portfólio</strong></a> |
  <a href="mailto:goncalves.wdp@outlook.com" target="_blank"><strong>Email</strong></a>
</p>

<h2><strong>Créditos</strong></h2>
<p align="justify">
  Projeto desenvolvido como parte da formação em Desenvolvimento Web Full Stack da Trybe, no módulo de Back end, seção de Docker.
</p>

<hr>

<details>
  <summary><strong>English Version</strong></summary>

  <h1><strong>Docker Todo List</strong></h1>

  <h2><strong>Description</strong></h2>
  <p align="justify">
    Docker project focused on containerization and orchestration of a full stack to do application.
    The goal is to build images for Front end, Back end and a test service, connecting everything with docker compose to ensure the containers communicate and the application runs as an integrated system.
  </p>

  <h2><strong>Features</strong></h2>
  <ul>
    <li align="justify"><strong>Front end</strong> and <strong>Back end</strong> running in separate containers.</li>
    <li align="justify"><strong>Orchestrated services</strong> via <code>docker-compose.yml</code>, ensuring communication between components.</li>
    <li align="justify"><strong>Test container</strong> to validate integration and service communication.</li>
    <li align="justify"><strong>Docker commands</strong> documented in individual <code>commandNN.dc</code> files.</li>
  </ul>

  <h2><strong>Project Demo</strong></h2>
  <p align="center">
    <em>No visual demo available, as the focus is on containerization and orchestration using Docker.</em>
    <br>
    <a href="https://github.com/williandpg/docker-todo-list" target="_blank"><strong>Open the repository</strong></a>
  </p>

  <h2><strong>Technologies Used</strong></h2>
  <ul>
    <li align="justify">
      <a href="https://www.docker.com/" target="_blank"><strong>Docker</strong></a>:
      image building, container execution, networks and volumes.
    </li>
    <li align="justify">
      <a href="https://docs.docker.com/compose/" target="_blank"><strong>Docker Compose</strong></a>:
      multi service orchestration (front end, back end and tests) as a single environment.
    </li>
    <li align="justify">
      <a href="https://docs.docker.com/engine/reference/commandline/cli/" target="_blank"><strong>Docker CLI</strong></a>:
      commands to inspect, build, run and manage Docker resources.
    </li>
  </ul>

  <h2><strong>Project Structure</strong></h2>
  <p align="justify">The repository follows this base structure:</p>
  <pre><code>
  /
  ├── docker/
  │   ├── docker-commands/    # Files with Docker commands
  │   │   ├── command01.dc
  │   │   ├── command02.dc
  │   │   └── ...
  │   ├── todo-app/           # Aplication full stack
  │   │   ├── back-end/       # Back end code
  │   │   ├── front-end/      # Front end code
  │   │   └── tests/          # Automated tests code
  │   ├── docker-compose.yml
  │   └── docker-compose.yml.example
  ├── jest.config.js
  ├── package.json
  ├── package-lock.json
  └── README.md
  </code></pre>

  <h2><strong>Contact</strong></h2>
  <p>
    <strong>Willian Gonçalves</strong> |
    <a href="https://www.linkedin.com/in/williandpg/" target="_blank"><strong>LinkedIn</strong></a> |
    <a href="https://github.com/williandpg" target="_blank"><strong>GitHub</strong></a> |
    <a href="https://williandpg.github.io/" target="_blank"><strong>Portfolio</strong></a> |
    <a href="mailto:goncalves.wdp@outlook.com" target="_blank"><strong>Email</strong></a>
  </p>

  <h2><strong>Credits</strong></h2>
  <p align="justify">
    This project was developed as part of Trybe Full Stack Web Development program, Back end module, Docker section.
  </p>
</details>