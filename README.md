# After make migration

Script to change the ownership and rules for a migration file created using laravels artisan make:migration

## Options

* --path - path to laravel project
* -p, --password - system password to use with sudo
* -n, --name - name to use with chown (defaults to reggie:reggie)
* -r, --rules - to use with chmod (defaults to 664)

## Notes

* try to use bash's built in getopts utility
