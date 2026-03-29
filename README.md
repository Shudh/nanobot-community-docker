# 🤖 Nanobot Community Docker Images

👋 **Hey there, fellow AI tinkerer!**

Love the awesome [HKUDS/nanobot](https://github.com/HKUDS/nanobot) project, but tired of watching your poor Raspberry Pi or $4 VPS cry every time you run `docker build`? You have come to the right place!

### 🤔 What is this?
This repository hosts **unofficial, pre-built Docker images** for the `nanobot` AI assistant. Every time there is a new stable release, GitHub Actions does the heavy lifting in the cloud so your local server does not have to.

### 💡 Why use this?
* **Instant Deployments:** Pulling an image takes seconds. Building one from source takes... well, enough time to question your life choices.
* **Coolify & Portainer Friendly:** Plug and play perfectly with modern container management tools.
* **Save your RAM:** Keep your server memory free for actually *running* the AI, not compiling it.

### 🚀 How to use it

You can pull the latest image directly from the GitHub Container Registry (GHCR):

```bash
docker pull ghcr.io/shudh/nanobot-community:latest
```

Or pin it to a specific release tag (e.g., `v0.1.4.post6`):
```bash
docker pull ghcr.io/shudh/nanobot-community:v0.1.4.post6
```

### ⚠️ The "Nice Guy" Disclaimer
I am just a huge fan of the project trying to help out the community! This is an **unofficial** image. All the actual brain-magic, code, and credit belongs to the brilliant folks at the [HKU Data Science Lab](https://github.com/HKUDS). If you love the bot, go give their repo a star! ⭐
