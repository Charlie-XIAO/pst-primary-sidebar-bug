===========================================
Secondary Sidebar Removed via Configuration
===========================================

.. raw:: html

   <style>
     .bd-article-container {
       border: 3px solid var(--pst-color-border);
     }
   </style>

This page has its secondary sidebar removed via ``html_theme_options``. In particular,

.. code-block:: python

   html_theme_options = {
       "secondary_sidebar_items": {
           "issue-1686/remove_with_conf": [],
       }
   }

One can see that though the secondary sidebar is not actually displayed, the
``.bd-sidebar-secondary`` element still exists there, though completely empty. It is
also taking up the width of the page, which is not desired.

The border of the ``.bd-article-container`` is added by in-page CSS.
