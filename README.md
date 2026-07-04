# Laboratorio-virtualbox-redes: Preparación y Configuración de Red en VirtualBox
# 1. Captura de la Configuración de Red
En esta imagen podemos ver el modo de red seleccionado para la VM:
Red Interna
# 2. Justificación Técnica
He seleccionado este modo porque el principal motivo es el aislamiento y seguridad del dispositivo. Al configurar una red interna estoy creando un entorno cerrado y aislado dentro de mi VirtualBox.
No uso el modo Puente (Bridge) ya que esto genera que la VM se conecte directamente al router de casa como si fuera un dispositivo fisico mas, y su usara dicho puente, dejaria de ser un entorno de laboratorio seguro . Cualquier tipo de prueba, error o ataque simulado podria impactar accidentalmente ante el propio host, router o cualquier otro dispositivo del hogar.
# 3. Captura del Administrador de Instantáneas (Snapshot)
En esta otra captura podemos ver mi primer snapshot generado llamado: Instalación base limpia
Snapshot Inst. Base Limpia

