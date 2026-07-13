## Project: 03_STM32_GPIOdriverHAL

## Objective: Implement a custom-built GPIO peripheral driver mimicking the HAL structure to toggle an onboard LED (PA5) at a 500 ms interval on the STM32F446RE.

## Functionality: 
The system continuously toggles the user LED (PA5) with a precise delay of 500 milliseconds (ON for 500ms, OFF for 500ms), creating a clean and stable blinking pattern.

## Technical Focus: 
Designing a reusable, modular peripheral driver using predefined HAL register structures and bit definitions. This demonstrates abstracting low-level hardware configuration into standard driver APIs (`GPIO_Init`, `GPIO_TogglePin`) similar to professional industrial firmware.

## Key Concepts:
- Structural driver architecture (Separation of application logic and peripheral configuration).
- Utilizing predefined HAL device header files and structures.
- Developing modular APIs for GPIO Initialization and Pin Toggling.
- Software-based precise timing control for the 500 ms interval.
- Emulating the official STMicroelectronics HAL workflow from scratch.

### 📸 Hardware Setup :


https://github.com/user-attachments/assets/1ed191b6-1b06-4fbf-ad4c-3eee2c1794df

