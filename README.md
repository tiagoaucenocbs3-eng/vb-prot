# English Presell & Landing Page Project

Este é o projeto estruturado e pronto para subir no GitHub e implantar na Vercel.

## Estrutura de Pastas

* `/` - Página de entrada (Presell reCAPTCHA).
* `/inicio/` - Página de vendas principal (VSL atualizada e pixel do TikTok configurados).
* `/up1/` - Upsell 1.
* `vercel.json` - Configuração da Vercel (URLs limpas e cache agressivo de fontes/imagens/scripts para máxima velocidade).

---

## Como subir para o GitHub

1. Abra o terminal (Prompt de Comando ou PowerShell) e navegue até esta pasta:
   ```cmd
   cd "C:\Users\tiago\Downloads\oferta ed\ingles-vercel"
   ```

2. Inicialize o repositório Git local:
   ```bash
   git init
   ```

3. Adicione todos os arquivos:
   ```bash
   git add .
   ```

4. Faça o primeiro commit:
   ```bash
   git commit -m "Initial commit - Presell structure, optimization and new TikTok Pixel"
   ```

5. Crie um repositório no seu GitHub (vazio, sem README ou .gitignore).

6. Copie a URL do repositório do GitHub (exemplo: `https://github.com/seu-usuario/seu-repositorio.git`) e vincule ao repositório local:
   ```bash
   git remote add origin https://github.com/seu-usuario/seu-repositorio.git
   ```

7. Envie os arquivos para o GitHub:
   ```bash
   git branch -M main
   git push -u origin main
   ```

---

## Como implantar na Vercel

1. Acesse o painel da [Vercel](https://vercel.com/) e faça login.
2. Clique em **Add New...** -> **Project**.
3. Importe o repositório GitHub que você acabou de criar.
4. No campo **Framework Preset**, deixe como **Other** (ele detectará como site estático automaticamente).
5. Clique em **Deploy**.

A Vercel criará uma URL pública para você e, sempre que você atualizar os arquivos e fizer um `git push` no GitHub, a Vercel atualizará o site automaticamente!
