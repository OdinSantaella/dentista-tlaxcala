# 📸 Guía de Reemplazo de Imágenes
## Dentista Elizabeth Rodríguez - Tlaxcala

---

## 🎯 IMÁGENES QUE NECESITAN REEMPLAZO

### 1. **HERO IMAGE** (Imagen principal - La más visible)
**Ubicación en el sitio:** Sección Hero (arriba de todo)
**Tamaño recomendado:** 1920x1200px o superior
**Formato:** JPG (1280x800px para web) + WebP

**Archivos a reemplazar:**
```
docs/img/hero-dental-elizabeth-tlaxcala.jpg
docs/img/hero-dental-elizabeth-tlaxcala.webp
```

**Qué fotografiar:**
- Sonrisa radiante de paciente (o modelo dental)
- Consultorio dental moderno de fondo
- Ambiente profesional y acogedor
- Iluminación profesional
- Fotografía de alta calidad

**Sugerencias:**
- Incluir silla dental o equipo moderno
- Ambiente limpio y luminoso
- Colores que combinen con turquesa/azul
- Transmitir confianza y profesionalismo

---

### 2. **PROCESS/CONSULTATION IMAGE**
**Ubicación en el sitio:** Sección "Cómo Funciona" (proceso)
**Tamaño recomendado:** 1200x800px
**Formato:** JPG (800x500px para web) + WebP

**Archivos a reemplazar:**
```
docs/img/consultorio-dental-elizabeth-tlaxcala.jpg
docs/img/consultorio-dental-elizabeth-tlaxcala.webp
```

**Qué fotografiar:**
- Dra. Elizabeth en consultorio
- Consultando con paciente
- O equipo dental moderno
- Ambiente profesional
- Énfasis en seguridad e higiene

---

### 3. **ABOUT/INTERIOR IMAGE**
**Ubicación en el sitio:** Sección "Conoce a tu Dentista" (about)
**Tamaño recomendado:** 1000x700px
**Formato:** JPG (600x400px para web) + WebP

**Archivos a reemplazar:**
```
docs/img/consultorio-dental-elizabeth-tlaxcala-interior.jpg
docs/img/consultorio-dental-elizabeth-tlaxcala-interior.webp
```

**Qué fotografiar:**
- Interior del consultorio
- Sala de espera acogedora
- Equipo dental moderno
- Ambiente limpio y profesional
- O retrato profesional de la Dra. Elizabeth

---

### 4. **LOGO**
**Ubicación en el sitio:** Header y Footer
**Tamaño recomendado:** 200x200px (vectorial)
**Formato:** SVG (preferido para logos)

**Archivo a reemplazar:**
```
docs/img/logo-dentista-elizabeth-tlaxcala.svg
```

