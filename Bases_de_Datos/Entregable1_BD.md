# 📄 **Entregable 1 - Bases de Datos**

## ✅ **Formato del documento**

*   **Fuente:** Arial, tamaño 11-12 puntos
*   **Tamaño:** Carta
*   **Sin color ni imagen de fondo, sin marca de agua**
*   **Archivo:** Word o PDF
*   **Nombre del archivo:** `Vargas_Organista_Claudio_Alonso_E1`

***

## 🏷️ **Portada**

Debe incluir:

*   **Título del documento**
*   **Nombre del alumno:** *Vargas Organista Claudio Alonso*
*   **Materia:** *Gestión de Base de Datos*
*   **Profesor:** *María Consuelo Lourdes Alison*
*   **Fecha de entrega:** *Fecha actual*

***

## 📚 **Desarrollo**

### 🔍 **1. Identificación de archivos log**

*   Localiza al menos un archivo **log** de tu SGBD:
    *   **Oracle XE:** Archivos *redo log* o *alert log*
    *   **SQL Server Express:** Archivo de log de transacciones (`.ldf`)
    *   **MySQL:** *error log* o *binary log* (si está habilitado)
*   **Incluye:**
    *   📸 Captura de pantalla mostrando la ubicación o visualización del archivo
    *   ✍️ Explicación breve (2-3 renglones) sobre su utilidad

***

### 🔄 **2. Transacción completa en tu base de datos**

*   Usando las tablas creadas en la práctica de la semana 1, desarrolla una transacción que afecte al menos **dos tablas**.
*   **Ejemplos:**
    *   🛒 Venta de un producto (*Insertar en Ventas y DetalleVentas, actualizar Stock*)
    *   🎓 Inscripción de un alumno (*Insertar en Inscripción y Pagos*)
*   **Incluye:**
    *   `BEGIN TRANSACTION` (o equivalente)
    *   Al menos un `INSERT` y un `UPDATE` o `DELETE`
    *   Finalizar con `COMMIT` o `ROLLBACK`
    *   📸 Capturas: Código y resultado en tablas

***

### 💾 **3. Respaldo de la base de datos**

*   Realiza un respaldo lógico según tu SGBD:
    *   **Oracle XE:** `expdp` o `exp`
    *   **SQL Server Express:** Opción *backup* en SSMS o comando `BACKUP DATABASE`
    *   **MySQL:** `mysqldump` o exportación desde Workbench
*   **Incluye:**
    *   📸 Captura del respaldo generado (`.dmp`, `.bak`, `.sql`, etc.)
    *   ✍️ Explicación breve sobre el tipo de respaldo y su utilidad

***

## 📝 **Conclusiones**

*   Mínimo **150 palabras**
*   Reflexión personal demostrando lo aprendido
*   Redacción propia (sin plagio)

***

## 📖 **Citas y Referencias**

*   Fundamenta tus ideas con citas y referencias
*   Lista ordenada al final según **norma APA**

***

### ⚠️ **Notas importantes**

*   Fecha límite: **18 al 23 de noviembre**
*   Se revisará **redacción, ortografía y autenticidad**
*   Plagio o uso excesivo de IA = **calificación cero**
