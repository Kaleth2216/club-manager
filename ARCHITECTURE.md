# Arquitectura del Proyecto Club Manager

## Niveles de ambiente
- develop → entorno de desarrollo
- qa → entorno de pruebas
- main(prod) → entorno de producción

## Arquitectura (Microservicios)
El sistema está estructurado bajo el enfoque de microservicios [reactive/events].

## Módulos principales
1. Security → Autenticación y gestión de roles
2. Members → Administración de miembros del club
3. Events → Gestión de eventos y asistencia
4. Finance → Control de ingresos y egresos
5. Reports → Generación de reportes
6. Shared → Recursos compartidos entre servicios

## Repositorios por módulo
Cada módulo incluye:
- docs
- api
- portal
- app
- db
- refactory

## Flujo de trabajo
develop → qa → main(prod)

