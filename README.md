# data-flow-visualisation

https://bl.ocks.org/mbostock/4062045

https://glitch.com/edit/#!/woozy-nickel?path=index.html:1:0

The above takes a data structure of nodes and links and creates a force-directed graph. 

Steps to development

1. Create nodes and links to describe system
2. Allow editable structure to add/delete nodes
3. Create forms to facilitate removal, deletion, editing of nodes/links
4. Allow users to update/edit by manipulating links/nodes directly
5. Allow association of information with the nodes

```
{
  "nodes": [
    {"id": "Helix", "group": 1},
    {"id": "EFT", "group": 2}
  ],
  "links": [
    {"source": "Helix", "target": "EFT", "value": 1}
  ]
}

```
