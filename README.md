# Transmita - Fale Conosco

Página de contato moderna e responsiva para a Transmita Digital.

## 🚀 Auto-Deploy (GitHub Actions)

Este repositório está configurado para atualizar automaticamente sua hospedagem via FTP sempre que houver um `push` na branch `main`.

### Como configurar:

Para que a atualização automática funcione, você precisa adicionar as seguintes **Secrets** no seu repositório do GitHub (`Settings > Secrets and variables > Actions`):

1.  **`FTP_SERVER`**: O endereço do servidor FTP (ex: `ftp.seusite.com.br`).
2.  **`FTP_USERNAME`**: Seu nome de usuário do FTP.
3.  **`FTP_PASSWORD`**: Sua senha do FTP.
4.  **`FTP_REMOTE_PATH`** (Opcional): A pasta onde o site deve ser instalado (ex: `/public_html/`).

Sempre que fizermos uma alteração no código e subirmos para o GitHub, ele enviará os arquivos automaticamente para sua hospedagem!
