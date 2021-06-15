# Pavilion Composer Wordpress

A fork of [Delicious Brains' SpinupWP Composer Site](https://github.com/deliciousbrains/spinupwp-composer-site)

## Requirements

* PHP >= 7.1
* Composer - [Install](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)

## Installation

1. Update environment variables in the `.env` file:
  * `DB_NAME` - Database name
  * `DB_USER` - Database user
  * `DB_PASSWORD` - Database password
  * `DB_HOST` - Database host
  * `WP_ENV` - Set to environment (`development`, `staging`, `production`)
  * `WP_HOME` - Full URL to WordPress home (https://mysite.com)
  * `WP_SITEURL` - Full URL to WordPress including subdirectory (https://mysite.com/wp)
2. Add theme(s) in `public/content/themes/` as you would for a normal WordPress site
3. Set the document root in SpinupWP's server settings to `/public`. 
4. Access WordPress admin at `https://mysite.com/wp/wp-admin/`



