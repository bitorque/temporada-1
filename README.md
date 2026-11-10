<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/bitorque-logo-horizontal.png">
    <img alt="Bitorque" src="assets/bitorque-logo-horizontal-claro.png" width="440">
  </picture>
</p>

<p align="center"><code>de cero a robot</code></p>

# Temporada 1 · Un brazo robótico desde cero

Soy programador y no sé nada de electrónica. En esta temporada construyo en público, desde cero, un brazo robótico que:

- se mueve con servos,
- se controla por wifi desde una app Android propia,
- es seguro: le hago una auditoría de seguridad y lo blindo,
- y ve con una cámara e IA para coger objetos.

Aquí va el código de cada episodio. Los videos salen cada dos martes en [YouTube](https://www.youtube.com/@bitorque).

## Episodios

| # | Episodio | Código |
|---|---|---|
| 0 | Soy programador y no sé nada de electrónica | — |
| 1 | Encender un LED sin quemarlo | Próximamente |
| 2 | Sensores: leer el mundo | Próximamente |
| 3 | Motores y servos | Próximamente |
| 4 | La primera articulación | Próximamente |
| 5 | Montar el brazo (1/2) | Próximamente |
| 6 | Montar el brazo (2/2) | Próximamente |
| 7 | Cómo sabe el brazo dónde está su mano | Próximamente |
| 8 | Controlarlo por wifi | Próximamente |
| 9 | Audito la seguridad de mi propio robot | Próximamente |
| 10 | Lo blindo | Próximamente |
| 11 | Le doy ojos | Próximamente |
| 12 | Final: el robot hace una tarea él solo | Próximamente |

Cada episodio tendrá su carpeta (`ep01-led/`, `ep02-sensores/`…) con el código y un README que explica qué hace.

## Material

ESP32 · protoboard, LEDs, resistencias y sensores básicos · servos SG90 y MG996R · controlador de servos PCA9685 · fuente de 5 V aparte para los servos · multímetro · kit de brazo de 4–6 ejes · webcam USB.

## Seguridad

- Los servos se alimentan con una fuente aparte, nunca desde el USB del ordenador, con la tierra (GND) común.
- Todo lo de ciberseguridad se hace solo sobre mi propio robot y en mi propia red.

## ¿Sabes más que yo?

Seguro que sí. Abre un *issue* o déjalo en los comentarios del video: aquí aprendemos juntos.

[YouTube](https://www.youtube.com/@bitorque) · [TikTok](https://www.tiktok.com/@bitorque) · [Instagram](https://www.instagram.com/bitorquelab/) · [Twitch](https://www.twitch.tv/bitorque)

## Licencia

[MIT](LICENSE): usa el código como quieras.
