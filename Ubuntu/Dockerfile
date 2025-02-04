# Usa la imagen oficial de Ubuntu
FROM ubuntu:latest

# Actualiza e instala algunas utilidades básicas
RUN apt-get update && apt-get install -y \
    curl \
    wget \
    vim \
    git \
    lsb-release \
    sudo \
    && rm -rf /var/lib/apt/lists/*

# Establece el directorio de trabajo
WORKDIR /workspace

# Exponer el puerto 80 (opcional si deseas servir algo)
EXPOSE 80

# Comando por defecto para mantener el contenedor corriendo
CMD ["bash"]
