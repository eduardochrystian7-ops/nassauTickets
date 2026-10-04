# nassauTickets

Sistema de controle de atendimento para um Laboratório de Análises Clínicas.

## Objetivo

Permitir a emissão anônima de senhas, o atendimento por guichê e a visualização das chamadas e dos indicadores operacionais.

## Tecnologias

- Ionic React + Capacitor para aplicativo Android/iOS e PWA;
- estado local para a demonstração sem backend.

## Estrutura

- `frontend/`: aplicativo Ionic React com integração Capacitor;
- `docs/`: artefatos de branding, MER, mockups, UML e requisitos;
- `backend/`: reservado para a futura integração de serviços.

## Como executar o frontend

```bash
cd frontend
npm install
npm install
npm run dev
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

## Capacitor (Android)

Após instalar o Android Studio e o SDK Android, sincronize os arquivos web e abra o projeto nativo:

```bash
cd frontend
npm run android
```

Para iOS, execute `npm run ios` em um macOS com o Xcode instalado.

