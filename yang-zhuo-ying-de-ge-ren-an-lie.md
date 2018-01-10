&lt;!--  
 /\* Font Definitions \*/  
 @font-face  
	{font-family:"Cambria Math";  
	panose-1:2 4 5 3 5 4 6 3 2 4;  
	mso-font-charset:0;  
	mso-generic-font-family:roman;  
	mso-font-pitch:variable;  
	mso-font-signature:-536870145 1107305727 0 0 415 0;}  
@font-face  
	{font-family:等线;  
	panose-1:2 1 6 0 3 1 1 1 1 1;  
	mso-font-alt:DengXian;  
	mso-font-charset:134;  
	mso-generic-font-family:auto;  
	mso-font-pitch:variable;  
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
@font-face  
	{font-family:"\@等线";  
	panose-1:2 1 6 0 3 1 1 1 1 1;  
	mso-font-charset:134;  
	mso-generic-font-family:auto;  
	mso-font-pitch:variable;  
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}  
@font-face  
	{font-family:楷体;  
	panose-1:2 1 6 9 6 1 1 1 1 1;  
	mso-font-charset:134;  
	mso-generic-font-family:modern;  
	mso-font-pitch:fixed;  
	mso-font-signature:-2147482945 953122042 22 0 262145 0;}  
@font-face  
	{font-family:"\@楷体";  
	panose-1:2 1 6 9 6 1 1 1 1 1;  
	mso-font-charset:134;  
	mso-generic-font-family:modern;  
	mso-font-pitch:fixed;  
	mso-font-signature:-2147482945 953122042 22 0 262145 0;}  
 /\* Style Definitions \*/  
 p.MsoNormal, li.MsoNormal, div.MsoNormal  
	{mso-style-unhide:no;  
	mso-style-qformat:yes;  
	mso-style-parent:"";  
	margin:0cm;  
	margin-bottom:.0001pt;  
	text-align:justify;  
	text-justify:inter-ideograph;  
	mso-pagination:none;  
	font-size:10.5pt;  
	mso-bidi-font-size:11.0pt;  
	font-family:等线;  
	mso-ascii-font-family:等线;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:等线;  
	mso-fareast-theme-font:minor-fareast;  
	mso-hansi-font-family:等线;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;  
	mso-font-kerning:1.0pt;}  
.MsoChpDefault  
	{mso-style-type:export-only;  
	mso-default-props:yes;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;}  
 /\* Page Definitions \*/  
 @page  
	{mso-page-border-surround-header:no;  
	mso-page-border-surround-footer:no;}  
@page Section1  
	{size:595.3pt 841.9pt;  
	margin:72.0pt 90.0pt 72.0pt 90.0pt;  
	mso-header-margin:42.55pt;  
	mso-footer-margin:49.6pt;  
	mso-paper-source:0;  
	layout-grid:15.6pt;}  
div.Section1  
	{page:Section1;}  
--&gt;  


**判断“水仙花数”的计算程序——用blockly实现**

**16生物萃英班杨倬颖 320160926980**



  
 题目：判断输入的数是否为"水仙花数"，所谓"水仙花数"是指一个三位数，其各位数字立方和等于该数本身。例如：153是一个"水仙花数"，因为153=1的三次方＋5的三次方＋3的三次方。



1.程序截图：

![](/assets/import.png)



2.运行界面

![](/assets/import.png2)

![](/assets/import.png3)

![](/assets/import.png4)

![](/assets/import.png5)







3. XML 代码

&lt;xml xmlns="http://www.w3.org/1999/xhtml"&gt;

&lt;variables&gt;

&lt;variable type="" id="1.ug=$E~K66\_BPh\*mvzv"&gt;a&lt;/variable&gt;

&lt;variable type="" id="i1\)p/qQTeJj/J^d0HQy\("&gt;b&lt;/variable&gt;

&lt;variable type="" id="Mc8DM3-3k;\|X,v\[z6I+A"&gt;c&lt;/variable&gt;

&lt;variable type="" id="%Ozc\|zq\#9x6VZY{/@}B~"&gt;d&lt;/variable&gt;

&lt;variable type="" id="C:T2;9^Yt.;J9IR%2~8k"&gt;m&lt;/variable&gt;

&lt;variable type="" id="BOaw!wiJKTd5txfBnilO"&gt;n&lt;/variable&gt;

&lt;variable type="" id="ziUMg7@9QakI6fFc8/OC"&gt;x&lt;/variable&gt;

&lt;variable type="" id="hhG8HfrC3\|cT-0~-W?.v"&gt;y&lt;/variable&gt;

&lt;variable type="" id="b!vo@4hKfv\)^4+gXJ\*f="&gt;z&lt;/variable&gt;

&lt;/variables&gt;

&lt;block type="variables\_set" id="rCif}w4B08AX\`n!W.S\|n" x="-638" y="-437"&gt;

&lt;field name="VAR" id="1.ug=$E~K66\_BPh\*mvzv" variabletype=""&gt;a&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="text\_prompt\_ext" id="bvNq\(%@K0ukjjS5\)zKnn"&gt;

&lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

&lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="}.O+^C@;d1\[@/KWpO.uU"&gt;

&lt;field name="TEXT"&gt;number&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="dBGmbgH^\`I1}d~k0A\`E%"&gt;

&lt;field name="VAR" id="i1\)p/qQTeJj/J^d0HQy\(" variabletype=""&gt;b&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_modulo" id="cgF5:zJL/fIrh}3?fGu:"&gt;

