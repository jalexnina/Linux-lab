# Reporte de Analisis de Logs

**Archivo analizado:** sample.log
**Fecha del analisis:** 2026-06-04 17:15:01
**Total de entradas:** 500

---

## 1. Top 10 Direcciones IP

| Solicitudes   | Direccion IP |
|---------------|--------------|
| 160 | 192.168.1.10 |
| 108 | 10.0.0.5 |
| 67 | 203.0.113.42 |
| 67 | 192.168.1.25 |
| 49 | 172.16.0.3 |
| 49 | 10.0.0.99 |

## 2. Distribucion por Severidad

| Nivel  | Cantidad  |
|--------|-----------|
| FATAL | 88 |
| ERROR | 95 |
| WARNING | 88 |
| INFO | 229 |

## 3. Eventos por Hora
|  Hora  |  Eventos  |
|--------|-----------|
| 00:00 | 25 |
| 01:00 | 29 |
| 02:00 | 26 |
| 03:00 | 20 |
| 04:00 | 24 |
| 05:00 | 16 |
| 06:00 | 18 |
| 07:00 | 16 |
| 08:00 | 17 |
| 09:00 | 19 |
| 10:00 | 15 |
| 11:00 | 22 |
| 12:00 | 18 |
| 13:00 | 18 |
| 14:00 | 22 |
| 15:00 | 17 |
| 16:00 | 11 |
| 17:00 | 20 |
| 18:00 | 17 |
| 19:00 | 29 |
| 20:00 | 13 |
| 21:00 | 23 |
| 22:00 | 36 |
| 23:00 | 29 |

## 4. Top 5 Mensajes de Error

|  Frecuencia  |  Mensaje  |
|--------------|-----------|
| 65 | Connection timeout after 30s |
| 51 | Authentication failed for user admin |
| 25 | Failed to write to disk |
| 22 | Database connection refused |
| 20 | Out of memory error in module X |

## 5. Resumen

- Sistema analizado con 500 eventos registrados
- 183 eventos requieren atencion (ERROR y FATAL)
- Analisis completado con herramientas UNIX estandar
