# Miel Don Carlos — página de vendas

Landing page de vendas da **Apicultura Don Carlos** (Asunción, Paraguai), com
elementos 3D e todas as chamadas para ação indo para o WhatsApp do cliente.

```
index.html   página completa (HTML, CSS e JS num arquivo só)
img/         fotos dos produtos usadas no carrossel
```

## O que tem na página

- **Topo 3D (Three.js):** favo de mel interativo, com as células subindo sob o
  mouse e abelhas 3D voando em volta.
- **Carrossel 3D de produtos:** Línea Clásica, Gourmet, Medicinal, Apisana,
  sachet e propóleo, cada um com botão de pedido no WhatsApp.
- Loja para apicultores, serviços, curso, história, como pedir, FAQ e CTA final.
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
