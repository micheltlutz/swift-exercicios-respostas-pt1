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

```swift
```

```swift
```

```swift
```

```swift
```

```swift
```

```swift
```

```swift
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
