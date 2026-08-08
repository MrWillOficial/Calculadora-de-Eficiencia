WPG PROJECT 1.0 — RELEASE CANDIDATE

Estrutura
- /                 Home
- /pacotes          Planner Pacotes
- /upgrade          Planner Upgrade
- /eventos          Planner Eventos

Publicação no Cloudflare Pages
1. Envie o conteúdo desta pasta como projeto/site estático.
2. Mantenha o arquivo _redirects na raiz publicada.
3. O fallback /* /index.html 200 permite acesso direto às rotas.
4. Publique o domínio configurado no projeto.

Assets
- assets/wpg-logo.png
- assets/wpg-favicon.png
- assets/wpg-share.png

Metadados
- title e description por rota
- canonical por rota
- Open Graph por rota
- Twitter Card por rota
- imagem de compartilhamento WPG

Regras principais auditadas
- Limite gratuito do Upgrade: 50 Pack FC por evolução.
- Acima de 50 Pack FC: acesso VIP.
- Invocação Vermelha: rota Y = 225 Pack FC até 202 de 1º ATK.
- Invocação Vermelha: série 15/15 = 289,8 Pack FC.
- Diferença até 15/15 = 64,8 Pack FC.
- Série completa = 72.450 Pergaminhos de Liberação de Selo.

Validação estática
- JavaScript extraído e validado com Node.js --check: OK.
- Rotas principais presentes: OK.
- _redirects: OK.
- Logo, favicon e imagem de compartilhamento: OK.
- Metadados canonical/Open Graph: OK.
- Nenhum emoji/pictograma decorativo encontrado no HTML: OK.
