# Trabajo practico 0 
### Analisis sobre lenguajes de programacion en base a la logica paradigmatica 
### Ignacio Milone - Ing en sistemas



  ## Ejercicio 1 - C
  1. Generalización simbólica: ¿Cuáles son las reglas escritas del lenguaje? 
  
      **Respuesta:** El uso obligatorio del ; al final de cada linea de codigo, el uso de estructuras de control, el manejo de punteros para acceder a memoria y la gestion manual de la misma memoria (malloc / ffllush), el                         llamado de funciones mediante valor o referencia.
                    
  2. Creencias de los profesionales: ¿Qué características particulares del lenguaje se
  cree que sean "mejores" que en otros lenguajes?
  
      **Respuesta:** C esta pensado para tener una manipulacion directa de la memoria a diferencia de otros lenguajes donde esto es "automatico" otorgando asi un control mas rapido y manual, ademas de estar disponible en                          muchas plataformas y contar con una gran cantidad de bibliotecas
  
  3. Valores: ¿Qué pensamiento o estilo de programación consideraron mejor los creadores?
  
      **Respuesta:** Es un lenguaje de bajo nivel simple que se puede usar desde cualquier plataforma o OS, fue pensado para remplazar el lenguaje ensamblador para crear sistemas operativos, en pocas palabras c es un                               lenguaje pensado para ser eficiente, portatil y simple 
  
  4. Ejemplares: ¿Qué clase de problemas pueden resolverse más fácilmente en el lenguaje?
  
      **Respuesta:** Muchos problemas pueden resolverse utilizando c, pero es mas facil resolver problemas que tengan que ver con sistemas operativos

  ## Ejercicio 1 - JAVA
  1. Generalización simbólica: ¿Cuáles son las reglas escritas del lenguaje? 
  
        Esta basado en c/c++, esta orientado a objetos y tiene un manejo mas "automatico" de la memoria (no usa ni malloc ni free), todo en java es un objeto y reside en alguna clase 
                    
   2. Creencias de los profesionales: ¿Qué características particulares del lenguaje se
      cree que sean "mejores" que en otros lenguajes?
  
       **Respuesta:** Portabilidad total con JVM, tiene menos probabilidades de errores de memoria al ser automatico, y es un lenguaje con buena seguridad 
  
   3. Valores: ¿Qué pensamiento o estilo de programación consideraron mejor los creadores?
  
       **Respuesta:** Esta pensado para resolver paradigmas de programacion orientada a objetos, debe ser facil de usar y tomar lo mejor de otros lenguajes (Ej : c/c++)
  
   4. Ejemplares: ¿Qué clase de problemas pueden resolverse más fácilmente en el lenguaje?
      
      **Respuesta:** Aplicacciones web, moviles, empresariales o multiplataforma
##
## Ejercicio 2 Analizando Java

1. ¿Tiene una sintaxis y una semántica bien definida? ¿Existe documentación oficial?
2. ¿Es posible comprobar el código producido en ese lenguaje?
3. ¿Es confiable?
4. ¿Es ortogonal?
5. ¿Cuáles son sus características de consistencia y uniformidad?
6. ¿Es extensible? ¿Hay subconjuntos de ese lenguaje?
7. El código producido, ¿es transportable?

### Respuestas: 

 1: si estan bien definidas, su sintaxis es estricta pero simple ( ;, {}, declaracion de clases public class Nombre {}) y su semantica esta bien especificada. Tambien existe documentacion oficial sobre java en la pagina de     Oracle con toda la informacion que se necesite
 
 2: Si es posible, ya que en java los errores se detectan a la hora de compilarlo

 3: Es un lenguaje confiable, ya que la memoria se gestiona automaticamente (punteros , liberacion de memoria) y posee un buen manejo a la hora de prevenir errores con el try-catch

 4: en este caso java no es del todo ortogonal, hay un par de casos especiales que rompen las reglas de java por ejemplo los tipos de datos int , double, char no son considerados objetos esto rompe la regla de java donde       se dice que todo es un objeto
 
 5: Tiene una alta consistencia por que esta todo dentro de clases, pero no es tan uniforme por los casos especiales, como en el punto anterior los datos int, double, char al no ser considerados objetos son un caso             especial y rompen un poco la uniformidad de java

 6: si es extensible pero sin modificar directamente la sintaxis o semantica del codigo, y existen subconjuntos de java como por ejemplo, Java ME que esta diseñado para dispositivos moviles o sistemas mas pequeños

 7: El transportable gracias al JVM, codigos hechos en Windows pueden usarse en Linux o MacOS





      


