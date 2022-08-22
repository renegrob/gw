# gw
Bash script looking for gradlew and invoking it

## Install
Copy the file to a binary folder, e.g. `$HOME/bin` and add that folder to `$PATH`

## Usage
Usage is like `.\gradlew` but it works from every subdirectory

Instead of
```
user@machine:~ $ ./gradlew clean build
```
use
```
user@machine:~ $ gw clean build
```

Instead of
```
user@machine:~/dir1/dir2 $ ../../gradlew clean build
```
use
```
user@machine:~/dir1/dir2 $ gw clean build
```
