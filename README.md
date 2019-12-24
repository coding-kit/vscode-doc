# vscode setup customization

### VSCode commands

#### Extension Setup Commands
1. Set the root path for extensions.
```sh
code --extensions-dir <dir>
```
2. List the installed extensions.
```sh
code --list-extensions
```
3. Show versions of installed extensions, when using --list-extension.
```sh
code --show-versions
```
4. Installs an extension.
```sh
code --install-extension (<extension-id> | <extension-vsix-path>)
```
5. Uninstalls an extension.
```sh
code --uninstall-extension (<extension-id> | <extension-vsix-path>)
```
6. Enables proposed API features for extensions. Can receive one or more extension IDs to enable individually.
```sh
code --enable-proposed-api (<extension-id>)
```
----
