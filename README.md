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
|-----------------------------------------------------------|
| Crysthian Eduardo Santos Sousa | 01862423 | Scrum Master |
| Heytor Farias Fernando da Silva | 01857126 | Documentador |
| Jair Liberato da Silva Filho | 01864955 | Testador |
| Luiz Vinicius da Silva Cavalcanti | 01863636 | Desenvolvedor |
| Marcelo Nascimento Da Silva | 01865122 | Desenvolvedor |
| Thiago Henrique Dos Santos Medino Rodrigues | 01864917 | Desenvolvedor |

## Branches

- `main`: versão estável;
- `dev`: desenvolvimento e integração das funcionalidades.

##  Regras de Negócio e Senhas

O sistema gerencia três tipos principais de atendimento, respeitando a seguinte ordem de prioridade na fila:
1. **SP (Prioritário):** Gestantes, idosos, PCDs e casos de urgência leve.
2. **SE (Exames):** Coleta de sangue, entrega de materiais e triagem laboratorial.
3. **SG (Geral):** Informações, cadastros e retirada de laudos.

## Capacitor (Android)

Após instalar o Android Studio e o SDK Android, sincronize os arquivos web e abra o projeto nativo:

```bash
cd frontend
npm run android
```

Para iOS, execute `npm run ios` em um macOS com o Xcode instalado.

