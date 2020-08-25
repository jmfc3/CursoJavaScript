# CursoJavaScript

## Variaveis
* **let**  ➞ É uma variavel que funciona apenas no escopo onde foi declarada.
* **var**  ➞ É uma variavel que pode "ultrapassar" o escopo de onde foi declarada e pode ser usada fora desse scopo.
* **const** ➞ É uma varavel constante que nao pode ser modificada depois.
![](\images\const-vs-let-vs-var.png)
    >Pode se defenir varias variaveis numa so linha <br>
    ```let nome, idade, peso, altura```

## Tipos primitivos
* **string**
* **number**
* **boolean**
* **null**
>Uma variavel que nao for declarada fica com o valor __undefined__.

## Tipagem dinamica
* No javascript não é necessário informar o tipo de variavel que estamos a declarar, ele mesmo é responsável por fazer isso em tempo de execução
>A função __Typeof *variavel*__ devolve o tipo da variavel

## Objetos
* Os objetos guardam varios elementos
```javascript
    let pessoa = {
    nome: 'Ricardo',
    sobrenome: undefined,
    idade: 23,
    estaAprovado: true
}
```
* Para acessar um elemento especifico desse objeto 
```javascript
    pessoa.nome
```

## Arrays
* Os arrays são um conjunto de dados, dados esses que podem ser de qualquer tipo
* Os arrays podem ser acessados atravez de um indice 
* metodos de um array
**length** ➞ devolve o numero de elementos de um array
```javascript
    let familia = [true, 'maria', 23, 10]
    let segundaElemento = idades[1]
```

## Funções
* 