#Como instalar o Trivy

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
