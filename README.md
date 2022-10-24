# gege
pseudocódigo lanchonete

programa{
	funcao inicio()	{
		inteiro op
		cadeia titulo
		escreva("Digite a opção de 1 a 5: ")
		leia(op)
		escolha(op){
			caso 1: 
		 		escreva ("Opção 1")
		 		pare   
		 	caso 2: 
		 		escreva ("Opção 2")
		 		pare   
		 	caso 3: 
		 		escreva ("Opção 3")
		 		pare
		 	caso 4: 
		 		escreva ("Opção 4")
		 		pare   
		 	caso 5: 
		 		escreva ("Opção 5")
		 		pare
		 	caso contrario: // Será executado para qualquer opção diferente de 1 a 5
		 		escreva ("Opção errada !")
		}
        escreva("\nTitulo : " ,op)
		
	}
}
