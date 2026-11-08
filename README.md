# Sugarbell 🍰
## Game Design Document (GDD)

<img width="1000" height="1000" alt="WhatsApp Image 2026-11-07 at 11 49 10 PM" src="https://github.com/user-attachments/assets/1f9752b3-6d24-4e33-892a-c8776155ee90" />


- [Especificaciones técnicas](#especificaciones-técnicas)
- [Cómo se juega](#cómo-se-juega)
- [Sinopsis](#sinopsis)
- [Elementos del juego](#elementos-del-juego)
- [Niveles del juego](#niveles-del-juego)
- [Control del jugador](#control-del-jugador)
- [Por qué es divertido este juego](#por-qué-es-divertido-este-juego)
- [Características clave](#características-clave)
- [Documento de diseño](#documento-de-diseño)
- [Guía de diseño](#guía-de-diseño)
- [Definiciones de diseño del juego](#definiciones-de-diseño-del-juego)
- [Transiciones entre niveles](#transiciones-entre-niveles)
- [Fracaso del nivel](#fracaso-del-nivel)
- [Enfoque principal del juego](#enfoque-principal-del-juego)
- [Diagrama de flujo del juego](#diagrama-de-flujo-del-juego)
- [Definición de jugador](#definición-de-jugador)
- [Propiedades del jugador](#propiedades-del-jugador)
- [Interfaz de usuario (UI)](#interfaz-de-usuario-ui)
- [Enlaces de interés](#enlaces-de-interés)
- [Colaboradores](#colaboradores)
- [Autores](#autores)

---

## Especificaciones técnicas

- **Nombre del juego:** Sugarbell
- **Género:** Cozy game / simulación.
- **Temática:** Pastelería y realización de encargos.
- **Plataforma:** Por definir.
- **Motor de desarrollo:** Godot.
- **Público objetivo:** Personas que disfrutan de juegos relajantes y creativos.

## Cómo se juega

En este relajante juego vas a ser la única pastelera de la ciudad de Lumi, tu tarea: preparar los pedidos mas dulces y ricos, logrando desbloquear más postres y recetas a medida que avances de niveles.


## Sinopsis

En la mágica ciudad de Lumi, una humana decide abrir la primera pastelería, un lugar completamente nuevo para sus habitantes fantásticos. A través de deliciosas preparaciones dulces, buscará conquistar los paladares de las distintas criaturas que viven en la ciudad.

A medida que los clientes visitan la pastelería y prueban nuevas delicias, la protagonista irá descubriendo recetas y ampliando su menú. Con cada nivel, tendrá la oportunidad de preparar más variedades de dulces y sorprender a los habitantes de Lumi, convirtiendo su pequeño negocio en un lugar cada vez más especial.

## Elementos del juego

- Cocina de la pasteleria.
- Encargos y pedidos.
- Productos de pastelería.
- Elementos decorativos.

## Niveles del juego

El nivel avanzara dependiendo de la cantidad de monedas que cada pedido deje, obteniendo cada vez nuevas recetas. 

<img width="1165" height="1350" alt="WhatsApp Image 2026-11-07 at 11 56 36 PM" src="https://github.com/user-attachments/assets/3ed7fdeb-d4ce-40ef-96fa-eda27a726eef" />


•NIVEL 1•

El nivel uno presenta órdenes de la primera receta, medialunas. Para poder pasar al nivel 2 se deberán conseguir 10 monedas.

•NIVEL 2•

El nivel dos desbloquea una receta nueva: palmeritas. 
Para avanzar al nivel 3 se deberán conseguir 50 monedas.

•NIVEL 3•

El nivel tres suma una nueva receta: cupcakes. 
Para avanzar al nivel 4 se deberán conseguir 100 monedas.

•NIVEL 4•

Junto con las recetas ya conocidas se suma una nueva: cookies.
Para avanzar al nivel 5 deberán conseguir 150 monedas.

•NIVEL 5•

Para este nivel se suma las primeras recetas que otorgan más de 10 monedas: los rolls de canela y los fresier.
Para ganar la demo de juego se deberán conseguir 500 monedas.


## Control del jugador

 En Sugarbell el jugador ocupará el rol de Mochi, la pastelería de la ciudad. El juego permite a los jugadores dirigir los utensilios e ingredientes con el mouse creando así la receta del postre encargado.

La misión de los jugadores es realizar los pedidos de los ciudadanos los cuales tienen recetas que cada vez requieran más paso.

## Por qué es divertido este juego

Sugarbell propone una experiencia relajante y creativa, combinando la temática de la pastelería con la satisfacción de completar pedidos y progresar dentro del juego. Es un juego sin presión, hecho para pasar el rato completando relajantes recetas.

## Características clave

- Ambientación acogedora.
- Tareas y encargos.
- Progresión del jugador.
- Experiencia relajante.
- Temática de pastelería.


## Guía de diseño

En Sugarbell adoptaremos la siguiente paleta de colores para mantener el ambiente acogedor y llamativo de la ciudad de Lumi. Con un distintivo estilo pixelart, buscamos ofrecer una experiencia visual acogedora y envolvente que acompañe el momento satisfactorio de un juego tranquilo.

<img width="679" height="432" alt="Captura de pantalla 2026-11-06 200004" src="https://github.com/user-attachments/assets/d9572b4b-eb7f-4e86-9015-164cb24a6140" />


La interfaz de usuario se mantendrá clásica, intuitiva y fácil de entender, mientras que las animacione de elementos mejorarán la inmersión del jugador en este mundo mágico.


## Definiciones de diseño del juego


## Transiciones entre niveles

Las transiciones permitirán pasar de una etapa a otra mediante el progreso del jugador y la finalización de los objetivos.

## Enfoque principal del juego

Ofrecer una experiencia cozy centrada en una pastelería, la realización de encargos y el progreso del jugador.

## Diagrama de flujo del juego

<img width="1212" height="1924" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/81539698-8ab5-4d0d-98ee-ba50c50041ed" />


## Definición de jugador

El jugador representa a la persona encargada de realizar las tareas y gestionar los pedidos dentro de la pastelería. 

Dirigido a cualquiera que quiera pasar una experiencia relajante y acogedora. Diseñado con inclusividad en mente, para atraer a jugadores de todos los géneros y garantizar una experiencia equitativa. Orientado a aquellos que dan sus primeros pasos en el mundo de los videojuegos o disfrutan de juegos tranquilos que no requieran concentración ni acción.

La dificultad se ajusta para ser accesible, asegurando que los jugadores disfruten del juego sin sentirse abrumados, promoviendo así una experiencia divertida y gratificante. 

## Propiedades del jugador

Mochi es la personaje de este mágico juego sin embargo su apariencia no se muestra para que así el jugador se imagine a su mismo siendo el que se encarga de la pastelería Sugarbell.

## Interfaz de usuario (UI)


La interfaz del juego en PC será diseñada para brindar una experiencia intuitiva y fluida. El cronómetro del horno marcará el tiempo exacto en que los postres se cocinan y la paciencia de los clientes no es un obstáculo en este tipo de juegos ya que no se tomará en cuenta. Los controles, configurados con el mouse el cual arrastrará todos los elementos visbles se adaptan de manera eficiente a la jugabilidad en PC. Mensajes como "¡Entregado!" y "Ganaste x cantidad de monedas" aparecerán al entregar el pedido de la misma forma en que el mismo se mostrará al inicio del nivel, proporcionando una retroalimentación clara al jugador. La interfaz será simple y efectiva, centrada en mejorar la experiencia de juego en la plataforma de PC.

<img width="1600" height="900" alt="WhatsApp Image 2026-11-07 at 11 55 04 PM" src="https://github.com/user-attachments/assets/00b19834-f405-463a-81ec-5b9a829b4593" />


## Enlaces de interés

Tomamos de referencia juegos como: 

•Buena Pizza, Gran Pizza

<img width="736" height="414" alt="Review_ Good Pizza, Great Pizza – A Surprisingly Addictive Cozy Management Sim _  PeaPodGirlGaming" src="https://github.com/user-attachments/assets/790f8f61-3d22-4603-a371-9c40df455bc6" />

Link: https://store.steampowered.com/app/770810/Buena_Pizza_Gran_Pizza_Simulador_de_cocina_acogedor/?l=latam

•Papa's Bakeria

<img width="640" height="480" alt="images" src="https://github.com/user-attachments/assets/25c21b70-5a30-49af-ad68-c3b280bc60dd" />

Link: https://www.crazygames.com/es/game/papas-bakeria

•Cocina con Sarah

<img width="736" height="579" alt="descarga - 2026-11-06T200520 143" src="https://github.com/user-attachments/assets/71cb1173-60fc-4945-b7af-0d4a17121451" />

Link: https://www.juegosdechicas.com/juegos/juegos_de_cocina_con_sara
## Colaboradores



## Autores

Páez Tello María Luz
Gordillo Guadalupe
Tejerina Carolina
