# Docker e Astronomer CLI no Ubuntu

Este repositório contém guias e scripts para instalar e configurar o Docker e o Astronomer CLI no Ubuntu.

---

## Conteúdo

- [Guia de Instalação do Docker](INSTALL_DOCKER.md)
- [Guia de Instalação do Astronomer CLI](INSTALL_ASTRONOMER.md)
- [Automação com Script](SCRIPT_USAGE.md)

---

## Estrutura do Repositório

```plaintext
📂 docker-astronomer-setup
├── README.md           # Este arquivo
├── INSTALL_DOCKER.md   # Guia detalhado para instalação do Docker
├── INSTALL_ASTRONOMER.md # Guia detalhado para instalação do Astronomer CLI
└── SCRIPT_USAGE.md     # Instruções para uso do script de automação

## Passos Rápidos

### Passo 1: Clonar o Repositório
Clone este repositório para sua máquina:
```bash
git clone https://github.com/seu-usuario/docker-astronomer-setup.git
cd docker-astronomer-setup

### Passo 2: Dar Permissões de Execução ao Script
Dê permissão para o script ser executado:
```bash
chmod +x setup.sh

### Passo 3: Executar o Script
Execute o script para automatizar a instalação:
```bash
./setup.sh
