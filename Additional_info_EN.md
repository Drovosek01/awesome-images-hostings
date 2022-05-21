Language: [Русский](Additional_info_RU.md) | English

## Additional information about services

Unfortunately, Markdown features do not allow you to adjust the width of cells and tables, and if you add all the additional information about each service to the comparison table, then it becomes too elongated in height, not beautiful and less easy to read.

Therefore, I decided to transfer the existing additional information to a separate file and add new information here as well.

For each service for which additional information will be added, you need to make the header `H3` so that you can access it via the anchor link.

You can also find out more information about the service if you visit the official pages, the official rules of the services, their FAQ, etc. yourself.

### imgur

- [API Info](https://api.imgur.com/)
- [API Docs](https://apidocs.imgur.com/)
- [Full supported fil types and size limits](https://apidocs.imgur.com/)
- Maximum PNG size = 5 MB, if the PNG file size is larger, it is automatically converted to JPG
- Information about the name of the original file can be obtained by clicking on the image in the account
- Links to the preview can be found by clicking on the picture in the account
- Links to the preview can be made by adding these characters in the direct link before the extension `s`/`b`/`t`/`m`/`l`/`h`
  - For example here original https://i.imgur.com/AoQ28wt.jpeg and thumbnails https://i.imgur.com/AoQ28wts.jpeg, https://i.imgur.com/AoQ28wtb.jpeg, https://i.imgur.com/AoQ28wtt.jpeg, https://i.imgur.com/AoQ28wtm.jpeg, https://i.imgur.com/AoQ28wtl.jpeg, https://i.imgur.com/AoQ28wth.jpeg

### imageban

- [API Info](https://imageban.ru/api)
- [FAQ](https://imageban.ru/faq)

### fastpic

- Loading from the clipboard does not work on the old version of the site
- For large images by weight (more than 512 KB) and size (any side of the image is larger than 1.164 Megapixels), a direct link is not generated automatically (but can be obtained manually)

### imgbb

- [API Info](https://api.imgbb.com/)
- Preview links can only be obtained manually from embed codes
- The service has paid functions

### postimages

- The preview link can only be obtained manually from the embed codes
- The preview link is the same as a regular direct link
- The service has paid functions

### imgbox

- You can also get a preview link by replacing `images2` with `thumbs2` and `_t` with `_o`
  - For exapmle here original https://images2.imgbox.com/45/98/GjnpItqF_o.png and thumbnail https://thumbs2.imgbox.com/45/98/GjnpItqF_t.png
- The preview can only be square