# VIZELA MINIGOLF WORLD — GUIA DE INSTALAÇÃO DO PAINEL

## O que é isto?

Um painel de administração gratuito que te permite:
- Publicar notícias sem tocar em código
- Adicionar fotos à galeria
- Registar eventos no diário
- Atualizar a seleção portuguesa

Tudo do browser, incluindo do telemóvel.

---

## PASSO 1 — Criar o repositório no GitHub

1. Entra em github.com com a tua conta (ruidafilgest-sketch)
2. Clica "New repository"
3. Nome: **vizelaminigolfworld**
4. Público (Public)
5. Clica "Create repository"

---

## PASSO 2 — Fazer upload dos ficheiros

No repositório que acabaste de criar, faz upload destes ficheiros:

```
index.html          ← o site principal
admin/
  index.html        ← o painel de admin
  admin/config.yml  ← a configuração do painel
_noticias/          ← pasta (criar vazia)
_diario/            ← pasta (criar vazia)
_galeria/           ← pasta (criar vazia)
_data/              ← pasta (criar vazia)
imagens/            ← pasta para as fotos
```

---

## PASSO 3 — Ativar GitHub Pages

1. No repositório, clica "Settings"
2. No menu lateral clica "Pages"
3. Em "Source" escolhe "Deploy from a branch"
4. Branch: **main**, pasta: **/ (root)**
5. Clica "Save"

O site fica em: `ruidafilgest-sketch.github.io/vizelaminigolfworld`

---

## PASSO 4 — Configurar autenticação (15 minutos)

Para o painel de admin funcionar precisas de uma conta Netlify gratuita:

1. Vai a **netlify.com** e cria conta gratuita (usa o GitHub para entrar)
2. Clica "Add new site" → "Import an existing project" → GitHub
3. Escolhe o repositório **vizelaminigolfworld**
4. Clica "Deploy site"
5. O site fica também em Netlify (com URL tipo `amazing-name-123.netlify.app`)

Depois:
6. Em Netlify, vai a "Site configuration" → "Identity"
7. Clica "Enable Identity"
8. Em "Registration" escolhe "Invite only"
9. Em "External providers" adiciona "GitHub"
10. Clica "Invite users" e convida o teu email

---

## PASSO 5 — Apontar o domínio (opcional mas recomendado)

Se registares `vizelaminigolfeworld.com` no Namecheap:
1. Em Netlify → "Domain management" → "Add domain"
2. Adiciona `vizelaminigolfeworld.com`
3. No Namecheap aponta os nameservers para os da Netlify

---

## COMO USAR O PAINEL

Depois de tudo configurado:

1. Vai a `vizelaminigolfeworld.com/admin` (ou `netlify-url.netlify.app/admin`)
2. Faz login com o teu GitHub
3. Aparece o painel com 4 secções:
   - **Notícias** — escreve e publica notícias
   - **Diário de Eventos** — regista eventos e datas
   - **Galeria de Fotos** — carrega fotos com legenda
   - **Configurações** — atualiza a seleção portuguesa

4. Clicas "Save" → o site atualiza em 1-2 minutos automaticamente

---

## PRECISO DE AJUDA?

Envia uma mensagem ao Claude com:
- O erro que aparece
- O que tentaste fazer

E recebess instruções passo a passo.

---

*Vizela Minigolf World — Portal Independente*
*© 2026 Rui Gonçalves*
