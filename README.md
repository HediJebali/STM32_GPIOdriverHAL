## Project: 02_CMSIS_Register_Access

## Objective: Implement a GPIO-based logic control using CMSIS (Cortex Microcontroller Software Interface Standard) register access on STM32F446RE.

## Functionality: 
The system controls a user LED (PA5) based on a push-button input (PC13) configured with an internal pull-down resistor. The LED remains active for a predefined duration of 8 seconds upon triggering.

## Technical Focus: 
Moving from pure hardware memory-mapping to standardized peripheral structures provided by the CMSIS library, improving code readability and portability while maintaining bare-metal efficiency.

## Key Concepts:
- GPIO Configuration using CMSIS structures (Input/Output modes).
- Standardized Pull-down Resistor implementation.
- Timing control and Debouncing.
- Utilizing predefined core headers instead of manual address mapping.
- A simple instruction executes in 1 microsecond.