# Usa una imagen base con herramientas básicas (ej: Ubuntu)
FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Instala SWI-Prolog y dependencias
RUN apt-get update && apt-get install -y \
    software-properties-common \
    && apt-add-repository -y ppa:swi-prolog/stable \
    && apt-get update \
    && apt-get install -y swi-prolog

# Opcional: Instala herramientas adicionales (ej: git, curl)
RUN apt-get install -y git curl