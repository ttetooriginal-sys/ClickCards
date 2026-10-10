# RzK SysteM — vitrine demonstrativa

Implementação própria, responsiva e estática, baseada nas informações públicas observáveis da página inicial de `rzksystem.store`. O desafio anti-bot impediu a inspeção de páginas internas; esta pasta recria a vitrine e o catálogo visível, não o backend original.

## Conteúdo
- `index.html`: página única com navegação, hero, categorias, catálogo, seção institucional e rodapé.
- `styles.css`: identidade visual escura com acento lima, componentes responsivos e estados acessíveis.
- `app.js`: busca, filtro por categoria, ordenação, carrinho local e persistência via `localStorage`.

## Executar
Abra `index.html` diretamente ou sirva esta pasta com qualquer servidor estático, por exemplo:

```sh
python3 -m http.server 8080
```

O catálogo inclui os produtos e preços exibidos publicamente na home consultada. Arte dos produtos é original/CSS, não foram copiados os arquivos, código, logotipos ou imagens do site de referência. O carrinho é apenas demonstrativo: não há checkout nem processamento de pagamento.
