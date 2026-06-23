# Ilegra AI-Native Engineering Presentations

Este repositório reúne apresentações HTML sobre a abordagem da Ilegra para adoção de Inteligência Artificial na engenharia de software.

O objetivo é disponibilizar decks navegáveis, leves e prontos para apresentação em reuniões internas, conversas executivas e encontros com clientes.

## Apresentações disponíveis

### AI-Native Engineering para desenvolvimento

Arquivo: `playbook-ai-native-engineering.html`

Playbook interno sobre como usar IA no ciclo de desenvolvimento com contexto, especificação, agentes, skills, MCPs, knowledge bases, prompts, gateways, observabilidade, governança, segurança, métricas e melhoria contínua.

### AI-Native Engineering para empresas

Arquivo: `playbook-ai-produto-clientes.html`

Apresentação client-facing da oferta Ilegra para empresas: maturidade, jornada de adoção, portfólio de serviços, arquitetura de referência, guardrails, métricas, ROI, modelos de contratação, demonstrações e próximos passos.

## Página inicial

O arquivo `index.html` funciona como landing page do projeto e referencia as duas apresentações principais.

Para abrir localmente, basta acessar:

```text
index.html
```

Ou abrir diretamente qualquer uma das apresentações HTML no navegador.

## Estrutura

```text
.
├── index.html
├── playbook-ai-native-engineering.html
├── playbook-ai-produto-clientes.html
├── README.md
└── .github/
    └── workflows/
        └── pages.yml
```

## Publicação no GitHub Pages

Este repositório contém um workflow do GitHub Actions para publicar automaticamente o conteúdo estático no GitHub Pages sempre que houver push ou merge na branch `main`.

Para funcionar, o repositório precisa estar configurado em:

```text
Settings → Pages → Source → GitHub Actions
```

Depois disso, cada alteração enviada para `main` publica novamente o site.

## Navegação dos decks

As apresentações suportam:

- Setas do teclado
- Barra de espaço
- Botões de navegação na tela
- Swipe em dispositivos móveis

## Observações

Os decks são arquivos HTML estáticos e não exigem build, servidor ou dependências locais para visualização básica.

Algumas fontes e ícones são carregados por CDN, então a experiência visual completa depende de acesso à internet.
