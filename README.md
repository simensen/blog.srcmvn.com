Source Maven Legacy
===================

This repository contains (almost) everything that makes up
[blog.srcmvn.com](http://blog.srcmvn.com).

Powered by [Sculpin](http://sculpin.io). =)


Build
-----

### If You Already Have Composer

    composer install
    vendor/bin/sculpin generate --watch --server

Your newly generated clone of [blog.srcmvn.com](http://blog.srcmvn.com) is now
accessible at `http://localhost:8000/`.

### If You Need Composer

    curl -s https://getcomposer.org/installer | php
    php composer.phar install
    vendor/bin/sculpin generate --watch --server

