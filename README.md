# Recifavela — Classificação de Resíduos Plásticos
### Parte 1: Carregamento, Exploração e Pré-processamento

**Grupo Verde | ecmgroup2 | Material: PEAD**

| Nome | RA |
|------|----|
| Leandro Meneghetti Fabre | 23.00099-6 |
| Enzo Pistori Fontenele de Oliveira | 23.00768-0 |
| Gustavo Henrique Lamberti Widonsck | 23.00438-0 |
| Pedro Kuba Bloise | 23.00161-5 |
| Michelle Mitie Hamazaki | 20.00539-3 |

## Dataset
**RealWaste** — [kaggle.com/datasets/joebeachcapital/realwaste](https://www.kaggle.com/datasets/joebeachcapital/realwaste)  
4.752 imagens reais de resíduos coletadas em aterro sanitário | Foco: classe **Plastic** (921 imagens)

Referências adicionais: [TACO](https://github.com/pedropro/TACO) | [Bottle Synthetic Images](https://www.kaggle.com/datasets/vencerlanz09/bottle-synthetic-images-dataset)

## Estrutura
```
notebooks/   → parte1_exploracao_preprocessamento.ipynb
```

## Como executar
```bash
pip install -r requirements.txt
# Baixar dataset: kaggle datasets download -d joebeachcapital/realwaste -p data/raw --unzip
jupyter notebook notebooks/parte1_exploracao_preprocessamento.ipynb
```
