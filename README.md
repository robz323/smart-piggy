# Smart Piggy - Don Jaimito 🤖💰

Un agente inteligente especializado en finanzas personales con personalidad mexicana cálida y empática.

## 🎭 Don Jaimito

Don Jaimito es un sabio anciano mexicano que ayuda a las personas a ahorrar dinero y construir mejores hábitos a través de la empatía, el humor y la experiencia de vida. Actúa como un amigo de confianza y un anciano que siempre cuida de los demás.

### 🌟 Características Principales

- **Personalidad:** Sabio anciano mexicano cálido y empático
- **Especialidad:** Finanzas personales y hábitos de ahorro
- **Estilo:** Casual, amigable, con toque mexicano
- **Enfoque:** Alcancías digitales (nunca usa "wallet")

### 💰 Funcionalidades

- **Estrategias de Ahorro:** Basadas en ingresos y hábitos de gasto
- **Hábitos Atómicos:** Promueve buenas prácticas de finanzas personales
- **Alcancías Digitales:** Enfoque en ahorro seguro y disciplinado
- **Soporte Emocional:** Actúa como amigo de confianza

## 🚀 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/robz323/smart-piggy.git
cd smart-piggy

# Instalar dependencias
bun install

# Configurar variables de entorno
cp .env.example .env
# Editar .env con tus API keys
```

## 🔧 Configuración

### Variables de Entorno Requeridas

```bash
# Model Provider (Requerido - elegir uno)
ANTHROPIC_API_KEY=tu-clave-anthropic
# o
OPENAI_API_KEY=tu-clave-openai

# Telegram (Opcional)
TELEGRAM_BOT_TOKEN=tu-token-telegram
```

## 🎯 Uso

### Modo Desarrollo
```bash
bun run dev
# o
elizaos dev
```

### Modo Producción
```bash
bun run start
# o
elizaos start
```

## 🏗️ Arquitectura

```
smart-piggy/
├── src/
│   ├── character.ts          # Personalidad de Don Jaimito
│   ├── index.ts             # Punto de entrada
│   └── plugin.ts            # Plugin personalizado
├── scripts/                 # Scripts de utilidad
└── tests/                   # Pruebas
```

## 🧪 Testing

```bash
# Ejecutar todas las pruebas
bun test

# Pruebas de componentes
bun run test:component

# Pruebas end-to-end
bun run test:e2e
```

## 📝 Características del Personaje

### 🎭 Personalidad
- **Nombre:** Don Jaimito
- **Origen:** Experto financiero en bancos prestigiosos
- **Música:** Cumbia, mariachi, bolero, Pedro Infante
- **Comida:** Tacos, enchiladas con queso extra

### 💡 Enfoque en Finanzas
- **Alcancías Digitales:** Nunca usa "wallet", siempre "alcancía digital"
- **Estrategias Personalizadas:** Basadas en ingresos y gastos
- **Hábitos Atómicos:** Promueve buenas prácticas
- **Comunidad:** Enfoque en ahorro grupal y confianza

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

## 🙏 Agradecimientos

- ElizaOS por el framework de agentes
- La comunidad mexicana por la inspiración cultural
- Todos los contribuidores que hacen este proyecto posible

---

**Don Jaimito dice:** *"Una alcancía digital es como guardar monedas bajo el colchón, pero más seguro que el Banco de México."* 🏦✨
