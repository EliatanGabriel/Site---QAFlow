# QAFlow

> Plataforma de gestão de testes de software.
> Centralize casos de teste, bugs, automações, métricas e relatórios em um único lugar para equipes de QA e desenvolvimento.

## Sobre o Projeto

O **QAFlow** é uma plataforma web voltada para equipes de QA e desenvolvimento que desejam organizar todo o ciclo de qualidade de software em um só lugar. Com ele é possível gerenciar projetos de teste, criar e executar casos de teste, registrar bugs, acompanhar demandas, armazenar evidências e gerar relatórios e métricas automaticamente.

## Funcionalidades

- **Gestão de projetos** — cadastro e organização de múltiplos projetos de teste
- **Casos de teste** — criação, organização por suíte e execução
- **Gestão de bugs** — registro, vinculação a casos de teste e acompanhamento
- **Demandas** — gestão de tarefas e solicitações
- **Evidências de teste** — armazenamento por sessão de teste
- **Sessões de teste** — controle das execuções realizadas
- **Relatórios e métricas** — geração automática com base nos dados
- **Perfil do usuário** — gestão de dados pessoais e preferências
- **Autenticação** — login de acesso à plataforma

## Tecnologias

- **HTML5** — estrutura e marcação
- **CSS3** — estilização, design system via variáveis CSS e responsividade
- **JavaScript** — interatividade e comportamentos da aplicação

## Como Executar

Não é necessário instalar dependências — o projeto é 100% estático.

1. Clone o repositório:

   ```bash
   git clone <url-do-repositorio>
   cd "Site - QAFlow"
   ```

2. Abra o arquivo `index.html` no navegador, ou sirva a pasta com um servidor local:

   ```bash
   # Opção A: Python
   python -m http.server 8000

   # Opção B: Node.js
   npx serve .
   ```

3. Acesse `http://localhost:8000` no navegador.

## Páginas

| Página       | Caminho                | Descrição                              |
| ------------ | ---------------------- | -------------------------------------- |
| Landing page | `index.html`           | Página institucional e de apresentação |
| Login        | `pages/login.html`     | Autenticação de usuários               |
| Dashboard    | `pages/dashboard.html` | Visão geral com métricas e atalhos     |
| Projetos     | `pages/projetos.html`  | Gestão de projetos de teste            |
| Casos        | `pages/casos.html`     | Casos de teste                         |
| Bugs         | `pages/bugs.html`      | Registro e acompanhamento de bugs      |
| Demandas     | `pages/demandas.html`  | Gestão de demandas                     |
| Sessões      | `pages/sessoes.html`   | Sessões de teste                       |
| Evidências   | `pages/evidencias.html`| Evidências de teste                    |
| Relatórios   | `pages/relatorios.html`| Relatórios e métricas                  |
| Perfil       | `pages/perfil.html`    | Perfil do usuário                      |

## Estrutura do Projeto

```
QAFlow/
├── assets/
│   └── img/               # Imagens, logos e favicon
├── css/
│   ├── style.css          # Estilos base (variáveis, reset, landing, responsivo)
│   ├── variables.css      # Design tokens (cores, raios, sombras, transições)
│   ├── global.css         # Reset e estilos globais
│   ├── landing.css        # Estilos da landing page
│   ├── responsive.css     # Media queries
│   ├── login.css          # Página de login
│   └── ...                # Estilos por página
├── js/
│   └── script.js          # JavaScript principal
├── pages/                 # Páginas internas da aplicação
│   ├── login.html
│   ├── dashboard.html
│   └── ...
├── docs/                  # Documentação do projeto
├── index.html             # Landing page
└── README.md
```

## Documentação

- [Estrutura e guia](docs/README.md)
- [Requisitos funcionais](docs/requisitos.md)
- [Regras de negócio](docs/regras-negocio.md)
- [Roadmap](docs/roadmap.md)

## Licença

Projeto em desenvolvimento. Consulte o mantenedor para informações sobre licenciamento e uso.