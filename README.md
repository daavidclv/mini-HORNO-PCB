# 🔥 Mini Horno — Diseño de PCB en KiCad

Diseño completo de PCB para un mini horno, desde el esquemático hasta los ficheros de fabricación (Gerbers).

## 📋 Descripción

Proyecto de diseño electrónico centrado en la placa de control de un mini horno: esquemático, layout, y generación de todos los archivos necesarios para su fabricación (Gerbers y taladros). Incluye la PCB ya fabricada y montada.

## 🛠️ Stack técnico

- **Diseño de PCB:** KiCad (esquemático + layout)
- **Fabricación:** Gerbers (RS-274X) + ficheros de taladro (PTH/NPTH)

## 📁 Estructura del repositorio

- `Horno.kicad_pro` / `Horno.kicad_sch` / `Horno.kicad_pcb` — proyecto KiCad completo (esquemático + layout)
- `Horno-*.gbr` — Gerbers de cada capa (cobre, máscara, pasta, serigrafía, corte)
- `Horno-PTH.drl` / `Horno-NPTH.drl` — ficheros de taladro
- `HornoGBR.zip` — paquete de fabricación listo para enviar al fabricante de PCBs

## 📸 Resultado

![PCB del mini horno montada](./WhatsApp%20Image%202025-05-19%20at%2021.27.21.jpeg)
![Detalle de la PCB](./WhatsApp%20Image%202025-05-19%20at%2021.27.34.jpeg)

## 🎯 Lo más complejo del proyecto

- Diseño del layout considerando disipación térmica y separación de pistas de potencia
- Preparación del paquete completo de fabricación (Gerbers + taladros) sin errores de DRC

## 👤 Autor

David Calvo Heredero — [LinkedIn](https://www.linkedin.com/in/david-calvo-heredero-20b20a33a) · [GitHub](https://github.com/daavidclv)
