# Arrays

![](../../media/java-arrays-1.png)

## Declarando um array
```java
int[] idade = new int[10];
int[] ficha = { 1,2,3,4,5,6,7,8,9,10 };
```
## Acessando um elemento com seu index

```java
ficha[2];
```
## Trocar o elemento de acordo com o index

```java
ficha[2] = 3;
```

# ArraysList

## Declarando um ArrayList

```java
ArrayList<String> nomes = new ArrayList<>();
```

## Adicionando um elemento
```java
nomes.add("Bruno");
```
## Retornando o tamanho do ArrayList
```java
nomes.size();
```

## Pegar o elemento através do index
```java
nomes.get(0);
```

## Achar um elemento na lista

```java
nomes.indexOf("Bruno");
```

## Checa se a lista contem
```java
nomes.contains("Bruno");
```

## Removendo um elemento
```java
nomes.remove("Bruno");
nomes.remove(0);
```
