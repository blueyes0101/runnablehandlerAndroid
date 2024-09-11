# Android Runnable and Handler Example

This is a simple Android application demonstrating how to use a **Runnable** and **Handler** to create a timer. The app starts a timer that updates every second and displays the elapsed time in a **TextView**. The user can start and stop the timer using buttons, and the elapsed time resets when the timer is stopped.

## Features
- A timer that updates every second using **Runnable** and **Handler**.
- Displays the elapsed time in a **TextView**.
- Ability to start and stop the timer with buttons.
- Resets the timer when stopped.
- Immersive UI with **EdgeToEdge** and **WindowInsetsCompat** for managing system bars.

## Technologies Used
- **Android Studio**
- **Java**
- **Handler** and **Runnable** for managing the timer.
- **EdgeToEdge** and **WindowInsetsCompat** for immersive UI.

## Code Overview

### Main Components
1. **MainActivity**:
   - Defines a **Handler** and a **Runnable** to update the **TextView** with the elapsed time.
   - **start(View view)**: Starts the timer and disables the start button.
   - **stop(View view)**: Stops the timer, resets the elapsed time, and re-enables the start button.
   - The timer updates every second using **handler.postDelayed()**.

### Methods
- **start(View view)**: Initializes and starts the timer. The timer runs continuously until stopped, updating the **TextView** every second.
- **stop(View view)**: Stops the timer, resets the elapsed time to 0, and allows the user to restart the timer.

### Layout
- A **TextView** displays the elapsed time.
- A **Button** to start the timer and another to stop and reset it.

## Getting Started

### Prerequisites
To run this project, you need:
- Android Studio installed on your computer.
- Basic knowledge of Kotlin/Java and Android development.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/blueyes0101/runnablehandlerAndroid.git
    ```

2. Open the project in Android Studio.

3. Build and run the project on an emulator or physical device.

## Usage

1. Press the "Start" button to begin the timer.
2. The **TextView** will update every second to show the elapsed time.
3. Press the "Stop" button to stop and reset the timer.

## Contributing
Feel free to contribute by opening issues or submitting pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
