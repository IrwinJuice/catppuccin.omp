<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://ohmyposh.dev/">Oh My Posh</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>
<h4  align="center"><a href="https://github.com/Microsoft/Terminal">Windows Terminal</a></h4>

## catppuccin.omp
![catppuccin](https://github.com/IrwinJuice/catppuccin.omp/blob/main/catppuccin.png)

## catppuccin_short.omp
![catppuccin_short](https://github.com/IrwinJuice/catppuccin.omp/blob/main/catppuccin_short.png)

## Usage 
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

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
