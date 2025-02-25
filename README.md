# PortSwigger OS Command Injection, Simple Case

Solución automatizada en Python para el laboratorio de PortSwigger "OS command injection, simple case". Este script explota una vulnerabilidad de inyección de comandos para ejecutar `whoami` y obtener el nombre del usuario actual.

## Requisitos
- Python 3.x
- Dependencia: `requests` (instala con `pip install -r requirements.txt`)

## Uso
1. Clona el repositorio:
   ```bash
   git clone https://github.com/[tu_usuario]/PortSwigger-OS-Command-Injection.git
   cd PortSwigger-OS-Command-Injection

   ## Uso
2. Crea y activa un entorno virtual:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ## Uso
3. Instala dependencia:
   ```bash
   pip install -r requirements/txt
   ## Uso
4. Edita exploit.py con tu ID de laboratorio en base_url.

5. Ejecuta:
   ```bash
   python exploit.py

