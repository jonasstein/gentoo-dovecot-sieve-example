# gentoo-dovecot-sieve-example

A new gentoo developer wants to configure the mailfilter at woodpecker. 
This example configuration can be used to save some time.

Usage
=====

Copy dovecot.sieve.example to ~/.dovecot.sieve on woodpecker

Forward all mails to dovecot with

    echo '| "/usr/libexec/dovecot/deliver"' > ~/.forward

subscribe all folders on commandline

    user@woodpeck ~ $ for b in `doveadm mailbox list`; do doveadm mailbox subscribe $b; done

Todo
====
* add more mailinglists
* test and improve
* find a good place to distribute. gentoo-wiki? or a file on woodpecker? Suggestions are welcome.


License and distribution
========================
http://unlicense.org
