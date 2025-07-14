# talks
talk about tecnology
This site plays slide presentations and articles stored on GitHub

## ShellScripting
This is a presentation about Shell Scripting. It covers the basics of what a shell is, what shell scripting is, and how to create and use shell scripts.

To run the presentation, you can use the `present` tool from the `golang.org/x/tools/present` package.

Example:
```bash
go get golang.org/x/tools/present
present -http=:3999
```
Then open your browser to `http://localhost:3999/shellscript/shellscript.slide`

### Scripts
The presentation includes the following scripts:
- `shellscript/scripts/argumentos.sh`: Demonstrates how to access command line arguments.
- `shellscript/scripts/comentario.sh`: Shows how to use comments in shell scripts.
- `shellscript/scripts/condicionalargumentos.sh`: An example of using conditional statements with arguments.
- `shellscript/scripts/shabang.sh`: Shows the usage of the shebang.
- `shellscript/scripts/variables.sh`: Demonstrates variable declaration and usage.
- `shellscript/scripts/variablesdef.sh`: A script with some variable definition errors to be corrected by the user.
