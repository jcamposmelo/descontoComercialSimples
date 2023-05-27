# descontoComercialSimples
Desconto comercial simples, ou desconto por fora, é o desconto aplicado sobre o valor nominal, ou futuro, do título. O desconto é prática comumente exercida pelas instituições financeiras e no comércio em geral.

##

```
public class DescontoComercial {
    public static void main(String[] args) {
        double valorOriginal1 = 975.00;
        double valorOriginal2 = 250.00;
        double valorOriginal3 = 1200.00;
        double taxaDesconto1 = 0.25; 
        double taxaDesconto2 = 0.17;
        double taxaDesconto3 = 0.12;
        double valor_1;
        double valor_2;
        double valor_3;
        double valorFinal;

        double desconto1 = valorOriginal1 * taxaDesconto1;
        double desconto2 = valorOriginal2 * taxaDesconto2;
        double desconto3 = valorOriginal3 * taxaDesconto3;

        valor_1 = (valorOriginal1 - desconto1);      
        System.out.println("Valor da primeira compra: " + valor_1 + " reais");

        valor_2 = (valorOriginal2 - desconto2);
        System.out.println("Valor da segunda compra: " + valor_2 + " reais");

        valor_3 = (valorOriginal3 - desconto3);
        System.out.println("Valor da segunda compra: " + valor_3 + " reais");

        valorFinal = valor_1 + valor_2 + valor_3;
        System.out.println("Quanto eu gastei no final? "  + valorFinal + " reais");

    }
}
