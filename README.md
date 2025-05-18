# Tarea 2: Modelos generativos de imágenes y lenguajes

Evaluar y comparar el desempeño de diferentes modelos de generación de imágenes a partir de prompts y anti-prompts creados mediante un modelo de lenguaje generativo, utilizando frases extraídas de libros como base inicial.

--- 
# Frases a usar 

- `Un dragón sin su jinete es una tragedia. Un jinete sin su dragón está muerto.` - Alas de Sangre, Rebecca Yarros.
- `Hasta el día de hoy, no he sido capaz de romper la conexión entre este chico, Peeta Mellark, el pan que me dio esperanza y el diente de león que me recordó que no estaba condenada` - Los Juegos del Hambre - Suzanne Collins.
- `Cuando se juega al juego de trono, solo se puede ganar o morir. No hay puntos intermedios.` - Juego de Tronos 1: Canción de Hielo y Fuego - George R.R Martin.

## Prompts Generados con su Antiprompt + Imágenes Generadas
### Frase 1: Un dragón sin su jinete es una tragedia. Un jinete sin su dragón está muerto.

#### Prompt y Antiprompt 1
-  Prompt: Un dragón anciano y cansado yace sobre una colina cubierta de hierba seca, su escama brillante y sucia, mientras que en el fondo, un jinete caído y sin vida yace en el suelo, su armadura oxidada y rota.
- Antiprompt: Evita generar una imagen con un dragón demasiado colorido o brillante, evita mostrar al jinete con expresiones de dolor o sufrimiento, evita incluir elementos sobrenaturales o fantasiosos que no estén directamente relacionados con la frase.


- Imagen modelo Stable Diffusion XL  
![Prompt1](images/Frase_1/Stabilityai/imagen_1.png)

- Imagen modelo PixArt-α  
![Prompt1](images/Frase_1/PixArt/imagen_1.png)

Coherencia:
El primer modelo presenta una imagen coherente con lo solicitado mayormente ya que falta el jinete. Mientras que el segundo modelo no arroja una imagen relacionada, se solicita un dragón y muestra un águila.

---

#### Prompt y Antiprompt 2
- Prompt: Un campo de batalla abandonado, con un dragón grande y poderoso, solo y desolado, rodeado de cadáveres de jinetes y caballos, con un fondo de cielo oscuro y nubes negras.
- Antiprompt:  Evita mostrar un dragón con un jinete a su lado, no incluyas detalles de la batalla, no muestres un dragón atacando a un jinete, no incluyas texto o leyendas en la imagen.

- Imagen modelo Stable Diffusion XL  
![Prompt2](images/Frase_1/Stabilityai/imagen_2.png)

- Imagen modelo PixArt-α  
![Prompt2](images/Frase_1/PixArt/imagen_2.png)

Coherencia:
El primer modelo no arroja una imagen muy relacionada, ya que no muestra al dragón ni el campo de batalla con jinetes muertos pero si la nube gris en el cielo. Mientras que el segundo modelo tampoco muestra lo solicitado pero si da a entender que se pudo estar en un campo de batalla y aparece un jinete, solo que de caballo y no de dragón. 

---

#### Prompt y Antiprompt 3
- Prompt: Un campo de batalla cubierto de niebla, donde un dragón herido yaciera solo, sin su jinete, con las alas rotas y la cola partida, rodeado de cadáveres de soldados y caballos, con un sol poniente detrás que ilumina la escena con tonos dorados y rojizos.
- Antiprompt: Evita generar una imagen que muestre un dragón con alas intactas y una cola entera, o un jinete montado en un dragón sin heridas, o una escena de batalla con soldados y caballos sin muertes, o un sol que ilumine la escena con tonos brillantes y vivos.

- Imagen modelo Stable Diffusion XL  
![Prompt3](images/Frase_1/Stabilityai/imagen_3.png)

- Imagen modelo PixArt-α  
![Prompt3](images/Frase_1/PixArt/imagen_3.png)

Coherencia:
El primer modelo muestra una imagen cero relacionada, exceptuando por la niebla en el campo de batalla. Mientras que el segundo modelo muestra algo más cercano a lo solicitado, exceptuando porque muestra un caballo y no un dragón.

---

