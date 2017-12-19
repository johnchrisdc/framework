node {
    stage("composer_install") {
        // Run `composer update` as a shell script
        shell 'composer install'
    }
    stage("phpunit") {
        // Run PHPUnit
        shell 'vendor/bin/phpunit'
    }
}
