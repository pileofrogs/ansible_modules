My Crappy Ansible Modules  
===============

I wrote these quickly and badly.  I probably wouldn't have written them
at all if I tried to do them correctly.  Hey, it's "agile", right?  I do not guarantee that these will break your computer, but please assume they will.

### pear ###

install php libs with pear - only does installs - only advantage over command is it says unchanged if lib already installed.. Oh, you can specify "changed_when:" now?  Uh.. if code were a doorstop...

### cpan ###

Install perl libs with cpan.  Only does installs.  Will hang if the
module's installation asks for input.  Unless you know exactly what the
perl module will do when you install it with cpan, using this ansible
module to install it is a very bad idea.
