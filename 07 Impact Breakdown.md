# ⚠️ This is not final. Very much WIP. Don't rely on this yet
# Overall Summary
Assuming the Reference Set would use the same Syntax / Meaning combo as the Minimal theme, which was identified to align with the most popular set of Checkboxes across all themes:
- 10 of 44 Themes with Alternative Checkbox implementation would be impacted *IF* they decided to align their themes with the Reference Set (detailed breakdowns below).
- Of the impacted themes, 1 Theme is Officially Unmaintained and 2 Themes are Light / Dark variants of the same theme.
- Of the impacted themes, judging by download count as an indicator of theme's use, impact is relatively low with the exception to Spectrum (Officially Unmaintained), ITS Theme and Cyber Glow.
- The following Syntax and Meaning parings have no conflicts:
	- `- [!]` Important / Warning / Exclamation
	- `- [?]` Question
	- `- [*]` Star / Favourites
	- `- [l]` Location / Navigation
	- `- [S]` Savings / Amount / Piggy Bank / Money / Price
	- `- [k]` Key

---
# Per Theme Breakdown

`?` = Next to the meaning indicates that the theme doesn't provide any meaning indication. It's being assumed based on the icon used for that checkbox.

Spectrum (Downloads: 50762) *Officially Unmaintained*
- `- [-]` "Minus" instead of "Cancelled"

Sparkling Night (Downloads: 9251)
- `- [-]`"Pause / Stand-by" instead of "Cancelled"
- `- [/]` "Stop" instead of "In Complete"
- `- [>]` "Working Progress" instead of "Forwarded"

Sparkling Day (Downloads: 1790) *Same developer as above*
- `- [-]`"Pause / Stand-by" instead of "Cancelled"
- `- [/]` "Stop" instead of "In Complete"
- `- [>]` "Working Progress" instead of "Forwarded"

Aura (Downloads: 17680)
- `- [/]` "Settings?" instead of "In Complete"
- `- [i]` "Idea / Light Bulb" instead of "Information"
- `- [I]` "Information" instead of "Idea / Light Bulb"

Vicious (Downloads: 10588)
- `- [/]` "Pause" instead of "In Complete"
- `- [<]` "Backward" instead of "Scheduling"
- `- [p]` "Person" instead of "Pros"
- `- [c]` "Comment" instead of "Cons"
- `- [d]` "Diamond" instead of "Down"
- `- [u]` "URL" instead of "Up"
- `- [w]` "World" instead of "Win"

Nightingale (Downloads: 2297)
- `- [>]` "Right" instead of "Forwarded"
- `- [<]` "Left" instead of "Scheduling"
- `- [d]` "Date / Calendar" instead of "Down"

ITS Theme / Snippet (Downloads: 160972 + impact of ITS CSS Snippet)
- `- [i]` "Idea" instead of "Information"
- `- [I]` "Information" instead of "Idea / Light Bulb"
- `- [p]` "Paraphrase" instead of "Pros"
- `- [c]` "Choice" instead of "Cons"

Cyber Glow (Downloads: 49299)
- `- [i]` "Idea" instead of "Information"

Gummy Revived (Downloads: 921)
- `- [b]` "Brainstorm" instead of "Bookmark"
- `- [i]` "Idea" instead of "Information"

Underwater (Downloads: 2522)
- `- [w]` "Wave" instead of "Win"

# Per Syntax Breakdown

`?` = Next to the meaning indicates that the theme doesn't provide any meaning indication. It's being assumed based on the icon used for that checkbox.

---

## `- [-]` Cancelled / Dropped

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 41     | 3         | -        |

**Disagreed:**
- Spectrum (Officially Unmaintained)
	- Meaning: Minus
	- Downloads: 50762
- Sparkling Night
	- Meaning: Pause / Stand-by
	- Downloads: 9251
- Sparkling Day
	- Meaning: Pause / Stand-by
	- Downloads: 1790

---

