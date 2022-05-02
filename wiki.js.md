---
description: Notation in wiki.js, an excellent wiki tool
---

# 🔍 Wiki.js

> <mark style="background-color:yellow;">**Excerpt from the official website**</mark>

## Editors

Using the various editors of Wiki.js



When creating a page, you can use the editor of your choice. Some users prefer to write content in Markdown while others might prefer a more visual editor.

### List of Editors <a href="#list-of-editors" id="list-of-editors"></a>

* [Code _Raw HTML_](https://docs.requarks.io/editors/code)
* [Markdown _Plain Text Formatting_](https://docs.requarks.io/editors/markdown)
* [Visual Editor _Rich-Text WYSIWYG_](https://docs.requarks.io/editors/visualeditor)

### Change Editor <a href="#change-editor" id="change-editor"></a>

> This feature is available from version **2.5.201 and up**.

You can change the editor used for any page using the **Convert** action. This will attempt to convert the content to be used by the newly selected editor. For example, a page previously created with the Markdown editor can be converted to HTML to be used with the Visual Editor.

From the **Page Actions** menus (located at the top-right corner and bottom-right corner), select **Convert**. The following dialog is shown:

![ui-convert-page-dialog.png](https://docs.requarks.io/assets/ui/ui-convert-page-dialog.png)

Select the editor you want to use going forward and click **Convert**.

> ![⚠️](https://docs.requarks.io/\_assets/svg/twemoji/26a0.svg) **Important**
>
> Because of differences between editor / format capabilities, some formatting or non-rendered content may be lost after the conversion.
>
> A snapshot of the page is **automatically taken before the conversion** and you can revert or refer to this version **at any time afterwards** from the page history.
>
> _Examples_
>
> ∗ When going from Markdown to HTML, `draw.io` diagrams will be kept as their final rendered image. You will no longer be able to edit the diagram.\
> ∗ When going from Markdown to HTML, tabsets will be reverted to standard headers and paragraphs (as seen in the markdown editor).\
> ∗ When going from HTML to Markdown, custom CSS classes and HTML elements that don't exist in the Markdown language will not be preserved.

As a reference, the following format conversions occur based on the source / target editor selected:

| Source        | Target        | Format Conversion             |
| ------------- | ------------- | ----------------------------- |
| Markdown      | Visual Editor | Markdown -> HTML              |
| Markdown      | Raw HTML      | Markdown -> HTML              |
| Visual Editor | Markdown      | HTML -> Markdown              |
| Visual Editor | Raw HTML      | _no format conversion needed_ |
| Raw HTML      | Markdown      | HTML -> Markdown              |
| Raw HTML      | Visual Editor | _no format conversion needed_ |



{% hint style="success" %}
[https://docs.requarks.io/editors](https://docs.requarks.io/editors)
{% endhint %}



