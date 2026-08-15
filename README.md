# Mapeamento Digital dos Teores de Fe₂O₃, MnO, Nb e TiO₂ em Morro dos Seis Lagos – AM, Brasil

Este repositório reúne os códigos relacionados ao artigo publicado na revista *Espaço Aberto*, volume 14, número 1, páginas 157–174, em 2024.

> Rodrigues, N. B., Silva, J. C. L., Silva, R. P. M., Pinheiro, H. S. K., & Carvalho Júnior, W. (2024). Mapeamento Digital dos Teores de Fe₂O₃, MnO, Nb e TiO₂ em Morro dos Seis Lagos – AM, Brasil. *Espaço Aberto, 14*(1), 157–174. https://doi.org/10.36403/espacoaberto.2024.60234

## Visão geral

O estudo aplica técnicas de pedometria e aprendizado de máquina ao mapeamento digital de teores de elementos e compostos químicos na formação petroférrica/laterítica de Morro dos Seis Lagos, no Amazonas, Brasil.

## Objetivo

Avaliar o desempenho dos modelos Multivariate Adaptive Regression Splines (MARS), Support Vector Machine com kernel radial (SVMRadial) e Random Forest (RF) na predição espacial de:

- Fe₂O₃ — óxido de ferro;
- MnO — óxido de manganês;
- Nb — nióbio;
- TiO₂ — dióxido de titânio.

## Metodologia

O fluxo metodológico compreendeu:

1. Revisão bibliográfica;
2. Compilação dos dados geoquímicos;
3. Tratamento e análise dos dados de entrada;
4. Seleção de covariáveis;
5. Aplicação de algoritmos de aprendizado de máquina;
6. Predição espacial dos elementos e compostos;
7. Produção dos mapas;
8. Análise e interpretação dos resultados.

## Modelos avaliados

- Multivariate Adaptive Regression Splines (MARS);
- Support Vector Machine com kernel radial (SVMRadial);
- Random Forest (RF).

## Principais resultados

O modelo Random Forest apresentou maior acurácia na predição de Fe₂O₃, MnO e Nb. Para TiO₂, o melhor desempenho foi obtido pelo modelo SVMRadial. De forma geral, covariáveis morfométricas foram mais relevantes para as predições do que covariáveis derivadas de índices espectrais.

## Estrutura prevista do repositório

```text
.
├── README.md
├── CITATION.cff
├── .gitignore
├── scripts/
├── data/
├── raster/
└── outputs/
```

Os dados geoquímicos e rasters somente serão disponibilizados quando houver autorização e condições adequadas de redistribuição.

## Artigo

- [Página oficial do artigo](https://revistas.ufrj.br/index.php/EspacoAberto/article/view/60234)
- [DOI: 10.36403/espacoaberto.2024.60234](https://doi.org/10.36403/espacoaberto.2024.60234)

## Autores

- Niriele Bruno Rodrigues
- Júlio Cesar Lopes da Silva
- Renan Pereira Marinatti da Silva
- Helena Saraiva Koenow Pinheiro
- Waldir de Carvalho Júnior

## Citação e reutilização

Ao utilizar este material, cite o artigo associado. O artigo está publicado sob a licença CC BY-NC-SA 4.0. Uma licença específica para o código-fonte não foi definida nesta versão inicial; portanto, a licença do artigo não deve ser interpretada automaticamente como licença do software.
