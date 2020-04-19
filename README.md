# books-bibtex
ISBNからBibTeXのコードを出力するコード（Python）です。

Google booksのAPIを使って書籍情報を取得してBibTeXの形式にしてprintします。 

## 使い方
ISBN、BibTeXで参照するときの名前（`\cite{ }`に入る名前）、本の出版社
を入力します。

- 書籍情報がヒットすれば、BibTeX形式でprintされます。
- ヒット件数が0だとerrorと表示されます。
