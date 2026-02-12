
# 📊 Curso de Análise de Dados com Python (Pandas)

Bem-vindo ao repositório oficial da aula prática de **Tratamento e Limpeza de Dados**! 🚀

Este projeto foi desenvolvido para demonstrar, na prática, como transformar dados brutos e "sujos" em informações confiáveis e prontas para análise utilizando as principais ferramentas do ecossistema Python.

---

## 🎯 Objetivo da Aula

O foco principal é ensinar o **Data Cleaning (Limpeza de Dados)**, uma das etapas mais críticas e demoradas de qualquer projeto de Ciência de Dados. Ao final deste notebook, o aluno será capaz de:

1.  **Diagnosticar problemas** comuns em bases de dados reais (valores nulos, duplicatas, formatos incorretos).
2.  **Aplicar técnicas de correção** robustas utilizando a biblioteca Pandas.
3.  **Padronizar dados** complexos (datas e moedas) usando Regex (Expressões Regulares).
4.  **Preparar o dataset** final para análise estatística ou visualização.

---

## 🛠️ Tecnologias Utilizadas

O projeto utiliza a stack padrão da indústria para análise de dados:

*   **[Python 3.8+](https://www.python.org/)**: Linguagem de programação versátil e poderosa.
*   **[Pandas](https://pandas.pydata.org/)**: A principal biblioteca para manipulação e análise de dados tabulares.
*   **[Jupyter Notebook](https://jupyter.org/)**: Ambiente interativo que permite misturar código executável, visualizações e texto explicativo.

---

## 📂 Estrutura do Projeto

*   `sample.ipynb`: O notebook principal contendo todo o código da aula, explicações passo a passo e exercícios.
*   `data/`: Pasta contendo os arquivos CSV utilizados:
    *   `clientes_senac.csv`: Dataset original com erros propositais para correção.
    *   `clientes_senac_atividade.csv`: Dataset para o exercício prático final.
*   `requirements.txt`: Lista de dependências para reproduzir o ambiente.

---

## 🚀 Como Executar o Projeto

Siga os passos abaixo para rodar o notebook na sua máquina:

### Pré-requisitos
Certifique-se de ter o **Python** instalado. Recomendamos o uso do **Anaconda** ou **Miniconda** para facilitar o gerenciamento de pacotes.

### Passo a Passo

1.  **Clone o repositório** (ou baixe os arquivos):
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2.  **Crie um ambiente virtual** (Opcional, mas recomendado):
    ```bash
    python -m venv .venv
    # Windows:
    .venv\Scripts\activate
    # Linux/Mac:
    source .venv/bin/activate
    ```

3.  **Instale as dependências**:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Executando na sua IDE (Recomendado)**:
    
    Se você prefere usar uma IDE em vez do navegador:

    *   **Visual Studio Code (VS Code) / Cursor / Antigravity**:
        1.  Instale a extensão **"Jupyter"** da Microsoft (busque por `ms-toolsai.jupyter` na aba de extensões).
        2.  Abra o arquivo `sample.ipynb` no VS Code.
        3.  No canto superior direito do editor, clique em **"Select Kernel"** e escolha o ambiente Python que você configurou (`.venv` ou `base`).

    *   **PyCharm**:
        *   **Versão Professional**: O suporte é nativo. Basta abrir o arquivo.
        *   **Versão Community**: Requer configuração adicional ou uso em modo de apenas leitura. Recomenda-se o VS Code ou o Jupyter via navegador para melhor experiência gratuita.

    *   **Via Navegador (Clássico)**:
        Rode no terminal:
        ```bash
        jupyter notebook
        ```
        Isso abrirá uma aba no seu navegador. Clique no arquivo `sample.ipynb` para começar!

---

## 🧠 Conteúdo Programático do Notebook

O notebook está dividido nas seguintes seções práticas:

1.  **Carregamento e Inspeção**: `read_csv`, `head`, `info`, `isnull`.
2.  **Limpeza de Strings**: `strip`, `astype(str)`.
3.  **Conversão Numérica**: Tratamento de símbolos de moeda (`R$`) e conversão segura para `float`.
4.  **Manipulação de Datas com Regex**: Padronização de datas mistas (`dd/mm/yyyy`, `yyyy-mm-dd`) para o padrão internacional ISO.
5.  **Remoção de Duplicatas**: Identificação e remoção de registros redundantes.
6.  **Imputação de Valores Ausentes**: Estratégias inteligentes para preencher dados faltantes (`fillna` com mediana).

---

## 📝 Exercício Prático

No final do notebook, há uma **Atividade Prática** desafiadora usando o arquivo `clientes_senac_atividade.csv`. O objetivo é aplicar sozinho tudo o que foi aprendido na aula!

---

**Bons estudos!** 🎓
