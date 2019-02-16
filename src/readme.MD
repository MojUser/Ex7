##Zadania

1. Napisz własną prostą implementację drzewa:
    1. Stwórz klasę `Node`, reprezentującą 1 węzeł w drzewie, klasa powinna mieć listę swoich dzieci a także swoją wartość (int).
    2. Stwórz klasę `SimpleTree`, która będzie posiadała referencję do korzenia.    
    3. Dodaj metodę `addNode(Node node)`, która bedzie dodawała dziecko do danego węzła. 
   4. Dodaj metodę `isHeap()`, która zweryfikuje czy dane drzewo jest poprawnym kopcem.
   5. Zmodyfikuj swoją klasę tak, aby można było podać maksymalną liczbę dzieci dla węzłów. Wszystkie węzły będą miały tą samą maksymalną liczbę dzieci.
   
2. Napisz metodę `verifyHeap(int[] arr)`, która przyjmie tablicę a następnie zweryfikuje czy ta tablica przedstawia poprawnie zapisany kopiec binarny.

3. Napisz metodę `arrToTree(int[] arr, int maxChildren)`, która wykorzystując twoją klasę z poprzedniego ćwiczenia, zamieni daną tablicę na drzewo którego węzły będą miały maksymalną liczbę dzieci równą `maxChildren`.

4. Podobnie do zadania `1` zaimplementuj własną klasę `BinaryTree`, która będzie reoprezentowała drzewo binarne dla liczb całkowitych.

5. Zaimplementuj metodę `addNode(int value)`, która doda do drzewa węzeł z daną wartością.
 
5. Zaimplementuj w klasie `BinaryTree` metodę `getMin()`, która będzie wypisywała najmniejszy węzeł w drzewie.

6. Zaimplementuj w klasie `BinaryTree` metodę `getNax()`, która będzie wypisywała największy węzeł w drzewie.

7. Zaimplementuj w klasie `BinaryTree` metodę `contains(int num)`, która sprawdzi czy dane drzewo zawiera węzeł który ma wartość równą `num`.

8. Zaimplementuj metodę `delete(int num)` , która usunie węzeł z wartością równą `num`. Pamiętaj, że drzewo musi pozostać poprawne po usunięciu.