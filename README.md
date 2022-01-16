Qual o principal objetivo da contextAPI? 
Que problemas ela busca solucionar?

Permite compartilhar estados entre componentes que não façam parte da mesma hierarquia;
É um gerenciador de estado;
Disponibiliza uma forma de passar dados entre a árvore de componentes sem precisar passar props manualmente em cada nível que poderiam gerar o famoso prop-drilling;
Para isso utiliza contextos, permitindo a criação e organização em um ou mais contextos;
É indicado para compartilhar dados que podem ser considerados “globais” para a árvore de componentes do React, como tema, idioma, se o usuário está autenticado;
O uso deve ser moderado, pois dificulta a reutilização de componentes;
Sempre que possível deve ser quebrado em pequenos contextos, pois quando um valor do contexto é atualizado, todos os componentes ligados à ele serão renderizados novamente.

