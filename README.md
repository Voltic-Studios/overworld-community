# 🌍 OverworldCM Roleplay - FiveM

¡Bienvenido al repositorio oficial de Overworld Community! Este proyecto está diseñado para ofrecer una experiencia de roleplay inmersiva en GTA V a través de la plataforma FiveM. Aquí encontrarás información sobre los sistemas en desarrollo, incluyendo el **Voltic-Hud** y **Voltic-Inventory**.

---

## 🚀 Características principales del servidor

1. **Experiencia Inmersiva**: Diseñado para una narrativa rica y realista.
2. **Scripts Personalizados**:
   - **[Voltic-Hud](https://github.com/Voltic-Studios/Voltic-Hud)**: HUD dinámico e intuitivo que mejora la interfaz del jugador.
   - **[Voltic-Inventory](https://github.com/Voltic-Studios/voltic-inventory)**: Sistema de inventario avanzado para una interacción fluida con objetos y equipos.
3. **Comunidades Activas**: Fomentamos la creatividad y el respeto en el roleplay.

---

## 📂 Repositorios clave

### Voltic-Hud
El **Voltic-Hud** es un HUD personalizable y minimalista. Está diseñado para mostrar información relevante como salud, armadura, hambre, sed, y más, sin abrumar al jugador con datos innecesarios.

#### Estado del proyecto:
🚧 **En desarrollo avanzado**  
- ✅ Visualización de parámetros básicos (vida, hambre, sed).  
- ✅ Diseño minimalista.  
- ⏳ Configuración por comandos y soporte multi-idioma.  

#### Planes futuros:
- Adición de personalización visual en tiempo real.  
- Indicadores dinámicos para estados especiales (ejemplo: lesiones, efectos de estado).  

---

### Voltic-Inventory
El **Voltic-Inventory** es un sistema de inventario único que utiliza un enfoque gráfico para gestionar objetos y equipos de manera sencilla y funcional.

#### Estado del proyecto:
🚧 **En desarrollo avanzado**  
- ✅ Sistema drag-and-drop básico implementado.  
- ✅ Gestión de objetos con categorías.  
- ⏳ Integración con cofres, vehículos y NPCs.  

#### Planes futuros:
- Compatibilidad con tiendas y comercio entre jugadores.  
- Gestión de inventarios en tiempo real desde dispositivos móviles (ingame).  

---

## 📋 Requisitos

- **FiveM** (última versión recomendada).  
- **MySQL/MariaDB** para almacenar datos persistentes.  
- **ESX/Standalone**: Estos scripts pueden adaptarse a ambos entornos con configuraciones mínimas.  

---

## 📖 Instalación

### 1. Clona el repositorio
```bash
git clone https://github.com/[TuUsuario]/[TuRepositorio].git
```

### 2. Configura los scripts
Cada script tiene su propia carpeta y archivo de configuración (`config.lua`).
Configura las credenciales de tu base de datos (si aplica).
Ajusta los parámetros de cada script según las necesidades de tu servidor.
### 3. Añade los scripts al `server.cfg`
En tu archivo `server.cfg`, añade:

```ruby
ensure Voltic-Hud
ensure Voltic-Inventory
```
### 4. Reinicia tu servidor
Ejecuta el comando de reinicio en la consola o reinicia manualmente.

### 📧 Contacto
Si tienes preguntas o necesitas ayuda, no dudes en contactarnos:
- Discord: [Overworld Community](https://discord.overworld.es)
- Email: [info@overworld.es](mailto:info@overworld.es)

### 🛠️ Créditos
Desarrolladores: [@UnaiMedina](https://github.com/unaimedina), [@Joordih](https://github.com/joordih) y colaboradores.

### Cambios realizados:
- Se cerraron las secciones correctamente.  
- Se revisaron las listas y el formato de los encabezados.  
- Se mantuvo una estructura clara y uniforme.
