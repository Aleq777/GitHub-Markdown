# Headers
```md
# Header1
## Header2
### Header3
#### Header 4
##### Header 5
###### Header 6

<h1 id="header1">Header1</h1>
<h2>Header</h2>
<h3>Header</h3>
<h4>Header</h4>
<h5>Header</h5>
<h6>Header</h6>

Header1
===

Header2
---
```

<h6>header 6 can be a small text</h6>

<h1 id="links">Links</h1>

```md
[Click here](./README.md "Tooltip")

[Go to Links](./README.md#links)

<https://www.markdownguide.org/basic-syntax/>
<fake@example.com>

The [link][1]

[1]: https://en.wikipedia.org
```

[Click here](./README.md "Tooltip")

[Go to Links](./README.md#links)

<https://www.markdownguide.org/basic-syntax/>

<fake@example.com>

The [link][1]

[1]: https://en.wikipedia.org

# New line

```md
same
line
```

same
line

```md
other

line
```

other

line

```md
Break<br />1
Break\
2
```

Break<br />1
Break\
2

# Emphasis

```md
**bold**

__bold or underline__

*italic*

_italic too_

~~strike~~

`code`

==highlight==
```

**bold**

__bold or underline__

*italic*

_italic too_

~~strike~~

`code`

==highlight==

# Quotes

```md
> Quote 1
> Continue
> 
> Continue
>> Nested
```

> Quote 1
> Continue
> 
> Continue
>> Nested

# Lists

```md
1. First
2. Second
3. Third

break

1. First
1. Second
1. Third

break

1. First
2. Second
    1. Indent
```

1. First
2. Second
3. Third

break

1. First
1. Second
1. Third

break

1. First
2. Second
    1. Indent

```md
- A
- B
* C
* D
+ E
+ F
    - Indent
```

- A
- B
* C
* D
+ E
+ F
    - Indent

```md
- 1968\. was a good year

break

- 1968. was a good year
```

- 1968\. was a good year

break

- 1968. was a good year

# Images

```md
![Tux, the Linux mascot](https://www.markdownguide.org/assets/images/generated/assets/images/tux-1080.webp)
```

![Tux, the Linux mascot](https://www.markdownguide.org/assets/images/generated/assets/images/tux-1080.webp)

# Horizontal lines

```md
---

***

___
```

---

***

___

# Tables

```md
| Title 1 | Title Left | Title Center | Title Right |
| --- | :--- | :---: | ---: |
| Value 1 | Value 2 | a | b |
| Value 3 | Value 4 | a | b |
```

| Title 1 | Title Left | Title Center | Title Right |
| --- | :--- | :---: | ---: |
| Value 1 | Value 2 | a | b |
| Value 3 | Value 4 | a | b |

# Footnotes

```md
The small[^1], and a big [^big]

[^1]: Smaller
[^big]: Bigger
    Use tab to include
```

The small,[^1] and a big [^big]

[^1]: Smaller
[^big]: Bigger
    Use tab to include

# Definition

```md
First
: Definition

Second
: Def 1
: Def 1 continue
```

First
: Definition

Second
: Def 1
: Def 1 continue

# Tasks

```md
- [ ] Unfinished
- [x] Finished
```

- [ ] Unfinished
- [x] Finished

# Emoji

<https://emojipedia.org/>

# Sub and super script

```md
H~2~O
H<sub>2</sub>O

X^2^
X<sup>2</sup>
```

H~2~O
H<sub>2</sub>O

X^2^
X<sup>2</sup>

# Code block

\`\`\`LANGUAGE OR NOTHING <br />
write here <br />
\`\`\`

```md
write here
```

# GitHub blocks

```md
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
```

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

Original: <https://github.com/orgs/community/discussions/16925>

# Badges

```md
![Static badge](https://img.shields.io/badge/)
```

![Static badge](https://img.shields.io/badge/)

Visit: <https://shields.io/badges>