## `- [/]` In Complete / In Progress / Half Done / Partial / WIP

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 37     | 4         | 3        |

**Disagreed:**
- Aura
	- Meaning: Settings? (undefined by theme / making an assumption based on icon used)
	- Downloads: 17680
-  Vicious
	- Meaning: Pause
	- Downloads: 10588
- Sparkling Night
	- Meaning: Stop
	- Downloads: 9251
- Sparkling Day
	- Meaning: Stop
	- Downloads: 1790

---

## `- [>]` Forwarded / Rescheduled / Delayed / Deferred

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 38     | 3         | 3        |

**Disagreed:**
- Sparkling Night
	- Meaning: Working Progress
	- Downloads: 9251
- Sparkling Day
	- Meaning: Working Progress
	- Downloads: 1790
- Nightingale
	- Meaning: Right
	- Downloads: 2297

---

## `- [!]` Important / Warning / Exclamation

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 41     | -         | 3        |

---

## `- [?]` Question

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 39     | -         | 5        |

---

## `- [<]` Scheduling / Meeting / Migrated

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 36     | 2         | 6        |

**Disagreed:**
- Nightingale
	- Meaning: Left
	- Downloads: 2297
-  Vicious
	- Meaning: Backward
	- Downloads: 10588

---

## `- [i]` Information

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 33     | 4         | 7        |

**Disagreed:**
- ITS Theme
	- Meaning: Idea
	- Downloads: 160972 (+ impact of ITS CSS Snippet)
- Cyber Glow
	- Meaning: Idea
	- Downloads: 49299
- Aura
	- Meaning: Idea / Light Bulb
	- Downloads: 17680
- Gummy Revived
	- Meaning: Idea
	- Downloads: 921

---
## `- [b]` Bookmark / Book

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 34     | 1         | 9        |

**Disagreed:**
- Gummy Revived
	- Meaning: Brainstorm
	- Downloads: 921

---

## `- [I]` Idea / Light Bulb

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 31     | 2         | 11       |

**Disagreed:**
- ITS Theme
	- Meaning: Information
	- Downloads: 160972 (+ impact of ITS CSS Snippet)
- Aura
	- Meaning: Information
	- Downloads: 17680

---

## `- [*]` Star / Favourites

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 30     | -         | 14       |

---

## `- [p]` Pros / Thumbs Up / Like / Positive

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 29     | 2         | 13       |

**Disagreed:**
- ITS Theme
	- Meaning: Paraphrase
	- Downloads: 160972 (+ impact of ITS CSS Snippet)
-  Vicious
	- Meaning: Person
	- Downloads: 10588

---

## `- [c]` Cons / Thumbs Down / Dislike / Negative

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 29     | 2         | 13       |

**Disagreed:**
- ITS Theme
	- Meaning: Choice
	- Downloads: 160972 (+ impact of ITS CSS Snippet)
-  Vicious
	- Meaning: Comment
	- Downloads: 10588

---

## `- [l]` Location / Navigation

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 30     | -         | 14       |

---

## `- [d]` Down / Trend Down

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 25     | 3         | 16       |

**Disagreed:**
-  Vicious
	- Meaning: Diamond
	- Downloads: 10588
- Nightingale
	- Meaning: Date / Calendar
	- Downloads: 2297

---

## `- [S]` Savings / Amount / Piggy Bank / Money / Price

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 28     | -         | 16       |

---

## `- [u]` Up / Trend Up

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 25     | 1         | 18       |

**Disagreed:**
-  Vicious
	- Meaning: URL
	- Downloads: 10588

---

## `- [k]` Key

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 21     | -         | 23       |

---

## `-[w]` Win

| Agreed | Disagreed | Not Used |
| ------ | --------- | -------- |
| 19     | 2         | 23       |

**Disagreed:**
- Vicious
	- Meaning: World
	- Downloads: 10588
- Underwater
	- Meaning: Wave
	- Downloads: 2522