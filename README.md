# how to get start with dev containers

dev containers is a **full-featured development environment**

it uses **containers** and we don't need to install ruby, rails or its **dependencies on the machine**

it's the **fastest way** to get your ruby on rails application up and running




## setup and installation

### installing docker

for mac, install [docker desktop](https://docs.docker.com/desktop/setup/install/mac-install/)




### installing vs code

install [vs code](https://code.visualstudio.com/)

install [dev container extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

dev container extension allows you to open any folder inside a container

**devcontainer.json** file tells vs code how to access or create a container, spin up containers, access terminal, debug, etc...




### installing rails-new

uses the new application generator and docker to generate the rails app without having to install rails and its dependencies

to install, see the instructions [in the readme](https://github.com/rails/rails-new?tab=readme-ov-file#installation)

see [how to permanently export an app to your shell](./docs/how%20to%20permanently%20export%20an%20app%20to%20your%20shell.md) to export the **rails-new** command




## creating the store app

run `rails-new store --devcontainer`




## opening an verifying the app in dev container

open the app folder on vs code

once open, vs code will prompt that found a dev container config. click on **"reopen in container"** button

verify if it work running `rails --version`




# references
- [(rails guides) # Getting Started with Dev Containers](https://guides.rubyonrails.org/getting_started_with_devcontainer.html)
- [install docker desktop on mac](https://docs.docker.com/desktop/setup/install/mac-install/)
- [rails-new](https://github.com/rails/rails-new?tab=readme-ov-file#installation)
- [how to permanently export an app to your shell](./docs/how%20to%20permanently%20export%20an%20app%20to%20your%20shell.md)