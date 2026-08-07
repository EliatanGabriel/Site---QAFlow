# QAFlow

<p align="center">
  <b>Plataforma de gestão de testes de software.</b><br>
  Centralize casos de teste, bugs, automações, métricas e relatórios em um único lugar.
</p>

---

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
│   ├── dashboard.css      # Dashboard
│   ├── projetos.css       # Gestão de projetos
│   ├── casos.css          # Casos de teste
│   ├── bugs.css           # Gestão de bugs
│   ├── demandas.css       # Gestão de demandas
│   ├── sessoes.css        # Sessões de teste
│   ├── evidencias.css     # Evidências de teste
│   ├── relatorios.css     # Relatórios e métricas
│   └── perfil.css         # Perfil do usuário
├── js/
│   └── script.js          # JavaScript principal
├── pages/                 # Páginas internas da aplicação
│   ├── login.html
│   ├── dashboard.html
│   ├── projetos.html
│   ├── casos.html
│   ├── bugs.html
│   ├── demandas.html
│   ├── sessoes.html
│   ├── evidencias.html
│   ├── relatorios.html
│   └── perfil.html
├── docs/
│   ├── README.md          # Documentação da estrutura
│   ├── requisitos.md      # Requisitos funcionais
│   ├── regras-negocio.md  # Regras de negócio
│   └── roadmap.md         # Planejamento de evolução
├── index.html             # Landing page
└── README.md
```

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

| Página       | Caminho               | Descrição                              |
| ------------ | --------------------- | -------------------------------------- |
| Landing page | `index.html`          | Página institucional e de apresentação |
| Login        | `pages/login.html`    | Autenticação de usuários               |
| Dashboard    | `pages/dashboard.html`| Visão geral com métricas e atalhos     |
| Projetos     | `pages/projetos.html` | Gestão de projetos de teste            |
| Casos        | `pages/casos.html`    | Casos de teste                         |
| Bugs         | `pages/bugs.html`     | Registro e acompanhamento de bugs      |
| Demandas     | `pages/demandas.html` | Gestão de demandas                     |
| Sessões      | `pages/sessoes.html`  | Sessões de teste                       |
| Evidências   | `pages/evidencias.html` | Evidências de teste                  |
| Relatórios   | `pages/relatorios.html` | Relatórios e métricas                |
| Perfil       | `pages/perfil.html`   | Perfil do usuário                      |

## Regras de Negócio

- Usuários podem gerenciar múltiplos projetos
- Casos de teste podem ser organizados por suíte
- Bugs são vinculados a casos de teste e projetos
- Relatórios são gerados automaticamente com base nos dados
- Evidências são armazenadas por sessão de teste

Veja a documentação completa em [docs/regras-negocio.md](docs/regras-negocio.md).

## Roadmap

### Fase 1 — MVP
- [x] Estrutura do projeto
- [x] Landing page completa
- [ ] Autenticação (login)
- [ ] CRUD de projetos

### Fase 2
- [ ] Casos de teste
- [ ] Registro de bugs
- [ ] Gestão de demandas

### Fase 3
- [ ] Evidências
- [ ] Relatórios
- [ ] Sessões de teste
- [ ] Perfil do usuário

## Documentação

- [Requisitos funcionais](docs/requisitos.md)
- [Regras de negócio](docs/regras-negocio.md)
- [Roadmap](docs/roadmap.md)

## Licença

Projeto em desenvolvimento. Consulte o mantenedor para informações sobre licenciamento e uso.
