# Debug React in VSCode

The example in this article uses create-react-app to create a React project, and the code shows how to use the most basic debugging methods in VSCode.

## Quick experience

``` bash
git clone git@github.com:forsigner/vscode-debug-examples.git
cd TypeScript/react-app
npm i & npm start
code .  # open in VScode
```

Then, put a breakpoint on the code in VSCode, press `f5`, and you will see the Debug toolbar.

## Advanced

In the above, we use the `launch` mode to debug. In real development, it is recommended to use the `attach` mode for debugging, which will be more flexible. See: [Use `attach` in react (Advanced)](/JavaScript/react-app-attach/README.md)




