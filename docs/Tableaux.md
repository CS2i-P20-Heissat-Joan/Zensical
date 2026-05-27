---
title: Tableaux
icon: material/table
---

# Tableaux

## Tableaux : syntaxe de base

Les tableaux ont cette structure :

=== "Code"
    ```markdown
    | Janvier | Février | Mars |
    |---------|---------|------|
    | 100     | 200     | 300  |
    | 400     | 500     | 600  |
    ```

    Ou encore :

    ```markdown
    | Janvier | Février | Mars |
    |-|-|-|
    | 100 | 200 | 300 |
    | 400 | 500 | 600 |
    ```

=== "Résultat"
    | Janvier | Février | Mars |
    |---------|---------|------|
    | 100     | 200     | 300  |
    | 400     | 500     | 600  |

## Alignement des colonnes

Les colonnes peuvent être alignées à gauche, à droite, et centrées :

=== "Code"
    ```markdown
    | Gauche | Centré | Droite |
    |:-------|:------:|-------:|
    | 100    | 200    | 300    |
    | 400    | 500    | 600    |
    ```

=== "Résultat"
    | Gauche | Centré | Droite |
    |:-------|:------:|-------:|
    | 100    | 200    |    300 |
    | 400    | 500    |    600 |