#### Prompt y Antiprompt 4
- Prompt: Un dragón grande y viejo, con escamas cubiertas de polvo y una mirada lastimera, se sienta solo en un valle de piedra, mientras que en el cielo, un jinete sin armadura cae en picado hacia el suelo.
- Antiprompt: Evita imágenes con dragones felinos, jinetes con armaduras brillantes o escenas de batalla, y no incluyas elementos sobrenaturales o de fantasía exagerados.

- Imagen modelo Stable Diffusion XL  
![Prompt4](images/Frase_1/Stabilityai/imagen_4.png)

- Imagen modelo PixArt-α  
![Prompt4](images/Frase_1/PixArt/imagen_4.png)

Coherencia:
El primer modelo muestra gran parte de lo solicitado, muestra al dragón solo en un valle pero falta la parte del jinete cayendo. El segundo modelo, muestra lo que debería evitar, es decir, un dragón felino. 

---

#### Prompt y Antiprompt 5
- Prompt: Un dragón solitario yacía en una llanura desolada, su escudo vacío y su cola doblada en un gesto de desesperación, mientras que en el cielo, un jinete sin dragón caía hacia la tierra, su armadura cubierta de polvo y su espada brillando débilmente en la luz del sol.
- Antiprompt: No genere una imagen con un dragón que parezca feliz o juguetón, ni un jinete que esté sonriendo o saludando, evite colores vivos y brillantes, y no incluya objetos innecesarios o elementos que distraigan la atención del tema principal.

- Imagen modelo Stable Diffusion XL  
![Prompt5](images/Frase_1/Stabilityai/imagen_5.png)

- Imagen modelo PixArt-α  
![Prompt5](images/Frase_1/PixArt/imagen_5.png)

Coherencia: 
El primer modelo muestra una imagen relacionada a lo solicitado y a lo que se debe evitar, solo no muestra al jinete a lo lejos. El segundo modelo muestra algo relacionado al poner al jinete pero lo hace en primer plano y no hay muestra del dragón. 

---

#### Prompt y Antiprompt 6
- Prompt: Un jardín secreto, rodeado de árboles antiguos, donde un dragón dorado yacía inmóvil, rodeado de flores moribundas y una tumba oscura, con un jinete sin vida a su lado, rodeado de hierbas silvestres y sombras.
- Antiprompt: Evita imágenes con colores vibrantes y brillantes, no incluyas personajes humanos saludables, no muestres un dragón en vuelo o combate, no incluyas objetos o elementos que no sean naturales o relacionados con la muerte.

- Imagen modelo Stable Diffusion XL  
![Prompt6](images/Frase_1/Stabilityai/imagen_6.png)

- Imagen modelo PixArt-α  
![Prompt6](images/Frase_1/PixArt/imagen_6.png)

Coherencia: 
El primer modelo muestra el jardín tal cómo se solicita pero no muestra nada más del prompt, con el segundo modelo pasa exactamente lo mismo.

---

#### Prompt y Antiprompt 7
- Prompt: Un jardín abandonado, con un dragón gigante yacido en el centro, rodeado de hierbas y flores silvestres, con la armadura de su jinete rota y desmoronada a su lado, bajo un cielo oscuro y lluvioso.
- Antiprompt: No genere una imagen con un dragón que parezca feliz o juguetón, evite la presencia de otros seres vivos en la escena, no incluya objetos modernos o tecnológicos y no utilice colores brillantes o vivos.

- Imagen modelo Stable Diffusion XL  
![Prompt7](images/Frase_1/Stabilityai/imagen_7.png)

- Imagen modelo PixArt-α  
![Prompt7](images/Frase_1/PixArt/imagen_7.png)

Coherencia:
Al igual que con el prompt anterior, el primer modelo muestra solo el campo pero nada más, a diferencia del segundo que muestra de forma precisa lo que fue solicitado. 

---

#### Prompt y Antiprompt 8
- Prompt: Un valle soleado yermo, con un dragón grande y anciano sentado sobre una roca, rodeado de una aureola de polvo y sombras, mientras un jinete sin vida yace a sus pies, con una espada rota a su lado.
- Antiprompt: Evita imágenes con colores brillantes o exagerados, no incluyas objetos innecesarios, no representes al dragón con expresión agresiva o emocional, y no centras la atención en el jinete más que en el dragón.

