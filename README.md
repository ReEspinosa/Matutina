# 📖 Matutina 2026 — App de Estudio para Concurso

App web para memorizar los 89 versículos de la Matutina (Febrero, Marzo y Abril) del concurso de Conquistadores y Guías Mayores.

🔗 **[Ver app en vivo](https://TU-USUARIO.github.io/TU-REPO)**

---

## ¿Qué incluye?

| Modo | Descripción |
|------|-------------|
| **Estudio** | Explora todos los versículos por mes. Expande cada tarjeta para ver fecha, título, versículo y cita. Marca los que ya memorizaste. |
| **Práctica** | Se muestra la fecha, grabas tu voz y dices título + versículo + cita. La app transcribe y te da un porcentaje de acierto por componente. |
| **Quiz** | Preguntas escritas aleatorias: opción múltiple, falso/verdadero, completar espacios y relacionar columnas — igual que el examen real. |
| **Concurso** | Se te muestra una variable aleatoria (fecha, título, versículo o cita), presionas BUZZ y dices las otras tres. Cronómetro de 30 segundos. |

---

## Cómo subir a GitHub Pages (paso a paso)

### 1. Asegúrate de que el archivo se llame `index.html`

GitHub Pages sirve `index.html` por defecto. Si tu archivo se llama `matutina-final.html`, renómbralo:

```bash
# En tu computadora
mv matutina-final.html index.html
```

O directamente en GitHub: abre el archivo → botón de lápiz (editar) → cambia el nombre en la barra superior → commit.

### 2. Activa GitHub Pages

1. Ve a tu repositorio en GitHub
2. **Settings** → **Pages** (menú izquierdo)
3. En *Source* selecciona **Deploy from a branch**
4. Branch: **main** (o master) — carpeta: **/ (root)**
5. Guarda

### 3. Espera 1-2 minutos

GitHub Pages tarda un poco. Luego entra a:
```
https://TU-USUARIO.github.io/TU-REPO/
```

---

## Estructura del repo

```
/
├── index.html       ← toda la app (un solo archivo)
└── README.md
```

---

## Requisitos para el reconocimiento de voz

| Plataforma | Navegador recomendado |
|---|---|
| Android | Chrome |
| Windows / Mac | Chrome o Edge |
| iPhone / iPad | Safari (limitado) |

El reconocimiento de voz usa la **Web Speech API** del navegador, que funciona mejor en Chrome. No se guarda ningún audio — todo se procesa localmente.

---

## Versículos incluidos

- **Febrero**: 28 versículos (01/02 al 28/02)
- **Marzo**: 31 versículos (01/03 al 31/03)
- **Abril**: 30 versículos (01/04 al 30/04)
- **Total**: 89 versículos

---


*Matutina "Héroes o Villanos" (Conquistadores) · Matutina "Inverso" (Guías Mayores)*
