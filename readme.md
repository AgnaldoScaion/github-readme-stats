# 📊 GitHub Readme Stats — Self-Hosted Instance / Instância Própria

---

## 🌐 Table of Contents / Índice

- 🇺🇸 [English Version](#-english-version)
  - [Quick Fix](#-quick-fix--use-this-url-in-your-readme)
  - [Ready-to-use Examples](#-ready-to-use-examples)
  - [Side-by-side Example](#%EF%B8%8F-side-by-side-example)
  - [Deploy Your Own Instance](#-want-to-deploy-your-own-instance)
- 🇧🇷 [Versão em Português](#-versão-em-português)
  - [Solução Rápida](#-solução-rápida--use-esta-url-no-seu-readme)
  - [Exemplos Prontos](#-exemplos-prontos-para-copiar)
  - [Exemplo Lado a Lado](#%EF%B8%8F-exemplo-de-uso-no-readme-lado-a-lado)
  - [Criar Sua Própria Instância](#-quer-ter-sua-própria-instância)

---

---

## 🇺🇸 English Version

If you landed here, you're probably facing one of these errors on your GitHub profile README:

```
Error Fetching Resource
```
```
Not Found
```
```
Invalid upstream response (401)
```

This happens because the public instance at `github-readme-stats.vercel.app` is **overloaded and unstable**. The fix is to use a dedicated instance — and that's exactly what this guide is about.

---

### ✅ Quick Fix — Use this URL in your README

Simply replace:
```
https://github-readme-stats.vercel.app
```

With:
```
https://readme-stats-agnaldo.vercel.app
```

---

### 📋 Ready-to-use Examples

#### Stats Card
```md
![GitHub Stats](https://readme-stats-agnaldo.vercel.app/api?username=YOUR_USERNAME&hide_border=true&show_icons=true&count_private=true&title_color=ffffff&text_color=cccccc&icon_color=999999&bg_color=0d1117)
```

#### Top Languages Card
```md
![Top Langs](https://readme-stats-agnaldo.vercel.app/api/top-langs/?username=YOUR_USERNAME&hide_border=true&layout=compact&langs_count=6&title_color=ffffff&text_color=cccccc&icon_color=999999&bg_color=0d1117)
```

> ⚠️ Replace `YOUR_USERNAME` with your GitHub username.

---

### 🖥️ Side-by-side Example

```html
<div align="center">
  <img height="199em" src="https://readme-stats-agnaldo.vercel.app/api?username=YOUR_USERNAME&hide_border=true&show_icons=true&count_private=true&title_color=ffffff&text_color=cccccc&icon_color=999999&bg_color=0d1117"/>
  <img height="199em" src="https://readme-stats-agnaldo.vercel.app/api/top-langs/?username=YOUR_USERNAME&hide_border=true&layout=compact&langs_count=6&title_color=ffffff&text_color=cccccc&icon_color=999999&bg_color=0d1117"/>
</div>
```

---

### 🚀 Want to Deploy Your Own Instance?

If you'd rather have your own server (recommended so you don't depend on anyone), follow these steps:

**1. Fork the original repository**
Go to [github.com/anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) and click **Fork**.

**2. Create a Vercel account**
Go to [vercel.com](https://vercel.com) and sign in with GitHub.

**3. Import the project**
On the Vercel dashboard, click **Add New Project** and import your fork.

**4. Generate a GitHub token**
Go to [github.com/settings/tokens](https://github.com/settings/tokens) → **Generate new token (classic)** → check `repo` and `read:user` → click **Generate token** and copy it.

**5. Add the token on Vercel**
Go to **Settings → Environment Variables** and add:
- Name: `PAT_1`
- Value: the token you copied

**6. Add a custom domain**
Go to **Settings → Domains** and add a `.vercel.app` subdomain of your choice, e.g.:
```
readme-stats-YOUR_NAME.vercel.app
```

**7. Redeploy**
Go to **Deployments**, click the 3 dots on the latest deploy → **Redeploy**.

**8. Use your URL in your README**
```
https://readme-stats-YOUR_NAME.vercel.app
```

---

---

## 🇧🇷 Versão em Português

Se você chegou aqui, provavelmente está enfrentando um desses erros no seu README do GitHub:

```
Error Fetching Resource
```
```
Not Found
```
```
Invalid upstream response (401)
```

Isso acontece porque a instância pública `github-readme-stats.vercel.app` está **sobrecarregada e instável**. A solução é usar uma instância dedicada — e é exatamente isso que esse guia ensina.

---

### ✅ Solução Rápida — Use esta URL no seu README

Basta substituir:
```
https://github-readme-stats.vercel.app
```

Por:
```
https://readme-stats-agnaldo.vercel.app
```

---

### 📋 Exemplos Prontos para Copiar

#### Stats Card
```md
![GitHub Stats](https://readme-stats-agnaldo.vercel.app/api?username=SEU_USERNAME&hide_border=true&show_icons=true&count_private=true&title_color=ffffff&text_color=cccccc&icon_color=999999&bg_color=0d1117)
```

#### Top Languages Card
```md
![Top Langs](https://readme-stats-agnaldo.vercel.app/api/top-langs/?username=SEU_USERNAME&hide_border=true&layout=compact&langs_count=6&title_color=ffffff&text_color=cccccc&icon_color=999999&bg_color=0d1117)
```

> ⚠️ Substitua `SEU_USERNAME` pelo seu usuário do GitHub.

---

### 🖥️ Exemplo de Uso no README (Lado a Lado)

```html
<div align="center">
  <img height="199em" src="https://readme-stats-agnaldo.vercel.app/api?username=SEU_USERNAME&hide_border=true&show_icons=true&count_private=true&title_color=ffffff&text_color=cccccc&icon_color=999999&bg_color=0d1117"/>
  <img height="199em" src="https://readme-stats-agnaldo.vercel.app/api/top-langs/?username=SEU_USERNAME&hide_border=true&layout=compact&langs_count=6&title_color=ffffff&text_color=cccccc&icon_color=999999&bg_color=0d1117"/>
</div>
```

---

### 🚀 Quer Ter Sua Própria Instância?

Se preferir ter o seu próprio servidor (recomendado para não depender de ninguém), siga esses passos:

**1. Faça um fork do repositório original**
Acesse [github.com/anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) e clique em **Fork**.

**2. Crie uma conta no Vercel**
Acesse [vercel.com](https://vercel.com) e faça login com o GitHub.

**3. Importe o projeto**
No dashboard do Vercel, clique em **Add New Project** e importe o fork.

**4. Gere um token do GitHub**
Acesse [github.com/settings/tokens](https://github.com/settings/tokens) → **Generate new token (classic)** → marque `repo` e `read:user` → clique em **Generate token** e copie.

**5. Adicione o token no Vercel**
Em **Settings → Environment Variables**, adicione:
- Nome: `PAT_1`
- Valor: o token copiado

**6. Adicione um domínio personalizado**
Em **Settings → Domains**, adicione um subdomínio `.vercel.app` de sua escolha, ex:
```
readme-stats-SEU_NOME.vercel.app
```

**7. Faça o Redeploy**
Em **Deployments**, clique nos 3 pontinhos do deploy mais recente → **Redeploy**.

**8. Use sua URL no README**
```
https://readme-stats-SEU_NOME.vercel.app
```

---

## 👨‍💻 Author / Autor

Designed by **Agnaldo Júnior** for real-world practicality.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/agnaldo-j%C3%BAnior-81364934b/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5511983490572)