&lt;value name="DIVIDEND"&gt;

&lt;shadow type="math\_number" id=",5v@NQq\#Q^GuibJ76?T/"&gt;

&lt;field name="NUM"&gt;64&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="qRR{Gk?@ZYy\)NFuY9WW\["&gt;

&lt;field name="VAR" id="1.ug=$E~K66\_BPh\*mvzv" variabletype=""&gt;a&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="DIVISOR"&gt;

&lt;shadow type="math\_number" id="e\[?Wk.hy\|M:COC3h\*\`gz"&gt;

&lt;field name="NUM"&gt;100&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="nzP\#su,\*!jFg9%K\`1j$\#"&gt;

&lt;field name="VAR" id="Mc8DM3-3k;\|X,v\[z6I+A" variabletype=""&gt;c&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_modulo" id="j~thU\#ecDn}\]m1^Onq\]\("&gt;

&lt;value name="DIVIDEND"&gt;

&lt;shadow type="math\_number" id="Kx\`Z/W0r+lFyD@9pnff9"&gt;

&lt;field name="NUM"&gt;64&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="C0TJ\(.:P,\|1/Cd8EBX4E"&gt;

&lt;field name="VAR" id="i1\)p/qQTeJj/J^d0HQy\(" variabletype=""&gt;b&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="DIVISOR"&gt;

&lt;shadow type="math\_number" id="+81a^D\*\#W!xMaES:{1tj"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="o0ar$\(zvA1Q%miFK6j5k"&gt;

&lt;field name="VAR" id="C:T2;9^Yt.;J9IR%2~8k" variabletype=""&gt;m&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_arithmetic" id="u^~Gw72X=I6\)\|B}Jy\*la"&gt;

&lt;field name="OP"&gt;DIVIDE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="Wt+GT\]9?pH.qQHHEaKbf"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="SiE\|\[SU26nq!l\),suVkF"&gt;

&lt;field name="OP"&gt;MINUS&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="D\#d}F7DUg;dIg4=T,\]l;"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="P{ncjeA8:WXjek7m96\|^"&gt;

&lt;field name="VAR" id="i1\)p/qQTeJj/J^d0HQy\(" variabletype=""&gt;b&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="\[E9SXAADnmg!fM2%\($!6"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id=".xHK!p81Q.3awUkGB$\[u"&gt;

&lt;field name="VAR" id="Mc8DM3-3k;\|X,v\[z6I+A" variabletype=""&gt;c&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="8\|ep1HenTca;HO;qabFY"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="variables\_set" id="\|Vm!8tp~b0Ywvflt:jJy"&gt;

&lt;field name="VAR" id="BOaw!wiJKTd5txfBnilO" variabletype=""&gt;n&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_arithmetic" id="xGeO9\*u^T04.\#56O!/xE"&gt;

&lt;field name="OP"&gt;DIVIDE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="mUsA5$1N=yOywM\#iVjB+"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="akiB1$4+^$yIGb/EK\[21"&gt;

&lt;field name="OP"&gt;MINUS&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="s3dOfX^9BiHg,r$/%I=g"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="yJo~Yp\*%L.\_\[XHgL\|kEi"&gt;

&lt;field name="VAR" id="1.ug=$E~K66\_BPh\*mvzv" variabletype=""&gt;a&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="j\`~\[\#i69\`SQ\|f-NRI+ez"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="u-w0~~\`O$x\`,ePwDho\*D"&gt;

