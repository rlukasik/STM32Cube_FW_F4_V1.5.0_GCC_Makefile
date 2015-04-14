# STM32Cube_FW_F4_V1.5.0_GCC_Makefile
Port of STM32Cube_FW_F4_V1.5.0 to ARM GNU Toolchain environment. Makefiles added to oryginal STM32CubeF4: http://www.st.com/web/catalog/tools/FM146/CL2167/SC2004/PF259243. Preconfigured for NUCLEO-F401RE but settings can be changed in top Makefile.

#Build
OpenOCD 0.8.0 is required to use NUCLEO-F401RE with ST-LINK/V2-1 debugger. For ST-LINK/V2 OpenOCD 0.7.0 is enough.

* To build the project type: 'make'
* Clean project: 'make clean'
* Flash binary output to flash: 'make flash'
* Debug in GDB: './arm-gdb'; in gdb type: 'file main.out' 'load'

The compiled project files are in folders 'Src' and 'Inc' on top of the direcories tree.
The examples and templates are in 'Projects'. Currently in 'Src' and 'Inc' is example STM32F401RE-Nucleo/Examples/UART/UART_Printf.
To use other example copy appropriate files from example folder to top 'Src' and 'Inc'.

#Keywords
STM32CubeF4, GNU, GCC, Makefile, GDB, Linux, Internet of Things, IoT, mbed, ARM, Cortex-M, NUCLEO-F401RE, STM32F401RET6, ST-LINK/V2-1, arm-none-eabi, OpenOCD
