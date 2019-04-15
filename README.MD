# Global Graph Day, April 2019 - Datasets for Neo4J demo

### Game of Thrones Dataset 
The dataset is available at GOT_Query.txt
Finding Relationships between characters
`MATCH (tywin:Person { name:"Renly Baratheon" }),(arya:Person { name:"Arya Stark" }),
  p = shortestPath((tywin)-[*]-(arya))
RETURN p`

![GOT Query Result](/images/got.PNG)

### Mahabharat Dataset 
The dataset is available at Mahabharat_query.txt
Finding Relationships between characters
`MATCH (vich:Person { name:"Vichitravirya" }),(ghat:Person { name:"Ghatotkacha" }),
  p = shortestPath((vich)-[*]-(ghat))
RETURN p`
![Mahabharat Query Result](/images/maha.PNG)