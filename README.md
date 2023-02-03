# hotfix
Patch your UserSpice install before a full version comes out
When there is a long interval between releases of major updates, this repo will contain hotfix code to get you closer to the next major version.

It will NEVER contain users/includes/user_spice_ver.php, so you will always be able to update to the next version seamlessly.  
Once a file appears in here, it will ALWAYS be pushed to the next release, or dealt with in an update in some way. You will not be left with orphaned files.

Version numbers will be in the format of 5.5.5.1
This is telling you that it is the first hotfix released after 5.5.5 but before 5.5.6

These patches are ONLY safe to run on a version that matches the first 3 numbers of the version.

Versions such as 5.5.5.2 will ALWAYS be cumulative and contain everything from 5.5.5.1, so you do not need to apply multiple hotfixes.  Just grab the latest one.

ONLY apply the code inside the hotfix folder, not the gitignore and readme files and any notes that sit outside of it.
