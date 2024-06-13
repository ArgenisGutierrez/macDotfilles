# Requirimientos para la configuracion.
>[!warning] Nota
Esta configuracion funciona con macs con procesador intel para los modelos con series M algunas aplicaciones necesitan configuraciones extras.
## Hombrew https://brew.sh/
El mejor manejador de paquetes para mac desde el cual obtendremos todo lo necesario para nuestra configuración.
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Alacratty https://alacritty.org/
El emulador de terminal que usaremos.
```bash
brew install alacratty
```

## Zsh Autosuggestion https://github.com/zsh-users/zsh-autosuggestions
Sugerencias de autocompletado para terminal.
```bash
brew install zsh-autosuggestions
```

## Zsh Syntax Highlight https://github.com/zsh-users/zsh-syntax-highlighting
Resaltado en terminal para comando correctos o errores.
```bash
brew install zsh-syntax-highlighting
```
## Neovim  https://neovim.io/
Nuestro editor preferido del cual requerimos al menos la version 0.10.0.
```bash
brew install neovim
```

## Fzf https://github.com/junegunn/fzf
El plugin buscador de archivos.
```bash
brew install fzf
```

## gcc
Un conjunto de compiladores necesarios para algunas de nuestras aplicaciones.
```bash
brew install gcc
```

## Eza https://github.com/eza-community/eza
Una version mejorada del comando ls.
```bash
brew install eza
```

## Zoxide  https://github.com/ajeetdsouza/zoxide
Una version mejorada del comando cd.
```bash
brew install zoxide
```

## Zellij https://zellij.dev/
Mejora para la terminal permitiendo la creacion de paneles, tabs, etc.
```bash
brew install zellij
```

## Yabai https://github.com/koekeishiya/yabai
El tailing window manager para Mac.
```bash
brew install koekeishiya/formulae/yabai
```
Para funcionar yabai es necesario desactivar el System Integrity Protection de Mac:
1. Apagar el equipo.
2. Presionar Command + R para entrar en modo recovery.
3. En el menu seleccionar Utilities y seleccionar Terminal.
4. csrutil disable --with kext --with dtrace --with nvram --with basesystem
5. Reiniciar.
Para mejor información revisar la documentación de yabai https://github.com/koekeishiya/yabai/wiki
Iniciamos el servicio de yabai:
```bash
yabai --start-service
```
## Skhd https://github.com/koekeishiya/skhd
Lo que nos permitira definir nuestros hotkeys para manejar las ventanas.
```bash
brew install koekeishiya/formulae/skhd
shkd --start-service
```

