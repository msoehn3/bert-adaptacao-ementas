# BERTimbau - Adaptação ao Domínio Jurídico Trabalhista

[cite_start]Repositório oficial dos experimentos apresentados no artigo "Adaptação de LLMs para Ementas Trabalhistas: Uma Análise Comparativa de Estratégias de Treinamento e Tokenização", avaliando técnicas de continue pre-training, tokenização customizada e treinamento "do zero" para linguagem jurídica trabalhista[cite: 1, 2].

## Objetivo

[cite_start]Avaliar como diferentes estratégias de adaptação de domínio - incluindo variação do tamanho do corpus, tokenização customizada e treinamento do zero - afetam o desempenho de modelos BERT em tarefas de Masked Language Modeling (MLM) no domínio das ementas trabalhistas[cite: 3, 4].

## Estrutura do Repositório

| Arquivo/Pasta | Descrição |
| :--- | :--- |
| `notebook.ipynb` | [cite_start]Notebook completo com todos os experimentos[cite: 6]. |
| `config_used.json` | [cite_start]Configurações exatas usadas nas execuções[cite: 6]. |
| `dataset_ementas_trt.txt` | [cite_start]Dataset composto por 5.000 ementas trabalhistas[cite: 6]. |
| `results/` | [cite_start]Pasta contendo gráficos e tabela de métricas finais[cite: 6]. |
| `results/metrics.csv` | [cite_start]Tabela final com os resultados utilizados no artigo[cite: 6, 16]. |
| `results/*.png` | [cite_start]Gráficos de Loss, Perplexity, BERTScore e Heatmap[cite: 6]. |

## Reprodutibilidade

[cite_start]Para garantir a replicação fiel do experimento, siga os passos abaixo[cite: 8, 9]:

1.  [cite_start]**Ambiente:** Utilize o Google Colab com GPU T4[cite: 10].
2.  [cite_start]**Dependências:** Instale exatamente as versões listadas no arquivo `config_used.json`[cite: 11].
3.  [cite_start]**Dataset:** O dataset utilizado deve ser carregado manualmente no ambiente com o nome `dataset_ementas_trt.txt`[cite: 13].
4.  [cite_start]**Execução:** Execute o arquivo `notebook.ipynb` célula por célula[cite: 12].
5.  [cite_start]**Resultados:** Os artefatos gerados serão salvos automaticamente dentro da pasta `results/`[cite: 14].

## Resultados

[cite_start]A tabela final de métricas e os gráficos produzidos pelo estudo encontram-se no diretório `results/`[cite: 15, 16, 18].

## Licença

[cite_start]Este projeto está licenciado sob a licença MIT[cite: 19, 20].
