## Version 10 Breaking Changes

Incompatibilities:
- chore(parser): compressed version 9.x language definitions no longer supported (rebuild them minified) [Josh Goebel][]

Renamed Language Files:
- chore(parser): rename `cs.js` to `csharp.js` [Josh Goebel][]

Legacy Browser Potential Issues:
- chore(parser): remove `load` listener in favor of only the newer `DOMContentLoaded` [Josh Goebel][]

Removed styles:
- chore(styles): darkula.css (use darcula.css instead) [Josh Goebel][]

[Josh Goebel]: https://github.com/yyyc514

---

Also see:
https://github.com/highlightjs/highlight.js/issues/2273
