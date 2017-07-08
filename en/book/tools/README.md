# Tools of the Trade

There are many things that are needed to customize and maintain a XOOPS web
site that need to happen outside of XOOPS, or are more easily done there.

This is a list of types of tools that you might want to have available, along
with some suggestions for specific tools that XOOPS webmasters have found useful.

## Editors

Editors are a very personal choice, and people can become quite passionate
about their favorite. We will present only a few of the many possibilities.

For XOOPS use, you will need an editor to tweak some configuration options
as well as customize a theme for your site. For these uses, it is can be
very helpful to have an editor that can work with multiple files at the
same time, be able to search and replace across many files, and provide
syntax highlighting. You can use a very simple, no frills editor, but you
will be working a lot harder to accomplish some tasks.

**PhpStorm** from *JetBrains* is an IDE (integrated development environment)
specifically tailored for PHP web development. *JetBrains* has been very
helpful in sponsoring XOOPS, and its products are favorites for many developers.
It is a commercial product, and it might be cost prohibitive for some new
webmasters, but the time it can save makes it attractive to experienced
developers.

**Visual Studio Code** is a free, multi-platform source code editor from
Microsoft. It has support, either built in or through extensions, for the
core web technologies such as HTML, JavaScript, and PHP, making it a good
fit for XOOPS use.

**Notepad++** is a free, time honored contender in this category for Windows,
with loyal users.

**Meld** is not an editor, but it compares text files showing differences,
and allows for merging changes selectively, and making small edits. It is
very useful when comparing configuration files, theme templates, and of
course PHP code.

| Name | Link | License | Platform |
| --- | --- | --- | --- |
| PhpStorm | https://www.jetbrains.com/phpstorm/ | Commercial | Any |
| Visual Studio Code | https://code.visualstudio.com/ | MIT | Any |
| Notepad++ | https://notepad-plus-plus.org/ | GPL | Win |
| Meld | http://meldmerge.org/ | GPL | Any |

## FTP Client

File Transfer Protocol (FTP,) or a variation there of, is used to move
files from one computer to another. Most XOOPS installations will need
an FTP client to move files that come from the XOOPS distribution to a
host system where the site will be deployed.

**FileZilla** is a free and powerful FTP Client that is available for most
platforms. The cross-platform consistency made it the choice for the FTP
examples in this book.

| Name | Link | License | Platform |
| --- | --- | --- | --- |
| FileZilla | https://filezilla-project.org/ | GPL | Any |

## MySQL/MariaDB

The database contains all of the content of your site, the configurations
that customize your site, the information about the users of your site, and
more. Protecting and maintaining that information may be easier with some
extra tools that deal specifically with the database.

**phpMyAdmin** is the most popular web-based tool for working with MySQL
databases, including making one-off backups.

**BigDump** is a godsend for limited hosting accounts, where it helps in
restoring large database backup dumps while avoiding timeout and size
restrictions.

**srdb**, Search Replace DB for XOOPS is a XOOPS adaptation of [Search and Replace DB](https://github.com/interconnectit/Search-Replace-DB)
from interconnect/it. It is especially useful to change URLs and filesystem
references in MySQL data when you are moving a site.

| Name | Link | License | Platform |
| --- | --- | --- | --- |
| phpMyAdmin | https://www.phpmyadmin.net/ | GPL | Any|
| BigDump | http://www.ozerov.de/bigdump/ | GPL | Any |
| srdb | https://github.com/geekwright/srdb | GPL3 | Any |

## Developer Stacks

Some platforms, such as Ubuntu, have the whole stack needed to run XOOPS
built in, while others need some additions.

**WAMP** and **Uniform Server Zero** are all-in-one stacks for Windows.

**XAMPP**, an all-in-one stack from Apache Friends, is available for multiple
platforms.

**bitnami** offers a wide range of prebuilt application stacks, including
virtual machine and container images. Their offerings can be a valuable
resource to quickly try out applications (including XOOPS) or various web
technologies. They can be suitable for production as well as development
use.

| Name | Link | License | Platform |
| --- | --- | --- | --- |
| WAMP | http://www.wampserver.com/ | Multiple | Win |
| Uniform Server Zero | http://www.uniformserver.com/ | Multiple | Win |
| XAMPP | https://www.apachefriends.org/index.html | Multiple | Any |
| bitnami | https://bitnami.com/ | Multiple | Any |
