# Ilex Logistica - Organizacao GitHub

Plataforma web para rastreio automatizado de entregas, identificacao de atrasos e tratamento de excecoes operacionais.

## Verdade oficial de planejamento

- Janela oficial da Sprint 1: **12/05/2026 a 23/05/2026**.
- Owner do projeto: `ilex-logistica`.
- Project oficial: `Ilex Logistica - Roadmap 60 dias (12/05 a 11/07/2026)`.
- Regras obrigatorias de rastreio em todas as issues e PRs:
  - `Epic (Docs)`
  - `Issue de origem (Docs)`
  - `Sprint/Milestone`

## Mapa de repositorios

| Repositorio | Responsabilidade | Stack principal |
|---|---|---|
| `Api` | API principal, regras de SLA, excecoes, alertas e relatorios | FastAPI, SQLAlchemy, PostgreSQL |
| `Web` | Dashboard e operacao logistica web responsiva | Next.js, TypeScript, Tailwind |
| `Infra` | Ambientes, containerizacao, CI/CD e observabilidade | Docker, Nginx, GitHub Actions |
| `Integrations` | Conectores de transportadoras e adaptadores | Python workers, clients de API |
| `Docs` | Escopo, sprints, guias tecnicos e materiais de operacao | Markdown |
| `.github` | Governanca, templates e padroes globais | GitHub Templates/Docs |

## Fluxo Scrum oficial

1. Planning:
- validar backlog da sprint no `Docs`;
- confirmar rastreio (`Epic`, `Issue origem`, `Milestone`) antes de iniciar execucao.

2. Daily:
- atualizar status de cards no Project (`Todo`, `In Progress`, `Done`);
- registrar impedimentos e proximas acoes.

3. Review:
- validar criterios de aceite por tarefa;
- checar evidencias (tests, logs, links de PR/issue).

4. Retro:
- registrar aprendizados e acoes de melhoria na trilha de documentacao da sprint.

## Milestones de sprint

Todos os repositorios de execucao usam milestones sincronizadas:

- Sprint 01 - Fundacao do MVP (2026-05-12 a 2026-05-23)
- Sprint 02 - Coleta e Monitoramento (2026-05-26 a 2026-06-06)
- Sprint 03 - Operacao e Eficiencia (2026-06-09 a 2026-06-20)
- Sprint 04 - Relatorios e Integracoes (2026-06-23 a 2026-07-04)
- Sprint 05 - Cotacao e Go-Live (2026-07-07 a 2026-07-11)

## Convencao de commits

`<tipo>(<repo>): <ID> <resumo em pt-BR>`

Exemplos:

- `docs(api): A-09 publica contrato tecnico da fundacao`
- `feat(web): B-07 cria formulario de transportadoras`
- `chore(infra): C-03 habilita pipeline CI inicial`

## Referencias

- Escopo base: `ESCOPO_PROJETO_ILEX_LOGISTICA.pdf`
- Apendice: `APENDICE_1_ILEX_LOGISTICA_SOLICITACOES_CLIENTE.pdf`
- Rastreio central da sprint: `Docs/sprints/2026-05-12_2026-05-23/`
