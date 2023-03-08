# senai-logica-4aAtividade1
<h1>Desenvolvimento de algoritmo para um sistema de controle de estoque de peças</h1>
Esse sistema terá como função principal a de controlar a entrada e saída de peças do estoque, além de atender aos seguintes requisitos:

- a empresa possui apenas uma peça a ser controlada;
- o sistema deverá solicitar sempre o saldo inicial da peça uma única vez a cada vez que o sistema é iniciado;
- o sistema deverá ter dois tipos de entrada de dados:  
    1 = compra (entrada) de peças
    2 = venda (saída) de peças
- enquanto o usuário não encerrar a entrada de dados, o sistema deverá continuar solicitando nova entrada de dados:
    - os dados de entradas são: tipo de entrada e quantidade de peças;
    - caso a entrada seja do tipo 1 (compra), somar a quantidade ao estoque da peça;
    - caso a entrada seja do tipo 2 (venda), subtrair a quantidade do estoque da peça caso a quantidade de entrada seja inferior ou igual ao saldo de estoque. Caso seja informado uma quantidade maior que o saldo da peça, apresentar a mensagem “Saldo insuficiente" e desconsiderar atualização de saldo;
    - a cada entrada de dados, apresentar o saldo atualizado do estoque;
    - ao final de cada entrada de dados, perguntar se o usuário deseja continuar (s) ou não (n) a entrada de dados;
- caso o usuário encerre o sistema, apresentar a mensagem "Sistema encerrado".
