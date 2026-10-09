🏎️ RACECUBE Custom Dashboard Project

Welcome to the RACECUBE Custom Dashboard repository! 🏁
This isn't just a standard gauge cluster setup — it’s a highly complex, fully custom-built instrument panel designed from the ground up for a very specific, one-of-a-kind automotive build. 🛠️✨
🌟 About the Project

The goal of this project was to create a modern, highly responsive, and fully customizable analog dashboard managed by an ESP32-S3 microcontroller. It reads real-time telemetry via CAN-bus (OBD2) and ESP-NOW, drives 10 independent stepper motors, and controls 15 LED indicators, all calibratable through a built-in Wi-Fi Web Server! 📱⚙️
🧟‍♂️ The Hardware "Frankenstein"

We took the best parts from legendary JDM cars and combined them into one ultimate cluster:

    The Housing: The main dashboard casing is sourced from a Mitsubishi FTO 🚙, giving it that classic, aggressive sports car layout.

    The Guts: The mechanical internals and stepper motors were harvested from TWO Toyota Altezza dashboards ⚙️.

    The Aesthetics: To make it truly ours, the gauge dials (scales) and the LED backlighting system were 100% custom-made to order 🎨💡.

🐉 The Ultimate Destination: Evo V Wagon

This dashboard is being specifically built and programmed for a completely unique, heavily modified project car.
It will be installed in a custom Mitsubishi Lancer Evolution V Wagon 🚘🔥 featuring an insane spec list:

    Engine: Swapped to a 4B12 Turbo 🐌💨

    Drivetrain: Full AWD system retrofitted from a Mitsubishi Airtrek 🛤️

    Transmission: A highly customized W5A51 Automatic Transmission, beefed up with reinforced planetary gears from an A5HF1 (A300) to handle the extreme torque! 🦾💥

💻 Tech Specs & Features

    🧠 Brain: ESP32-S3 Microcontroller.

    🧭 Motor Control: 10 stepper motors driven by 3x PCA9685 I2C PWM drivers with a custom microstepping sine-wave algorithm.

    🚦 Indicators: 15 physical LED warning lights controlled via a PCF8575 I2C expander.

    📡 Data Sources: Direct CAN-bus reading (VP1050 module), ESP-NOW wireless telemetry, and direct Digital/Analog GPIO inputs (via PC817 optocouplers).

    🌐 Web Dashboard: Built-in Wi-Fi Access Point with an HTML interface to calibrate zero-offsets, working angles, scaling multipliers, and lamp inputs on the fly!

Built with passion, caffeine, and lots of burnt wire insulation. Let's race! 🏁🚀
