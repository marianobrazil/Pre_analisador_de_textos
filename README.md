# Pre_analisador_de_textos
Programa em Java para realizar a etapa de pré-processamento de um texto a ser analisado como dígrafo pela ferramenta de software livre Gephi. O programa deverá aceitar uma lista de nomes de arquivos do tipo texto simples (.txt) e, para cada um deles, gravar uma saída no formato .csv contendo listas de adjacências indicando sucessão de palavras para posterior construção dos dígrafos, como descrito a serguir:

• cada palavra é um nó único do dígrafo (início de uma lista de adjacência);

• o nó A tem um arco para o nó B se e somente se a palavra representada por B segue aquela representada por A no texto;

• cada linha do arquivo de saída inicia-se com a palavra que representa o nó de origem, seguida das palavras que são os destinos dos arcos que partem dela, separadas por espaços ou vírgulas (formato Gephi).

O restante da descrição do projeto está no documento projeto.pdf.
