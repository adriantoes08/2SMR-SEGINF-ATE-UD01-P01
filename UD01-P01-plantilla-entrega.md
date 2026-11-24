# Entrega Práctica UD01 · Auditoría y fortificación Clínica Dental Sonrisas

- **Nombre y apellidos del alumno/a:** Adrian Torres Escarramán
- **Grupo:** 2º SMR
- **Fecha de realización:** 24/11/2026

---

### Actividad 1 · Mecanismos y objetivos de la seguridad informática

| ID | Mecanismo | Objetivo principal (C, I, D, NR) | Física / Lógica | Activa / Pasiva | Justificación |
|:---|:---|:---:|:---:|:---:|:---|
| 1.1 | SAI servidor | D | Física | Pasiva | |
| 1.2 | Cifrado BitLocker |C | Lógica | Activa | |
| 1.3 | Cortafuegos perimetral | D| Lógica | Activa | |
| 1.4 | Copias de seguridad NAS | D| Lógica | Pasiva | |
| 1.5 | Antivirus corporativo |I | Lógica | Activa | |

---

### Actividad 2 · Cadena del incidente de seguridad

1. **Activos afectados:**
   - Activo 1: Los datos de los clientes
   - Activo 2: Y la suspencion de las citas de las siguientes semanas
2. **Amenaza:** Un atacante externo 
3. **Vulnerabilidad y clasificación:** El servicio de acceso remoto que no actualizaban desde hacia un año
4. **Riesgo previo:** Hay una posibilidad de que una persona mediante un exploit entre a su servidor web
5. **Ataque:** El atacante entra en la base de datos de los clientes se hace una copia y la borra
6. **Impacto:**
   - Impacto cuantitativo: Pérdidas económicas directas de 3.200€ en tratamientos cancelados
   - Impacto cualitativo: Los clientes se quejan de la cancelacion de las citas que tenian.

---

### Actividad 3 · Plan de contingencia

1. **Clasificación de medidas:**
   - Medida A: Plan de emergencia
   - Medida B: Plan de respaldo
   - Medida C: Plan de recuperación
   - Medida D: Plan de emergencia
   - Medida E: Plan de recuperación
   - Medida F: Plan de respaldo
2. **Diferencia entre plan de respaldo y plan de recuperación:** El plan de respaldo se hace antes del ataque y el plan de recuperación es despues del ataque

---

### Actividad 4 · Software malicioso y test de intrusión

#### 4.1. Diagnóstico de malware
- **Caso 1:**
  - Tipo de malware: Troyano 
  - Justificación (archivo anfitrión e intervención usuario): Se presenta como un archivo pdf, pero oculta una funcionalidad maliciosa (abrir una puerta trasera).
- **Caso 2:**
  - Tipo de malware: Gusano
  - Justificación (archivo anfitrión e intervención usuario): Se propaga de forma autónoma a través de la red, sin necesidad de un archivo anfitrión ni de intervención del usuario.
- **Medida preventiva para Caso 2:** Actualizar el firewall y tener todo en regla.

#### 4.2. Secuenciación de test de intrusión
- Secuencia ordenada cronológicamente (letras):
- Fases correspondientes:
  - Acción Z: Fase footprinting
  - Acción X: Fase fingerprinting
  - Acción W: Fase Busqueda de vulnerabilidad
  - Acción Y: Fase Parcheo

---

### Actividad 5 · Contraseñas e identificación digital

#### 5.1. Contraseñas
1. **Comparativa de seguridad frente a fuerza bruta:** 

La seguridad del sistema depende en gran medida de una buena elección de la contraseña y de su confidencialidad.

La fuerza bruta depende tanto de su longitud como de la variedad de caracteres empleados

2. **Política de contraseñas (3 reglas):**
   - Regla 1: Longitud de 8 o mas caracteres
   - Regla 2: Poner Mayúsculas, minúsculas, caracteres especiales.
   - Regla 3:Cambiarla cada cierto tiempo

#### 5.2. Identificación digital
3. **Mecanismos aplicados:**
   - Trámite A: Certificado digital
   - Trámite B: Firma electrónica
4. **Objetivo de seguridad garantizado y diferencia con usuario/contraseña:**