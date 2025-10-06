# Estudo-de-Caso-Construindo-um-Pipeline-de-Dados-de-Ponta-a-Ponta

A RetailNow é uma rede de lojas de varejo que atua em todo o Brasil, vendendo produtos eletrônicos e de utilidades domésticas.
Com a expansão das operações e canais digitais, a empresa passou a gerar grandes volumes de dados em diferentes sistemas:

Sistema de Vendas (ERP) — registros transacionais de cada venda realizada nas lojas físicas e no e-commerce.

Sistema de Marketing — planilhas com campanhas, investimentos e retorno (ROI).

Logs do Site — arquivos semiestruturados em JSON que registram acessos, buscas e cliques.

Atualmente, essas informações estão dispersas, sem integração entre as áreas.
A diretoria de dados contratou seu time para propor e documentar um pipeline de dados unificado, que permita coletar, armazenar, processar e disponibilizar essas informações para análise.





Projetar e documentar uma arquitetura de dados moderna, aplicando tecnologias que atenda aos seguintes requisitos:

Ingestão de dados estruturados (vendas, clientes, marketing) e semiestruturados (logs JSON);

Armazenamento organizado por camadas (Raw, Staging, Curated, Analytics);

Processamento distribuído e escalável (ex: Spark, Hive, Hadoop, etc.);

Orquestração de etapas com Airflow (ou equivalente);

Controle de demandas e versionamento via Azure Boards (ou similar);

Disponibilização de dados prontos para BI (Power BI, Superset ou outro).
