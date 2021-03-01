# IMC  Java  
## Programa ao ser executado, Mostrará se estamos gordinhos :stuck_out_tongue_winking_eye:  

```
public class IMC {
	public static void main(String[] args) {
  
		Scanner sc = new Scanner(System.in);
		
		//Variaveis
		double peso, altura, IMC;
		
    //Entrada de dados peso
		System.out.print("Digite opeso: ");
		peso = sc.nextDouble();
		
    //Entrada de dados altura
		System.out.print("Digite a altura: ");
		altura = sc.nextDouble();
		
    //Processsamento
		IMC = peso / (altura * altura);
	
    // Lógica para verificar o IMC
		if(IMC < 18.5) {
			System.out.println("Abaixo do peso.");
		}else if(IMC < 24.9 ) {
			System.out.println("Peso Ideal");
		}else if(IMC < 29.9) {
			System.out.println("Levemente acima do peso");
		}else if(IMC < 34.9) {
			System.out.println("Obesidade grau I");
		}else if(IMC < 39.9) {
			System.out.println("Obesidade grau II");
		}else {
			System.out.println("Obesidade III");
		}
	}
}

```
