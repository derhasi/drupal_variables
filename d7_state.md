# Drupal 7 Variables used for storing state

The list below holds variables, that are used for storing state in Drupal 7 and therefore should not be exported as configuration. The format with prefix `variable.` is used to provide easy copy-paste for the [Configuration Management (D7) module](https://drupal.org/project/configuration)'s _Exclude configuration_ setting (admin/config/system/configuration/settings).

## Core

```
variable.color_*_files
variable.color_*_palette
variable.color_*_logo
variable.color_*_stylesheets
variable.cron_last
variable.css_js_query_string
variable.install_current_batch
variable.install_profile_modules
variable.install_task
variable.install_time
variable.javascript_parsed
variable.language_count
variable.menu_default_active_menus
variable.menu_expanded
variable.node_access_needs_rebuild
variable.node_cron_comments_scale
variable.node_cron_last
variable.node_cron_views_scale
variable.node_recent_block_count
variable.path_alias_whitelist
variable.statistics_day_timestamp
variable.syslog_facility
variable.syslog_format
variable.syslog_identity
variable.tracker_index_nid
```

## Core tests

```
variable.batch_test_stack
variable.block_test_*
variable.common_test_cron
variable.dependency_test
variable.entity_cache_test
variable.entity_cache_test_label
variable.drupal_css_cache_files
variable.entity_form_langcode
variable.entity_test_translation
variable.field_test_*
variable.file_test_*
variable.front_page_output
variable.image_test_results
variable.language_test_*
variable.menu_test_*
variable.node_access_test_private
variable.node_access_test_secret_catalan
variable.node_test_change_view_mode
variable.node_test_node_access_all_uid
variable.openid_test_*
variable.path_test_results
variable.test_module_enable_order
variable.test_verbose_module_hooks
variable.update_d8_requirements
variable.xmlrpc_test_xmlrpc_alter
```

## Ctools

```
variable.ctools_last_cron
```

## Erpal

```
variable.commerce_billy_invoice_nr_last
variable.custom_order_number_commerce_order_nr_last
variable.custom_order_number_quote_nr_last
```
