# Cassandra PHP IDE Stubs

This repository provide the cassandra php driver stubs which enables autocompletion in modern IDEs. The library comes from https://github.com/datastax/php-driver. We try to fix some issues, as wrong namespace

We hope Datastax will maintain their own stubs in a near future.

For now, you can use this one... Enjoy \o/

## Installing via Composer

1. Install Composer in a common location or in your project:
    ```bash
    curl -s http://getcomposer.org/installer | php
    ```

2. Create the `composer.json` file as follows:
    ```json
    {
        "require-dev": {
            "moarty/cassandra-php-stubs": "*"
        }
    }
    ```

3. Run the composer installer:
    ```bash
    php composer.phar install
    ```

4. Setup your IDE.

## Installing via Git

1. Clone the Cassandra IDE Stubs repository in a common location.

2. Setup your IDE.