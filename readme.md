// How to create a node project
1. On terminal, mkdir a folder
2. With directory of the folder, command "npm init"
    - You can add -y if you want make npm with default setting
3. In the same folder, make a index.js and module.js using touch command
4. In the module.js, create anything you want to exports to index.js.
5. Import module.js file from index.js with require.
- ex) const myModule = require('module.js')
- You can also use import method.