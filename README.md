# FiscalQuest Backup — página pública de informações OAuth

Site estático para a página inicial e a política de privacidade da integração **pessoal** do FiscalQuest Backup com o Google Drive. Nenhum dado de backup, token ou senha deve ser colocado neste repositório.

## Publicar com GitHub Pages

No GitHub, acesse **Settings → Pages → Build and deployment**. Selecione **Deploy from a branch**, escolha `main` e **/(root)** e salve.

Após a publicação, confira:

- Início: `https://adoroostrabalhosdeandrekkk.github.io/fiscalquest-backup-site/`
- Privacidade: `https://adoroostrabalhosdeandrekkk.github.io/fiscalquest-backup-site/privacidade.html`

Na página OAuth **Branding**, use as duas URLs. Em **Authorized domains**, cadastre o domínio que o Google aceitar para o site, conforme suas regras de verificação. O Google pode exigir prova de controle de domínio; GitHub Pages não é garantia de aprovação formal. Se for necessário verificar domínio próprio, use um domínio personalizado sob seu controle.

## Segurança

- Não inclua OAuth Client Secret, refresh token, `rclone.conf`, dumps do PostgreSQL ou chaves do rclone crypt.
- A página é pública, mas o FiscalQuest e os arquivos de backup devem continuar privados.
- Revise o texto da política se o fluxo, o escopo OAuth ou o armazenamento mudarem.
