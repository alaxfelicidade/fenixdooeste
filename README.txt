# Fênix 2026 — PWA

## Como instalar no celular

### Android (Chrome)
1. Abra o arquivo index.html em um servidor local ou via GitHub Pages
2. O popup de instalação aparecerá automaticamente em 1,5s
3. Toque em "Instalar" e confirme

### iOS (Safari)
1. Abra o index.html no Safari
2. Toque no ícone de compartilhar (quadrado com seta para cima)
3. Role para baixo e toque em "Adicionar à Tela de Início"
4. Toque em "Adicionar"

## Hospedagem recomendada
Para funcionar como PWA completo (offline + instalação automática),
o arquivo precisa ser servido via HTTPS. Opções gratuitas:
- GitHub Pages (gratuito)
- Netlify Drop (arrastar e soltar)
- Firebase Hosting

## Arquivos
- index.html   → Dashboard principal
- manifest.json → Configuração PWA
- sw.js         → Service Worker (cache offline)
- icon-192.png  → Ícone 192x192
- icon-512.png  → Ícone 512x512
- icon.svg      → Ícone SVG (fonte)
