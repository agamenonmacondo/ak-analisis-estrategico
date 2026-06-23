# A&K Datos Actualizados - Supabase Query Results
## Fecha: 2026-06-23

---

## QUERY 1: Ventas por mes (Ene-Jun 2026)

| Mes | Ventas (COP) | Cheques |
|-----|-------------|---------|
| 2026-01 | 676,380,989 | 2,524 |
| 2026-02 | 676,016,053 | 2,520 |
| 2026-03 | 759,953,570 | 2,513 |
| 2026-04 | 665,989,950 | 2,298 |
| 2026-05 | 782,317,935 | 2,560 |
| 2026-06 | 486,686,555 | 1,660 |

**Total Ene-Jun**: $4,047,345,052 | 14,075 cheques
**Ticket promedio**: $287,547

**Nota**: Junio está incompleto (datos hasta ~22 junio), por eso muestra menos ventas y cheques.

---

## QUERY 2: Ventas por hora del día (Junio 2026)

| Hora | Revenue (COP) | Cheques |
|------|--------------|---------|
| 0 | 9,451,500 | 53 |
| 1 | 4,673,000 | 21 |
| 2 | 196,000 | 1 |
| 9 | 1,030 | 1 |
| 10 | 1,343,560 | 7 |
| 11 | 3,948,500 | 4 |
| 12 | 19,676,445 | 63 |
| 13 | 24,349,310 | 94 |
| 14 | 28,462,540 | 78 |
| 15 | 18,828,765 | 65 |
| 16 | 10,957,235 | 56 |
| 17 | 32,677,720 | 104 |
| 18 | 58,542,030 | 161 |
| 19 | 118,831,935 | 284 |
| 20 | 88,510,750 | 271 |
| 21 | 35,621,085 | 183 |
| 22 | 20,459,300 | 122 |
| 23 | 10,155,850 | 92 |

**Pico**: Hora 19 (7pm) con $118.8M | Hora 20 (8pm) con $88.5M
**Horas valle**: 9am-11am casi sin actividad | 2am-8am sin ventas

---

## QUERY 3: Heatmap - Ventas por día de semana y hora (Junio 2026)

