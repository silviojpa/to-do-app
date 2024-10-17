
# Plugin utilizados

1. Docker
- CloudBees Docker Build and Publish plugin
- Docker Compose Build Step Plugin
- Docker Pipeline
- docker-build-step
  
2. Dependency-Check Plugin
- OWASP Dependency-Check Plugin

3. Sonarqube
- SonarQube Scanner for Jenkins


# Como instalar o Trivy

1. Usando o Snap:
O Snap é um sistema de empacotamento universal para aplicações Linux. Ele facilita a instalação e atualização de aplicativos.

Bash
```
# Habilitar o snap (se ainda não estiver habilitado)
sudo apt install snapd
sudo systemctl enable --now snapd.socket

# Instalar o Trivy
sudo snap install trivy
Use o código com cuidado.
```
