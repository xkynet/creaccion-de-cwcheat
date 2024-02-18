# Creacion de CwCheats para principiantes.

* **Aclaración:**
  
    La creación de cwcheats **`NO PROMUEVE`** la piratería ni la modificación interna de los juegos o **`ISO`** 💿,
    los cwcheats son un archivo en **`formato.ini`**, **`db`** o **`txt`**, que modifican el comportamiento del 
    juego, al acceder una región de la memoria `RAM` *(donde se ejecutan ciertas instrucciones)* y por 
    medio de líneas de texto, con un formato de instrucciones en concreto,`MIPS`, con el cual podemos
    *(modificar el comportamiento de estas direcciones)*, por lo general, allí se almacenan los datos e 
    instrucciones que se desean modificar, sin comprometer la integridad del ISO.

# Reglas para este hilo.
  
*	`Respetar y agradecer` a todo el que te ayude en la resolución de algún problema.
  
*	Toda persona que esté interesada en aprender a crear/desarrollar cwcheats tiene la `responsabilidad de compartir sus resultados` y ayudar a otros que también estén en proceso de aprendizaje de estos.
  
*	Ayuda mutua para comprender lo aprendido y solucionar problemas.
  
*	`Toda pregunta es importante`, sin importar cuan tonta o básica suene, nadie nace aprendido.
  
*	No importa si el conocimiento es `básico, medio, o avanzado,` no se denigrará o minimizara al conocimiento del otro, ya que `es por falta de conocimiento e información de este tema` que se crea este hilo, (la idea/concepto en si de este hilo es `aprender desde 0.`)
  
*	Las personas con mayor nivel `ayudaran en lo posible` en la comprensión y solución de dudas.
  
*	No importa si no se tiene conocimiento del tema, `todo aporte` es de importancia.
  
*	Toda persona que cree y comparta un CwCheat, `debe dejar registrado el proceso de cómo fue creado,` ya sea tanto `textual` como en un `video`, (*preferiblemente*) de forma que, si al activarlo, este presenta `inconvenientes` como:
  
 	  * Crasheos del emulador.
 	  * Malos accesos en la memoria.
 	  * Crasheos en consola física psp.
    * No funciona o hace nada.
    * funciona parcialmente en diferentes zonas.
    * etc.
 	
  gracias a este registro, las personas podran ayudar a buscar la manera de `solucionar` y `explicar el origen del problema`, en dado caso, y esto ayudara a los mas nuevos en el futuro.
  
# El proceso de registro:
  
  `a.`Al crearse un cwcheat debe de `registrarse` en un archivo de `texto` **[todos los pasos que se realizaron para su creación!]** es decir, como se llegó a la **[dirección final]**, que por lo general, es la que se usamos al momento de `activar` el cwcheat.

  `b.`	Detallar los `valores` que **[venían originalmente/inicialmente]** en la `dirección original` del cwcheat y por cuales `fueron cambiados` y el `por qué` **(*la razon del cambio de ese valor*).**

  **OPCIONAL**
  
  `c.`	Crear un `video` con buen audio y el `paso a paso`, explicado `detalladamente` el cómo se creó el cheat.

   * * **Antes de comenzar la explicación/grabacion**, `se debe mostrar la versión del emulador y su configuración`, y de la misma forma con el `cheat engine`.
  
  `d.`	Este `video` se subiriá a una `cuenta genérica` de youtube (según en idioma del publico), ya que mantener videos directamente en el hilo, **cuesta dinero**, así que de esta forma nos evitamos este conflicto.
  
     * * Ejemplo: PPSSPP_CWCHEATS_ESPAÑOL_DUB
     * * Ejemplo: PPSSPP_CWCHEATS_ENGLISH_DUB
     * *  Ejemplo: PPSSPP_CWCHEATS_..._DUB

  `e.`	**Opcional pero muy importante:** Debido a que esta comunidad es bastante amplia, siempre nos encontraremos con problemas debido a la `barrera del lenguaje`, propongo como solución recaudar un pequeño fondo para abrir una cuenta en `RASK.AI` controlada por los moderadores, de esa manera con la inteligencia artificial podemos doblar los videos, de tal manera que esta barrera no sea un impedimento, de lo contrario en lo posible `ayudar en la creación de subtítulos` para estos videos.
  
Al terminar la creación del Cwcheat este debe `cumplir` los `requisitos` para ser `compartido` a la comunidad, de no ser así se debe `clarificar o filtrar` la fase o estado en la que se encuentra el cheat, de forma que se sepa que tan fiable es su uso de la siguiente manera:

![image](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/045d4145-7efc-4ec1-a848-a42f1c362784)
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
VERIFICAR SI CUMPLE LA MAYORIA DE LAS CONDICIONES DE IZQUIERDA A DERECHA: EJEMPLO... -A-A-A-A-B-C-B-A-A->
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
 
* Si en el proceso de filtrado todo o la gran mayoria esta en verde al momento de llegar a **los accesos a la memoria**, entonces es un cwcheat `confiable` y "estable", solo entonces se testea ese cwcheat en una consola física psp, de otra manera podía ocasionarse un hardbrick / softbrick. 

* Es muy `importante` **respetar los bites que se usan a la hora de crear un cwcheat** ya que si se modifica una dirección que no se debe, así sea solo un par de bites, esto puede crashear y generar conflictos, y en dado caso que se **guarde la partida** puede llegar a corromperse el savedata.

