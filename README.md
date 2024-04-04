# Combinador de CSV

O Combinador de CSV é um script Python projetado para automatizar a tarefa de combinar múltiplos arquivos CSV em um único arquivo. Ele verifica se cada arquivo não está vazio antes de processá-lo, garantindo que apenas dados válidos sejam incluídos no arquivo final.

## Funcionalidades

- Busca por arquivos CSV em um diretório especificado.
- Verifica se os arquivos não estão vazios antes de tentar lê-los.
- Combina todos os arquivos CSV válidos em um único DataFrame do pandas.
- Salva o DataFrame combinado como um novo arquivo CSV no mesmo diretório.

## Como usar

### Pré-requisitos

Para utilizar este script, você precisa ter o Python instalado em seu sistema, além das bibliotecas pandas e glob. Você pode instalar as dependências necessárias usando o seguinte comando:

pip install pandas

### Execução

1. Modifique a variável `caminho_csv` no script para apontar para o diretório que contém seus arquivos CSV.
   
   ```python
   caminho_csv = 'C:\\Seu\\Diretório\\Aqui\\'

2. Execute o script Python.
   ```python
  python combinador_csv.py

## Notas
  - Certifique-se de que o caminho para o diretório termine com uma barra (\\ no Windows ou / em sistemas baseados em Unix).
  - O script ignora arquivos CSV vazios automaticamente.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para forkar o repositório e submeter suas pull requests.

## Licença

[MIT](https://mit-license.org/)
