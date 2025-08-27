# Como executar os códigos

1. Compile os dois programas:
   - Gerador de dados:
     gcc gerador.c -o gerador
   - Produto interno com threads:
     gcc produto.c -o produto -lpthread

2. Rode o gerador para criar o arquivo binário:
   ./gerador <N> <arquivo_saida>
   Exemplo:
   ./gerador 100000 entrada.bin

3. Rode o programa com threads para calcular o produto interno:
   ./produto <num_threads> <arquivo_entrada>
   Exemplo:
   ./produto 4 entrada.bin