| Día | Hora | Revenue (COP) |
|-----|------|--------------|
| Lun | 12 | 2,245,270 |
| Lun | 13 | 4,862,000 |
| Lun | 14 | 1,477,250 |
| Lun | 15 | 2,626,080 |
| Lun | 16 | 762,000 |
| Lun | 17 | 2,829,500 |
| Lun | 18 | 3,971,000 |
| Lun | 19 | 7,071,500 |
| Lun | 20 | 1,827,000 |
| Lun | 21 | 111,500 |
| Mar | 9 | 1,030 |
| Mar | 12 | 4,382,000 |
| Mar | 13 | 948,000 |
| Mar | 14 | 824,000 |
| Mar | 15 | 885,000 |
| Mar | 16 | 1,026,230 |
| Mar | 17 | 616,000 |
| Mar | 18 | 5,769,070 |
| Mar | 19 | 3,055,000 |
| Mar | 20 | 2,637,000 |
| Mar | 21 | 1,347,500 |
| Mie | 12 | 1,203,000 |
| Mie | 13 | 1,745,090 |
| Mie | 14 | 1,234,690 |
| Mie | 15 | 832,000 |
| Mie | 16 | 991,500 |
| Mie | 17 | 12,118,500 |
| Mie | 18 | 13,023,085 |
| Mie | 19 | 13,774,170 |
| Mie | 20 | 8,760,000 |
| Mie | 21 | 5,037,110 |
| Mie | 22 | 3,764,870 |
| Mie | 23 | 2,583,000 |
| Jue | 0 | 1,477,000 |
| Jue | 1 | 257,000 |
| Jue | 2 | 196,000 |
| Jue | 11 | 3,569,000 |
| Jue | 12 | 2,918,875 |
| Jue | 13 | 2,417,750 |
| Jue | 14 | 977,250 |
| Jue | 15 | 991,500 |
| Jue | 16 | 168,000 |
| Jue | 17 | 2,948,470 |
| Jue | 18 | 17,519,800 |
| Jue | 19 | 24,632,125 |
| Jue | 20 | 16,951,545 |
| Jue | 21 | 4,303,770 |
| Jue | 22 | 1,781,020 |
| Jue | 23 | 595,350 |
| Vie | 0 | 19,000 |
| Vie | 10 | 728,000 |
| Vie | 11 | 225,500 |
| Vie | 12 | 2,738,880 |
| Vie | 13 | 3,114,000 |
| Vie | 14 | 15,248,350 |
| Vie | 15 | 3,371,875 |
| Vie | 16 | 3,318,225 |
| Vie | 17 | 4,690,000 |
| Vie | 18 | 6,271,875 |
| Vie | 19 | 36,557,230 |
| Vie | 20 | 32,023,920 |
| Vie | 21 | 14,181,160 |
| Vie | 22 | 7,725,110 |
| Vie | 23 | 4,437,000 |
| Sab | 0 | 3,806,500 |
| Sab | 1 | 1,235,000 |
| Sab | 12 | 2,864,000 |
| Sab | 13 | 4,746,000 |
| Sab | 14 | 3,169,000 |
| Sab | 15 | 6,727,750 |
| Sab | 16 | 2,801,000 |
| Sab | 17 | 4,632,750 |
| Sab | 18 | 6,050,200 |
| Sab | 19 | 22,415,750 |
| Sab | 20 | 22,089,785 |
| Sab | 21 | 9,213,495 |
| Sab | 22 | 5,697,710 |
| Sab | 23 | 2,540,500 |
| Dom | 0 | 4,149,000 |
| Dom | 1 | 3,181,000 |
| Dom | 10 | 615,560 |
| Dom | 11 | 154,000 |
| Dom | 12 | 3,324,420 |
| Dom | 13 | 6,516,470 |
| Dom | 14 | 5,532,000 |
| Dom | 15 | 3,394,560 |
| Dom | 16 | 1,890,280 |
| Dom | 17 | 4,842,500 |
| Dom | 18 | 5,937,000 |
| Dom | 19 | 11,326,160 |
| Dom | 20 | 4,221,500 |
| Dom | 21 | 1,426,550 |
| Dom | 22 | 1,490,590 |

---

## QUERY 4: Ventas por vendedor (staff) - Junio 2026 (Top 15)

| pos_staff_id | Ventas (COP) |
|-------------|-------------|
| 42 | 119,620,690 |
| 28 | 94,427,645 |
| 19 | 70,864,000 |
| 15 | 61,554,710 |
| 13 | 46,080,980 |
| 43 | 45,871,580 |
| 37 | 31,068,730 |
| 33 | 11,313,070 |
| 05 | 1,909,200 |
| 04 | 1,812,830 |
| 34 | 1,734,000 |
| 20 | 229,620 |
| 23 | 111,500 |
| 00 | 88,000 |

**Top 3 vendedores (42, 28, 19) concentran ~58.7% de las ventas de junio.**

---

## QUERY 5: Shift Assignments (Horas Extra Junio)

Se encontraron 16 schedules para semanas de junio (W21-W26).
50 registros de shift_assignments recuperados.

**Overtime assignments (is_overtime=true):**
| Schedule ID | Employee ID | Day | Shift | Est. Hours | Est. Cost |
|------------|------------|-----|-------|-----------|----------|
| 88cda7b4 (W21) | 9a6e5ac2 | 5 | P1 | 9.0 | 85,383 |
| 88cda7b4 (W21) | 9b4155c6 | 4 | P1 | 9.0 | 121,912 |
| 88cda7b4 (W21) | 662cc429 | 6 | P1 | 9.0 | 142,834 |
| 88cda7b4 (W21) | fd33694b | 4 | P1 | 9.0 | 85,383 |
| 88cda7b4 (W21) | 795243ce | 4 | P2 | 10.5 | 94,611 |

