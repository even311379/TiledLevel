
# Workflow

 
```mermaid
flowchart TD;
    
    subgraph    
    TS[Tiled Item Set] --> |Create Tiled Level </br> Asset from this| TL[Tiled Level Asset];
    TS --> |Drag to Level| TA[Tiled Level Actor];
    TA --> |Save To Asset| TL;
    TL o--o |Edit|TL;
    TL --> |Drag to Level| TA;
    TA o--o |Edit|TA;
    end;
    TA --> |Break| N{{Normal Level}};
    
```

### Break Tiled level

You can always return normal level design workflow after using this plugin. By breaking tiled level, it is converted to separated static mesh actors or BP actors which allows you to fine tuning their properties. They are organizd in each floor folders, which enable you to hide specific floors.


Break

![Demo](../_media/DemoGIF/Break.gif)

