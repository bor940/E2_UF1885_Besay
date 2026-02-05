# E2 UF1885 - Detección, análisis y resolución de incidencias (ERP-CRM)

**Alumno:** ojeda ruiz, besay  
**Fecha:** 2026-02-04  
**Entorno:** Ubuntu Server + Docker  
**Contenedores:** odoo-dev (CRM) | postgres-dev (BD)

---

## 1. Análisis inicial del sistema y parámetros de rendimiento
### 1.1 Servicios de acceso al CRM
- Descripción:
- Evidencias: evidencias/01_analisis/

### 1.2 Parámetros (CPU / RAM / Disco / Red) y relación con CRM+BD
- Conclusiones:

---

## 2. Monitorización de procesos y detección de sobrecarga
### 2.1 Proceso problemático detectado
- Proceso/servicio:
- Datos y justificación:
- Impacto en el CRM:

---

## 3. Resolución de una incidencia técnica simulada
### 3.1 Síntomas
  -los usuarios no pueden acceder al CRM
  -la url del servicio no respnde
### 3.2 Diagnóstico
  -verificar el estado de los contenedores (docker ps)
  -el cntenedor odoo-dev no seencuentra en ejecucion
### 3.3 Acción aplicada
  -se procede a restableer el servicio de contenedor, arrancando nuevamente
  -**sudo docker start odoo-dev**
### 3.4 Verificación
  -verificar estado del contenedor
  -**sudo docker ps**
### 3.5 Rollback
  -en esta situacion consiste en arrancar el contenedor como se inicia en la situacion anterior
---

## 4. Simulación de saturación del sistema (CPU o Memoria)
- Técnica utilizada:
- Datos capturados:
- Análisis:
- Verificación requisitos HW/SW:
- Registro:

---

## 5. Documentación y registro técnico
### 5.1 Incidencias detectadas / Acciones / Resultados
### 5.2 Interpretación de documentación en inglés (monitorización / rendimiento / administración CRM)
- Fragmento 1 (EN):
- Interpretación (ES):
- Fragmento 2 (EN):
- Interpretación (ES):
- Fragmento 3 (EN):
- Interpretación (ES):
