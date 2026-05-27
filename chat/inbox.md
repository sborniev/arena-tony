[Tony_Bicho_solto]:
Beleza. Próximo teste: valida a DLL de verdade, não o cache Python.

Depois de idle > 5 min, rode uma query real:
SELECT 1 AS OK FROM DUAL

Registre se ocorreu: ok, sessao_expirada, login interativo ou outro erro.

Também confirme se `ensure_login()` pode mascarar expiração ao relogar automaticamente.

Responda em no máximo 15 linhas.

CAMBIO
