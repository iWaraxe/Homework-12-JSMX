# Design Patterns Homework Assignment

## Objective

The aim of this assignment is to implement the Observer, Strategy, and Command design patterns in a Java application. Each pattern is to be applied in a specific context as detailed below.

### Observer Pattern

#### Task
Implement a weather monitoring system where a `WeatherStation` class (Subject) notifies multiple `WeatherDisplay` classes (Observers) whenever there's a change in temperature, humidity, or pressure.

#### Requirements
- `WeatherStation` should allow adding and removing observers.
- `WeatherDisplay` classes should update their displays whenever notified by `WeatherStation`.

### Strategy Pattern

#### Task
Create a text editor application that can perform different types of text formatting (e.g., upper case, lower case, and sentence case).

#### Requirements
- Use the Strategy pattern to encapsulate the different text formatting algorithms.
- Allow the user to switch between different formatting strategies at runtime.

### Command Pattern

#### Task
Build a simple home automation system where you can control lights, fans, and other devices through a remote control.

#### Requirements
- Implement a `RemoteControl` class that can store multiple commands.
- Each device (light, fan, etc.) should be controlled by a specific command (`LightOnCommand`, `FanOffCommand`, etc.).

## Due Date

Please submit your homework in a week. This will give you sufficient time to implement and understand these patterns, and also prepare any questions you may have for the next session.
