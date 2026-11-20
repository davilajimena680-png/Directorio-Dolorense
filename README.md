# Directorio Dolores Hidalgo: TDD y API

## 1. Servidor API

Encendido: el servidor local en Node.js inicia y queda listo para recibir peticiones.

![Servidor encendido](assets/R1_01_servidor_encendido.png)

---

## 2. Modelo Negocio

Rojo: la prueba falla porque la lógica o clase `Negocio` todavía no cumple con lo esperado.

![Negocio rojo](assets/R2_01_rojo_negocio_test.png)

Verde: se implementa `Negocio` y la prueba pasa.

![Negocio verde](assets/R2_02_verde_negocio_test.png)

---

## 3. Conexión y Pruebas de API

Rojo: la prueba de integración con la API falla.

![API rojo](assets/R3_01_rojo_api_test.png)

Verde: se conecta correctamente con los endpoints y la prueba pasa.

![API verde](assets/R3_02_verde_api_test.png)

### Casos de falla

Verde: se manejan los errores del servidor (como respuestas 500 o sin conexión) y la prueba pasa.

![Casos de falla verde](assets/R3_03_verde_casos_falla.png)

---

## 4. Secuencia de Estados (ViewModel)

Rojo: la prueba de la secuencia de estados (cargando, error, datos) falla.

![Secuencia de estados rojo](assets/R5_01_rijo_secuencia_estatos.png)

Verde: se implementa la gestión de estados en el ViewModel y la prueba pasa.

![Casos de falla verde](assets/R3_03_verde_casos_falla.png)

---

## Pantallas funcionando

<table>
  <tr>
    <td align="center">
      <strong>Captura 1</strong><br>
      <img src="https://github.com/user-attachments/assets/1b85e9e8-ab56-4c47-8d01-1947dc80945e" width="250">
    </td>
    <td align="center">
      <strong>Captura 2</strong><br>
      <img src="https://github.com/user-attachments/assets/ced572d3-3786-4465-b0a7-5613c7890c86" width="250">
    </td>
  </tr>
</table>

