---
title: "Restructuredtext"
date: 2025-02-11T18:16:52+09:00
draft: true
---

reStructuredText is a lightweight markup language used for technical documentation. It is part of the Docutils project and is used by Python's documentation system.

# reStructuredText Syntax

## Headers
```
Header 1
========

Header 2
--------

Header 3
~~~~~~~~
```

## Emphasis
```
*italic* or _italic_
**bold** or __bold__
```

## Lists
```
- Item 1
- Item 2
  - Subitem 1
  - Subitem 2
```

## Links
```
`Link text <http://example.com>`_
```

## Images
```
.. image:: image.jpg
   :alt: Alt text
```

## Code
```
``inline code``

.. code-block:: python

    def hello():
        print("Hello, world!")

