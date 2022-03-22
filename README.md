# CALCULADORA
![calculadora](https://images.vexels.com/media/users/3/139836/isolated/lists/cbb25ff6f1471030763f0709c87e276a-icono-de-calculadora.png) 
## Utilidad
Es una aplicación para realizar:
* **Sumas**
* **Restas**
* **Medias aritméticas**


## Clases
Hace uso de diferentes clases agrupadas en paquetes:
* App:
> Aritmetica  
> MainApp  
* Model
> Base (Enumerado)  
> Decimal  
> Entero  
> Numero (Abstract)  
> NumeroException  
* Utils
> CollectionUtils  

**Aritmetica:** Se establecen los métodos de suma, resta y media.  
**MainApp:** Se lanzan diversas operaciones con un try para que  
las capture si hubiese algun error.  
**Base:** Es un enumerado de _decimal_ o _binario_ para el tipo de numero  
**Decimal:** Hereda de _Numero_   
**Entero:** Hereda de _Numero_  
**Numero:** Clase abstracta de la que heredan  
**NumeroException:** Hereda de _RuntimeException_

### Especificaciones
Se establece como valor máximo: 100001   
y como valor mínimo: -100000  
Para no saturar el programa.
