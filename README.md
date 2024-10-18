# 💽 Instalação do Typebot

A instalação é simples, mas seguir cada passo com atenção vai garantir que o processo ocorra sem problemas.


### 1. Clone o repositório do Typebot e inicie a instalação

Clone o repositório e execute o script de instalação:

```bash
sudo apt update && sudo apt upgrade -y && sudo apt install -y git && git clone https://github.com/anozapvirus/Typebot.git && cd /root/Typebot && chmod +x typebot.sh && ./typebot.sh

```


### 1. Configuração de Email SMTP

Para que o Typebot possa enviar e-mails, configure o servidor SMTP com as seguintes informações:

- **Servidor:**
   ```
  smtp.gmail.com
 ```
- **Nome de usuário:**
```
sistemazapzap@gmail.com
```
- **Número da porta:**
```
465
```
- **Senha do app:**
```
egnmcnndecwvgryr
```

### 3. Configuração de Subdomínios

Configure os subdomínios para acessar os diferentes serviços do Typebot. Abaixo estão os subdomínios recomendados:


 ```
  typebot.seudominio.com
  ```

  ```
 bot.seudominio.com
  ```
```
storage.seudominio.com
```
" > README.md

### 4. Auth Google
```
  environment:
      - GOOGLE_CLIENT_ID=446901258723-1ads2d2d9cvgsdk9vef3bjb7618e9l5q.apps.googleusercontent.com
      - GOOGLE_CLIENT_SECRET=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
      ```
