# ⚡ GUÍA RÁPIDA: OSFAR EXPRESS EN VERCEL (5 MINUTOS)

## 📋 RESUMEN
```
✅ Paso 1: Preparar archivos (1 min)
✅ Paso 2: Crear cuenta Vercel (2 min)
✅ Paso 3: Desplegar (1 min)
✅ Paso 4: Tu tienda en VIVO (1 min)
✅ Total: 5 MINUTOS
```

---

## 🚀 PASO 1: DESCARGAR ARCHIVOS (1 MIN)

Descarga estos 4 archivos en una carpeta llamada `osfar-express`:
1. ✅ `index.html` - Tu tienda completa
2. ✅ `vercel.json` - Config de Vercel
3. ✅ `package.json` - Metadatos
4. ✅ `.gitignore` - Ignorar archivos

**Todos están en:** `/mnt/user-data/outputs/`

---

## 📍 PASO 2: CREAR CUENTA VERCEL (2 MIN)

### 2.1 Ir a Vercel
```
Abre: https://vercel.com
```

### 2.2 Crear Cuenta
```
Clic en "Sign Up"
↓
Elige GitHub (recomendado)
↓
Autoriza Vercel
↓
¡Cuenta creada!
```

**Si no tienes GitHub:**
- Usa tu email directamente
- Verifica tu cuenta
- ¡Listo!

---

## 📤 PASO 3: SUBIR ARCHIVOS (2 OPCIONES)

### OPCIÓN A: Con GitHub (Automático)

#### A1. Crear repositorio GitHub
```
1. Abre: https://github.com/new
2. Nombre: osfar-express
3. Crear repositorio
```

#### A2. Subir archivos
```bash
# En tu carpeta osfar-express
git init
git add .
git commit -m "OSFAR Express"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/osfar-express.git
git push -u origin main
```

#### A3. Conectar con Vercel
```
1. Ve a https://vercel.com/dashboard
2. Clic en "New Project"
3. Selecciona "osfar-express"
4. Clic en "Deploy"
```

**⏱️ Tiempo: 2 minutos**

---

### OPCIÓN B: Directo con Vercel (Más fácil)

#### B1. Instalar Vercel
```bash
npm install -g vercel
```

#### B2. Desplegar
```bash
cd osfar-express
vercel
```

#### B3. Seguir instrucciones
```
- Equipo: Personal
- Nombre: osfar-express
- Directorio: ./
- ¡Listo!
```

**Vercel te dará una URL:** `https://osfar-express.vercel.app`

**⏱️ Tiempo: 1 minuto**

---

## ✅ PASO 4: TU TIENDA ESTÁ EN VIVO

### Visitarla
```
https://osfar-express.vercel.app
```

### Pruebas rápidas
- [ ] Agrega productos al carrito
- [ ] Abre carrito
- [ ] Ve a checkout
- [ ] Completa formulario
- [ ] Haz clic en "Completar Compra"
- [ ] Se abre WhatsApp automáticamente ✅

---

## 🎯 PERSONALIZAR (OPCIONAL)

### 1. Cambiar número de WhatsApp
En `index.html`, busca:
```javascript
const whatsappNumber = '595982392681';
```
Reemplaza con tu número (sin +, sin espacios)

### 2. Agregar más productos
En `index.html`, busca el array `products` y agrega:
```javascript
{ 
  id: 19, 
  name: 'Tu Producto', 
  category: 'hogar', 
  price: 150000, 
  icon: '📦', 
  rating: 4.5,
  reviewsCount: 10
}
```

### 3. Actualizar después
```bash
cd osfar-express
git add .
git commit -m "Actualizaciones"
git push
# Vercel actualiza automáticamente ✅
```

---

## 🌐 DOMINIO PERSONALIZADO (OPCIONAL)

### Opción 1: Gratis (Vercel)
Tu tienda ya tiene: `osfar-express.vercel.app`

### Opción 2: Con tu dominio (Pago)
1. Compra dominio en Namecheap/GoDaddy (~$5 USD/año)
2. Ve a Vercel → Tu Proyecto → Domains
3. Agrega tu dominio
4. Sigue instrucciones DNS
5. Espera 24h para propagación

---

## 💳 PAGO FÁCIL (OPCIONAL)

### Para aceptar tarjetas de crédito:

1. Regístrate en: https://www.pagofacil.net
2. Obtén tu **Merchant ID**
3. En `index.html`, reemplaza:
```javascript
const merchantId = '8110'; // CAMBIA A TU ID
```
4. Guarda y deploya

---

## 🚨 SI ALGO FALLA

### WhatsApp no abre
```
✓ Verifica número: 595xxxxxxxxx (sin +)
✓ Edita el archivo
✓ Haz git push (Vercel actualiza solo)
```

### Tienda no carga
```
✓ Limpia caché (Ctrl+Shift+Suprimir)
✓ Abre en incógnito
✓ Espera 30 segundos
```

### Vercel dice error
```
✓ Ve a https://vercel.com/dashboard
✓ Ve a tu proyecto
✓ Mira tab "Deployments"
✓ Busca línea roja con error
```

---

## 📊 VER TUS ESTADÍSTICAS

### Dashboard Vercel
```
https://vercel.com/dashboard
→ Tu proyecto
→ Analytics / Deployments
```

### Ver visitas
```
- Páginas vistas
- Países
- Dispositivos
- Performance
```

---

## 🎉 ¡LISTO!

Tu tienda está:
- ✅ EN VIVO en Vercel
- ✅ CON WHATSAPP automático
- ✅ LISTA para vender
- ✅ 100% GRATIS

---

## 📝 CHECKLIST FINAL

- [ ] Archivos descargados
- [ ] Cuenta Vercel creada
- [ ] Archivos subidos
- [ ] Tienda en vivo
- [ ] Probada en móvil
- [ ] WhatsApp funciona
- [ ] Número personalizado
- [ ] Compartida en redes

---

## 🔗 LINKS IMPORTANTES

| Servicio | URL |
|----------|-----|
| Tu tienda | https://osfar-express.vercel.app |
| Dashboard Vercel | https://vercel.com/dashboard |
| Pago Fácil | https://www.pagofacil.net |
| Tu WhatsApp | https://wa.me/595982392681 |

---

## 📞 AYUDA

**Problema → Solución**

| Problema | Solución |
|----------|----------|
| No puedo crear GitHub | Usa email en Vercel directo |
| Vercel pide código | Verifica email para confirmación |
| WhatsApp no abre | Formato: 595xxxxxxxxx (sin +) |
| Tienda se ve mal en móvil | Limpia caché (Ctrl+Shift+Supr) |

---

## 🎯 PRÓXIMOS PASOS

1. **Invita gente:** Comparte tu link
2. **Recibe órdenes:** Por WhatsApp
3. **Procesa pagos:** Con Pago Fácil
4. **Aumenta:**
   - Más productos
   - Publicidad en Meta/Google
   - Email marketing

---

**¡A VENDER! 🚀🇵🇾**

Tiempo total: **5 MINUTOS**

Última actualización: 2025-05-01