**Total estimated overtime cost (W21):** $530,123

**Shift codes observados:** A, C, CS, S, P1, P2, SX2, SX3, SX5, SX11, SX18, SX19, SX20, SX21, VAC, INCAPACI

---

## QUERY 6: Staff activo C75

| Nombre | Area | Cargo | Salario | Fijo | Líder |
|--------|------|-------|---------|------|-------|
| ALEJANDRO SEVILLA VELEZ | admin | ANALISTA DE DATOS | 1,750,905 | True | False |
| CINDY VIVIANA MUÑOZ HERNANDEZ | admin | AUXILIAR CONTABLE | 2,600,000 | True | False |
| JORGE ALFONSO PALACIO MALDONADO | admin | COMMUNITY MANAGER | 4,650,000 | True | False |
| EDILBERTO AGUILAR RAMIREZ | apoyo | SERVICIOS GENERALES | 1,750,905 | True | False |
| JAVIER JAMPIER DUQUE BUITRAGO | apoyo | INGENIERO DE SONIDO | 1,750,905 | True | False |
| MARIA CRISTINA ALFARO FONSECA | apoyo | SERVICIOS GENERALES | 1,750,905 | True | False |
| NATHALIA ANDREA GONZALEZ HENAO | apoyo | ASESOR COM VENTAS | 1,900,000 | True | False |
| SOFIA PEREZ SANCHEZ | apoyo | PASANTE ADMINISTRATIVA | 1,750,905 | True | False |
| ANGIE JULIETH RODRIGUEZ CUBILLOS | barra | AUXILIAR BAR | 1,750,905 | False | False |
| ASHLYE STEPHANIE TELLEZ VALDERRAMA | barra | JEFE BAR 50% PROPINAS | 1,750,905 | False | False |
| BRANDON ESTIVEN MEJIA OLAYA | barra | AUXILIAR BAR | 1,750,905 | False | False |
| LIZETH DAYANNA CASALLAS ORTIZ | barra | BARTENDER | 875,452 | False | False |
| MANUEL ALEJANDRO NORENA RENZA | barra | AUXILIAR BAR | 1,750,905 | False | False |
| WALTER VILLAMOROS RODRIGUEZ | barra | JEFE DE BAR | 3,000,000 | True | True |
| YOHAN FELIPE MORA ESCOBAR | barra | AUXILIAR BAR | 1,750,905 | False | False |
| AGAMENON MACONDO | cocina | CHEF EJECUTIVO | 1 | False | False |
| CARLOS STEVEN SUAREZ HERRERA | cocina | AUXILIAR DE COCINA | 1,750,905 | False | False |
| CLARA EDUVINA GONZALEZ GUTIERREZ | cocina | STEWARD | 1,750,905 | False | False |
| DUCIBETH ARIOLA PUSHAINA URIYU | cocina | STEWARD | 1,750,905 | False | False |
| ESNEIDER BLANCO CASTILLO | cocina | JEFE DE COCINA | 2,500,000 | True | True |
| IVAN FELIPE LARRAHONDO CARABALI | cocina | AUXILIAR DE COCINA | 1,750,905 | False | False |
| JUAN PABLO NARVAEZ REINOSO | cocina | AUXILIAR DE COCINA | 1,750,905 | False | False |
| LEIDY CATALINA ROZO MARTINEZ | cocina | PASANTE AUX COCINA | 1,750,905 | False | False |
| MAURICIO LAVERDE GUTIERREZ | cocina | AUXILIAR DE COCINA | 1,750,905 | False | False |
| NICOLAS DAVID CORRALES CASTILLO | cocina | PASANTE COCINA | 1,313,179 | False | False |
| NICOLAS STIVEN ALFARO FONSECA | cocina | AUXILIAR DE COCINA | 1,800,000 | False | False |
| OMAR DAVID RICO CABRA | cocina | AUXILIAR DE COCINA | 1,750,905 | False | False |
| RODRIGO ALBERTO PAZOS MUÑOZ | cocina | CHEF SUPERVISOR | 4,000,000 | True | True |
| WENDY VANNESA ALDANA CHILA | cocina | AUXILIAR DE COCINA | 1,750,905 | False | False |
| YOHANA ALEXI CRUZ PADUA | cocina | STEWARD | 1,750,905 | False | False |
| BRYAN ALBERTO SIERRA TORRES | servicio | MESERO | 1,750,905 | False | False |
| DAVID BENJAMIN CUBILLOS VARGAS | servicio | MESERO | 1,750,905 | False | False |
| GIOVANNY ALDAIR POMPEYO ORTIZ | servicio | MESERO | 1,750,905 | False | False |
| LEANIS CAROLINA AULAR BRACHO | servicio | MESERA | 1,750,905 | False | False |
| LEONARDO SUAREZ RODRIGUEZ | servicio | SUB JEFE SERVICIO | 1,923,500 | False | False |
| LESHLYE MICHELLE TELLEZ VALDERRAMA | servicio | CAJERA ADMINISTRATIVO | 1,750,905 | False | False |
| MARTIN EDUARDO ORREGO ROJAS | servicio | MESERO | 1,750,905 | False | False |
| MARTIN FERNANDO ORREGO DELGADO | servicio | MESERO | 1,750,905 | False | False |
| OSCAR ALBERTO MORENO MANCIPE | servicio | MESERO | 1,750,905 | False | False |
| RONAL FERNANDO ANZOLA CORREDOR | servicio | MESERO | 1,750,905 | False | False |
| VERONICA FRANCHESKA MEDINA MOLINA | servicio | JEFE DE SERVICIO | 2,750,000 | True | True |
| YELSON EDUARDO RUIZ ALMEIDA | servicio | MESERO | 1,750,905 | False | False |