&lt;field name="VAR" id="i1\)p/qQTeJj/J^d0HQy\(" variabletype=""&gt;b&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="PP5\].+CcTg?-0.dp1GL\*"&gt;

&lt;field name="NUM"&gt;100&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="controls\_if" id="ox%mP2\`GQq9\|TLSq$=\|."&gt;

&lt;value name="IF0"&gt;

&lt;block type="logic\_compare" id="^iMOP0Vhe8CvncKx6ogO"&gt;

&lt;field name="OP"&gt;EQ&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_arithmetic" id="LF/LUqO6$~CzhaQ;iU9Q"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id=".aWa1DuwDN2e^XuTQh3!"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="y\(v\*YAQ;Ua?vEM\|\)G3mq"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="w9cSfU1Km8ETE@XsV28n"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="=rRRQRq}}w\_.X-wiD\(;H"&gt;

&lt;field name="VAR" id="Mc8DM3-3k;\|X,v\[z6I+A" variabletype=""&gt;c&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="$wAjjo\*\_t}mDBX!w.EUp"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="FDp^BtSH@{{+UCgQd0d}"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="fZG{bLJ4\`svf\[\_as~di0"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="WS\[$JhRUyp%LBMk$!oO\["&gt;

&lt;field name="VAR" id="Mc8DM3-3k;\|X,v\[z6I+A" variabletype=""&gt;c&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="+1\]\|Nuex@.0yL\|NCm7lt"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="vE/0H^DL\*=^q}a\)jYt76"&gt;

&lt;field name="VAR" id="Mc8DM3-3k;\|X,v\[z6I+A" variabletype=""&gt;c&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="7\|\]crJ%\_\(igAmUgBqQA="&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="a\[M,u40H!+irKTOx\`9mj"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="3HtcU.;1NTHs\*}1kWpT{"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="C4Jg6:?vTECWN@c\(i\[C-"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="q\_jW-ihh7Ify3\[Z2nJ,v"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="q/P\[nVWIJ;XK:~4~\*\(Hp"&gt;

&lt;field name="VAR" id="C:T2;9^Yt.;J9IR%2~8k" variabletype=""&gt;m&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="86J\)H;RxC^zC0^LV\`kPx"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="xl,P^Yz$f1Ei\(M\`AT\]VG"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="e5G9;E{kLF}m^C\[z60VU"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="Q\#bZw4t\|+\]zxmYvyg\*OK"&gt;

&lt;field name="VAR" id="C:T2;9^Yt.;J9IR%2~8k" variabletype=""&gt;m&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="joLL6!U11\|.Isf0,-/qr"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="C3P3{5M;Ch2:mJufEN:a"&gt;

&lt;field name="VAR" id="C:T2;9^Yt.;J9IR%2~8k" variabletype=""&gt;m&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="~FKN\#@2ykcR@IOo{{N+8"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="^BZlHG}zQh6cLp\*He+kN"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="+gE}WgPWqUaD\)W\]8M4+U"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="x}9a;\_i\|eQy76\`a?lR}P"&gt;

&lt;field name="VAR" id="BOaw!wiJKTd5txfBnilO" variabletype=""&gt;n&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="\]Rnz:S+5kH\(gI\_IoL%tm"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="\_ap\[ScH}{EH233,IJ:\*G"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="b?\`JDIipDnNogLt~V?xQ"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="W423,A=U5kt{2Y/+GbG^"&gt;

&lt;field name="VAR" id="BOaw!wiJKTd5txfBnilO" variabletype=""&gt;n&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="gCDPi@?jLx2OxQ~VUpQ{"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="}wjJ\#0iG10k\(XejfZwAT"&gt;

&lt;field name="VAR" id="BOaw!wiJKTd5txfBnilO" variabletype=""&gt;n&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="variables\_get" id="In2im$;v$/ZarUOqp+Wu"&gt;

&lt;field name="VAR" id="1.ug=$E~K66\_BPh\*mvzv" variabletype=""&gt;a&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block type="text\_print" id="FDmk.R\*ent/K0^Ral-JZ"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="1sT\#-:.eMfPZ3FR\#r%E+"&gt;

&lt;field name="TEXT"&gt;是水仙花数&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;next&gt;

&lt;block type="text\_print" id="z.\`uffkh\`!Gtya58.od$"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="^s$MVNp~AsXZfJc-h.\*,"&gt;

&lt;field name="TEXT"&gt;不是水仙花数&lt;/field&gt;

&lt;/shadow&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/xml&gt;

 c

