# SI · UT2 — Ficha de taller: montaje y revisión de un ordenador

## 1. Orden de trabajo

**Fecha:** 16/11/2026  
**Puesto:** ____________________  
**Equipo / etiqueta:** ____________________

**Integrantes del grupo:**

1. Caleb Martín Cepero.
2. Daniel Prades.

> **Equipo A:** ordenador de prácticas utilizado para el montaje o la revisión. Puede estar averiado; no se exige que arranque.
>
> **Equipo B:** vuestro propio ordenador funcional. Se utiliza a partir del apartado 9 para analizar el arranque y el hardware desde Linux.

## 2. Recepción e inspección visual · Equipo A

**Trabajo previsto:**

- [x] Desmontaje y montaje
- [x] Revisión / diagnóstico
- [ ] Otro: ___________________________________

**Estado al recibirlo:**

- [x] Completo
- [ ] Faltan piezas
- [ ] Sucio
- [ ] Daños visibles

**Síntomas conocidos, piezas ausentes o daños observados:**

La ficha de recepción indica que el equipo estaba completo. Durante la revisión se observó un cable SATA doblado (apartado 5).

**Estado inicial del equipo**

![Caja del equipo con la tapa puesta antes del desmontaje](images/montaje-01-caja-estado-inicial.jpeg)

**Panel trasero y puertos**

![Puertos traseros y entrada de alimentación sin cables conectados](images/montaje-02-panel-trasero.jpeg)

## 3. Seguridad y preparación · Equipo A

- [x] Equipo desconectado de la corriente y de los periféricos.
- [x] Botón de encendido pulsado tras desconectar.
- [x] Superficie despejada y piezas organizadas.
- [x] Estado inicial y conexiones fotografiados.

**Herramientas utilizadas:** Destornillador.

**No abráis la fuente ni forcéis piezas.** Ante daños o baterías, avisad al profesor.

**Interior al abrir la caja**

![Interior al retirar la tapa, con la placa, el disco, la fuente y el cableado en su posición inicial](images/montaje-03-interior-al-abrir.jpeg)

**Ficha en papel de los apartados 1–3**

![Página 1 de la ficha: orden de trabajo, recepción y seguridad](images/01-entrada-y-preparacion.jpeg)

## 4. Componentes identificados · Equipo A

| Componente | Marca / modelo | Dato observado |
|---|---|---|
| Placa base | Gigabyte GA-B85M-DS3H | Ranuras PCIe y conectores SATA. |
| Procesador | Intel Celeron G1840 | 2,80 GHz, grabados en el procesador. |
| RAM | Crucial | Un módulo de 2 GB DDR3. |
| Almacenamiento | Western Digital WD Blue WD5000AAKX | Disco duro SATA de 500 GB. |
| Fuente | Power Man IP-S300EF7-2 H | Potencia de salida de 300 W, según la etiqueta. |
| Disipador / ventilador | Intel de serie | Disipador con ventilador y cuatro anclajes. |
| Tarjetas / otros | No identificadas | Las ranuras PCIe se ven vacías en la foto de la placa. |

**Placa base y ranuras de expansión**

![Detalle del modelo GA-B85M-DS3H impreso en la placa, junto a la ranura PCIe](images/montaje-04-modelo-placa-y-ranura-pcie.jpeg)

**Fuente de alimentación**

![Etiqueta de la fuente Power Man de 300 W](images/montaje-05-etiqueta-fuente-300w.jpeg)

**Procesador**

![Detalle del modelo Intel Celeron G1840 grabado en el procesador](images/montaje-06-modelo-procesador-celeron.jpeg)

## 5. Conexiones y observaciones · Equipo A

Conexiones presentes y comprobadas:

- [x] Alimentación de la placa
- [x] Alimentación de la CPU
- [x] Ventilador de la CPU
- [x] Datos de almacenamiento
- [x] Alimentación del disco
- [x] Panel frontal

**¿Hay algún cable suelto, conector dañado o conexión que no sepáis identificar?**

Cable SATA doblado.

**Fotografías de referencia (nombre de archivo o ubicación):**

![Conector SATA de datos junto al disco duro WD Blue](images/montaje-07-conector-sata-del-disco.jpeg)

**Detalle de las conexiones en la placa**

![Conexiones SATA, USB internos y panel frontal en la placa base](images/montaje-08-conexiones-en-la-placa.jpeg)

No retiréis la CPU ni el disipador sin indicación del profesor. Si se retira el disipador, consultad sobre limpieza y pasta térmica antes de volver a instalarlo.

**Ficha en papel de los apartados 4–5**

![Página 2 de la ficha: componentes identificados y conexiones comprobadas](images/02-inventario-y-conexiones.jpeg)

