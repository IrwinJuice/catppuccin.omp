<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://ohmyposh.dev/">Oh My Posh</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

![catppuccin](https://github.com/IrwinJuice/catppuccin.omp/blob/main/assets/catppuccin_all.png)
# Previews

<details>
<summary>Mocha</summary>
<img src="https://github.com/IrwinJuice/catppuccin.omp/blob/main/assets/catppuccin_mocha.png"/>
</details>
<details>
<summary>Macchiato</summary>
<img src="https://github.com/IrwinJuice/catppuccin.omp/blob/main/assets/catppuccin_macchiato.png"/>
</details>
<details>
<summary>Frappe</summary>
<img src="https://github.com/IrwinJuice/catppuccin.omp/blob/main/assets/catppuccin_frapp.png"/>
</details>
<details>
<summary>Latte</summary>
<img src="https://github.com/IrwinJuice/catppuccin.omp/blob/main/assets/catppuccin_latte.png"/>
</details>

## Usage ([Windows Terminal](https://github.com/Microsoft/Terminal))

- Install [Oh My Posh](https://ohmyposh.dev/)
- Creat $PROFILE (run in PowerShell)
```
New-Item -Path $PROFILE -Type File -Force
```
- Clone catppuccin.omp.json or catppuccin_short.omp.json into any folder, for example C:\Users\<username>\AppData\Local\oh-my-posh
- Open $PROFILE (run in PowerShell)
```
notepad $PROFILE  
```
-  Copy next line into the opened $PROFILE and save (**DON'T forget to change PATH**):
```
oh-my-posh init pwsh --config 'C:\Users\<username>\AppData\Local\oh-my-posh\catppuccin_short.omp.json' | Invoke-Expression
```
- Reload you $PROFILE (run in PowerShell)
```
. $PROFILE
```

See official documentation for 
- [Linux](https://ohmyposh.dev/docs/installation/linux) or [MacOS](https://ohmyposh.dev/docs/installation/macos) installation
- [Prompt](https://ohmyposh.dev/docs/installation/prompt) configuration

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
