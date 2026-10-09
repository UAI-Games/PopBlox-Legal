# PopBlox-Legal

Documentos legais de **PopBlox** (`com.studioblockwave.blockwave`) — publicados via GitHub Pages.

> ⚠️ **NÃO EDITE OS HTML DIRETAMENTE.** Este repositório é **gerado** por
> `Python/legalkit/generate.py` do `NoGamingKit`. Edição manual some na próxima
> geração. Para mudar: altere o mestre em `legalkit/master/` (vale para todos os
> apps) ou o adendo em `legalkit/games.json` (vale só para este), e regere.

## Publicar

1. **Settings ▸ Pages ▸ Source: Deploy from a branch ▸ `main` / `(root)`**
2. A URL fica `https://UAI-Games.github.io/PopBlox-Legal/`

## URLs para a ficha da Play Store

| Campo do Play Console | URL |
|---|---|
| Política de Privacidade | `https://UAI-Games.github.io/PopBlox-Legal/privacidade.html` |
| Exclusão de conta (Data safety) | `https://UAI-Games.github.io/PopBlox-Legal/exclusao-de-conta.html` |
| Site do desenvolvedor | `https://UAI-Games.github.io/PopBlox-Legal/` |
| E-mail de suporte | `studio.blockwave@gmail.com` |

## Antes de publicar o app — confira

- [ ] Os flags de feature em `games.json` batem com o que o app **realmente faz**
      (hoje: `leaderboard, iap, ads, ads_intersticial, attribution, crash_reports, analytics, analytics_consentimento, cloud_save, seasons, regiao_por_locale, exclusao_no_app`). Data Safety divergente do comportamento real é a causa
      nº 1 de remoção da Play.
- [ ] A política **não** promete ajuste que o app não tem (ranking, apelido,
      fantasma, medição): onde o ajuste não existe, ela manda ao contato.
      Se o app ganhar o ajuste, a flag e o texto mudam junto.
- [ ] Se o jogo tem **conta**, o caminho de exclusão na página
      (`exclusao_caminho`: Configurações → Excluir minha conta) é o que o app mostra hoje.
- [ ] Revisão jurídica feita (veja o aviso ao pé de cada documento).

Estúdio: **NoGaming** · Caixeta Nogueira — Consultoria Financeira LTDA · São Paulo, Brasil · studio.blockwave@gmail.com
