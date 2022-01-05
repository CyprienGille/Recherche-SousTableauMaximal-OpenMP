# Recherche de Sous-tableau Maximal

Ce repository contient le code d'un projet de Programmation Parallèle visant à implémenter la recherche de sous tableau maximal (avec prefix sum) pour prendre en main OpenMP.

Le format des données d'entrée était fixé, et donné en exemple par `data`.

---

Les fonctions :

- int* etapeZero(int* inputTable, int inputSize)
- int* retrieveResult(int* b, int inputSize)
- int* flipArray(int* table, int size)
- void monteeSomme(int\* a, int m)
- void descenteSomme(int* a, int* b, int m)
- void finaleSomme(int* a, int* b, int m)
- void monteeMax(int\* a, int m)
- void descenteMax(int* a, int* b, int m)
- void finaleMax(int* a, int* b, int m)
- void maxSubTable(int* inputTable, int inputSize, int* psum, int* ssum, int* pmax, int\* smax)

sont parallélisées.

---

Note : dans tout le code, on se sert des notations des TPs vus en classe pour une traduction plus directe de l'algo en code, quitte à donner des noms muets aux variables (comme 'a').
