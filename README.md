# stm32-2in1-dmm-oscilloscope

# 2-in-1 Digital Multimeter and Oscilloscope

## Overview

This project is a 2-in-1 embedded measurement instrument developed using an STM32 development board. The system combines digital multimeter functions and dual-channel oscilloscope functions into one educational-purpose device.

The oscilloscope mode captures analog input signals through ADC channels and displays real-time waveforms on a TFT LCD. The digital multimeter mode supports basic measurement functions such as voltage, current, resistance, capacitance, temperature, and connectivity testing.

## Features

### Oscilloscope Mode

* Dual-channel ADC signal acquisition
* Real-time waveform display on TFT LCD
* Grid line display for voltage and time reference
* Adjustable time base
* Channel enable and disable control
* Basic signal measurements such as frequency, average value, duty cycle, and peak-to-peak voltage

### Digital Multimeter Mode

* Voltage measurement
* Current measurement
* Resistance measurement
* Capacitance measurement
* Temperature measurement using DHT22
* Connectivity test with buzzer indication

## Technologies Used

* STM32 Microcontroller
* Embedded C
* STM32CubeIDE
* ADC
* GPIO
* Timer
* PWM
* TFT LCD
* DHT22 Sensor
* Buzzer
* SPI / I2C, depending on hardware configuration

## System Architecture

The system consists of analog input circuits, STM32 ADC modules, signal processing logic, TFT LCD display control, and user input control. The user can switch between oscilloscope mode and digital multimeter mode during operation.

## My Contributions

* Developed embedded C firmware for ADC signal acquisition and measurement processing.
* Implemented waveform plotting on TFT LCD with voltage scale, time base, and grid display.
* Designed digital multimeter measurement functions including voltage, resistance, capacitance, temperature, and connectivity testing.
* Implemented user interface logic to switch between DMM mode and oscilloscope mode.
* Performed hardware testing and debugging to verify measurement accuracy and display output.

## Project Structure

```text
src/        Source code and the addition Libraries need
docs/       System architecture, hardware setup, and testing documentation
```

## Status

Completed
