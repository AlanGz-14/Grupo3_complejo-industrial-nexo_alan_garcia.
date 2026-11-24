# Grupo3_complejo-industrial-nexo_alan_garcia.
# 🏥 SaludEnLínea

> Aplicación de gestión médica para reservar citas en línea, consultar el historial clínico digital y recibir recetas médicas electrónicas.

**Trabajo Práctico Experimental 4 (TPE 4)** · Introducción a la Ingeniería del Software

---

## 📋 Tabla de contenidos

- [Descripción del proyecto](#-descripción-del-proyecto)
- [Problema y objetivo](#-problema-y-objetivo)
- [Usuarios del sistema](#-usuarios-del-sistema)
- [Requisitos funcionales](#-requisitos-funcionales-rf)
- [Requisitos no funcionales](#-requisitos-no-funcionales-rnf)
- [Casos de prueba](#-casos-de-prueba)
- [Criterios de aceptación](#-criterios-de-aceptación)
- [Equipo de trabajo](#-equipo-de-trabajo)
- [Información académica](#-información-académica)

---

## 📖 Descripción del proyecto

**SaludEnLínea** es una aplicación de gestión médica que permite a los pacientes:

- 📅 Reservar citas médicas en línea.
- 📂 Consultar su historial clínico digital.
- 💊 Recibir recetas médicas electrónicas.

La necesidad principal del proyecto es **facilitar la atención médica**, **reducir la congestión en los centros de salud** y permitir una **gestión organizada de la información de los pacientes**, garantizando la privacidad, seguridad y confidencialidad de sus datos personales.

---

## 🎯 Problema y objetivo

| Campo | Detalle |
|---|---|
| **Problema o necesidad** | Dificultad para gestionar citas médicas y organizar la información de los pacientes. |
| **Objetivo del sistema** | Facilitar la gestión de citas, historiales clínicos y recetas médicas mediante una plataforma digital segura. |

---

## 👥 Usuarios del sistema

| Usuario | Funciones |
|---|---|
| 🧑‍🦱 **Pacientes** | Registrarse, iniciar sesión, reservar citas médicas y consultar su información médica. |
| 🩺 **Médicos** | Consultar historiales clínicos, registrar consultas y generar recetas médicas electrónicas. |
| 🛠️ **Administradores** | Gestionar los usuarios y supervisar el funcionamiento de la plataforma. |

---

## ✅ Requisitos funcionales (RF)

| Código | Requisito funcional |
|:---:|---|
| **RF01** | El sistema debe permitir a los pacientes registrarse e iniciar sesión mediante sus credenciales. |
| **RF02** | El sistema debe permitir a los pacientes reservar citas médicas en línea, seleccionando fecha y horario disponibles. |
| **RF03** | El sistema debe permitir a los médicos registrar y consultar el historial clínico digital de los pacientes. |

---

## ⚙️ Requisitos no funcionales (RNF)

Los requisitos no funcionales establecen las condiciones de calidad y funcionamiento del sistema.

| Código | Requisito no funcional |
|:---:|---|
| **RNF01** | **Seguridad:** el sistema debe garantizar la seguridad y confidencialidad de la información médica, evitando que personas no autorizadas accedan a los datos de los pacientes. |
| **RNF02** | **Usabilidad:** el sistema debe ofrecer una interfaz fácil de utilizar, permitiendo que pacientes y personal médico realicen sus actividades de manera sencilla. |

---

## 🧪 Casos de prueba

### CP1 — Registro e inicio de sesión (RF01)

| Campo | Descripción |
|---|---|
| **Objetivo** | Comprobar que los pacientes puedan ingresar al sistema utilizando sus credenciales. |
| **Procedimiento** | 1. Registrar un paciente con sus datos personales, usuario y contraseña.<br>2. Iniciar sesión con las credenciales registradas. |
| **Resultado esperado** | El sistema permite el registro y el acceso correcto del paciente. |
| **Criterio de aceptación** | La prueba es satisfactoria si el paciente puede registrarse e iniciar sesión sin errores. |

### CP2 — Reserva de citas médicas (RF02)

| Campo | Descripción |
|---|---|
| **Objetivo** | Verificar que los pacientes puedan reservar citas médicas en línea. |
| **Procedimiento** | 1. Iniciar sesión.<br>2. Seleccionar una fecha y un horario disponible.<br>3. Confirmar la reserva. |
| **Resultado esperado** | El sistema registra la cita y muestra un mensaje de confirmación al paciente. |
| **Criterio de aceptación** | La prueba es satisfactoria si la cita queda registrada correctamente y el horario seleccionado deja de aparecer como disponible. |

### CP3 — Historial clínico digital (RF03)

| Campo | Descripción |
|---|---|
| **Objetivo** | Comprobar que los médicos puedan registrar y consultar la información clínica de los pacientes. |
| **Procedimiento** | 1. Iniciar sesión como médico.<br>2. Seleccionar un paciente.<br>3. Registrar una consulta médica.<br>4. Consultar su historial clínico. |
| **Resultado esperado** | El sistema guarda la información de la consulta y la muestra correctamente en el historial del paciente. |
| **Criterio de aceptación** | La prueba es satisfactoria si los datos registrados se almacenan y pueden consultarse sin errores. |

---

## 📏 Criterios de aceptación

Una prueba se considera **satisfactoria** cuando el sistema realiza la acción solicitada, muestra los resultados esperados y no presenta errores durante su ejecución. Para evaluarlo se usan estos criterios:

- ✔️ **Correcto funcionamiento:** la funcionalidad ejecuta la acción solicitada sin errores.
- ✔️ **Exactitud de la información:** los datos ingresados se guardan y muestran correctamente.
- ✔️ **Cumplimiento del requisito:** el sistema realiza lo establecido en cada requisito funcional.
- ✔️ **Seguridad de la información:** los datos médicos solamente pueden ser consultados por usuarios autorizados.

---

## 👨‍💻 Equipo de trabajo

**Grupo 3** · 8 integrantes

- Angel Alexis Arreaga Ortega
- Joselyne Nicol Chiriguaya Romero
- Julia Aracelli Chavez Vasquez
- Raquel Miroslaba Cabrera Bajaña
- Alan Josue Garcia Zambrano
- Daniel Francisco Chiriguaya
- Brianna Amelia Chulde
- Erick Joan Rugel Arteaga

---

## 🎓 Información académica

| Campo | Detalle |
|---|---|
| **Facultad** | Facultad de Ciencias e Ingeniería |
| **Carrera** | Ingeniería de Software |
| **Asignatura** | Introducción a la Ingeniería del Software |
| **Docente** | Jorge Dumar Guevara Serrano |
| **Fecha de entrega** | 4 de octubre de 2026 |
| **Periodo** | Agosto 2026 – Diciembre 2026 |
| **Lugar** | Daule – Ecuador |
