# Rynex 10k

Vitrine estática responsiva para a marca **Rynex 10k**. A logo foi fornecida pelo usuário; a home agora usa uma paleta preta/violeta, banners originais sem texto embutido e um carrossel com controles, indicadores e troca automática. As páginas existentes de categorias, produtos, login e termos foram mantidas e atualizadas para a nova identidade.

## Rotas

- `index.html` — carrossel promocional, Mais Vendidos, categorias e catálogo.
- `categories/` — grade das cinco categorias.
- `category/<slug>/` — coleções de produtos.
- `product/<id>/` — detalhes dos 27 produtos.
- `login/` e `terms/` — páginas institucionais.

## Recursos

A home tem busca, carrossel de banners, cards promocionais horizontais, navegação por categorias, carrinho demonstrativo, produtos relacionados, animações e layout responsivo. Os banners roxos do topo são artes originais; as fotos das ofertas/cards de produto ainda são as imagens de catálogo que já estavam no projeto e podem ser substituídas pelas novas fotos quando forem enviadas.

O projeto continua estático no GitHub Pages: login, atendimento social, checkout e pagamentos não estão conectados. Os botões de atendimento exibem um aviso até que os links oficiais da Rynex 10k sejam configurados.

## Executar localmente

Dentro da pasta `rzk-store`, rode:

```sh
python3 -m http.server 8080
```
