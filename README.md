# exila

**exila** é uma ferramenta de linha de comando desenvolvida em Python que permite salvar o conteúdo de arquivos legíveis (como arquivos de texto) de um diretório e seus subdiretórios em um único arquivo de saída. 

## Requisitos

- Python 3

## Instalação

    ```sh
    sudo dpkg -i exila_0_0_amd64.deb
    ```

## Uso

Para usar a ferramenta `exila`, execute o seguinte comando no terminal:

```sh
exila <diretorio> <arquivo_saida> --ignored .mp3 .mp3 .img  # <--extensões a ignorar