- Imagen modelo Stable Diffusion XL  
![Prompt8](images/Frase_1/Stabilityai/imagen_8.png)

- Imagen modelo PixArt-α  
![Prompt8](images/Frase_1/PixArt/imagen_8.png)

Coherencia: 
La imagen del primer modelo, es casi igual a lo solicitado, mientras que el segundo ni similar al prompt. 

---

#### Prompt y Antiprompt 9
- Prompt: Un valle oscuro y solitario, iluminado solo por la llama de un dragón muerto, con el jinete caído a sus pies, rodeado de restos de armas y armaduras.
- Antiprompt: No genere imágenes de dragones felinos, jinetes con armaduras brillantes o escenas de batallas épicas.

- Imagen modelo Stable Diffusion XL  
![Prompt9](images/Frase_1/Stabilityai/imagen_9.png)

- Imagen modelo PixArt-α  
![Prompt9](images/Frase_1/PixArt/imagen_9.png)

Coherencia: 
El primer modelo muestra una imagen que no se ajusta a lo solicitado, mientras que el segundo muestra una llama que es lo único que ilumina la imagen pero no del dragón y el jinete.  

---

#### Prompt y Antiprompt 10
- Prompt: Un escenario medieval con un dragón grande y poderoso, solo y abandonado en un campo de batalla, con armas y armaduras dispersas alrededor, evocando sentimiento de tristeza y soledad.
- Antiprompt: No incluya a un jinete o figura humana en la imagen, no muestre armas o objetos que sugieran combate o victoria, no utilice colores vibrantes o brillantes, evita representaciones de drama o tragedia exageradas.

- Imagen modelo Stable Diffusion XL  
![Prompt10](images/Frase_1/Stabilityai/imagen_10.png)

- Imagen modelo PixArt-α  
![Prompt10](images/Frase_1/PixArt/imagen_10.png)

Coherencia:
Ambos modelos muestran una imagen muy parecida a lo que se solicita aunque no sigue muy bien las instrucciones de lo que se debe evitar en el primero.

### Frase 2: Hasta el día de hoy, no he sido capaz de romper la conexión entre este chico, Peeta Mellark, el pan que me dio esperanza y el diente de león que me recordó que no estaba condenada

#### Prompt y Antiprompt 1
- Prompt: Una escena nocturna en un jardín abandonado, donde una figura femenina, con un vestido suelto y cabello suelto, se sienta en un banco de piedra, rodeada de flores marchitas, con un pan tostado y un diente de león a su lado, mirando hacia atrás con una expresión melancólica.
- Antiprompt: Evita la representación de la figura femenina como una modelo de moda, no incluyas objetos innecesarios en la escena, no utilices colores brillantes ni efectos visuales exagerados, no muestres la figura femenina con una expresión de tristeza o desesperanza, no incluyas fondo o texturas que distraigan la atención del objeto de la escena.

- Imagen modelo Stable Diffusion XL  
![Prompt1](images/Frase_2/Stabilityai/imagen_1.png)

- Imagen modelo PixArt-α  
![Prompt1](images/Frase_2/PixArt/imagen_1.png)

Coherencia: 
En ambas imagenes se muestra gran parte de lo solicitado, faltan detalles clave cómo el pan y el diente de león.

---

#### Prompt y Antiprompt 2
- Prompt: Una joven con un vestido blanco y un cabello castaño claro se sienta en una mesa de madera en un jardín abandonado, con un pedazo de pan en la mano y un diente de león en la otra, mientras que en el fondo se ve un mural de la ciudad de Panem en ruinas.
- Antiprompt: Evita imágenes con colores brillantes y exagerados, no incluyas a otros personajes de la trilogía, no representes la escena en un entorno urbano o industrial, no incluyas objetos o elementos que no estén directamente relacionados con la frase, evita crear una atmósfera de violencia o drama.


- Imagen modelo Stable Diffusion XL  
![Prompt2](images/Frase_2/Stabilityai/imagen_2.png)

- Imagen modelo PixArt-α  
![Prompt2](images/Frase_2/PixArt/imagen_2.png)

Coherencia: 
En ambas imagenes se muestra gran parte de lo solicitado, faltan detalles clave el muro en la parte trasera de la imagen.

