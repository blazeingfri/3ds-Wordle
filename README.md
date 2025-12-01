# Wordle-3DS
A fully playable Wordle clone built for the Nintendo 3DS using devkitARM & libctru.


🎮 About the Project

Wordle-3DS is a homebrew port of the classic Wordle word-guessing game, rewritten in C++ and designed to run natively on Nintendo 3DS systems.

The project includes:

•6 guesses per game

•Full 5-letter scoring logic

•Green / Yellow / Gray tile rules

•Optional Hard Mode (must reuse revealed hints)

•Keyboard input through 3DS buttons


This is my personal 3DS homebrew project created for fun and to learn devkitARM + libctru development.


📦 Features

✔ Authentic Wordle logic

✔ Hard Mode using previous clues

✔ Clean console rendering

✔ Fast input + simple UI

✔ Works on Homebrew Launcher (3DSX)

✔ Compiles to .3dsx, .elf, and .smdh



🧠 How It Works

The game uses:

Console API from libctru for text rendering
HID for button input
A modified Wordle scoring function
A loop-based frame update cycle
3DS homebrew SMDH metadata through Makefile configuration


All logic is in source/main.cpp.



🛠 Building From Source

Requirements:
Install devkitARM + msys2 using devkitPro Updater.

Inside MSYS2 terminal:
git clone https://github.com/YOUR_USERNAME/Wordle-3ds.git
cd Wordle-3ds
make

Output files will be in:
Wordle-3ds.3dsx
Wordle-3ds.smdh
Wordle-3ds.elf


🤝 Credits

devkitPro — devkitARM toolchain

smealum — libctru & 3DS Homebrew Launcher

Original Wordle by Josh Wardle (This is a fan-made project for educational purposes.)



📜 License

This project is open source for educational/homebrew use. Wordle is a trademark of its respective owners; this project is not affiliated with them.
