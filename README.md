# Htaccess-Rewrite-Demo
Sample .htaccess file to selectively rewrite URIs

This demo is intented to be installed at the root level of a web server.

It demonstrates the use of a .htaccess file, using rewrite rules, to do the following:

- Rewrite any URI of the form /string/<x> to /<x>
- Preserve URIs of the form /string/checkout/<x> to still go to /string/checkout</x>

It was tested on an AWS Linux server.

This was written to test and offer a solution to this Stack Overflow question:
  https://stackoverflow.com/questions/49969159/redirecting-all-urls-containing-a-word-to-a-url-using-htaccess/49971525#49971525

A working demo is installed in a subdirectory here:

  http://dev.byteslinger.net/htaccessdemo/
