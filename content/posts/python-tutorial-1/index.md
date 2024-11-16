+++
date = '2024-11-15T12:11:31Z'
draft = false
title = 'Python教學Ep1 | 你好，世界！'
tags = ['python', '程式', '教學']
categories = ['科技','程式']
+++

> *你好，世界！~~這是我統治你們的開端~~*
--*電腦 沒有說過*

## 前言 | 你好，世界
> *C is not a big language, and it is not well served by a big book.*  
--*Brian W. Kernighan, [The C Programming Language](https://en.m.wikipedia.org/wiki/The_C_Programming_Language)*

上世紀70年代，一個叫Brian Kernighan的工程師在一份內部文件《A Tutorial Introduction to the Language B》中，首次使用了B語言寫出一個會在終端印出"hello, world"的程式。  

接著之後，這個範例又出現在他與電腦傳奇Dennis Ritchie一起出版的[C程式設計語言 The C Programming Language](https://en.m.wikipedia.org/wiki/The_C_Programming_Language)  

自那時起，讓電腦說出"hello, world"便慢慢成為不管哪種語言的基礎範例。

*資料來源 - [維基百科](https://zh.m.wikipedia.org/zh-tw/Hello_World)*

## Step 1 | 新增檔案
請打開VS code並開啟一個任意一個資料夾，在其中選擇「新增檔案」並輸入檔名為`<任意檔名>.py`
> ⚠️ 副檔名`.py`**不可以省略！！！**

我們在上一章[Ep0](/posts/python-tutorial-0)時有提到，編譯器會幫我們翻譯程式語言成機器語言。  
如果今天副檔名不是`.py`，那麼編譯器無法辨識這是一個「要被編譯的檔案」，所以`.py`不可以省略。  
好了之後，就可以進行下一步了！  

## Step 2 | 寫程式
在Python中，要印出hello world，只需要一行就能解決：
```python
print("hello, world!")
```
請在複製這段代碼到VS code並執行。你應該會看到：
```
hello, world!
```
> ⚠️ 雙引號`"`是**不能省略**的！關於這件事，我們下一章會談到

恭喜你，你已經完成進入程式圈子的第一步了！  
現在，讓我們嘗試一些更進階的吧！  

## 習題 | 早安owo
請設計一個程式，會印出「早安！今天天氣真好owo」字樣。

## 結語 | 好欸
俗話說得好，今天能讓終端印出東西，~~明天就能駭進別人的電腦~~  
好吧沒有，我在瞎掰。不過，能使用程式印出文字，這代表你已經開始試圖理解電腦。  
只要繼續學下去，總有一天，你會變成超強的Programmer！