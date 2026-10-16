# SportsPulse - Sports Performance Analytics Platform

A plain Java/Eclipse Data Structures & Advanced Algorithms project inspired by the six-module Advanced Algorithms syllabus.

## What is included
- Sports performance dashboard for player statistics.
- String algorithms: Naive, KMP, Z-function, Rabin-Karp, Aho-Corasick.
- Suffix Array + Kasai LCP for similarity/search analysis.
- Dynamic Programming: Levenshtein, Damerau-Levenshtein, Needleman-Wunsch, Smith-Waterman, Matrix Chain, bitmask TSP.
- Network Flow: Ford-Fulkerson, Edmonds-Karp, Dinic, min-cut, bipartite matching.
- NP-hard demonstration: greedy project scheduling and Vertex-Cover 2-approximation using maximal matching.
- Randomised algorithms: Miller-Rabin, randomized hashing, reservoir sampling.
- Parallel primitives: parallel reduction and prefix scan using Java threads.
- Custom data structures: DynamicArray, IntQueue, IntStack, MaxHeap, HashTable, Graph.
- No third-party libraries. The engine avoids `java.util.*` and hand-builds core structures.

## Eclipse
1. Extract the ZIP.
2. Eclipse -> File -> Import -> Existing Projects into Workspace.
3. Select the extracted `SportsPulse` folder.
4. Run `sportspulse.app.Main` as Java Application.
5. Java 17+ is recommended.

## Console menu
1. Dashboard
2. Search player notes (KMP)
3. Fuzzy player-name matching (Edit Distance)
4. Player similarity (Suffix Array/LCP)
5. Performance flow network (Dinic)
6. Project scheduling / Vertex Cover approximation
7. Primality test (Miller-Rabin)
8. Random sample of players (Reservoir Sampling)
9. Parallel analytics demo
0. Exit

Sample data is in `data/players.csv`.
