# SolarOS — Landing Page de Alta Conversão

> Landing page minimalista e de alta performance com design editorial para o produto **SolarOS** (kit de skills e engenharia de resposta direta para LLMs).

Desenvolvida com foco em **zero ruído visual ("Zero AI Slop")**, precisão métrica de 1px e ergonomia mobile-first.

---

## ⚡ Destaques & Arquitetura

- **Design Minimalista Editorial:** Paleta sólida sem gradientes genéricos, sem sombras difusas pesadas e com hierarquia tipográfica precisa (*Plus Jakarta Sans*).
- **Mobile-First & Responsivo:** Adaptado para telas desde 320px (iPhone SE) até desktops ultrawide, respeitando áreas seguras (*iOS safe-area-inset-bottom*).
- **FAQ Acessível em CSS Grid:** Acordeão nativo com transição fluida por CSS Grid (`0fr -> 1fr`), tags semânticas ARIA (`aria-expanded`, `aria-controls`) e suporte total a navegação por teclado.
- **Sticky Conversion Bar:** Barra inferior persistente para dispositivos móveis com ação direta para a âncora de checkout (`#comprar`).
- **Pronto para Vercel:** Configuração nativa com `vercel.json` e headers de segurança pré-configurados.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico**
- **Tailwind CSS (CDN com configuração customizada)**
- **Plus Jakarta Sans (Google Fonts)**
- **JavaScript Vanilla (Zero dependências externas)**

---

## 🚀 Como Executar Localmente

### Opção 1: Com Node.js nativo

```bash
# Inicia o servidor estático local na porta 3000
node server.js
```

Acesse em seu navegador:
- No computador: [http://localhost:3000](http://localhost:3000)
- No celular (mesma rede Wi-Fi): `http://SEU_IP_LOCAL:3000`

### Opção 2: Abrir diretamente

Basta abrir o arquivo `index.html` em qualquer navegador moderno.

---

## ☁️ Deploy no Vercel

O projeto foi configurado com `vercel.json` para deploy estático imediato:

1. Importe este repositório no painel do [Vercel](https://vercel.com/new).
2. Deixe as opções de **Framework Preset** como `Other`.
3. Clique em **Deploy**.

Ou via CLI:

```bash
npm i -g vercel
vercel
```

---

## 📄 Licença

Projeto desenvolvido para uso exclusivo no ecossistema Solar.
