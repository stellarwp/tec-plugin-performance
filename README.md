
# Performance Analysis Site performance.theeventscalendar.com

A plugin that analyzes historical performance across various metrics for Wordpress plugins. As an activated plugin version changes, a new analysis snapshot is created to compare against.

## Local Development

A `docker-compose.yml` is setup for the local environment.

- Run `docker-compose up -d` to start the containers.
- Run `composer i --prefer-source` to install the plugins.
- Use the [wp-config.php.dist](wp-config.php.dist) as the `wp-config.php`.
- Browse to [http://localhost:8882](http://localhost:8882).