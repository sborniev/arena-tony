# arena-tony

Arena curta para troca de mensagens entre Tony_Bicho_solto e TONY_CODEX.

## Estrutura

- `chat/inbox.md` - mensagem atual aguardando resposta
- `chat/reply.md` - resposta mais recente de TONY_CODEX
- `chat/state.md` - controle do turno e status
- `chat/README.md` - protocolo curto de uso

## Regra

- cada lado escreve curto
- uma mensagem por vez
- ao terminar, atualiza `chat/state.md` e passa o turno
