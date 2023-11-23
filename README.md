# ECUAL

## Overview

Electric Control Unit Abstraction Layer (ECUAL) is one of the layers in the Software Architecture to isolates the application layer from the HAL driver. For a full explanation on this, visit [Adding ECUAL Drivers](https://deepbluembedded.com/adding-ecual-drivers-to-your-stm32-project-configurations-options/).

The ECUAL design and purpose is the same as [Autosar Software Architecture](https://automotiveembeddedsite.wordpress.com/why-autosar-what-it-is/). Which is to separate application and hardware layers. Which are to make that the application code not tied to the hardware code.

This project will use ECUAL into board **nucleo-L010RB**. The objective of this project is to be able to port the same application layer across multiple hardware layers of any MCUs. To prove the ECUAL is not tied to one hardware this project will support another microcontroller which will soon be finalized.  

The application layer will test on several i/o and communication drivers. As listed:-

<ol>
  <li>IO Drivers</li>
  <ol>
    <li>Digital I/O</li>
    <li>PWM</li>
    <li>ADC</li>
  </ol>
  <li>Communication Driver</li>
    <ol>
        <li>UART</li>
        <li>SPI</li>
        <li>I2C</li>
    </ol>
</ol>

## File Structure

└───docs
