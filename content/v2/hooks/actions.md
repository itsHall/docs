---
title: "Action Hooks"
is_reference: true
---

## timber\_{$object\_type}\_get\_meta\_pre

Filters post meta data before it is fetched from the database.

**DEPRECATED** since 2.0.0, use `timber/{object_type}/pre_meta`

## timber/loader/render\_file

Fires after …

| Name | Type | Description |
| --- | --- | --- |
| $result | `string` |  |

## timber\_loader\_render\_file

Fires after …

**DEPRECATED** since 2.0.0, use `timber/loader/render_file`

This action is used by the Timber Debug Bar extension.

## timber/calling\_php\_file

Fires after the calling PHP file was determined in Timber’s compile
function.

This action is used by the Timber Debug Bar extension.

**since** 1.1.2 

| Name | Type | Description |
| --- | --- | --- |
| $caller_file | `string` or `null` | The calling script file. |

## timber/compile/done

Fires after a Twig template was compiled and before the compiled data
is returned.

This action can be helpful if you need to debug Twig template
compilation.

**since** 2.0.0 

| Name | Type | Description |
| --- | --- | --- |
| $output | `string` |  |
| $file | `string` |  |
| $data | `array` |  |
| $expires | `bool` |  |
| $cache_mode | `string` |  |

## timber\_compile\_done

Fires after a Twig template was compiled and before the compiled data
is returned.

**DEPRECATED** since 2.0.0, use `timber/compile/done`

