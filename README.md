# Productos Service — Analisis SonarQube

## Estado inicial del analisis
| Categoria | Cantidad | Rating |
|-----------|----------|--------|
| Bugs | X | ? |
| Vulnerabilidades | X | ? |
| Code Smells | X | ? |
| Cobertura | X% | — |

## Hallazgos principales identificados
### Bug 1: [nombre del bug]
- Archivo: ProductoService.java, linea X
- Descripcion: [descripcion del problema]
- Severidad: [Critical/Major/Minor]

### Code Smell 1: [nombre]
- Archivo: ProductoService.java, linea X
- Descripcion: [descripcion]

### Code Smell 2: [nombre]
- Archivo: Producto.java, linea X
- Descripcion: [descripcion]

## Capturas del dashboard
![Dashboard SonarQube](img/sonar-dashboard.png)
![Detalle Bugs](img/sonar-bugs.png)

## Ejecucion del analisis
1. Levantar SonarQube en Docker.
2. Ejecutar `mvn clean verify`.
3. Ejecutar `mvn sonar:sonar -Dsonar.token=TU_TOKEN`.

## Notas
- Las capturas se guardan en la carpeta img/.
