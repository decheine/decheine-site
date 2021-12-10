---
layout: "post"
title: "snippets"
date: "2020-12-04 14:49"
---

# Markdown

```CoffeeScript
'.md':
  'Terminal Block':
    'prefix': 'termblock'
    'body': """
    ```bash
    $1
    ```
    """

  'collapsable block':
    'prefix': 'tdo'
    'body': """
    ??? info "$1"
        $2
    """
```
