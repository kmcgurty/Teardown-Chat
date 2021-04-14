# Teardown Chat
Teardown Chat is an open source chat client for the game Teardown. Is based off of [Nahu's TDU](https://github.com/nxhu64/TDU).

## Features
* In-game chat window
* Ability to move the window around and resize to fit your screen
* Commands - type /help in game to view them

## Todo
* SSL
* Account verification (after SSL). Usernames are not unique as of writing.
* Copy/paste
* User roles [Admin/Mod/VIP]
* More work on the server needs to be done (including the website)

## Installation
1. Download the latest release of [Teardown Chat-X.X.X.zip](http://github.com/kmcgurty/TDU/releases/latest).
2. Right click Teardown in Steam > Manage > click Browse Local Files
3. Extract the entire contents of Teardown Chat-X.X.X.zip to the folder that opened. Overwrite any files if necessary.

## Key binds
* T opens the chat window
* ESC or clicking out of the chat window closes it.

## Build requirements
* [MS Detours](https://github.com/microsoft/Detours)
* [GLEW](http://glew.sourceforge.net/)
* [Boost](https://github.com/boostorg/boost)

## Building:
1. Clone the repository **`git clone --recurse-submodules https://github.com/nxhu64/TDU`**
2. Open TDU.sln in Visual Studio 2019
3. On project properties->Debugging set the Command argument to your version of Teardown (SteamStub has anti-debugging, you'll have to figure how to circumvent that on your own) and set the working directory to Teardown's root directory (where the exe is located)
4. On VC++ Directories set your include/library directories for GLEW, MS Detours, and Boost.
5. Everything should be ready to build.

## Special thanks to
* [Nahu](https://github.com/nxhu64/) Seriously wouldn't have been possible without Nahu's work!
* [SK83RJOSH](https://github.com/SK83RJOSH)
* [Xorberax](https://github.com/ss-gnalvesteffer)
* [Nymda](https://github.com/nymda)
