#estilo Rails de organização 
Organizado os elementos individuais da nossa aplicação com uma abordagem "estilo Rails". 
Quer dizer, os ativos são organizados por "tipo" ou "capacidade": qualquer ação será encontrada na pasta Actions, qualquer redutor será encontrado na pasta Reducers, e por aí vai. 
De fato, um exemplo do “mundo real” do Redux no GitHub estrutura o app exatamente desta forma. 
Nesta estrutura de diretórios, se quiséssemos importar todas ações para um componente, podemos pegar todas em um único comando import!

#Frontend
   - Components
      - component1.js
      - component2.js
      - component3.js
   - Actions
      - action1.js
      - action2.js
   - Reducers
      - reducer1.js
   - Util
   - Store