# Pokedex

Este es un proyecto de Pokedex simple que te permite buscar y ver información sobre Pokémon. Utiliza la API de PokeAPI para obtener los datos de los Pokémon.

## Características

- Buscar Pokémon por nombre.
- Mostrar detalles de un Pokémon, como su nombre, imagen, altura y peso.
- Borrar la información del Pokémon.

## Capturas de pantalla

![Captura de pantalla 1](screenshot1.png)
![Captura de pantalla 2](screenshot2.png)

## Uso

1. Clona este repositorio en tu máquina local.
2. Abre `index.html` en tu navegador.
3. Escribe el nombre de un Pokémon en el campo de búsqueda y haz clic en "Buscar".
4. Se mostrarán los detalles del Pokémon si se encuentra en la base de datos.

## Tecnologías utilizadas

- HTML
- CSS (incluyendo Bootstrap)
- JavaScript

## Consumiendo la API

Para obtener los datos de los Pokémon, este proyecto utiliza la [PokeAPI](https://pokeapi.co/), una API pública que proporciona información detallada sobre todas las especies de Pokémon.

### Funcionalidades de la API

- **Búsqueda por nombre:** La API permite realizar consultas de Pokémon mediante su nombre. Esto se integra en la funcionalidad de búsqueda del proyecto.
- **Detalles de un Pokémon:** Al realizar una solicitud con el nombre del Pokémon, se obtienen datos como el nombre, imagen, altura, peso y más detalles relacionados.
- **Borrado de información:** La API también permite el borrado de la información de un Pokémon específico, lo cual se refleja en la opción del proyecto.

### Endpoints Utilizados

- `/pokemon/{id o nombre}`: Proporciona detalles de un Pokémon específico según su nombre o ID.
- Otros endpoints adicionales se utilizan para recopilar información detallada y específica de cada Pokémon.

### Integración en el Proyecto

El código JavaScript del proyecto realiza solicitudes HTTP utilizando fetch para interactuar con la API PokeAPI. Estas solicitudes se enfocan en obtener y mostrar los detalles de los Pokémon en el navegador.

## Contribuciones

¡Siéntete libre de contribuir a este proyecto! Puedes abrir problemas, enviar solicitudes de extracción o sugerir mejoras. Estamos abiertos a colaboración.

## Próximos Pasos

- Mejorar la experiencia del usuario al mostrar más detalles sobre los Pokémon, como movimientos, habilidades, etc.
- Implementar funcionalidades de filtrado y ordenación para facilitar la búsqueda de Pokémon.
- Añadir soporte para la carga de imágenes de otros juegos de la franquicia Pokémon.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

Este proyecto fue creado por Gabriel Arturo Felix Paez. Puedes contactarme en gabriel_arturo01@hotmail.com.
