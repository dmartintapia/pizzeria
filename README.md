# Pizzería Criolla

App liviana para tomar pedidos de pizzas, empanadas, hamburguesas y lomitos, con envío de la orden a WhatsApp y un panel simple para actualizar precios, stock e imágenes.

## Requisitos
- Node.js 18+

## Cómo usar
1. Instalar dependencias (no se requieren librerías externas).
2. Ejecutar el servidor:
   ```bash
   npm start
   ```
3. Abrir `http://localhost:3000` para el flujo de compra.
4. Abrir `http://localhost:3000/admin` para actualizar menú, stock y fotos. Las imágenes se guardan en `public/uploads` y se referencian en `data/menu.json`.

Los productos con stock `0` no se muestran en el front de compra. El checkout arma un mensaje con los datos de contacto y pago y abre WhatsApp al número +54 9 11 3627-5604.
