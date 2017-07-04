- ```sudo apt install rustc```
- https://www.rust-lang.org/en-US/install.html
- https://tomordonez.com/install-rust-on-ubuntu/

```sh
  stable installed - rustc 1.18.0 (03fc9d622 2017-06-06)


	Rust is installed now. Great!

	To get started you need Cargo's bin directory ($HOME/.cargo/bin) in your PATH 
	environment variable. Next time you log in this will be done automatically.

	To configure your current shell run source $HOME/.cargo/env
```

Running ```cargo init``` also seems to run ```git init```. Interesting!

```bash
$ cargo init

Created library project
> ll
total 40
drwxrwxr-x  4 dev  dev   4096 Jul  4 13:34 ./
drwxrwxrwt 18 root root 20480 Jul  4 13:34 ../
-rw-rw-r--  1 dev  dev    100 Jul  4 13:34 Cargo.toml
drwxrwxr-x  6 dev  dev   4096 Jul  4 13:34 .git/
-rw-rw-r--  1 dev  dev     30 Jul  4 13:34 .gitignore
drwxrwxr-x  2 dev  dev   4096 Jul  4 13:34 src/
```
