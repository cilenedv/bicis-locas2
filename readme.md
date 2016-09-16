#Nos piden que realicemos el siguiente imagen

![image](http://i65.tinypic.com/2e1r9rt.png {width=40px height=50px})

- Lo que gregamos fue el siguiente codigo
	var span = document.createElement("span"); --> Es para crear un elemeno span
        var referencia= document.getElementById("name"); --> creamos una referencia despues de id "name" este caso es del nombre.
        var padre=referencia.parentNode; -- > para que nos retorne al padre
        padre.insertBefore(span,referencia); --> para insertar al padre
        var texto = document.createTextNode("Debe ingresar su nombre");--> creamos la variable para guardar el texto que aparecera
        span.appendChild(texto);--> el hijo
        return span;-->retorna
