# Mercado Diario

Portfolio público de **Jorge Sánchez Cava** — analista de datos, mercados
eléctricos europeos.

**→ [jorgescava-maker.github.io/mercado-diario](https://jorgescava-maker.github.io/mercado-diario/)**

Presenta los resultados y el método de un proyecto personal: modelos propios de
predicción del precio horario del mercado diario (*day-ahead*) para España,
Alemania, Francia y Países Bajos, más dieciséis estudios de mercado construidos
sobre la misma base de datos.

| Mercado | MAE del modelo | MAE de repetir el precio de ayer | Mejora |
|---|---|---|---|
| España | 9,83 EUR/MWh | 17,95 | 45,2 % |
| Alemania | 14,22 | 27,61 | 48,5 % |
| Francia | 15,93 | 24,05 | 33,8 % |
| Países Bajos | 16,36 | 26,06 | 37,2 % |

Medido con validación *walk-forward* mensual sobre unas 36.000 horas por mercado
que el modelo nunca vio al entrenarse, usando únicamente información disponible
antes del cierre de la subasta.

## Qué hay en este repositorio

Solo la página: `index.html`, un documento autocontenido sin dependencias más
allá de las tipografías de Google Fonts.

**El código del proyecto, las variables construidas y los modelos entrenados no
se publican.** Este repositorio existe para alojar la página, no para distribuir
el trabajo que hay detrás.

## Contacto

jorge.s.cava@gmail.com

---

© 2026 Jorge Sánchez Cava. Contenido y resultados de elaboración propia.
