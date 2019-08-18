### erdos
---
https://github.com/Erdos-Graph-Framework/Erdos

```java
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

```
```

```
```


