1 - E
2 - D
3 - C
4 - A
5 - A
6 - C
7 - E


8 -

	public Integer criaC(int a, int b){
		String aString = String.valueOf(a);
		String bString = String.valueOf(b)
		String cString = "";
		int i = 0;
		while (aString.length() > 0 && bString.length() > 0){
			cString = cString + aString.charAt(0);
			cString = cString + bString.charAt(0);

			aString = aString.substring(1, aString.length()-1);
			bString = bString.substring(1, bString.length()-1);
		}
		cString = cString + aString;
		cString = cString + bString;

		Integer c = Integer.valueOf(cString);


		return c > 1000000 ? -1 : c;

	}

9 - 

	public int calculaValor (BinaryTree bTree){
		int valor = 0;
		if(bTree == null){
			return valor;
		}
		valor = calculaValor(bTree.left);	
		valor = valor + calculaValor(bTree.right);
		
		return valor + bTree.valor;
	}