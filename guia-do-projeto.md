# Achados da Fé — Guia do Projeto

## O que foi entregue

- `index.html` — página inicial, com categorias e explicação do método
- `biblias-de-estudo.html` — página de exemplo completa (comparativo + produtos + FAQ), pronta para servir de modelo
- `style.css` — identidade visual compartilhada por todas as páginas

## Como cada "especialista" trabalhou nesse projeto

Não existem bots separados rodando sozinhos — mas cada etapa seguiu o padrão de uma função diferente, pra evitar os erros mais comuns de quem faz isso sem método:

- **Estrategista de nicho**: definiu categorias e faixas de preço (entrada/intermediária/premium) que cobrem diferentes intenções de compra
- **Especialista em SEO**: título, meta description e estrutura de perguntas frequentes pensados para aparecer em buscas como "melhor bíblia de estudo" ou "presente cristão barato"
- **Copywriter**: textos que conectam produto a versículo/necessidade, sem parecer anúncio forçado
- **Web designer**: identidade visual própria (não um template genérico) e responsiva
- **Compliance de afiliados**: aviso de divulgação incluído em toda página (exigência legal e das regras do próprio Mercado Livre)

## Como publicar

Você precisa hospedar esses arquivos em algum lugar público. Opções simples e gratuitas:
- **GitHub Pages** — grátis, bom se você já usa Git
- **Netlify / Vercel** — arrasta a pasta e já publica
- **Hostinger ou hospedagem que você já tenha**

Depois de hospedado, você cadastra a **URL do site** no seu perfil de afiliado do Mercado Livre (isso é obrigatório — só contam links divulgados nos canais que você registrou).

## Checklist antes de publicar cada página nova

- [ ] Produto tem reputação verde no Mercado Livre
- [ ] Link foi gerado pelo painel oficial de afiliados (não o link comum do produto)
- [ ] Preço na página bate com o preço real (revisar semanalmente — preços mudam)
- [ ] Aviso de divulgação de afiliado está visível na página
- [ ] Título e descrição da página têm palavras-chave que alguém buscaria no Google
- [ ] Pelo menos 1 FAQ relevante para a categoria

## Como expandir (próximas categorias)

Use `biblias-de-estudo.html` como modelo. Para cada nova categoria:
1. Duplique o arquivo e renomeie (ex: `decoracao-crista.html`)
2. Troque título, meta description, textos e produtos
3. Adicione o link dela no `index.html` (troque o `href="#"` do card correspondente por `href="decoracao-crista.html"`)

Me envie os produtos reais (nome, preço, link de afiliado, 1-2 fotos) de cada categoria que você quiser lançar, e eu preencho o conteúdo completo pra você.

## Próximos passos sugeridos

1. Substituir os produtos placeholder da página de Bíblias pelos reais
2. Publicar o site (escolher uma das opções de hospedagem acima)
3. Cadastrar a URL no painel de afiliados do Mercado Livre
4. Me trazer 3-5 produtos reais da próxima categoria (decoração ou presentes) para eu montar a página
