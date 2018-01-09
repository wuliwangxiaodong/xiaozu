![](/assets/IMG_20180108_210303.jpg)

&lt;xml xmlns="http://www.w3.org/1999/xhtml"&gt;

&lt;variables&gt;

&lt;variable id="7-j8N.I0MDV0ObZn;GSv" type=""&gt;i&lt;/variable&gt;

&lt;variable id="?nXqe6?Lb\*oD@;n-Fe?l" type=""&gt;s&lt;/variable&gt;

&lt;/variables&gt;

&lt;block id="PLG}8EPo9f,}HD@AHVN7" type="variables\_set" x="-538" y="-237"&gt;

&lt;field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType=""&gt;i&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block id="9/}LkBto\]dWoH1JHm?ON" type="math\_number"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block id="lTENFSBz\_A\(2u!yY3a\)y" type="variables\_set"&gt;

&lt;field id="?nXqe6?Lb\*oD@;n-Fe?l" name="VAR" variableType=""&gt;s&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block id="4LZ\(q\`37jm;:\#KTIvFTp" type="math\_number"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block id="1UBqWpvNEWT%QFaE=C}1" type="controls\_whileUntil"&gt;

&lt;field name="MODE"&gt;UNTIL&lt;/field&gt;

&lt;value name="BOOL"&gt;

&lt;block id="gtAUM7Biq%^T9EN$^zws" type="logic\_compare"&gt;

&lt;field name="OP"&gt;GT&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block id="^y%Sg\*;={T/1L;foE7fU" type="variables\_get"&gt;

&lt;field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block id=":sSPrBGA%1?PCuob54Ut" type="math\_number"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO"&gt;

&lt;block id="D!^/t3G3pn=W.L+;\_Mz\)" type="controls\_if"&gt;

&lt;value name="IF0"&gt;

&lt;block id="by3WB\]o6+QaBs-L8dL$\`" type="logic\_compare"&gt;

&lt;field name="OP"&gt;LTE&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block id="keLu+LsIjFP\`3ODo}X.\_" type="variables\_get"&gt;

&lt;field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block id="RV5$ct+8BGyR%71D\#\($q" type="math\_number"&gt;

&lt;field name="NUM"&gt;10&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block id="uK\`b+7Q\#:\(\[m4i\|@\*Ql1" type="variables\_set"&gt;

&lt;field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType=""&gt;i&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block id="\`^\_Pi3Bk6\(YOwQ/x{mB3" type="math\_arithmetic"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow id="lF-E:Vkx\`gmL~WjGna@q" type="math\_number"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="4JgF^FH5Zqf^p90JH!V5" type="variables\_get"&gt;

&lt;field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow id="LJbWWj\`{{hTi1?^=Ri6O" type="math\_number"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="}6.TtVZ%{3\|J7%F:G,uz" type="math\_number"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block id="F\*U3fOb8c8$\`mdsDmdXO" type="variables\_set"&gt;

&lt;field id="?nXqe6?Lb\*oD@;n-Fe?l" name="VAR" variableType=""&gt;s&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block id="FfgQDBWz4-5.GP.=+bmE" type="math\_arithmetic"&gt;

&lt;field name="OP"&gt;ADD&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow id="?eGpd5\`1M4l@~BiX.rJ0" type="math\_number"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="-EM=zOZaAlxrlh4F\#Anx" type="variables\_get"&gt;

&lt;field id="?nXqe6?Lb\*oD@;n-Fe?l" name="VAR" variableType=""&gt;s&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow id="Up;ku@sU4/Ui!R57a0Mg" type="math\_number"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="5Hgfa;\*d{$8@hl-{nD\[p" type="math\_arithmetic"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow id="d8\_wKl;VgCA\|zas-\]Bi." type="math\_number"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="o/MM0sTY\|\*3^gs=vSq%G" type="variables\_get"&gt;

&lt;field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow id="7;hH%E9Yt~9I\_/XM;EM@" type="math\_number"&gt;

&lt;field name="NUM"&gt;2&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="Z@\)\)\|oloQ\`Fse7=rQyz\`" type="math\_number"&gt;

&lt;field name="NUM"&gt;2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;next&gt;

&lt;block id="x^~4^kPWmg\*~gGJyk?zu" type="controls\_flow\_statements"&gt;

&lt;field name="FLOW"&gt;CONTINUE&lt;/field&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;next&gt;

&lt;block id="3d,}6h\`WJ\(ei{e4g\|nf%" type="text\_print"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow id="\]idn,0B$;e/jedtCC@l/" type="text"&gt;

&lt;field name="TEXT"&gt;abc&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="d\*,Riv,{dJY${z\_K\_WTd" type="variables\_get"&gt;

&lt;field id="?nXqe6?Lb\*oD@;n-Fe?l" name="VAR" variableType=""&gt;s&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;block id=",z3J;$\_aF\*?+^F},gDRt" type="variables\_get" x="812" y="437"&gt;

&lt;field id="7-j8N.I0MDV0ObZn;GSv" name="VAR" variableType=""&gt;i&lt;/field&gt;

&lt;/block&gt;

&lt;/xml&gt;

 C

