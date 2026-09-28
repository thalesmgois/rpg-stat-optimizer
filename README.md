# RPG Stat Optimizer

Ferramenta web, em português, para testar e otimizar a distribuição de pontos de atributos entre diferentes heróis.

## Recursos

- Uma aba independente para cada herói.
- Nome, nível e pontos disponíveis configuráveis.
- Base, equipamento e crescimento por ponto configuráveis para cada status.
- Cálculo de DPS esperado, defesa efetiva e EHP aproximado.
- Otimização por objetivo: DPS, defesa efetiva, sobrevivência equilibrada ou DPS + defesa.
- Distribuição manual ou automática.
- Salvamento automático no navegador (`localStorage`).
- Funciona sem servidor e pode ser hospedada no GitHub Pages.

## Uso

Abra `index.html` no navegador. A ferramenta já vem com um Cavaleiro de exemplo baseado nos prints enviados, mas todos os valores podem ser alterados.

> As fórmulas são editáveis no código em `app.js`, pois cada RPG pode interpretar bloqueio, esquiva, crítico e defesa de maneira diferente.

## Publicar no GitHub Pages

1. Acesse **Settings → Pages**.
2. Selecione a branch `main` e a pasta `/ (root)`.
3. Salve e abra a URL fornecida pelo GitHub.
