<div align="center">

# 📚 MiHorario Data

### *Generador de Horarios ESIME Culhuacán IPN*

[![Website](https://img.shields.io/badge/Website-mihorarioesime.com-blue?style=for-the-badge&logo=google-chrome)](https://mihorarioesime.com/)
[![Facebook](https://img.shields.io/badge/Facebook-Le0nardSF-1877F2?style=for-the-badge&logo=facebook)](https://www.facebook.com/Le0nardSF/)
[![JSON](https://img.shields.io/badge/Data-JSON-orange?style=for-the-badge&logo=json)]()
[![ESIME](https://img.shields.io/badge/ESIME-Culhuacán-green?style=for-the-badge)]()

---

*Repositorio de datos JSON para la aplicación **MiHorario***

> 🎓 **Proyecto estudiantil independiente** - No es la página oficial de ESIME  
> 💡 **Desarrollado por un estudiante para ayudar a la comunidad estudiantil**

</div>

## 🎯 ¿Qué es MiHorario?

<table>
<tr>
<td width="60%">

**MiHorario** es una herramienta innovadora que revoluciona la forma en que organizas tu horario escolar:

- 🚀 **Organización rápida y eficiente** de tus clases
- 🧠 **Sugerencias inteligentes** de materias para horas libres
- 💼 **Compatibilidad total** con tu vida laboral
- 😌 **Inscripciones sin estrés** garantizadas

</td>
<td width="40%">

```
┌─────────────────────┐
│   📅 LUNES         │
├─────────────────────┤
│ 08:00 │ Cálculo    │
│ 10:00 │ Física     │
│ 12:00 │ 🆓 LIBRE   │
│ 14:00 │ Programación│
└─────────────────────┘
```

</td>
</tr>
</table>

## 📁 Estructura del Proyecto

<details>
<summary><strong>📚 Archivos de Horarios por Carrera</strong></summary>

| Archivo | Carrera | Descripción |
|---------|---------|-------------|
| `horarios_C.json` | 💻 **Computación** | Ingeniería en Computación |
| `horarios_E.json` | ⚡ **Eléctrica** | Ingeniería Eléctrica |
| `horarios_E24.json` | ⚡ **Eléctrica 2024** | Ingeniería Eléctrica (variante 2024) |
| `horarios_M.json` | ⚙️ **Mecánica** | Ingeniería Mecánica |
| `horarios_S.json` | 🖥️ **Sistemas** | Ingeniería en Sistemas |

</details>

<details>
<summary><strong>🏢 Directorio de Salones</strong></summary>

```
salones/
├── 📅 salon_libre_lunes.json
├── 📅 salon_libre_martes.json
├── 📅 salon_libre_miercoles.json
├── 📅 salon_libre_jueves.json
└── 📅 salon_libre_viernes.json
```

*Información actualizada sobre disponibilidad de salones por día*

</details>

## 📊 Estructura de Datos

### Horarios de Materias
Cada archivo de horarios contiene un array de objetos con la siguiente estructura:

```json
{
  "Carrera": "C",
  "Turno": "M",
  "Semestre": "1",
  "Grupo": "1CM11",
  "Asignatura": "CALCULO DIFERENCIAL E INTEGRAL",
  "Profesor": "Gonzalez Medina Vera",
  "Lunes": "11:30-13:00",
  "SalonLunes": "1202",
  "Martes": "10:00-11:30",
  "SalonMartes": "1202",
  "Miercoles": "",
  "SalonMiercoles": "",
  "Jueves": "8:30-10:00",
  "SalonJueves": "1119",
  "Viernes": "10:00-11:30",
  "SalonViernes": "1202",
  "Salon": "X",
  "Edificio": "X"
}
```

### Salones Libres
Cada archivo de salones contiene información sobre disponibilidad:

```json
{
  "dia": "lunes",
  "hora_inicio": "07:00",
  "hora_fin": "21:30",
  "fecha_extraccion": "2025-08-24T15:03:47.768284",
  "salones_por_edificio": {
    "1": [
      {
        "salon": "1101",
        "horario": "14:30-16:00",
        "edificio": "1"
      }
    ]
  }
}
```

## 🚀 Características Principales

<div align="center">

| 🎯 Funcionalidad | 📝 Descripción |
|:---:|:---|
| 🧩 **Organización Inteligente** | Estructura tus clases de manera óptima |
| 💡 **Sugerencias Automáticas** | Encuentra materias ideales para tus horas libres |
| 💼 **Modo Trabajador** | Perfecto para estudiantes que trabajan |
| 🔄 **Datos Actualizados** | Información del período 2025-2 |
| 🏢 **Consulta de Salones** | Disponibilidad en tiempo real |
| 📱 **Diseño Responsivo** | Funciona en cualquier dispositivo |

</div>

## 🔮 Roadmap & Próximas Actualizaciones

<div align="center">

```mermaid
gantt
    title Cronograma de Desarrollo
    dateFormat  YYYY-MM-DD
    section Diseño
    Nuevo UI/UX        :done, des1, 2025-01-01, 2025-01-15
    section Mobile
    Versión Móvil      :active, mob1, 2025-01-15, 2025-02-15
    section Datos
    Auto-actualización :future, data1, 2025-02-01, 2025-02-28
```

</div>

- 🎨 **Nuevo diseño** - Interfaz moderna y atractiva
- 📱 **App móvil** - Disponible próximamente
- 🤖 **Actualización automática** - Datos siempre frescos
- 🔔 **Notificaciones** - Alertas de cambios importantes

## 🎓 Carreras Soportadas

<div align="center">

| Código | 🎯 Carrera | 👥 Estudiantes | 📊 Estado |
|:------:|:-----------|:-------------:|:---------:|
| **C** | 💻 Ingeniería en Computación | ~800 | ✅ Activo |
| **E** | ⚡ Ingeniería Eléctrica | ~600 | ✅ Activo |
| **M** | ⚙️ Ingeniería Mecánica | ~700 | ✅ Activo |
| **S** | 🖥️ Ingeniería en Sistemas | ~500 | ✅ Activo |

</div>

## 👨‍💻 Desarrollador

<div align="center">

### Leonardo Sánchez
*Estudiante de ESIME Culhuacán*

[![Facebook](https://img.shields.io/badge/Facebook-Le0nardSF-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/Le0nardSF/)

---

> 💡 *"Creando herramientas que faciliten la vida académica de mis compañeros estudiantes"*

</div>

## 📊 Información del Proyecto

<div align="center">

| 📅 **Período Actual** | 🔄 **Actualización** | 🎯 **Versión** |
|:---:|:---:|:---:|
| Febrero - Julio 2025 (2025-2) | Semanal | v2.0 |

</div>

---

<div align="center">

**⭐ Si te gusta el proyecto, no olvides darle una estrella ⭐**

*Proyecto estudiantil independiente para ESIME Culhuacán*

</div>
