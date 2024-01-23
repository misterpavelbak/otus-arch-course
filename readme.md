| Column1 | Column2 | Column3 |   |
| ------- | ------- | ------- | - |
| Row1    | 2       | 3       |   |
| Row2    |         |         |   |
| Row3    |         |         |   |
| Row4    |         |         |   |

---

### Some diagram

```mermaid
flowchart LR
A["Some text"] -->|Text| B(Round)
B --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
  A --> node_1
  node_2 --> node_3
  node_3 --> node_4
  C --"3"--> node_5
  node_1("new_node")
  node_2[["new_node"]]
  node_3[["new_node"]]
  node_4[["new_node"]]
  node_5[["new_node"]]
```

---

### Some C4

![Current C4](diagrams/C4.drawio.png)

> [!NOTE]
> Some note

1. asdasd
2. asdas
3. sadasd

---

[link to ADRs](ADRs\09_architecture_decisions.md)

