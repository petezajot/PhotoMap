# PhotoMap
Permite a los usuarios tomar fotos, añadirles una breve descripción y colocarlas sobre un mapa en su ubicación actual (o personalizada). Otros pueden explorar el mapa y descubrir imágenes de distintos lugares.

# Funcionalidades principales:
- Mapa interactivo (MapKit + SwiftUI): Mostrar pines con imágenes. Al tocar un pin, aparece un "sheet" con la foto, descripción, autor y fecha.
- Captura y carga de fotos: Usar la cámara o galería del dispositivo para añadir imágenes.
- Geolocalización: Detectar la ubicación actual con "CLLocationManager", o permitir al usuario seleccionar manualmente una ubicación.
- Almacenamiento en la nube(Firebase storage): Guardar imágenes de forma eficiente.
- Base de datos (Firestore): Guardar metadatos de cada foto: ubicación, descripción, autor, fecha, URL de imágen etc.
- Inicio de sesión (Firebase Auth): Autenticación simple por correo o con Apple/Google para llevar control de usuarios.
- Realm: Guardar imágenes favoritas o vistas recientemente para poder verlas offline.
- Push notifications (Cloud messaging)*: Opcional. Por ejemplo, cuando alguien sube una nueva foto cerca de tu ubicación.

Desarrollado utilizando:
- SwiftUI
- MapKit
- Firebase
- Realm
- URLSession
- MVVM

Agregar más adelante:
- Filtros por categoría
- Likes o comentarios.
- Modo privado: Solo tu puedes ver tus fotos
- Compartir enlaces a pines específicos.
