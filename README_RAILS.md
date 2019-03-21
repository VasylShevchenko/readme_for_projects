# README EXAMPLE FOR RAILS

# Readme for ***NAME_PROJECT***

**Ruby on Rails** ***version***

**Ruby**  ***version***

**Node**  ***version***

**NPM**  ***version***

**Yarn**  ***version***

## Setup project

### 1. Dependency

##### Mac OS

- Install RMagick
    ```bash
    $ brew install imagemagick
    ```

- Install Redis
    ```bash
    $ brew install redis
    ```

- Install Yarn
    ```bash
    $ brew install yarn
    ```
    Chack version
    ```
    $ yarn --version
    ```
 
##### Ubuntu

- Install RMagick
    ```bash
    $ sudo apt-get install libmagickwand-dev
    ```

- Install Redis

    [How To Install and Secure Redis on Ubuntu 18.04](https://duckduckgo.com)
    
    ```bash
    $ sudo apt install redis-server
    ```

- Install Yarn
    ```bash
    $ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
    
    $ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
    
    $ sudo apt-get update && sudo apt-get install yarn
    
    $ yarn --version
    ```

- Install Node

    [n – Interactively Manage Your Node.js Versions](https://github.com/tj/n)
    
    [How can I update my nodeJS to the latest version?](https://askubuntu.com/questions/426750/how-can-i-update-my-nodejs-to-the-latest-version)

    [Upgrade Node.js via NPM](https://davidwalsh.name/upgrade-nodejs)

    ```bash
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
$ gem install bundler && bundle install
```

```bash
$ yarn install
```

```bash
$ rails db:create
```

```bash
$ rails db:migrate
```

#### Run project
```bash
that start rails local server

$ rails s 
```

or


```bash
$ raisl s -b your_ip
```

## 3. Testing


## 4. Deploy

### Deploy production

- <span style="color:red">If you add key in application.yml</span>.

    ```bash
    $ bundle exec cap production setup
    ```

```bash
$ cap production deploy
```

### Deploy staging

- <span style="color:red">If you add key in application.yml</span>.

    ```bash
    $ bundle exec cap staging setup
    ```

```bash
$ cap staging deploy
```

## 5. Other

