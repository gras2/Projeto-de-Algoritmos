# Projeto: Grafo com Árvore Geradora Mínima 

Este projeto implementa o algoritmo de Kruskal para encontrar a árvore geradora mínima em um grafo representando 100 cidades de Pernambuco e seus pontos turísticos. O código é escrito em Python e utiliza uma abordagem de lista de adjacência para representar o grafo.

# Descrição
O código consiste em duas partes principais:

1. Definição do Grafo: A classe Graph é responsável por representar o grafo e implementar as operações necessárias para encontrar a árvore geradora mínima. Ela utiliza listas para armazenar as arestas do grafo e implementa os métodos para adicionar arestas, encontrar conjuntos disjuntos e aplicar a união por rank durante a execução do algoritmo de Kruskal.

2. Execução do Algoritmo: Após a definição do grafo, o código cria uma instância da classe Graph e adiciona arestas entre todas as combinações de cidades e pontos turísticos. Em seguida, o algoritmo de Kruskal é aplicado para encontrar a árvore geradora mínima no grafo.

# Requisitos
Python 3.x
pandas
numpy
scipy
Instale as dependências necessárias usando o seguinte comando:
bash
Copy code
pip install pandas numpy scipy

# Como Usar
 Certifique-se de que seus dados estejam organizados em um arquivo Excel (Cidades e pontos turísticos de Pernambuco CORRETO.xlsx neste exemplo).
Execute o script digitando o seguinte comando no terminal ou prompt de comando:
bash
Copy code
python script.py
Veja os resultados impressos no console, mostrando as cidades e suas distâncias correspondentes na Árvore Geradora Mínima.
Explicação do Código
O script utiliza a biblioteca pandas para ler dados de um arquivo Excel.
Calcula a distância euclidiana entre as coordenadas geográficas para criar arestas ponderadas.
Em seguida, aplica o algoritmo de Kruskal para encontrar a Árvore Geradora Mínima.
Os resultados, incluindo cidades e distâncias, são impressos no console.
Sinta-se à vontade para adaptar o script ao seu conjunto de dados específico ou requisitos.
# Observações Adicionais
O script assume que o arquivo Excel contém colunas com os nomes 'Latitude', 'Longitude' e 'Cidades mais conhecidas de Pernambuco'.
Certifique-se de que o caminho do arquivo (file_path) no script está correto e modifique-o conforme necessário.
Aproveite a exploração de Árvores Geradoras Mínimas com base em coordenadas geográficas!

# Autores
Gleybson Ricardo Alves da Silveira
Marcos Christopher de Souza Martins
