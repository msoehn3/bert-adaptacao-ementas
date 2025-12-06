# BERTimbau - Adaptação ao Domínio Jurídico Trabalhista

Repositório oficial dos experimentos apresentados no artigo "Adaptação de LLMs para Ementas Trabalhistas: Uma Análise Comparativa de Estratégias de Treinamento e Tokenização", avaliando técnicas de continue pre-training, tokenização customizada e treinamento "do zero" para linguagem jurídica trabalhista.

## Objetivo

Avaliar como diferentes estratégias de adaptação de domínio - incluindo variação do tamanho do corpus, tokenização customizada e treinamento do zero - afetam o desempenho de modelos BERT em tarefas de Masked Language Modeling (MLM) no domínio das ementas trabalhistas.

## Estrutura do Repositório

| Arquivo/Pasta | Descrição |
| :--- | :--- |
| `notebook.ipynb` | Notebook completo com todos os experimentos. |
| `config_used.json` | Configurações exatas usadas nas execuções. |
| `dataset_ementas_trt.txt` | Dataset composto por 5.000 ementas trabalhistas. |
| `results/` | Pasta contendo gráficos e tabela de métricas finais. |
| `results/metrics.csv` | Tabela final com os resultados utilizados no artigo. |
| `results/*.png` | Gráficos de Loss, Perplexity e BERTScore. |

## Reprodutibilidade

Para garantir a replicação fiel do experimento, siga os passos abaixo:

1. **Ambiente:** Utilize o Google Colab com GPU T4.
2. **Dependências:** Instale exatamente as versões listadas no arquivo `notebook.ipynb`.
3. **Dataset:** O dataset utilizado deve ser carregado manualmente no ambiente com o nome `dataset_ementas_trt.txt`.
4. **Execução:** Execute o arquivo `notebook.ipynb` célula por célula.
5. **Resultados:** Os artefatos gerados serão salvos automaticamente dentro da pasta `results/`.

## Resultados

A tabela final de métricas e os gráficos produzidos pelo estudo encontram-se no diretório `results/`.

## Licença

Este projeto está licenciado sob a licença MIT.
