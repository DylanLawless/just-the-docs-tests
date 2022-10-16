---
title: TOC heading
---

# ✅ Customize TOC heading

1.  Check that `_includes/toc_heading_custom.html` does not exist.

1.  Select the top-level page with title [`F`](../../navigation/grandparent/f/)
    in the collection of navigation tests.

1.  Check that the heading of the list of children is "**Table of Contents**{: .text-delta }".

1.  Customize the TOC heading by creating `_includes/toc_heading_custom.html` and adding:
 
    ```html
    <h2>Contents</h2>
    ```
1.  Refresh the page.

1.  Check that the heading of the list of children is now "**Contents**".

1.  Remove `_includes/toc_heading_custom.html`.
