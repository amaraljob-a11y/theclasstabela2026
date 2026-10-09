# The Class Professional: Orçamento rápido 2026

Painel para montar orçamentos na hora, com a tabela de preços 2026 da The Class Professional.

## Como abrir

Dê dois cliques no arquivo `index.html`. Ele abre no navegador e funciona sem internet. Não precisa instalar nada.

## O que o painel faz

- Escolhe o tipo de cliente: Distribuidor, Profissional (salão) ou Cliente final.
- Escolhe a região: RJ Baixada/Centro, Região II ou Região III. Para Cliente final existem duas tabelas: Cliente final e Cliente final Região III.
- Aplica o preço de caixa fechada quando a quantidade chega ao tamanho da caixa.
- Tem a opção de desconto exclusivo para Profissional na RJ.
- Soma o orçamento, aceita desconto adicional, nome do cliente e observações.
- Copia o orçamento em texto para o WhatsApp ou imprime em PDF.
- Limpa o orçamento com um botão, com opção de desfazer.
- Tem modo dia e modo noite.
- Guarda o orçamento em andamento no próprio aparelho.

## Regras de preço

- **Distribuidor:** tabela única. Caixa fechada tem 15% de desconto.
- **Profissional RJ Baixada/Centro:** caixa fechada tem 15% de desconto. A condição de desconto exclusivo dá 20% abaixo da tabela RJ e não tem preço de caixa.
- **Profissional Região II:** caixa fechada tem 10% de desconto.
- **Profissional Região III:** tem tabela própria de caixa fechada.
- **Cliente final:** preço sugerido, sem desconto de caixa.
- **Produtos só para distribuidor e profissional:** 31 produtos não são vendidos para cliente final e não aparecem nessa opção.
- **Caixa fechada:** por padrão, o preço de caixa vale só para as caixas completas. Na tela, em "Como o preço de caixa fechada é calculado", dá para trocar a regra.

## Como atualizar os preços

Os preços ficam dentro do `index.html`. Quando a marca enviar uma nova tabela, é preciso gerar um novo `index.html` a partir da planilha nova. Depois, troque o arquivo aqui no GitHub: **Add file**, **Upload files**, arraste o novo `index.html` (com o mesmo nome) e clique em **Commit changes**.

## Atenção

- Este repositório deve ser **privado**. O arquivo contém todas as tabelas de preço, inclusive as de distribuidor.
- Na planilha de 2026, o código PFI600474 aparece repetido em dois produtos (Majestic Oil e Splendid Oil). Vale confirmar com a marca.

## Arquivos

- `index.html`: o painel completo, com tela, regras e preços.
- `README.md`: este guia.

Versão: tabela de preços 2026, gerada em 09/10/2026.
