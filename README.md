### ProjetoFinal-Engenharia-de-Dados 

### Licença
[MIT License](LICENSE)

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
- Apache Spark 3.4.3
- Ferramentas de orquestração (e.g., Airflow, Dagster)
- Data Lake (usando Delta Lake ou Apache Iceberg)
- Biblioteca Faker para geração de dados sintéticos

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
- Apache Spark: Transformação de dados
- Delta Lake: Gerenciamento de dados no Data Lake
- MkDocs: Documentação do projeto
- Faker: Geração de dados sintéticos

### Autores
- Aluno 1: Angiel Leal - (https://github.com/angielleal)
- Aluno 2: Lucas Daufenbach - (https://github.com/lucasdaufenbach)
- Aluno 3: Marcos Jeronimo - (https://github.com/marcoshjf)
- Aluno 4: Mateus Zanin - (https://github.com/Zaanin)

### Referências
- [Modelo de Projeto no GitHub](https://github.com/jlsilva01/projeto-ed-satc)

---
