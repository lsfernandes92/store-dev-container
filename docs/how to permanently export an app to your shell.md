# how to permanently export an app to your shell

this consider that I am using **zsh** and **dotfiles**




## method 1
### open your terminal and run

```ruby
code ~/.dotfiles

# or

dotfiles
```




### create a path.zsh file

search or create the topic folder

create a **path.zsh** file inside it

for example:

```text
docker/
└── path.zsh
```

```ruby
# path.zsh
export DOCKER_DESKTOP="/Applications/Docker.app/Contents/Resources"

export PATH="$DOCKER_DESKTOP/bin:$PATH"
```




## method 2
### adding to your path

run the following:

```ruby
echo 'export PATH="/path/to/your/app:$PATH"' >> ~/.zshrc
```

for example:
```shell
echo 'export PATH="/Applications/Docker.app/Contents/Resources/bin:$PATH"' >> ~/.zshrc
```




### reload your shell configuration

by running:

```ruby
source ~/.zshrc


# or the alias


reload!
```




## verify if the command is working

`$ which <COMMAND>`



# references