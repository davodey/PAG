# PAG
Pearson Accessibility Guidelines

This is a temporary github placement while the Guidelines are being updated.

## Current TODOs:
- Powerpoint guidelines added, however changes may need to be done by Proto team on behalf of PPTX Guideline changes from accessibility team.


## Issue
The current Pearson Accessibility Guidelines are sitting on a server we cannot easily access and update: <a href="http://wps.pearsoned.com/accessibility/115/29601/7577872.cw/index.html#parent_12631413">http://wps.pearsoned.com/accessibility/115/29601/7577872.cw/index.html#parent_12631413</a>.

They've been copied to NEO, where they're easier to update, but versioning isn't fun there, nobody wants to maintain them there, and so github seems a good place to get started with editing. It's easier to copy the text from NEO than from the media server above since NEO is flat text and the media server is nested iframes.

Example NEO guideline #6 (even though the URL says 4!): <a href="https://neo.pearson.com/docs/DOC-627964-guideline-4-check-the-order-that-content-is-read-in-screen-readers-correct-any-issues-sensible-reading-order">Guideline 6. Check keyboard access (access without a pointing device) and correct any issues (Keyboard Access)</a>

### Things of note

#### 508 Refresh Draft

We've decided that we're keeping none of the Section 508 Refresh **draft** notices (they tend to start with a number-letter combo like 3-R or 3-S) since those were iterant pubs while the refresh was still being... refreshed. Ben Schroeter has been taking those out of the live Guidelines that are sitting on the media server, so we have no need to copy them from NEO to Github.

#### New windows/tabs

For now, if the original code had link text with "opens in a new window", we'll add in `target="_blank"` just so behaviour matches the text. When updating we may remove this entirely.

## Goal
The ideal setup is a single place to go to for accessibility guidelines, with both the ability to view all the content at once (so browser-based search works), as well as showing only relevant content using filters ("For Designers" for example). 
Unique URLs should be able to point to any particular guideline for referencing in other documents.
Eventually the media server will need to 301 Redirect to wherever the new guidelines go to live. Since there will be significant rewriting, individual 301's to particular guidelines may no longer work. A lot of documentation within Pearson refers to Guidelines by number so we may have to keep topic associated with numbers.

### Cupper

<a href="https://thepaciellogroup.github.io/cupper/">Cupper</a> looks like a tool we could use to host these guidelines.

<a href="https://github.com/pearson-ux/cupper">Private repo Pearson-ux cupper</a>.
