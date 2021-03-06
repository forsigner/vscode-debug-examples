# Use with npm 

## Quick experience

``` bash
git clone git@github.com:forsigner/vscode-debug-examples.git
cd JavaScript/use-npm
npm i
code .  # open in VScode
```

Then, put a breakpoint on the code in VSCode, press `f5`, and you will see the Debug toolbar.

## configurations

`package.json`

```json
{
  "scripts": {
    "dev": "node --nolazy --inspect app.js"
  }
}
```

`.vscode/launch.json`

```json
{
  "version": "0.2.0",
  "configurations": [
    {
      "type": "node",
      "request": "launch",
      "name": "use npm",
      "runtimeExecutable": "npm",
      "runtimeArgs": ["run-script", "dev"],
      "console": "integratedTerminal",
      "port": 9229
    }
  ]
}
```