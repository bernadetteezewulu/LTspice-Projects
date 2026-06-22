# LTspice-Projects

A Simulink-like power electronics simulation environment built on LTspice, featuring ready-to-use circuit libraries and custom tools.

## Features ✨

- **Optimized Models for Convergence**: Includes circuit models specifically designed to enhance simulation convergence.
- **Transparent Model Definitions**: All models are defined using LTspice schematic files (.asc), allowing users to view and edit the circuits directly as needed.
- **Extensive example circuits**: A wide range of example circuits covering DC-DC converters, resonant converters, Totem-Pole PFC, motor drivers, battery charger, and digitally controlled power stages.

## Symbols 🧩

![Symbols](img/Symbols.png)

## Example Screen Shots 🖼️

### Type-II Compensator (FRA)
![Type-II Compensator (FRA)](img/TYPE2_FRA.png)

### Peak Current Mode Buck Converter (Current-Mode Control)
![Peak Current Mode Buck Converter](img/BUCK_PCM.png)

### Peak Current Mode Boost Converter (Current-Mode Control)
![Peak Current Mode Boost Converter](img/BOOST_PCM.png)

### CCCV Buck Converter for Battery Charging (CC/CV control)
![CCCV Buck Converter](img/BUCK_CCCV.png)

### Boundary Conduction Mode Flyback Converter (BCM / CrCM)
![Flyback Converter](img/FLYBACK.png)

### Phase-Shift Full-Bridge Converter (PSFB with ZVS)
![Phase-Shift Full-Bridge Converter](img/PSFB.png)

### LLC Resonant Converter (Frequency Control)
![LLC Resonant Converter](img/LLC.png)

### Single-Phase Totem-Pole PFC (2-Phase Interleaved)
![Single-Phase Totem-Pole PFC](img/1Ph-TTP-PFC_2ITLV.png)

### Single-Phase 4-Level Totem-Pole PFC
![Single-Phase 4-Level Totem-Pole PFC](img/1Ph-4LvTTP-PFC.png)

### Three-Phase Totem-Pole PFC (VOC + SVPWM Control)
![Three-Phase Totem-Pole PFC](img/3Ph-TTP-PFC_VOC_SVPWM.png)

### Discrete-Time PID Controller (Z-Domain FRA)
![Discrete PID FRA](img/zPID_FRA.png)

### Discrete-Time Voltage-Mode Buck Converter (Digital Control)
![Discrete Voltage-Mode Buck Converter](img/BUCK_VM_discrete.png)

### Two-Phase Stepper Motor Control using FOC
![Two-Phase Stepper Motor FOC](img/STEP2PH_FOC.png)

### Neural-Network Controlled Buck Converter using pytorch2ltspice
![NN Controlled Buck Converter](img/NN_BUCK_VM.png)

## License

MIT
