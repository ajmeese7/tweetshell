# Tweetshell v1.0
Multi-thread Twitter BruteForcer in Shell Script

Tweetshell is an Shell Script to perform multi-threaded brute force attack against Twitter, this script can bypass login limiting and it can test infinite number of passwords with a rate of +400 passwords/min using 20 threads.

![tweet](https://user-images.githubusercontent.com/34893261/38052298-2abf6b28-32a7-11e8-83e6-de7c015b774e.png)

### Features
- Multi-thread (400 pass/min, 20 threads)
- Save/Resume sessions
- Anonymous attack through TOR
- Default password list (best +39k 8 letters)
- Check valid username
- Check and Install all dependencies

### Install requirements (Curl, Tor):

```shell
chmod +x install.sh
sudo ./install.sh
```

### Usage:

```shell
git clone https://github.com/ajmeese7/tweetshell
cd tweetshell
chmod +x tweetshell.sh
sudo service tor start
sudo ./tweetshell.sh
```

### Kill orphan processes

```shell
sudo pkill -9 -f tweetshell.sh
sudo pkill -9 -f curl
```
