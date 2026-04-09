# Guía de Implementación WordPress - Los Deleites de Carlita

Esta guía explica paso a paso cómo implementar el diseño v0 en WordPress Site Editor usando el tema Assembler.

---

## Estructura del Sitio (Secciones del Diseño v0)

1. **Header** - Logo + Nombre + Menú
2. **Hero** - Título "Endulzamos tus momentos especiales" + CTA
3. **Estadísticas** - 10+ Años | 500+ Clientes | 100% Artesanal
4. **Catálogo de Tortas** - Grid de productos con filtros
5. **Nuestro Menú** - Lista de sabores
6. **Nuestra Historia** - Sobre la pastelería
7. **Contacto** - Formulario + Info
8. **Footer** - Navegación + Copyright

---

## Paso 1: Configurar el Tema

1. Ir a **Apariencia > Temas**
2. Activar tema **Assembler** (ya está activado)
3. Ir a **Apariencia > Editor** para acceder al Site Editor

---

## Paso 2: Configurar Estilos Globales

En el Site Editor, haz clic en **Estilos** (botón derecho superior):

### Colores
- **Primario**: `#D4AF37` (Dorado - para títulos y acentos)
- **Secundario**: `#8B4513` (Café - para texto)
- **Fondo**: `#FAF8F5` (Crema claro - para fondo)
- **Blanco**: `#FFFFFF`
- **Verde WhatsApp**: `#25D366`

### Tipografía
- **Títulos**: Playfair Display (Serif) - para nombres de tortas y títulos
- **Cuerpo**: Inter o system-ui - para descripciones

---

## Paso 3: Implementar Header

En la plantilla de Inicio:

1. **Grupo** (contenedor principal)
   - Fondo: `#FAF8F5`
   - Padding: 20px arriba/abajo

2. **Fila** (Logo + Nombre + Menú)
   - Alineación: Espacio entre (space-between)
   - **Logo**: Bloque Imagen con el logo de Carlita
   - **Título**: "Los Deleites de Carlita"
     - Fuente: Playfair Display
     - Color: `#8B4513` (café oscuro)
   - **Menú**: Bloque Navegación con enlaces a secciones

---

## Paso 4: Implementar Hero Section

1. **Grupo** (sección Hero)
   - Fondo: `#FAF8F5`
   - Padding: 60px arriba/abajo
   - Alineación: Centro

2. **Etiqueta**: "PASTELERÍA ARTESANAL"
   - Fuente: Inter, uppercase
   - Tamaño: 14px
   - Color: `#D4AF37` (dorado)
   - Espaciado entre letras: 4px

3. **Título**: "Endulzamos tus momentos especiales"
   - Fuente: Playfair Display
   - Tamaño: 48px (desktop) / 32px (mobile)
   - Color: `#1A1A1A`
   - Alineación: Centro

4. **Descripción**: Párrafo con texto sobre tortas artesanales
   - Fuente: Inter
   - Tamaño: 18px
   - Color: `#666666`
   - Ancho máximo: 600px

5. **Botones** (Fila con 2 botones)
   - **"Hacer Pedido"**: Botón negro con enlace a WhatsApp
   - **"Ver Catálogo"**: Botón con borde dorado

---

## Paso 5: Implementar Estadísticas

1. **Grupo** (sección Stats)
   - Fondo: `#FFFFFF`
   - Padding: 40px
   - Bordes superior e inferior: 1px sólido `#E5E5E5`

2. **Fila** con 3 columnas (Stat items)
   - **Columna 1**: "10+" / "Años"
   - **Columna 2**: "500+" / "Clientes"
   - **Columna 3**: "100%" / "Artesanal"
   - Números: 32px, Playfair Display, color `#1A1A1A`
   - Etiquetas: 14px, Inter, color `#666666`

---

## Paso 6: Implementar Catálogo de Tortas

1. **Título**: "Catálogo de Tortas"
   - Fuente: Playfair Display
   - Tamaño: 36px
   - Color: `#1A1A1A`
   - Alineación: Centro

2. **Descripción**: Párrafo descriptivo

3. **Filtros** (Botones tipo píldora)
   - "Todas" | "Clásicas" | "Temporada" | "Especiales"

4. **Grid de Productos** (Columnas, 2 o 3 columnas)
   - Cada producto es un **Grupo** con:
     - **Imagen** de la torta
     - **Etiqueta** "Especialidad" (si aplica)
     - **Título** de la torta (Playfair Display)
     - **Descripción** corta
     - **Botón** "Consultar" (enlace a WhatsApp)