---

#### Prompt y Antiprompt 3
- Prompt: "Una escena en un jardín abandonado, con un chico joven, Peeta Mellark, sentado en una piedra, con un pan en su mano, mientras un diente de león dorado reposa en el suelo a su lado, con una luz tenue y melancólica que ilumina la escena."
- Antiprompt: "Evita imágenes con un fondo colorido y brillante, no incluyas figuras adicionales, no utilices efectos de luz exagerados, no muestres el rostro de Peeta con una expresión feliz o sonriente, no incluyas elementos que distraigan la atención del pan y el diente de león."

- Imagen modelo Stable Diffusion XL  
![Prompt3](images/Frase_2/Stabilityai/imagen_3.png)

- Imagen modelo PixArt-α  
![Prompt3](images/Frase_2/PixArt/imagen_3.png)

Coherencia:
El primer modelo muestra una imagen más cercana a lo que solicita pero faltan objetos importante como el pan. Mientras que el segundo también muestra lo principal, pero muestra un león, no la flor diente de león.

---

#### Prompt y Antiprompt 4
- Prompt: Una escena en blanco y negro, con una joven (Katniss) sentada en un árbol, rodeada de hojas secas y ramas, con un pedazo de pan y un diente de león en su mano, mirando hacia abajo con una expresión reflexiva y melancólica.
- Antiprompt: Evita imágenes con colores vibrantes, personajes con expresiones felices o triunfales, escenas con acción o movimiento rápido, y objetos que no estén relacionados con la historia o la emoción de la frase.


- Imagen modelo Stable Diffusion XL  
![Prompt4](images/Frase_2/Stabilityai/imagen_4.png)

- Imagen modelo PixArt-α  
![Prompt4](images/Frase_2/PixArt/imagen_4.png)

Coherencia: 
En ambas imagenes se muestra lo mismo solo de forma ligeramente diferente. En ambas faltan los mismos elementos, es decir, el pan y el diente de león. 

---

#### Prompt y Antiprompt 5
- Prompt: Una escena nocturna en un bosque, donde una figura femenina, con el cabello suelto y la ropa rasgada, se sienta en un tronco caído, rodeada de flores silvestres y hojas secas, con un diente de león en la mano y un panadero en el suelo a su lado, con un pan en la mesa entre ellos, iluminada por la luna llena.
- Antiprompt: Evita la representación de una escena romántica o sensual, no incluyas figuras adicionales, no uses colores vibrantes ni efectos de iluminación exagerados, no muestra la cara de la figura femenina, no incluyas objetos innecesarios en la escena, no crea una sensación de drama o tensión.

- Imagen modelo Stable Diffusion XL  
![Prompt5](images/Frase_2/Stabilityai/imagen_5.png)

- Imagen modelo PixArt-α  
![Prompt5](images/Frase_2/PixArt/imagen_5.png)

Coherencia:
Ningun modelo muestra lo que se solicita, solo se muestra a la chica pero no todo el resto de elementos que le dan coherencia a lo solicitado.

---

#### Prompt y Antiprompt 6
- Prompt: Una escena en blanco y negro, con una joven rubia sentada en un banco, rodeada de pan y otros alimentos, con un diente de león en la mano, mientras mira hacia atrás, con un aire de nostalgia y melancolía, evocando la conexión entre el chico, el pan y el diente de león que la recuerdan de su pasado.
- Antiprompt: Evita la representación de la escena con colores vibrantes, evita la inclusión de elementos que distraigan la atención del personaje principal, no incluyas objetos que no estén relacionados con la historia, no utilices texturas o efectos visuales que distraigan la atención del espectador, y no hagas que el personaje principal tenga una expresión demasiado feliz o alegre.


- Imagen modelo Stable Diffusion XL  
![Prompt6](images/Frase_2/Stabilityai/imagen_6.png)

- Imagen modelo PixArt-α  
![Prompt6](images/Frase_2/PixArt/imagen_6.png)

Coherencia:
El primer modelo muestra parte de lo solicitado, que es la chica con la escena en blanco y negro pero nada más faltan elementos como el pan, otros alimentos entre otros. La segunda imagen muestra algo más cercano a lo solicitado pero en vez de la flor diente de león muestra a un león. 

