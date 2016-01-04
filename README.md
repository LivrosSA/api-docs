# Livros S.A - API v1
> Temporary Endpoint - http://livrossa-api.herokuapp.com/v1/

## Books

**REQUEST**

> **GET** 
> 
> /book

> **HEADERS**
> 
> Cache-Control: no-cache;
> 
> Authorization: TOKEN << YOUR-CLIENT-TOKEN >>

>

**RESPONSE**

> **HTTP CODE** 
> 
> 200

> **HEADERS**
> 
> X-Powered-By: Livros SA
>
>Content-Type: application/json; charset=utf-8
>
> **BODY**
> 
>   
    {  
        "title"    : "Livro de teste",
	    "category" : "1",
	    "keywords" : "teste, pt-br",
	    "language" : "pt-br",
	    "infos"    :{
	      "pages"  : "200",
	      "author" : "cleiton tavares"
	    },
	    "urls"      : ["http://google.com", "http://adasda.com"],
	    "create_at" : "25/02/1992 10:20hrs",
	    "update_at" : "25/02/1992 10:20hrs",
	    "updated_by": "1"
	  }

## Categories

**REQUEST**

> **GET** 
> 
> /book

> **HEADERS**
> 
> Cache-Control: no-cache;
> 
> Authorization: TOKEN << YOUR-CLIENT-TOKEN >>

>

RESPONSE

* 200
