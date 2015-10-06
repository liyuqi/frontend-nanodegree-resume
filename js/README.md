javascript Boolean

Truthy | Falsy
-------|-------
true | false
non-zero num|0
"string"|""
Object|undefined
arrayys|null
function|NaN


javascript Object

|. notation     | ok| [] notation       | ok |
|:--------------|:--|:------------------|:--|
|obj.property   | O | obj["property"]   | O |
|obj.property$  | O | obj["property$"]  | O |
|obj.property1  | O | obj["property1"]  | O |
|obj.property-2 | X | obj["property-2"] | O |
|obj.property 3 | X | obj["property 3"] | O |
|obj. property  | X | obj[" property"]  | O |
|obj.property() | X | obj["property()"] | O |
|obj.property[] | X | obj["property[]"] | O |
|obj.8property  | X | obj["8property"]  | O |
