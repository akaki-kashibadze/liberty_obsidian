#mermaid #plugin 

plugin name: Mermaid tools
use: Diagram and chart making tool


```mermaid
flowchart TD
Start --> Stop


```

```mermaid
stateDiagram-v2
        [*] --> Still
        Still --> [*]
    
        Still --> Moving
        Moving --> Still
        Moving --> Crash
        Crash --> [*]
```

