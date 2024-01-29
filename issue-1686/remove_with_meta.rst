:html_theme.sidebar_secondary.remove: true

================================================
Secondary Sidebar Removed via Page-Wide Metadata
================================================

.. raw:: html

   <style>
     .bd-article-container {
       border: 3px solid var(--pst-color-border);
     }
   </style>

This page has its secondary sidebar removed via page-wide metadata. In particular, this
page has ``:html_theme.sidebar_secondary.remove: true`` at its top. One can see that
the secondary sidebar is really removed, in the sense that the ``.bd-sidebar-secondary``
element does not even exist. Consequently, the main content area is taking its space,
which I believe is desired.

The border of the ``.bd-article-container`` is added by in-page CSS.
