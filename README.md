# gentoo-dovecot-sieve-example

A new gentoo developer wants to configure the mailfilter at woodpecker. 
This example configuration can be used to save some time.

Usage
=====

Copy dovecot.sieve.example to ~/.dovecot.sieve on woodpecker

Forward all mails to dovecot with
echo '| "/usr/libexec/dovecot/deliver"' > ~/.forward


License and distribution
========================
http://unlicense.org
