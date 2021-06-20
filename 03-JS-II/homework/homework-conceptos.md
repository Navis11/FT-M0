Homework: Javascript II
Instrucciones
En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

1. for - Es una estructura que permite que las instrucciones, el código, que escribas dentro de ella se repitan por un número determinado de veces. Para poder crear esta estructura, además de darle las instrucciones a realizar, debes de darle también ciertas reglas o parámetros bajo los cuales tiene que trabajar. ej. Si queremos que el For nos devuelva los números del cero al diez, tenemos que responder las siguientes preguntas:

  ¿Desde dónde empezará a contar? - Inicializador o Contador
    R: Desde el 0
  ¿Hasta dónde a va a contar? - Condición o evaluación
    R: Hasta el 10
  ¿Como irá contando (de uno en uno, de dos en dos, de tre en tres, etc.)? - Incremento
    R: de uno en uno

  Ahora vamos a acomodar esta información dentro del paréntesis, en el mismo órden.

  1. ¿Desde dónde? Para este primer paso necesitamos decirle que desde cero, sin embargo, como esperamos que la cuenta empiece en 0 y después pase a 1, 2, 3 y así sucesivamente, necesitamos asiganrle ese valor a una variable, en este caso el nombre de esta será i.

/*                          for (var i = 0; i < 11; i++){
                            // instrucciones
                            }  
                                                                                                                 */
  2. Como puedes ver los tres parámetros están separadoss por "";"". Para la segunda parte, la condición, se le pide al código que continue ejecutandose o siga contando si el valor de i es menor a once. Esto quiere decir que una vez que el valor de i iguale al once, dejará de contar, ya que 11 no es menor que 11, retornando así una cuenta hasta el número diez.

  /*                          for (var i = 0 ; i < 11 ; i++){
                                    console.log(i);
                            }                                                                                       */
  3. Intrucciones. Una vez establecidos los parámetros necesitamos darle a la máquina el cógido las instrucciones a llevar a cabo. En este caso se uso un console.log() con lo cual pedimos a la computadora que muestre los resultados en la consola. El ciclo que va a recorrer este for empezará con i valiendo 0, la instrucción se va a ejecutar, porque cero es menor a once, va a aparecer un cero en la consola, al terminar, la i con el operador ++ va a aumentar en uno el valor actual convirtiendo el cero en uno. Ahora i vale uno y volvera a completar el ciclo hasta que i = 11.

2. &&  - Es un operador lógico que representa una "y".Se usa cuando es necesario que dos condiciones se cumplan. ej.
          mi casa deseada: tiene que tener patio (porque tengo un perro) y tiene que tener dos habitaciones (porque vivo con mi hermana)
          Para poder comprar una casa tienen que cumplirse ambas condiciones, de otra manera no la compro.
                                        habitaciones = 2 && patio = 1
          Siempre y cuando ambas condiciones se cumpla, el resultado será verdadero, mientras una de ellas no se cumpla, devolverá el valor falso.

3. ||  - Operador lógico que representa una "o". Devuelve el valor verdadero mientras una de las dos se cumplen y falso si
          ninguna de las dos se cumple.

                                ej. mis próximas vacaciones. Tengo dos opciones Acapulco || Cancún
          Mientras una de mis dos opciones se cumpla está bien, porque saldría de vacaciones, a menos que ninguna se cumpla, porque entonces no saldría a ningún lado.

4. !   - Operador lógico que representa una negación. Devueve el valor false, si la operación lógica debía regresar tru y        devuelve true, si esta devía regresar false.
