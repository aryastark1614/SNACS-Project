# SNACS-Project

The analysis of temporal networks, where edges represent interac-
tions between nodes marked with their times of occurrence, plays
a crucial role in understanding dynamic processes in real-world
systems. However, for very large and dense temporal networks,
counting all the causal paths efficiently remains computationally
costly as path length and size of the time window increase. This
paper discusses the performance evaluation and scalability of the
proposed PaCo algorithm for path counting problems using causal-
ity on several real-world temporal network datasets: StackOverflow,
Ubuntu, EU-email and Reality Mining against a baseline algorithm.
Our experiments demonstrate that PaCo consistently outper-
forms the baseline in terms of execution time and scalability. While
the baseline algorithm has exponential runtime growth with in-
creasing maximum path length and sliding time window (delta) for
most datasets, PaCo has a much more gradual runtime increase
that can handle larger and more complex networks. However, we
notice that in very dense networks, such as StackOverflow, the
computational challenge for PaCo arises for path lengths greater
than 4 and sliding time windows greater than delta = 900, where
the memory and computational demands become too expensive.
We provide a comprehensive discussion of these limitations. Overall,
this study highlights the effectiveness of PaCo for scalable tempo-
ral path analysis while identifying key challenges that arise when
processing highly dense and temporally extensive datasets.
