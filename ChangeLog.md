#### 1.3.0 (17 jun 2015)
* Removed support for WCML - use [WCML hooks](https://wpml.org/documentation/related-projects/woocommerce-multilingual/multi-currency-support-woocommerce/) instead
* Closes issue [#2](https://github.com/nekojira/wp-currencies/issues/2)

#### 1.2.5 (30 apr 2015)
* Supports WordPress 4.2

#### 1.2.4 (26 feb 2015)
* Fixes "The plugin generated ... characters of unexpected output" upon activation

#### 1.2.2 (06 feb 2015)
* Fixes a bug where the currencies table is not created in database upon plugin activation
* If you were experiencing issues with previous version, you may want to deactivate and reactivate plugin after update

#### 1.2.1 (06 feb 2015)
* Fixes broken link to plugin settings page (props @jkomar)

#### 1.2.0 (15 Jan 2015)
* Added support to WooCommerce MultiLanguage
* Updated Settings Page (you may need to re-enter your API Key)
* The plugin now uses `wp_cron` for periodical updates
* Introduced `currency_exists()` function
* Bugfixes

#### 1.1.3 (08 Jul 2014)
* Added field support for Advanced Custom Fields 5.x
* More currency data

#### 1.1.1 (04 Jul 2014)
* Bugfix (accidentally deactivated admin class in 1.1.0)

#### 1.1.0 (04 Jul 2014)
* Introduced `format_currency()` function
* Added endpoints for JSON REST API (WP API)
* Added a "Currency field" for Advanced Custom Fields 4.x

#### 1.0.0 (03 Jul 2014)
* Initial public release