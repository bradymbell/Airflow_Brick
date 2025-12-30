# Airflow / Spiro Brick

The Spiro Brick interfaces with the [Sensirion SFM3300-D](https://sensirion.com/products/catalog/SFM3300-D) airflow sensor. It also enables airway pressure measurement using Amphenol differential pressure sensor such as [ELVH-family](https://allsensors.com/en/product-listing?family=elvh) with I2C 3.3V or 5V interface.

[Datasheet SFM3300](./datasheets/Sensirion_Datasheet_SFM3300-AW_SFM3300-D.pdf)
[Datasheet ELVH Family](./datasheets/DS-0376.pdf)

Example differential pressure sensor with I2C and 5V interface: ELVH-M160D-HRRD-C-N2A5 for 1/16 ID 1/8 OD tubing.


## Power Brick PCB Design

The following files were created for this project using KiCad.

<img src="./KiCad/Schematic.svg" alt="Schematics" width="500" />

<img src="./KiCad/PCB.svg" alt="Schematics" width="500" />
<img src="./KiCad/Spiro_Brick_Front.png" alt="3D" width="500" />
<img src="./KiCad/Spiro_Brick_Back.png" alt="3D" width="500" />
