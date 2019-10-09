# Guia-de-estudios-U1
Una pequeña guia de estudios para el examen.
---
Interfaces
---
Una interfaz la union de metodos abstractos y constantes publicas las cuales obligan la herencia. Por lo tanto, todo los metodos declarados en la interfaz deben de ser implemntados en las clases que implementen a la interfaz.

En otras palabras, si tenemos la interfaz spiderman que contiene todos los poderes del superheroe y la clase concreta Peter Parker con sus atributos, al implementarle la interfaz spiderman Peter consigue todos las habilidades de spiderman mas sus propios atributos

```
public interface MyA(){
    void A();
}
public class youA() implements MyA{
    @Override
    void A(){
      System.out.println("My A");
    }
}
```
Las interfaces tiene muchos tipos de aplicaciones, entre ellas la generalicacion y la herencia multiple.
 
La generalicacion se refiere a la construccion de un prototipo que muchas cosas pueden seguir. Viendolo desde el punto de vista de POO, se define como la creacion de clases apartir una clase ya definida, en este caso, una interfaz. 


---
Clases abstractas.
---

