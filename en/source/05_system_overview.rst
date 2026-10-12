.. _System Overview:

System Overview
***************

.. _Compatibility:

Compatibility
++++++++++++++++

The compatibility between the |product_name| and the robot is as follows.

.. csv-table:: Compatibility
   :file: ./tables/Compatibility.csv
   :encoding: utf-8-sig
   :widths: 20 20 20 20 20
   :header-rows: 1
   :class: no-auto-merge

.. container:: table-notes

   :sup:`1` When pairing these robot models with the |product_name|, the CAB L is required for regions with an input voltage of 200–240 V, while the CAB H is used in regions with an input voltage of 100–200 V.

.. _System Architecture:

System Architecture
+++++++++++++++++++++

When the robot is used with CAB L/H, the required components are as shown in figure below. 

.. figure:: ../../images/05_系统概述/CAB_LH系统部件.*
   :width: 15cm
   :align: center

   Components with CAB L/H

When the robot is used with CAB LiteAC, the required components are as shown in figure below.

.. figure:: ../../images/05_系统概述/CAB_LiteAC系统部件.*
   :width: 15cm
   :align: center

   Components with CAB LiteAC

1. Control stick: Equipped with an emergency stop button and a three-position enabling switch. Used to start up or shut down the robot system, configure parameters, and move the robot.
2. Control cabinet: The control cabinet includes the core computing components and various electrical interfaces.
3. (User-supplied) Router and network cable: CAB V3 has a built-in Wi-Fi module which is accessible by any android, IOS or windows device. This allows the user to connect the JAKA App to the controller wirelessly with the SSID being the control cabinet serial number, and default password being JKadmin123. It is also possible to use a wired teach pendant, or connect the cabinet network port of the control cabinet to the router and the operation terminal to the wireless network of this router at the same time. It is recommended to configure a specialized router for the robot to prevent conflicts with other devices.
4. Control cabinet power cord: Provides power to the control cabinet.
5. Robot: A six axes robotic arm which moves as programmed by the user. It consists of a ring-shaped light; buttons for dragging and point teaching and a I/O interface for connecting tools (the TIO interface) on joint 6.
6. Robot connection cable: Connect the robot and the control cabinet.

When paired with the CAB LiteDC, the robot can be integrated into mobile platforms such as AGVs and powered directly by the AGV’s built‑in 48V traction battery. The control cabinet features a compact design, simplifies integration. The components necessary are illustrated in the figure below.

.. figure:: ../../images/05_系统概述/CAB_LiteDC系统部件.*
   :width: 15cm
   :align: center

   Components with CAB LiteDC

1. Control stick: Equipped with an emergency stop button and a three-position enabling switch. Used to start up or shut down the robot system, configure parameters, and move the robot.
2. Control cabinet: The control cabinet includes the core computing components and various electrical interfaces.
3. (User-supplied) Router and network cable: CAB V3 has a built-in Wi-Fi module which is accessible by any android, IOS or windows device. This allows the user to connect the JAKA App to the controller wirelessly with the SSID being the control cabinet serial number, and default password being JKadmin123. It is also possible to use a wired teach pendant, or connect the cabinet network port of the control cabinet to the router and the operation terminal to the wireless network of this router at the same time. It is recommended to configure a specialized router for the robot to prevent conflicts with other devices.
4. Robot: A six axes robotic arm which moves as programmed by the user. It consists of a ring-shaped light; buttons for dragging and point teaching and a I/O interface for connecting tools (the TIO interface) on joint 6.
5. Robot connection cable: Connect the robot and the control cabinet.
6. DC Power Supply: The control cabinet operates on DC power, with a 48V power supply recommended.