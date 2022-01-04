# bureau

Fork of https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau. 

Requires oh-my-zsh, antigen and kube-ps1

## Installation
Add the following snippet to your `.zshrc`

```
source /path/to/kube-ps1.sh
antigen theme aopal/bureau@main bureau
```

## Customizations

- Add kubernetes status via [kube-ps1](https://github.com/jonmosco/kube-ps1) to the right-hand prompt.
- Color the prompt based on the last command's status