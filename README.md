### ProjetoFinal-Engenharia-de-Dados 

### Licença
[MIT License](LICENSE)

---

### Descrição

Este projeto implementa um pipeline de dados relacionados ao tema de **educação**, com foco em análise de desempenho, frequência e engajamento de alunos. O objetivo é criar um Data Lake e aplicar técnicas de transformação de dados com Apache Spark para suportar a visualização de KPIs e métricas relevantes em um dashboard.

---

### Começando
Estas instruções ajudam a configurar o ambiente local para desenvolvimento e testes.

---

### Desenho de Arquitetura
Adicione aqui o diagrama representando seu pipeline (use ferramentas como [Excalidraw](https://excalidraw.com) ou [Diagrams.net](https://app.diagrams.net)).

A arquitetura do pipeline segue a abordagem **medalhão**, com as camadas **Landing**, **Bronze**, **Silver** e **Gold** para o armazenamento e transformação dos dados. Os dados gerados pelo Faker serão usados para preencher as tabelas relacionadas a alunos, cursos, avaliações e frequência, simulando um cenário realista de dados educacionais.

---

### Pré-requisitos
- Python 3.9 ou superior
- PostgreSQL instalado e configurado
- Apache Airflow para orquestração
- Apache Spark 3.4.3
- Biblioteca Faker para geração de dados sintéticos
- Conta no Azure para usar o ADLS Gen2 (ou equivalente local para simulação)
- Power BI Desktop para visualização de dashboards

---

### Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/Zaanin/ProjetoFinal-Engenharia-de-Dados.git

2. Configure o ambiente:

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   pip install -r requirements.txt

3. Configure e inicie o Spark localmente: (Detalhe isso no README posteriormente.)

### Ferramentas utilizadas
- [MkDocs](https://www.mkdocs.org): Documentação do projeto.
- [Faker](https://faker.readthedocs.io): Geração de dados sintéticos.
- [PostgreSQL](https://www.postgresql.org): Banco de dados relacional para armazenar os dados.
- [Apache Airflow](https://airflow.apache.org): Orquestração e agendamento de tarefas no pipeline de dados.
- [Apache Spark](https://spark.apache.org): Transformação de dados em grande escala.
- [Azure Data Lake Storage Gen2](https://azure.microsoft.com/en-us/products/storage/data-lake-storage/): Repositório para armazenamento em camadas.
- [Power BI](https://powerbi.microsoft.com): Visualização de dados e construção de dashboards interativos.


### Autores
- Aluno 1: Angiel Leal - (https://github.com/angielleal)
- Aluno 2: Lucas Daufenbach - (https://github.com/lucasdaufenbach)
- Aluno 3: Marcos Jeronimo - (https://github.com/marcoshjf)
- Aluno 4: Mateus Zanin - (https://github.com/Zaanin)

### Referências
- [Modelo de Projeto no GitHub](https://github.com/jlsilva01/projeto-ed-satc)

---
