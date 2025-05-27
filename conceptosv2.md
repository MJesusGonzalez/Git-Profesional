# Uso de commits
- Cada vez que se crea una pieza o cambio sobre el código.
# Mensajes
- Titulo con menos de 50 caracteres
- Utiliza verbos imperativos (fix, add, delete, update)
- Linea en blanco entre titulo y descripción
- Enfoque en qué y por qué
- Convenciones definidas por el equipo

# Uso de ramas
Cada que se realice un cambio en el código
- agregar, arreglar, eliminar, modificar

# Merge de ramas
- Unificar ramas

## Tipos de Merge
| Tipo | Concepto |
|----------|----------|
| Fast Forward merge | prederterminado: la rama con cambios tiene actualizada la última version de origen |
| Merge Commit | Contiene los cambios que tiene ese merge |
| squash merge | tiene todos los cambios a implementar|

# Stash
Interpretación como una cuarta área (un caché), donde se guardan los cambios sin un commit y sin afectar al área de trabajo.
- Permite guardar cambios en caso de necesitar realizar otra actividad de urg.
- Luego volver a sacar los cambios para el área de trabajo y continuar
- NO incluye archivos nuevo o creados
    - Se debe especificar

# Ignorar archivos
- Info como .env, compilados, librerias
- se crea el .gitignore