# Biblioteca de rótulos Luci Luci

Esta biblioteca reúne a skill de produção, o modelo editável de Ômega 3 e cinco referências visuais. Cada designer recebe uma cópia local e pode criar rótulos no Illustrator sem baixar a base a cada trabalho.

## Instalar pelo PowerShell

Com Node.js 22.20 ou superior e Git instalados, abra o PowerShell na pasta do projeto e execute:

```powershell
npx skills add murilomarketingluciluci/luci-luci-rotulos-illustrator
```

O pacote inclui a skill, a matriz do Illustrator e as imagens de referência. Para instalar diretamente no Codex e usar em todos os projetos:

```powershell
npx skills add murilomarketingluciluci/luci-luci-rotulos-illustrator -g -a codex -y
```

Abra um novo chat e peça: “Use a skill luci-luci-rotulos-illustrator. Crie uma cópia do modelo da biblioteca para este produto e aplique a ficha anexa.” A edição no Illustrator requer uma ponte de automação local e as fontes usadas pela matriz.

Para atualizar uma instalação feita pelo CLI:

```powershell
npx skills update luci-luci-rotulos-illustrator
```

Se você já instalou por clonagem do Git, pode continuar atualizando com `git pull --ff-only` dentro da pasta clonada.

## Modelos e referências

O modelo em `modelos/OMEGA 3 - Caixas de texto.ai` é o arquivo de trabalho indicado por Murilo. Crie os rótulos fora da pasta da biblioteca para manter a matriz pronta para o próximo trabalho. O arquivo traz o texto lateral de peso líquido e via de uso. Confira QR, EAN e saída do rolo na cópia de cada produto, conforme o [procedimento da skill](SKILL.md).

Para ampliar a biblioteca, acrescente o arquivo editável aprovado para distribuição pública em `modelos/`, preserve eventuais vínculos e registre em `SKILL.md` quando escolher esse modelo. Inclua exemplos visuais em `referencias/`. Depois de publicar a alteração, a equipe pode atualizar a instalação.
