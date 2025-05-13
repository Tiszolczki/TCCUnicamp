TCCUnicamp
📌 Visão Geral
Este projeto visa resolver problemas relacionados à fragmentação de dados e baixa qualidade das informações, utilizando Apache Spark e práticas avançadas de qualidade de dados, catalogação e governança. Os resultados apontam para uma base sólida para análises futuras e maior transparência e eficiência na gestão pública.

🧰 Tecnologias Utilizadas
Apache Spark: Processamento distribuído de grandes volumes de dados.

Python: Linguagem principal para desenvolvimento dos scripts.

Jupyter Notebook: Ambiente interativo para desenvolvimento e documentação do código.

Ambiente Virtual (venv): Isolamento das dependências do projeto.

🗂️ Estrutura do Projeto
alerts/: Scripts relacionados à geração de alertas com base na qualidade dos dados.

catalog/: Implementações para catalogação e governança dos dados.

data quality/: Scripts para avaliação e melhoria da qualidade dos dados.

ingestion/: Processos de ingestão e integração de dados de diferentes fontes.

layer/: Definição das camadas de dados (raw, trusted, refined).

pipeline/: Orquestração dos processos de ETL.

write/: Scripts para escrita e persistência dos dados processados.

venv/: Ambiente virtual contendo as dependências do projeto.

⚠️ Importante:
O diretório config/, responsável por armazenar credenciais de acesso (como configurações de webhook ou conexões externas), foi removido do repositório por motivos de segurança.
Para execução local, crie manualmente o diretório config/ e insira os arquivos necessários com suas credenciais de acesso nos formatos esperados pelos scripts.

🚀 Como Executar
Clone o repositório:
git clone https://github.com/Tiszolczki/TCCUnicamp.git

Ative o ambiente virtual:
Linux/macOS:
source venv/bin/activate
Windows:
venv\Scripts\activate

Instale as dependências:
pip install -r requirements.txt

Execute os notebooks:
Navegue até os diretórios desejados e abra os notebooks .ipynb com o Jupyter Notebook para explorar e executar os scripts.

📊 Resultados Esperados
Melhoria na Qualidade dos Dados: Implementação de práticas que asseguram dados mais consistentes e confiáveis.

Governança de Dados: Estruturação de políticas e processos para melhor gerenciamento dos dados.

Base Sólida para Análises Futuras: Preparação dos dados para suportar análises avançadas e tomadas de decisão mais informadas.

Transparência e Eficiência na Gestão Pública: Facilitação do acesso e compreensão dos dados por parte de gestores e cidadãos.

👥 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests com sugestões de melhorias ou correções.
