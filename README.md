___

<p align="center">
	<img align="center" src="https://user-images.githubusercontent.com/41551840/82152527-37348200-9838-11ea-96b4-5749348a9d3e.png">
</p>

<p align="center">
	<h3 align="center">Combo Clean</h3>
	<p align="center">by i386angel</p>
</p>

<p align="center">
	<a target="__blank" href="#">
	  <img src="https://img.shields.io/badge/status-in progress-red?&style=for-the-badge"/>
	  <img src="https://img.shields.io/badge/license-mit-blue?&style=for-the-badge"/>
	</a>
</p>

___

<br>

<h2>Install</h2>

Copy and paste on your terminal.

```shell
$ git clone https://github.com/i386angel/comboclean && cd comboclean/ && chmod +x comboclean && sudo cp comboclean /usr/bin/comboclean
```

<h2>How to use</h2>

```shell
$ comboclean --help
```

___

<h2>Example</h2>

A combolist example:

```shell
$ cat combolist.txt

username:password something | something | something
username:password something | something | something
username:password something | something | something
username:password something | something | something
username:password something | something | something
username:password something | something | something
```

Using <b>comboclean</b>

```shell
$ comboclean -f combolist.txt -o combolist2.txt
```

```shell
$ cat combolist2.txt

username:password
username:password
username:password
username:password
username:password
username:password
```