## 6. Registro del trabajo · Equipo A

| Operación | Hecho | N/P | Foto / observaciones |
|---|:---:|:---:|---|
| Apertura y fotos iniciales | ☒ | ☐ | [Interior al abrir](images/montaje-03-interior-al-abrir.jpeg) |
| Desconexión y organización de cables | ☒ | ☐ | [Chasis sin la placa](images/montaje-10-chasis-sin-placa-base.jpeg) y [cableado frontal](images/montaje-13-cableado-del-panel-frontal.jpeg) |
| Desmontaje / montaje de memoria | ☒ | ☐ | [Ranuras DIMM vacías](images/montaje-11-procesador-sin-disipador-y-ram-retirada.jpeg) y [RAM reinstalada](images/montaje-19-placa-y-ram-reinstaladas.jpeg) |
| Revisión / montaje de almacenamiento | ☒ | ☐ | [Soporte del disco retirado](images/montaje-14-soporte-del-disco-retirado.jpeg) y [disco en el chasis](images/montaje-18-disco-y-fuente-en-el-chasis.jpeg) |
| CPU y disipador, si se autoriza | ☒ | ☐ | [Procesador al descubierto](images/montaje-11-procesador-sin-disipador-y-ram-retirada.jpeg) y [colocación del disipador](images/montaje-17-colocacion-del-disipador.jpeg) |
| Tarjetas de expansión | ☒ | ☐ | [Detalle de la ranura PCIe](images/montaje-04-modelo-placa-y-ranura-pcie.jpeg) |
| Reconexión y orden de cables | ☒ | ☐ | [Reconexión de la placa y el panel frontal](images/montaje-20-reconexion-de-placa-y-panel-frontal.jpeg) |
| Cierre y limpieza del puesto | ☒ | ☐ | [Interior antes del cierre](images/montaje-21-interior-antes-del-cierre.jpeg) |

### Desmontaje

**Placa base retirada**

![Placa base fuera del chasis, con el módulo Crucial y el disipador Intel todavía instalados](images/montaje-09-placa-retirada-con-ram-y-disipador.jpeg)

**Chasis sin la placa base**

![Chasis con los cables desconectados de la placa, la fuente y el disco todavía dentro](images/montaje-10-chasis-sin-placa-base.jpeg)

**Procesador y ranuras de memoria**

![Procesador en el zócalo con restos de pasta térmica, disipador retirado y ranuras de RAM vacías](images/montaje-11-procesador-sin-disipador-y-ram-retirada.jpeg)

**Puertos frontales y soporte de unidades**

![Vista frontal sin el embellecedor, con los puertos USB y de audio y el soporte del disco a la vista](images/montaje-12-puertos-y-soporte-frontales.jpeg)

**Cableado del panel frontal**

![Cables del panel frontal dentro del chasis, desconectados de la placa base](images/montaje-13-cableado-del-panel-frontal.jpeg)

**Soporte del disco retirado**

![Soporte extraído del chasis con el disco WD Blue de 500 GB todavía sujeto](images/montaje-14-soporte-del-disco-retirado.jpeg)

**Componentes desmontados**

![Chasis con la placa base, la RAM, el disipador, el disco duro y la fuente separados sobre la mesa](images/montaje-15-componentes-desmontados.jpeg)

### Montaje y reconexión

**Pasta térmica en el procesador**

![Procesador con pasta térmica visible antes de colocar el disipador](images/montaje-16-pasta-termica-en-el-procesador.jpeg)

**Colocación del disipador**

![Disipador Intel colocado sobre el procesador con la placa todavía fuera del chasis](images/montaje-17-colocacion-del-disipador.jpeg)

**Disco y fuente en el chasis**

![Disco en su soporte y fuente en el chasis, con el espacio para la placa y los conectores a la vista](images/montaje-18-disco-y-fuente-en-el-chasis.jpeg)

**Placa base y memoria reinstaladas**

![Placa base, módulo de RAM y disipador colocados en el chasis, con la alimentación principal aún sin conectar](images/montaje-19-placa-y-ram-reinstaladas.jpeg)

**Reconexión de la placa y del panel frontal**

![Alimentación de la placa y la CPU conectadas, con los cables del panel frontal encaminados hacia sus conectores](images/montaje-20-reconexion-de-placa-y-panel-frontal.jpeg)

## 7. Incidencia o reparación · Equipo A

**Problema encontrado / hipótesis:**

Se observó un doblez en el cable SATA de datos del disco.

**Acción realizada y resultado observado:**

Se volvió a conectar el disco durante el montaje. En la foto final se ve el cableado conectado.

## 8. Comprobación final · Equipo A

