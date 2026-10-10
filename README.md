# test-manager-library-3413974-page — Sitio Público de Presentación

Sitio público estático de presentación para la feria del proyecto **Manager Library** (Ficha ADSO 3413974 — T-23).

## Características

- **Independiente de la API:** Funciona en modo puramente estático sin dependencias de backend ni base de datos.
- **Diseño Responsive:** Totalmente adaptado para dispositivos móviles, tablets y monitores de escritorio.
- **Exposición Técnica:** Explica el alcance, historias de usuario, invariantes de negocio (RN-1 a RN-6), arquitectura hexagonal y resultados del enfoque *Spec-Driven Development* (SDD).

## Cómo Visualizar

### Opción 1: Apertura directa
Abra directamente el archivo `index.html` en cualquier navegador web moderno.

### Opción 2: Con servidor web local / Docker
```bash
# Con Python
python -m http.server 8080

# Con contenedor Nginx
docker run --rm -p 8080:80 -v "${PWD}:/usr/share/nginx/html:ro" nginx:alpine
```
Acceda en su navegador a `http://localhost:8080`.
