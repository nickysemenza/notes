# notes
misc.

# Code
## Shell
* Show which ports applications are bound to (MacOS) `sudo lsof -iTCP -sTCP:LISTEN -n -P`

## MySQL
* Show charsets for mysql client + server: `SHOW VARIABLES WHERE Variable_name LIKE 'character\_set\_%' OR Variable_name LIKE 'collation%';`

## PHP
### Laravel
When composer is acting up:
`php artisan clear-compiled`
`composer dump-autoload`
`php artisan optimize`


## MacOS Finder 
* Show full path in Title bar: `defaults write com.apple.finder _FXShowPosixPathInTitle -bool true; killall Finder`
