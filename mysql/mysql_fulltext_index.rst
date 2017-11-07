=============
MySQL全文索引
=============

简介
----

FULLTEXT indexes are created on text-based columns (CHAR, VARCHAR, or TEXT columns) 
to help speed up queries and DML operations on data contained within those columns, 
omitting any words that are defined as stopwords.


创建全文索引
------------

.. code-block:: sql

  CREATE FULLTEXT INDEX index_name ON table_name (index_col_name, ...);