---

#### Prompt y Antiprompt 7
- Prompt: Un cuadro en blanco y negro que muestra a Katniss Everdeen sentada en un banco, con un pedazo de pan en su mano izquierda y un diente de león en su mano derecha, con una expresión melancólica en su rostro, mientras que en el fondo, se ve una imagen borrosa de Peeta Mellark sonriendo, con un pan caliente en su mano.
- Antiprompt: Evita imágenes que sean demasiado coloridas o brillantes, evita incluir elementos que distraigan la atención de Katniss, como personas o objetos en el primer plano, y no incluyas texto o subtítulos que distraigan la atención del espectador.

- Imagen modelo Stable Diffusion XL  
![Prompt7](images/Frase_2/Stabilityai/imagen_7.png)

- Imagen modelo PixArt-α  
![Prompt7](images/Frase_2/PixArt/imagen_7.png)

Coherencia:
El primer modelo parece tener más un contexto sobre quien es el personje que se solicita ya que las caracteristicas del personaje que se muestra es muy similar a la persona de la que se habla, pero hablando de otros elementos falta todo menos Katniss. El segundo modelo pareciera no tener la misma información ya que muestra a una persona no parecida a Katniss y el resto del prompt tampoco está presente. 

---

#### Prompt y Antiprompt 8
- Prompt: Una imagen de una joven con un vestido blanco y un cabello rubio, sentada en un jardín con flores rojas, rodeada de pan y panadería, con un diente de león en la mano, y en el fondo, una ciudad en ruinas.
- Antiprompt: Evita la representación de la escena con un fondo de guerra o destrucción, no incluyas a otros personajes, no utilices colores vibrantes o llamativos, no muestres la cara de la joven de manera detallada, y no incluyas elementos que sugieran violencia o sufrimiento.


- Imagen modelo Stable Diffusion XL  
![Prompt8](images/Frase_2/Stabilityai/imagen_8.png)


- Imagen modelo PixArt-α  
![Prompt8](images/Frase_2/PixArt/imagen_8.png)

Coherencia: 
Ambas imagenes muestran lo mismo y siguen gran parte del prompt menos la sección de la ciudad en ruinas, muestran algo ídilico mientras que debiese ser algo distópico.

---

#### Prompt y Antiprompt 9
- Prompt: Una escena nocturna en un campo de ruinas, con Peeta Mellark sentado en un tronco de árbol, rodeado de panes y frutas, con un diente de león en su mano derecha, y Katniss Everdeen de pie detrás de él, con una mirada nostálgica y una expresión de melancolía.
- Antiprompt: Evita imágenes con colores vivos y brillantes, no incluyas a otros personajes del libro comoDistrict 12 o el Capitolio, no representes la conexión entre Peeta y Katniss de manera explícita o romántica, y no incluyas elementos que sugieran violencia o peligro.

- Imagen modelo Stable Diffusion XL  
![Prompt9](images/Frase_2/Stabilityai/imagen_9.png)

- Imagen modelo PixArt-α  
![Prompt9](images/Frase_2/PixArt/imagen_9.png)

Coherencia:
El primer modelo muestra tal cual lo que se solicita y da las vibras de ser una escena perfecta. Mientras que la segunda falta el detalle de que uno de los personajes no está. 

---

#### Prompt y Antiprompt 10
- Prompt: Una joven, Katniss Everdeen, sentada en una roca, con un pan y un diente de león a su lado, mirando hacia el horizonte con un semblante pensativo, evocando la nostalgia y la reflexión sobre su pasado.
- Antiprompt: No generar imágenes de Katniss con expresiones agresivas o violentas, no incluir elementos que sugieran una conexión romántica con Peeta, no representar a Katniss con armas o vestimenta de combate, no mostrar la escena en un entorno urbano o industrial.

- Imagen modelo Stable Diffusion XL  
![Prompt10](images/Frase_2/Stabilityai/imagen_10.png)

- Imagen modelo PixArt-α  
![Prompt10](images/Frase_2/PixArt/imagen_10.png)

Coherencia: 
En la primera imagen se muestra más cercano a lo que se solicita ya que la imagen si da un aire melancólico pero faltan elementos de lo solicitado. El segundo no da el mismo aire, si no uno más vivaz pero muestra un león y no un diente de león. 

