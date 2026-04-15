# Santander Dev Week 2023 - Pipeline de ETL com Python

Projeto desenvolvido para o desafio da **Santander Dev Week 2023** na plataforma **DIO**. O objetivo é demonstrar um pipeline de ETL (Extract, Transform, Load) funcional.

## 🚀 O Projeto
Devido à instabilidade na API original do evento, este pipeline foi adaptado para operar utilizando arquivos locais, garantindo a execução completa do fluxo de dados.

### Etapas do Pipeline:

1.  **Extract (Extração):** Leitura de IDs de usuários a partir de um arquivo CSV gerado no Excel e carregamento dos dados detalhados via arquivo JSON (Mock).
2.  **Transform (Transformação):** Processamento dos dados para criar mensagens personalizadas focadas em investimentos.
3.  **Load (Carga):** Salvamento dos dados atualizados em um novo arquivo JSON, simulando a atualização de um banco de dados.

## 🛠️ Tecnologias Utilizadas
*   **Python 3**
*   **Pandas** (Manipulação de dados CSV)
*   **JSON** (Manipulação de dados estruturados)
*   **Google Colab** (Ambiente de desenvolvimento)

## 📁 Estrutura de Arquivos
*   `IDs(Planilha1).csv`: Fonte inicial dos IDs.
*   `users.json`: Base de dados simulada.
*   `santander-dev-week-2023-etl.ipynb`: Notebook com a lógica do pipeline.