**Qué necesita:**
- Logo profesional de Dra. Elizabeth Rodríguez
- Preferentemente en SVG para escalabilidad
- Colores: Turquesa (#5AB9B5) y Navy (#1B4965)
- Si no existe SVG: JPG de alta resolución (300dpi)

---

## 🛠️ CÓMO REEMPLAZAR LAS IMÁGENES

### Opción 1: Manualmente (Recomendado)
1. Reemplaza los archivos JPG con tus nuevas imágenes
2. Genera versión WebP de cada imagen:
   ```bash
   # Usando ImageMagick (si está instalado)
   convert original.jpg -quality 80 original.webp

   # O usando cwebp (Google WebP tool)
   cwebp -q 80 original.jpg -o original.webp
   ```
3. Mantén los mismos nombres de archivo
4. Verifica que las dimensiones sean similares

### Opción 2: Con herramientas online
1. Ve a https://cloudconvert.com
2. Sube tu JPG
3. Descarga como WebP
4. Reemplaza en `docs/img/`

---

## 📐 ESPECIFICACIONES TÉCNICAS

### JPGS - Optimización para Web
```
- Calidad: 80% (balance calidad/tamaño)
- Tamaño máximo: 200KB (preferiblemente <150KB)
- Dimensiones: Las mostradas arriba
- Formato: RGB (no CMYK)
```

### WEBP - Formato Moderno
```
- Calidad: 80%
- Tamaño típico: 50-70% menor que JPG
- Navegadores soportados: Todos excepto IE
- Fallback a JPG automático en el HTML
```

### LOGO - SVG
```
- Vectorial infinitamente escalable
- Tamaño típico: 5-50KB
- Colores: RGB
- Transparencia: Soportada
```

---

## 🎨 REFERENCIA DE COLORES

Estos colores están en el sitio y debes mantener coherencia:

| Nombre | Código | Uso |
|--------|--------|-----|
| Turquesa Principal | #5AB9B5 | Botones, headers |
| Turquesa Oscuro | #45A29E | Hover effects |
| Navy | #1B4965 | Headers, footer, texto |
| Blanco | #FFFFFF | Fondos principales |
| Gris Claro | #F8F9FA | Secciones alternadas |

**Recomendación:** Al fotografiar, busca fondos que complementen estos colores.

---

## ✅ CHECKLIST ANTES DE SUBIR IMÁGENES

- [ ] Imágenes tienen el tamaño correcto
- [ ] Nombre de archivo coincide exactamente
- [ ] JPG optimizado (calidad 80%, <200KB)
- [ ] WebP versión creada
- [ ] Alt text es descriptivo
- [ ] Imágenes representan servicios dentales
- [ ] Calidad profesional (no pixeladas)
- [ ] Coherencia con branding de la Dra.

---

## 🚀 DESPUÉS DE REEMPLAZAR

1. **Verifica localmente:**
   ```bash
   # Abre en navegador
   file:///path/to/docs/index.html
   ```

2. **Chequea en móvil:**
   - Tamaño correcto
   - Carga rápida
   - No distorsionadas

3. **Test de colores:**
   - ¿Las imágenes combinan con turquesa/navy?
   - ¿Se ven profesionales?
   - ¿Transmiten confianza?

4. **Deploy:**
   - Sube a Netlify (automático con push a git)
   - O despliega donde tengas hospedaje

---

## 📁 ESTRUCTURA ACTUAL

```
docs/
├── img/
│   ├── hero-dental-elizabeth-tlaxcala.jpg          ← REEMPLAZAR
│   ├── hero-dental-elizabeth-tlaxcala.webp         ← REEMPLAZAR
│   ├── consultorio-dental-elizabeth-tlaxcala.jpg   ← REEMPLAZAR
│   ├── consultorio-dental-elizabeth-tlaxcala.webp  ← REEMPLAZAR
│   ├── consultorio-dental-elizabeth-tlaxcala-interior.jpg  ← REEMPLAZAR
│   ├── consultorio-dental-elizabeth-tlaxcala-interior.webp ← REEMPLAZAR
│   ├── logo-dentista-elizabeth-tlaxcala.svg        ← REEMPLAZAR
│   └── whatsapp-icon.png                           (Mantener igual)
├── css/
├── js/
└── index.html
```

---

## 💡 SUGERENCIAS DE FOTÓGRAFOS

Si necesitas contratar a alguien:
- Fotógrafo profesional de empresas/consultorio
- Especializado en fotografía comercial
- Con experiencia en clínicas/negocios de salud
- Costo estimado: $200-500 USD para sesión + edición

**O usar stock photos profesionales:**
- Unsplash (gratis)
- Pexels (gratis)
- Shutterstock ($1-50 por imagen)
- iStock ($15-100 por imagen)

---

## 🎬 FOTOGRAFÍA PASO A PASO

### Para Hero Image:
1. Ilumina bien el consultorio
2. Cero pacientes visibles (privacidad)
3. Silla dental limpia y moderna
4. Sonrisa del personal o modelo dental
5. Composición: 2/3 consultorio, 1/3 rostro
6. Resolución: 2000x1200px mínimo

### Para Process Image:
1. Escena de consulta dental real
2. O equipo moderno de fondo
3. Dra. Elizabeth si es posible
4. Ambiente profesional
5. Iluminación homogénea
6. Resolución: 1500x1000px mínimo

### Para About Image:
1. Retrato profesional de Dra. Elizabeth
2. O interior del consultorio
3. Colores cálidos/azules
4. Fondo no distractivo
5. Profesionalismo
6. Resolución: 1200x800px mínimo

---

## 📞 CONTACTO PARA AYUDA

Si tienes dudas sobre:
- **Tamaños de imagen:** Usa online-convert.com
- **Optimización:** TinyPNG.com para JPG
- **WebP conversion:** CloudConvert.com
- **Fotógrafos:** Busca "fotógrafo profesional Tlaxcala"

---

**Nota Final:** Una vez reemplaces las imágenes, el sitio estará 100% listo para producción. ¡Las imágenes son el último paso! 🎉
