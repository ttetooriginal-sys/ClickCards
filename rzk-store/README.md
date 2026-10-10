# RzK SysteM #TheBest

Vitrine estática responsiva recriada a partir da aparência pública de [rzksystem.store](https://rzksystem.store/), das páginas públicas de categorias, produto, login e termos inspecionadas no navegador e do HTML enviado no chat. Usa uma implementação própria de HTML/CSS/JS, com as artes de marca/categorias/produtos fornecidas no HTML guardadas localmente em `assets/`.

## Páginas

- `index.html` — home com hero, carrossel de categorias e os cinco grupos de produtos.
- `categories/` — grade das cinco categorias.
- `category/<slug>/` — coleções Destaques, Jogos Populares, Produtos do Discord, Assinaturas Exclusivas e Produtos Diversos.
- `product/<id>/` — detalhe estático de cada um dos 27 produtos, usando seus IDs públicos.
- `login/` e `terms/` — páginas públicas de entrada e termos.
- `catalogo.html`, `ofertas.html`, `sobre.html` e `produto.html` — aliases simples para compatibilidade com links antigos.

## Recursos

- Busca com sugestões, categorias clicáveis, ordenação por preço e carrossel horizontal.
- 27 produtos com nomes, emojis, preços, descontos, IDs e imagens locais observados na loja de referência.
- Carrinho e favoritos demonstrativos persistidos no navegador (`localStorage`).
- Página de IA com preço, variantes, estoque e descrição capturados no site público; demais páginas de produto usam o mesmo layout e dados de catálogo com texto de descrição genérico.
- Animações de entrada, órbita/flutuação, brilho no hover e transições; preferência por movimento reduzido respeitada.
- Layout responsivo para desktop e celular.

## Limites desta cópia estática

GitHub Pages serve apenas arquivos estáticos. O login Google/Discord/e-mail é somente visual; não autentica nem envia e-mails. Carrinho e botões de compra são demonstrativos e não processam pedidos ou pagamentos. Links de Instagram, WhatsApp e Discord apontam para os canais públicos observados.

## Executar

Na pasta `rzk-store`, sirva os arquivos localmente:

```sh
python3 -m http.server 8080
```
