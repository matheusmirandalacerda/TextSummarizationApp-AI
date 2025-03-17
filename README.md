Este projeto utiliza a biblioteca **LangChain** em conjunto com o modelo de linguagem **Claude-3** da **Anthropic** para processar um texto longo e gerar um resumo condensado. O objetivo principal do código é dividir um texto grande em partes menores, utilizando a funcionalidade de fatiamento de texto, e, em seguida, gerar um resumo coeso e preciso.

O modelo **Claude-3** foi configurado para proporcionar uma sumarização de alta qualidade, ajustando o nível de criatividade com base nas necessidades do projeto.

## Funcionalidade

- **Divisão de Texto**: O código usa a biblioteca **LangChain** para dividir o texto longo em partes menores.
- **Geração de Resumo**: O modelo de linguagem **Claude-3** é utilizado para criar um resumo coeso e informativo a partir das partes menores do texto.
- **Integração com Variáveis de Ambiente**: As chaves de API necessárias são gerenciadas com a ajuda da biblioteca **dotenv**, que carrega as variáveis de ambiente a partir de um arquivo `.env`.

## Tecnologias Utilizadas

- **LangChain**: Framework utilizado para construir e gerenciar o fluxo de dados entre diferentes componentes de processamento de linguagem natural.
- **Claude-3 (Anthropic)**: Modelo de linguagem utilizado para processar o texto e gerar resumos.
- **dotenv**: Biblioteca para carregar e gerenciar variáveis de ambiente de maneira segura.
- **Python**: Linguagem de programação utilizada para o desenvolvimento do código.


