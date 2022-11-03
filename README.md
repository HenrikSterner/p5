# Formål

Dette projekt har til formål at få p5.js til at fungere sammen med bl.a. es-lint.

# Opsætning

- Installér Visual Studio Code [https://code.visualstudio.com/](https://code.visualstudio.com/).
- I Visual Studio Code skal du installere Microsofts eslint-plugin. Det kan gøres på en af følgende måder:
  1. Fra plugin-menuen søg på `ESlint`. Vælg det første plugin, der kommer frem (Microsoft har publiceret det). 
  2. Fra quick-open-menuen i Visual Studio Code (Win: Ctrl+P, Mac: Cmd+P) køres kommandoen:
     ```
     ext install dbaeumer.vscode-eslint
     ```
- Installér node.js [https://nodejs.org/en/](https://nodejs.org/en/).
- Åbn Visual Studio Code.
- Åbn kommando-paletten (Win: Ctrl+Shift+P, Mac: Cmd+Shift+P).
- Klon projektet. Det kan gøres på en af følgende måder:

  1. Fra kommando-paletten i Visual Studio Code vælges `Git: Clone`.
  2. Fra en terminal køres kommandoen: 
     ```
     git clone git@github.com:PeterSterner/p5.git
     ```
- Installér projektets afhængigheder (enten fra kommando-paletten med `Run task` eller fra en terminal):
  ```
  npm install
  ``` 
- Kør nu følgende script fra en terminal for at starte en webserver, der viser en p5-sketch fra `explosion.js`, der ligger i mappen `src`
  ```
  npm run sketch
  ```  
  (Genvejen til at køre `ńpm run sketch` er  Win: Ctrl+Shift+B, Mac: Cmd+Shift+B).
