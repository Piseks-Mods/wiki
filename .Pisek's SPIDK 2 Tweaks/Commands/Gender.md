---
tags: commands
---

Sets or queries player's gender.

| Command | Permission level required | Restrictions |
| ------- | ------------------------- | ------------ |
| gender  | 0                         | None         |

# Syntax

`gender get <player>`
	Returns selected player's gender.
`gender set <player> <isMale>`
	Set selected player's gender. Player can set own's gender but can't set others unless player have permission level `2`.

# Arguments

`<player>`:entity
`<isMale>`:boolean
	`True`: Player is male, [[Squeeze|squeezing]] is enabled.
	`False`: Player is female, squeezing is disabled. Default.

# Result

| Command | Trigger              | Result      |
| ------- | -------------------- | ----------- |
| any     | no argument provided | Unparseable |
| any     | Otherwise            | Successful  | 

# History

| Version | Change          |
| ------- | --------------- |
| 2.0     | Added `/gender` | 