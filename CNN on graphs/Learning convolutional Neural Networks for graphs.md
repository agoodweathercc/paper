* Learning convolutional Neural Networks for graphs

  works for directed, undirected graph with both discrete and continuous node and edge attributes

  learning a representation for classification/regression

  state of the art: graph kernels based on substructures: shortest path, random walk, subtree...

  Patchy: 1)node sequence selection(use centrality measures to generate node sequence)

  ​		2) neighborhood assembly(breadth-first search until k nodes are added)

  ​		3) neighborhood normaization, served as receptive fields(unclear)

  ​		   node and edge attributes correspond to channels(?)

  ​		![Screen Shot 2017-09-21 at 11.05.06 AM](/Users/admin/Desktop/ScreenShot/Screen Shot 2017-09-21 at 11.05.06 AM.png)

  ​

  ​		4) build a neural network on top  