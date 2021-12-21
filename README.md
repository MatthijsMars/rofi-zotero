# rofi-zotero

Python 3 script that uses [rofi](https://github.com/davatorium/rofi) to open an
attachment from [Zotero](https://www.zotero.org). The script scrapes the Zotero
SQLite database to gather the list of attachments. The attachment is opened by
`xdg-open`.


## Usage

To use, run or set a keyboard shortcut to run: 

```bash
python3 rofi-zotero.py -z [zotero_path]
```

where `[zotero_path]` points to the path of your zotero folder (typically `~/Zotero/`).


## Example

![](rofi-zotero.gif)
