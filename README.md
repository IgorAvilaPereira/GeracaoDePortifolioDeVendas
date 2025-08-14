# GeracaoDePortifolioDeVendas

Este projeto automatiza a geração de portfólios de vendas a partir de imagens organizadas em um diretório. Ele possui scripts para gerar portfólios nos formatos HTML e Markdown, facilitando a apresentação dos produtos.

## Estrutura do Repositório

- `gerar_portifolio_html.sh`: Script para gerar o portfólio em formato HTML.
- `gerar_portifolio_markdown.sh`: Script para gerar o portfólio em formato Markdown.
- `README.md`: Documentação do projeto.

## Como executar os scripts Bash para gerar o portfólio

### Pré-requisitos

- Sistema com Bash (Linux, macOS ou Windows com WSL/Git Bash).
- Permissão para executar scripts.
- Coloque as imagens na mesma pasta onde os scripts estão localizados, ou execute os scripts na pasta que contém as imagens.

### Passos para executar

1. Abra o terminal na pasta onde estão as imagens e os scripts (ou copie os scripts para a pasta das imagens).

2. Garanta que os scripts têm permissão de execução (caso ainda não tenham):

```bash
chmod +x gerar_portifolio_html.sh
chmod +x gerar_portifolio_markdown.sh
````

3. Execute o script desejado:

* Para gerar o portfólio em HTML:

```bash
./gerar_portifolio_html.sh
```

* Para gerar o portfólio em Markdown:

```bash
./gerar_portifolio_markdown.sh
```

4. Verifique o arquivo gerado na mesma pasta (`portifolio.html` ou `portifolio.md`) e abra com seu navegador ou editor de texto preferido.

