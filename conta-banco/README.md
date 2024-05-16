## Projeto Conta Terminal

**Desenvolvimento do projeto de conta Terminal que tinha as seguintes demandas:**

Entradas Esperadas
- Número da Conta: Um número inteiro, por exemplo, 1021
- Agência: Um texto no formato NNN-N, por exemplo, 067-8
- Nome do Cliente: Um texto, por exemplo, MARIO ANDRADE
- Saldo Inicial: Um número decimal, por exemplo, 237.48

Saída esperada:
= Olá MARIO ANDRADE, obrigado por criar uma conta em nosso banco, sua agência é 067-8, conta 1021 e seu saldo 237,48 já está disponível para saque.

## Modificações em relação à demanda inicial

- Acrescentadas verificações em relação ao tipo de dados entrados e ao padrão dos mesmo, com mensagem de erro para coreção
- Acrescida uma linha em branco entre as solicitações de entrad apara dar mais legibilidade ao cliente
- Acrescido os símbolo de R$ na saída espera, uma vez que estamos falando de dinheiro
- Linguagem padrão PT-BR
  
### OS arquivos estão em duas pastas padrão

- src: a pasta para manter os fontes
- lib: a pasta para manter as dependências

- **Enquanto isso, os arquivos de saída compilados serão gerados na pasta bin por padrão.**