- [x] Piezas sujetas.
- [x] RAM encajada.
- [x] Cables revisados.
- [x] Sin tornillos sueltos.
- [x] Ventilador de CPU conectado.
- [x] Puesto recogido.

**¿Encendido autorizado?** ☒ Sí  ☐ No

**Resultado / motivo:** Comprobación visual realizada. Resultado del encendido pendiente de registrar.

Una observación no demuestra por sí sola la causa de una avería.

**Interior antes del cierre**

![Vista final del interior con el disco y el cableado conectados y el soporte trasero en su posición](images/montaje-21-interior-antes-del-cierre.jpeg)

**Ficha en papel de los apartados 6–8**

![Página 3 de la ficha: operaciones realizadas, incidencias y comprobación final](images/03-intervencion-y-cierre.jpeg)

---

## 9. Identificación y arranque · Equipo B

Utilizad vuestro propio ordenador funcional para los siguientes apartados.

**Equipo:** ☒ Portátil  ☐ Sobremesa  ☐ Otro

**Marca y modelo:** MSI Katana 15 B13VFK.

**Linux:** ☒ Instalado directamente  ☐ Máquina virtual

**Sistema operativo y versión:** Omarchy 4.5.0 (`/etc/os-release`), basado en Arch Linux, con Hyprland.

**Si es virtual: sistema anfitrión y programa de virtualización:** No procede.

