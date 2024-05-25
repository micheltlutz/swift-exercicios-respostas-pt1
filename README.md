# Parabéns!

🎉 **Parabéns por completar o desafio!** 🎉

Você conseguiu desembaralhar a string e descobrir a URL original. Isso mostra que você está no caminho certo para se tornar um desenvolvedor Swift habilidoso.

Como recompensa, aqui está o link para o repositório com as respostas dos exercícios:

👉 [Respostas dos Exercícios - Repositório GitHub](https://github.com/micheltlutz/swift-exercicios-pt1)

Este repositório contém as soluções para todos os exercícios que você trabalhou. Use-o para revisar suas respostas, aprender novas abordagens e aprimorar suas habilidades de programação.

Continue praticando e explorando o mundo da programação em Swift. O aprendizado contínuo é a chave para o sucesso. Bom trabalho e boa sorte na sua jornada de desenvolvimento!

🚀 **Mantenha-se motivado e continue aprendendo!** 🚀


👨‍💻 Espero ter ajudado em seus estudos, atenciosamente, **[Michel Lutz](https://linktr.ee/micheltlutz)**

----

1. Manipulação de Strings

Exercício 1: Escreva uma função que recebe uma string e retorna o número de caracteres dessa string.

```swift
func countCharacters(in str: String) -> Int {
    return str.count
}

// Exemplo de uso
print(countCharacters(in: "hello")) // Output: 5
```

Exercício 2: Escreva uma função que recebe duas strings e retorna a concatenação dessas strings.


```swift
func concatenateStrings(_ str1: String, _ str2: String) -> String {
    return str1 + str2
}

// Exemplo de uso
print(concatenateStrings("hello", " world")) // Output: "hello world"
```

Exercício 3: Escreva uma função que recebe uma string e retorna a string em maiúsculas.

```swift
func toUpperCase(_ str: String) -> String {
    return str.uppercased()
}

// Exemplo de uso
print(toUpperCase("hello")) // Output: "HELLO"
```

---

2. Manipulação de Inteiros

Exercício 4: Escreva uma função que recebe dois inteiros e retorna a soma deles.

```swift
func sum(_ a: Int, _ b: Int) -> Int {
    return a + b
}

// Exemplo de uso
print(sum(3, 5)) // Output: 8
```
Exercício 5: Escreva uma função que recebe um inteiro e retorna true se o número for par e false se for ímpar.

```swift
func isEven(_ number: Int) -> Bool {
    return number % 2 == 0
}

// Exemplo de uso
print(isEven(4)) // Output: true
print(isEven(7)) // Output: false
```

---

3. Manipulação de Double e Float

Exercício 6: Escreva uma função que recebe dois números do tipo Double e retorna o resultado da multiplicação deles.
swift

```swift
func multiply(_ a: Double, _ b: Double) -> Double {
    return a * b
}

// Exemplo de uso
print(multiply(3.5, 2.0)) // Output: 7.0
```

Exercício 7: Escreva uma função que recebe um número do tipo Float e retorna o valor arredondado para o inteiro mais próximo.

```swift
func roundFloat(_ number: Float) -> Int {
    return Int(round(number))
}

// Exemplo de uso
print(roundFloat(3.6)) // Output: 4
print(roundFloat(3.4)) // Output: 3
```
---

4. Casting

Exercício 8: Escreva uma função que recebe um Double e retorna esse número convertido para Int.

```swift
func doubleToInt(_ number: Double) -> Int {
    return Int(number)
}

// Exemplo de uso
print(doubleToInt(3.9)) // Output: 3
```

Exercício 9: Escreva uma função que recebe uma string contendo um número e retorna esse número como Int. Se a string não puder ser convertida, retorne nil.


```swift
func stringToInt(_ str: String) -> Int? {
    return Int(str)
}

// Exemplo de uso
print(stringToInt("123")) // Output: Optional(123)
print(stringToInt("abc")) // Output: nil
```
---

5. Optionals e if let

Exercício 10: Escreva uma função que recebe uma string contendo um número e retorna esse número multiplicado por 2. Use if let para fazer o unwrapping do optional.


```swift
func multiplyStringNumber(_ str: String) -> Int? {
    if let number = Int(str) {
        return number * 2
    }
    return nil
}

// Exemplo de uso
print(multiplyStringNumber("10")) // Output: Optional(20)
print(multiplyStringNumber("abc")) // Output: nil
```
---

6. guard let

Exercício 11: Escreva uma função que recebe uma string contendo um número e retorna esse número dividido por 2. Use guard let para fazer o unwrapping do optional.

```swift
func divideStringNumber(_ str: String) -> Int? {
    guard let number = Int(str) else {
        return nil
    }
    return number / 2
}

// Exemplo de uso
print(divideStringNumber("20")) // Output: Optional(10)
print(divideStringNumber("abc")) // Output: nil
```

---

7. Trabalhando com Optionals

Exercício 12: Escreva uma função que recebe um array de opcionais do tipo Int e retorna a soma dos valores não nulos.

```swift
func sumOfNonNilValues(_ array: [Int?]) -> Int {
    return array.compactMap { $0 }.reduce(0, +)
}

// Exemplo de uso
print(sumOfNonNilValues([1, 2, nil, 4, nil, 6])) // Output: 13
```
--- 

#### Desafio


Passo 1: Embaralhar a URL
Aqui está um exemplo de como embaralhar a URL invertendo-a:

```swift
let originalURL = "https://github.com/usuario/repo-exercicios-swift"
let scrambledURL = String(originalURL.reversed())
print(scrambledURL) // Output: "tfiws-sioicrecxe-oper/oirasu/mboc.htig//:sptth"
```

Seu objetivo é desembaralhar essa string para revelar a URL original. Siga as instruções para completar o desafio.

**Instruções**
Inverter a String: Escreva uma função que inverte a string.
Revele a URL: Use a função para descobrir a URL original.

```swift
// Passo 1: Escreva uma função que inverte uma string
func reverseString(_ str: String) -> String {
    return String(str.reversed())
}

// Passo 2: Use a função para descobrir a URL original
let scrambledURL = "tfiws-sioicrecxe-oper/oirasu/mboc.htig//:sptth"
let originalURL = reverseString(scrambledURL)

print("A URL original é: \(originalURL)")
```
