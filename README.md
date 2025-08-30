🚀 STM32 OTA Firmware Update Projects
This repository demonstrates Over-The-Air (OTA) firmware update mechanisms on STM32 microcontrollers using different communication interfaces. 
The project progresses from a simple UART bootloader to Wi-Fi and Ethernet-based OTA with security.


⚙️ Hardware Used

STM32F407G-DISC1 (Cortex-M4)
STM32F767ZI Nucleo (Cortex-M7, Ethernet capable)
ESP8266 Wi-Fi Module (for F4 board OTA)
USB-TTL converter (for initial bootloader debugging)




🛠️ Software & Tools

STM32CubeIDE or Keil uVision for firmware development
STM32CubeProgrammer (initial programming, testing)
FreeRTOS (task scheduling, OTA over Ethernet)
LwIP stack (TCP/IP networking on STM32F7)
Python and C/C++ script or PC tool for sending firmware over UART
HTTP Server (local Python server or cloud server for OTA binaries)
