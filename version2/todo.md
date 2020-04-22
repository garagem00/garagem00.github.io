# Garagem00 - Versão 1.1

Segue abaixo plano para organização da estrutura das páginas do site, para que possamos colocar o site no Hugo CMS

O site vai ficar com a seguinte estrutura:

```
  <raiz>
   - /style/
       - main.css : único arquivo css para todo o site
   - /js/
       - * arquivos javascript
   -/equipamentos/
      - index.html
      * imagens
   -/quem-somos/
      - index.html
      * imagens
   -/nossos-trabalhos/
      - index.html
      * imagens
   -/contato/
      - index.html
``` 

## Planejamento

Para cada uma das páginas atuais do site fazer a seguinte conversão:

  1. Usar a estrutura de template nas páginas index.html
  2. Colocar o conteúdo dentro da estrutura da página index.html
  3. Mover as imagens por diretório de página, manter as imagens da home no diretório raiz
  4. Ajustar css pra ficar somente no arquivo /style/main.css, as páginas e classes css talvez precisem de ajuste; NÃO UTILIZAR ARQUIVOS CSS SEPARADOS

_Sugestão:_
  - Começar fazendo uma página template que tenha somente cabeçalho e rodapé
  - Replicar este template para as outras páginas e copiar somente o conteúdo (miolo) de cada página/seção
  - Mover as imagens para o diretório de cada seção e ajustar a referências para os links

Uma vez com a estrutura das páginas e um único CSS vamos conseguir utilizar um CMS estático como [Hugo CMS](https://gohugo.io/getting-started/quick-start/)


  