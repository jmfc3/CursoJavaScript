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
* Pedaços de codigo que resolvem um pedaço do problema
* Funções podem returnar alguma coisa, ou apenas realizar uma tarefa sem returnar nada
```javascript
    function resetaCor(c, tonalidade) {
        cor = c + ' ' + tonalidade
        return cor
    }
    let corAplicacao = resetaCor("verde", "claro")
```

## Operadores
### Aritmeticos
    ➞ +(adição), -(subtração), *(multiplicação), /(divisao), **(exponencial)
### Atribuição
    ➞ = (igual), +=, -=, *=, /= 
### Comparação
    == ➞ compara os valores
    === ➞ compara os valores e o tipo dos valores
### Logicos

### Bitwise

### Incrementação
    ➞ ++ (incremento), -- (decremento)
    ➞ idade++ (mostra a idade e depois incrementa)
    ➞ idade-- (mostra a idade e depois decrementa)
    ➞ ++idade (incrementa e depois mostra o valor)
    ➞ --idade (decrementa e depois mostra o valor)