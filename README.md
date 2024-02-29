# FreePBX-Superfecta-Tellows
This module can be used for Spam detection against the Tellows online service (German speaking area) and to create a caller spam filtering with allowed callers bypass in conjunction with the modified Allowlist module.

Thanks to @Igaetz in the FreePBX forum for his idea and the initial work on this script.

## Installation
Copy the file to /var/www/html/admin/modules/superfecta/sources . It'll be available immediately in your Superfecta list and you can configure and use it.

*Attention*: An update of the Superfecta module unfortunately seems to delete all other files, you might need to disable automatic module updates and copy the file again after a module update. All settings will be preserved.

## Configuration

* SPAM Threshold: The Tellows score from which on a caller is marked as spam. Defaults to 7.
* COMMENTS Threshold: The number must have at least this number of comments to be marked as spam. Defaults to 2.
* SEARCHES Threshold: The number must have at least this number of searches to be marked as spam. Defaults to 5.
* Tellows Key: Your Tellows API key as MD5 hash. The module currently works also without a key, but it's not clear if this is limited by Tellows.

