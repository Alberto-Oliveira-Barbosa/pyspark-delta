# Utilizando PySpark com Delta Tables

Este repositório contém exemplos de uso e explicações sobre a utilização e o funcionamento de Delta Tables em conjunto com o PySpark.

## Visão geral

O projeto demonstra como utilizar o PySpark em conjunto com Delta Lake para:
- Criar tabelas Delta
- Realizar Operações ACID
- Gerenciar o versionamento das tabelas
- Implementar Upset, Merge e Delete
- History e Time Travel
- Navegar entre versões e restaurar versões anteriores

### Pré requisitos:
- Python 3.13 ou superior
- Poetry

### Tecnologias usadas:
- Python 3.13
- PySpark 4.0
- Delta-Spark 4.0
- Jupyter Lab

### Modo de uso:

1. Clone o repositório com o comando:
```bash
git clone git@github.com:Alberto-Oliveira-Barbosa/pyspark-delta.git
```
2. Navegue até o diretório `pyspark-delta`
```bash
cd pyspark-delta
```
3. Instale as dependências com o comando:
```bash
poetry install
```

4. Inicialize o ambiente com o comando:
```bash
poetry shell
```

5. Os exemplos de uso e demais explicações estão no arquivo `example.ipynb`

## Recursos Adicionais

- [Documentação oficial do Delta Lake](https://docs.delta.io/latest/index.html)
- [Documentação oficial do PySpark](https://spark.apache.org/docs/latest/api/python/index.html)
- [Blog com artigos sobre Delta Lake](https://delta.io/blog/)