#Build Task Add-ons for Visual Studio Code

Misc. build tasks for the VS Code Editor. Syntax errors will be identified by Visual Studio's trademark red squiggly underlines and in the error listing (OSX: Cmd+Shift+M), in addition to the status bar.

Installation:

1. Create a task runner (tasks.json) if you have not done so already:
```
Command Palette -> Tasks: Configure Task Runner.
```
2. Add the desired task's json found here to your existing task runner.
3. Run task(s): 
```
Mac OSX: Cmd+Shift+B
```  

# Python Linter

Uses pylint to error check code.

```
pip install pylint
```

# Lua Linter

Uses luac to error check code. Generally included in lua distro.

# Ruby Linter

Uses ruby -wc to error check code.
