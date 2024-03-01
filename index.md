---
layout: default
---

Este sábado, 5 de março de 2022, é o
[Open Data Day](https://opendataday.org/pt_br/) (dia dos dados abertos)!
Neste dia, eventos ao redor do mundo reúnem pessoas para discutir e
celebrar os dados abertos. Para saber mais sobre os eventos passados do
Open Data Day no Brasil,
[veja este texto](https://herrmann.tech/pt/blog/2022/02/23/open-data-day-2022-esta-chegando-conheca-os-anteriores-no-brasil.html).

![OPEN DATA SETS SEGES]({{ 'assets/images/open-datasets-seges.png' | relative_url }})

Neste ano, a Secretaria de Gestão (SEGES) do Ministério da Economia
apresentou e mostrou como usar os dados abertos que disponibiliza.

## Programação

| Quem | O quê | Quando | Material |
|---|---|---|---|
| Augusto Herrmann | Abertura | 14:00 |  |
| Hugo Rezende | <ul><li>introdução</li><li>papel da CGINF</li><li>datasets: <ul><li>SIORG</li><li>Raio-X da Administração Pública Federal</li></ul></ul> | 14:10 |  |
| Cleiton Pontes e Rodrigo Siqueira | Compras.gov.br Contratos e o dataset disponível | 14:30 |  |
| Luís Izycki | TaxiGov e o dataset disponível | 14:50 |  |
| Jorge Ubirajara | Análise de dados do TaxiGov | 15:10 | [slides](assets/slides/TaxiGov%20e%20Pandemia.pdf) |
| Augusto Herrmann | Oficina de uso de dados abertos: Raio-X, Compras.gov.br Contratos e TaxiGov | 15:30 | [cadernos](https://github.com/economiagovbr/opendataday2022/tree/main/notebooks) |

## Conjuntos de dados utilizados

No evento apresentamos e utilizamos alguns conjuntos de dados da SEGES:

* [Compras.gov.br Contratos](https://dados.gov.br/dataset/comprasnet-contratos)
* [TaxiGov](https://dados.gov.br/dataset/corridas-do-taxigov)
* [Raio-X da Administração Pública Federal](https://dados.gov.br/dataset/raio-x-da-administracao-publica-federal)
* Estrutura organizacional do poder executivo federal
([SIORG](https://dados.gov.br/dataset/siorg))

Para participar das oficinas, sugerimos preparar o seu ambiente de
análise de dados e baixar os conjuntos de dados.

Utilizaremos o ambiente do Jupyter Lab que está
[neste repositório](https://github.com/augusto-herrmann/docker-jupyter-extensible).
Posso usar outro? Claro que pode. Mas este já vem com os pacotes e
dependências que vamos utilizar, tornando tudo mais fácil.

**Obs.:** antes de fazer o build do contêiner Docker é necessário acrescentar
o pacote `frictionless` no arquivo `Dockerfile`.

## Códigos

Os cadernos Jupyter com os códigos utilizados na oficina estão
[no Github](https://github.com/economiagovbr/opendataday2022/tree/main/notebooks).

## Como participar

Não havia inscrição. Era só chegar e participar!

Perdeu o evento? Não tem problema. Para assistir à gravação, basta
reproduzir o vídeo abaixo.
