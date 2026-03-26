# Actividad_Comunicaci-nRedes

# 🌐 Actividad: Comunicación en Redes

---

## I. Conceptos Clave

| Concepto | Definición Simple | Nivel Técnico (Breve) | Ejemplo Real |
|----------|------------------|----------------------|--------------|
| **TCP** | Mensajería con confirmación de entrega. | Protocolo orientado a conexión y confiabilidad. | Enviar un email o archivo (no puede faltar nada). |
| **UDP** | Envío rápido sin esperar respuesta. | Protocolo sin conexión, prioriza velocidad. | Videollamada (si se pierde un frame, sigue). |
| **Puerto** | Las "puertas" numeradas de un edificio. | Punto lógico que identifica un proceso. | Puerto 80 (web), 22 (SSH). |
| **HTTP** | Lenguaje para pedir y enviar webs. | Protocolo de aplicación (Capa 7 OSI). | Escribir una URL en el navegador. |

---

### 🧠 Frase Clave

> "Para ver una web, usas HTTP, que viaja por TCP, entrando al servidor por un puerto."

---

## ⚙️ II. TCP vs UDP

### Respuestas

- **Diferencia principal:**
  - TCP asegura que los datos lleguen completos y en orden.
  - UDP envía datos sin verificar si llegaron.

- **¿Cuál es más confiable?**
  - TCP, porque confirma entrega y reenvía datos perdidos.

- **¿Cuál es más rápido?**
  - UDP, porque no espera confirmación.

---

### ⚡ Comparativa

| Protocolo | Característica | Analogía | Uso |
|----------|--------------|----------|-----|
| **TCP** | Confiabilidad | Llamada telefónica | Web, email, archivos |
| **UDP** | Velocidad | Megáfono | Streaming, juegos, videollamadas |

---

## 🚪 III. Puertos

### ¿Qué es un puerto?
Número lógico (0–65535) que permite identificar un proceso dentro de una máquina.

### ¿Por qué se necesita?
Para que el sistema sepa a qué aplicación enviar los datos.

---

### 🔑 Puertos Comunes

| Puerto | Servicio | Uso |
|--------|---------|-----|
| **80** | HTTP | Web sin seguridad |
| **443** | HTTPS | Web segura |
| **3000** | Desarrollo | Apps Node/React |
| **5432** | PostgreSQL | Base de datos |

---

## 🌐 IV. HTTP

### ¿Qué es HTTP?
Protocolo que permite la comunicación entre cliente y servidor en la web.

---

### 🔄 ¿Cómo funciona?

1. Cliente envía **Request**
2. Servidor procesa
3. Servidor responde (**Response**)

---

### 🛠️ Métodos HTTP

| Método | Acción | Ejemplo |
|--------|-------|--------|
| **GET** | Obtener | Ver datos |
| **POST** | Crear | Registrar usuario |
| **PUT** | Actualizar | Editar perfil |
| **DELETE** | Eliminar | Borrar datos |

---

## 💻 V. fetch("http://localhost:3000/api")

### ¿Qué pasa?

- **Protocolo:** HTTP (Capa 7) sobre TCP
- **Puerto:** 3000
- **Tipo:** Cliente-Servidor (Request-Response)
- **Naturaleza:** Asincrónica

---

## 🚨 VI. Debugging

### 1. Port already in use
- **Significa:** Puerto ocupado
- **Solución:** Cerrar proceso o cambiar puerto

---

### 2. Connection refused
- **Significa:** Nadie escucha en ese puerto
- **Solución:** Levantar servidor o corregir puerto

---

### 3. Timeout
- **Significa:** No hubo respuesta
- **Solución:** Revisar red, firewall o servidor

---

## 🌍 VII. Caso Práctico

### Problema: Frontend no conecta con Backend

- **Puerto:** Puede estar incorrecto
- **Protocolo:** HTTP vs HTTPS (CORS / Mixed Content)
- **Red:** Firewall o IP privada

---

## 🧠 ANALOGÍA FINAL

| Concepto | Analogía | Definición Técnica | Importancia |
|----------|----------|-------------------|------------|
| **TCP** | Llamada telefónica | Orientado a conexión | Datos completos |
| **UDP** | Mensaje sin confirmación | Sin conexión | Mayor velocidad |
| **Puerto** | Número de departamento | Identificador de proceso | Define dónde escucha la app |
| **HTTP** | Idioma | Protocolo de aplicación | Base de la web |

---

## 🚀 RESUMEN

- HTTP = Lenguaje  
- TCP = Transporte confiable  
- UDP = Transporte rápido  
- Puerto = Entrada a la app  

---
