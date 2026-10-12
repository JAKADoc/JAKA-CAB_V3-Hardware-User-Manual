.. _Safety Standard:

Safety Standard
***************

.. _Introduction:

Introduction
++++++++++++

This chapter mainly introduces the safety principles and standards that should be followed while using the JAKA robot. Users should carefully read and strictly abide by the content related to safety in this manual. Operators should fully recognize the complexity and danger of the robot system, and pay special attention to the content related to warning signs.

.. _Important Safety Notice:

Important Safety Notice
+++++++++++++++++++++++

According to the 2006/42/EC Machinery Directive, the JAKA robot is **partly completed machinery**. A risk assessment must be performed for every robot installation. All safety instructions must be followed.

.. _Safety Signals and Symbols:

Safety Signals and Symbols
++++++++++++++++++++++++++

The danger level in this manual is described with the following safety symbols. Contents related to safety should be strictly observed.

.. list-table:: Safety Symbol Descriptions
   :widths: 20 80 
   :header-rows: 1
   
   * - **Symbol**
     - **Description**

   * - **WARNING: ELECTRICITY**
     - This symbol indicates a potentially dangerous power consumption situation which, if not avoided, may result in injuries to personnel or serious damage to equipment.  

   * - **WARNING** 
     - This symbol indicates a potentially dangerous situation which, if not avoided, may result in injuries to personnel or serious damage to equipment.

   * - **WARNING: HOT SURFACE** 
     - This symbol indicates a potentially dangerous hot surface that may result in injuries to personnel if touched.

   * - **ATTENTION** 
     - This symbol is used to indicate important facts and conditions.

   * - **NOTE**
     - This symbol is used to indicate additional information.

.. _Warnings and Cautions:

Warnings and Cautions
+++++++++++++++++++++

This section focuses on the protection of operators and the relevant precautions of the first installation. Users need to read the safety warnings in this manual carefully.

.. list-table:: General warnings
   :widths: 20 80      
   :header-rows: 1
   :class: longtable
   
   * - **Symbol**
     - **Description**
  
   * - .. figure:: ../../images/04_安全规范/触电.*
          :width: 1.5cm
     - **WARNING: ELECTRICITY** 

       | Technical personnel are instructed to carry out the installation and commissioning procedures for any JAKA products in strict accordance with the provided specifications.
       | Adjustment and alteration of any JAKA product parameters must be executed exclusively by authorized personnel to safeguard against unauthorized modifications by individuals lacking appropriate operating expertise.
       | Associated risks of the use of control cabinets not supplied by JAKA is solely the responsibility of the operator.
       | Please ensure that all non-waterproof equipment remains dry. In case of water ingress, please lock and tag all power sources and contact JAKA technical service personnel.
       | Please do not use non-original cables. When using the robot, please do not bend the cables.

   * - .. figure:: ../../images/04_安全规范/危险.*
          :width: 1.5cm
     - **WARNING**
       
       | To prevent damage, refrain from connecting safety equipment to the standard I/O interface (use safety I/O interface).
       | All safety-related signals should be designed redundantly (with two independent channels). Keep the two independent channels separate from each other to ensure that safety functions are not lost when one channel is in error.
       | Confirm the accuracy of mounting settings, including mounting angles, Tool Center Point (TCP) position, tool mass, TCP offset and the robot's safety configuration.
       | Ensure that tools and obstacles do not possess sharp corners or points and maintain a safe distance between all personnel and the robot.
       | Connecting the robot to different machinery may increase existing hazards or introduce new ones. Conduct a comprehensive risk assessment for the entire system installation.
       | The control cabinet operates with DC voltage input. Please use DC power supply properly. When using battery power, please consider the related risks associated with the battery.

   * - .. figure:: ../../images/04_安全规范/热表面.png
          :width: 1.5cm
     - **WARNING: HOT SURFACE**

       | JAKA |product_name| generates heat during operation. Avoid contact with it during operation and after shutdown. In both instances allow approximately 1 hour for the equipment to cool down.
       | |product_name| generates heat. Do not put your hand on the |product_name| housing.

.. _Liability and Risk:

Liability and Risk
++++++++++++++++++

**Liability**

| This manual does not contain full application examples, complete solution designs, or information on peripheral equipment that could affect the robot system's security.
| It is the responsibility of the user to ensure that relevant practical national laws and regulations are followed, and that there are no significant hazards in the workspace.
| The safety information in this manual does not constitute a guarantee from JAKA. Even when all safety instructions are followed, operator actions may still result in injury or damage.
| JAKA is committed to continuously improving the performance and reliability of our robots. However, we are not responsible for any errors or omissions in this manual and reserve the right to the final interpretation of its contents.

**Risk**

Operators engaging with the robot will inevitably experience direct or indirect physical contact. It is essential to maintain awareness of self-protection and adhere to safe operating procedures. The following hazards should be considered:

- Robot brake failure causing it to drop.
- Loose bolts and screws causing vibrations.
- Robot collision with operator.
- Lack of prompt repair.
- Danger when sharp-end effectors are used.
- Toxic or corrosive environments.
- Strong magnetic environment.

.. _Network-Security:

Network Security
++++++++++++++++

This product is designed to be connected to and to communicate information and data via a network interface. 
It is your sole responsibility to establish and maintain a secure connection between the product and to your network or any other network (as the case may be).

