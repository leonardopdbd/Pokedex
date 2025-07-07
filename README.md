# Pokedex

# Análise de Requisitos – Aplicativo Pokédex
1. Visão Geral do Sistema
O sistema será um aplicativo móvel desenvolvido com React Native e Expo, que consumirá a PokéAPI para exibir informações dos Pokémon. Os usuários poderão visualizar uma lista com os primeiros Pokémon e acessar seus detalhes individuais.

2. Objetivo do Sistema
Fornecer uma interface intuitiva e responsiva para que os usuários possam navegar por informações básicas dos Pokémon, como nome, tipo, imagem e estatísticas base.

3. Requisitos Funcionais (RF)
   
Código	Requisito	Prioridade

RF01	O sistema deve exibir uma lista com os 10 primeiros Pokémon da PokéAPI.	Alta
RF02	O sistema deve mostrar o nome, tipo e imagem de cada Pokémon na lista.	Alta
RF03	O sistema deve permitir ao usuário clicar em um Pokémon para visualizar detalhes.	Alta
RF04	O sistema deve exibir na tela de detalhes: nome, imagem, tipos e status base (ex: HP, ataque).	Alta
RF05	O sistema deve permitir navegação entre a tela de lista e a tela de detalhes.	Alta
RF06	O sistema deve mostrar um indicador de carregamento durante a requisição dos dados.	Média

5. Requisitos Não Funcionais (RNF)
Código	Requisito	Prioridade
RNF01	O sistema deve ser desenvolvido usando React Native com Expo.	Alta
RNF02	O sistema deve consumir dados da PokéAPI.	Alta
RNF03	O sistema deve apresentar um tempo de carregamento inferior a 3 segundos para a lista.	Média
RNF04	O design deve ser responsivo e funcionar bem em celulares Android e iOS.	Alta
RNF05	O código deve ser modularizado em componentes reutilizáveis.	Média
RNF06	A navegação deve ser fluida e sem travamentos.	Alta

6. Tecnologias Utilizadas
   
Frontend: React Native + Expo
API: PokéAPI

7. Público-Alvo
Fãs de Pokémon
Estudantes de programação
Usuários de dispositivos móveis Android e iOS


