# SustentabilidadeJá

Repositório que deve ser utilizado como template inicial pelos grupos da matéria de Arquitetura e Desenho de Software.

## Introdução

Este repositório traz um template de repo de documentação a ser seguido pelos grupos de arquitetura e desenho de software.

## Tecnologia

A geração do site estático é realizada utilizando o [docsify](https://docsify.js.org/).

```shell
"Docsify generates your documentation website on the fly. Unlike GitBook, it does not generate static html files. Instead, it smartly loads and parses your Markdown files and displays them as a website. To start using it, all you need to do is create an index.html and deploy it on GitHub Pages."
```

### Configuração do Ambiente

1. Criar e ativar ambiente virtual:

    ```shell
    python -m venv venv
    .\venv\Scripts\activate
    ```

2. Instalar docsify:

    ```shell
    npm i docsify-cli -g
    ```

### Executando localmente

Para iniciar o site localmente:

1. Ative o ambiente virtual (se ainda não estiver ativo):

    ```shell
    .\venv\Scripts\activate
    ```

2. Execute o docsify:

    ```shell
    docsify serve ./docs
    ```

3. Acesse http://localhost:3000 em seu navegador

## Integrantes

<table>
  <tr>
    <td align="center"><a href="https://github.com/ArtyMend07"><img style="border-radius: 50%;" src="https://github.com/ArtyMend07.png" width="100px;" alt=""/><br /><sub><b>Artur Mendonça</b></sub></a><br /><a href="https://github.com/ArtyMend07"></a></td>
    <td align="center"><a href="https://github.com/lucasarruda9"><img style="border-radius: 50%;" src="https://github.com/lucasarruda9.png" width="100px;" alt=""/><br /><sub><b>Lucas Mendonça</b></sub></a><br /><a href="https://github.com/lucasarruda9"></a></td>
  </tr>
</table>

## Histórico de Versões

| Versão | Data       | Descrição | Autor | Revisor | Data da Revisão |
|--------|------------|-----------|--------|---------|-----------------|
| 1.0    | 02/09/2025| Adição das instruções de ambiente virtual | [Artur Mendonça](https://github.com/ArtyMend07) | [Lucas Mendonça](https://github.com/lucasarruda9) | 02/09/2025 |
