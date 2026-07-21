# Annotated algorithm notes

Annotated solutions to interview and competitive-programming problems in Python, TypeScript, and Rust.

## Five good places to start

1. [Longest Common Subsequence](neetcode/2d-dynamic-programming/1143-longest-common-subsequence.py) derives the dynamic-programming recurrence from optimal substructure, then works through a complete table by hand.
2. [Largest Rectangle in a Histogram](neetcode/stack/0084-largest-rectangle-in-histogram.py) explains the monotonic stack in terms of the rectangles that remain possible, including the subtle meaning of each stored start index.
3. [Pacific Atlantic Water Flow](neetcode/graphs/0417-pacific-atlantic-water-flow.py) turns the problem around: instead of tracing water downhill from every cell, it flood-fills uphill from both oceans.
4. [Binary Tree Maximum Path Sum](neetcode/trees/0124-binary-tree-maximum-path-sum.py) uses post-order traversal to distinguish a complete path at a node from the one-sided path that can be extended by its parent.
5. [Two Knights](cses/cses-007-two-knights/src/main.rs) develops a closed-form counting argument by subtracting the attacking configurations, found through the geometry of 2-by-3 rectangles, from all possible placements.

For a broader guide to choosing techniques, see [“Is dismissing the algorithmic tech interview a memetic hazard?”](https://sebinsua.com/algorithmic-bathwater#what-kind-of-problem-do-i-have).

The rest of the repository contains solutions from [NeetCode](neetcode/), [CSES](cses/), and [CodeSignal](codesignal/).
