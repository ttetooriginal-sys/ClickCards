# Rynex 10k

Vitrine estática responsiva da **Rynex 10k**. A home usa a logo fornecida pelo usuário e uma direção visual roxa de alto contraste, com fundo e grafismos feitos em CSS — sem banners com aparência sintética. Os contornos dos cards foram reforçados. O carrossel mantém as páginas de jogos e assinaturas em destaque.

## Rotas

- `index.html` — apresentação, categorias e catálogo.
- `categories/` — grade das cinco categorias.
- `category/<slug>/` — coleções de produtos.
- `product/<id>/` — detalhes dos 27 produtos.
- `login/` e `terms/` — páginas institucionais.

A home tem busca, carrossel com controles, categorias, carrinho demonstrativo e layout responsivo. As imagens de produtos continuam sendo as que já estavam no catálogo; podem ser trocadas pelas novas fotos quando forem enviadas.

O projeto continua estático no GitHub Pages: login, atendimento social, checkout e pagamentos não estão conectados. Os botões de atendimento mostram um aviso até que sejam fornecidos os links oficiais.

## Executar localmente

Dentro da pasta `rzk-store`, rode:

```sh
python3 -m http.server 8080
```
