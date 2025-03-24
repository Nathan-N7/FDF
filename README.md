# fdf

Projeto desenvolvido para renderização gráfica utilizando a biblioteca MiniLibX. Este repositório contém o código fonte que, ao ser compilado, gera um executável que recebe um mapa como argumento e exibe a renderização.

## Requisitos

- **GCC ou Clang**: Compilador C compatível com as flags `-Wall`, `-Werror` e `-Wextra`.
- **Make**: Para executar as instruções do Makefile.
- **MiniLibX**: Biblioteca para renderização gráfica (inclusa no repositório em `minilibx-linux`).
- **Bibliotecas X11 e Math**: Necessárias para o funcionamento da MiniLibX.

## Estrutura do Projeto

- **src/**: Arquivos fonte (.c) do projeto.
- **libft/**: Biblioteca auxiliar de funções utilitárias.
- **gnl/**: Implementação da função `get_next_line`.
- **minilibx-linux/**: Biblioteca MiniLibX para Linux.

## Compilação

Para compilar o projeto, execute:

```bash
make
Este comando compila os arquivos fonte, gera os objetos, compila as bibliotecas necessárias e cria o executável fdf.

Execução
Após a compilação, execute o programa passando o mapa como argumento:

bash
Copy
Edit
./fdf caminho/para/seu/mapa.fdf
Exemplo:

bash
Copy
Edit
./fdf maps/mapa1.fdf
Certifique-se de que o arquivo de mapa esteja formatado corretamente de acordo com os requisitos do projeto.

Limpeza
Para remover os arquivos objetos e outros arquivos gerados durante a compilação, utilize:

bash
Copy
Edit
make clean
Se desejar remover também o executável e as bibliotecas compiladas, utilize:

bash
Copy
Edit
make fclean
Reconstrução Completa
Para forçar uma recompilação completa do projeto:

bash
Copy
Edit
make re
Considerações
Certifique-se de que todas as dependências estejam instaladas e corretamente configuradas no seu ambiente.

Caso encontre algum problema durante a compilação ou execução, verifique as versões do compilador e das bibliotecas necessárias.
