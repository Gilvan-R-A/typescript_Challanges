# desafios_TypeScript   

Projeto criado para solucionar os desafios de código TypeScript propostos no Santander Bootcamp Fullstack Developer da Digital Innovation One.

## Ferramentas necessárias   
 
* Node instalado  
* Instalar o typescript usando o npm (npm install -g typescript)
* Uma IDE como o visual studio code   

## Os Desafios   

**Desafio 1**   
```javascript
// Como podemos rodar isso em um arquivo .ts sem causar erros? 

let employee = {};
employee.code = 10;
employee.name = "John";   

```   

**Desafio 2**   
```javascript
// Como podemos melhorar o esse código usando TS?

 let pessoa1 = {};
 pessoa1.nome = "maria";
 pessoa1.idade = 29;
 pessoa1.profissao = "atriz"
 let pessoa2 = {}
 pessoa2.nome = "roberto";
 pessoa2.idade = 19;
 pessoa2.profissao = "Padeiro";
 let pessoa3 = {
     nome: "laura",
     idade: "32",
     profissao: "Atriz"
 };
 let pessoa4 = {
     nome = "carlos",
     idade = 19,
     profissao = "padeiro"
}   

```   

**Desafio 3**   
```javascript

// O código abaixo tem alguns erros e não funciona como deveria. Você pode identificar quais são e corrigi-los em um arquivo TS?

 export {}
 let botaoAtualizar = document.getElementById('atualizar-saldo');
 let botaoLimpar = document.getElementById('limpar-saldo');
 let soma = document.getElementById('soma');
 let campoSaldo = document.getElementById('campo-saldo');
 campoSaldo.innerHTML = 0
 function somarAoSaldo(soma) {
     campoSaldo.innerHTML += soma;
 }
 function limparSaldo() {
     campoSaldo.innerHTML = '';
 }
 botaoAtualizar.addEventListener('click', function () {
     somarAoSaldo(soma.value);
 });
 botaoLimpar.addEventListener('click', function () {
     limparSaldo();
 });
/**
    <h4>Valor a ser adicionado: <input id="soma"> </h4>
    <button id="atualizar-saldo">Atualizar saldo</button>
    <button id="limpar-saldo">Limpar seu saldo</button>
    <h1>"Seu saldo é: " <span id="campo-saldo"></span></h1>
 */   
 
 ```






















