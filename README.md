# Graph encoding in Quantum Computing

This is my master's thesis. Here you may find both the full version of the manuscript as well as the slides I prepared to discuss it.

## Abstract
Quantum walks have become a fundamental tool in the field of Quantum Computing. Differently from
classical random walks, the class of graphs over which quantum walks may be performed is severely
restricted by the condition of unitarity.

After reviewing the general construction of quantum walks, the thesis investigates their limits,
exploring the properties that characterize the directed graphs over which they may be performed. The
analysis is also conducted with respect to coined quantum walks, a generalization of quantum walks. In
this regard, the underlying graph of a coined quantum walk on a regular graph is known to be the line
graph. This thesis proposes a version of the result that is extended to the case of regular multigraphs.
In turn, this allows to determine the underlying graph of coined quantum walks on reversible graphs
with self-loops.

In light of the rigid conditions that regulate quantum walks, the thesis proceeds to study techniques
to circumvent them. These take shape into encoding procedures that edit general connected graphs
into ones that are amenable to quantum walks. More specifically, the thesis is concerned with two
edge-addition based procedures: encoding to Eulerian graphs, encoding to regular multigraphs.

Thus, the thesis extends the discussion to the notion of encoding bias. Through addition and
duplication of edges, the aforementioned encoding procedures appear to affect the resulting quantum
walks with local bias. Due to their nature, these local phenomena are here referred to as encoding
bias. It is shown that there exists no unitary remedy to encoding bias, implying that any solution to
the problem relies on the adopted encoding procedure. Finally, it is given proof that, for any strongly
connected, irregular, Eulerian graph, the encoding procedure to regular multigraphs inevitably leads to
encoding bias
