# AI Chat — GitHub Pages

App de chat con IA estilo Instagram DM. Un solo archivo HTML, sin dependencias.

## 🚀 Cómo subir a GitHub Pages (paso a paso)

### 1. Sube los archivos al repositorio

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

### 2. Activa GitHub Pages

1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (arriba a la derecha)
3. En el menú izquierdo, haz clic en **Pages**
4. En **Source**, selecciona **Deploy from a branch**
5. En **Branch**, selecciona `main` y carpeta `/ (root)`
6. Haz clic en **Save**

### 3. Espera ~1 minuto y accede en:
```
https://TU_USUARIO.github.io/TU_REPO/
```

---

## 📁 Estructura del repositorio

```
/
├── index.html    ← toda la app (HTML + CSS + JS)
└── README.md
```

---

## 🔑 API Keys

Las keys se guardan en `localStorage` del navegador (nunca salen del dispositivo).
Configúralas dentro de la app en **⚙️ → Modelos**.

| Proveedor | Dónde obtener la key | ¿Gratis? | ¿Funciona en GitHub Pages? |
|-----------|----------------------|----------|---------------------------|
| Groq | console.groq.com | ✅ Sí | ✅ Sí |
| Gemini | aistudio.google.com | ✅ Con límites | ✅ Sí |
| Claude | console.anthropic.com | 💳 De pago | ✅ Sí |
| OpenAI | platform.openai.com | 💳 De pago | ❌ Requiere proxy local |
| Grok | console.x.ai | 💳 De pago | ❌ Requiere proxy local |
| Mistral | console.mistral.ai | 💳 De pago | ❌ Requiere proxy local |

> **Recomendado desde GitHub Pages:** Groq (gratis y rápido) o Gemini (gratis con límites).
