<div align="center"><a name="readme-top"></a>

<img height="500" width="100%" src="https://github.com/seths10/personal-vscode-config/assets/59029978/3cca62b5-94d0-4605-9826-c9cd79d2ee8a" style="object-fit: cover; border-radius: 8px;" >

<br/>

<h3>Personal VSCode config</h4>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)
</div>

### 📦 Extension & Tools

Here is a list of the packages available in this repository:

| Extensions or Tool                             | Type                                                              |
| ---------------------------------------- | ------------------------------------------------------------------------ |
| `Monokai Pro (Filter Octagon)`           | VSCode Theme Extension              |
| `Apc Customize UI++`   | VSCode extension for customizing it        |
| `Moxer Icons`           | VSCode folder themse          |
| `Indent rainbow` | VSCode extension - Line for code |
| `Cascadia Code` | Font family |
| `CaskaydiaCove Nerd Font` | Terminal nerd font - contains icons  |
| `Git Bash` | Terminal  |
| `Starship` | Terminal Prompt  |
| `C Spell` | VSCode extension - Checks for wrong spellings  |
| `Toggle Excluded Files` | VSCode extension for hidding certain folders from view  |

<br/>

### 🔨 Starship Setup

> Make sure there is a Nerd Font and scoop installed on PC,
> then run:

```bash
scoop install starship
```

now, update your `.bashrc` file with:

```bash
eval "$(starship init bash)"
```

> You can add further configurations in this file:  `~/.config/starship.toml` (create one if it doesn't exist)
>
> ```bash
> "$schema" = 'https://starship.rs/config-schema.json'
> add_newline = true
>
> # Replace the '❯' symbol in the prompt with '➜'
> [character] # The name of the module we are configuring is 'character'
> success_symbol = '[➜](bold green)' # The 'success_symbol' segment is being set to '➜' with the color 'bold green'
>
> ```
>

<br/>

### 🔨 Setup

```tsx
install extensions
install font (Cascadia Code)
install terminal (bash and starship)

update Settings.JSON
```

<br/>

> [!NOTE]
> 
> This is my vscode setup
