# DIO.-Sistema-de-Recomendcao-de-Imagens-com-CIFAR-10

# Sistema de Recomendação de Imagens com CIFAR-10

Este projeto usa uma ResNet-18 pré-treinada para extrair vetores de imagens do dataset CIFAR-10 e encontra imagens visualmente similares usando Annoy.

## Como funciona

1. Baixa e salva imagens do CIFAR-10
2. Extrai vetores com ResNet-18
3. Cria índice Annoy
4. Busca imagens similares

## Requisitos

- Python 3.8+
- torchvision
- annoy
- matplotlib

## Instalação

```bash
pip install -r requirements.txt
