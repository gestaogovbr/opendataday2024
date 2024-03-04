# Open Data Day 2024

Na sexta-feira, 8 de março de 2024, será realizado o Open Data Day 2022
da Secretaria de Gestão e Inovação (SEGES) do Ministério da Gestão e da Inovação
em Serviços Públicos (MGI).

![OPEN DATASETS SEGES](public/assets/images/open-datasets-seges.png)

## Programação

| Quem | O quê | Quando | Material |
|---|---|---|---|
| Augusto Herrmann | O que é o Open Data Day | 15:00 |  |
| Priscila Cabral | Abertura | 15:10 |  |
| a definir | Datasets da DELOG | 15:30 |  |
| a definir | Datasets da DTPAR | 15:50 |  |
| Augusto Herrmann | Oficina de uso de dados abertos no Jupyter Lab | 16:10 | [cadernos](notebooks) |

Para ver como foi o ano anterior, veja o
[site do evento de 2022](https://gestaogovbr.github.io/opendataday2022/).

## Conjuntos de dados da SEGES

Os conjuntos de dados publicados pela SEGES são os seguintes:

*5E5trutura organizacional do poder executivo federal
  ([SIORG](https://dados.gov.br/dados/conjuntos-dados/dados-da-estrutura-organizacional-do-poder-executivo-federal-sistema-siorg))
* [Processo Eletrônico Nacional - PEN](https://dados.gov.br/dados/conjuntos-dados/processo-eletronico-nacional---pen)
* [Raio-X da Administração Pública Federal](https://dados.gov.br/dados/conjuntos-dados/raio-x-da-administracao-publica-federal)
* [Sistema Integrado de Gestão Patrimonial (SIADS)](https://dados.gov.br/dados/conjuntos-dados/sistema-integrado-de-gestao-patrimonial-siads)
* [TaxiGov](https://dados.gov.br/dados/conjuntos-dados/sistema-de-transportes-de-servidores-publicos---taxigov-v2)
* [Transferências e Parcerias da União](https://dados.gov.br/dados/conjuntos-dados/transferencias-e-parcerias-da-uniao)
* [Viagens a Serviço do Governo Federal (SCDP)](https://dados.gov.br/dados/conjuntos-dados/viagens-a-servico-do-governo-federal-scdp)

Para participar das oficinas, sugerimos preparar o seu ambiente de
análise de dados e baixar os conjuntos de dados.

Utilizaremos o ambiente do Jupyter Lab que está
[neste repositório](https://github.com/augusto-herrmann/docker-jupyter-extensible).
Posso usar outro? Claro que pode. Mas este já vem com os pacotes e
dependências que vamos utilizar, tornando tudo mais fácil.

**Obs.:** antes de fazer o build do contêiner Docker é necessário acrescentar
o pacote `frictionless` no arquivo `Dockerfile`.

## Códigos

Os códigos utilizados no evento estão na pasta
[jupyterlite/notebooks](jupyterlite/notebooks).
