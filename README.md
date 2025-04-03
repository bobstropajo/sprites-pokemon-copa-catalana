# sprites-pokemon-copa-catalana
Repositorio para almacenar los sprites custom de la Copa Catalana a fin de reemplazarlos en Pokemon Showdown mediante un script.

### Usar el script
Puedes habilitar el script en tu navegador usando la extensión de Violentmonkey o similares (Tampermonkey, Greasemonkey, etc). 

El script se ha testeado con Violentmonkey en Firefox pero debería de funcionar correctamente al usar Chrome u otros navegadores siempre que JS esté habilitado.

Desde la extensión de tu elección, crea un nuevo script y pega el contenido de *script_reemplazar_sprites.txt*. Recuerda recargar la página (preferiblemente limpiando la caché con Control + Shift + R). 

**Importante:** Por el momento solo se reemplazan los sprites 3D animados, por lo que tienes que asegurarte de no estar usando las opciones *'Disable animations'* o *'Use 2D sprites instead of 3D models'*. 

Actualmente el script solo se aplica a los sprites de los pokemons durante las batallas, por lo que el cambio no será visible desde el Teambuilder.

### Añadir imágenes
Las imágenes han de ser 96x96, preferiblemente con fondo transparente. El nombre de la imagen ha de ser \<nombre del pokemon en minusculas\>.gif. 

Para mantener la estructura de archivos que usa el Pokemon Showdown, cada imagen se tiene que añadir a */sprites/ani*, */sprites/ani-back*, */sprites/ani-shiny* y */sprites/ani-back-shiny*. En caso de querer dos sprites personalizados para el mismo pokemon, se puede añadir una imagen distinta para el shiny.
