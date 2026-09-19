# GenKeep

**Connecting generations, saving lives.**

GenKeep is a mobile application designed to bridge the gap between elderly people and their immediate community during emergencies. It ensures that senior citizens can alert nearby caregivers in seconds.

## En
### Architecture: MVVM
The project follows the **MVVM (Model-View-ViewModel)** pattern to ensure a clean separation of concerns:
- **Model:** Defines the data structures for users, alerts, and locations.
- **View:** Declarative UI built with **SwiftUI**, focusing on high accessibility (oversized elements, high contrast).
- **ViewModel:** Handles the business logic and mediates between Firebase and the UI, ensuring the views remain lean and reactive.
- **Service Layer:** Encapsulates Firebase Firestore and Auth logic to provide a clean API for the ViewModels.

## Es
**Conectando generaciones, salvando vidas.**
GenKeep es una aplicación móvil diseñada para cerrar la brecha entre las personas mayores y su comunidad inmediata durante emergencias, asegurando que puedan alertar a cuidadores cercanos en segundos.

### Arquitectura: MVVM
El proyecto sigue el patrón **MVVM (Model-View-ViewModel)** para garantizar una separación clara de responsabilidades:
- **Modelo:** Define las estructuras de datos para usuarios, alertas y ubicaciones.
- **Vista:** UI declarativa construida con **SwiftUI**, enfocada en accesibilidad (elementos sobredimensionados y alto contraste).
- **ViewModel:** Maneja la lógica de negocio y actúa como mediador entre Firebase y la UI.
- **Capa de Servicio:** Encapsula la lógica de Firebase Firestore y Auth para proporcionar una API limpia a los ViewModels.
