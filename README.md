# Understanding Jenkins


<br>

## Install Jenkins


```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

```shell
brew doctor
```

```shell
brew install java11
```

```shell
brew install jenkins-lts
```

<br>


## Start Jenkins Services

Start the Jenkins service

```shell
brew services start jenkins-lts
```

Restart the Jenkins service

```shell
brew services restart jenkins-lts
```

Update the Jenkins version

```shell
brew upgrade jenkins-lts
```
