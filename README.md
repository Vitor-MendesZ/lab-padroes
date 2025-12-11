# lab-padroes

## Descrição
Este projeto implementa um padrão de conexão segura com o banco de dados, utilizando **Design Pattern** para evitar *Hardcoding*.

## O que foi feito
- [X] Criação do repositório
- [X] Implementação da conexão
- [X] Resolução de conflito de Merge
- [X] Separação de configuração

## Exemplo de uso
Abaixo, o código padrão utilizado pelo Arquiteto:

```python
# Constante de configuração
DB_HOST = "192.168.0.1"

def configurar_banco():
  """Conecta usando a constante definida"""
  return f"Conectado ao {DB_HOST}"
