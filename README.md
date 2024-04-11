# Heuristic-chess


# Human vs Computer Heuristic Chess
## Description 

This project is an implementation of a human vs. computer chess program utilizing heuristic algorithms with full control over the allowed moves of pieces. The project aimed to create a player program capable of making optimal moves based on two main criteria: maximizing material and maximizing hits on the opponent's pieces.
The implementation was carried out using object-oriented programming concepts and integrated into a Windows Presentation Foundation (WPF) interface for user interaction. The heuristic of maximum opponent hits was explored and incorporated into the decision-making process of the chess player.

## Features

- Classic chess gameplay with standard rules.
- User-friendly interface built with WPF.
- Highlights legal moves for pieces when selected.
- Monitoring illegal moves.
- Keeps track of game state, including check and checkmate conditions.
- All special rules included (En Passant, Castle King side, Castle Queen side, etc.).
- Responsive design for different screen sizes.
- Computer opponent playing with heuristic.
- Displaying the principles and computations of computer opponent.

# Hardware and Software Setup
## Hardware Requirements
- Processor: Intel Core i3 or equivalent
- RAM: 4GB or higher
- Storage: 100MB available space for installation

## Software Requirements
- Operating System: Windows 7 or later
- .NET Framework: Version 7.7.2 or later
- Microsoft Visual Studio: Version 2019 or later (for development)
- Windows Presentation Foundation (WPF): Included with .NET Framework

## Dependencies
- C# Programming Language: The chess game is implemented using C#.
- Windows Presentation Foundation (WPF): WPF is used for creating the graphical user interface (GUI) of the chess game.
- .NET Framework: The .NET Framework provides the runtime environment for executing C# code.

## Specific Configurations:
- Display Resolution: The chess game is optimized for a minimum display resolution of 1280x720 pixels to ensure proper visibility of game elements.
- Input Devices: The game supports input from standard keyboard and mouse devices. Touchscreen support may be implemented for touch-enabled devices.
- Network Connectivity: While the game is primarily designed for local multiplayer (human vs. human), online multiplayer functionality may be added in future iterations, requiring internet connectivity and server infrastructure.

## Additional Considerations:
- Compatibility: The chess game is developed and tested primarily on Windows-based systems. Compatibility with other operating systems (e.g., macOS, Linux) may vary and require additional testing and optimization.
- Performance: The performance of the game may vary depending on the hardware specifications of the user's system. Optimization techniques such as code profiling and performance tuning may be employed to enhance the overall performance and responsiveness of the game.

# Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MonicaMell/Heuristic-chess.git
   ```

Open the solution file ChessGame.sln in Visual Studio.
Build the solution (Ctrl+Shift+B) to restore NuGet packages and build the project.
Start the application by running the project (F5).

# Usage

    Upon starting the application, the chessboard is displayed along with the pieces in their starting positions.
    Click on a piece to select it. Legal moves for the selected piece will be highlighted.
    Click on a highlighted square to move the selected piece there.
    The game ends when a player's king is in checkmate.
    After human move, the computer opponent makes its move.
    It displays the criterion considered.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

    1.Fork the repository.
    2.Create a new branch (git checkout -b feature/new-feature).
    3.Make your changes and commit them (git commit -am 'Add new feature').
    4.Push to the branch (git push origin feature/new-feature).
    5.Create a new Pull Request.

## Credits

This Chess Game project is maintained by MonicaMell.
