## prueba para team C


| column | colum2 |ddddd|
|--|--|--|
| gdgdgdg | hdhdhdhdhdh |alsdkjalkdja

 1. List item
 2. ghdfgfd
 3. dfgdgf
 4. dfgdfg

```mermaid
erDiagram

CUSTOMER  }|..|{  DELIVERY-ADDRESS  : has

CUSTOMER  ||--o{  ORDER  : places

CUSTOMER  ||--o{  INVOICE  : "liable for"

DELIVERY-ADDRESS  ||--o{  ORDER  : receives

INVOICE  ||--|{  ORDER  : covers

ORDER  ||--|{  ORDER-ITEM  : includes

PRODUCT-CATEGORY  ||--|{  PRODUCT  : contains

PRODUCT  ||--o{  ORDER-ITEM  : "ordered in"
 
 
```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

    import io
		print("hola mundo")
