# 🗄️ Curso Completo de Banco de Dados

Repositório dedicado aos estudos, anotações e práticas do Curso Completo de Banco de Dados. 

O projeto foi inicialmente estruturado com SQLite, mas logo no início das aulas foi migrado para **MySQL**. Essa mudança foi feita para utilizar um Sistema de Gerenciamento de Banco de Dados (SGBD) mais robusto, baseado em arquitetura cliente-servidor, que reflete melhor os ambientes reais de produção e análise de dados no mercado.

As consultas e modelagens são executadas diretamente em arquivos do Jupyter Notebook (`.ipynb`) utilizando a extensão SQL Magic.

---

## 🛠️ Tecnologias Utilizadas

* **Banco de Dados:** MySQL
* **Linguagem:** Python / SQL
* **Ambiente:** Jupyter Notebook (VSCode)
* **Servidor Local:** XAMPP
* **Bibliotecas Python:** `ipython-sql`, `pymysql`, `sqlalchemy`, `pandas`

---

## ⚙️ Pré-requisitos

Para conseguir rodar as células de código deste repositório na sua máquina, você precisará ter instalado:

1. **Python 3.x** e o **Jupyter Notebook** (recomenda-se o uso do VSCode com a extensão do Jupyter).
2. Um servidor MySQL rodando localmente. Neste projeto, utilizo o **[XAMPP](https://www.apachefriends.org/pt_br/index.html)**.

---

## 🚀 Como Executar o Projeto

### 1. Preparando o Banco de Dados
1. Abra o painel de controle do XAMPP.
2. Dê "Start" no módulo **MySQL**.

### 2. Configurando o Ambiente Python
Abra o terminal do seu VSCode (ou prompt de comando) e instale os pacotes necessários para fazer a ponte entre o Jupyter e o MySQL:

```bash
pip install ipython-sql pymysql sqlalchemy pandas
