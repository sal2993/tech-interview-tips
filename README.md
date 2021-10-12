# Tech Interview Java Cheat Sheet

## OOP Princibles

### 4 tenants of OOP
- Abstraction:
    - "Abstraction is a concept of hiding the details and showing only the necessary things to the user. We use an abstract class/Interface to express the intent of the class rather than the actual implementation."
- Inheritance
    - "Inheritance is a concept where the properties of one class can be inherited by the other. It helps with reusability and establishes a relationship between different classes. The relationship is established in code using the keyword extends."
- Polymorphism:
    - "Polymorphism is the ability of a variable, function, or object to take multiple forms. It allows you to define one interface or method and have multiple implementations. Polymorphism is characterized by the method overloading and method overriding."
- Encapsulation:
    - "Encapsulation is a process of hiding data implementation by restricting access to public methods. The instance variables are kept private and the accessor methods(getters and setters) are made public."

## Data Structures

### Primitive Arrays

#### Split string by the indexes of chars example
```String.substring(0,2)```


#### Create Primitive Array
example: ```int[] ages = new int[0]```
example2: ```int[] ages = new int[]{25,41,28,9}```

### ArrayLists

#### Create ArrayList
example: ```new ArrayList<>()```

#### Split Array by index
example: ```String.subList(2,4)```

### Sets

#### Create a Hash Set
example: ```Set<Integers> uniqueVals = new HashSet<>()```

#### Loop a Hash Set's Values
example: 
```
for (Integer val : uniqueVals) {
    System.out.println(val)
}
```

### Maps

#### Create a Hash Map
example: ```Map<String, Integer> hashMap = new HashMap<>();```

#### Loop a Hash Map by Keys

## Powerful Utils



## Random INT
example: ```Math.random()```