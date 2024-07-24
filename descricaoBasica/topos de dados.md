# Tipos de Dados em Java

Java possui dois grupos principais de tipos de dados:

- Tipos de dados primitivos
- Tipos de dados não-primitivos (ou tipos de referência)

## Tipos de Dados Primitivos

Existem oito tipos de dados primitivos em Java:

### Tipos Numéricos Inteiros

1. **byte**
   
   - **Tamanho:** 8 bits
   - **Intervalo:** -128 a 127
   - **Exemplo:** `byte b = 10;`

2. **short**
   
   - **Tamanho:** 16 bits
   - **Intervalo:** -32.768 a 32.767
   - **Exemplo:** `short s = 10000;`

3. **int**
   
   - **Tamanho:** 32 bits
   - **Intervalo:** -2^31 a 2^31-1
   - **Exemplo:** `int i = 100000;`

4. **long**
   
   - **Tamanho:** 64 bits
   - **Intervalo:** -2^63 a 2^63-1
   - **Exemplo:** `long l = 100000L;`

### Tipos Numéricos de Ponto Flutuante

5. **float**
   
   - **Tamanho:** 32 bits
   - **Precisão:** Aproximadamente 7 dígitos decimais
   - **Exemplo:** `float f = 10.5f;`

6. **double**
   
   - **Tamanho:** 64 bits
   - **Precisão:** Aproximadamente 15 dígitos decimais
   - **Exemplo:** `double d = 10.5;`

### Outros Tipos Primitivos

7. **boolean**
   
   - **Tamanho:** 1 bit
   - **Valores:** `true` ou `false`
   - **Exemplo:** `boolean bool = true;`

8. **char**
   
   - **Tamanho:** 16 bits
   - **Intervalo:** '\u0000' (ou 0) a '\uffff' (ou 65.535)
   - **Exemplo:** `char c = 'A';`

## Tipos de Dados Não-Primitivos

### Strings

- **String**
  - **Descrição:** Uma sequência de caracteres.
  - **Exemplo:** `String str = "Hello, World!";`

### Arrays

- **Arrays**
  - **Descrição:** Uma coleção de elementos do mesmo tipo.
  - **Exemplo:** `int[] array = {1, 2, 3, 4, 5};`

### Classes

- **Classes e Objetos**
  
  - **Descrição:** Representações de entidades do mundo real.
  
  - **Exemplo:** 
    
    ```java
    class Car {
        String color;
        String model;
    
        void display() {
            System.out.println("Model: " + model + ", Color: " + color);
        }
    }
    ```

### Interfaces

- **Interfaces**
  
  - **Descrição:** Abstrações que permitem a definição de métodos que devem ser implementados por classes.
  
  - **Exemplo:** 
    
    ```java
    interface Animal {
        void makeSound();
    }
    
    class Dog implements Animal {
        public void makeSound() {
            System.out.println("Woof");
        }
    }
    ```

### Outros Tipos de Referência

- **Enumerations (Enums)**
  
  - **Descrição:** Uma lista de constantes nomeadas.
  - **Exemplo:** 
    
    ```java
    enum Day {
        SUNDAY, MONDAY, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY
    }
    ```

- **Null**
  
  - **Descrição:** Um valor especial que representa uma referência inválida ou inexistente.
  - **Exemplo:** `String str = null;`

## Referências

- [Java Documentation](https://docs.oracle.com/en/java/javase/11/docs/api/index.html)
