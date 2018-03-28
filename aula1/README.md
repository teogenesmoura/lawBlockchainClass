# Blockchain & Data Science aplicados ao Direito e à sociedade

# Aula 1

## Introdução

Nessa aula, abordaremos os seguintes tópicos:
- Criar uma _wallet_ de Bitcoin;
- Realizar uma transação;
- Visualizar transações na Blockchain usando uma ferramenta chamada _Block Explorer_;

## Criando uma Wallet

A _wallet_ é a representação da sua conta de criptomoedas. Com ela, você poderá receber e enviar criptomoedas para outras contas. Uma wallet de criptomoedas é 

**Nota:** Antes de darmos continuidade ao conteúdo, é preciso esclarecer a diferenlça entre dois conceitos: _Wallet_ e _Endereço_. Diferente da sua conta bancária, onde a representação de uma única conta bancária é feita através de uma única combinação entre agência e conta corrente, uma _wallet_ de criptomoedas pode ser representada por uma combinação infinita de _endereços_ de criptomoedas, sendo que a soma dos saldos destes _endereços_ equivale ao saldo da sua _wallet_. Entretanto, o termo _wallet_ vem sendo usado como sinônimo do termo _endereço_, uma vez que ambos os conceitos são semelhantes para quem usa apensa um _endereço_, então não faremos distinção entre estes termos no decorrer das aulas.

Nesta aula, você irá aprender a criar uma _wallet_ na corretora Mercado Bitcoin para poder enviar e receber transações a partir dele. Como o _endereço_ está sendo criado dentro de uma _corretora_, você também poderá realizar a compra de criptomoedas usando Reais. 

É importante destacar que as corretoras recomendam usar suas _wallets_ somente durante o processo de compra ou venda de criptomoedas, **não recomendando armazenar permanentemente suas criptomoedas nela**. Esta recomendação é dada graças a natureza do Bitcoin, que impede que um ato administrativo desfaça uma transação. Sendo assim, caso seja descoberta uma falha de segurança nos sistemas de uma corretora, o saldo de seus clientes não será comprometido. Para poder armazenar seus Bitcoins de maneira segura, recomenda-se usar um aplicativo que mantenha sua _chave privada_ longe da internet. Estes aplicativos serão apresentados mais a frente no curso.


### Cadastrando-se na Mercado Bitcoin

