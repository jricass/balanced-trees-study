# Estudo e Implementação de Árvores Balanceadas

Este repositório contém o código-fonte e a documentação para o projeto de **Estudo, Pesquisa e Modelagem de Árvores Binárias, Árvore 2-3-4 não-binária e Algoritmos de Balanceamento**.

O objetivo é implementar e analisar estruturas de dados avançadas, demonstrando seus mecanismos de inserção, remoção, busca e balanceamento.

## 📋 Estruturas Implementadas

As seguintes estruturas foram abordadas neste projeto:

1.  **Árvore 2-3-4 (B-Tree Ordem 4)**
    *   **Arquivo**: `src/tree234.ipynb`
    *   **Características**: Árvore não-binária onde cada nó pode conter até 3 chaves e 4 filhos.
    *   **Implementação**: Lógica completa de inserção (split proativo), remoção (merge/borrow proativo) e busca.
    *   **Visualização**: Gráficos gerados com `networkx` e `matplotlib`.

2.  **Árvore Rubro-Negra (Red-Black Tree)**
    *   **Arquivo**: `src/redblacktree.ipynb`W
    *   **Características**: Árvore binária de busca auto-balanceável com propriedades de coloração de nós.

3.  **Árvore k-D (k-Dimensional Tree)**
    *   (Explicação e demonstração conforme requisitos)

## 🚀 Como Executar

### Pré-requisitos

Certifique-se de ter o Python instalado. As dependências do projeto são:

*   `jupyter`
*   `networkx`
*   `matplotlib`

Você pode instalar as dependências executando:

```bash
pip install jupyter networkx matplotlib
```

### Executando os Notebooks

1.  Clone este repositório:
    ```bash
    git clone https://github.com/jricass/balanced-trees-study.git
    cd balanced-trees-study
    ```

2.  Abra o VS Code ou o terminal na pasta do projeto e inicie o Jupyter:
    ```bash
    jupyter notebook
    ```
    Ou utilize a extensão do Jupyter no VS Code para abrir os arquivos `.ipynb` diretamente na pasta `src/`.

3.  Execute as células dos notebooks para ver as demonstrações de inserção, remoção e visualização das árvores.

## 📂 Estrutura do Projeto

```
balanced-trees-study/
├── src/
│   ├── tree234.ipynb       # Implementação da Árvore 2-3-4
│   ├── redblacktree.ipynb  # Implementação da Árvore Rubro-Negra
│   └── ...
├── Readme.md               # Documentação do projeto
└── ...
```

## 👥 Equipe

*   João Ricardo Silva de Almeida
*   Felipe Gabriel Souza Libório 

## 📝 Requisitos do Projeto

*   **Implementação Manual**: Uso de nós e referências, sem bibliotecas de árvore.
*   **Operações**: Inserção, Exclusão e Busca com balanceamento.
*   **Visualização**: Plotagem gráfica das árvores.

---
*Projeto desenvolvido para a disciplina de Teoria de Grafos.*
