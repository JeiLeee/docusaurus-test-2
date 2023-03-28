---
title: Embedding gif
sidebar_position: 5
slug: /92cebd2d-de54-404b-a8b8-39deea36c0b7
---



If you embed a gif in notion, it should be embedded in Docusaurus


## Imgur {#938bb622c5e2449d9ed3c85d80e1191f}


![](./1607379524.gif)


## Giffy,  {#0dbdf9f00775458f96c2f9e89bb16015}


![](./705447076.gif)


When it detects an embedded gif, docu-notion does the following:

- Adds a `import GifPlayer from "react-gif-player";` to the markdown.
- Inserts html like `<GifPlayer gif="https://media.giphy.com/media/VhiAuDYHkNPydiNnOs/giphy.gif" />`

:::info

If your site is not based on `docu-notion-sample-site`, you may need to add react-gif-player to your Docusaurus project:
`yarn add react-gif-player` or `npm i react-gif-player`

:::



