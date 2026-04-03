# Underdark Gems Homebrew Repo

Repositório inicial de gemas do Subterrâneo, focado em personagens de nível 1–3 para **Out of the Abyss**.

## O que vem aqui

- `data/5etools/gems-level1-3.json`
  - arquivo de homebrew para carregar no **5e.tools**
- `data/foundry/sc-simple-sockets-level1-3.json`
  - arquivo de itens **Foundry-native** com flags do **SC - Simple Sockets**
- `docs/gem-reference.md`
  - referência rápida das famílias de gemas

## Importar no 5e.tools

1. Suba este repositório no GitHub.
2. Abra o arquivo `data/5etools/gems-level1-3.json`.
3. Clique em **Raw**.
4. Copie a URL `raw.githubusercontent.com/...`.
5. No 5e.tools, abra **Manage Homebrew** e importe pela URL.

## Importar no Foundry

### Opção A — via 5e.tools / Plutonium
Boa para criar os itens base no Foundry.

### Opção B — via JSON Foundry-native
Use `data/foundry/sc-simple-sockets-level1-3.json` com **Import Data** em um compendium de Item.

## Limitação importante

O fluxo **5e.tools → Foundry** normalmente importa bem os **itens base**, mas **não preserva de forma confiável flags específicas de módulos de Foundry**, como as flags do **SC - Simple Sockets**.

Por isso este repo inclui **duas versões**:
- uma para **5e.tools**
- outra para **Foundry + Shattered Codex**

## Estrutura inicial

- 12 famílias de gema
- 3 tiers por família
- total: **36 gemas**
- foco maior em **Chipped** e **Shard**, para campanha nível 1–3

## Próximos passos sugeridos

- Pack nível 4–6
- Pack corrompido por Faerzress
- Gemas de Lolth / Velkynvelve
- Hosts socketáveis prontos para SC - Simple Sockets
- Sets para **SC - Setforge**
- Progressão para **SC - Ascendant Items**
