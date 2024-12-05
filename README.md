# ClickBank - Sistema de Gerenciamento de Conta Bancária

**ClickBank** é um simples sistema bancário interativo que permite ao usuário realizar operações de depósito, saque e visualizar o extrato de sua conta. Este projeto foi desenvolvido para fins educativos e de aprendizado sobre operações bancárias básicas.

## Funcionalidades

O sistema oferece as seguintes funcionalidades:

- **Depositar**: Permite que o usuário deposite um valor em sua conta.
- **Sacar**: Permite que o usuário saque um valor, respeitando o saldo disponível, o limite diário de saque e o valor máximo por transação.
- **Extrato**: Exibe o saldo atual da conta do usuário.
- **Limite de Saque**: O sistema limita o valor máximo de saque a R$500,00 por transação e permite até 3 saques diários.
- **Verificação de Saldo**: Impede saques caso o saldo disponível seja insuficiente.

## Tecnologias

Este projeto foi desenvolvido em **Python** e não requer bibliotecas externas, o que o torna fácil de executar em qualquer máquina com Python instalado.

## Como Usar

1. **Clone este repositório** para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/ClickBank.git
Navegue até o diretório do projeto:

bash
Copiar código
cd ClickBank
Execute o programa:

bash
Copiar código
python main.py
Isso iniciará o sistema bancário interativo no terminal.

Exemplos de Interação
Ao executar o código, o sistema exibirá um menu interativo com as seguintes opções:

css
Copiar código
----ClickBank----
------Saldo------
--------0.00--------
[1] Depositar
[2] Sacar
[3] Extrato
[4] Sair
Escolha uma das opções acima:
Para depositar, digite o valor que deseja adicionar à sua conta.
Para sacar, insira o valor que deseja retirar, lembrando que o saque está limitado a R$500,00 por transação e a 3 saques diários.
Para ver o extrato, o saldo atual será exibido.
Para sair, o programa finalizará.
Funcionalidade de Saque
O saque tem as seguintes condições:

O valor do saque não pode ser superior ao saldo disponível.
O limite por saque é de R$500,00.
O limite diário de saques é de 3 saques por dia.
Saldo insuficiente: caso o saldo seja menor que o valor do saque, a operação não será realizada.
Contribuindo
Se você gostaria de contribuir para o desenvolvimento deste projeto, fique à vontade para enviar pull requests! Para isso, siga estas etapas:

Faça um fork deste repositório.
Crie uma nova branch (git checkout -b minha-nova-funcionalidade).
Realize as alterações necessárias.
Commit suas mudanças (git commit -am 'Adiciona nova funcionalidade').
Push para o repositório remoto (git push origin minha-nova-funcionalidade).
Envie um pull request.
Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
