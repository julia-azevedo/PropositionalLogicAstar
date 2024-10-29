# Provador de Teoremas na Lógica Proposicional 
Este projeto implementa um provador de teoremas na lógica proposicional utilizando o algoritmo de busca heurística A*. 
## Descrição 
O algoritmo A* é aplicado para provar uma sentença específica a partir de uma base de conhecimento fornecida pelo usuário. A heurística usada é o número de passos restantes para alcançar a prova do teorema desejado. 
## Estrutura de Dados 
- **Base de Conhecimento (BC)**: Conjunto de sentenças fornecidas pelo usuário. -
- **Regras de Inferência**: Inclui Modus Ponens (MP) e outras regras que podem ser expandidas.
-  **Algoritmo A***: Utilizado para buscar a prova de forma eficiente, combinando custo real e heurística.
  - ## Funcionalidades
    -  Entrada da base de conhecimento e sentença a ser provada pelo usuário.
    - Aplicação do algoritmo A* para encontrar a prova, se possível.
    - Exibição do caminho de inferência até a prova do teorema.

  ## Como executar
  1. Clone o repositório
  2. Execute o script principal para fornecer a base de conhecimento e a sentença alvo.
  3. O script exibirá a prova encontrada ou informará se a prova não foi possível.


  
