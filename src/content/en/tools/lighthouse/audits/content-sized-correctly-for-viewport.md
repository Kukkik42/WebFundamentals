project_path: /web/tools/_project.yaml
book_path: /web/tools/_book.yaml
description: Reference documentation for the "Content Sized Correctly for Viewport" Lighthouse audit.

{# wf_updated_on: 2017-12-11 #}
{# wf_published_on: 2016-10-04 #}
{# wf_blink_components: N/A #}

# Content Sized Correctly for Viewport  {: .page-title }

## Overview {: #overview }

This audit checks that the width of the content on your page is equal
to the width of the viewport. When content width is smaller or larger than
viewport width, that's often a cue that the page is not optimized for
mobile screens.

## Recommendations {: #recommendations }

This audit is a roundabout way of determining if your page is optimized for
mobile devices. If your site is not optimized and you want it to be, then see
[Responsive Web Design Basics](/web/fundamentals/design-and-ux/responsive/)
to get started.

You can ignore this audit if:

* Your site does not need to be optimized for mobile screens.
* The content width of your page is intentionally smaller or larger than the
  viewport width.

More information {: #more-info }

The audit passes if `window.innerWidth === window.outerWidth`.


{% include "web/tools/lighthouse/audits/_feedback/content-sized-correctly-for-viewport.html" %}
