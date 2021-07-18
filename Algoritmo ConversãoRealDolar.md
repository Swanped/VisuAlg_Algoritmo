	Algoritmo "ConversãoRealDolar"
	// Disciplina   : [Linguagem e Lógica de Programação] 
	// Professor   : Antonio Carlos Nicolodi 
	//rotina que converte um determinado valor em reais em dólares

	Var

 	 Valor_real,Cotacao_dolar, Conversao: real
 	 Cont, Q: inteiro


	Inicio
        cont <- 1
        Escreval (" ----------------------------------------------")
        Escreval ("|    Programa para converter reais em dolar    |")
        Escreval ("|         Quantas vezes vamos converter?       |")
        Escreval (" ----------------------------------------------")
        Leia(Q)
        
	Enquanto (Cont <= Q) faca
	     
	 Escreva ("Informe o valor disponivel em reais: ")
	     Leia (Valor_real)
	     Escreva ("Informe o valor(cotação) do dolar em reais: ")
	     Leia(Cotacao_dolar)
	     Conversao <-Valor_real/Cotacao_dolar
	     Escreval ("Será possivel comprar: U$", Conversao," Dolar")
	     cont <- cont + 1
	    
	Fimenquanto


	Fimalgoritmo