### Frase 3: Cuando se juega al juego de tronos, solo se puede ganar o morir. No hay puntos intermedios.

#### Prompt y Antiprompt 1
- Prompt: "Una mesa de juego de trono rodeada de sombras, con dos jugadores sentados en silencio, cada uno con un rostro serio y concentrado, rodeados de cartas y dados, con un ambiente oscuro y amenazador que sugiere la proximidad de la victoria o la derrota."
- Antiprompt: "No incluir figuras humanas ridículas, no mostrar la mesa de juego con un fondo colorido y animado, no incluir elementos que sugieran la presencia de puntos intermedios en el juego, no utilizar colores brillantes ni texturas extrañas."


- Imagen modelo Stable Diffusion XL  
![Prompt1](images/Frase_3/Stabilityai/imagen_1.png)

- Imagen modelo PixArt-α  
![Prompt1](images/Frase_3/PixArt/imagen_1.png)

Coherencia: 
Ambos modelos arrojan imágenes que cumplen en general con el prompt y siguien las instrucciones de qué cosas deben evitar. Eso si, la primnera imagen tiene más relación a la época medieval que la segunda lo que la hace ligeramente más correcta.

---

#### Prompt y Antiprompt 2
- Prompt: "Una mesa de juego de trono oscura y circular, rodeada de figuras oscuras y sombrías, con un rey y una reina sentados en el centro, cada uno con una mirada intensa y decidida, mientras un jugador caído yacía en el suelo, con un trono vacío detrás de él."
- Antiprompt: "Evita imágenes de juego de trono tradicional con piezas de madera y colores brillantes, no incluye elementos de fantasía como dragones o criaturas mágicas, no hay figuras femeninas que no sean la reina, no hay elementos de humor o ironía, no hay escenas de victoria o celebración."

- Imagen modelo Stable Diffusion XL  
![Prompt2](images/Frase_3/Stabilityai/imagen_2.png)

- Imagen modelo PixArt-α  
![Prompt2](images/Frase_3/PixArt/imagen_2.png)

Coherencia:
El primer modelo tiene características más precisas de lo solicitado,falta la mesa pero en todo lo demás está correcto. El segundo tiene la mesa y las personas pero falta el trono y lo que eso significa.

---

#### Prompt y Antiprompt 3
- Prompt: Un rey coronado sentado en un trono de piedra negra, rodeado de un halo de llamas que iluminan su rostro serio y decidido, con un juego de tronos en segundo plano, mientras que en la distancia se ve una ciudad en ruinas y un ejército de soldados en retirada.
- Antiprompt: Evita generar imágenes de un rey rodeado de flores, con un trono de madera blanca y un paisaje de campo verde y soleado, con una ciudad en el fondo con edificios altos y coloridos.

- Imagen modelo Stable Diffusion XL  
![Prompt3](images/Frase_3/Stabilityai/imagen_3.png)

- Imagen modelo PixArt-α  
![Prompt3](images/Frase_3/PixArt/imagen_3.png)

Coherencia:
En ambos modelos faltan elementos clave de lo solicitado, por ejemplo la ciudad en ruinas o los ejercitos. Pero cumplen con una parte, el segundo es más cercano a lo solicitado que el primero. 

---

#### Prompt y Antiprompt 4
- Prompt: Un rey sentado en un trono de piedra, con una espada en su mano derecha y un reino en llamas detrás de él, rodeado de cadáveres de sus súbditos caídos.
- Antiprompt: Evita imágenes con colores pastel, flores, o elementos lúdicos, y no representes al rey con una sonrisa o un gesto alegre, mantén la escena oscura y dramática, y no incluyas elementos que sugieran un final feliz o un compromiso.

- Imagen modelo Stable Diffusion XL  
![Prompt4](images/Frase_3/Stabilityai/imagen_4.png)

- Imagen modelo PixArt-α  
![Prompt4](images/Frase_3/PixArt/imagen_4.png)

Coherencia: 
Ambos modelos muestran la misma imagen con la misma falta de elementos claves cómo el reino en llamas o los cadáveres,

---

