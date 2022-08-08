# Arquitetura Frontend

## Mobile

Vamos focar o frontend direcionado para devices mobiles. Para isso é necessário escolher entre dois modos de se desenvolver, com tecnologias de fontes nativas ou não nativas.
Nessa opção escolhemos desenvolver em uma tecnologia de fonte não nativa, pois nesse caso é possível manter apenas uma base de código, o ponto negativo dessa escolha seria abrir mão de funcionalidades nativas não tratadas pelas possíveis bibliotecas. Como nossa aplicação não é dependente de tais funcionalidades, o risco é minimizado com essa escolha.

### React Native

Como framework de desenvolvimento decidimos pelo [React Native](https://reactnative.dev/), pois ele permite desenvolvimento nativo com uma base de código em JavaScript, que se aproxima da base do ReactJS.
Desta forma é mais simples a passagem e a tradução de conhecimento entre os desenvolvedores que já tiveram experiência com este framework.
Ele também permite o uso das funções mobile básicas que, pelo escopo atual, estamos interessados, com pouco ou nenhuma trativa de código, ou manifestos nativos.

### Comunicação e Padrão de Arquitetura

Para realizar a comunicação do mobile com o backend escolhemos pelo uso de APIs e para isso podemos usar o padrão de comunicação do próprio React Native.
Como padrão de arquitetura podemos seguir o padrão [Redux](https://redux.js.org/) e utilizar para isso a biblioteca de JavaScript de mesmo nome. Com isso podemos mais rápidamente desenvolver o código de maneira organizada e segregada nas camadas de gerenciamento de UI e gerenciamento de estados. Mantendo uma base de código de simples manuntenção e mais reutilizável.
