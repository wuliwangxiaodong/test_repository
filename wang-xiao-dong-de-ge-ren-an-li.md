![](/assets/IMG_20180108_210303.jpg)<xml xmlns="http://www.w3.org/1999/xhtml">
<variables>
<variable id="7-j8N.I0MDV0ObZn;GSv" type="">i</variable>
<variable id="?nXqe6?Lb*oD@;n-Fe?l" type="">s</variable>
</variables>
<block id="PLG}8EPo9f,}HD@AHVN7" type="variables_set" x="-538" y="-237">
<field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType="">i</field>
<value name="VALUE">
<block id="9/}LkBto]dWoH1JHm?ON" type="math_number">
<field name="NUM">0</field>
</block>
</value>
<next>
<block id="lTENFSBz_A(2u!yY3a)y" type="variables_set">
<field id="?nXqe6?Lb*oD@;n-Fe?l" name="VAR" variableType="">s</field>
<value name="VALUE">
<block id="4LZ(q`37jm;:#KTIvFTp" type="math_number">
<field name="NUM">0</field>
</block>
</value>
<next>
<block id="1UBqWpvNEWT%QFaE=C}1" type="controls_whileUntil">
<field name="MODE">UNTIL</field>
<value name="BOOL">
<block id="gtAUM7Biq%^T9EN$^zws" type="logic_compare">
<field name="OP">GT</field>
<value name="A">
<block id="^y%Sg*;={T/1L;foE7fU" type="variables_get">
<field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType="">i</field>
</block>
</value>
<value name="B">
<block id=":sSPrBGA%1?PCuob54Ut" type="math_number">
<field name="NUM">10</field>
</block>
</value>
</block>
</value>
<statement name="DO">
<block id="D!^/t3G3pn=W.L+;_Mz)" type="controls_if">
<value name="IF0">
<block id="by3WB]o6+QaBs-L8dL$`" type="logic_compare">
<field name="OP">LTE</field>
<value name="A">
<block id="keLu+LsIjFP`3ODo}X._" type="variables_get">
<field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType="">i</field>
</block>
</value>
<value name="B">
<block id="RV5$ct+8BGyR%71D#($q" type="math_number">
<field name="NUM">10</field>
</block>
</value>
</block>
</value>
<statement name="DO0">
<block id="uK`b+7Q#:([m4i|@*Ql1" type="variables_set">
<field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType="">i</field>
<value name="VALUE">
<block id="`^_Pi3Bk6(YOwQ/x{mB3" type="math_arithmetic">
<field name="OP">ADD</field>
<value name="A">
<shadow id="lF-E:Vkx`gmL~WjGna@q" type="math_number">
<field name="NUM">1</field>
</shadow>
<block id="4JgF^FH5Zqf^p90JH!V5" type="variables_get">
<field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType="">i</field>
</block>
</value>
<value name="B">
<shadow id="LJbWWj`{{hTi1?^=Ri6O" type="math_number">
<field name="NUM">1</field>
</shadow>
<block id="}6.TtVZ%{3|J7%F:G,uz" type="math_number">
<field name="NUM">1</field>
</block>
</value>
</block>
</value>
<next>
<block id="F*U3fOb8c8$`mdsDmdXO" type="variables_set">
<field id="?nXqe6?Lb*oD@;n-Fe?l" name="VAR" variableType="">s</field>
<value name="VALUE">
<block id="FfgQDBWz4-5.GP.=+bmE" type="math_arithmetic">
<field name="OP">ADD</field>
<value name="A">
<shadow id="?eGpd5`1M4l@~BiX.rJ0" type="math_number">
<field name="NUM">1</field>
</shadow>
<block id="-EM=zOZaAlxrlh4F#Anx" type="variables_get">
<field id="?nXqe6?Lb*oD@;n-Fe?l" name="VAR" variableType="">s</field>
</block>
</value>
<value name="B">
<shadow id="Up;ku@sU4/Ui!R57a0Mg" type="math_number">
<field name="NUM">1</field>
</shadow>
<block id="5Hgfa;*d{$8@hl-{nD[p" type="math_arithmetic">
<field name="OP">MULTIPLY</field>
<value name="A">
<shadow id="d8_wKl;VgCA|zas-]Bi." type="math_number">
<field name="NUM">1</field>
</shadow>
<block id="o/MM0sTY|*3^gs=vSq%G" type="variables_get">
<field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType="">i</field>
</block>
</value>
<value name="B">
<shadow id="7;hH%E9Yt~9I_/XM;EM@" type="math_number">
<field name="NUM">2</field>
</shadow>
<block id="Z@))|oloQ`Fse7=rQyz`" type="math_number">
<field name="NUM">2</field>
</block>
</value>
</block>
</value>
</block>
</value>
</block>
</next>
</block>
</statement>
<next>
<block id="x^~4^kPWmg*~gGJyk?zu" type="controls_flow_statements">
<field name="FLOW">CONTINUE</field>
</block>
</next>
</block>
</statement>
<next>
<block id="3d,}6h`WJ(ei{e4g|nf%" type="text_print">
<value name="TEXT">
<shadow id="]idn,0B$;e/jedtCC@l/" type="text">
<field name="TEXT">abc</field>
</shadow>
<block id="d*,Riv,{dJY${z_K_WTd" type="variables_get">
<field id="?nXqe6?Lb*oD@;n-Fe?l" name="VAR" variableType="">s</field>
</block>
</value>
</block>
</next>
</block>
</next>
</block>
</next>
</block>
<block id=",z3J;$_aF*?+^F},gDRt" type="variables_get" x="812" y="437">
<field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType="">i</field>
</block>
</xml>
