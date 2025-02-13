# Music Playlist Manager

## Overview
The **Music Playlist Manager** is a C program that implements a playlist system using a queue data structure. It allows users to add songs to the playlist (enqueue) and play songs in order (dequeue). The program provides a simple command-line interface for managing a dynamic playlist.

## Features
- 🎵 **Add Songs** – Enqueue songs into the playlist.
- ⏯ **Play Songs** – Dequeue songs in order of insertion.
- 📜 **Display Playlist** – View the current list of songs.
- ❌ **Remove Songs** – Remove songs from the playlist.
- 🎶 **Simple Command-Line Interface** – Lightweight and easy to use.

## Repository Structure
```
Music-Playlist-Manager/
│── src/                  # Source code files
│── include/              # Header files
│── main.c                # Main program file
│── queue.c               # Queue implementation
│── queue.h               # Queue header file
│── Makefile              # Compilation script
│── README.md             # Project documentation
```

## Technologies Used
- **Programming Language**: C
- **Data Structures**: Queue (FIFO)
- **User Interface**: Command Line

## Installation
### Prerequisites
Ensure you have the following installed:
- GCC compiler

### Setup
```bash
# Clone the repository
git clone https://github.com/your-username/Music-Playlist-Manager.git

# Navigate to the project directory
cd Music-Playlist-Manager

# Compile the program
make

# Run the application
./playlist_manager
```

## Usage
1. **Start the Music Playlist Manager**
   ```bash
   ./playlist_manager
   ```
2. **Add songs** to the playlist by selecting the corresponding option.
3. **Play songs** in the order they were added.
4. **Remove songs** when needed.
5. **Exit the program** when done.

## Contributors
- **Bhavesh Mishra** *(Lead Developer)*

## Contributing
Contributions are welcome! If you find any issues or want to improve the project, feel free to fork the repository and submit a pull request.

---
Developed with ❤️ to enhance music management through simple programming.
