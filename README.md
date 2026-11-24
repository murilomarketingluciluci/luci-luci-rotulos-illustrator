# Embalagens Nutra Luci Luci

A skill `embalagens-nutra-luciluci` reúne as matrizes editáveis [Base - Rótulo.ai](<modelos/Base - Rótulo.ai>) e [Base - Caixa.ai](<modelos/Base - Caixa.ai>) e suas referências visuais para Adobe Illustrator.

## Instalação

No PowerShell, com Git e Node.js 22.20 ou superior:

```powershell
npx skills add murilomarketingluciluci/luci-luci-rotulos-illustrator
```

Para usar no Codex em todos os projetos:

```powershell
npx skills add murilomarketingluciluci/luci-luci-rotulos-illustrator -g -a codex -y
```

O endereço do repositório mantém o nome original. No seletor de skills e nos pedidos ao agente, use **embalagens-nutra-luciluci**. Quem instalou a versão antiga pelo CLI pode instalar a nova pelo comando acima e remover a antiga no mesmo escopo com `npx skills remove luci-luci-rotulos-illustrator` (acrescente `-g` para uma instalação global). Para atualizar a nova instalação, use `npx skills update embalagens-nutra-luciluci`. A edição do AI requer acesso local ao Illustrator e às fontes da matriz.

## Como usar

1. Anexe os dizeres e os ativos do produto e peça: “Use a skill embalagens-nutra-luciluci para fazer o rótulo de [produto].”
2. Revise a prova e informe qual versão do rótulo o cliente aprovou. O agente exporta o PDF/X-1a:2001 final dessa versão e pergunta se pode fazer a caixa.
3. Autorize a montagem. A caixa usa aquela versão do rótulo, com texto editável, faca e máscara de verniz em prancheta própria. Quando o cliente aprovar a caixa, o agente exporta o PDF/X-1a final com arte e verniz.

O [fluxo completo](SKILL.md) reúne as instruções do [rótulo](rotulos.md) e da [caixa](caixas.md). Para projetos que já tenham um rótulo aprovado, entregue o arquivo e identifique a versão aprovada pelo cliente.
