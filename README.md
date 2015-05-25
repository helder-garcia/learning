# elearning
======

## Elearning system
-----------------------------------------------------------------
A frontend app for a elearning system

### Installation
-----
Install NVM

    curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.25.3/install.sh | bash

or Wget:

    wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.25.3/install.sh | bash

To activate nvm, you need to source it from your shell:

```
    . ~/.nvm/nvm.sh
```
    
Or just open a new shell.

Install the stable version of node using:

```
 nvm install stable
```

Select to use stable version:

```
 nvm use stable
```

Run the folowing commands on the root directory of the project:

```
 npm install -g grunt-cli
 
 npm install

 bower install
```

### Building the app

#### Building from source method #1:

This method is faster and recommended while in development.

```
 grunt build:d --min false --theme html
 grunt build:d --min false --theme angular
```

Will generate dist/themes/html and dist/themes/angular directories containing the resulting build files.

#### Building from source method #2:

This method is slower and recommended for the final build.

```
 grunt build:dm --theme html
 grunt build:dm --theme angular
```

Will generate dist/themes/html and dist/themes/angular directories containing the resulting build files.

#### Starting the built-in BrowserSync web server and watchers

```
 grunt --theme html --min false
 grunt --theme html
```

### Credit
------
Helder Garcia <br />
<a href="http://www.sounerd.com.br/">SouNerd.com.br</a> <br />
