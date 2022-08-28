# Vocal01 tech stack extraordinaire :rainbow: :star:

## Clone the repo first

```sh
git clone git@github.com:Pefington/stack-vocal01.git
```

## To use this stack, there is a _small_ installfest

```sh
# 1. First install Ruby 3.0.4
rvm install 3.0.4

# 2. Then install NVM: Node Version Manager. It's like RVM for Node.JS
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

# 3. Then install Node.JS v16.17.0. LTS means "Long Term Support"
nvm install --lts

# 4. If it goes "nVm: cOmMaNd NoT fOuNd" then reload your shell config:
source ~/.zshrc
# or
source ~/.bashrc

  # 4.1 Check you're good:
  node -v

# 5. Install yarn, it's a package manager for Node.JS, like bundle for gems.
sudo npm install -g yarn

  # 5.1 Check you're good:
  yarn -v

# 6. Install the project dependencies:
bundle # is like 'bundle install' and will install all the gems
# then
yarn # is like 'yarn install' and will install all the Node.JS packages
```

## Now you can run vscode

### - Go to your extensions and search `@recommended`

You will see **WORKSPACE RECOMMENDATIONS**.
Workspace in VSCode means project (folder).

- **Git Cheatsheet**: Optional, shows git commands for the CLI.

- **Git Lens**: Mandatory:exclamation:, will give you git commands in the editor.

- **Github Pull Request**: Recommended, asks you if you want to create a pull request when you push a new branch.

- **Git Graph**: Optional, shows git branches history in a graph.

- **VSCode Ruby**: Mandatory:exclamation:.

- **ruby-rubocop-revived**: Mandatory:exclamation:, linter and formatter for Ruby.

- **Ruby Solargraph**: Recommended, adds Ruby autocompletion.

- **Rails Snippets**: Recommended, adds Rails snippets.

- **Endwise**: Recommended, automatically adds 'end' when you start a Ruby block.

- **Tailwind CSS Intellisense**: Mandatory:exclamation:, adds Tailwind CSS autocompletion and tells you what pure CSS is applied for a given class.

- **ESLint**: Mandatory:exclamation:, linter for JavaScript.

- **Prettier**: Mandatory:exclamation:, formatter for JavaScript, CSS and many other languages.

- **ERB Formatter/Beautify**: Mandatory:exclamation:, formatter for ERB.

- **HTML CSS Support**: Recommended, adds classes and ids to HTML.

- **Highlight Matching Tag**: Recommended, highlights matching tags in HTML.

- **Auto Rename Tag**: Recommended, automatically renames closing tags in HTML.

- **Color Highlight**: Optional, gives a bigger area to see the color preview in HTML/CSS.

- **Sass**: Optional, adds Sass support. We probably won't use it.

## What's different in this stack ?

Well now we have a package.json as well as a Gemfile.
It's like a Gemfile, but for Node.JS packages instead of Ruby gems.

Ideally, we want to use the gems for backend utilities and the node packages for frontend utilities.
Tailwind-rails is the exception, it's a Ruby gem for Rails. I couldn't get Tailwind to work without it.

## Usage

```sh
# Run the localhost dev server (port is 3000)
yarn dev

# Before committing, run the linter
yarn formatall
```

We have a short week to decide if the stack is valid for the final project.

## :crossed_fingers::crossed_fingers::crossed_fingers:
