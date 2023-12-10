- In the control system, there are 4 main parts:
  - Sensors: a device that is used to sense a physical phenomenon.
  - System: The object that wants to control and apply changes.
  - Actuator: the device that is used to alter or adjust the system or the environment. 
  - Controller: the device that is used to control the change in the system.

- **Open-Loop Control System**: is a system with just a controller, and actuator with no sensor; it is a system without feedback.
  
- **Closed-Loop Control System**: is a system that utilizes an extra component that compares the actual output with the desired output. (the measure of the output is called the feedback signal)

- **Multioop Feedback Control System**: a system with more than one type of sensor and controller that monitors different factors in the system.

- **Industrial Control Systems**:  ICSs, are a subset of cyber-physical systems.  ICSs are automation systems that provide control and monitoring functions in industrial facilities. They combine
different system types like process control systems, distributed control systems, supervisory control and data acquisition systems, safety instrumented systems, and more.

- **Supervisory Control and Data Acquisition (SCADA) systems**: are used for controlling, monitoring, and analyzing industrial devices and processes. The system consists of both software and hardware components and enables remote and on-site gathering of data from the industrial equipment.

- **Historian**: As the task executes, the results are recorded in a database called a historian.

- Modbus/TCP | DNP3: application layer layer protocols that are used in industrial control systems (non-routable protocols but there are new routable versions of them). 

- **(PPD-21)**: define 16 sectors that have critical ICS.

- **Smart grid**: is a modernization of energy transmission, distribution, and consumption systems. A smart grid improves upon legacy systems through the addition of monitoring,
measurement, and automation.

- **Programmable Logic Controller (PLC)**: is a ruggedized computer used for industrial automation. It is designed to handle the harsh conditions of industrial environments, such as extreme temperatures, vibrations, and dust. PLCs are used to control a wide variety of machines and processes.

- **Human-Machine Interface (HMI)**: is the user interface or dashboard that connects a person to a machine, system, or device. It allows the user to monitor and control the machine or system, and to input data or instructions.

- **The Purdue Reference Model (PRM)**: defines five levels for industrial automation and information flow in a Computer Integrated Manufacturing (CIM) environment. Although not explicitly mentioned in the original model, Level 0 can be added to represent the physical process itself. Here's a breakdown of each level:

    - **Level 0: Physical Process**
    : This level represents the physical machinery and equipment used in the manufacturing process. It includes things like sensors, actuators, and process equipment.
    Components: Sensors, actuators, process equipment, materials, energy.
    
     - **Level 1: Field Level**
    : The field level interfaces with the physical process and collects data from sensors. It also sends signals to actuators to control the process.
    Components: PLCs, Fieldbus networks, sensors, actuators.
    
    - **Level 2: Control Level**
    : This level is responsible for controlling and monitoring the manufacturing process. It includes functions such as process control, quality control, and safety systems.
    Components: DCS, PLCs, HMI (Human-Machine Interface) systems.
    
    - **Level 3: Operations Level**
    : This level is responsible for managing the production process and scheduling tasks. It includes functions such as production planning, inventory control, and maintenance scheduling.
    Components: MES (Manufacturing Execution System), ERP (Enterprise Resource Planning) system.
    
    - **Level 4: Enterprise Level**: This level is responsible for managing the entire manufacturing enterprise. It includes functions such as order processing, financial management, and customer relationship management.
    Components: ERP system, CRM (Customer Relationship Management) system.

- Night Dragon and Stuxnet are examples of the weaponized malware that is used to attack ICS.
