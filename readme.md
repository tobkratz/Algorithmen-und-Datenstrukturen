<h1 align="center">

  Algorithmen und Datenstrukturen
  <br>
</h1>


![GitHub release (latest by date)](https://img.shields.io/github/v/release/tklitschi/Algorithmen-und-Datenstrukturen)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/tklitschi/Algorithmen-und-Datenstrukturen/Build%20Latex%20Document)
![GitHub All Releases](https://img.shields.io/github/downloads/tklitschi/Algorithmen-und-Datenstrukturen/total)
![GitHub](https://img.shields.io/github/license/tklitschi/Algorithmen-und-Datenstrukturen)


Ein Merkblatt zu der Algorithmen und Datenstrukturen. Mit den Meisten Grundelegenden Themen, wie Suchalgorithmen, Datenstrukturen.
Made with :heart: and a lot $\LaTeX$

Tested with **[GitHub action]**

 ---

[toc]

## About The Project

<p align="center">
  <img src="res/Vorschau.gif" alt="Vorschu">
</p>

---

Ein mit $\LaTeX$ geschriebenes Merkblatt rund um die Thematik Alogrithmen und Datenstrukturen. 
Basierend auf der Vorlesung `Algorithmen und Datenstrukturen` an der Teschnichen Universität Darmstadt im Sommersemester 2019.

### Inhaltsverzeichnis

<details>
<summary>#ExpandME</summary><br/>

- Allgemein Algorithmen 1
  - ProblemederInformatik
  - Aufgaben und Eigenschaften eines Algorithmus
  - EffizienzvonAlgorithmen
- Sortieralgorithmen
  - DasSortierproblem
  - Vergleichbarkeiten von Algorithmen
  - Korrektheit
  - Laufzeiten
    - Komplexität
    - AsymptotischeNotationen
    - Θ-Notation (Average Laufzeit)
    - O-Notation (Worst Case Laufzeit)
    - Ω-Notation (Best-Case Laufzeit)
    - Komplexitätsklassen
    - o-Notationundω-Notation
  - Divide-and-Conquer
  - Lösung von Rekusionsgleichungen
    - Substitutionsmethode
    - Rekursionsbaum-Methode
    - Mastermethode
    - Mastertheorem
  - InsertionSort
    - Kurzbeschreibung
    - PseudoCode
    - Korrektheit von Insertion Sort
    - Laufzeit(O(n2))
  - BubbleSort
    - Kurzbeschreibung
    - PseudoCode
    - Laufzeit(Ω=O=n2)
  - MergeSort
    - Kurzbeschreibung
    - PseudoCode
    - Laufzeit
    - Korrektheit
    - Analyse
  - Quicksort
    - Kurzbeschreibung
    - PseudoCode
    - Laufzeit
    - Korrektheit
    - RandomizedQS
- Grundlegende Datenstrukturen
  - Abstrakte Datentypen und Datenstrukturen
  - Stack
    - Laufzeiten
    - Realisierungen
  - VerketteListen
    - Laufzeiten
    - Realisierungen
  - AbstrakterDatentypQueue
    - Laufzeiten
    - Realisierungen
  - BinärBäume
    - Realisierung
    - Inorder-Traversieren
    - Pre- und Postorder-Traversieren
    - Suche
    - Einfügen
    - Löschen
    - Binäre Suchbäume
- Erweiterte Datenstrukturen 10
  - Rot-Schwarz-Bäume
    - Eigenschaften
    - Schwarzhöhe
    - Einfügen
    - Laufzeiten
  - AVL-Bäume
    - Laufzeiten
    - Einfügen
    - Löschen
    - Rebalance
  - Splay-Bäume
    - Splay-Methode
    - Suchen
    - Einfügen
    - Löschen
  - Heaps
    - (BinäreMax-)Heaps
    - Heaps als Array
    - Einfügen
    - Wurzel Löschen
    - Heap-Konstruktion
    - Heap-Sort
  - B-Bäume
    - Darstellung
    - Suche
    - Einfügen
    - Löschen
    - Zusammenfassung
- Zufällige Datenstrukturen
  - SkipList
  - HashTables
- Erweiterte Strukturen
  - DynamischeProgrammierung
  - Stabzerlegungsproblem
    - Lösung
  - Greedy-Algorythmus
  - Damenproblem
  - Heuristiken
  - Bergsteigeralgorithmus
  - IterativeLokaleSuche
  - SimulatedAnnealing
  - TabuSearch
  - Populations-basierteMethode
  - EvolutionärerAlgorithmus
    - Evolutionäres
  - Evolutionsstrategien
  - AmortisierteAnalyse
- Graphen
  - (Endliche)GerichteteGraphen
  - UngerichteterGraph
  - Darstellung
    - als Adjazenzmatrix
    - als Adjazenzliste
  - Gewichtete Graphen
  - Search-Methoden
    - BFSBreadth-First-Search
    - DFSDepth-First-Search
  - Anwendung von DFS
    - Topologisches Sortieren
    - Starke Zusammenhangskomponenten
    - Minimale Spannbäume MST
      - Generische Methode
      - Korrektheit
      - Terminologie
    - Algorithmus von Kruskal
      - Korrektheit
    - Algorithmus von Prim
      - Korrektheit
    - Kürzester Weg, gerichteter Graph
      - SSSP
      - Lockerung bzw. Relax
      - Bellman Ford Algorithmus
      - TOPO-Sort
      - Dijkstra-Algorithmus
    - Maximaler Fluss in Graphen
      - Netzwerkflüsse
      - Transformationen
      - Ford-Fulkerson-Methode
      - Reste
- NP 23
- Logarithmus-Gesetze 23
</details>


## Getting Started 
Das Merkblatt lässt sich mit den in $\LaTeX$ enthaltenden Standartklassen zu kompillieren. 

### Installation
1. Clone dieses Repository
```
git clone https://github.com/tklitschi/Algorithmen-und-Datenstrukturen.git
```
2. compile 
```
pdflatex Algorithmen-und-Datenstrukturen/main.tex
```

## Contributing

Contributions sind ein fundamental für Open Source Projekte, also feel free to contribute! :octocat:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

Tobias Kratz - [@tlitschi](https://twitter.com/tlitschi) - litsch@darmstadt.ccc.de

