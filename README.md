# Calculadora PRO de Sublimación

Versión descargable inspirada en la hoja de cálculo compartida y en `app-electricistaV2.0`.

## Incluye

- Calculadora de costos y precios.
- Productos sublimables editables.
- Papel, tinta, amortización, merma, mano de obra, electricidad, packaging y otros gastos.
- Margen, comisión e IVA.
- Presupuestos guardados.
- Historial local.
- Diseño responsive.
- PWA con soporte offline.

## Cómo usarla

1. Descomprimí el archivo ZIP.
2. Abrí `index.html` en el navegador.
3. Para instalarla como aplicación, servila desde un servidor local, por ejemplo:

```bash
python3 -m http.server 8000
```

Luego visitá `http://localhost:8000`.

## Importante

Esta versión guarda los datos en el navegador usando `localStorage`. No contiene las credenciales Firebase del proyecto Electricista. Para sincronización entre usuarios y dispositivos hay que conectar Firebase Authentication y Firestore en una segunda etapa.
