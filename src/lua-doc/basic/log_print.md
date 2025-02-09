> **⚠️ Disclaimer:** The Nrbbr3d Engine V2 Lua API is still in development and will change in the future. It may be partially incomplete or out of date.  
> 📖 [Read more](/Lua%20API%20reference.html#important)

# log_print

## Description

Prints a message to the console.

## Usage

```lua
log_print(typ, modul, message)
```

### Parameters

- `typ`: The type of the message. Can be set to everything, but it's recommended to use `Normal`, `Warning` or `Error`.
- `modul`: The module that the message belongs to. Like `your mod name`.
- `message`: The message to print. Can be anything.

### Return value

None.

### Example

```lua
log_print("Normal", "Example Mod Name", "Hello World!")
```

Output:

```
Normal, Module: Example Mod Name, Hello World!
```

### C++ Implementation

```cpp  
log::log_print(std::string typ, std::string modul, std::string message)
```
