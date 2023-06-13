# UwUtopia [![Status Zero][status-zero]][andivionian-status-classifier]
[andivionian-status-classifier]: https://github.com/ForNeVeR/andivionian-status-classifier#status-zero-
[status-zero]: https://img.shields.io/badge/status-zero-lightgrey.svg

## Manifesto 

### Genereal

- Full managed code
- Developer-friendly
- Clean code and design are preferred for future implementation
- No Legacy Code
- No Legacy Protocol 
- No Legacy Solution 
- Target on Linux/Windows 
- This project is not intended for mobile platforms 

### HMI

- HMI is only client NO MORE
- ModbusTCP/OPC UI/MQTT NO MORE
- We will not use FBD or IEC 61131-3 programming language for HMI scripting because its cringe and not align with modern approaches to UX/UI development
- C# and Lua(probably) HMI scripting
- We will support touch for platforms that are compatible with Avalonia UI

### Editor

- Support C# and Lua scripting to generate HMI panels
- WYSIWYG editor for HMI
- Beautiful and consistent property view
- Reduce the pain during HMI coding

### Storage Concept

- We will store timeline process values in a specialized database, not using MS SQL, PostgreSQL, or MySQL because - cringe
- We will store configuration in an embedded database, not using MS SQL, PostgreSQL, or MySQL because - cringe
- Complete storage configuration from UI, including redundancy policies, storage strategies, and more

### Out Stack:
    
- Avalonia UI for HMI/Editor
    - Zero Reactive UI
    - Rx when needed
- Dotnet for everything else 
