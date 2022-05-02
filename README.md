# :maple_leaf: DesignPatterns
Simple examples of using patterns.
--------------------------------------

### 1. :zzz: Singleton  -  Wzorzec czy Antywzorzec? :fearful: 
#### Klasa w kodzie, która jest instancjowana tylko jeden raz! Każde użycie tej klasy odnosi się do tej jednej instancji.

#### :heavy_plus_sign: Zalety
- Globalny dostęp do instancji
- Obiekt singleton inicjalizowany jest dopiero wtedy, gdy jest po raz pierwszy potrzebny.
- Pewność, że istnieje tylko jedna instancja klasy.

#### :heavy_minus_sign: Wady
- Łamie zasadę SRP - Single-responsibility principle. Wzorzec rozwiązuje bowiem dwa różne problemy jednocześnie.
- Można doprowadzić do sytuacji w której, komponenty programu wiedzą zbyt wiele o sobie nawzajem.
- W środowisku wielowątkowym, należy uważać, na stworzenie wielu instancji sigletona przez wiele testów. 
- Utrudnienia przy wykonywaniu testów jednostkowych. Wiele frameworków testujących polega dziedziczeniu przy produkcji atrap obiektów. Ze względu na to, że konstruktor klasy Singleton jest prywatny, a nadpisywanie statycznyuch metod jest niemożliwe, trzeba znaleźć inny sposób na stworzenie atrapy singletona. [Ewentualnie nie pisać testów / albo zrezygnować z tego wzorca].

--------------------------------------
### 2. :zzz: Builder 

#### 

#### :heavy_plus_sign: Zalety
-
-
-

#### :heavy_minus_sign: Wady
-
-
-

--------------------------------------
### 3. :zzz: Facade 

#### 

#### :heavy_plus_sign: Zalety
-
-
-

#### :heavy_minus_sign: Wady
-
-
-
