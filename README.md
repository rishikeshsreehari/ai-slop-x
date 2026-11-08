# ai-slop-x

![usernames](https://img.shields.io/badge/usernames-811-blue)

This repository mirrors the union of two public X lists: [ai slop posters](https://x.com/i/lists/2116659176894071283) and [AI slop additions](https://x.com/i/lists/2119015827240309009).

Use these lists as a starting point to filter suspected AI spam and find genuine accounts—not as proof that any account uses AI.

`usernames.txt` has one username per line. `usernames.json` is the same usernames as a JSON array of strings, in the same order. The snapshot is 791 unique usernames from the original list. The additions list was empty when it was created, so the union is still those 791 names.

`appeals.json` stores only a stable X ID, a username, and a status of `pending`, `approved`, or `rejected`. Emails, appeal text, and other personal details are never committed.

Appeals go to aislop-x@mail.grokbot.com and are reviewed by the repository owner. They are not approved automatically.

Grok Bot checks both lists every four hours and manages blocks for this account. When a username is removed from the source lists, the bot unblocks it only if that block was created by the automation. An approved appeal overrides a block.


