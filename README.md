# Adriano Diamarante · Site Profissional

Site institucional de Adriano Diamarante, Psicólogo Clínico (CRP 06/127613).
Construído em HTML + CSS puros, sem dependências, sem framework.

## Estrutura

```
.
├── index.html              # Página única (one-page)
├── styles.css              # Todo o estilo
└── images/
    ├── photo-hero-new.jpg  # Hero (sentado no sofá)
    ├── photo-about-new.jpg # Sobre mim (braços cruzados, plantas)
    └── photo-book.png      # Agendar (recostado)
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (público).
2. Arraste todos os arquivos desta pasta para o repositório, ou faça upload via interface.
3. Vá em **Settings → Pages**.
4. Em **Branch**, selecione `main` (ou `master`) e pasta `/ (root)`. Salve.
5. Em poucos minutos o site estará no ar em `https://SEU_USUARIO.github.io/NOME_DO_REPO/`.

Para usar um domínio próprio (ex.: `adrianodiamarante.com.br`), siga as instruções em **Settings → Pages → Custom domain**.

## Personalização rápida

### Trocar tamanhos de título
No `styles.css`:
- **Hero** (linha ~85, `.h-hook`): título "Um espaço para escutar o que pesa"
- **Agendar** (linha ~95, `.h-display`): título "Escolha o tempo…"
- **Mobile do hero** (linha ~862, dentro do `@media (max-width: 640px)`)

### Trocar fotos
Substitua os arquivos em `images/` mantendo o mesmo nome. Proporção ideal: **4:5** (retrato).

### Trocar links de agendamento ou WhatsApp
No `index.html`, procure por:
- `calendar.app.google/eTKFVdGQUsaGByAk8`: sessão de 50 min
- `calendar.app.google/3KWaMZpDLwRmodFK8`: sessão de 30 min
- `wa.me/5511957956411`: WhatsApp

### Painel de Tweaks
O site tem um painel discreto (canto inferior direito) que permite trocar:
- Tema (Claro / Escuro)
- Formato do retrato (Oval / Fade / Arco / Reta)
- Densidade (Amplo / Compacto)

Esses são controles para experimentação. Quando definir a versão final, pode remover o `<button class="tw-toggle">` e o `<aside class="tw-panel">` do `index.html`, junto com o `<script>` no final.

## Identidade visual

- **Tipografia:** Times New Roman (serifa clássica, sem dependência de fontes externas).
- **Paleta:**
  - Branco Gelo `#F0F0F0` (fundo)
  - Teal Escuro `#145470` (texto e CTA final)
  - Teal Tinta `#0B3A4E` (seção de agendamento)
  - Cream `#F1EFE9` (texto sobre fundo escuro)

## Ética profissional

Os valores das sessões **não são exibidos** no site, em conformidade com o Código de Ética do Psicólogo (CFP).

---

© 2026 · Adriano Diamarante · CRP 06/127613
