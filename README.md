htaccess-config interactively walks a user through establishing basic
authentication security on a web directory using the .htaccess scheme.  This
was designed to be used by the average user, who has little to no knowledge of
how to set up this sort of file for a website they keep.  Primarily, it was
designed to be used in a multi-user environment where each user has their own
web space hosted by the Apache server (i.e. http://example.com/~user).  The
working directory must be the directory you wish the .htaccess file to be
placed in.

## Usage ##

When run, the script will initially check for existing ".htaccess" and
".htpasswd" files.  The user will then be prompted to find out if they want to
create/modify permissions, remove permissions, or quit.  If they choose to
remove permissions it will confirm that they want to remove the files and then
delete them.  This assumes they have permission to delete the files to begin
with.  If they choose to create/modify permissions it will walk you through
various questions, allowing you to add usernames and passwords, and specify
which files to password protect.

