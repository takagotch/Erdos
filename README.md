### erdos
---
https://github.com/Erdos-Graph-Framework/Erdos

```java
SimpleDirectedGraph graph_triangle = new SimpleDirectedGraph();

Vertex v0 = new Vertex();
Vertex v1 = new Vertex();
Vertex v2 = new Vertex("tag_v2");

graph_triangle.addVertex(v0);
graph_triangle.addVertex(v1);
graph_triangle.addVertex(v2);

Edge e_0 = graph_triangle.addEdge(v0, v1);
graph_triangle.addEdge(v1, v2);
graph_triangle.addEdge(v2, v3);

for (IVertex vertex : graph_triangle) {
  System.out.println(vertext.toString());
}

for (Edge edge : graph_triangle.edges()) {
  System.out.println(edge.toString());
}

graph_triangle.removeVertex(v0);
graph_triangle.vertices().remove(v1);
graph_triangle.vertices().iterator().remove();

boolean allow_self_loops = true;
boolean allow_multi_edges = true;

UndirectedGraph graph_undirected = Erdos.newUndirectedGraphWithEngine(new AdjIncidenceGraphEngine(),
    allow_self_loops, allow_multi_edges);
DirectedGraph graph = Erdos.newGraphWithEngine(new AdjIncidenceGraphEngine(),
  Edge.EDGE_DIRECTION.DIRECTED,
  allow_self_loops, allow_multi_edges);


private void BellmanFord(0
{
  SimpleDirectedGraph graph = new SimpleDirectedGraph();
  
  Vertex s = new Vertex("s");
  
  graph.addVertex(s);
  
  graph.addEdge(s, t, 6);
  
  graph.setTag("graph");
  graph.print();
  
  ShortesPathsTree res = new BellmanFordShortesPath(graph).setStartVertex(s).applyAlgorithm();
  res.print();
  AllPairsShortPathResult floyd_result = new FloydWarshall(graph).applyAlgorithm();
  floyd_result.shortestPathsTreeOf(s).print();
  System.out.print(floyd_result.shortestPathBetween(s, z).toString());
}
```

```sh
./gradlew build
ls 0l build/libs
```

```
```


