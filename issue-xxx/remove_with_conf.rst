===========================================
Secondary Sidebar Removed via Configuration
===========================================

This page has its secondary sidebar removed via ``html_theme_options``. In particular,

.. code-block:: rst

    html_theme_options = {
        "secondary_sidebar_items": {
            "issue-xxx/remove_with_conf": [],
        }
    }
