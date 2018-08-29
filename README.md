# Curso de diseño html y css para Emails

El email no funciona como pagina web
y la web no funciona como email.

Para ver los emails mas utilizados podemos ver
[Email Client Market Share](https://emailclientmarketshare.com/)

## Formatos de Imagen

*Gif*: Graphics Interchange Format (
formato de gráficos intercambeable)

*JPEG*: Joint Photographic Experts Group (Grupo Conjunto de Expertos en Fotografía)

*PNG*: Portable Network Graphics(Gráficos de Red Portátiles)

Aplica la propiedad `srcset` para dispositivos retina.

## Reglas de css para mail

Podemos visitar la siguiente página:
[Campaign Monitor](https://www.campaignmonitor.com/css/)


## Media Queries

Tenemos que tener muy en cuenta el tamaño,
de los dispositivos.

- Smarth Phone: <= 320px

- Smarth Phone Plus: <= 480px

- Tablets, Ipad: <= 600px

El elemento `table` no tiene la propiedad `height`.


## Técnica de Stacking

Posición de elementos en forma vertical. Es una técnica para un
`apilamiento de enfoque` y también afecta el orden - En este caso
hay dos tablas, como contenedores y a ambas se aplica la clase
`blockwrap`. Si se desea cambiar el orden, hay una clase declarada
en Styles: `movedown` y `moveup` respectivamente. Esas clases deben
incluirse en `inline style` junto a `blockwrap`. 
El resultado: cambia la posición; es decir, el `Module right` aparecerá
sobre el `Module left`.
La técnica de Stacking proporcionan mayor libertad y control en el diseño.


## Proyecto

### header: 
elementos de : brand , pre header podemos poner una linea de texto de invitacion al usuario para que abra el email, link para la version online.
tambien se puede incluir una parte mas definida con un CTA.

### Hero:
por lo general se tiene una grafica y un headline llamativo

### body:
contiene un detalle pequeño de lo que hace la app.

### recovery: 
se puede repetir cierto tipo de mensaje o CTA que se mostro al principio.
tambien se incluye los link social media.
tambien se puede tener otro CTA pero no como boton sino como pregunta

### footer: 
lo mas importante es la información sobre tu empresa y un botón para darse de baja fácilmente.

### CTA : 
Call To Action, botón o enlace que deseamos que nuestro usuario tenga una interacción.