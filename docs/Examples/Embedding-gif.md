---
title: Embedding gif
sidebar_position: 5
slug: /f105ae8f-4193-47c3-b91b-1140d9e4f39c
---



If you embed a gif in notion, it should be embedded in Docusaurus


## Imgur {#d9aea2bf5f144ad18e7a03d9e2696ad0}


![](/notion_imgs/1607379524.gif)


## Giffy,  {#2b6ce97eb0ae482c89dc59f163b2511a}


![](/notion_imgs/705447076.gif)


When it detects an embedded gif, docu-notion does the following:

- Adds a `import GifPlayer from "react-gif-player";` to the markdown.
- Inserts html like `<GifPlayer gif="https://media.giphy.com/media/VhiAuDYHkNPydiNnOs/giphy.gif" />`

:::info

If your site is not based on `docu-notion-sample-site`, you may need to add react-gif-player to your Docusaurus project:
`yarn add react-gif-player` or `npm i react-gif-player`

:::



