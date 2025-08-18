# Unidad 3

## 🔎 Fase: Set + Seek


## Actividad 1
 ![Imagen de WhatsApp 2025-08-17 a las 21 44 20_c0fa170c](https://github.com/user-attachments/assets/1f10dca8-b34a-45d2-afb3-819625d8fe45)

## Actividad 2:
### Codigo de visuales 
``` js
const socket = io();

socket.on('connect', () => {
    console.log('Visuales conectadas');
});

socket.on('message', (data) => {
    console.log('Datos recibidos en visuales:', data);
});

socket.on('disconnect', () => {
    console.log('Visuales desconectadas');
});
```
### Codigo del nuevo mobile 
 ```js
// Conexión con el servidor usando Socket.IO
const socket = io();

// Cuando el cliente se conecta, envía datos simulados al servidor
socket.on('connect', () => {
    console.log('Connected to server');
    const controlData = {
        type: 'control',
        x: Math.random() * 100,
        y: Math.random() * 100,
        timestamp: Date.now()
    };
    socket.emit('message', controlData);
    console.log('Mobile sent:', controlData);
});
```
### Codigo del nuevo desktop
``` js
const socket = io();

socket.on('connect', () => {
    console.log('Mobile client connected');
    
    // Enviar un dato simple
    const data = {
        value: "test from pc"
    };
    socket.emit('message', data);
    console.log('Sent:', data);
});
```