#### Prompt y Antiprompt 5
- Prompt: Una escena de un juego de mesa con un tablero de madera oscura y piezas de metal brillante, donde un jugador con una expresión seria y concentrada está a punto de derrotar a su oponente, que tiene una pieza caída en el suelo y una mirada de desesperación en su rostro, rodeados de cartas y dados esparcidos por la mesa.
- Antiprompt: Evita crear una escena con figuras de personajes con expresiones felices o relajadas, no incluyas objetos innecesarios como floreros o jarrones, y no representes la mesa con un fondo excesivamente brillante o llamativo, enfócate en la tensión y la dramática del momento clave del juego.


- Imagen modelo Stable Diffusion XL  
![Prompt5](images/Frase_3/Stabilityai/imagen_5.png)

- Imagen modelo PixArt-α  
![Prompt5](images/Frase_3/PixArt/imagen_5.png)

Coherencia: 
La primera imagen tiene cero relación a lo solicitado, mientras que la segunda cumple gran parte del prompt. Cabe mencionar que este promnpt igual no tiene mucha relación al significado o contexto de la frase original. 

---

#### Prompt y Antiprompt 6
- Prompt: "Un rey sentado en un trono de piedra negra, con un ejército de soldados muertos a sus pies, rodeado de una niebla oscura y pesada, con una mirada de determinación en sus ojos, como si estuviera dispuesto a luchar hasta la muerte por el trono que ocupa."
- Antiprompt: "No generar imágenes de reyes felices o sonrientes, no incluir elementos de fantasía o mágicos, no mostrar a los soldados muertos como fantasmas o espectros, no incluir colores brillantes o vivos en la escena."

- Imagen modelo Stable Diffusion XL  
![Prompt6](images/Frase_3/Stabilityai/imagen_6.png)

- Imagen modelo PixArt-α  
![Prompt6](images/Frase_3/PixArt/imagen_6.png)

Coherencia: 
Ambos modelos muestran la misma imagen con la misma falta de elementos claves cómo los cadáveres.

---

#### Prompt y Antiprompt 7
- Prompt: Una mesa de juego oscura y laberíntica, con piezas de ajedrez humanas y monstruosas, rodeada de velas que danzan en la sombra, mientras un rey y una reina se enfrentan en un duelo mortal, con el destino de sus reinos en juego.
- Antiprompt: Evita imagenes con colores brillantes y vibrantes, no incluyas objetos cotidianos como teléfonos o relojes, no representes a los personajes con expresiones neutrales o sonrientes, no incluyas fondo de paisajes naturales, y no hagas que los personajes estén relajados o distraídos.


- Imagen modelo Stable Diffusion XL  
![Prompt7](images/Frase_3/Stabilityai/imagen_7.png)


- Imagen modelo PixArt-α  
![Prompt7](images/Frase_3/PixArt/imagen_7.png)

Coherencia:
La primera imagen tiene poca o nulo sentido, ponen dragones humanizados jugando ajedrez que no fue precisamente lo que se solicito, por otro lado el segundo modelo generó imágenes más relacionadas a lo solicitado, el juego y las personas entablandose en casi un juego mortal.

---

#### Prompt y Antiprompt 8
- Prompt: Un rey sentado en un trono, con un rostro serio y determinado, rodeado de un halo de luz, con un puñal ensangrentado en la mano derecha, mientras en el fondo se ve una ciudad en ruinas y un cielo oscuro y tormentoso.
- Antiprompt: Evita imágenes con colores pastel, flores, animales felices o escenas idílicas, y no representes al rey sonriendo o con expresiones de alegría, ni incluyas elementos como arcoíris, nubes blancas o un sol brillante.

- Imagen modelo Stable Diffusion XL  
![Prompt8](images/Frase_3/Stabilityai/imagen_8.png)

- Imagen modelo PixArt-α  
![Prompt8](images/Frase_3/PixArt/imagen_8.png)

Coherencia: 
Ambos modelos muestran la misma imagen con la misma falta de elementos claves cómo la ciudad en ruinas.

---

#### Prompt y Antiprompt 9
- Prompt: Una mesa de juego destruida, con piezas de ajedrez desparramadas por el suelo, rodeada de dos figuras oscuras y majestuosas, con ropas rasgadas y armas rotas, que se enfrentan en un duelo mortal, con un fondo de niebla y sombras que sugieren la proximidad de la muerte.
- Antiprompt: Evita imágenes con elementos de color brillante o alegres, no incluyas figuras de fondo con expresiones sonrientes o risueñas, no utilices texturas suaves o abstractas, y no colores demasiado vivos o llamativos.

