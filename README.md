# Understanding Jenkins


<br>

## Install Jenkins [^1]


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

<br>

## Jenkins

http://localhost:8080


<br>



## References

[^1]:
- <a href="https://www.macminivault.com/installing-jenkins-on-macos/">Installing Jenkins on macOS</a>
- <a href="https://www.jenkins.io/download/lts/macos/">macOS Installers for Jenkins LTS</a>
