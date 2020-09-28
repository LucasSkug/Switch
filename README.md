# Switch

//Programa que mostra ao usuario opção de alimentos

     String alimento;
		
		Scanner entradaDados = new Scanner(System.in);
		
		System.out.println("Digite o tipo de alimento que deseja:");
		System.out.println("01. Não pereciveis");
		System.out.println("02. Frutas");
		System.out.println("03. Bebidas");
		
		alimento = entradaDados.nextLine();
		
		switch (alimento) {
			case"1":
				System.out.println("Arroz, feijão, café");
				break;
			case"2":
				System.out.println("Manga, banana, maça");
				break;
			case"3":
				System.out.println("Leite, suco refrigerante");
		}
    
    
   //Programa que da ao usuario o poder de escolhe de 3 frutas, e em cada caso diz se há disponibilidade ou não
 
     String fruta;
		
		Scanner entradaDados = new Scanner(System.in);
		 
		System.out.println("Informe a fruta que deseja");
		System.out.println("Maça");
		System.out.println("Kiwi");
		System.out.println("Melancia");
		
		fruta = entradaDados.nextLine();
		
		switch (fruta) {
		case "maça":
			System.out.println("Não vendemos essa fruta aqui");
			break;
		case "kiwi":
			System.out.println("Estamos com escassez de kiwi");
			break;
		case"melancia":
			System.out.println("Aqui está, são 3 reais o kilo");
			break;
		}
    
    
   //Programa que mostra ao usuario 4 tipos de modelos automotivos e oq eu acontece quando ele escolhe algum
    
    String carro;
		
		Scanner entradaDados = new Scanner(System.in);
		
		System.out.println("Informe o modelo que deseja comprar");
		System.out.println("Sedan");
		System.out.println("Hatch");
		System.out.println("Motocicleta");
		System.out.println("Caminhonete");
		
		carro = entradaDados.nextLine();
		
		switch(carro) {
		case "sedan":
			System.out.println("Tem certeza que não prefere outro modelo");
			break;
		case "hacth":
			System.out.println("Compra efetuada com sucesso");
			break;
		case"motocicleta":
			System.out.println("Tem certeza que não prefere outro modelo");
			break;
		case "caminhonete":
			System.out.println("Tem certeza que não prefere outro modelo");
			break;
		
		
		}			
