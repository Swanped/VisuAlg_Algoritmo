	Algoritmo "CriançaEsperança"

	// Data atual  : 29/06/2021
	Var

	D: inteiro
	Valor: real

	Inicio
		 Escreva (" __________________________________________" )
		Escreval ("|                                          |")
		Escreval ("|       Bem-vindo ao Criança Esperança     |")
		Escreval ("|                 Vamos Doar?              |")
		Escreval ("| 1. Doar 10 reias                         |")
		Escreval ("| 2. Doar 20 reias                         |")
		Escreval ("| 3. Doar 40 reias                         |")
		Escreval ("| 4. Doar 60 reias                         |")
		Escreval ("| 5. Doar  qualquer valor                  |")
		Escreval ("| 6. Sair                                  |")
		Escreval ("|__________________________________________|")
		Leia (D)


	 Escolha D
		caso 1
		valor <- 10
		caso 2
		 valor <- 20
		 caso 3
		 valor <- 40
		caso 4
		valor <- 60
		caso 5
	Escreva("Por favor informe o valor de sua doação: ")
		Leia (Valor)
		caso 6
		Interrompa
		outrocaso
		Escreval ("Opção inválida")
	      Fimescolha
	Escreval ("----------------------------------------------")
	Escreval ("           MUITO OBRIGADO")
	Escreval ("   Agradecemos pela a sua ajuda de RS" ,Valor)
	Escreval ("----------------------------------------------")
	Fimalgoritmo
