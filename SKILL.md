---
name: embalagens-nutra-luciluci
description: Cria embalagens de suplementos Luci Luci no Adobe Illustrator. Começa pelo rótulo, acompanha a aprovação do cliente e, com autorização de Murilo, adapta o rótulo aprovado para uma caixa editável com faca e verniz localizado.
---

# Embalagens Nutra Luci Luci

## 1. Criar e revisar o rótulo

Use o [guia de rótulos](rotulos.md) e a [Base - Rótulo.ai](<modelos/Base - Rótulo.ai>) para produzir o AI editável e uma prova visual identificada pelo produto e pela versão. Entregue a prova a Murilo para aprovação do cliente. Nesse ponto, aguarde o retorno. Se o cliente pedir ajustes, aplique-os ao rótulo, entregue uma nova prova e aguarde a aprovação dessa versão.

## 2. Exportar o rótulo aprovado e perguntar pela caixa

Aceite o retorno de Murilo de que o cliente aprovou o rótulo. Vincule a aprovação ao produto e à versão entregue. Se ele já trouxer um AI ou PDF em curvas aprovado, use esse arquivo e retome daqui. Se houver várias versões e estiver incerto qual o cliente aprovou, esclareça antes de avançar.

Quando o cliente aprovar, gere e entregue o **PDF/X-1a final do rótulo** conforme o fechamento abaixo, mesmo que o trabalho termine no rótulo. A aprovação da versão já autoriza essa exportação. Pergunte a Murilo: **“Posso fazer a caixa de [produto] usando o rótulo [versão] que o cliente aprovou?”** Aguarde a resposta antes de abrir uma cópia da matriz de caixa ou iniciar a montagem. Um pedido inicial para produzir as duas peças mantém esta etapa de confirmação após a aprovação.

Se Murilo já comunicar as duas decisões na mesma mensagem, por exemplo “o cliente aprovou a v3, pode fazer a caixa”, prossiga diretamente. Se ele solicitar uma mudança de conteúdo no rótulo aprovado antes da montagem, volte à revisão do rótulo e confirme a versão que deverá seguir para a caixa.

## 3. Fazer a caixa autorizada

Com a aprovação e a autorização confirmadas, execute o [guia de caixas](caixas.md). Use o **arquivo exato do rótulo aprovado** como fonte de dados e identidade. Use a [Base - Caixa.ai](<modelos/Base - Caixa.ai>) para a estrutura, as faces e o verniz. Aplique a distribuição de conteúdo própria de cada peça, inclusive a posição do SAC. Mantenha os textos corridos em caixas de texto de área e confira o registro da máscara com a arte final.

Entregue o novo AI editável e a prova da caixa, identificando o produto e a versão do rótulo que lhe deu origem. A aprovação do cliente registrada na etapa 2 vale para o rótulo; a caixa segue para sua própria revisão.

## 4. Exportar a caixa aprovada

Quando Murilo confirmar a aprovação da caixa pelo cliente, gere e entregue o **PDF/X-1a final da caixa** a partir daquela versão. Inclua a arte e a máscara de verniz em registro como nas duas pranchetas da matriz. Se a gráfica pedir o verniz em arquivo separado, exporte dois PDFs com a mesma escala, origem relativa e enquadramento.

## Fechamento em PDF/X-1a para as duas peças

1. Trabalhe em uma cópia da versão aprovada e preserve o AI editável. Use o preset real **PDF/X-1a:2001** do Illustrator, ou a variante PDF/X-1a especificada pela gráfica. Em JSX, consulte os nomes instalados em `app.PDFPresetsList` e use a predefinição correspondente em `PDFSaveOptions.pDFPreset`. Se faltar o preset ou requisitos do arquivo impedirem o fechamento, sinalize a pendência antes de identificar a saída como final.
2. No rótulo, enquadre pelo corte em tamanho real e aplique a sangria definida para o trabalho. Cotas, saída do rolo e anotações da folha de apresentação ficam na prova, salvo orientação expressa da gráfica. Na caixa, preserve o tamanho da planificação, a sangria e a correspondência das duas pranchas. Use o perfil CMYK de saída da produção e preserve tintas especiais, faca, vincos e sobreimpressões conforme a especificação da gráfica. Mantenha a representação da máscara de verniz acordada.
3. Identifique os arquivos por produto, peça, versão aprovada e padrão, por exemplo `Produto - Rótulo - v03 - PDF-X1a.pdf`. Reabra o PDF exportado, confira o corte, a sangria, a quantidade de páginas, as separações e a aparência contra a prova aprovada. Verifique o registro da máscara na caixa. Execute a verificação de conformidade PDF/X-1a no Acrobat Preflight ou ferramenta equivalente quando disponível e informe se essa verificação ficou pendente. Se a arte mudar depois da aprovação, trate a alteração como nova versão.
