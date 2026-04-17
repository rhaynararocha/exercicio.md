# exercicio


## 🚗 Manipulação de Listas em Java (Stream API)

Breve guia sobre as funções mais utilizadas para manipular coleções de forma funcional e eficiente.

### 🛠️ Funções Principais


| Função | Finalidade | Resultado Esperado |
| :--- | :--- | :--- |
| `find()` | Encontrar o **primeiro** item que atenda a um critério. | Retorna um único item (ou vazio). |
| `filter()` | **Filtrar** a lista com base em uma regra. | Retorna uma nova lista (menor ou igual à original). |
| `map()` | **Transformar** os dados de cada item. | Retorna uma nova lista com o mesmo tamanho. |
| `forEach()` | Executar uma **ação** para cada item. | Não retorna lista, apenas executa o código. |

---

### 📝 Descrição Detalhada

#### 🔍 `find()`
Busca na lista e entrega o primeiro item que corresponde ao que você pediu. Caso não encontre nada, ele retorna um valor vazio (`Optional`).
*   **Exemplo:** Buscar o primeiro carro de uma marca específica.

#### ⚖️ `filter()`
Cria uma nova lista contendo apenas os itens que passaram na sua "regra" ou condição.
*   **Exemplo:** Filtrar apenas carros da cor azul.

#### 🔄 `map()`
Pega cada item da lista original, aplica uma transformação e gera uma nova lista com esses novos valores.
*   **Exemplo:** Pegar uma lista de nomes e transformar todos para letras maiúsculas.

#### 🚀 `forEach()`
Percorre a lista e executa uma ação para cada item, mas não gera uma lista nova. É o substituto moderno do laço `for` tradicional.
*   **Exemplo:** Imprimir o nome de todos os carros no console.
