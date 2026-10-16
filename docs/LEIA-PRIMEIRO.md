# Visual Therapy Atlas — versão França

Página adaptada do endereço fornecido pelo proprietário: https://recursospsicologia.online/therapy-mind-maps/

## O que está preparado

- Mesma oferta, ordem das seções, identidade visual e argumentos; copy localizada para francês da França.
- Chamada com mais de 250 mapas preservada por instrução do proprietário. O detalhamento de 120 mapas principais e os 120 temas enumerados foi conservado como na referência, sem inventar temas adicionais.
- Preço solicitado: 100 € → 29 € → 10 €, pagamento único e acesso vitalício. O desconto entre 29 € e 10 € é 19 €.
- Imagens dos entregáveis recriadas em francês a partir das composições originais. Arquivos do produto não foram alterados.
- Nenhum identificador antigo de pixel, checkout anterior ou dependência de WordPress no site final.
- Pixel 2141962266672792 configurado com escolha de consentimento. Carrega somente após aceitar a medição publicitária.
- Os três botões apontam para https://pay.hotmart.com/G108050774O?checkoutMode=10.

## Onde inserir checkout e pixel

Editar apenas `config.js` na raiz do site:

```javascript
window.ATLAS_CONFIG = Object.freeze({
  checkoutUrl: "https://pay.hotmart.com/G108050774O?checkoutMode=10",
  metaPixelId: "2141962266672792"
});
```

Checkout e pixel fornecidos pelo proprietário já estão preenchidos. Usar HTTPS se alterar o checkout.

O pixel só carrega após aceitar a medição publicitária, enviando PageView e ViewContent. Cliques nos botões enviam InitiateCheckout somente com consentimento. Não há envio de Purchase em clique: a confirmação de compra precisa ser configurada na Hotmart. A configuração do pixel no checkout da Hotmart é separada desta página.

## Condições preservadas da copy

“Aujourd’hui seulement” e a âncora de 100 € foram solicitados pelo proprietário. A validade do prazo e a base comercial dos preços precisam ser verdadeiras antes de ativar as vendas; não foi criado contador reiniciável nem histórico fictício de preços. A página não altera automaticamente preços do processador.

A garantia de sete dias foi conservada da oferta. Ela não deve ser apresentada como substituta dos direitos legais do consumidor na França. Conferir a operação do checkout e as informações sobre conteúdo digital/retratação antes da venda. Referência oficial: https://www.economie.gouv.fr/dgccrf/les-fiches-pratiques/delais-de-reflexion-ou-de-retractation-comment-sappliquent-t-ils

Identificação do vendedor, suporte e políticas não foram inventados nem substituídos por dados de terceiros. Esses dados devem ser completados com os dados reais da operação.

## Imagens

Geração/edição: ferramenta integrada de imagem; originais usados como referência de composição. Títulos e elementos principais foram localizados. A microtipografia das miniaturas geradas não é transcrição certificada dos PDFs; conferir com os entregáveis franceses reais antes da publicação comercial, especialmente ao ampliar amostras.

Os prompts e notas de revisão acompanham a pasta `docs`. A exportação WebP usa qualidade 88, conserva dimensões e transparência e não redesenha a composição ou os textos. Os PNGs da geração são preservados no projeto local.

## Publicação e revisão

O ZIP de site contém `index.html`, `config.js`, `app.js` e `assets/`, prontos para hospedagem estática. Sem instalação de pacotes. Os arquivos precisam permanecer nas mesmas posições.

A prévia local é uma revisão da página. Destino dos três botões verificado no navegador e eventos testados com simulação local. Aprovação de pagamento, entrega dos PDFs, preço/moeda na Hotmart, recebimento dos eventos pela Meta e desempenho comercial não foram validados em produção.
