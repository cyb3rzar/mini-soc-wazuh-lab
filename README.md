# Wazuh
# Laboratorio SOC – Implementación de Wazuh

## 📌 Descripción
Este laboratorio presenta la implementación del SIEM de Wazuh y su despliegue, para mostrar de forma sencilla como recopila los logs de las actividades

## 🎯 Objetivo
- Implementación de un SIEM.
- Aplicar configuración y despliegue de Wazuh
- Demostrar la recepción de logs del SIEM Wazuh.
  
## 🛠️ Herramientas utilizadas
- VirtualBOx
- Wazuh v4.12.0 OVA
- VM Windows 11

## 🔎 Pasos principales
1. Instalación y configuración de Wazuh OVA en VirtualBox.
2. Importación de logs de autenticación de Windows.
3. Creación de reglas de búsqueda para detectar intentos de login fallidos.
4. Configuración de alertas ante intentos repetidos.

## 📷 Evidencias
![Dashboard Splunk](imagenes/dashboard.png)

## ✅ Conclusiones
Con este laboratorio logré detectar intentos de fuerza bruta correlacionando eventos de login en Splunk. 
Aprendí a configurar reglas de búsqueda y alertas que pueden aplicarse en un entorno SOC real.
