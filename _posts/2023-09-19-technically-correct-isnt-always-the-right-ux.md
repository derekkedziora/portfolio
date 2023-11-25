---
title: "Technically correct isn’t always the right UX"
description: "We should favor descriptions that are useful and actionable over technically correct"
canonical: "https://derekkedziora.com/notes/20230919144613"
tag: ux-writing
permalink: /blog/technically-correct-isnt-always-the-right-ux
date: 2023-09-19 14:46
---

In iA Writer you no longer delete files. Instead, the menu text is “Move to trash”.

That’s technically correct. Your files will not be deleted, but moved to the trash, where they will be deleted in 30 days. 

But this doesn’t sit well with me. My intent has *never* been to move something to the trash. I want to delete a file. Each time I delete a file, it takes me a couple seconds longer to find the menu item because the interface text is written in the mental model of the developer, not the end user.

I know some people insist on every text being *technically* correct, but this isn’t always helpful. If you really insist on adding some caveat, still call the primary action delete and consider a success toast the first time the action is done, “File moved to the trash”.