# Proyecto: Plataforma de Alquimia — Trabajo Final

Contenido:
- backend/  (Go 1.21, Gorilla Mux, GORM, JWT, Redis worker)
- frontend/ (React + Vite + TypeScript)
- db/       (init SQL + sample data)
- docker-compose.yml
- README con instrucciones básicas.

**Requisitos en tu máquina**: Docker y Docker Compose (los servicios se levantarán en contenedores).
Comandos principales:

1. Descomprime el zip.
2. Desde la raíz del proyecto ejecuta:
   ```bash
   docker compose up --build
   ```
3. El frontend estará en http://localhost:3000
   El backend en http://localhost:8080
4. Para inicializar datos de ejemplo la API hará auto-seed al arrancar.

