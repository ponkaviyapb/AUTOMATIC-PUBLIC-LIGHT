# AUTOMATIC-PUBLIC-LIGHTING

# Overview

This project presents an automated street lighting system using a Real-Time Clock (RTC) module for efficient power management and automation.

# Features

    Automatic ON/OFF using RTC: The street light operates automatically from 6 PM to 6 AM.
    IoT Control & Manual Switching: If the light is needed before 6 PM, it can be controlled via IoT applications or manual switches.
    Solar Power Integration: A solar panel automatically adjusts based on sunlight intensity to optimize energy harvesting.
    Battery Storage: Energy from the solar panel is stored in a lithium-ion battery for backup power.
    Smart Power Management:
    Summer Season: The system initially uses 20% of the lithium-ion battery voltage before switching to an external power source.
    Monsoon/Rainy Season: The initial 20% battery usage is disabled to preserve power.
    Battery Backup: If external power is interrupted, the light switches to battery power.
    Morning Usage (5 AM - 6 AM in Summer): If battery voltage is above 50%, the system uses the excess charge until it reaches 50%.
    Human Detection & Adaptive Brightness: A human detector sensor adjusts the light intensity based on presence, further reducing power consumption.

# Benefits

    Energy Efficiency: Maximizes solar energy usage, reducing reliance on external power.
    Cost-Effective: Decreases electricity costs and minimizes power wastage.
    Automated & Smart Control: Reduces human intervention and improves reliability.
    By integrating these features, this system provides a sustainable, smart, and cost-effective solution for automated street lighting.
