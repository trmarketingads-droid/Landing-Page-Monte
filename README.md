# Monte — Site Institucional

Site institucional da Monte, empresa de comunicação para negócios e mídia paga.

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | Versão desktop |
| `mobile.html` | Versão mobile |

## Como subir no GitHub Pages

1. Crie um repositório no GitHub com o nome `monte-site` (ou o nome que preferir)
2. Suba os arquivos conforme as instruções abaixo
3. Vá em **Settings → Pages**
4. Em **Source**, selecione `main` e pasta `/ (root)`
5. Clique em **Save**
6. Seu site estará disponível em: `https://seu-usuario.github.io/monte-site`

## Como subir os arquivos (passo a passo)

### Windows

```bash
# 1. Instale o Git: https://git-scm.com/download/win

# 2. Abra o terminal (CMD ou PowerShell) na pasta do projeto e rode:
git init
git add .
git commit -m "primeiro commit"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/monte-site.git
git push -u origin main
```

### Mac / Linux

```bash
# Abra o Terminal na pasta do projeto e rode:
git init
git add .
git commit -m "primeiro commit"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/monte-site.git
git push -u origin main
```

> Substitua `SEU-USUARIO` pelo seu usuário do GitHub.

## Como atualizar o site depois de fazer mudanças

```bash
git add .
git commit -m "atualização do site"
git push
```

## Domínio personalizado (opcional)

Para usar `monte.com.br` em vez do link do GitHub:

1. No GitHub, vá em **Settings → Pages → Custom domain**
2. Digite seu domínio e salve
3. No painel da sua hospedagem de domínio, crie um registro DNS:
   - Tipo: `CNAME`
   - Nome: `www`
   - Valor: `seu-usuario.github.io`
