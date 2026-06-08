# 🏎️ Viaje a la F1 — GP de São Paulo 2026 (Interlagos)

Viaje en auto con amigos para ver el **Gran Premio de São Paulo de Fórmula 1 2026**
en el Autódromo José Carlos Pace (Interlagos), del **viernes 6 al domingo 8 de
noviembre de 2026**.

> Ronda 20 del calendario 2026 — "Formula 1 MSC Cruises Grande Prêmio de São
> Paulo 2026", Interlagos, ~25 km al sur del centro de São Paulo.
> Fuente: [formula1.com/en/racing/2026](https://www.formula1.com/en/racing/2026),
> [brasilf1.com](https://www.brasilf1.com/en/f1-sao-paulo)

## El grupo y el vehículo

- **6 amigos**, turnándose para manejar y llegar lo más directo posible (sin
  paradas para dormir — solo combustible, comida y descanso corto):
  Ariel B, Ariel S, Charly, Elias, Dani y Gaston.
- **Vehículo:** Chevrolet Trailblazer 2020, 7 asientos, diésel.
- **Autonomía estimada:** ~600 km por tanque.
- **Punto de partida:** Juan María Gutiérrez, Berazategui, Buenos Aires,
  Argentina.
- **Combustible:** cargar siempre en estaciones **Shell** (ver plan de
  paradas más abajo).

## Estructura de esta carpeta

```
formulauno/
├── README.md          # este archivo — itinerario completo
├── index.html         # página web del viaje — desplegada en Vercel
├── sw.js              # service worker — cachea la página para uso 100% offline
└── vercel.json        # config de Vercel (cleanUrls)
```

> 🌐 Sitio publicado en **[formulauno-phi.vercel.app](https://formulauno-phi.vercel.app/)**
> (deploy automático desde [github.com/DasLatam/formulauno](https://github.com/DasLatam/formulauno) — cada push a `main` redespliega).

> 📴 **Funciona sin internet:** la página registra un *service worker* (`sw.js`) que
> guarda todo en el teléfono la primera vez que se abre. Después de esa primera visita
> (con conexión), el mapa de la ruta, el cronograma, las paradas de combustible y toda
> la info de la página quedan disponibles aunque no haya señal — ideal para el tramo
> sin cobertura entre Argentina y Brasil. El botón **«¿Dónde estoy?»** usa el GPS del
> teléfono (que tampoco necesita datos móviles) para ubicarte en el mapa y mostrar tu
> próxima parada.

---

## 1. Ruta — la más directa posible

**Distancia total estimada:** ~2.190 km · **Tiempo de manejo puro:** ~24-25 h
(sin contar paradas). Con paradas de combustible, comida, descanso y el cruce
de frontera, calculá realísticamente **~28-30 h totales** puerta a puerta.

### Tramos

| Tramo | Vía | Distancia aprox. | Tiempo aprox. |
|---|---|---:|---:|
| Berazategui → Zárate (acceso a RN14) | Av. Bs As–La Plata / RN9 / RN12 | ~110 km | ~1h30 |
| Zárate → Paso de los Libres (Corrientes) | **RN14** (Ruta del Mercosur) — Entre Ríos y Corrientes | ~870 km | ~9h30 |
| **Cruce de frontera** Paso de los Libres ↔ Uruguaiana | Puente Internacional "Agustín P. Justo – Getúlio Vargas" | ~8 km | ~20min + trámite aduana |
| Uruguaiana → Porto Alegre (RS, Brasil) | **BR-290** | ~630 km | ~7h |
| Porto Alegre → Curitiba (PR) | **BR-116** | ~710 km | ~8h |
| Curitiba → Interlagos (São Paulo) | **BR-116** (Rodovia Régis Bittencourt) → acceso SP | ~410 km | ~4h30 |

> ⚠️ Una alternativa más corta entre Uruguaiana y Porto Alegre sería la
> BR-285 vía São Borja, pero al momento de esta investigación tenía tramos
> con el asfalto levantado — **conviene re-chequear el estado antes de
> salir** y, si sigue mal, mantenerse en BR-290.

### Resumen del recorrido
**Berazategui → RN14 (Entre Ríos / Corrientes) → Paso de los Libres →
[frontera] → Uruguaiana → BR-290 → Porto Alegre → BR-116 → Curitiba →
BR-116 / Rodovia Régis Bittencourt → São Paulo → Interlagos**

Esta es la combinación de rutas más directa por asfalto entre Buenos Aires
y San Pablo: RN14 es la "ruta del Mercosur" hacia el cruce de Paso de los
Libres, y la BR-116 conecta de punta a punta el sur de Brasil con San Pablo.

Sources:
- [Distancia y tiempo Buenos Aires – São Paulo (Himmera)](https://es.distancias.himmera.com/distancia_de-buenos_aires_a_estado_de_sao_paulo_entre_mapa_carretera-36536.html)
- [Ruta Buenos Aires – São Paulo en auto (Ruta0)](https://www.ruta0.com/ruta/internacional/buenos-aires-a-sao-paulo/)
- [Paso de frontera Paso de los Libres – Uruguayana (Argentina.gob.ar)](https://www.argentina.gob.ar/seguridad/pasosinternacionales/detalle/ruta/73/Paso-de-los-Libres-Uruguayana)
- [Estado de la BR-285 / BR-290 hacia Brasil (El Litoral)](https://www.ellitoral.com/informacion-general/auto-brasil-sur-playas-turismo-argentinos-puente-paso-libres-uruguaiana-frontera-ruta-br290-estado-roto-peligro_0_9TjTzKfgly.html)

---

## 2. Plan de carga de combustible — solo Shell ⛽

Con ~600 km de autonomía, conviene cargar **cada ~450-500 km** (margen de
seguridad de ~100 km, evitando llegar al límite en zonas sin estaciones).
Esto da aproximadamente **5 paradas de carga** en todo el viaje.

| # | Km aprox. acumulados | Zona | Estación Shell sugerida | Notas |
|---|---:|---|---|---|
| 1 | ~480 km | Entre Ríos (RN14) | Shell **Chajarí** o **San José** (RN14) | Aprovechar para comer algo |
| 2 | ~950 km | Corrientes — antes del cruce | Shell **Santo Tomé** (RN14, ~70 km antes de Paso de los Libres) | Cargar acá antes de cruzar — el combustible suele ser más barato en Argentina |
| 3 | ~1.430 km | Brasil — Río Grande do Sul (BR-290) | A confirmar — ver localizador Shell Brasil | 🔍 Verificar cerca de la fecha (ver nota abajo) |
| 4 | ~1.900 km | San Pablo — Rodovia Régis Bittencourt (BR-116) | Shell **Fase Quattro – Juquiá** (km 413,8 — tiene diésel y Arla 32) o **Posto Presidente Shell – Pariquera-Açu** | Zona de Registro/Juquiá es el "hub" de servicios de la ruta |
| 5 | ~2.180 km (final) | Llegando a San Pablo | Shell **Posto Rota 116 – Taboão da Serra** (BR-116, km 16,5) | Última carga antes de Interlagos — dejar el tanque lleno para moverse en la ciudad |

> 🔍 **Pendiente de verificar más cerca de la fecha:** no encontré estaciones
> Shell confirmadas sobre la BR-290 entre Uruguaiana y Porto Alegre, ni en el
> tramo Porto Alegre–Curitiba de la BR-116. Recomendamos usar el localizador
> oficial de Shell antes de salir y cargar la app:
> - 🇦🇷 [Localizador de estaciones Shell Argentina](https://www.shell.com.ar/empresas/shell-flota/station-locator.html)
> - 🇧🇷 Shell Brasil — buscar "encontre um posto" en shell.com.br
>
> Con la autonomía real (~600 km) hay margen de sobra para resolver sobre la
> marcha si una estación puntual no aparece exactamente donde se planeó —
> la idea es no bajar de ~150-200 km de reserva en ningún tramo.

Sources:
- [Estaciones Shell en Ruta Nacional 14 — Entre Ríos y Corrientes](https://rutaserviciosargentina.online/estaciones-de-servicio-shell-ypf-y-axion-en-la-ruta-14-en-argentina-guia-rapida-para-viajeros/)
- [Posto Shell Fase Quattro – Juquiá, BR-116 km 413,8 (diésel + Arla 32)](https://www.planetabrasileiro.com/shell-posto-fase-quattro-juquia-sp-F100BC4001AD4)
- [Posto Presidente Shell – Pariquera-Açu, BR-116](https://www.planetabrasileiro.com/posto-presidente-shell-rodovia-br-116-regis-bittencourt-pariquera-acu-sp-F1709C0031ED1)
- [Posto Rota 116 (Shell) – Taboão da Serra, BR-116 km 16,5](https://www.gasoradar.com.br/posto-de-gasolina/15500)

---

## 3. Cronograma sugerido

El GP es viernes 6 a domingo 8/11. Para llegar con margen y descansar antes
de la primera práctica libre del viernes, conviene salir el **miércoles 4 de
noviembre** bien temprano:

| Momento | Evento |
|---|---|
| **Mié 4/11, ~05:00** | Salida desde Juan María Gutiérrez, Berazategui |
| Mié 4/11, durante el día | RN14 a través de Entre Ríos y Corrientes — parada 1 de combustible/comida |
| Mié 4/11, tarde-noche | Llegada a Paso de los Libres — parada 2 (cargar antes de cruzar) — **cruce de frontera** |
| Mié 4/11 noche → Jue 5/11 | BR-290 hacia Porto Alegre — turnos de manejo nocturnos |
| Jue 5/11, mañana/mediodía | Porto Alegre → Curitiba (BR-116) — parada 3 |
| Jue 5/11, tarde | Curitiba → San Pablo (Régis Bittencourt) — parada 4 |
| **Jue 5/11, noche / Vie 6/11 madrugada** | Llegada estimada a San Pablo / Interlagos — parada 5 y descanso |
| **Vie 6/11 – Dom 8/11** | 🏁 GP de São Paulo 2026 en Interlagos |

Esto deja **todo el día jueves de colchón** para imprevistos (demoras en la
frontera, tráfico, descanso real antes de entrar al circuito el viernes).

## 4. Turnos de manejo (6 personas)

Con 6 conductores y ~25 h de manejo puro, la idea es turnos de **~3 horas**
cada uno, dando ~2 vueltas completas por persona y dejando a cada uno
suficiente descanso entre turnos:

- Definir el orden de los turnos antes de salir (sorteo o por preferencia).
- El que no maneja navega/controla combustible y el que sigue debería
  intentar dormir, no quedarse de "compañía" todo el viaje.
- Relevos ideales: en las paradas de combustible (cada ~450-500 km / ~4-5 h),
  así se aprovecha la parada para el cambio sin perder tiempo extra.

## 5. Documentación para cruzar la frontera (Paso de los Libres → Uruguaiana)

Llevar **original y en papel** (las versiones digitales no se aceptan):

- [ ] DNI o pasaporte vigente de cada uno de los 6 viajeros
- [ ] Licencia de conducir habilitada para la categoría del vehículo (de
      cada uno de los que vaya a manejar)
- [ ] Título de propiedad del vehículo (cédula verde / azul)
- [ ] Si el auto no es de quien maneja: autorización correspondiente
- [ ] **Seguro Carta Verde (Mercosur)** vigente — obligatorio para circular
      por Brasil
- [ ] VTV vigente
- [ ] Patentes delantera y trasera en buen estado
- [ ] Hacer la **premigración con código QR** antes de llegar al paso, para
      agilizar el trámite migratorio

Sources:
- [Documentación para viajar a Brasil en auto 2026 (LA NACION)](https://www.lanacion.com.ar/sociedad/ruta-a-brasil-en-auto-que-documentacion-necesito-para-ir-desde-la-argentina-nid02012026/)
- [Requisitos de cruce de frontera Argentina-Brasil (Cardinal Assistance)](https://www.cardinalassistance.com/tips/requisitos-para-cruzar-la-frontera-entre-argentina-y-brasil-en-coche-este-verano/)
- [Información de trámites en frontera (Argentina.gob.ar)](https://www.argentina.gob.ar/interior/asuntos-tecnicos-de-fronteras/informacion-tramites-en-frontera)

## 6. Checklist de preparación

- [ ] Service y chequeo general de la Trailblazer (frenos, neumáticos —
      incluida auxilio, niveles, batería) — un viaje de 2.200 km no perdona
- [ ] Confirmar entradas al GP (prácticas / clasificación / carrera)
- [ ] Reservar alojamiento en San Pablo para las noches del 5, 6, 7 y 8
- [ ] Carta Verde (seguro Mercosur) — sacarla con anticipación
- [ ] Premigración con QR
- [ ] Cambiar/llevar reales (BRL) para peajes y combustible en Brasil
- [ ] Descargar offline los mapas de la ruta (Google Maps / Maps.me)
- [ ] Power banks, cargadores de auto, playlists/podcasts para los turnos
      nocturnos
- [ ] Botiquín, agua y snacks para los tramos largos sin estaciones

---

*Última actualización: 2026-06-08 — este documento es la base del viaje;
ajustar fechas/paradas más cerca de noviembre con info actualizada
(estado de rutas, estaciones Shell sobre BR-290/BR-116 en Brasil, horarios
oficiales del GP).*
