language-txl Changes
---

0.3.0 - 30 July 2016
  - Fix multi-line comments by moving before single-line comments so the regex applies first
  - Multi-line comments now require a match of '(' and ')' or '{' and '}'
  - Add handling of single-quoted literals
  - Use proper names for comments ('comment.block.txl' and 'comment.txl')

0.2.0 - 29 July 2016
  - Initial version
