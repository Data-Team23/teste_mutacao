# Teste de Mutação
Este projeto é desenvolvido usando Python e inclui testes de mutação com MutPy. Este documento fornece instruções sobre como configurar o ambiente do projeto e executar testes de mutação.

## Pré-requisitos
- **pyenv**: Uma ferramenta para gerenciar múltiplas versões do Python.
- **Python 3.6**: A versão específica do Python utilizada neste projeto.
- **pip**: Instalador de pacotes Python.

## Configurando o Ambiente
### Instalar pyenv

Siga as instruções de instalação para o seu sistema operacional no [repositório do GitHub do pyenv](https://github.com/pyenv/pyenv).

### Instalar Python 3.6 usando pyenv
Uma vez que o pyenv esteja instalado, execute o seguinte comando para instalar o Python 3.8.10:

```bash
  pyenv install 3.6
  pyenv local 3.6
  pip install -r requirements.txt
```

### Executar testes de mutação pelo mutpy
```bash
  mut.py --target calculator --unit-test tests -m
```
