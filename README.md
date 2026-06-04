# 🎓 Treinamento Scrum Code[] Academy

Uma plataforma interativa, moderna e de alta fidelidade desenvolvida para capacitar equipes da **Code[]** nos fundamentos, valores, segredos e práticas recomendadas do **Scrum Framework**, totalmente alinhada ao **Scrum Guide 2020 Oficial**.

Este portal educacional transforma teoria densa em uma experiência prática, otimizada para estudo fluido, com recursos visuais excepcionais e um mecanismo de quiz integrado e altamente intuitivo.

---

## 🎨 Design & Proposta Visual

O portal foi concebido sob a estética **Bento Grid** moderna, inspirando-se em conceitos industriais e espaciais de ponta:

*   **Identidade Visual (Cosmic Slate Theme):** Uma interface em modo escuro profundo baseada em tons de zinco mineral (`#09090b` ao `#18181b`), combinada com acentos sutis em Indigo (`#6366f1`), Emerald (`#10b981`) para elementos de sucesso, e Amber (`#f59e0b`) para alertas e interações adicionais.
*   **Tipografia Refinada:** Uma cuidadosa combinação de **Space Grotesk** para displays e cabeçalhos marcantes, **Inter** para leitura limpa e de alta legibilidade, e **JetBrains Mono** para indicações técnicas, métricas e estatísticas.
*   **Arquitetura Responsiva Fluida:** Uma experiência perfeitamente otimizada para todas as telas (Desktops Ultra-wide, Laptops, Tablets e Smartphones) assegurando o redimensionamento fluido de cartões, espaçamentos internos adequados e leitura sem quebras involuntárias.

---

## 🚀 Principais Funcionalidades

### 📖 1. Trilha de Estudo Interativa (Scrum Guide 2020)
*   **Barra de Leitura Dinâmica:** Um indicador visual localizado no topo acompanha o progresso de rolagem em tempo real, incentivando o usuário a ler cada seção em profundidade.
*   **Navegação Inteligente Lateral (Sidebar):** Permite saltar rapidamente entre as subseções-chave da teoria:
    1.  **Início:** Painel bento introdutório com métricas de estudo.
    2.  **O que é Scrum?:** Definição concisa e direta ao ponto.
    3.  **Teoria do Scrum:** Pilares empíricos (Transparência, Inspeção, Adaptação).
    4.  **Valores:** Foco, Respeito, Abertura, Coragem e Compromisso descritos com interações dinâmicas.
    5.  **Time Scrum:** Entenda as responsabilidades do Product Owner, Scrum Master e Desenvolvedores.
    6.  **Eventos:** Detalhes de Sprint, Sprint Planning, Daily Scrum, Sprint Review e Sprint Retrospective.
    7.  **Artefatos:** Product Backlog (Meta do Produto), Sprint Backlog (Meta da Sprint) e Incremento (Definição de Pronto).
    8.  **Glossário:** Termos técnicos essenciais para referência ágil a qualquer momento.

### 📊 2. Diagrama Interativo do Ciclo Scrum
*   Um vetor moderno integrado e responsivo que ilustra visualmente a cronologia dos eventos Scrum, permitindo correlacionar as fases teóricas com o fluxo operacional do dia a dia de forma simplificada.

### 📝 3. Módulo de Quiz Independente (Página Separada)
Atendendo ao feedback de uso e melhores práticas de UI, o **Quiz interativo foi isolado em uma página própria**, controlada dinamicamente via Hash Router (`#quiz`).
*   **Foco Total:** Toda a barra de rolagem e conteúdos de leitura teórica são ocultados para que o estudante possa focar exclusivamente nas questões.
*   **Métricas em Tempo Real:** Acompanhamento dinâmico de acertos, erros e o progresso de questões restantes.
*   **Feedback Imediato:** Explicações claras e detalhadas após cada resposta com correções cromáticas em Emerald e Crimson.
*   **Painel de Revisão de Erros:** Um sumário ao final da sessão permite focar nos pontos fracos e repassar as resoluções detalhadas com base no Scrum Guide.

---

## 🛠️ Tecnologias Utilizadas

A aplicação utiliza uma refinada pilha minimalista de desenvolvimento web sob os padrões de ecossistema moderno:

*   **HTML5 / CSS3 (Variações Bento Customizadas)** – Estrutura robusta, animações de entrada suaves e layouts flexíveis adaptados para mobile.
*   **Vite** – Motor de build ultra-rápido focado em desenvolvimento ágil de aplicações front-end modernas.
*   **JavaScript (ES6+)** – Controle reativo de estados de navegação, gerenciamento dinâmico de roteamento interno, lógica completa de cálculo e feedback do Quiz.
*   **Inter, Space Grotesk & JetBrains Mono** – Fontes oficiais importadas do Google Fonts para suporte estético unificado.

---

## 💻 Configuração e Desenvolvimento

### Pré-requisitos
*   [Node.js](https://nodejs.org/) (versão 18 ou superior recomendada)
*   NPM (geralmente empacotado junto com o Node.js)

### Passos para executar localmente

1.  **Clone o diretório do projeto** ou extraia o arquivo zip.
2.  Instale as dependências executando o comando a partir do diretório raiz:
    ```bash
    npm install
    ```
3.  Inicie o servidor de desenvolvimento local:
    ```bash
    npm run dev
    ```
4.  Abra seu navegador no endereço indicado (geralmente [http://localhost:3000](http://localhost:3000)).

### Outros Scripts Disponíveis

*   `npm run build`: Compila o portal para arquivos de produção estáticos otimizados na pasta `./dist`.
*   `npm run preview`: Inicializa um servidor prévio para testar os pacotes de produção gerados.
*   `npm run lint`: Executa checagens estáticas rápidas baseadas no compilador TypeScript para garantir estabilidade sintática.

---

## 📝 Compromisso Técnico Code[] Academy
Este portal reflete o compromisso com a engenharia de software pragmática, prezando por layouts limpos, tipografias ricas, espaçamentos respiráveis e ausência intencional de poluentes visuais ou distrações técnicas não requeridas.

---
*Feito com rigor e paixão pela excelência ágil na **Code[] Academy**.*
