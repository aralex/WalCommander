         Wal commander 0.18.0 GitHub Edition
    https://github.com/corporateshark/WalCommander
=======================================================

Dual panel multi-platform open source file manager
for Windows, Linux, FreeBSD and OS X with

- terminal emulator
- built-in editor with syntax highlighting (c/c++, java, pascal, latex, glsl, perl, php, python, sh, sql, xml)
- built-in text viewer
- virtual file systems: smb, ftp, sftp
- file associations
	
=======================================================

Build (FreeBSD, Linux, OS X, MinGW):

	UNIX builds run smooth on Ubuntu 14.04LTS, on amd64, and i386 architectures. Required libraries:

		libX11-dev
		libfreetype-dev			
		libssh2-1-dev
		libsmbclient-dev

	The code uses c++11. GCC versions below 4.7 do not have the c++11 support. This is the only minimum requirement known by this time.

		cd wcm
		make all -B

Install:

		sudo make install

Mac OS X installation way (refer to https://github.com/corporateshark/WalCommander/issues/5 for more details):

	Install Quartz from http://xquartz.macosforge.org/landing/
	Install brew http://brew.sh/
	brew install --HEAD https://gist.githubusercontent.com/KonstantinKuklin/9001d95fa30fecf3231c/raw/walcommander.rb
