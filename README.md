# Proyecto Sistemas recomendadores 2024-2
**Integrantes:** Gustavo Cornejo, Juanita Fernández, Francisco Jorquera.

# Sistema Recomendador para Juegos de Cartas Coleccionables (Hearthstone)

Este proyecto presenta un sistema recomendador diseñado para juegos de cartas coleccionables, con un enfoque particular en **Hearthstone**. El objetivo principal es optimizar los mazos de los jugadores, mejorando su **win-rate** a través de algoritmos de recomendación.

## Más Información

Para obtener una descripción detallada del sistema y los resultados obtenidos, consulta el documento [**Nombre del Paper**].

## Descargar el Código

Puedes descargar el código fuente y los archivos necesarios para replicar el sistema desde el archivo .zip disponible [aquí](./Proyecto_Final.zip).

## Modelos y Archivos Importantes

- El modelo utilizado para predecir el **win_rate** fue entrenado usando el archivo [**win_rate_prediction**](./Entrega%203/win_rate_prediction.ipynb).
- El código necesario para replicar los resultados y entrenar el modelo se encuentra en [**DeckRec**](./Entrega%203/DeckRec.ipynb).

### Documentación:
**[1] Looking for archetypes: Applying game data mining to hearthstone decks**: Análisis de los datos en la bases de datos de **[2]** 
Doi: https://doi.org/10.1016/j.entcom.2022.100498

**[2] History of Hearthstone**: Bases de datos con masos de cartas de Hearthstone con descripciones de y puntuaciones obtenidas de https://www.hearthpwn.com/. (archive.zip)
https://www.kaggle.com/datasets/romainvincent/history-of-hearthstone

**[3] Q-DeckRec: A Fast Deck Recommendation System
for Collectible Card Games**: Sistema recomendador para hearthstone que usa Reinforced learning para modificar masos propuestos por el usuario.
Doi: 10.1109/CIG.2018.8490446
