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

En palabras simples, si tenemos dos clases que son goku y vegeta que son sayayines, en vez darle sus atributos a cada una, creamos una interfaz llamada sayayin para poner ahi los atrubutos que tiene en comun para hacerlo mas eficiente.
```
public interface A {
    void MyA();
}

public class B  implements A{

    @Override
    public void MyA() {
        System.out.println();
    }
}
public class C implements A {
    @Override
    public void MyA() {

    }
}
```
El otro punto es la herencia  multiple, esta practica de POO es usada para darle los atributos y metodos de dos clases padres a una clase hija. Esto tal cual solo puede ser implementado en C ya que Java no cuenta con esta posibilidad. Sin embargo, existe de manera altera la forma de hacer herencia multiple mediante interfaces porque no hay restriccion de cuantas interfaces puede implementar una clase.

Un ejemplo mas colocial de esto podrian ser la transformaciones que sufre Ben 10 a la hora de transformarse ya que este implentará las clases humano y por ejemplo, cuatro brazos.
```
public class B  implements A, D {

    @Override
    public void MyA() {
        //Metodo de la interfaz A
    }

    @Override
    public void MyD() {
        //Metodo de la interfaz D
    }
}
```

---
Clases abstractas.
---
Un clase abstracta es similar a una interfaz ya que comparten ciertas caracteristicas como la de obligar la herencia y no poder crear instancias a partir de ellas.

¿Para que usar una clase abstracta?
-Se utilizan para creacion de una especie de cascaron para otras clases hijas que heredarán de ella. 

lo que diferencia las interfaces y las clases abstractas es que la interfaces obligan la implementacion a difrencia de las clases abstractas 
que solo inicializan
```
public class C extends E implements A {
    @Override
    public void MyA() {

    }
   
}
public abstract class E {
    int E;
    void MyE(){

    }
}
```




