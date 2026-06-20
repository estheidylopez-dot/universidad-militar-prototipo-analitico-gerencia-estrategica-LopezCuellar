## Contexto de la Hipótesis

| Columna | Valor |
|---|---|
| Causa | Debilidades en conocimientos técnicos y estratégicos en ERP y transformación digital |
| Fase DT origen (E/D/I) | Definir |
| Insight de empatía | El usuario siente que la información se encuentra distribuida entre múltiples ERP y lo genera procesos manuales |
| Supuesto central | Si el equipo tecnológico fortalece sus conocimientos técnicos y estratégicos en integración ERP y transformación digital, entonces se mejorará la integración de la información. |
| Pregunta analítica | ¿Hasta qué punto el fortalecimiento de competencias técnicas y estratégicas del equipo tecnológico contribuye a mejorar la integración de la información? |

## Variables y Clasificación Analítica

| Variable | Tipo |
|---|---|
| porcentaje_integracion_erp | Outcome |
| horas_capacitacion_erp | Explic |
| nivel_conocimiento_transformacion_digital | Explic |
| reprocesos_operativos | Outcome |
| area_funcional | Segmento |
| proyecto_tecnologico | Segmento |
| tiempo_conciliacion_datos | Outcome |
| inconsistencias_informacion | Outcome |
| procesos_automatizados | Outcome |
| uso_excel_operativo | Outcome |
| antiguedad_colaborador | Control |
| cantidad_usuarios_erp | Control |
| complejidad_proceso | Control |
| sede | Segmento |
| tipo_area | Segmento |
| tipo_erp | Segmento |
| experiencia_integracion_erp | Explic |

## Diseño Analítico y Validación

| Columna | Valor |
|---|---|
| Cálculo / Transformación | `Xnorm=(X−Xmin)/(Xmax−Xmin)`<br>`0≤Xnorm≤1` |
| Métrica (nombre + fórmula) | **Índice de Integración Operativa Potenciada (IIOP)**<br>`(%IntegraciónERP+ProcesosAutomatizados)×(HorasCapacitación+NivelConocimiento+ExperienciaERP)` |
| Periodo / Segmento | Periodo de 4 a 7 Meses |
| Patrón esperado (si cierta) | entre 81 a 100 |
| Condición refutación | **entre 81 a 100** |
| Valor esperado para usuario/ciudadano | Los colaboradores percibirán una reducción en la carga operativa.<br>La compañía contará con una integración de información más eficiente. |
| Riesgo si falsa | La organización seguiría asumiendo altos costos operativos y reprocesos |
| Acción si confirma | Implementar capacitación técnica especializada, estandarización de procesos, automatización operativa y consolidación progresiva de la información en un único ecosistema ERP integrado. |
| Acción si refuta | No se ejecuta ningun proceso de Capacitación.<br>Se posterga plan de capacitación.<br>Se solicita al area de Tecnologia que construya planes de formación. |
| Experimento analítico mínimo (query + visual 1 línea) | Vacío |
| Estado (V/A/R) | Vacío |