### Productos del Catálogo:
1. **4 Leches con Frutilla** - Especialidad
2. **Chocolate Sublime** - Con o sin maní
3. **Torta de Girasoles** - Popular
4. **Hojarasca - Mil Hojas** - Clásica
5. **Torta Navideña** - Temporal
6. **Torta San Valentín** - Temporal
7. **Set de Tortas** - Eventos
8. **Navidad Casita** - Eventos

---

## Paso 7: Implementar Nuestro Menú

1. **Título**: "Nuestro Menú"
   - Subtítulo: "Sabores Exclusivos"

2. **Lista de sabores** (usar bloque Lista o Grupos)
   - 4 Leches con Frutilla - Estrella
   - Chocolate Sublime - Con o sin maní
   - Tutti Frutti - Trozos de fruta fresca
   - Moka - Café - Con o sin nueces
   - Pisco Sour - Con o sin almendra
   - Hojarasca - Mil Hojas - Tradición chilena

3. **Botón**: "Consultar Precios" (enlace a WhatsApp)

---

## Paso 8: Implementar Nuestra Historia

1. **Grupo** (sección con fondo claro)

2. **Título**: "Nuestra Historia" + "Pasión por la Repostería"

3. **Descripción**: Párrafo sobre el origen de Los Deleites de Carlita

4. **Fila** con 4 tarjetas de características:
   - **Hecho con Amor** - Icono + texto
   - **Ingredientes Premium** - Icono + texto
   - **Frescura Garantizada** - Icono + texto
   - **Diseños Únicos** - Icono + texto

---

## Paso 9: Implementar Contacto

1. **Título**: "Haz tu Pedido"
   - Subtítulo: "¿Tienes una celebración especial?"

2. **Información de Contacto** (Fila con columnas)
   - **Teléfono**: +56 962104980
   - **WhatsApp**: Enlace directo
   - **Horario**: Lun - Sáb: 9:00 - 20:00
   - **Ubicación**: Chile

3. **Botón principal**: "Abrir WhatsApp"

4. **Formulario** (usar bloque Formulario o Grupo con inputs)
   - Nombre Completo
   - Teléfono
   - Mensaje
   - Botón "Enviar por WhatsApp"

---

## Paso 10: Implementar Footer

1. **Grupo** (fondo oscuro o café)

2. **Logo** + descripción corta

3. **Navegación** (enlaces a secciones)

4. **Tortas destacadas** (lista)

5. **Contacto** (teléfono, WhatsApp)

6. **Horario** y copyright

---

## Paso 11: Botón Flotante de WhatsApp

1. Añadir un **Grupo** con posición fija (bottom-right)
2. **Botón** con icono de WhatsApp
3. Texto: "¡Haz tu pedido!"
4. Enlace: `https://wa.me/56962104980`

---

## Paso 12: Imágenes y Assets

### Imágenes necesarias:
1. **Logo Carlita** - Para header y footer
2. **Tortas del catálogo** - Para cada producto
3. **Fondo Hero** - Imagen de tortas artesanales
4. **Iconos** - Para características (corazón, ingredientes, etc.)

### Obtener imágenes:
- Desde la web actual de WordPress
- Desde Facebook: facebook.com/losdeleitesdecarlita.oficial
- Desde Instagram: instagram.com/reel/C0FgyPCommK/

---

## Enlaces de WhatsApp (para botones)

- **Pedido general**: `https://wa.me/56962104980?text=¡Hola!%20Me%20gustaría%20hacer%20un%20pedido%20de%20torta.`
- **4 Leches**: `https://wa.me/56962104980?text=¡Hola!%20Me%20gustaría%20pedir%20la%20torta%204%20Leches%20con%20Frutilla.`
- **Diseño personalizado**: `https://wa.me/56962104980?text=¡Hola!%20Me%20gustaría%20consultar%20por%20un%20diseño%20personalizado.`

---

## Referencia del Diseño v0

El diseño original fue creado en v0.dev y está disponible en:
- **Preview**: https://vm-sv75fqt3lpg8phvoknjeb8.vusercontent.net/
- **v0 Chat**: https://v0.app/chat/carlita-website-design-tvzNLCQAe2G

---

## Datos del Negocio

- **Nombre**: Los Deleites de Carlita
- **Ubicación**: Chile
- **Teléfono**: +56 962104980
- **Horario**: Lunes a Sábado, 9:00 - 20:00
- **Especialidad**: Torta 4 Leches con Frutilla
- **Años de experiencia**: 10+
- **Clientes**: 500+
