------------------------------------------------
ロケールID(LCID)の一覧
------------------------------------------------

Excelで指定可能なロケールの一覧は、外部サイトの `ロケール ID (LCID) の一覧 <https://msdn.microsoft.com/ja-jp/library/cc392381.aspx>`_ で確認できます。

Excelの書式で指定する際には、16進数表記の値で指定します。

日本語の場合、LCIDは0x0411であるため、書式上では ``[$-411]`` と指定します。

.. csv-table:: LCIDの一覧
   :widths: 20 10 10 10 20 10 10 10
   :header-rows: 1
   :file: _static/lcid_list.csv
