# Requirements​

## Software Environment \(the Stack\)

Most XOOPS production sites run on a _LAMP_ stack \(a **L**inux system running **A**pache, **M**ySQL and **P**HP\) nut, there are a lot of different possible stacks.

It is often easiest to prototype a new site on a local machine. For this case, many XOOPS users choose a _WAMP_ stack \(using **W**indows as the OS,\) while others run _LAMP_ or _MAMP_ \(**M**AC\) stacks.

### PHP

Any PHP version &gt;= 5.3.7 \(PHP 5.6 or higher is strongly recommended\)

### MySQL

MySQL server 5.5 \(MySQL Server 5.6 or higher is strongly recommended.\) MariaDB is a backward compatible, binary drop-in replacement of MySQL, and also works fine with XOOPS.

### Web server

A web server that supports running PHP scripts, such as Apache, NGINX, LiteSpeed, etc.

## Services

### File System Access \(for Webmaster Access\)

You will need some method \(FTP, SFTP, etc.\) to transfer the XOOPS distribution files to the web server.

### File System Access \(for Web Server Process\)

To run XOOPS, the ability to create, read and delete files and directories is needed. There are a few exceptions, but the vast majority of files written in normal operation are in two directories, _xoops\_data_ and _uploads_.

### Database

XOOPS will need to create, modify and query tables in MySQL. For this you will need:

* a MySQL user account and password
* a MySQL database that user has all privileges on \(or alternately, the user can have privilege to create such a database\)

### Email

For a live site, you will need a working email address that XOOPS can use for user communication, such as account activations and password resets. While not strictly required, it is recommended if possible to use an email address that matches the domain that your XOOPS runs on. That helps to avoid your communications ending up being rejected or marked as spam.

## Tools

You may need some additional tools to setup and customize your XOOPS installation. These may include:

* FTP Client Software
* Text Editor
* Archive Software to work with XOOPS release \(_.zip_ or _.tar.gz_\) files.

See the [Tools of the Trade](tools.md) section for some suggestions for suitable tools and web server stacks if needed.

