![](/assets/P3XMJFMPXPJU7T]~7UTB%29}8.png)

&lt;!--  
 /\* Font Definitions \*/  
 @font-face  
	{font-family:宋体;  
	panose-1:2 1 6 0 3 1 1 1 1 1;  
	mso-font-alt:SimSun;  
	mso-font-charset:134;  
	mso-generic-font-family:auto;  
	mso-font-pitch:variable;  
	mso-font-signature:3 680460288 22 0 262145 0;}  
@font-face  
	{font-family:"Cambria Math";  
	panose-1:2 4 5 3 5 4 6 3 2 4;  
	mso-font-charset:0;  
	mso-generic-font-family:roman;  
	mso-font-pitch:variable;  
	mso-font-signature:-536870145 1107305727 0 0 415 0;}  
@font-face  
	{font-family:Calibri;  
	panose-1:2 15 5 2 2 2 4 3 2 4;  
	mso-font-charset:0;  
	mso-generic-font-family:swiss;  
	mso-font-pitch:variable;  
	mso-font-signature:-536859905 -1073732485 9 0 511 0;}  
@font-face  
	{font-family:"\@宋体";  
	panose-1:2 1 6 0 3 1 1 1 1 1;  
	mso-font-charset:134;  
	mso-generic-font-family:auto;  
	mso-font-pitch:variable;  
	mso-font-signature:3 680460288 22 0 262145 0;}  
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
	mso-bidi-font-size:12.0pt;  
	font-family:"Calibri","sans-serif";  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:宋体;  
	mso-fareast-theme-font:minor-fareast;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:"Times New Roman";  
	mso-bidi-theme-font:minor-bidi;  
	mso-font-kerning:1.0pt;}  
.MsoChpDefault  
	{mso-style-type:export-only;  
	mso-default-props:yes;  
	font-size:10.0pt;  
	mso-ansi-font-size:10.0pt;  
	mso-bidi-font-size:10.0pt;  
	mso-ascii-font-family:"Times New Roman";  
	mso-fareast-font-family:宋体;  
	mso-hansi-font-family:"Times New Roman";  
	mso-font-kerning:0pt;}  
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


&lt;xml xmlns="http://www.w3.org/1999/xhtml"&gt;

&lt;variables&gt;

&lt;variable type="" id="f%kPU\]nX-cI=~Gx\[f\*=%"&gt;平均成绩&lt;/variable&gt;

&lt;variable type="" id="T\`O}i@8g?vlBlVu\|x8ru"&gt;出勤情况&lt;/variable&gt;

&lt;variable type="" id="2jM\(=hqJ\#W%Z.K\#D^%+x"&gt;期中成绩&lt;/variable&gt;

&lt;variable type="" id="\(1=oAhM\)S~vPlHDKk!Ls"&gt;期末成绩&lt;/variable&gt;

&lt;/variables&gt;

&lt;block type="variables\_set" id="}^-}@Qy,7!w\|5U\[ADS9R" x="137" y="-37"&gt;

&lt;field name="VAR" id="f%kPU\]nX-cI=~Gx\[f\*=%" variabletype=""&gt;平均成绩&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="WHgsi1ay!x\#U-=C,0Zf9"&gt;

&lt;field name="NUM"&gt;4&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block type="controls\_if" id="3s2~yL\`mzs//\)KYYhf;q"&gt;

&lt;value name="IF0"&gt;

&lt;block type="logic\_compare" id="nw\]2Rfrl\|.:1^Lxx\|,:\#"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="logic\_compare" id="\[pQuLCa0AN\#fIV\[h21yC"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_number" id="DbywE{P-b+VxliI8o9\)l"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="variables\_get" id="cB\*::Nj\)g3xWTtk=4e/t"&gt;

