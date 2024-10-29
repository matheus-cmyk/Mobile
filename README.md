# **App FuelSaver/ App Calculadora de Potencia**

> Dois aplicativos de Android que funcione de forma fácil para o usuário.


## 📱 Descrição

Dois aplicativos de Android que funcione como uma calculadora de consumo de
combustível e outro que calcula o consumo de energia e o custo associado de diferentes aparelhos eletrônicos.


## 🔧 Funcionalidades da Calculadora de Potencia: 

- [x] Calcula o consumo de energia e o custo associado de diferentes aparelhos eletrônicos;
- [x] Formula
      CE = P X H / 1000
      C = CE X PKWH

     CE = Consumo de energia em quilowatts/hora
     p = Potência
     H = tempo de uso em horas (h)
     C = Custo da energia
     PKWH = Preço de energia por kwh

    Exemplo Prático:
    Consumo:  se uma lâmpada de 60 watts é usada por 5 hora, o consumo é:
    CE = 60 X 5 / 1000 = 0,3 kwh

    Custo:  se o preço da energia é de R$ 0,50 por kwh, o custo seria:
    c = 0.3 X 0.50 = R$0.15

## 🔧 Funcionalidades do App FuelSaver: 

- [x] Cadastro de Dados; 
- [x] Cálculo do Consumo de Combustível;
- [x] Cálculo do Custo da Viagem;
- [x] Exibição dos Resultados.

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView** e **EditText** para entrada e exibição de dados
- [x] **Button**   para executar o app.

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:

    ```bash
    git clone (https://github.com/matheus-cmyk/Mobile)

    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├──
│   │   │  
│   ├── MainActivity.java      
│   │   │   ├──
res
│   │   │  
│   ├── layout
│   │   │  
│   │   ├── activity_main.xml   #
Layout da tela principal
│   │   │  
│   └── values
│   │   │  
│       ├──strings.xml         # Strings usadas no
app
│   │   │  
│       ├── colors.xml          # Cores definidas no projeto
│   └── build.gradle                        # Configuração do
Gradle
└── README.md                               # Este arquivo

 
## 🎨 Design e Prototipagem
 
A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela.
 
O design é minimalista e fácil de usar, com foco na simplicidade.
 
  
## 👨‍💻 Desenvolvedores –

**Matheus Munhoz** - Desenvolvedor - [GitHub](https://github.com/matheus-cmyk)

 ## 📄 Licença
