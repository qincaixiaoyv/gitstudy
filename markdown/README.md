Markdown:Basices 快速入门
==========================
[原文](https://www.appinn.com/markdown/basic.html)
[语法说明](https://www.appinn.com/markdown/#overview)


# 1 段落、标题、区块代码
Markdown 支持两种标题的语法，Setext 和 atx 形式。Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题），Atx 形式在行首插入 1 到 6 个 # ，对应到标题 1 到 6 阶。

区块引用则使用 email 形式的 '>' 角括号。

	A First Level Header
	====================
	A Second Level Header
	---------------------
	
	Now is the time for all good men to come to
	the aid of their country. This is just a
	regular paragraph.
	
	The quick brown fox jumped over the lazy
	dog's back.
	### Header 3
	
	> This is a blockquote.
	> 
	> This is the second paragraph in the blockquote.
	>
	> ## This is an H2 in a blockquote

#修辞和强调
Markdown 使用星号和底线来标记需要强调的区段。

Markdown 语法:

	Some of these words *are emphasized*.
	Some of these words _are emphasized also_.
	Use two asterisks for **strong emphasis**.
	Or, if you prefer, __use two underscores instead__.
输出 HTML 为:

	<p>Some of these words <em>are emphasized</em>.
	Some of these words <em>are emphasized also</em>.</p>
	<p>Use two asterisks for <strong>strong emphasis</strong>.
	Or, if you prefer, <strong>use two underscores instead</strong>.</p>
