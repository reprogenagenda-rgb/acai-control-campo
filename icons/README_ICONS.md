# Pasta icons — Açaí Control

Use esta pasta no repositório do GitHub Pages:

/icons/
  icon-192x192.png
  icon-512x512.png
  apple-touch-icon.png
  favicon.ico
  favicon-32x32.png
  favicon-16x16.png
  demais tamanhos auxiliares

No index.html, dentro do <head>, usar:

<link rel="manifest" href="./manifest.json">
<link rel="apple-touch-icon" href="./icons/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="./icons/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="./icons/favicon-16x16.png">
<meta name="theme-color" content="#0f5132">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Açaí Control">

No manifest.json principal do projeto, usar os caminhos:

./icons/icon-192x192.png
./icons/icon-512x512.png

Critério de aprovação:
1. No GitHub, a pasta icons deve aparecer na raiz do repositório.
2. O manifest.json deve estar na raiz.
3. O index.html deve apontar para ./manifest.json e ./icons/apple-touch-icon.png.
4. No Android, após limpar cache/reabrir o site, deve aparecer opção de instalar app.
5. No iPhone, usar Compartilhar > Adicionar à Tela de Início.
