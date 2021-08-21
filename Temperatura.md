            Algoritmo "Temperatura "

            Var
               celsius, fahrenheit, Sair, Opcao: real


            Inicio
                 Escreval (" -------------------------------------" )
                 Escreval ("|      Escolha as opções abaixo:      |")
                 Escreval ("|1.Fahrenheit/Celsius                 |")
                 Escreval ("|2.Celsius/Fahrenheit                 |")
                 Escreval ("|3.Sair                               |")
                 Escreval (" -------------------------------------")
                 Escreva (" Digite sua opção: ")
                 Leia (Opcao)
                 Se (Opcao = 1) Entao
                  fahrenheit <-Opcao
                  Escreva ("Qual a temperatura em Fahrenheit? ")
                  Leia(fahrenheit)
                  celsius <- ((fahrenheit-32)*5/9)
                  Escreva ("A temperatura em Celsius é: ",celsius)
                  Senao
                  se (Opcao=2) Entao
                   celsius <-Opcao
                    Escreva ("Qual a temperatura em Celsius? ")
                   Leia(celsius)
                   fahrenheit <- ((celsius *9/5)+32)
                   Escreva ("A temperatura em Fahrenheit é: ",fahrenheit)
                 Senao
                  se (Opcao=3)entao
                  Sair <-Opcao
                  Escreva ("Fim")
                 Fimse
                 Fimse
                 Fimse


            Fimalgoritmo
