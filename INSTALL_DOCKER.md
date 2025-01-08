
---

### **INSTALL_DOCKER.md**
```markdown
# Instalação do Docker no Ubuntu

Este guia explica como instalar o Docker Desktop no Ubuntu.

---

## Passo 1: Configurar o Repositório APT do Docker

1. Acesse o link da [documentação oficial do Docker](https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository).
2. Siga os passos para adicionar o repositório `apt` ao seu sistema.

---

## Passo 2: Instalar o Docker

1. Atualize a lista de pacotes:
    ```bash
    sudo apt-get update
    ```

2. Instale o Docker Community Edition:
    ```bash
    sudo apt install docker-ce
    ```

3. Verifique a instalação:
    ```bash
    docker --version
    ```

---

## Passo 3: Configurar o Serviço Docker

Inicie o serviço Docker e configure-o para iniciar automaticamente:
```bash
sudo systemctl start docker
sudo systemctl enable docker
