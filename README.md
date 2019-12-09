# LSP-settings-sublime
LSP settings for Sublime text 3 with Powershell.  
See link below on integration of LSP Powershell with Sublime text 3:  
1. https://lsp.readthedocs.io/en/latest/#powershell  
2. https://github.com/tomv564/LSP

## Prerequisites
1. Powershell core executable `pwsh` should be in your PATH.

## Notes
1. With Powershell core, you cannot and don't need to download Powershell help files with `Update-Help`.

## How to use
1. Download and extract the latest (stable) release of PowerShellEditorServices.  
https://github.com/PowerShell/PowerShellEditorServices
2. Install Sublime package - Powershell (for syntax highlight).  
https://packagecontrol.io/packages/PowerShell  
3. Install Sublime package - LSP (for intellisense, etc.).  
https://packagecontrol.io/packages/LSP  
4. In Sublime menu: Preferences -> Package settings -> LSP -> Settings. Edit this file as fit.
5. Contents of file `LSP.sublime-settings` can be copied over the config in step 4.

Happy coding.
