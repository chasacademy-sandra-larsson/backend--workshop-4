
# Backendutveckling och API:er #4: Använda Mongoose

👋 Se Linus Rudbecks föreläsning från 24 april ✅ 

Och se även Linus länkar i sina slides (finns på Canvas). 2 st bästa resurser är nog dessa för dagens workshop:

[Mongoose - Getting started](https://mongoosejs.com/docs/validation.html)

[Getting Started with MongoDB & Mongoose](https://mongoosejs.com/docs/validation.html)


### Innehåll denna workshop:

Använda Mongoose för: 

* **Schemas** - definiera strukturen och datatypen för dokument som lagras i MongoDB
* **Modeller** - skapa instanser av schemas som kan användas för att manipulera data i MongoDB
* **Queries** - ställa frågor till MongoDB-databasen
* **Validation** - validera data som används i dokumenten

Frivilligt:

* **Virtuals** - skapa fördefnierade värden som automatiskt beräknas eller genereras från annan data som lagras i dokumenten
* **Middleware** - definiera funktioner som körs innan eller efter en Mongoose operation
* **Plugins** - lägga till extra funktionalitet för Mongoose-modeller. 

**Obs!** Middleware och validering kan användas i såväl Mongoose och Express


# 👩🏽‍💻 Övning: Använda Mongoose för REST API

Du bygger vidare på förra veckans workshop, d.v.s REST API för två resurser men istället för MongoDB Node.js Driver använder du Mongoose där du skapar schemas, modeller och kommunikation mot databasen med mongooses funktioner. Alltså inte Node.js MongoDB Driver.

Strukturera även ditt projekt enligt mappar ```model```, ```view```, ```controller```. Dina routes har du i en ```routes-mapp```.

### Redovisning:
* Du redovisar ett fungerande API enligt REST API för en eller flera resurser med ovanstående tekniker och mappstruktur.

***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***


# 💬 Diskutera

* Vad är skillnaden mellan Mongoose och MongoDB Node.js Driver?
* Vad är fördelen att strukturera sin data i Schemas?
* Varför vill man döpa mappnamnen efter model, view, controller? 
* Varför är det viktigt att validera inkommande data?
* Finns det andra möjliga sätt att validera inkommnde data än Mongoose?
* Finns det andra möjliga sätt att använda middleware än Mongoose?


