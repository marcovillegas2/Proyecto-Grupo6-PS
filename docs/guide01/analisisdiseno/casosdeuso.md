
%# Diagrama de casos de uso 

actor Usuario
actor Administrador

Usuario --> (Registrarse con verificación de identidad institucional)
Usuario --> (Subir y descargar materiales académicos)
Usuario --> (Administrar biblioteca personal)
Usuario --> (Vista previa de materiales)
Usuario --> (Búsqueda avanzada con filtros)
Usuario --> (Recomendaciones automáticas)
Usuario --> (Ver testimonios y recomendaciones de egresados)
Usuario --> (Reseñar y calificar materiales y docentes)
Usuario --> (Participar en dinámicas de juego (insignias y ranking))

Administrador --> (Moderación de contenido)

(Registrarse con verificación de identidad institucional) ..> (Subir y descargar materiales académicos) : <<include>>
(Registrarse con verificación de identidad institucional) ..> (Búsqueda avanzada con filtros) : <<include>>
(Registrarse con verificación de identidad institucional) ..> (Reseñar y calificar materiales y docentes) : <<include>>
(Registrarse con verificación de identidad institucional) ..> (Participar en dinámicas de juego (insignias y ranking)) : <<include>>
(Búsqueda avanzada con filtros) ..> (Recomendaciones automáticas) : <<extend>>
