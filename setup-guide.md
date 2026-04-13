# Guia de Setup — Email Automation con IA

## Descripcion
Secuencias de email automatizadas para nurturing de leads. Corre cada dia habil a las 9 AM, obtiene contactos activos del CRM, y envia emails personalizados segun el dia en la secuencia (Dia 1, 7, y 14).

## Pasos
1. Importar `workflow.json` en n8n
2. Configurar credencial de Email (SMTP o Gmail)
3. Configurar credencial de Zoho CRM con OAuth token
4. Reemplazar las variables con valores reales del cliente
5. Activar el workflow

## Variables Configuradas
| Variable | Valor |
|----------|-------|
| CLIENT_ID | ${CLIENT_ID} |
| CLIENT_NAME | ${CLIENT_NAME} |
| CLIENT_EMAIL | ${CLIENT_EMAIL} |

## Secuencia de Emails
| Dia | Tipo | Objetivo |
|-----|------|----------|
| 1 | Bienvenida | Presentar y generar confianza |
| 7 | Seguimiento | Caso de exito + agendar call |
| 14 | Ultimo contacto | Urgencia + oferta especial |

## Schedule
Lunes a viernes a las 9:00 AM.

## Soporte
contact@ai50m.com | ai50m.com