- Imagen modelo Stable Diffusion XL  
![Prompt9](images/Frase_3/Stabilityai/imagen_9.png)

- Imagen modelo PixArt-α  
![Prompt9](images/Frase_3/PixArt/imagen_9.png)

Coherencia:
Ninguna de las dos imágenes plasman lo que se busca, el prompt parte con el juego destriudo pero ninguna imagen muestra eso. La coherencia entre lo solicitado y lo entregado en ambos casos es muy baja. 

---

#### Prompt y Antiprompt 10
- Prompt: "Un jugador solitario se sienta en un trono de piedra, rodeado de sombras y velas que iluminan la habitación. Su mirada está fija en el tablero de juego, donde las piezas de madera están dispuestas en una configuración letal. La cuestión es: ¿quién saldrá vivo de esta partida?"
- Antiprompt: "Evita generar una imagen que sea demasiado colorida o alegre, no hay espacio para la esperanza en este juego. No incluyas elementos como flores, arcoíris o personas felices en la escena. Enfócate en la tensión y la dramática, y asegúrate de que el jugador esté rodeado de sombras y oscuridad."

- Imagen modelo Stable Diffusion XL  
![Prompt10](images/Frase_3/Stabilityai/imagen_10.png)

- Imagen modelo PixArt-α  
![Prompt10](images/Frase_3/PixArt/imagen_10.png)

Coherencia: 
Ambas imagenes se acercan mucho a los solicitado. Incluyen los elementos como el jugador solitario, el trono, las sombras y velas que iluminan la habitación. Coherencia alta.

# Estructura del código

El archivo principal `Tarea2-IPD441-Tabata Ahumada.ipynb` contiene todo el flujo de procesamiento, incluyendo:

- Se conecta al token de Hugging Face
- Se descarga una carpeta con tipografía para poder poner la frase en la imagen considerando actuación.
- Se carga el modelo Llama3
- Se ejecuta un for que recorre las frases mencionadas para la generación de prompts y antiprompts inspirados en dichas imágenes y los guarda en un array para su posterior uso.
- Se imprimen todas los textos generados por frase
- Eliminamos lo relacionado a Llama3 para liberar uso de GPU
- Se crea una función con lo necesario para poner el texto en la imagen
- Se crea una función general para la generación de imágenes cuyos parámetro definirá qué modelo se utiliza.
- Se carga modelo stabilityai/stable-diffusion-xl-base-1.0
- Se ejecuta la función de generar imagenes con este modelo para los parámetros por default
- Se ejecuta la función de generar imagenes con este modelo para los parámetros modificados. 
- Eliminamos lo relacionado al modelo para liberar uso de GPU
- Se carga modelo PixArt-alpha/PixArt-XL-2-1024-MS
- Se ejecuta la función de generar imagenes con este modelo para los parámetros por default
- Se ejecuta la función de generar imagenes con este modelo para los parámetros modificados. 
- Eliminamos lo relacionado al modelo para liberar uso de GPU

# Preguntas

## ¿Cuáles fueron los parámetros seleccionados por cada modelo para ajustar y cómo afectaron la generación de la imagen?
## ¿Cuál es la arquitectura subyacente del modelo que estás utilizando?
## ¿Qué datos de entrenamiento se utilizaron para entrenar este modelo y cómo afecta esto a la diversidad de las imágenes generadas?
## ¿Cuáles son las limitaciones de los modelos que estás usando en términos de resolución, coherencia visual y generación realista de detalles?
## ¿Cómo maneja el modelo la variabilidad en la generación de imágenes? ¿Utiliza redes neuronales convolucionales (CNNs), transformers u otra técnica para capturar patrones visuales?
## ¿Qué diferencias clave has encontrado entre los modelos de generación de imágenes que has probado en términos de calidad de salida, velocidad de generación y precisión visual?
## ¿Cómo afectan las configuraciones de parámetros (como la resolución, el tamaño de la imagen y el número de iteraciones) a la calidad final de la imagen generada por cada modelo?