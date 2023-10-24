## Access token:

**Pra que serve?**

- Pegar qualquer tipo de informação do usuário
- Atualizar qualquer tipo de informação do usuário
- Inserir qualquer tipo de informação do usuário
- Deletar qualquer tipo de informação do usuário

**Duração**

- Dura pouco tempo/ O mínimo possível

**Risco se vazar**

- Quanto maior o tempo de vida dele, maior o estrago que quem tiver o token pode fazer

## Refresh token:

**Pra que serve?**

- Para não precisar pedir a senha e usuário para gerar um novo access_token

**Duração**

- Longa
- O refresh token a nivel de backend está associado ao usuário de alguma forma

**Risco se vazar**

- Se ele vazar, o usuário novo pode gerar tokens INFINITOS (access tokens, refresh tokens)
- Precisa ter alguma forma de invalidar os refresh tokens
