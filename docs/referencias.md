# Gerenciamento de Riscos
- [Relacione aqui referências a documentos, sítios na Internet, manuais ou qualquer outro item que tenha sido usado para a confecção do presente artefato.]

# Depois exlcuir

# Como usar algumas funções: 

# Documentação de Software

**Negrito**  
*Italico* 

1. Primeiro
2. Segundo
3. Terceiro  

-[x]Tomar Banho  
-[ ]Comer Cuscuz  
-[ ]Limpar casa 

|Nome |Idade|
|-----|-----|
|Eduardo|28| 
|Odineia|26|
|Abdenaide|22|

~~Tachado~~

```
    # coding: utf-8

    def soma(a, b):
        if isinstance(a, basestring) or isinstance(b, basestring):
            raise ValueError(u'Somente números são permitidos')
        return a + b
```

Emoji - :snake: :heart::rocket:

> "Essa é uma citação"

* Item 1
* Item 2

`def soma(a, b):
    if isinstance(a, basestring) or isinstance(b, basestring):
        raise ValueError(u'Somente números são permitidos')
    return a + b`

[Portal P2](https://www.portalp2.com)

For full documentation visit [mkdocs.org](https://www.mkdocs.org).


* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
