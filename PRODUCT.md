# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users
Una sola persona: Rafael, artista 3D de personajes y entornos para videojuegos (Madrid), en plena búsqueda de empleo. No es programador. Lo usa sobre todo en el PC, normalmente por la mañana para revisar las ofertas nuevas; el móvil es secundario pero debe funcionar. Nadie más ve el panel.

## Product Purpose
Panel personal para gestionar la búsqueda de empleo en la industria del videojuego con el mínimo esfuerzo. Éxito = revisar las ofertas del día en pocos minutos, no perder ninguna candidatura y saber siempre qué toca hacer.

## Positioning
Hecho a medida de un perfil concreto (Character / Environment / 3D Artist): una búsqueda diaria automática con Claude deja las ofertas ya puntuadas contra su perfil, y él solo decide (me interesa / ya aplicada / descartar).

## Operating Context
- Una tarea programada de Claude busca ofertas cada mañana y las deja en `ofertas-nuevas.json` en un repositorio privado de GitHub; el panel las importa solo al abrirse.
- Los datos viven en localStorage y se sincronizan con ese repositorio de GitHub (GitHub Pages para abrirlo desde cualquier dispositivo).
- Flujo: Inicio (ofertas de los últimos 3 días sin decidir) → Radar de ofertas (todas, con filtros y orden) → Candidaturas (estados: Preparando, Sin respuesta, Respondida, Entrevista, Prueba técnica, Oferta, Rechazada) → Mi perfil → Agente IA (reglas, generador de prompt, conexión GitHub).

## Capabilities and Constraints
- Un único `index.html` sin dependencias ni frameworks (HTML + CSS + JS), comentado y sencillo.
- Interfaz y textos en español. Modo claro y oscuro obligatorios. Debe verse bien en móvil.
- Las funciones de IA solo funcionan dentro de Claude por ahora; fuera deben fallar con un mensaje amable (fase 2: servidor propio con la API de Anthropic).
- Nunca mostrar ni subir claves; el token de GitHub vive solo en el navegador.
- Pendiente: avisos de respuestas por correo en Inicio (marcado como "próximamente").

## Brand Commitments
Ninguna marca previa. Rafael eligió una dirección visual inspirada en Raycast (ver `prototipo-estilos.html`, estilo "Raycast").

## Evidence on Hand
Datos reales del usuario en `Datos.json` (perfil y candidaturas). No hay testimonios ni contenido de terceros; no inventar ofertas ni experiencia.

## Product Principles
1. Ahorrar trabajo por encima de todo: cada pantalla debe acortar el camino hasta una decisión.
2. Lo nuevo y pendiente, primero; lo antiguo se aparta solo sin perderse.
3. Nada se borra sin poder deshacerlo o sin que quede registro.
4. Claridad para alguien que no programa: textos sencillos, sin jerga.