**Total staff**: 41 personas
**Líderes**: 5 (Walter Villamoros/barra, Esneider Blanco/cocina, Rodrigo Pazos/cocina, Verónica Medina/servicio, +1 admin)
**Costo fijo**: 8 personas (admin + apoyo + líderes)
**Salario mínimo en nómina**: $875,452 (Bartender) - $1 (Chef Ejecutivo - likely error o contrato especial)

---

## QUERY 7: Shift Schedules Recientes

| ID | Week | Restaurant ID |
|----|------|---------------|
| db2b6860-2b1b-4c6b-842a-306f7137933b | 2026-W26 | a0000000-0000-0000-0000-000000000001 |
| 3cbfbd37-6f0a-42bf-9c18-9ab63a0bab47 | 2026-W26 | a0000000-0000-0000-0000-000000000001 |
| 5962d3d4-fcaf-471a-97a6-e6d5aeeebc2a | 2026-W26 | a0000000-0000-0000-0000-000000000001 |
| 406ffe3e-9ff1-4802-895f-afc21ad6657e | 2026-W25 | a0000000-0000-0000-0000-000000000001 |
| b64e672b-f4c5-4c8b-af46-aae2b7ade09b | 2026-W25 | a0000000-0000-0000-0000-000000000001 |
| da24654f-174c-4311-aa95-9083738fed6d | 2026-W25 | a0000000-0000-0000-0000-000000000001 |
| b2c2e178-e3aa-4b82-87dc-f338ecbbd9ba | 2026-W24 | a0000000-0000-0000-0000-000000000001 |
| acf17964-7c8d-4699-83d2-17d742350dc4 | 2026-W24 | a0000000-0000-0000-0000-000000000001 |
| ca9483ef-ab9b-4212-bd6a-1b60bcd08baa | 2026-W24 | a0000000-0000-0000-0000-000000000001 |
| ab3242a6-4c19-4087-b76e-09f9a6ce560b | 2026-W22 | a0000000-0000-0000-0000-000000000001 |

**Nota**: Se crean múltiples schedules por semana (probablemente uno por empleado o rol).