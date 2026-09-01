# Dr. Carlos Soluções — Landing Page

Site estático simples (HTML + CSS + JS puro, sem build), pronto pra subir na Vercel.

## Estrutura
```
index.html      → conteúdo da página
styles.css       → estilos
script.js        → menu mobile
images/          → fotos dos trabalhos (adicione novas fotos aqui)
```

## ⚠️ Antes de publicar
Confirme o número de WhatsApp usado nos links `wa.me` dentro do `index.html`
(são 4 ocorrências). Hoje está como **5534998354892**
(55 + DDD 34 + 9 9835-4892) — ajuste se o número completo for outro.
Basta usar Ctrl+F / buscar por `5534998354892` no arquivo e trocar em todas
as ocorrências.

## Como publicar na Vercel

**Opção 1 — pelo site (mais fácil, sem instalar nada):**
1. Crie uma conta em https://vercel.com (dá pra usar GitHub, Google ou e-mail)
2. Clique em "Add New" → "Project"
3. Escolha "Deploy manually" / arraste esta pasta inteira (`site`) para a área de upload
4. Não precisa configurar nada (é um projeto estático) — clique em Deploy
5. Em alguns segundos o site estará no ar com uma URL tipo `seu-projeto.vercel.app`

**Opção 2 — via GitHub (recomendado para facilitar futuras atualizações):**
1. Crie um repositório no GitHub e suba esta pasta
2. Na Vercel, clique em "Add New" → "Project" → "Import Git Repository"
3. Selecione o repositório — a Vercel detecta que é estático e já publica
4. Toda vez que você atualizar o repositório (ex: trocar fotos), o site atualiza sozinho

## Trocar/adicionar fotos
Basta colocar o arquivo dentro de `images/` e referenciar no `index.html`
dentro da seção `<section id="trabalhos">`, seguindo o mesmo padrão dos
outros itens da galeria.

## Domínio próprio (opcional)
Depois do deploy, em Project → Settings → Domains você pode apontar um
domínio próprio (ex: drcarlossolucoes.com.br) para o site.
