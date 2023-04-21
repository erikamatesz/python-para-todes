# Aula 1 - Introdução

## 1.1 - Comentários

Comentar o código significa inserir descrições em linguagem legível para humanos dentro do código. A utilização apropriada dos comentários pode facilitar a manutenção do código, assim como o oposto pode causar confusão e dificultar a manutenção... E causar um certo desespero quando você encontra coisas desse tipo no meio do código:

```python
# segura na mão de deus e vai
```

Sim, coisas desse tipo acontecem e costuma-se dizer que um código bem escrito é um código que não precisa de comentários. Ainda assim, escrever comentários é muito importante quando se está escrevendo funções que serão utilizadas por outras pessoas. 

Existem algumas maneiras de escrever comentários. Use-as com parcimônia e sabedoria!

```python
# este é um comentário de uma linha
# este é outro comentário de uma linha
```
Podemos utilizar o `#` no início de uma linha para escrever um comentário e tudo o que vier à direita desse caractere será ignorado pelo interpretador. Você também pode utilizar o `#` depois de uma instrução:

```python
print("Hello, World!") # este é um comentário
```

O interpretador vai ler e executar a instrução `print` e ignorar o resto da linha.

Também podemos utilizar `"""` para escrever comentários em múltiplas linhas como no exemplo a seguir:

```python
"""
já este é 
um comentário
em múltiplas 
linhas
"""
```
Você pode colocar a quantidade de texto que quiser entre `"""` e `"""`. O interpretador vai ignorar tudo o que estiver entre esses caracteres.  


## 1.2 - Função `print`
