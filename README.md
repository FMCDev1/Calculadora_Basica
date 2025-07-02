# 📝 Calculadora Básica 1

Proyecto sencillo de una calculadora básica, con un fondo transparente y usando funciones de JavaScript para hacer operaciones básicas.
---
<br>


## 🚀 Tecnologías utilizadas

- HTML5, CSS3, JavaScript
- La lógica principal ha sido desarrollada mediante JavaScript y usando funciones para recolectar la información del DOM

<br>

## ⚙️ Mejoras futuras

-Crear un botón para poder pasar a oscuro la aplicación y los botones usando javaScript.

<br>

## 🔀 Diagrama de flujo

┌─────────────┐
│  BOTÓN CLICK │
└──────┬──────┘
       │
       ▼
┌────────────────────┐
│ Obtener texto pulsado │
└──────┬─────────────┘
       │
       ▼
┌─────────────────────────────┐
│ ¿Es "C"?                    │
├───────────────┬─────────────┤
│ SÍ            │ NO          │
▼               ▼             │
Resetear        ┌──────────────────────────────┐
pantalla,       │ ¿Es "←"?                     │
operacion,      ├───────────────┬──────────────┤
operador        │ SÍ            │ NO           │
                ▼               ▼              │
       Borrar último   ┌────────────────────────────┐
       carácter de     │ ¿Es "="?                   │
       operacion       ├───────────────┬────────────┤
                       │ SÍ            │ NO         │
                       ▼               ▼            │
          ┌──────────────────────────┐  ┌────────────────────────┐
          │ Intentar evaluar operacion│  │ ¿Es un operador? (+−×÷)│
          │ usando eval (try-catch)  │  ├─────────────┬──────────┤
          └─────────────┬────────────┘  │ SÍ          │ NO       │
                        │               ▼             ▼          │
       ┌────────────┐   │     Añadir operador a   Añadir número │
       │ Si OK:     │   │     operacion y pantalla  o "." a     │
       │ mostrar res│   │                          operacion    │
       │ y guardar  │   │                          y pantalla   │
       │ en operacion │  │                                      │
       │ Si error:  │   │                                      │
       │ mostrar    │   │                                      │
       │ "Error"    │   │                                      │
       └────────────┘   │                                      │
                        │                                      │
────────────────────────┘──────────────────────────────────────┘


<br>

## 📸 Capturas de pantalla

![image](https://github.com/user-attachments/assets/c3629dec-a693-470a-80f3-1113ab63f2cf)

<br>


## 👨‍🎓 Autor

**Nombre**: [Fabio Cuffaro Camara]  
**Curso**: Youtube     
**Año**: 2025
---
