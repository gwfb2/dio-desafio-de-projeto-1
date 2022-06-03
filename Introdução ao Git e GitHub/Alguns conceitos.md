Alguns conceitos de GitHub



- **Commit**: uma representação dos arquivos e diretórios do projeto em um certo ponto no tempo. Possui atributos como: parente (commit anterior), comentário, autor, data e hora e uma chave criptográfica que representa todo o conteúdo dela.
- **Tree**: uma representação de um diretório no repositório que pode apontar para outras trees ou arquivos. Também possui seus atributos como a chave criptográfica.
- **Blob**: contém a chave cript. dos arquivos na tree na qual se encontra. Se o conteúdo de um arquivo é alterado, sua chave identificadora também é, causando o mesmo para a tree e o commit. 
- **Branch**: ramificação do projeto, as mudanças nela feita não causa alterações na branch principal (main/master) do projeto. Posteriormente pode ser feito o merge das branches.