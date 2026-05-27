---
title: Code
icon: material/code-braces
---

# Code

## Code "en ligne"

Le **code en ligne** (*inline code*) est délimité par un simple *backtick*, caractère : `` ` ``

=== "Code"
    ```markdown
    Sous Linux, tapez `ls -la` pour lister le contenu d'un dossier,
    y compris les fichiers cachés.
    ```

=== "Résultat"
    Sous Linux, tapez `ls -la` pour lister le contenu d'un dossier,
    y compris les fichiers cachés.

## Listing de code

Les listings de code source sont créés à l'aide de *code fences*, c'est-à-dire par un bloc délimité par des *triple backticks*.

=== "Code"
    ````markdown
    ```javascript
    function hello() {
        console.log("Hello World!");
    }
    ```

    ```csharp
    void hello(string who) {
        Console.WriteLine("Hello " + who);
    }
    ```
    ````

=== "Résultat"
    ```javascript
    function hello() {
        console.log("Hello World!");
    }
    ```

    ```csharp
    void hello(string who) {
        Console.WriteLine("Hello " + who);
    }
    ```