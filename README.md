# swift-exercicios-respostas-pt1

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
