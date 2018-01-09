![](/assets/25272109E52C2474672F8627CCB678BE.jpg)

&lt;xml xmlns="http://www.w3.org/1999/xhtml"&gt;

&lt;variables&gt;

&lt;variable id="R\`FO\_3Zbb+-hAOqsD^qj" type=""&gt;i&lt;/variable&gt;

&lt;variable id="ns4X9UZ\_k\#\*x9:KGY;zf" type=""&gt;f&lt;/variable&gt;

&lt;variable id="--N4\(IWV$2t=DlxG^3Sl" type=""&gt;f1&lt;/variable&gt;

&lt;variable id=",9\#=Ah+@Y$0Rt3tym$xv" type=""&gt;f2&lt;/variable&gt;

&lt;variable id="Jp}ZI?ek8m\_\|xT$\`TVmy" type=""&gt;f3&lt;/variable&gt;

&lt;variable id="oCCm@\*b$3ae=EzC:@\[85" type=""&gt;f4&lt;/variable&gt;

&lt;variable id="xWD2Z3L6Uc{G,{J32o%\)" type=""&gt;f5&lt;/variable&gt;

&lt;variable id="=rYAc\*P+uaZtKR\)l4!xS" type=""&gt;x&lt;/variable&gt;

&lt;variable id="N^Gc5uT5y%wi9y:kNx\_6" type=""&gt;x1&lt;/variable&gt;

&lt;variable id="^,zs\`,xaV5\(f0V\`\]k6\]r" type=""&gt;x2&lt;/variable&gt;

&lt;variable id="-MhKM\)v\|I\(E3\#Y~cy8p%" type=""&gt;x3&lt;/variable&gt;

&lt;variable id="sV0iq=^m.\`;F7ezIgYlK" type=""&gt;x4&lt;/variable&gt;

&lt;variable id="V640\)ogG2AyEG7DxAVO@" type=""&gt;x5&lt;/variable&gt;

&lt;variable id="VcrptFR41Kdfcs\#9DuS$" type=""&gt;j&lt;/variable&gt;

&lt;variable id="h\)L0tc\*Jo6TB5dzdyQHr" type=""&gt;k&lt;/variable&gt;

&lt;variable id="\#\#CN=79,bR55;M?r9$,Z" type=""&gt;m&lt;/variable&gt;

&lt;variable id="qMZXX\)E\]gbI\(3dJz2%pp" type=""&gt;{listVariable}&lt;/variable&gt;

&lt;variable id="fXJ1316\(CyK$KRhb{9\_b" type=""&gt;汇率&lt;/variable&gt;

&lt;variable id="oLMQ9Z\`V.\[=5QB\(lwv3l" type=""&gt;本币&lt;/variable&gt;

&lt;variable id="AiN7}J+GY4MPx\)\|ncsu\(" type=""&gt;外币&lt;/variable&gt;

&lt;/variables&gt;

&lt;block id="J\(ucQqe97\*i8:%RLkL\|C" type="variables\_set" x="-37" y="-187"&gt;

&lt;field id="fXJ1316\(CyK$KRhb{9\_b" name="VAR" variableType=""&gt;汇率&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block id="}Hl,F6SGNVU,A\(\_N!BA=" type="math\_number"&gt;

&lt;field name="NUM"&gt;1.2&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block id="\(6Nm/sm}acF\)j^7%+^oP" type="variables\_set"&gt;

&lt;field id="oLMQ9Z\`V.\[=5QB\(lwv3l" name="VAR" variableType=""&gt;本币&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block id="j\]4KI\)k{.Ack{18y6-}\#" type="math\_number"&gt;

&lt;field name="NUM"&gt;100&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;next&gt;

&lt;block id="\*\_{YZGJW\(+h}3IBkL^Vs" type="controls\_if"&gt;

&lt;value name="IF0"&gt;

&lt;block id="YRnu$O+tR5Mh\]E6pBk^j" type="logic\_operation"&gt;

&lt;field name="OP"&gt;AND&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block id="}JkA3@tQb\]b{40V\_x4p1" type="logic\_compare"&gt;

&lt;field name="OP"&gt;NEQ&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block id=":Jp6stTZ-RBEh:+?a}Q$" type="variables\_get"&gt;

&lt;field id="oLMQ9Z\`V.\[=5QB\(lwv3l" name="VAR" variableType=""&gt;本币&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block id="-:g\(\]WoBx\_:.O/!2V\|\|S" type="math\_number"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block id="Z\#M2Nww+\[+q=wDzjf\`z@" type="logic\_compare"&gt;

&lt;field name="OP"&gt;NEQ&lt;/field&gt;

&lt;value name="A"&gt;

&lt;block id="ZPWq58c\[%Zxn5Re;=p~Q" type="variables\_get"&gt;

&lt;field id="fXJ1316\(CyK$KRhb{9\_b" name="VAR" variableType=""&gt;汇率&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;block id="^XYMi\)\(e/}\(M=1En%n\`5" type="math\_number"&gt;

&lt;field name="NUM"&gt;0&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;statement name="DO0"&gt;

&lt;block id="4-vH!1?/fHl\|\#\`$5+VA\*" type="variables\_set"&gt;

&lt;field id="AiN7}J+GY4MPx\)\|ncsu\(" name="VAR" variableType=""&gt;外币&lt;/field&gt;

&lt;value name="VALUE"&gt;

&lt;block id="gJoZD=/%4\#Ev,pL~VX2," type="math\_arithmetic"&gt;

&lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

&lt;value name="A"&gt;

&lt;shadow id="N/-{,iox-/xa}@uYUj{w" type="math\_number"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="r\(F70ozmvMxx\[ZwH\)6G\|" type="variables\_get"&gt;

&lt;field id="oLMQ9Z\`V.\[=5QB\(lwv3l" name="VAR" variableType=""&gt;本币&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;value name="B"&gt;

&lt;shadow id="oS\#B.D6ZtSm=EiCJcPmx" type="math\_number"&gt;

&lt;field name="NUM"&gt;1&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id="P\]4t\|/.TNPTas~3$b3R/" type="variables\_get"&gt;

&lt;field id="fXJ1316\(CyK$KRhb{9\_b" name="VAR" variableType=""&gt;汇率&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/statement&gt;

&lt;next&gt;

&lt;block id="nBlj78rKy\_yQKouJ}MtZ" type="text\_print"&gt;

&lt;value name="TEXT"&gt;

&lt;shadow id="N$k\*qdD8,\*PVCOZJ!Zd;" type="text"&gt;

&lt;field name="TEXT"&gt;k&lt;/field&gt;

&lt;/shadow&gt;

&lt;block id=";\(G\_9P9y$c?O.;\_VH%\`P" type="variables\_get"&gt;

&lt;field id="AiN7}J+GY4MPx\)\|ncsu\(" name="VAR" variableType=""&gt;外币&lt;/field&gt;

&lt;/block&gt;

&lt;/value&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/next&gt;

&lt;/block&gt;

&lt;/xml&gt;

 ,.��6�Y

