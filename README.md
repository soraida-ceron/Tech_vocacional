# 🚀 Tech Vocacional

**Plataforma de Orientación Vocacional para Carreras Tech**

Descubre tu carrera ideal en el mundo de la tecnología mediante un análisis científico de tus intereses, personalidad y motivadores laborales.

---

## 📋 Descripción

Tech Vocacional es una plataforma web interactiva que orienta a personas hacia carreras de tecnología evaluando:

✅ **Intereses Vocacionales** (48 preguntas contextualizadas)
- Preguntas basadas en tareas reales de cada carrera
- Ejemplos concretos (Facebook, PayPal, Netflix, etc.)
- Escala Likert 1-5

✅ **Personalidad Big Five** (20 preguntas científicas)
- Modelo OCEAN validado internacionalmente
- 5 dimensiones: Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism
- Perfil código (ej: EOCNN)

✅ **Motivadores Laborales** (10 motivadores universales)
- CHARMFROGS: Causalidad, Humanidad, Autonomía, Reconocimiento, Maestría, Familia, Realización, Orden, Ganancia, Seguridad
- Ranking personalizado

**Resultado:** Carrera ideal + 2 alternativas + salarios + dónde estudiar + motivadores alineados

---

## 🎯 14 Carreras Cubiertas

1. **Full Stack Developer** 💻
2. **Data Scientist** 📊
3. **Data Engineer** ⚙️
4. **Ciberseguridad** 🔒
5. **UX/UI Design** ✨
6. **Cloud/DevOps** ☁️
7. **SRE** 📡
8. **Product Manager** 📱
9. **Tecnologías Emergentes** 🚀
10. **QA Automation** 🧪
11. **MLOps** 🤖
12. **No-Code** 🛠️
13. **Ética IA** ⚖️
14. **Arquitecto de Soluciones** 🏛️

---

## 🏗️ Arquitectura Técnica

### Stack Tecnológico

```
Frontend:
├── HTML5 (semántica, formularios)
├── CSS3 (responsivo, gradientes, flexbox)
└── JavaScript Vanilla (sin dependencias)

Backend:
└── Formspree (SaaS para emails, gratis)

Diseño:
├── Paleta: Azul Profundo, Azul Medio, Cian, Violeta
└── Responsive: Mobile-first
```

### Características

- ✅ **100% Client-side** - No requiere servidor
- ✅ **Sin dependencias** - JavaScript vanilla
- ✅ **Deployable** - GitHub Pages, Netlify, o local
- ✅ **Sin costos** - Gratis (Formspree gratuito)

---

## 🚀 Inicio Rápido

### Opción 1: Online (GitHub Pages)

1. Descarga `tech_vocacional_final.html`
2. Sube a tu repositorio GitHub
3. Activa GitHub Pages en Settings
4. Accede en `https://tuusuario.github.io/repo`

### Opción 2: Local

1. Descarga `tech_vocacional_final.html`
2. Haz doble clic para abrir en navegador
3. ¡Listo! No requiere servidor

### Opción 3: Netlify

1. Descarga `tech_vocacional_final.html`
2. Arrastra el archivo a https://app.netlify.com/drop
3. Obtén URL pública al instante

---

## 📧 Configurar Emails (Formspree)

Para que el botón "📧 Enviar por email" funcione:

1. Crea cuenta en https://formspree.io
2. Crea un form y obtén tu endpoint: `https://formspree.io/f/TU_ID`
3. En `tech_vocacional_final.html`, línea ~213:
   ```javascript
   const FORMSPREE_ENDPOINT = "https://formspree.io/f/TU_ID_AQUI";
   ```
4. ¡Listo! Los emails se enviarán automáticamente

---

## 📊 Algoritmo de Matching

### Scoring System

1. **Test Vocacional**: Suma de puntos (0-48)
2. **Big Five**: Dimensiones compatibles con carrera
3. **Motivadores**: Top 2 alineados con carrera

### Ejemplo

```
Usuario: Full Stack Developer (45 pts vocacionales)
Big Five: EOCNA (E=12, O=14, C=18, N=8, A=15)
Top Motivadores: Autonomía, Maestría

Resultado: ✅ Full Stack Developer
Razón: Autonomía (construye features) + Maestría (crece aprendiendo)
```

---

## 📁 Estructura de Archivos

```
tech-vocacional/
├── tech_vocacional_final.html    (archivo principal)
├── README.md                      (este archivo)
├── Tech_Vocacional_Documentacion.docx (documentación completa)
└── LICENSE
```

---

## 🔧 Características Avanzadas

### Explorador de Carreras

Haz clic en cualquier carrera para ver:
- Descripción detallada
- 6-8 tareas principales
- Tabla de salarios (Junior/Mid/Senior)
- Dónde estudiar en México (con links reales)
- Motivadores típicos

### Dashboard de Resultados

Muestra:
- 🎯 Carrera ideal con score
- 💡 Perfil Big Five (código + interpretación)
- ⚡ Top 2 motivadores
- 💰 Salarios por nivel
- 📚 2 carreras alternativas
- 📋 Próximos pasos

### Email Automático

Los resultados se envían en un email formateado con:
- Perfil personalizado
- Motivadores del usuario
- Carrera ganadora + alternativas
- Salarios + dónde estudiar
- Footer con CV del creador

---

## 📝 Documentación Detallada

Para información completa sobre:
- Fundamentación científica de cada test
- Detalles del algoritmo de matching
- Mapeo de las 14 carreras
- Teoría Big Five vs tests tradicionales

→ **Ver: `Tech_Vocacional_Documentacion.docx`**

---

## 🎨 Diseño & UX

### Paleta de Colores

```css
--azul-profundo: #1A237E   (encabezados, fondos)
--azul-medio: #0277BD      (botones, tablas)
--cian: #00E5FF            (acentos, botones hover)
--violeta: #7E57C2         (secciones secundarias)
--gris-texto: #333333      (texto principal)
--gris-fondo: #F5F5F5      (fondos claros)
```

### Tipografía

- **Fuente**: Segoe UI, Arial, sans-serif
- **Heading 1**: 32px, bold, azul profundo
- **Heading 2**: 28px, bold, azul medio
- **Cuerpo**: 22px, regular

### Responsive

- ✅ Mobile (320px+)
- ✅ Tablet (768px+)
- ✅ Desktop (1024px+)

---

## 🤝 Autor

**Soraida Cerón**

- 🎓 Psicóloga Organizacional
- 💼 Arquitecta de Desarrollo de Talento
- 📊 7+ años en Talent Development

**Personal Brand**: "No llego sola" 💪

**Contacto**:
- 📧 Email: soraida.ceron@gmail.com
- 🌐 CV: https://soraidaceroncv.netlify.app
- 💼 LinkedIn: [Tu LinkedIn aquí]

---

## 📜 Licencia

MIT License - Libre para usar, modificar y distribuir

---

## 🚀 Roadmap Futuro

- [ ] Versión en inglés y otras idiomas
- [ ] Base de datos para guardar historiales
- [ ] Dashboard de estadísticas (si 100+ usuarios)
- [ ] Integración con plataformas de estudio
- [ ] Versión móvil nativa (React Native)
- [ ] Tests de validación adicionales

---

## 💡 Contribuciones

Si encuentras bugs o tienes sugerencias:
1. Abre un GitHub Issue
2. Propón cambios con Pull Request
3. Contacta al autor

---

**Made with ❤️ for people entering the tech world** 🌟
