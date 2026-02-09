### .zshrc.minimal

1. Set theme to be `ys`

2. Add plugins to be 

```
plugins=(
	git
	z
	zsh-autosuggestions
	zsh-syntax-highlighting
)
```

### .p10k.zsh

Configure the zsh prompt to be in the form:

```
([Python_icon] [conda_env_name] if conda env activated)
[System Icon] username @ hostname in [path icon] [current/path] [time_icon] [HH:MM:SS]
```