You shall establish and maintain any appropriate measures (such as, but not limited to, the installation of firewalls, 
application of authentication measures, encryption of data, installation of anti-virus programs, etc) 
to protect the product, the network, its system and the interface against any kind of security breaches, 
unauthorized access, interference, intrusion, leakage and/or theft of data or information. 
JAKA and its entities are not liable for damage and/or loss related to such security breaches, 
any unauthorized access, interference, intrusion, leakage and/or theft of data or information.

.. _Labels:

Labels
++++++++++

The following labels are safety warnings and product labels on the robot and the control cabinet. 
During operation, be sure to follow the instructions and warnings on the labels to ensure safety. 
Do not remove the labels casually. 
Handle labeled parts or units and their surrounding area with caution to avoid damage to the labels. 
Product labels and robot model figures are only for reference. 
Please see the figures and tables below for detailed description on product labels.

.. figure:: ../../images/04_安全规范/CAB_L、CAB_H控制柜标签位置（正门）.*
   :width: 13.81cm
   :align: center

   Label position of CAB L/H (front)

.. figure:: ../../images/04_安全规范/CAB_L、CAB_H控制柜标签位置.*
   :width: 9.95cm
   :align: center

   Label position of CAB L/H

.. figure:: ../../images/04_安全规范/CAB_L、CAB_H控制柜标签位置_2.*
   :width: 11.09cm
   :align: center

   Label position of CAB L/H

.. figure:: ../../images/04_安全规范/CAB_LiteAC、CAB_LiteDC控制柜标签位置（正门）.*
   :width: 9.51cm
   :align: center

   Label position of CAB LiteAC、CAB LiteDC (front)

.. figure:: ../../images/04_安全规范/CAB_LiteAC、CAB_LiteDC控制柜标签位置.*
   :width: 10.52cm
   :align: center

   Label position of CAB LiteAC、CAB LiteDC

.. figure:: ../../images/04_安全规范/CAB_LiteAC、CAB_LiteDC控制柜标签位置_2.*
   :width: 10.35cm
   :align: center

   Label position of CAB LiteAC、CAB LiteDC

.. list-table:: Description of labels
   :widths: 7 71 22
   :header-rows: 1
   :class: longtable

   * -
     - **Labels**
     - **Description**

   * - A
     - .. figure:: ../../images/04_安全规范/CAB_L铭牌.*
          :width: 5cm
          :align: center
     - CAB L nameplate

   * -
     - .. figure:: ../../images/04_安全规范/CAB_H铭牌.*
          :width: 5cm
          :align: center
     - CAB H nameplate

   * -
     - .. figure:: ../../images/04_安全规范/CAB_LiteAC铭牌.*
          :width: 8cm
          :align: center
     - CAB LiteAC nameplate

   * -
     - .. figure:: ../../images/04_安全规范/CAB_LiteDC铭牌.*
          :width: 8cm
          :align: center
     - CAB LiteDC nameplate

   * - B
     - .. figure:: ../../images/04_安全规范/阅读说明书.*
          :width: 1.5cm
          :align: center
     - Read manual

   * - C
     - .. figure:: ../../images/04_安全规范/热表面.png
          :width: 1.5cm
          :align: center
     - Warning hot surface

   * - D
     - .. figure:: ../../images/04_安全规范/触电.*
          :width: 1.5cm
          :align: center
     - Beware of electric shock

   * - E
     - .. figure:: ../../images/04_安全规范/电源挂锁.*
          :width: 3cm
          :align: center
     - Lock out electrical power

   * - F
     - .. figure:: ../../images/04_安全规范/接地.png
          :width: 1.5cm
          :align: center
     - Grounding

   * - G
     - .. figure:: ../../images/04_安全规范/必须拔出插头.png
          :width: 1.5cm
          :align: center
     - Unplug before operation

   * - H
     - .. figure:: ../../images/04_安全规范/CE认证标识.png
          :width: 1.5cm
          :align: center
     - CE certification

   * - I
     - .. figure:: ../../images/04_安全规范/WEEE认证标识.png
          :width: 1.5cm
          :align: center
     - WEEE certification

   * - J
     - .. figure:: ../../images/04_安全规范/cSGSus认证标识.png
          :width: 1.5cm
          :align: center
     - cSGSus certification

   * - K
     - .. figure:: ../../images/04_安全规范/TUVsaar功能安全认证标识.png
          :width: 3cm
          :align: center
     - TUV saar functional safety certification

   * - L
     - .. figure:: ../../images/04_安全规范/CAB_L无线电认证标识.jpg
          :width: 4cm
          :align: center
     - CAB L wireless product certification

   * - 
     - .. figure:: ../../images/04_安全规范/CAB_H无线电认证标识.jpg
          :width: 4cm
          :align: center
     - CAB H wireless product certification

   * - 
     - .. figure:: ../../images/04_安全规范/CAB_LiteAC无线电认证标识.jpg
          :width: 4cm
          :align: center
     - CAB LiteAC wireless product certification

   * - 
     - .. figure:: ../../images/04_安全规范/CAB_LiteDC无线电认证标识.jpg
          :width: 4cm
          :align: center
     - CAB LiteDC wireless product certification
