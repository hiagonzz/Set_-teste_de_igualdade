## Como as coleções Hash testam igualdade?

`Se hashcode e equals estiverem implementados:`
    > Primeiro hashCode. Se der igual, usa equals para confirmar

    > lembre-se: String, integer, double, etc. já possuem equals  e hashCode


`Se hashCode e  equals não  estiverem implementados: `
    > Compara as referências (Ponteiros) dos objetos.