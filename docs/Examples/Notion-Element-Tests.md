---
title: Notion Element Tests
sidebar_position: 2
slug: /13bfbec5-126b-48f8-996f-b07f07f42533
---

import ReactPlayer from "react-player";

:::tip

This is a normal Notion Callout

:::




## Columns {#9b15d967002e467793c58a1a28f02d2f}


There should be text on the left, and an apple on the right.


<div class='notion-row'>
<div class='notion-column' style={{width: 'calc((100% - (min(32px, 4vw) * 1)) * 0.375)'}}>

A paragraph on the left.

Another paragraph.

</div><div className='notion-spacer' />

<div class='notion-column' style={{width: 'calc((100% - (min(32px, 4vw) * 1)) * 0.625)'}}>

![](/notion_imgs/1528015832.png)



</div><div className='notion-spacer' />
</div>


## Embedded YouTube: {#732a8b2447f24de1bd0410c33526c32a}


<ReactPlayer controls url="https://www.youtube.com/watch?v=VjINuQX4hbM" />


## Heading Links {#33f246f2235e477fbefb64fa3b5af333}


Though Docusaurus doesn’t allow linking to heading 1 within their system (see [linking to a heading 1](/oranges) still works through docu-notion if we just code it up the same way as the others.

- Link to a [heading 2](/oranges).
- Link to a [heading 3](/oranges).

## Tables {#e038c74836cf48d2b024811b4eaec6ff}


| head 1        | head 2 |
| ------------- | ------ |
| who           | this   |
| what<br/>yeah | that   |

