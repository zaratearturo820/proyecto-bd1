# NovaByte — Sistema de Gestión de Ventas de productos electrónicos

Proyecto integrador de Base de Datos I — FACENA (UNNE): base relacional en 3FN para una tienda física de artículos electrónicos (gestión de stock por producto, seguimiento de garantías, ventas de 1.N productos, precios pactados congelados), llevada hasta robustez con temas técnicos de etapa V.

## Etapas

| Etapa | Pregunta | Carpeta | Contenido | Estado |
|---|---|---|---|---|
| I. Requerimientos | ¿Qué necesita el negocio? | [docs/etapa-01/](docs/etapa-01/) | | |
| II. Modelado | ¿Cómo representamos la información? | [docs/etapa-02/](docs/etapa-02/) | | |
| III. Implementación | ¿Cómo construimos la BD? | [docs/etapa-03/](docs/etapa-03/) y [sql/ddl/](sql/ddl/) | | |
| IV. Consultas | ¿Cómo obtenemos información? | [docs/etapa-04/](docs/etapa-04/) y [sql/consultas/](sql/consultas/) | | |
| V. Temas técnicos | ¿Cómo la hacemos robusta? | [docs/etapa-05/](docs/etapa-05/) | | |

Documentos fuente por etapa:

- Etapa I:
- Etapa II:

## Estructura del repositorio

```
proyecto-bd1/
├── README.md
├── docs/               Documentación por etapa (de la I a la V)
│   ├── etapa-01/       Requerimientos y reglas de negocio
│   ├── etapa-02/       DER (Chen/ERDPlus) + modelo relacional 3FN
│   ├── etapa-03/       Documentación del DDL/DML
│   ├── etapa-04/       Documentación de las consultas
│   └── etapa-05/       Temas técnicos: 5 carpetas numeradas, un tema por carpeta
│       ├── 01-procedimientos-funciones/
│       ├── 02-transacciones/
│       ├── 03-triggers-auditoria/
│       ├── 04-seguridad/
│       └── 05-indices/
└── sql/
    ├── ddl/            DDL 
    ├── dml/            DML (lote de prueba)
```

## Cómo usar y reproducir

Requisitos: git, SQL Server Express 2016 SP1+ (o Docker), sqlcmd / SSMS.
