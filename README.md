# Sistema de Gestión de E-commerce (CLI en Go)

Proyecto desarrollado bajo el paradigma de **programación funcional** en Go (Unidad 1).

## Estructura del Proyecto
- `cmd/main.go`: Punto de entrada y navegación por consola.
- `internal/catalogo`: Gestión de productos e inventario inmutable.
- `internal/carrito`: Reglas de negocio, cupones de descuento e impuestos.
- `internal/ordenes`: Consolidación de compras (checkout) e historial.

## Dependencias
- Librería estándar de Go (`fmt`, `strings`, `strconv`, `time`, `errors`)
- `github.com/google/uuid`: Generación de identificadores únicos sin estado global mutable.
