# RzK SysteM — vitrine digital

Implementação estática e responsiva baseada nas informações públicas observáveis da página inicial de `rzksystem.store`. O site de referência bloqueou a inspeção de páginas internas; esta implementação recria as informações públicas observadas e tem identidade visual, ilustrações e código próprios. Não replica backend, checkout ou conteúdo privado do site de referência.

## Páginas
- `index.html` — início, categorias e produtos em destaque.
- `catalogo.html` — catálogo completo, pesquisa, filtros e ordenação.
- `ofertas.html` — produtos com preço promocional.
- `sobre.html` — informações sobre a experiência da vitrine.
- `produto.html?id=ID` — página de detalhes de cada produto do catálogo.

## Recursos
- 27 produtos e preços exibidos na página inicial consultada.
- Carrinho demonstrativo compartilhado entre as páginas, salvo no navegador com `localStorage`.
- Animações de entrada, rolagem, flutuação, órbita e hover; movimento reduzido é respeitado conforme preferência do dispositivo.
- Layout responsivo e navegação móvel.

## Executar
Abra `index.html` ou sirva esta pasta com um servidor estático:

```sh
python3 -m http.server 8080
```

Esta é uma demonstração estática: não há checkout, pagamento ou integração com o serviço original. Os preços são os observados na home consultada e podem não refletir valores atuais da loja de referência.
