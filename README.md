# PHPDBG bug

run
`vendor/bin/phpunit --no-configuration tests`
and everything is fine (No tests executed)

`phpdbg -qrr vendor/bin/phpunit --no-configuration tests`

Causes a segmentation fault
