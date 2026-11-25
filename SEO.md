# Relatório SEO — Escalada e Esportes Radicais (Atividade 2)

## 1. Palavras-Chave Planejadas (3 palavras-chave)
1. **escalada e esportes radicais**
2. **escalada em rocha e boulder**
3. **equipamentos de segurança paraquedismo**

## 2. Decisões Tomadas na Otimização
- **`title` e `meta description` únicos por página:** `index.html` foca no panorama geral das modalidades e equipamentos; `sobre.html` aprofunda o guia de modalidades e segurança com links internos descritivos.
- **URL canônica, Open Graph e Favicon:** Adicionados `<link rel="canonical">`, tags Open Graph (`og:title`, `og:description`, `og:image` em `1200x630`, `og:type`, `og:url`) e ícones (`favicon-32x32.png` e `favicon.png`).
- **Dados estruturados JSON-LD:** Implementados schemas `SportsOrganization` na página inicial e `Article` na página secundária, para validação em `validator.schema.org` (`imagens/validacao-schema.png`).
- **`robots.txt` e `sitemap.xml`:** Criados na raiz do projeto apontando para as URLs do site publicado.
- **Segunda página e links internos:** Criada `sobre.html` interligada de forma descritiva com `index.html`.
- **Imagens otimizadas:** Imagens convertidas para `.webp` com atributos `alt`, `width` e `height`, e `loading="lazy"` nas imagens abaixo da primeira dobra.

## 3. Tabela de Notas Lighthouse (Mobile — Antes e Depois)

| Métrica Lighthouse (Mobile) | Antes | Depois | Meta / Observação |
| :--- | :---: | :---: | :--- |
| **SEO** | *(91)* | *(100)* | Meta: `>= 95` |
| **Acessibilidade** | *(94)* | *(96)* | Meta: `>= 90` |


## 4. Evidências e Prints
- Validação Schema.org: `![Validação JSON-LD](imagens/validacao-schema.png)`
- Lighthouse antes: `![Lighthouse Antes](imagens/lighthouse-antes.png)`
- Lighthouse depois: `![Lighthouse Depois](imagens/lighthouse-depois.png)`
