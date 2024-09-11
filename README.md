# Great Code Off

Write an application that calculates which customer spent the most money in our store and displays his/her name, surname, and total amount spent.

https://github.com/Alex75-V1/tgco-2409

## Install Micronaut

Simply open a new terminal and enter:
```bash
$ curl -s https://get.sdkman.io | bash
```

Follow the on-screen instructions to complete installation.
Open a new terminal or type the command:
```bash
$ source "$HOME/.sdkman/bin/sdkman-init.sh"
```
Then install the latest stable version of the framework:
```bash
$ sdk install micronaut
```
If prompted, make this your default version. After installation is complete it can be tested with:
```bash
$ mn --version
```

## Creating Application
```bash
mn create-app com.version1.great-code-off-team7 \
--features=http-client,graalvm \
--build=maven \
--lang=java \
--test=junit
```