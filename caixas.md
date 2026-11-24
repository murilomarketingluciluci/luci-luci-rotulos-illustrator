# Caixas Luci Luci no Illustrator

Use [MORO_6_CAIXA_REVISAO.ai](modelos/MORO_6_CAIXA_REVISAO.ai) como matriz estrutural. O rótulo recebido fornece a identidade e os dados do novo produto. Entregue um novo AI com a caixa aberta na primeira prancha e a máscara de verniz correspondente na segunda. Consulte as provas de [arte](referencias/caixas/arte.png) e [verniz](referencias/caixas/verniz.png) para identificar os elementos da matriz.

## Preparar a adaptação

1. Identifique o rótulo de origem, o SKU, a versão e eventuais dizeres específicos da caixa. Registre em memória os campos de conteúdo e as respectivas fontes. Se a ficha e o rótulo divergirem em ingrediente, dose, advertência, peso ou identificação, deixe aquele dado indicado como pendente na prova até a confirmação. Os dados do Moro 6 pertencem somente ao modelo.
2. **AI editável.** Leia o texto na ordem de leitura dos grupos e faces, incluindo estilos por trecho. Reúna as linhas de um mesmo parágrafo mesmo que a origem as armazene em objetos separados. Verifique o resultado com a aparência do rótulo.
3. **PDF em curvas.** Renderize a arte em resolução suficiente para ler a menor nota. Transcreva os dizeres ou use OCR como rascunho e confira visualmente, campo a campo, acentos, decimais, símbolos, unidades, alertas e cada célula da tabela. Preserve logos e ícones em vetor quando disponíveis. Recrie os dizeres como texto vivo na caixa. Se algum trecho estiver ilegível, peça a ficha ou uma fonte melhor e identifique a pendência. Uma imagem do painel ou um grupo de contornos não atende à entrega de texto editável.
4. Copie a matriz para um novo arquivo de trabalho por produto. Confira fontes, vínculos, modo de cor, pranchetas e separações. Preserve medidas de corte e vinco, sangria, aba de cola, abas de fechamento, áreas livres, orientação e escala. A prancheta quadrada contém a planificação inteira. Use os vincos para medir os painéis.
5. Opere a cópia por uma ponte local do Illustrator. Use referência explícita ao documento e aos objetos, sem cliques ou atalhos no desktop do designer. Se for necessário abrir ou ativar abas na sessão em uso, prepare a execução para sessão dedicada ou intervalo combinado. Mantenha a matriz e o rótulo-fonte íntegros.

## Distribuir por face

Na planificação do Moro 6, a partir da aba de cola, a ordem é **frente A → lateral de uso e códigos → frente B → lateral nutricional**.

| Painel | Composição |
| --- | --- |
| Frentes A e B | Logo no alto. Abaixo, “My Routine”, nome e descrição dos ativos alinhados à esquerda. Na faixa branca, denominação, ícones pertinentes, quantidade, massa por unidade e peso líquido conforme o produto. Repetir identidade, escala e alturas nas duas faces. |
| Lateral de uso | Recomendações, conservação e advertências no campo superior. Em seguida, QR, código de barras e reserva de lote e datas. Na faixa branca, fabricação, distribuição e demais identificações aplicáveis. |
| Lateral nutricional | Tabela nutricional na área superior. Ingredientes, alergênicos e atendimento na faixa branca. Conferir a última linha do bloco e as notas da tabela. |
| Tampa | Nome centralizado na face retangular da tampa, delimitada pelos vincos e pela faca. Excluir a lingueta de fechamento da medida. |

**Centralização da marca.** Em cada frente, meça as coordenadas dos dois limites verticais do painel à altura do logo. Calcule o ponto médio e faça coincidir com ele o centro horizontal dos limites visíveis do vetor Luci Luci. Preserve a proporção e a distância ao vinco superior da matriz. Alinhe as duas marcas à mesma altura local, inclusive na face com entalhe. O restante da composição conserva o alinhamento próprio do modelo. Na tampa, conserve a altura do nome e centralize-o entre suas bordas laterais.

Use a cor do SKU nos campos de cor e textos da faixa branca conforme o modelo, preservando os elementos técnicos. Leia os atributos de “My Routine” no AI da caixa e preserve uma eventual especificação expressa do briefing. Ajuste o nome e a descrição nos espaços da caixa sem trazer a escala física ou a faixa lateral da embalagem cilíndrica. Na caixa modelo, o peso líquido está na faixa branca das duas frentes.

## Textos de área por bloco

O Ômega 3 validado no Illustrator serve de referência de edição: **uso/conservação/advertências**, **fabricação/identificação** e **ingredientes/alergênicos/contato** foram compostos como três objetos de texto de área. Na caixa, a divisão segue as faces e os campos gráficos acima. Cada trecho contínuo que o designer revisaria junto deve abrir com um único clique da ferramenta Texto e refluir como um bloco.

