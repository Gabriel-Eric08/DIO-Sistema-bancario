# Sistema Bancário via Terminal

## 📌 Sobre o Projeto
Este projeto é um sistema bancário simples desenvolvido em **Java** e executado via terminal. Ele permite operações básicas, como criação de contas, depósitos, saques e consultas de saldo.

## 🚀 Tecnologias Utilizadas
- Java 11+
- IntelliJ IDEA ou qualquer outra IDE compatível

## 📂 Estrutura do Projeto
```
BancoConta/
│── bin/
|   ├── Account.class
│   ├── ContaTerminal.java
│── src/
│   ├── Account.java
│   ├── ContaTerminal.java
│── lib/
│── .vscode/
│── README.md
```

## ⚙️ Como Executar
### **1️⃣ Clonar o Repositório**
```bash
git clone git@github.com:Gabriel-Eric08/DIO-Sistema-bancario.git
cd BancoConta
```

### **2️⃣ Compilar e Executar o Código**
Se estiver usando o terminal:
```bash
javac -d bin src/*.java
java -cp bin ContaTerminal
```
Ou execute o arquivo `ContaTerminal.java` diretamente pela IDE.

## 🏦 Funcionalidades
✅ Criar conta bancária
✅ Depositar valores
✅ Sacar valores
✅ Consultar saldo

## 💻 Exemplo de Uso
### **Criando uma Conta e Realizando Operações:**
```
Olá, seja bem vindo!
Para começar a usar o terminal, cadastre sua conta bancária no nosso sistema.
Por favor insira os dados solicitados abaixo:

- Nome de usuário: João
- Agência: 123-4
- Número da conta: 12345678
 
-----------------------------------------------------

Olá João! Obrigado por criar uma conta em nosso banco.
A sua é 123-4.
O número da sua conta é 12345678.
E o seu saldo inicial é de 00,00R$.
Para realizar um depósito ou saque basta acessar o menu abaixo.

MENU PRINCIPAL

1 - Consultar dados da conta
2 - Realizar um depósito
3 - Realizar um saque
Escolha uma opção: 2

----------------------------------

Digite o valor do depósito: 500.00
Depósito realizado com sucesso!

Caso deseje continuar a usar do terminal digite 1.
Caso queira encerrar a aplicação digite 2.
Escolha uma opção: 1

-----------------------------------------------
MENU PRINCIPAL

1 - Consultar dados da conta
2 - Realizar um depósito
3 - Realizar um saque
Escolha uma opção: 1

Certo! Aqui estão os dados da sua conta:

Nome de usuário: João
Agência: 123-4
Número da conta: 1234567
Saldo: 500,00

Caso deseje continuar a usar do terminal digite 1.
Caso queira encerrar a aplicação digite 2.
Escolha uma opção: 1

-----------------------------------------------

MENU PRINCIPAL

1 - Consultar dados da conta
2 - Realizar um depósito
3 - Realizar um saque
Escolha uma opção: 3
```

Se o usuário tentar sacar mais do que tem:
```
Digite o valor do saque: 600.00
Saldo insuficiente!
```

## 📌 Autor
Desenvolvido por [Gabriel Eric](https://github.com/Gabriel-Eric08). Contribuições são bem-vindas! 🚀

