# 🌊 Protolink: Sistema de Medición de Caudal Industrial

Este repositorio contiene el diseño electrónico completo (Esquemáticos, Layout y Modelado 3D) de un **Caudalímetro Digital** desarrollado bajo el ecosistema de **Galio**. 

El proyecto se enfoca en la precisión de la captura de pulsos y la robustez frente al ruido eléctrico industrial.

---

## 🛠️ Especificaciones Técnicas del Hardware

| Característica | Detalle |
| :--- | :--- |
| **Microcontrolador** | Compatibilidad nativa con Galio Core. |
| **Sensor de Flujo** | Interfaz para sensor de efecto Hall / Turbina. |
| **Alimentación** | 12V - 24V DC (Protección contra inversión de polaridad). |
| **Salidas** |  Modbus RTU. |

---

## ⚙️ Flujo de Trabajo (Workflow)

1. **Captura de Señal:** El sensor envía una frecuencia proporcional al flujo.
2. **Procesamiento:** La PCB acondiciona la señal cuadrada para evitar falsas lecturas por vibración.

## 📁 Contenido Destacado
* **`Esquemático`**: Archivos de exportación para el diseño de la carcasa/enclosure.
*<img width="1379" height="818" alt="image" src="https://github.com/user-attachments/assets/76ef5e95-ef27-40b7-936d-7df953809097" />

* **`PCB`**: Diseño de pistas optimizado para minimizar interferencias (EMI).
*<img width="1423" height="578" alt="image" src="https://github.com/user-attachments/assets/2077a528-f675-4fea-9ca9-677aa0abf603" />

* **`3D`**: Configuración lista para generar Gerbers y Pick&Place para fabricación automática.
*<img width="1430" height="550" alt="image" src="https://github.com/user-attachments/assets/e8c4cff1-1a9c-4d8c-a525-95e06d4cd2af" />


---
**Desarrollado por:** [Josep Alvizuri](https://github.com/Josep-Alvizuri) Galio HW 
**Proyecto:** Protolink Caudalímetro v1.0
