
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
----------------------------------------------

MIT License

Copyright (c) 2022 vidushidocker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
