# talk-react-ssr

Slides de uma apresentação sobre SSR em React no Café com Código

## Desafio

- Desenvolver uma aplicação SSR (framework/ferramentas à escolha) que atenda aos seguintes critérios
  - Não pode ocorrer FOUC, ou seja, os estilos devem ser carregados antes do conteúdo da página para que o mesmo não "pisque" com a formatação padrão do browser.
  - Deve obter dados de uma fonte externa (por ex. api de filmes, api de Pokémon).
  - A página inicial deve ser uma lista (não precisa ser extensa) de itens da categoria escolhida (ex. lista de filmes, pokédex)
    - Os itens da lista devem ser links para uma página específica com mais detalhes sobre esse item. (ex. Detalhes do filme, detalhes do pokémon)
    - Incluir meta tags adequadas para uma landing page (pesquise sobre SEO, OpenGraph e Twitter meta tags)
    - A requisição para a lista de itens deve ser feita no server-side
  
  - A página de um item deve apresentar informação detalhada sobre o item
    - A requisição para os dados do item deve ser feita no server-side
    - Incluir meta tags relevantes para o respectivo item. Devem estar inclusas no html inicial gerado pelo server, ou seja, não podem ser incluídas posteriormente pelo client (dica: use o Facebook Sharing Debugger para ver como os crawlers enxergam sua página)
  
  - Bonus
    - Hospede sua aplicação SSR em algum serviço, por exemplo o Heroku. Ao colar um link para sua página no facebook, whatsapp, twitter ou afim, deve ser gerada uma preview utilizando as informações que o crawler encontrou nas meta tags.

## Referências

- [stereobooster - Server Side Rendering pros and cons. When to use it and when to choose something else](https://dev.to/stereobooster/server-side-rendering-or-ssr-what-is-it-for-and-when-to-use-it-2cpg)
- [James K. Nelson - Static vs Server Rendering](https://frontarm.com/james-k-nelson/static-vs-server-rendering/)
- [Fernando Rocha - O que é Server Side Rendering e como usar na prática](https://medium.com/techbloghotmart/o-que-%C3%A9-server-side-rendering-e-como-usar-na-pr%C3%A1tica-a840d76a6dca)

