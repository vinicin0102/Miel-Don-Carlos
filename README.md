# Miel Don Carlos — página de vendas

Landing page de vendas da **Miel Don Carlos** (Asunción, Paraguai), empresa
familiar desde 2006, seguindo a identidade visual oficial da marca, com todas as
chamadas para ação indo para o WhatsApp do cliente. Os dados da trajetória vêm do material "Historia de Miel
Don Carlos" enviado pelo cliente.

```
index.html   página completa (HTML, CSS e JS num arquivo só)
img/         fotos dos produtos usadas no carrossel
img/historia fotos da trajetória (extraídas do PDF do cliente)
```

## O que tem na página

- **Topo:** sol listrado do logo atrás de três produtos (Clásica, Apisana, Gourmet).
- **Origem:** a marca leva o nome do pai dos fundadores (2006, 50 colmeias).
- **Carrossel 3D de produtos:** Apisana (o mais vendido), Clásica, Gourmet,
  Especialidades, Bienestar, sachet e propóleo, cada um com pedido no WhatsApp.
- **Trajetória 2006 → hoje** em linha do tempo com fotos reais.
- **Hoje em números:** ≈1.000 colmeias em Pozo Colorado, ≈30 produtos, 10 pessoas.
- **Para empresas:** supermercados, confeitarias, restaurantes e indústrias.
- Valores, como pedir, FAQ e CTA final.
- Botão flutuante do WhatsApp.

## Identidade visual

- **Logo oficial:** vetorizado a partir do material do cliente e embutido como
  `<symbol id="logo">` no `index.html` (header, CTA final e rodapé). O sol e o
  texto "MIEL DE ABEJAS" foram redesenhados em vetor; o "Don Carlos" foi
  vetorizado do original. Se o cliente enviar o logo em SVG/AI, substitua o
  conteúdo do símbolo.
- **Cores** (tokens no topo do CSS): amarelo CMYK 6/0/100/0 `#F3DF12` (destaques),
  dourado CMYK 0/20/60/20 `#CCA352` e bege (fundos artesanais), verde P375C
  `#97D700` (natural/origem), laranja P1655C `#FC4C02` (CTAs), azul P306C
  `#00B5E2` e coral P1785C `#F8485E` (só nas cores de cada linha, como nas etiquetas).
- **Tipografia:** Poppins em toda a página (títulos 700/800, textos 400, botões 600).

## WhatsApp

O número fica na constante `WA_NUMBER` no script de `index.html`
(formato internacional, só dígitos — hoje `595984399696`). Cada botão tem a
mensagem pronta no atributo `data-wa`.

## Fotos

Para trocar uma foto do carrossel, substitua o arquivo em `img/` mantendo o
mesmo nome. Fotos quadradas (1:1), de preferência com 800 px ou mais.

## Publicar

É um site estático: basta subir a pasta para qualquer hospedagem (Vercel,
Netlify, GitHub Pages, Hostinger…). As fontes vêm do Google Fonts; não há build nem dependências.
