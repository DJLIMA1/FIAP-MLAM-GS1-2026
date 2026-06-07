# Global Solution - MLAM 1CC

Projeto de analise estatistica em Python usando dados reais do NASA Exoplanet Archive.

## Tema escolhido

A base utilizada contem informacoes de exoplanetas confirmados, como ano de descoberta, metodo de descoberta, periodo orbital, raio do planeta, massa e distancia do sistema. A escolha tem relacao direta com o tema de ciencia espacial e nova economia espacial, pois dados astronomicos podem apoiar estudos sobre exploracao, monitoramento, pesquisa e desenvolvimento tecnologico.

## Fonte da base

NASA Exoplanet Archive:
https://exoplanetarchive.ipac.caltech.edu/

CSV baixado por consulta TAP em 07/06/2026.

## Arquivos do projeto

- `exoplanetas_nasa.csv`: base real usada no trabalho.
- `analise_exoplanetas.ipynb`: notebook com codigo, tabelas, graficos e interpretacoes.
- `relatorio_estatistico_final.pdf`: relatorio final do projeto.

## Como executar

Instale as dependencias:

```bash
pip install pandas matplotlib
```

Execute:

```bash
jupyter notebook analise_exoplanetas.ipynb
```

Tambem e possivel abrir o arquivo `analise_exoplanetas.ipynb` no Google Colab.

## Requisitos atendidos

- Base de dados real e justificada.
- Tabela de frequencia para uma variavel quantitativa discreta: `disc_year`.
- Tabela de frequencia para uma variavel quantitativa continua: `pl_orbper`.
- Dois graficos estatisticos com titulo e rotulos.
- Duas analises univariadas com media, mediana, moda, maximo, minimo, amplitude, variancia, desvio padrao e quartis.
- Relatorio estatistico final em PDF.

## Observacao

Antes de entregar, publicar este projeto em um repositorio no GitHub e enviar no portal um arquivo `.txt` separado com os nomes, matriculas e link do repositorio.
