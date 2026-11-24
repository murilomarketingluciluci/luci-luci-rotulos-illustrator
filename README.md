# Biblioteca de rótulos Luci Luci

Esta biblioteca reúne a skill de produção, o modelo editável de Ômega 3 e cinco referências visuais. Cada designer recebe uma cópia local e pode criar rótulos no Illustrator sem baixar a base a cada trabalho.

## Instalar no Codex pelo PowerShell

Em um computador com Git e GitHub CLI, entre em uma conta com acesso a este repositório privado usando `gh auth login`. Para instalar no diretório padrão de skills do Codex, execute:

```powershell
gh repo clone murilomarketingluciluci/luci-luci-rotulos-illustrator "$env:USERPROFILE\.codex\skills\luci-luci-rotulos-illustrator"
```

Se você configurou `CODEX_HOME`, use a pasta `skills` dessa instalação como destino. Abra um novo chat e peça: “Use a skill luci-luci-rotulos-illustrator. Crie uma cópia do modelo da biblioteca para este produto e aplique a ficha anexa.”

Para atualizar uma instalação feita pelo Git:

```powershell
git -C "$env:USERPROFILE\.codex\skills\luci-luci-rotulos-illustrator" pull --ff-only
```

Se já existir uma pasta da skill instalada manualmente, guarde-a com outro nome antes da primeira clonagem. Para outro agente, clone a biblioteca em uma pasta local e indique o caminho de `SKILL.md`. A edição no Illustrator requer uma ponte de automação local e as fontes usadas pela matriz.

## Modelos e referências

O modelo em `modelos/OMEGA 3 - Caixas de texto.ai` é o arquivo de trabalho indicado por Murilo. Crie os rótulos fora da pasta da biblioteca para manter a matriz pronta para o próximo trabalho. O arquivo traz o texto lateral de peso líquido e via de uso. Confira QR, EAN e saída do rolo na cópia de cada produto, conforme o [procedimento da skill](SKILL.md).

Para ampliar a biblioteca, acrescente o arquivo editável aprovado em `modelos/`, preserve eventuais vínculos e registre em `SKILL.md` quando escolher esse modelo. Inclua exemplos visuais em `referencias/`. Depois de publicar a alteração no repositório privado, cada pessoa recebe a nova versão com o comando de atualização acima.
