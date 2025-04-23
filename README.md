# STM32 F767 Experiments 🚀

This repository documents my ongoing learning journey with the STM32F767ZI Nucleo board. Each folder in this repo is a small project that explores one concept or feature of embedded systems development using STM32 HAL.

## Projects

### 🔁 Echo_Back

- **Description:** Echoes back a single character received via UART.
- **Goal:** Verify UART receive and transmit logic using interrupts.

### ⌨️ Keyboard_Blink

- **Description:** Press a key in the serial terminal to toggle an LED on the Nucleo board.
- **Goal:** Create interaction between keyboard input and hardware output.

### 📡 Morse_Code

- **Description:** Converts a message typed in PuTTY into Morse code and flashes it using an LED.
- **Goal:** Combine UART input parsing with custom encoding and GPIO control.

### 💬 MulticharMessage

- **Description:** Echoes back full strings (rather than just characters) typed into the serial terminal.
- **Goal:** Handle complete messages and learn buffer management.

### 💡 nucleo_blink

- **Description:** A simple blinking LED using HAL and `HAL_Delay`.
- **Goal:** First test to verify setup, toolchain, and board functionality.

---

## 🛠 Setup

These projects are developed using:

- STM32CubeIDE
- STM32 HAL libraries
- STM32F767ZI Nucleo board
- PuTTY or similar terminal to test UART

---

## 📚 Notes

- Some folders may include `.ioc` files for STM32CubeMX configuration.
- Each project is kept self-contained and focused on one idea.
- Interrupt-based UART is used in most examples for real-time behavior.

---

## 📌 To Do

- [ ] Add DMA-based UART example
- [ ] Add command parser (e.g., type `led toggle`)
- [ ] Integrate onboard button input
- [ ] Port to FreeRTOS

---

Stay tuned! These are just the first few building blocks. ⚙️
