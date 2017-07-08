# Moving a XOOPS Site

It can be a very useful technique to prototype a new XOOPS site on a local
system or a development server. It can also be very prudent to test a XOOPS
upgrade on a copy of your production site first, just in case something goes
wrong. To accomplish these, you need to be able to move your XOOPS site from
one site to another. Here is what you need to know to successfully move your
XOOPS site.

The first step is to establish your new site environment. The same items
that are covered in the section [Advance Preparations](../preparations/README.md) apply here as well.

In review, those steps are:
- obtain hosting account
- register domain
- obtain email address for webmaster
- obtain a MySQL user account and password
- obtain a MySQL database that above user has all privileges on

The remainder of the process is quite similar to a normal install, but:
- instead of copying the files from the XOOPS distribution, you will copy them from the existing site
- instead of running the installer, you will import a database already populated
- instead of entering answers in the installer, you will change the previous answers in the files and database

## Copy the Existing Site Files

Make a full copy of files of your existing site to your local machine where
you can edit them. If you are working with a remote host, you can use FTP
to copy the files. You need a copy to work with even if the site is running
on your local machine, just make another copy of the site's directories in that case.

It is important to remember to include the *xoops_data* and *xoops_lib*
directories even if they were renamed and/or relocated.

## Copy the Existing Site Database

For this step, using *phpMyAdmin* is highly recommended. Log in to *phpMyAdmin*
for your existing site, select your database, and choose *Export*.

If you have tables in your database that are not from XOOPS or its
modules, you should select "Export method" of *Custom* and
The default setting are usually fine, so just select "Export method" of
*Quick* and "Format" of *SQL*.

Use the *Go* button to download the database backup.



## Setup the New Environment

The same items that are covered in the section [Advance Preparations](../preparations/README.md)
apply here as well.

## mainfile.php and secure.php

Two files, `mainfile.php` in your site's web root, and `data/secure.php` in
your site's (renamed and/or relocated) *xoops_data* directory.

Open mainfile.php in your