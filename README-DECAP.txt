DECAM CMS - PASSO A PASSO

1. No Netlify: Site settings > Identity > Enable Identity > Invite only
2. Identity > Services > Git Gateway > Enable
3. Identity > Invite users > convide remerson e admin
4. Faça push desta pasta admin/ e content/ para seu repo GitHub
5. Netlify faz deploy automatico
6. Acesse seusite.netlify.app/admin > login > Blog > New > Publish
7. Em 30s atualiza para todo mundo automaticamente!

Arquivos:
- admin/index.html e config.yml = painel
- content/blog/*.md = posts
- index-com-decap.html = seu site que le posts automaticamente
