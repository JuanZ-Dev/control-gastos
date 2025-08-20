# 📝 Control de Gastos y Presupuestos 

Aplicación web moderna para gestionar gastos y presupuestos, desarrollada con **React**, **Vite** y **TypeScript**.  
Incluye **Context API** y **Reducer** para el manejo global del estado, **Custom Hooks** para lógica reutilizable, **TailwindCSS** para estilos y **LocalStorage** para persistencia de datos.

---

## Tecnologías principales

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Context API](https://img.shields.io/badge/Context%20API-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![LocalStorage](https://img.shields.io/badge/LocalStorage-FFCA28?style=for-the-badge&logo=googlechrome&logoColor=black)

---

## Funcionalidades clave

- **Visualización del presupuesto**
  - `react-circular-progressbar` para mostrar porcentaje gastado

- **Gestión de gastos**  
  - `react-swipeable-list` para deslizar y **eliminar** (izquierda) o **editar** (derecha)
  - `uuid` para generar IDs únicos
 
- **Ingreso y edición de gastos**
  - Modal con `@headlessui/react`
  - Icono de acción con `@heroicons/react`

- **Helpers personalizados**
  - Formatear cantidades en dólares
  - Formatear fechas en formato largo

- **Selección de fechas**  
  - `react-calendar` y `react-date-picker`

- **Persistencia de datos**  
  - Guardado automático en **LocalStorage**  

---

## Capturas de pantalla
- Modal para agregar/editar gastos
  ![Modal](https://github.com/user-attachments/assets/21fd73ac-c25c-456e-a930-18102acfa787)

- Lista con swipe actions
  ![Swipes](https://github.com/user-attachments/assets/b7cd7aae-1cbc-4a57-aa44-778828fa6554)

- Barra circular de progreso
![Barra_circular](https://github.com/user-attachments/assets/2a9fca97-48e0-4ed4-91bc-5cf88e5dc1fc)


---

## Instalación y uso
1. Clona el repositorio:
   
   ```bash
   git clone https://github.com/JuanZ-Dev/control-gastos.git
   ```
3. Entrar al directorio:
   
   ```bash
   cd control-gastos
   ```
4. Instalar dependencias:
   ```bash
   npm install
   ```
6. Ejecutar el proyecto:
   ```bash
   npm run dev
   ```
8. Abre en el navegador:
   ```bash
   http://localhost:5173
   ```

---

**Autor**

Juan Zapata Durand 🚀

[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JuanZ-Dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/juan-zapata-durand)
