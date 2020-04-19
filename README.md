# books-bibtex
ISBNからBibTeXのコードを出力するPythonコード（ipynb）です。

Google BooksのAPIを使って書籍情報を取得してBibTeXの形式にしてprintします。 

結果は書籍`@book{...}`形式で、author、title、publisher、yearが出力されます。


## 使い方と出力
jupyter notebook等で実行し、ISBN、BibTeXで参照するときの名前（`\cite{ }`に入る名前）、本の出版社
を入力します（Google booksのAPIでは出版社を取得できないので手動で入力 (^^;)）。

いずれかに「end」と入力すると、取得せずに終了します。

- 書籍情報がヒットすれば、BibTeX形式でprintされます。
- ヒット件数が0だとerrorと表示されます。

## 注意
- Google booksの情報が正しいとは限らないので（特に発行年）、結果を自分で確認してから使ってください。
- Google books APIsの取得制限数（1日に1000件まで）に注意してください。

---
## 参照
Google Books APIs : <https://developers.google.com/books?hl=ja>