- Crie **um `TextFrame` de tipo `TextType.AREATEXT` por bloco corrido**, nomeado pela face e pelo conteúdo, como “Lateral de uso — recomendações e advertências”. Em JSX, use um caminho de área com `textFrames.areaText(caminho)`. Mantenha títulos, parágrafos, endereços e ênfases dentro do mesmo objeto. Aplique negrito por intervalo e espaçamento por parágrafo. Use quebras explícitas para divisões editoriais; deixe a largura da caixa determinar as quebras visuais. Agrupar vários textos de ponto continua deixando uma linha por objeto.
- A descrição multilinha de cada frente também deve refluir em sua caixa. Nome, assinatura, quantidade, peso e nome da tampa podem ser objetos próprios por terem posição e função independentes. Na tabela, mantenha grade vetorial e textos editáveis por célula ou campo; preserve cabeçalhos, colunas, símbolos e notas. Logo, ícones e códigos permanecem objetos vetoriais ou ativos de origem, com proporção e áreas livres preservadas.
- Se um bloco exceder a caixa, amplie somente a borda livre dentro das margens úteis daquela face. Depois ajuste o mínimo de entrelinha e tracking e só então o corpo. Preserve os destaques e a leitura no tamanho de impressão. Não elimine texto para caber.
- **Teste de edição.** Na cópia de trabalho, confira o tipo e o conteúdo de cada bloco. Em uma duplicata temporária, estreite a caixa de um parágrafo longo e observe as palavras passarem para outras linhas dentro do mesmo objeto. Descarte a duplicata. Compare o texto composto visível com todo o conteúdo esperado, inclusive o fim do último parágrafo. Refaça blocos fragmentados, cortados ou com texto excedente antes de entregar.

### Composição da faixa branca das laterais

Na lateral nutricional, siga a [referência aprovada de ingredientes, alérgicos e atendimento](referencias/caixas/lateral-ingredientes.png). A referência define a composição visual. Preencha cada seção com os dizeres aprovados para o produto.

- Mantenha as três seções na mesma caixa de texto de área. Coloque **INGREDIENTES:** em uma linha própria, em negrito, e a composição no parágrafo seguinte, em peso regular. Após a última linha dos ingredientes, inicie **ALÉRGICOS:** em novo parágrafo com espaço antes, para deixar um intervalo visível como na referência. Mantenha o título junto das advertências de alergênicos e glúten aplicáveis, em caixa alta e negrito.
- Inicie **ATENDIMENTO AO CONSUMIDOR:** em outro parágrafo, com um intervalo maior antes do título do que o usado antes de “ALÉRGICOS:”. Coloque sac@luciluci.com.br na linha seguinte, em peso regular. Ajuste o espaço antes dos títulos nos atributos de parágrafo para preservar a separação quando o conteúdo refluir.
- Confira a pontuação no texto recomposto. Remova espaços ou quebras de linha indevidos antes da vírgula. Por exemplo, “gelatina , água” deve ficar “gelatina, água”. Conserve a vírgula junto à palavra anterior e use um espaço depois dela quando o texto continuar na mesma linha. Preserve vírgulas decimais e todos os ingredientes, códigos e unidades do SKU.
- Na prova ao tamanho final, confira o fim e o início de cada linha. Se “gelatina,” ultrapassar a borda por pouco, amplie apenas a borda direita da caixa o mínimo necessário para o conjunto caber, mantendo a origem, o corpo e a margem de segurança até o corte ou vinco. Se faltar largura útil, deixe a palavra inteira passar com a vírgula à linha seguinte. Nenhuma linha deve começar com uma vírgula solta.

Na lateral de fabricação e distribuição, use **FABRICADO POR:** e **DISTRIBUÍDO POR:** em caixa alta e Gotham Bold. Componha nomes das empresas, endereços, CNPJ, origem e notificação em Gotham Book. Para um produto notificado, escreva “Produto notificado pela ANVISA nº [número do SKU]”, mantendo o número completo da ficha.

## Máscara de verniz localizado

Na matriz, as camadas de arte e de verniz do produto são distintas. A segunda prancha contém a referência de faca e vincos, o título técnico e a máscara. O verniz inclui **os dois logos, as duas assinaturas “My Routine”, os nomes e descrições das duas frentes, o nome da tampa e a faixa horizontal**. As laterais com tabela, endereços e códigos ficam fora da cobertura observada.

Gere a máscara **depois de compor o texto final**. Duplique os vetores pertinentes da arte. Para textos, faça o contorno apenas nas cópias técnicas que o modelo representa em curvas. Mantenha texto vivo na arte principal. Reproduza furos, traços e silhuetas visíveis, inclusive o traçado da assinatura quando presente. Substitua a máscara antiga na cópia de trabalho para evitar vestígios do Moro 6.

Translade cada cópia pela diferença de origem entre as duas pranchetas. Conserve escala, orientação e coordenadas **relativas à respectiva prancha**. Use o acabamento da máscara do AI fornecido. A prévia exibe a máscara preta e referências técnicas coloridas. Confira amostras, cobertura e sobreimpressão no arquivo e nas instruções da gráfica antes de afirmar que há uma chapa spot pronta. Preserve as separações de corte `Artios_Cut` e vinco `Artios_Crease`.

## Conferência da entrega

- Compare as duas frentes pelo centro horizontal dos logos, altura, nome, descrição e conteúdo da faixa branca. Verifique a tampa separadamente. Revise todas as faces e abas em busca de texto do produto anterior.
- Confira os blocos como objetos nativos, a leitura da tabela e os códigos contra a origem do novo SKU. Se a entrada veio em curvas, confronte os textos recompostos com a imagem renderizada ou com a ficha aprovada.
- Sobreponha as duas pranchetas pela origem em uma prova temporária. Inspecione bordas do logo, letras finas, descrições, nome da tampa e extremidades da faixa. Confirme que os elementos sem verniz estão livres e que faca e vincos coincidem. Após qualquer alteração na arte, regenere os elementos correspondentes na máscara.
- Entregue o AI editável, indique o rótulo usado e relate campos ou verificações pendentes. Mantenha a condição de prova quando faltar informação para fechar a produção.
