# 🛠 Guillotina Hidráulica Modular para Perfiles Steel Frame

Este repositorio documenta el desarrollo completo de una **herramienta de corte hidráulica modular** diseñada y construida durante mi Práctica Profesional Supervisada (PPS) en la empresa **AD Barbieri S.A.**, como parte de mi formación en la Facultad de Ingeniería de la Universidad Nacional de Lomas de Zamora.

## 🎯 Objetivos del Proyecto

- Diseñar una herramienta de corte con accionamiento hidráulico adaptable a diferentes medidas de perfiles.
- Permitir el intercambio rápido entre cabezales de corte y punzonado.
- Automatizar el proceso utilizando un **PLC Siemens LOGO! 8**.
- Optimizar la ergonomía, seguridad y eficiencia del equipo.
- Validar el diseño en condiciones reales de producción.

## 🧰 Descripción General del Proyecto

La herramienta está compuesta por:
- Un **módulo base** estructural con guías.
- Un **cabezal de corte** y un **cabezal de punzonado**, intercambiables en menos de 3 minutos.
- Un **sistema hidráulico** de 8006 kgf de fuerza, con motor monofásico, bomba de engranajes y válvulas controladas eléctricamente.
- Automatización mediante **PLC LOGO! 8** con control de secuencia, luces indicadoras y lógica de stand-by.

## ⚙️ Especificaciones Técnicas

| Componente                    | Descripción                                         |
|------------------------------|-----------------------------------------------------|
| Cilindro hidráulico          | Ø100 mm, carrera 100 mm, doble efecto              |
| Motor                        | 1 HP, monofásico, 1450 RPM                          |
| Presión de trabajo           | 90 bar                                              |
| Fuerza máxima generada       | ~8000 kgf                                           |
| PLC                          | Siemens LOGO! 8 (modelo 6ED1052-1HB08-0BA0)         |
| Cuchilla / Punzón            | Acero AISI D6 tratado térmicamente                 |
| Estructura                   | Perfiles estructurales + chapa 1 mm cortada por láser |
| Seguridad                    | Botón de parada de emergencia, recubrimiento completo, sin elementos rotativos expuestos |

## 💻 Automatización

El PLC gestiona:
- Activación del ciclo (avance del cilindro)
- Detección de fin de carrera
- Temporización y retorno automático
- Stand-by automático tras inactividad
- Interfaz simple y segura para el operario

## 🔒 Seguridad y Ergonomía

- Sin chispas ni discos abrasivos
- Bajo nivel de ruido
- Fácil mantenimiento
- Panel de control frontal con pulsadores industriales

## 🖼 Anexos

- Planos técnicos 2D de la herramienta y cabezales
- Esquema hidráulico
- Diagrama lógico del PLC (parcial adjunto)

## 🏭 Empresa

**AD Barbieri S.A.**  
Burzaco, Buenos Aires, Argentina  
Fabricación de perfiles metálicos y plásticos para construcción en seco

## 👤 Autor

**Nicolás Barcia**  
Alumno de Ingeniería – UNLZ  
Tutor institucional: Ing. Ezequiel Panattoni  
Tutor académico: Ing. Cristian Lukaszewicz

---

> Proyecto realizado íntegramente en contexto real de planta industrial, integrando diseño mecánico, hidráulica, automatización y trabajo en equipo interdisciplinario.
