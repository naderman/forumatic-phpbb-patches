Forumatic's phpBB patches
=======================

These are phpBB patches used on Forumatic. Typically they are not suitable for a self hosted phpBB, and were thus not useful for phpBB in general.

Sometimes patches available here are in the process of receiving a more generic implementation within phpBB or will later be made available as a phpBB extension.

Patches
=======

preload-english.patch
---------------------
This patch always loads english language files before the chosen language. This
avoids errors and missing output when another language does not contain
variables which exist in the english language files. However it requires that
the english language files are present. It might display english language in
the middle of another language.

Status: N/A
