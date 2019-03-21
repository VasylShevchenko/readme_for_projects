# README EXAMPLE FOR ANGULAR with Capistrano for deploy

# Readme for ***NAME_PROJECT***

**Angular**  ***version***

**Ruby**  ***version***

**Node**  ***version***

**NPM**  ***version***

**Yarn**  ***version***

## Setup project

### 1. Dependency

##### Mac OS

- Yarn
    ```bash
    Install Yarn
    $ brew install yarn
    
    Chack version
    $ yarn --version
    ```
 
##### Ubuntu

- Yarn
    ```bash
    Install Yarn
    $ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
    
    $ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
    
    $ sudo apt-get update && sudo apt-get install yarn
    
    $ yarn --version
    ```

- Node

    [n – Interactively Manage Your Node.js Versions](https://github.com/tj/n)
    
    [How can I update my nodeJS to the latest version?](https://askubuntu.com/questions/426750/how-can-i-update-my-nodejs-to-the-latest-version)

    [Upgrade Node.js via NPM](https://davidwalsh.name/upgrade-nodejs)

    ```bash
    Install Node
    
    $ sudo npm cache clean -f
    
    $ sudo npm install -g n
    
    $ sudo n stable
    ```

### 2. Project

```bash
$ git clone project_url_on_git
```

```bash
$ cd project_folder
```

```bash
$ yarn install
```

```bash
$ npm install
```


#### Run project

```bash
$ ??????
```

or


```bash
$ ?????
```

## 3. Testing


## 4. Deploy

```bash
$ gem install bundler && bundle install
```

### Deploy production

```bash
$ cap production deploy
```

### Deploy staging

```bash
$ cap staging deploy
```

## 5. Other

