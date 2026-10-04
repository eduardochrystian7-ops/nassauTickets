# nassauTickets

Sistema de controle de atendimento para um Laboratório de Análises Clínicas.

## Objetivo

Permitir a emissão anônima de senhas, o atendimento por guichê e a visualização das chamadas e dos indicadores operacionais.

## Tecnologias

- React Native + Expo no aplicativo móvel;
- estado local no dispositivo para a demonstração sem backend.

## Estrutura

- `frontend/`: aplicativo React Native executável;
- `docs/`: artefatos de branding, MER, mockups, UML e requisitos;
- `backend/`: reservado para a futura integração de serviços.

## Como executar o frontend

```bash
cd frontend
npm install
npm start
```

## Funcionalidades demonstradas

- emissão de senhas SP, SE e SG com numeração `YYMMDD-PPSQ`;
- fila local com prioridade SP → SE → SG;
- fluxo de chamada, início, rechamada e finalização do atendimento;
- painel das cinco últimas chamadas;
- resumo diário e trilha de auditoria.

## Membros

| Nome | Matrícula | Papel |
|---|---|---|
| A definir | A definir | Scrum Master |

## Branches

- `main`: versão estável;
- `dev`: desenvolvimento e integração das funcionalidades.

