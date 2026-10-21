# Miel Don Carlos — página de vendas

Landing page de vendas da **Miel Don Carlos** (Asunción, Paraguai), empresa
familiar desde 2006, com elementos 3D e todas as chamadas para ação indo para o
WhatsApp do cliente. Os dados da trajetória vêm do material "Historia de Miel
Don Carlos" enviado pelo cliente.

```
index.html   página completa (HTML, CSS e JS num arquivo só)
img/         fotos dos produtos usadas no carrossel
img/historia fotos da trajetória (extraídas do PDF do cliente)
```

## O que tem na página

- **Topo 3D (Three.js):** favo de mel interativo, com as células subindo sob o
  mouse e abelhas 3D voando em volta.
- **Origem:** a marca leva o nome do pai dos fundadores (2006, 50 colmeias).
- **Carrossel 3D de produtos:** Apisana (o mais vendido), Clásica, Gourmet,
  Especialidades, Bienestar, sachet e propóleo, cada um com pedido no WhatsApp.
- **Trajetória 2006 → hoje** em linha do tempo com fotos reais.
- **Hoje em números:** ≈1.000 colmeias em Pozo Colorado, ≈30 produtos, 10 pessoas.
- **Para empresas:** supermercados, confeitarias, restaurantes e indústrias.
- Valores, como pedir, FAQ e CTA final.
- Botão flutuante do WhatsApp.

## WhatsApp

O número fica na constante `WA_NUMBER` no script de `index.html`
(formato internacional, só dígitos — hoje `595984399696`). Cada botão tem a
mensagem pronta no atributo `data-wa`.

## Fotos

Para trocar uma foto do carrossel, substitua o arquivo em `img/` mantendo o
mesmo nome. Fotos quadradas (1:1), de preferência com 800 px ou mais.

## Publicar

É um site estático: basta subir a pasta para qualquer hospedagem (Vercel,
Netlify, GitHub Pages, Hostinger…). O Three.js e as fontes vêm de CDN, então
não há build nem dependências.
