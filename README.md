**＃YOURLS日本語訳**
このフォーク及び日本語訳ファイルは、私(torichan)がより自然かつわかりやすい日本語訳へと編集したものです。

# YOURLS-ja_JP
Japanese translations for the YOURLS URL Shortener service

For some reason the original first translator of YOURLS to Japanese deleted the repository,
so I re-created it here.

Note these are original translations created by me, not the original translation.
All blame (and possibly credit if you must) goes to me.

Details here:

https://github.com/YOURLS/YOURLS/wiki/YOURLS-in-your-language

If you notice something that's still untranslated, or you see a mistake or something that
could be worded better, please feel free to contribute. It is open source, after all.

## Installation

1. Create the binary message file by either running `make` or `msgfmt -o ja_JP.mo ja_JP.po`
2. In `config.php` edit (or add if it's not there) the following line:
    - `define( 'YOURLS_LANG', 'ja_JP' );`
3. In directory `user/languages`, install the file `ja_JP.mo`. If you're using Apache on
CentOS or Ubuntu and YOURLS is in the root directory of web server html files
(`/var/www/html`), running `make install` with the correct permissions should copy the
binary message file into the right place.

## License

Same as YOURLS:
- MIT