&lt;field name="VAR" id="f%kPU\]nX-cI=~Gx\[f\*=%" variabletype=""&gt;平均成绩&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_number" id="G}P~0\[Ui~:3+=ne^;\#\(;"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block type="variables\_set" id="oo8=\(5mZr~w\`SQ:-47Uq"&gt;

&lt;field name="VAR" id="T\`O}i@8g?vlBlVu\|x8ru" variabletype=""&gt;出勤情况&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="4k$i?y-@-UhQW+7hz\_uB"&gt;

&lt;field name="NUM"&gt;8&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;next&gt;

&lt;block type="controls\_if" id="\*/VLguY2ZiG2b\|r^DA,2"&gt;

&lt;value name="IF0"&gt;

&lt;block type="logic\_compare" id="\]ftx+3Ej\)-P:lnFAXT\#p"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="logic\_compare" id="\[V^\*}{PHrv;rD!N$P$8o"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_number" id="x=@Khp{EVrM$a.t1Xn{k"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="variables\_get" id="W0p2=i4q\*5!U/u7K\|eyy"&gt;

&lt;field name="VAR" id="T\`O}i@8g?vlBlVu\|x8ru" variabletype=""&gt;出勤情况&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_number" id="5jprkU?2=D\*937Go6\#Bf"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block type="variables\_set" id="wFi?PtMEr\]4\|cWZSz\[4C"&gt;

&lt;field name="VAR" id="2jM\(=hqJ\#W%Z.K\#D^%+x" variabletype=""&gt;期中成绩&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="F!h63\*I~Cj~UeoGzR7,j"&gt;

&lt;field name="NUM"&gt;20&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;next&gt;

&lt;block type="controls\_if" id="tfUDtA$7\*h.\[!%o-S3,s"&gt;

&lt;value name="IF0"&gt;

&lt;block type="logic\_compare" id="mD%-\[t@W%t?PMW.4\(jxx"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="logic\_compare" id="!hnME44BZTv\#GKb!?S67"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_number" id="P!MXB\`yp\);s6$i^0,sVu"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="variables\_get" id="pfdTuvj16\(/ASk^%kn\|P"&gt;

&lt;field name="VAR" id="2jM\(=hqJ\#W%Z.K\#D^%+x" variabletype=""&gt;期中成绩&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_number" id="}:0pBJZcaY\|\)4amkDf3\|"&gt;

&lt;field name="NUM"&gt;30&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block type="variables\_set" id="l\`v0$tsLbJwybUGM5xM;"&gt;

&lt;field name="VAR" id="\(1=oAhM\)S~vPlHDKk!Ls" variabletype=""&gt;期末成绩&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block type="math\_number" id="cOErc.Ojmm{.YD:LS\#VG"&gt;

&lt;field name="NUM"&gt;40&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;next&gt;

&lt;block type="controls\_if" id="\#cgTYD\(0fg\`GsJX5;e.0"&gt;

&lt;value name="IF0"&gt;

&lt;block type="logic\_compare" id="{N3-ERy$y\)nhBgi\|TFox"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="logic\_compare" id="U}BAMTc8^X=^D\[!pAqVD"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_number" id="r5\)\[^J^\`\]KjOv\#30dgjf"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="variables\_get" id="{u1Ll?X\_?9nOb/n%K\#\]\("&gt;

&lt;field name="VAR" id="\(1=oAhM\)S~vPlHDKk!Ls" variabletype=""&gt;期末成绩&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_number" id="H5a6S}Hb\*kVp%}C;Jrk\#"&gt;

&lt;field name="NUM"&gt;50&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block type="controls\_if" id="P,B03\(!Z~Sul\[VeUmbX/"&gt;

&lt;value name="IF0"&gt;

&lt;block type="logic\_compare" id="}7?cw\#e\(X}r-t@:YM99~"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="logic\_compare" id="IA~\]7\*\]^nFD\`muqvRi3\`"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_number" id="5fg;!$=OXHXU5BDG\_j0q"&gt;

&lt;field name="NUM"&gt;5&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="variables\_get" id="?\[vJ@=HH!=ni3vQscJaN"&gt;

&lt;field name="VAR" id="f%kPU\]nX-cI=~Gx\[f\*=%" variabletype=""&gt;平均成绩&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_number" id=":a4Cz\|6f$;1l\_!c\(N1pZ"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block type="controls\_if" id="9-UA19\|Y\)BH@Rk!=,u!5"&gt;

&lt;value name="IF0"&gt;

&lt;block type="logic\_compare" id="aW3/\_idv74n$p4-v+a$Q"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="logic\_compare" id="Dy}%f\[\]MTu\)z0Bik\)c@$"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block type="math\_number" id="23Nu5Ejl5,bKIJv}CL\);"&gt;

&lt;field name="NUM"&gt;7&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="variables\_get" id="q\#cQlmoumy\]f@~Z\`@s93"&gt;

&lt;field name="VAR" id="T\`O}i@8g?vlBlVu\|x8ru" variabletype=""&gt;出勤情况&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block type="math\_number" id="I\`I\`bkWy~ewO3FB\[pipL"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block type="text\_print" id="@;NN\[3xx@\|fVmDuL%4Sm"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow type="text" id="YdWoq\(\)\`SR\*i%!J\*-Azi"&gt;

&lt;field name="TEXT"&gt;abc&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="CC45\`uUu=czEC\]C2D~3D"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="mEcp9@d^z\#izN6X\#KA@+"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="zK\#HPRv$6e{2-8HjUqk5"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="3U4rH\_K\)i64SkgrN\[\`\)h"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="r{Gox{VJY,\(\(!tf,5LGt"&gt;

&lt;field name="VAR" id="f%kPU\]nX-cI=~Gx\[f\*=%" variabletype=""&gt;平均成绩&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="R\(q;EuHu5Yh\*9INhjWUI"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="\`m~QF2tOSBIE9ji}z9hc"&gt;

&lt;field name="VAR" id="T\`O}i@8g?vlBlVu\|x8ru" variabletype=""&gt;出勤情况&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="\`q{duugAH~pN+vA!usHI"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="math\_arithmetic" id="M6r;QS\)g\(\[Irz2anvnFy"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow type="math\_number" id="RO}\)Dv0j\)tHu?}jb2xD/"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="\`uG\*H\*a\_qihA\#G/YqcNl"&gt;

&lt;field name="VAR" id="2jM\(=hqJ\#W%Z.K\#D^%+x" variabletype=""&gt;期中成绩&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow type="math\_number" id="8YXF2c%D\#du+FJ4q\_^xk"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block type="variables\_get" id="xxzM7UESU\`l1!E\]Of5d\("&gt;

&lt;field name="VAR" id="\(1=oAhM\)S~vPlHDKk!Ls" variabletype=""&gt;期末成绩&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;/block&gt;

&lt;/statement&gt;

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

 �

