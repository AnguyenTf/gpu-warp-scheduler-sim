# GPU Warp Scheduler Simulator

A cycle-level SIMT GPU Warp Schduler Simulator writtn in C++.
Models warp-level execution, memory latenfcy, and multiple scheduling policies.

## Learning order

graph_loader.cpp read_edges.cpp
- Whatever files loads the .txt edge list

Teaches you:
how the graph is read from disk
how edges are stored temporarily
how duplicates/self-leeps are removed
how the graph is prepared for CSR

csr_builder.cpp
- Algorithm

Teach you:
how edges become adjacency lists
how adjacency lists become sorted
how row_prt is built
how col_idx is built 
how memory is allocated

cpu_triangle_cout.cpp
- Algorithm

Teachs you:
the two-pointer intersection
the main triangle counting loop
the logic to avoid double-counting
the iteratino over edges
the final triangle count

utils.h / graph.h / common.h
- Help read main

Defind:
structs
helperfunctions
typedegs
small utilities

