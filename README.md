package com.mycompany.atividadecarro;
public class AtividadeCarro {
    public static void main(String[] args) {  
            
        Carro umCarro = new Carro ();
        umCarro.modelo = "Gol";
        umCarro.cor = "preto";
        umCarro.motor = "1.0";
        
        umCarro.ligar();
        umCarro.mudarMarcha();
        umCarro.acelerar();
        umCarro.brecar();
        umCarro.desligar();
        umCarro = null;
        
    }
}


package com.mycompany.atividadecarro;
public class Carro {
     String cor;
    String modelo;
    String motor;
    
    void ligar(){
    System.out.println("Ligando o carro");
    }

    
    void desligar(){
    System.out.println("Desligando carro");
    }
    
    void acelerar(){
    System.out.println("Acelerando o carro");
    }
    
    void brecar(){
    System.out.println("Brecando o carro");
    }
    
    void mudarMarcha(){
    System.out.println("Marcha engatada");
    }
}
