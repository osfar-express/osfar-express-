# 🏠 OSFAR EXPRESS - Tienda Ecommerce para Paraguay

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-Active-success.svg)

Tienda ecommerce profesional para vender **hogar, cocina y electrónica** con sistema de reseñas, carrito interactivo y pagos integrados.

## ✨ Características Principales

### 🛍️ Tienda
- ✅ 18 productos pre-cargados
- ✅ 3 categorías (Hogar, Cocina, Electrónica)
- ✅ Filtrado por categoría
- ✅ Precios en Guaraní (₲)
- ✅ Descuentos visibles
- ✅ Búsqueda de productos

### ⭐ Sistema de Reseñas
- ✅ Reseñas por producto
- ✅ Calificación con estrellas (1-5)
- ✅ Modal para agregar reseña
- ✅ Testimonios en el footer
- ✅ Rating promedio por producto

### 🛒 Carrito y Checkout
- ✅ Carrito completo
- ✅ Ajuste de cantidad
- ✅ Cálculo automático de impuestos
- ✅ Envío gratuito >500,000₲
- ✅ Formulario de entrega completo
- ✅ Confirmación de orden

### 💳 Pagos Integrados
- ✅ **Pago Fácil** (tarjeta crédito/débito)
- ✅ **Transferencia bancaria**
- ✅ **Efectivo contra entrega**
- ✅ **Billetera digital**
- ✅ Cálculo de totales automático

### 📱 WhatsApp Integrado
- ✅ Link directo a WhatsApp
- ✅ Mensaje automático con detalles
- ✅ Número personalizado (+595 982 392 681)
- ✅ Abre en nueva pestaña

### 📊 Dashboard
- ✅ Vercel Analytics
- ✅ Monitoreo de tráfico
- ✅ Logs de errores
- ✅ Performance metrics

## 🚀 Despliegue Rápido

### Opción 1: Vercel (Recomendado - 1 minuto)
```bash
# 1. Ir a https://vercel.com
# 2. Crear cuenta con GitHub
# 3. Importar repositorio
# 4. Deploy automático ✅
```

### Opción 2: GitHub Pages (Gratis)
```bash
git clone https://github.com/tu-usuario/osfar-express.git
cd osfar-express
git push origin main
# Activar Pages en settings
```

### Opción 3: Netlify (Alternativa)
```bash
# Arrastra la carpeta a https://app.netlify.com
# Espera a que se despliegue
# ¡Listo!
```

## 📋 Requisitos Previos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Cuenta en Vercel (gratuita)
- Número de WhatsApp (tuyo)
- Cuenta en Pago Fácil (opcional, para pagos con tarjeta)

## ⚙️ Configuración

### 1. Personalizar Número de WhatsApp
Edita `index.html` y busca:
```javascript
const whatsappNumber = '595982392681'; // TU NÚMERO AQUÍ
```

Formato: `595XXXXXXXXXXX` (sin +, sin espacios)

### 2. Integrar Pago Fácil
1. Regístrate en https://www.pagofacil.net
2. Obtén tu Merchant ID
3. Edita en `index.html`:
```javascript
const merchantId = 'TU_MERCHANT_ID_AQUI';
```

### 3. Agregar tus Productos
Edita el array `products` en `index.html`:
```javascript
{ 
  id: 1, 
  name: 'Mi Producto', 
  category: 'hogar', 
  price: 100000, 
  icon: '📦', 
  rating: 5 
}
```

## 📚 Estructura de Archivos

```
osfar-express/
├── index.html              # Aplicación principal
├── package.json            # Metadatos del proyecto
├── vercel.json             # Config de Vercel
├── .gitignore              # Archivos ignorados
├── README.md               # Esta documentación
└── GUIA_COMPLETA.md        # Guía detallada
```

## 🔧 Variables de Entorno (Opcional)

Si usas backend:
```bash
PAGO_FACIL_MERCHANT_ID=tu_id
PAGO_FACIL_API_KEY=tu_api_key
WHATSAPP_NUMBER=595982392681
```

## 📱 Responsive Design

- ✅ Optimizado para móvil
- ✅ Tablet compatible
- ✅ Desktop completo
- ✅ Velocidad optimizada

## 🔒 Seguridad

- ✅ HTTPS automático en Vercel
- ✅ Datos no se guardan en cliente
- ✅ Pago Fácil maneja tarjetas (PCI DSS)
- ✅ Validación de formularios

## 📊 Analytics y Monitoreo

### Vercel Dashboard
```
https://vercel.com/dashboard
```
- Visitas
- Performance
- Despliegues
- Error logs

### Pago Fácil Panel
```
https://www.pagofacil.net (Tu cuenta)
```
- Transacciones
- Reportes
- Estadísticas

## 🐛 Troubleshooting

### WhatsApp no abre
- [ ] Verifica el formato del número (595xxxxxxxxx)
- [ ] El dispositivo tiene WhatsApp instalado
- [ ] Prueba en móvil, no desktop

### Pago Fácil no funciona
- [ ] Verifica Merchant ID
- [ ] Usa sandbox para pruebas
- [ ] Contacta: soporte@pagofacil.net

### Tienda lenta
- [ ] Revisa Analytics de Vercel
- [ ] Optimiza imágenes
- [ ] Usa CDN global

## 📞 Soporte

| Tema | Contacto |
|------|----------|
| Hosting | https://vercel.com/help |
| Pagos | soporte@pagofacil.net |
| WhatsApp | Tu número |
| Código | Issues en GitHub |

## 📈 Roadmap

- [ ] Panel de administración
- [ ] Inventario dinámico
- [ ] Email marketing
- [ ] App móvil nativa
- [ ] Múltiples idiomas
- [ ] Sistema de cupones
- [ ] Programa de afiliados

## 💡 Tips para Aumentar Ventas

1. **Reseñas auténticas** → Aumentan conversión 270%
2. **Fotos de calidad** → Reemplaza emojis con imágenes
3. **Testimonios visibles** → Social proof = confianza
4. **Descuentos limitados** → Crea urgencia
5. **WhatsApp rápido** → Responde en <5 min
6. **SEO básico** → Meta tags y títulos
7. **Publicidad** → Invierte 10% de ganancias

## 📄 Licencia

MIT © 2025 OSFAR Express

## 🤝 Contribuir

1. Fork el proyecto
2. Crea tu rama (`git checkout -b feature/AmazingFeature`)
3. Commit cambios (`git commit -m 'Add AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre Pull Request

## 🌟 Agradecimientos

Hecho con ❤️ para Paraguay

---

## 📞 Contacto

**OSFAR Express**
- 📱 WhatsApp: +595 982 392 681
- 🌐 Web: https://osfar-express.vercel.app
- 📧 Email: info@osfar.com.py

---

**¡Hecho para vender! 🚀🇵🇾**

Última actualización: 2025-05-01
