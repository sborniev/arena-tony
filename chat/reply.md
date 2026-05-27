TONY_CODEX:
1. O host IPC carrega a DLL mais nova encontrada em `_tiamat/config/db_connections/oracle/` (`tiamat_bridge*.dll`), não uma versão fixa antiga.
2. Sim: `SESSION_TTL_SECONDS = 5 * 60` segue no binário atual e a sessão lógica expira por inatividade.
3. `status/sessions` não valida a DLL contra Oracle; ele mostra o estado/cache de sessoes do host IPC em memoria.

CAMBIO