* SI un Cwcheat es `compartido en el hilo` y **no cumple el filtrado, dejar en claro que su uso es bajo su propio riesgo**, y debera comentar que es necesario `**arreglarlo**` antes de compartirlo/usarlo y que la razón por la que se comparte, es para `busca ayuda` a los demás para llegar a una posible `solución o fix` de este, ya que este no debe de compartirse en la red, ya que podíamos causar el brickeo de muchas consolas PSP halla fuera.

* **NOTA: Obviamente se necesita mucho mas que esto para que un cheat sea realmente `confiable y estable` para ello es necesario aprender un poco de MIPS, logica y aprender a seguir el flujo del juego.**

# Requisitos previos

* PPSSPP para Windows (recomendado, ya que incluye exclusivamente Debugger).
* Un juego en formato ISO previamente dumpeado en la libreria de juegos de PPSSPP en este caso usamos el juego ULUS10022: The legend of heroes
* Editor de memoria como CheatEngine o ArtMoney.
* Aquí se recomienda encarecidamente Windows; la edición de memoria externa está limitada en otros sistemas operativos.
* [Notepad++](https://notepad-plus-plus.org) para análisis detallados de parches PPSSPP.
* Funcionalidad analítica, de agregación e inferencia del cerebro humano.

# GUIA:
* Comprension de la estructura de los datos tipo cwcheat.
* Herramienta cheat engine.
* Porteo de Cwcheat entre diferentes versiones del juego.
  
![ceppsspptut es_pages-to-jpg-0001](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/09d53a16-6e68-453d-8d22-a2f013a05153)
![ceppsspptut es_pages-to-jpg-0002](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/1c22cfeb-e79f-4c3b-9e8e-2e6847d8806c)
![ceppsspptut es_pages-to-jpg-0003](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/d9f805c7-5b36-49bc-91a7-3a5690c4a5df)
![ceppsspptut es_pages-to-jpg-0004](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/af46399d-8a92-4ea0-aee7-8be16a1fb6aa)
![ceppsspptut es_pages-to-jpg-0005](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/e6f35ecb-9378-442a-b1b1-b9ae5933fa17)
![ceppsspptut es_pages-to-jpg-0006](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/8fa78e8c-bf83-4287-b9ec-b59329eb11c0)
![ceppsspptut es_pages-to-jpg-0007](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/e8cd0b05-02e7-4649-acaf-b0e8784f7209)
![ceppsspptut es_pages-to-jpg-0008](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/5b979e61-ceef-49b2-af76-ebae21041ea5)
![ceppsspptut es_pages-to-jpg-0009](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/5c1f716b-46bb-4c14-90ca-d2acbe5d2781)
![ceppsspptut es_pages-to-jpg-0010](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/71a1ebcc-8275-4900-ba2b-94b13aa39628)
![ceppsspptut es_pages-to-jpg-0011](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/3e5c2acf-bc63-4e34-8bfd-557116ba4e3d)
![ceppsspptut es_pages-to-jpg-0012](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/58aafa3e-3dc9-4fc9-bafe-579a926b959c)
![ceppsspptut es_pages-to-jpg-0013](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/a166da06-342e-4696-813d-2d7b289cf31f)
![ceppsspptut es_pages-to-jpg-0014](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/15473f75-1526-4825-b969-f9fdecf0f648)
![ceppsspptut es_pages-to-jpg-0015](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/2e9bf369-c589-4cc7-a3af-828f225d5693)
![ceppsspptut es_pages-to-jpg-0016](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/9c72a428-ea97-4018-a98c-115aa6541519)
![ceppsspptut es_pages-to-jpg-0017](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/928cff14-046d-48d4-b3e5-8c3106e235a1)
![ceppsspptut es_pages-to-jpg-0018](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/8e1d2f02-6964-481f-8b9c-443b6d72182b)
![ceppsspptut es_pages-to-jpg-0019](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/765583cb-9467-404e-9898-ec50fe09cf92)
![ceppsspptut es_pages-to-jpg-0020](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/c5703e8b-1d1d-4b0c-bc3f-0000a0a346f6)
![ceppsspptut es_pages-to-jpg-0021](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/dc5dbd2d-c59c-4ce1-af37-214d70c6e06a)
![ceppsspptut es_pages-to-jpg-0022](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/51a59811-afad-4968-bfec-77cea6a1b95a)
![ceppsspptut es_pages-to-jpg-0023](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/6acf8e4d-4c9c-414a-b43e-fd66a3f350b5)
![ceppsspptut es_pages-to-jpg-0024](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/b9b10107-a4c6-4f50-bfdf-56bb7743b818)
![ceppsspptut es_pages-to-jpg-0025](https://github.com/xkynet/creaccion-de-cwcheat/assets/160412710/15693072-b917-41d1-97f5-fb9d35d14c4b)
Link de la guia en PDF en Español.
[ceppsspptut.es.pdf](https://github.com/xkynet/creaccion-de-cwcheat/files/14323804/ceppsspptut.es.pdf)
Link de la guia en PDF en Ingles.
[ceppsspptut.pdf](https://github.com/xkynet/creaccion-de-cwcheat/files/14323805/ceppsspptut.pdf)


