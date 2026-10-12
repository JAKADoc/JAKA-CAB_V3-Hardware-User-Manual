.. _Technical-Data:

Technical Data
**************

.. _Control cabinet technical specifications:

Control cabinet technical specifications
+++++++++++++++++++++++++++++++++++++++++++

.. csv-table:: Control cabinet technical specifications
   :file: ./tables/Control cabinet technical specifications.csv
   :encoding: utf-8-sig
   :widths: 16 12 18 17 20 17
   :header-rows: 1

.. _Control Cabinet Dimension:

Control Cabinet Dimension
++++++++++++++++++++++++++++

.. figure:: ../../images/06_技术规格/CAB_L、CAB_H外形尺寸.*
   :width: 17.21cm
   :align: center

   Outline dimensions of CAB L/H

.. figure:: ../../images/06_技术规格/CAB_LiteAC外形尺寸.*
   :width: 12.35cm
   :align: center

   Outline dimensions of CAB LiteAC

.. figure:: ../../images/06_技术规格/CAB_LiteDC外形尺寸.*
   :width: 13.17cm
   :align: center

   Outline dimensions of CAB LiteDC

.. _Electrical Specifications:

Electrical Specifications
+++++++++++++++++++++++++++

.. include:: Electrical Specifications.rst

.. _Front Panel Indicators:

Front Panel Indicators
++++++++++++++++++++++++

.. _I-O-Indicators:

I/O Indicators
==============

.. figure:: ../../images/06_技术规格/I-O指示灯.*
   :width: 16.86cm
   :align: center

   I/O indicators

| **1** I/O indicators
| **2** PNP/NPN indicators

The I/O indicator lights are on the right of the interface on the front panel of the control cabinet, displaying a yellow-green color. The indicator lights illuminate when the interface is connected. Besides the I/O indicator lights on the right side of the interface, there are two PNP and NPN indicator lights above the P7 to P10 interfaces. The NPN indicator displays blue, and the PNP indicator displays yellow-green. When the interface is configured as NPN and connected, the upper blue indicator light illuminates. When the interface is configured as PNP and connected, the upper yellow-green indicator light illuminates.

.. _Maintenance-Indicator:

Maintenance Indicator
=====================

Maintenance indicators are on the front panel of the control cabinet to display the status of the control cabinet.

.. figure:: ../../images/06_技术规格/维护指示灯.*
   :width: 8cm
   :align: center

   Maintenance indicator

.. list-table:: Meaning of maintenance indicator
   :widths: 14 13 73
   :header-rows: 1

   * - **Name**
     - **Color**
     - **Description**

   * - 5V_S
     - Green
     - Slave MCU power supply status indicator. Indicator is lit when power supply is normal.

   * - 5V_M
     - Green
     - Master MCU power supply status indicator. Indicator is lit when power supply is normal.

   * - B_L
     - Red
     - Button cell indicator. Indicator is lit when battery is low, which means the button cell should be replaced immediately according to procedures in the |product_name| Service Manual.

   * - B_H
     - Green
     - Button cell indicator. Indicator is lit when battery charge is sufficient.

   * - Power
     - Green
     - Robot powering on indicator. Indicator is lit when robot is powered on.

   * - E_M
     - Red
     - Master MCU status indicator. Indicator is lit during Master MCU malfunctions.

   * - E_S
     - Red
     - Slave MCU status indicator. Indicator is lit during Slave MCU malfunctions.

   * - 24V_IN
     - Green
     - Control cabinet powering on indicator. Indicator is lit when control cabinet is powered on.

   * - 4G
     - Green
     - 4G status indicator. Indicator is lit when 4G connection is normal.

   * - Wi-Fi
     - Green
     - Wi-Fi status indicator. Indicator is lit when wireless connection is established.

   * - IPC
     - Green
     - IPC status indicator. Indicator is lit when IPC functions normally.

   * - ER_M
     - Red
     - EtherCAT communication status indicator of Master MCU. Indicator is lit during communication abnormalities.

   * - ER_S
     - Red
     - EtherCAT communication status indicator of Slave MCU. Indicator is lit during communication abnormalities.

.. _Reset Buttons:

Reset Buttons
++++++++++++++++

.. figure:: ../../images/06_技术规格/复位按钮.*
   :width: 20cm
   :align: center

   Reset button

There are two reset buttons on the control panel front: RST SYS and RST Wi-Fi, with the following functions:

**RST SYS:** User password reset button. Press and hold for 8 seconds, 
the administrator password for the currently connected robot will revert to default password (jakazuadmin) when connecting the robot through Coboπ.

**RST Wi-Fi:** Control cabinet's Wi-Fi reset button. Press and hold for 8 seconds, 
the Wi-Fi configuration is restored to factory default settings. 
This includes all parameters configured within the Coboπ “Wi-Fi Settings > AP Device Networking” interface.

The reset button is housed in a 2 mm diameter bore and can be depressed using a 1.5 mm slotted ESD-safe screwdriver.

.. _Button-Cell:

Button Cell
+++++++++++

The button cell is used to provide power for BIOS of the IPC and is located at the button cell compartment behind the control cabinet’s front panel. The following illustration shows the location of the button cell compartment. The button cell compartment location of CAB LiteAC and CAB LiteDC is identical with figure above and not shown repeatedly.

The cell model is CR2032.

.. figure:: ../../images/06_技术规格/纽扣电池位置.*
   :width: 7.95cm
   :align: center

   Position of button cell

Refer to |product_name| Service Manual for button cell replacement.

.. _Wi-Fi-Function-Specification:

Wi-Fi Function Specification
++++++++++++++++++++++++++++

The control cabinet is equipped with a built-in Wi-Fi module. 
Its default network name (SSID) corresponds to the control cabinet's serial number, and the default password is “JKadmin123”.

.. csv-table::
   :file: ./tables/Wi-Fi specification.csv
   :encoding: utf-8-sig
   :widths: 26 16 28 30
   :header-rows: 2

.. container:: table-notes

   | :sup: `1` Alternatively: 100 mW (e.i.r.p = equivalent isotropically radiated power) 
   | :sup: `2` For 5,150...5,720 MHz. Alternatively: 200 mW (e.i.r.p = equivalent isotropically radiated power)
   | :sup: `3` For 5,720...5,825 MHz. Alternatively: 2000 mW (e.i.r.p = equivalent isotropically radiated power)

.. _Control-Stick-Buttons:

Control Stick Buttons
+++++++++++++++++++++

.. include:: Control Stick Buttons.rst