1 - Acesse o [ite da Mercado Mitcoin](https://www.mercadobitcoin.com.br/)
2 -  Clique em `Cadastre-se`.


![Tela de Cadastro](https://i.imgur.com/wQqYmCE.png "Tela de Cadastro")

3 - Insira suas informações, confime que você não é um robô e clique em `Cadastrar`.


![Formulário de Cadastro](https://lh5.googleusercontent.com/xG86F_FLL3sE7QFtYGiYARbarFhK7OpbY87qjZwKwot4QNP_PLNYuq0p0Xy-_H4dY6MxfLqsYpZGU49aVqHY3EGAWXAa_zn_4DMQ2H8EuCGh1f_VDcVL2ysp30dv9GV48UCRlew)

4 - Após fazer o cadastro, clique em `Login` e insira seus dados. Confirme-os e acesse a página principal.


![Login](https://lh4.googleusercontent.com/RZ3kgwkatxEyeq4OOuOIzt14069_Z9J1W8vB8FX2g3WjMRnmcMv8Q77RnUUbeVWzNPRmrQsZfu1qPzBGOSSFjg1WOLjYWIGdqGUeqFQhUxJSHFAB7kNLnDh4ReT_rwxuLH7ZPFk)

5 - Uma tela semelhante a tela seguir deverá aparecer. Esta é a tela principal da _corretora_.


![Painel](https://lh4.googleusercontent.com/WxEAcUwQiq-jNldugSinQqVWzdFg7CFbva3YxzJGw-dKcRI2zy0W5jlFBvKvPukdVAh2gN7yiuS9MtxDpLD8IA4HxFExcl3uAxBDgRB3I0Nak14Wy5oLLYiBjdfNU8EErvbd7jE)

6 - Primeiro é preciso fazer um depósito em reais no site para podermos comprar bitcoin, para isso é preciso fazer alguns ajustes de segurança.

6.1 - Clique no seu nome, no canto superior direito da tela e em seguida em `Configurações`. 


![Menu](https://lh5.googleusercontent.com/xyRMxb_i5JWeZsIDwOcG-xdzq4Ezk9sa6kNzpYOObZdmg2cOwedaATXe1hZqe4LmNVqYUwnZRBdi1yB5GvLgSZUmJBcNbut8Ocn-2Yv2dn8aojdOH3th0qqCb510GmPjSol9KG8)

7 - Clique em cada uma das pendências para tornar a conta mais segura. O sinal de exclamação vermelho significa que existem pedendências na segurança, enquanto o _check_ verde significa que esta tudo certo. Clique em cada uma das pendência e siga as instruções apresentadas na tela.


![Pendencias](https://lh5.googleusercontent.com/LYM9GZc-Cl6-iT8zpINfGAROj1b9-A62BpILno4r5bfvYf6Ir_4n0qJ8at7gd2jwAKq8jCc2AaVlwV1I22DKxwZgazNN48D57PAqw7PuW7PGduUlcwmD7iRjqFKR6fwgjel1W1Y)


### Depositando Reais na Mercado Bitcoin

8 - Volte para a tela inicial e clique em `Depósito`.


![Depósito](https://lh6.googleusercontent.com/cnjVYWBsmPk-sFCPKvCWBlpOV7l51A2qTM2g9xFKfIdnDOUts7H01VkaONUZafWgcD9I_yW-qSIXbbKjtgzzbeDPxDVBee0UbAP9MpA_h_pshhv8Kn3NLhhJDs24JspdiKn8NS8)

9 - Preencha o formulário conforme o método de depósito e valor desejados e clique em `Enviar`.


![Método](https://lh3.googleusercontent.com/3P5n30szkHkYnbF2-BranZY8fQ5X1bGuAbSXzeVEEEg9J46qk4YkLKPhH0qkKWAg8v7fwiMJu0YHRNYZVoh_YH9Fm8F8NyibkfTf9AEGVBym1GK0n7Qh3xnfNPAj_OLPpkmO4bM)

10 - Anexe o comprovante do depósito e espere até que a Mercado Bitcoin reconheça o depósito e confirme-o. **Atenção:** O envio do comprovante é necessário para que o depósito seja compensado. O não envio deste poderá impedir a compensação.


![Anexo](https://lh4.googleusercontent.com/_hojooAvX3Ef30QTiJpPY1sMfVf5tJWtJVgz-G6oqlUyDsPA_W0bZvqdbGM4hVMDwhhXyF_sjZXaLMlhyE66dNJCjGZZzYfAFSR1NigKQkqPSeTJgBjM_eADygbH3ZybTUfc4No)


### Comprando Bitcoins com seu saldo em Reais

11 - Selecione a opção `Comprar` para comprar Bitcoins, na Página Inicial.


![Comprar](https://lh5.googleusercontent.com/wP8yPcAjiD4ot2NtkamJznrI5qqf5ERdYoA80XBHxlfPN71-jtmdI4-CmCajJXT90d1XqxoempX-At7WJnVsM-Oy-RgapK5y6nRy_PDHT6IhWb1XuJtaWVevYqy5ytQClUC73cU)

12 - Insira o valor em Reais que deseja comprar e clique em `Comprar`. Lembre-se que é necessário que a Mercado Bitcoin já tenha recebido seu depósito para realizar a compra. 


![Comprar2](https://lh6.googleusercontent.com/UrxN2cpD14xe0UQFsCXw9MG8bftwYksiTZ_csX01P_1JPFepxPplwoECPfzz-qCawgowaA7XRzEJFMmK1__yAFEjAyf-9ErdlWxpAut-TCFZzfArQYov1OB4XaeD5lqIIijFSqw)

Feito isso, você verá seu saldo em Bitcoins aumentar e seu saldo em Reais diminuir na barra lateral esquerda. É importante destacar que existem taxas no processo de compra e venda de Bitcoins, então você verá seu saldo total diminuir um pouco a cada operação.

### Vendendo seus Bitcoins

13 - Para vender seus Bitcoin basta clicar em `Vender`.


![Vender](https://lh4.googleusercontent.com/FBpRJltTPQi_6a2SqG5s-sbnSHAbnB25IP6P_z1gZ-vieiJgo8ns5oIv3jaXUZEIvLn2p48TuUOCiq0uYLA4lC7U2x8occvZzrttHwpqXM4j_TwT0tAII768N7hXygjKX28a9Uw)

14 - Selecione quantos Bitcoins deseja vender e clique em `Vender`. Da mesma forma que a compra, você verá uma alteração de saldos na barra lateral esquerda.


![Vender2](https://lh4.googleusercontent.com/hlPlbbEFaPxu0C9MwIUDTwDB38T1KG-wzckoFiFmvFycKlwmnrYNGe53SFFJXohiXZkpQ186VpIWdldh-uvmGQd2zDinZKAkoSJQ5sOaVdZ6iuzBlNQGzeoQ8iy1Dw4kUTdK91g)

### Realizando um Saque em reais 

15 - Para sacar o dinheiro que está na sua conta da Mercado Bitcoin basta acessar a Página Principal e clicar em `Sacar`.

![Sacar](https://lh5.googleusercontent.com/aHC-hzLQ4-uvfvN8rn1Rp-BDiOX0GXLnIdztC9RBf6gUgF81dLgdgH17WdD_-22gOkfc11y--0sM0PJ59XhCWUyAaEEjIjn2PiQNcFbA8ZkwsI2UMMWqrYacKG4qJ5axZoSIJt4)

16 - Insira suas informações de conta e clique em `Solicitar Saque`.

![Sacar2](https://lh6.googleusercontent.com/Ukwr6hItWocuBpogtYwUYR9WUvJ40hJF4rEB6VNfzBUiTlePbEqV7HVc2dpjEw2j8Dr8rZLGMzkKirfMIfp_FdSg6bdgnFEuXf39Vi1jK-LSU0ytbbAJSzjWlY5589FyCe5Ig8I)


### Acessando o _endereço_ de depósito

1 - Na Página Principal do Mercado Bitcoin, após efetuado o login, clique em `Receber`.

2 - Na tela a seguir, o endereço mostrado é o endereço da sua carteira. Este endereço é usado para receber depósitos em sua conta para poder vender Bitcoins e transformá-los em Reais. 

![Receber](https://i.imgur.com/hceilKz.png)

Neste caso, o endereço da carteira é:

```12nMv7wTJ5dzoeuqRaZ2JgZRoLLKShy9UW```

Existem duas coisas interessantes a serem explicadas sobre este endereço. A primeira é que ele se inicia pelo número 1 e a segunda é que ele não possui caractéres que são visualmente semelhantes, como por exemplo `O` (o maiúsculo) e `0` (zero) ou `I` (i maiúsculo) e `l` (L minúsculo). O protocolo do Bitcoin estabelece que os _endereços_ sejam formatados assim para facilitar seu uso e evitar erros de digitação. Também é importante destacar que este modelo de _endereço_ possui alguns dígitos verificadores escondidos, que impedem uma transação caso algum dado esteja incorreto.

### Visualizando transações

Todas as transações dentro da _corrente de blocos_ do Bitcoin são públicas. Para consultá-las, você deverá usar uma ferramenta chamada `Block Explorer`. A finalidade desta ferramenta é prover uma interface amigável ao _blockchain_, facilitando a pesquisa por transações, endereços e blocos.

Existem vários `Block Explorers` na internet. O que vamos usar é o [BlockExplorer.com](https://blockexplorer.com;). 

```https://blockexplorer.com/blocks```

## Entrega

Para esta aula, poste no canal #entregaKits do nosso Slack as seguintes informações:

- Nome;
- Matrícula;
- Endereço da sua _wallet_ criada usando o procedimento acima;

Em caso de dúvida, entre em contato com a turma através do Slack.

