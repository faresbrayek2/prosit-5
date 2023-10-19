# Zoo Management System

This is a Java program for managing a zoo. The program includes classes and objects for managing different types of animals, such as aquatic and terrestrial animals, within a zoo.

## Table of Contents

- [Getting Started](#getting-started)
- [Features](#features)
- [Usage](#usage)
- [Classes](#classes)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To run this zoo management program, you'll need a Java development environment. You can compile and execute the program using Java.

## Features

- Create and manage a zoo with different types of animals.
- Add, remove, and display animals in the zoo.
- Check if the zoo is full.
- Compare two zoos to find the one with the most animals.
- Differentiate between aquatic and terrestrial animals.
- Display information about aquatic animals' swimming behavior.

## Usage

1. Clone the repository to your local machine.
2. Compile the Java source files using a Java development environment.
3. Run the `ZooManagement` class to execute the program.

## Classes

- `ZooManagement`: The main class that serves as the entry point to the program. It allows you to manage the zoo, add, and remove animals.

- `Zoo`: Represents the zoo and provides methods for adding, removing, and displaying animals. It can also compare zoos to find the one with the most animals.

- `Animal`: A superclass for different types of animals. It includes common attributes and methods for managing animals.

- `Aquatic`: A subclass of `Animal` representing aquatic animals. It includes information about the animal's habitat and swimming behavior.

- `Terrestrial`: A subclass of `Animal` representing terrestrial animals. It includes information about the number of legs of the animal.

- `Dolphin`: A subclass of `Aquatic` representing dolphins. It includes information about swimming speed.

- `Penguin`: A subclass of `Aquatic` representing penguins. It includes information about swimming depth.

## Contributing

Contributions to this project are welcome. You can open issues, suggest improvements, or submit pull requests.

## License

This code is available under the [MIT License](LICENSE).
