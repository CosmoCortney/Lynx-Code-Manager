# Lynx-Code-Manager
A Cheat Code Manager for PC games (Windows)

Description:
This tool allows you to execute Cheat Codes similar to the Action Replay or GameShark ones.
You can create, edit and save cheat lists for each game.
This tool comes with a Memory viewer which can be opened multiple times to watch more than one memory area.
Last but not least it can be used to create memory dumps.

Features:
- Execute Cheat Codes to manipulate games in real-time
- Create, edit and save cheat lists
- Adjust the execution times per second
- Memory Dumping
- Build-in Memory Viewer
  - Can be opened as many times you with to watch multiple memory locations
  - Manually refresh the memory view
  - or automatically refresh the memory view (60 times a second)
  - Memory View is in Little Endian
  - The clicked Address can be read as Byte, 2 Bytes, 4 Bytes or 8 Bytes
  - The hex representation on the left is in Big Endian for easy readability
  - Signed and unsigned dec representations beneath
  - Poke any custom value back into memory
Codehandler
  - Supports Cheat values of 8, 16, 32 and 64 bits of length
  - Huge Variety of Code Types (View the Code Type Documentation for more details)
    - RAM Writes
    - String Writes
    - Skip Writes
    - Conditional: if key is pressed (experimental)
    - Conditional value comparision
    - Conditional: if value between
    - Load integer (scalar and packed)
    - Store Integer (scalar and packed)
    - Operate Integer (scalar and packed)
    - Load Float Single (scalar and packed)
    - Store Float Single (scalar and packed)
    - Operate Float Single (scalar and packed)
    - Load Float Double (scalar and packed)
    - Store Float Double (scalar and packed)
    - Operate Float Double (scalar and packed)
    - Load Pointer
    - Add Offset to Pointer
    - End if
    - Branch here if pointer is invalid
    - No Operation/Place Holder