[Manual de Omarchy](https://omarchy.org/manual/).

**¿Arranca con normalidad? ¿Qué observáis desde el encendido hasta el inicio?**

El portátil arrancó en modo UEFI y llegó a una sesión de Omarchy desde la que se ejecutaron los comandos de los apartados siguientes. Queda por registrar la secuencia de pantallas desde el encendido.

**¿Qué es el POST y en qué se diferencia de la UEFI y del sistema operativo?**

El POST es la comprobación inicial del hardware que realiza el firmware al encender el ordenador. La UEFI es el firmware que inicializa los componentes, permite configurar el equipo y pone en marcha el proceso de carga del sistema operativo. El sistema operativo, en este caso Linux con Omarchy, gestiona los recursos del ordenador y permite ejecutar los programas.

**¿Habéis accedido a la UEFI o consultado información de ella? ¿Qué dato habéis visto?**

Se ha consultado la información del firmware: American Megatrends International, versión E1585IMS.11C, con fecha 26/08/2025.

No cambiéis ajustes de UEFI sin indicación del profesor. Si no podéis acceder, indicadlo.

## 10. Linux: procesador · `lscpu`

Ejecutad `lscpu`. Adjuntad la salida revisada o indicad si el comando falla.

**Modelo / CPU presentada a Linux:** Intel Core i7-13620H de 13.ª generación.

**Arquitectura:** x86_64 (64 bits).  **CPU lógicas visibles:** 16.

**Salida de `lscpu`**

![Salida de lscpu en el Equipo B: Intel Core i7-13620H, arquitectura x86_64, 10 núcleos físicos y 16 CPU lógicas](images/montaje-22-equipo-b-lscpu.png)

**¿Qué diferencia hay entre núcleo e hilo? ¿Qué podéis concluir de la salida?**

Un núcleo es una unidad física de procesamiento. Un hilo de hardware es una unidad de ejecución lógica que el sistema operativo puede utilizar para planificar tareas. Un núcleo puede admitir más de un hilo, por lo que el número de CPU lógicas puede superar al de núcleos físicos. El i7-13620H tiene 10 núcleos y admite 16 hilos.

[Manual de `lscpu`](https://man.archlinux.org/man/lscpu.1.en).

## 11. Linux: memoria · `free -h`

Adjuntad las salidas de los comandos. Si alguno falla o no está disponible, anotadlo. Antes de entregarlas, ocultad usuarios, nombres de equipo, números de serie y UUID. En una máquina virtual pueden mostrarse recursos virtuales, no el hardware físico completo.

**Memoria total instalada:** 16 GB, distribuidos en dos módulos de 8 GB.  
**Memoria disponible:** 11 GiB en el momento de la captura. `free -h` mostraba 15 GiB de RAM total visible para Linux y 9,5 GiB libres.

**Captura de los apartados 11–13**

![Salida de free -h con la memoria del Equipo B, seguida de lsblk con el SSD y sus particiones y lspci con los dispositivos PCI](images/montaje-23-equipo-b-free-lsblk-lspci.png)

**¿Qué significa «disponible» y por qué puede diferir de «libre»?**

La memoria libre es la RAM que no se está utilizando. La disponible estima cuánta memoria se puede destinar a nuevas aplicaciones sin recurrir al intercambio en disco. Incluye parte de la memoria ocupada por cachés que Linux puede recuperar cuando hace falta; por eso puede ser mayor que la memoria libre.

[Manual de `free`](https://man.archlinux.org/man/free.1.en).

## 12. Linux: almacenamiento · `lsblk`

**Disco identificado:** SSD Samsung MZVL41T0HBLB-00BTW de 1 TB. En `lsblk` aparece como `nvme0n1`, con un tamaño de 953,9 GiB.

**Particiones y puntos de montaje:**

- `nvme0n1p6` (2 GiB) está montada en `/boot`.
- `nvme0n1p7` (243,2 GiB) contiene el volumen cifrado `omarchy_root`, que aparece asociado a `/`, `/home`, `/var/log` y `/var/cache/pacman/pkg`.

[Captura de `lsblk`](images/montaje-23-equipo-b-free-lsblk-lspci.png).

**Explicad la diferencia entre disco, partición y punto de montaje:**

El disco es el dispositivo físico de almacenamiento. Una partición es una división lógica de ese dispositivo. El punto de montaje es el directorio desde el que se accede al sistema de archivos montado, por ejemplo `/` para la raíz del sistema.

[Manual de `lsblk`](https://man.archlinux.org/man/lsblk.8.en).

## 13. Linux: dispositivos · `lspci` y `lsusb`

**Dispositivo 1 y función:** NVIDIA GeForce RTX 4060 Laptop GPU (`01:00.0` en `lspci`). Es la tarjeta gráfica dedicada y acelera el procesamiento de gráficos y las aplicaciones compatibles.

**Dispositivo 2 y función:** Intel Wi-Fi 6 AX201 160 MHz, adaptador de red inalámbrica. `lspci` muestra el controlador Intel Raptor Lake PCH CNVi WiFi en `00:14.3` y el registro de `iwlwifi` identifica el modelo AX201.

[Captura de `lspci`](images/montaje-23-equipo-b-free-lsblk-lspci.png).

**`lsusb`:** el comando no está disponible en el equipo.

**¿Por qué podría no aparecer un componente físico o mostrarse de otra forma en una máquina virtual?**

Una máquina virtual utiliza los dispositivos que le presenta el programa de virtualización. Pueden ser dispositivos emulados o virtuales con nombres distintos a los componentes físicos. Algunos componentes del ordenador anfitrión no se muestran al sistema invitado si no se le asignan expresamente. En este portátil, Omarchy está instalado directamente.

## 14. Duda técnica y uso crítico de IA

Podéis usar una IA de Internet. No compartáis datos personales ni información privada del centro. Sin acceso a IA, resolved la duda con una fuente técnica.

**Herramienta utilizada y fecha:** Manual de `free` de procps-ng, consultado el 20/11/2026.

**Pregunta planteada:**

¿Por qué la memoria disponible puede ser mayor que la memoria libre en Linux?

**Respuesta resumida y afirmación concreta que decidisteis comprobar:**

Linux utiliza parte de la RAM como caché para agilizar el acceso a los datos. Parte de esa memoria se puede recuperar para ejecutar nuevas aplicaciones. La afirmación comprobada es que «disponible» tiene en cuenta memoria recuperable y no equivale únicamente a «libre».

**Fuente técnica o prueba utilizada y resultado:** confirmada / corregida / no verificada.

**Confirmada.** El [manual de `free`](https://man.archlinux.org/man/free.1.en), en la descripción de `available`, explica que se estima la memoria utilizable por nuevas aplicaciones sin intercambio en disco y se tiene en cuenta la caché recuperable.

## 15. Valoración y entrega

**¿Qué paso fue más difícil y cómo lo resolvisteis?**

________________________________________________________________________

________________________________________________________________________

**¿Qué relación existe entre el montaje y la información de Linux? Recordad que son equipos distintos.**

El montaje permite identificar físicamente los componentes y comprobar sus conexiones. Linux permite consultar el procesador, la memoria, el almacenamiento y los dispositivos que detecta el sistema. Se trata de equipos distintos: el equipo A tiene un Intel Celeron G1840, 2 GB de RAM DDR3 y un disco Western Digital de 500 GB; el equipo B es el portátil MSI con un Intel Core i7-13620H, 16 GB de RAM y un SSD Samsung de 1 TB. Los datos obtenidos en el portátil describen el equipo B.

**¿Qué haríais de otra manera en un próximo montaje?**

Etiquetaríamos los cables y tomaríamos fotografías más detalladas de los conectores antes de desmontarlos. También organizaríamos los tornillos por componente y comprobaríamos cada conexión siguiendo un orden antes de cerrar el equipo.

Antes de entregar:

- [ ] Ficha completa.
- [x] Fotos identificadas.
- [x] Salidas de Linux revisadas.
