
Hands-on Lab: Working with Networking Commands
```
theia@theia-u11203041:/home/project$ hostname
theia-u11203041
theia@theia-u11203041:/home/project$ hostname -i
172.22.187.145
theia@theia-u11203041:/home/project$ ifconfig
eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1480
        inet 172.22.187.145  netmask 255.255.255.255  broadcast 0.0.0.0
        inet6 fe80::30ad:b0ff:fef0:2652  prefixlen 64  scopeid 0x20<link>
        ether 32:ad:b0:f0:26:52  txqueuelen 0  (Ethernet)
        RX packets 124196  bytes 514239207 (514.2 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 93966  bytes 52663831 (52.6 MB)
        TX errors 0  dropped 1 overruns 0  carrier 0  collisions 0

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 198339  bytes 135486394 (135.4 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 198339  bytes 135486394 (135.4 MB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

theia@theia-u11203041:/home/project$ ping www.google.com
PING www.google.com (142.251.167.106): 56 data bytes
64 bytes from 142.251.167.106: icmp_seq=0 ttl=105 time=1.715 ms
64 bytes from 142.251.167.106: icmp_seq=1 ttl=105 time=1.856 ms
64 bytes from 142.251.167.106: icmp_seq=2 ttl=105 time=1.815 ms
64 bytes from 142.251.167.106: icmp_seq=3 ttl=105 time=1.833 ms
64 bytes from 142.251.167.106: icmp_seq=4 ttl=105 time=1.921 ms
64 bytes from 142.251.167.106: icmp_seq=5 ttl=105 time=1.706 ms
64 bytes from 142.251.167.106: icmp_seq=6 ttl=105 time=1.811 ms
64 bytes from 142.251.167.106: icmp_seq=7 ttl=105 time=1.822 ms
64 bytes from 142.251.167.106: icmp_seq=8 ttl=105 time=1.726 ms
64 bytes from 142.251.167.106: icmp_seq=9 ttl=105 time=1.820 ms
64 bytes from 142.251.167.106: icmp_seq=10 ttl=105 time=1.750 ms
64 bytes from 142.251.167.106: icmp_seq=11 ttl=105 time=1.876 ms
64 bytes from 142.251.167.106: icmp_seq=12 ttl=105 time=1.765 ms
64 bytes from 142.251.167.106: icmp_seq=13 ttl=105 time=1.774 ms
64 bytes from 142.251.167.106: icmp_seq=14 ttl=105 time=1.732 ms
64 bytes from 142.251.167.106: icmp_seq=15 ttl=105 time=1.705 ms
C64 bytes from 142.251.167.106: icmp_seq=16 ttl=105 time=1.763 ms
64 bytes from 142.251.167.106: icmp_seq=17 ttl=105 time=1.751 ms
64 bytes from 142.251.167.106: icmp_seq=18 ttl=105 time=1.670 ms
^C--- www.google.com ping statistics ---
20 packets transmitted, 19 packets received, 5% packet loss
round-trip min/avg/max/stddev = 1.670/1.780/1.921/0.064 ms
theia@theia-u11203041:/home/project$ ping -c 5 www.google.com
PING www.google.com (172.253.63.106): 56 data bytes
64 bytes from 172.253.63.106: icmp_seq=0 ttl=105 time=1.483 ms
64 bytes from 172.253.63.106: icmp_seq=1 ttl=105 time=1.481 ms
64 bytes from 172.253.63.106: icmp_seq=2 ttl=105 time=1.475 ms
64 bytes from 172.253.63.106: icmp_seq=3 ttl=105 time=1.488 ms
64 bytes from 172.253.63.106: icmp_seq=4 ttl=105 time=1.507 ms
--- www.google.com ping statistics ---
5 packets transmitted, 5 packets received, 0% packet loss
round-trip min/avg/max/stddev = 1.475/1.487/1.507/0.000 ms
theia@theia-u11203041:/home/project$ curl https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0250EN-SkillsNetwork/labs/Bash%20Scripting/usdoi.txt
The unanimous Declaration of the thirteen united States of America, When in the
Course of human events, it becomes necessary for one people to dissolve the
political bands which have connected them with another, and to assume among the
powers of the earth, the separate and equal station to which the Laws of Nature
and of Nature's God entitle them, a decent respect to the opinions of mankind
requires that they should declare the causes which impel them to the
separation.

We hold these truths to be self-evident, that all men are created equal, that
they are endowed by their Creator with certain unalienable Rights, that among
these are Life, Liberty and the pursuit of Happiness.--That to secure these
rights, Governments are instituted among Men, deriving their just powers from
the consent of the governed, --That whenever any Form of Government becomes
destructive of these ends, it is the Right of the People to alter or to abolish
it, and to institute new Government, laying its foundation on such principles
and organizing its powers in such form, as to them shall seem most likely to
effect their Safety and Happiness. Prudence, indeed, will dictate that
Governments long established should not be changed for light and transient
causes; and accordingly all experience hath shewn, that mankind are more
disposed to suffer, while evils are sufferable, than to right themselves by
abolishing the forms to which they are accustomed. But when a long train of
abuses and usurpations, pursuing invariably the same Object evinces a design to
reduce them under absolute Despotism, it is their right, it is their duty, to
throw off such Government, and to provide new Guards for their future
security.--Such has been the patient sufferance of these Colonies; and such is
now the necessity which constrains them to alter their former Systems of
Government. The history of the present King of Great Britain is a history of
repeated injuries and usurpations, all having in direct object the
establishment of an absolute Tyranny over these States. To prove this, let
Facts be submitted to a candid world.

He has refused his Assent to Laws, the most wholesome and necessary for the
public good.

He has forbidden his Governors to pass Laws of immediate and pressing
importance, unless suspended in their operation till his Assent should be
obtained; and when so suspended, he has utterly neglected to attend to them.

He has refused to pass other Laws for the accommodation of large districts of
people, unless those people would relinquish the right of Representation in the
Legislature, a right inestimable to them and formidable to tyrants only.

He has called together legislative bodies at places unusual, uncomfortable, and
distant from the depository of their public Records, for the sole purpose of
fatiguing them into compliance with his measures.

He has dissolved Representative Houses repeatedly, for opposing with manly
firmness his invasions on the rights of the people.

He has refused for a long time, after such dissolutions, to cause others to be
elected; whereby the Legislative powers, incapable of Annihilation, have
returned to the People at large for their exercise; the State remaining in the
mean time exposed to all the dangers of invasion from without, and convulsions
within.

He has endeavoured to prevent the population of these States; for that purpose
obstructing the Laws for Naturalization of Foreigners; refusing to pass others
to encourage their migrations hither, and raising the conditions of new
Appropriations of Lands.

He has obstructed the Administration of Justice, by refusing his Assent to Laws
for establishing Judiciary powers.

He has made Judges dependent on his Will alone, for the tenure of their
offices, and the amount and payment of their salaries.

He has erected a multitude of New Offices, and sent hither swarms of Officers
to harrass our people, and eat out their substance.

He has kept among us, in times of peace, Standing Armies without the Consent of
our legislatures.

He has affected to render the Military independent of and superior to the Civil
power.

He has combined with others to subject us to a jurisdiction foreign to our
constitution, and unacknowledged by our laws; giving his Assent to their Acts
of pretended Legislation:

For Quartering large bodies of armed troops among us:

For protecting them, by a mock Trial, from punishment for any Murders which
they should commit on the Inhabitants of these States:

For cutting off our Trade with all parts of the world:

For imposing Taxes on us without our Consent:

For depriving us in many cases, of the benefits of Trial by Jury:

For transporting us beyond Seas to be tried for pretended offences

For abolishing the free System of English Laws in a neighbouring Province,
establishing therein an Arbitrary government, and enlarging its Boundaries so
as to render it at once an example and fit instrument for introducing the same
absolute rule into these Colonies:

For taking away our Charters, abolishing our most valuable Laws, and altering
fundamentally the Forms of our Governments:

For suspending our own Legislatures, and declaring themselves invested with
power to legislate for us in all cases whatsoever.

He has abdicated Government here, by declaring us out of his Protection and
waging War against us.

He has plundered our seas, ravaged our Coasts, burnt our towns, and destroyed
the lives of our people.

He is at this time transporting large Armies of foreign Mercenaries to compleat
the works of death, desolation and tyranny, already begun with circumstances of
Cruelty & perfidy scarcely paralleled in the most barbarous ages, and totally
unworthy the Head of a civilized nation.

He has constrained our fellow Citizens taken Captive on the high Seas to bear
Arms against their Country, to become the executioners of their friends and
Brethren, or to fall themselves by their Hands.

He has excited domestic insurrections amongst us, and has endeavoured to bring
on the inhabitants of our frontiers, the merciless Indian Savages, whose known
rule of warfare, is an undistinguished destruction of all ages, sexes and
conditions.

In every stage of these Oppressions We have Petitioned for Redress in the most
humble terms: Our repeated Petitions have been answered only by repeated
injury. A Prince whose character is thus marked by every act which may define a
Tyrant, is unfit to be the ruler of a free people.

Nor have We been wanting in attentions to our Brittish brethren. We have warned
them from time to time of attempts by their legislature to extend an
unwarrantable jurisdiction over us. We have reminded them of the circumstances
of our emigration and settlement here. We have appealed to their native justice
and magnanimity, and we have conjured them by the ties of our common kindred to
disavow these usurpations, which, would inevitably interrupt our connections
and correspondence. They too have been deaf to the voice of justice and of
consanguinity. We must, therefore, acquiesce in the necessity, which denounces
our Separation, and hold them, as we hold the rest of mankind, Enemies in War,
in Peace Friends.

We, therefore, the Representatives of the united States of America, in General
Congress, Assembled, appealing to the Supreme Judge of the world for the
rectitude of our intentions, do, in the Name, and by Authority of the good
People of these Colonies, solemnly publish and declare, That these United
Colonies are, and of Right ought to be Free and Independent States; that they
are Absolved from all Allegiance to the British Crown, and that all political
connection between them and the State of Great Britain, is and ought to be
totally dissolved; and that as Free and Independent States, they have full
Power to levy War, conclude Peace, contract Alliances, establish Commerce, and
to do all other Acts and Things which Independent States may of right do. And
for the support of this Declaration, with a firm reliance on the protection of
divine Providence, we mutually pledge to each other our Lives, our Fortunes and
our sacred Honor.
theia@theia-u11203041:/home/project$ curl -O https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0250EN-SkillsNetwork/labs/Bash%20Scripting/usdoi.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  8121  100  8121    0     0  78086      0 --:--:-- --:--:-- --:--:-- 78086
theia@theia-u11203041:/home/project$ rm usdoi.txt
theia@theia-u11203041:/home/project$ wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0250EN-SkillsNetwork/labs/Bash%20Scripting/usdoi.txt
--2023-09-16 08:24:47--  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0250EN-SkillsNetwork/labs/Bash%20Scripting/usdoi.txt
Resolving cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud (cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud)... 169.63.118.104
Connecting to cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud (cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud)|169.63.118.104|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 8121 (7.9K) [text/plain]
Saving to: ‘usdoi.txt’

usdoi.txt               100%[==============================>]   7.93K  --.-KB/s    in 0s      

2023-09-16 08:24:48 (759 MB/s) - ‘usdoi.txt’ saved [8121/8121]

theia@theia-u11203041:/home/project$ 
```
PRACTICE EXERCISE
```
theia@theia-u11203041:/home/project$ cd /home/project
theia@theia-u11203041:/home/project$ pwd
/home/project
theia@theia-u11203041:/home/project$ hostname -i
172.22.187.145
theia@theia-u11203041:/home/project$ ping www.google.com
PING www.google.com (172.253.122.104): 56 data bytes
64 bytes from 172.253.122.104: icmp_seq=0 ttl=108 time=2.068 ms
64 bytes from 172.253.122.104: icmp_seq=1 ttl=108 time=1.893 ms
64 bytes from 172.253.122.104: icmp_seq=2 ttl=108 time=1.989 ms
64 bytes from 172.253.122.104: icmp_seq=3 ttl=108 time=1.944 ms
64 bytes from 172.253.122.104: icmp_seq=4 ttl=108 time=1.928 ms
64 bytes from 172.253.122.104: icmp_seq=5 ttl=108 time=2.001 ms
64 bytes from 172.253.122.104: icmp_seq=6 ttl=108 time=1.886 ms
64 bytes from 172.253.122.104: icmp_seq=7 ttl=108 time=1.886 ms
64 bytes from 172.253.122.104: icmp_seq=8 ttl=108 time=2.034 ms
64 bytes from 172.253.122.104: icmp_seq=9 ttl=108 time=1.938 ms
64 bytes from 172.253.122.104: icmp_seq=10 ttl=108 time=1.952 ms
64 bytes from 172.253.122.104: icmp_seq=11 ttl=108 time=1.889 ms
^C--- www.google.com ping statistics ---
12 packets transmitted, 12 packets received, 0% packet loss
round-trip min/avg/max/stddev = 1.886/1.951/2.068/0.058 ms
theia@theia-u11203041:/home/project$ igconfig etho
bash: igconfig: command not found
theia@theia-u11203041:/home/project$ igconfig eth0
bash: igconfig: command not found
theia@theia-u11203041:/home/project$ ifconfig eth0
eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1480
        inet 172.22.187.145  netmask 255.255.255.255  broadcast 0.0.0.0
        inet6 fe80::30ad:b0ff:fef0:2652  prefixlen 64  scopeid 0x20<link>
        ether 32:ad:b0:f0:26:52  txqueuelen 0  (Ethernet)
        RX packets 126928  bytes 514829736 (514.8 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 96407  bytes 53201782 (53.2 MB)
        TX errors 0  dropped 1 overruns 0  carrier 0  collisions 0

theia@theia-u11203041:/home/project$ curl www.google.com
<!doctype html><html itemscope="" itemtype="http://schema.org/WebPage" lang="en"><head><meta content="Search the world's information, including webpages, images, videos and more. Google has many special features to help you find exactly what you're looking for." name="description"><meta content="noodp" name="robots"><meta content="text/html; charset=UTF-8" http-equiv="Content-Type"><meta content="/images/branding/googleg/1x/googleg_standard_color_128dp.png" itemprop="image"><title>Google</title><script nonce="9gugpljIIs1qpbHoIacnZQ">(function(){var _g={kEI:'RJ8FZcS_HIPl5NoP-bWt0Ac',kEXPI:'0,1365468,206,4804,2316,383,246,5,1129120,1197754,380737,16114,28684,22430,1362,12313,2821,14765,4998,50699,7692,2891,3926,213,7615,606,29842,46172,781,1244,1,16916,2652,4,32894,13065,11442,2216,2980,1457,22604,6633,7596,1,42154,2,16395,342,23024,6699,31122,4569,6258,23418,1252,33064,2,2,1,23827,799,10161,23351,873,9625,10008,9,1920,9779,36285,6174,3142,17057,20136,14,82,13247,1,3266,3692,109,363,2049,5856,3785,15203,5375,2266,764,11151,4665,1804,7734,18098,7265,530,1641,961,4289,6564,1635,2171,6668,4654,1493,11712,7915,12742,3,9,5400,3592,5210139,2,195,5993561,1305,2803118,3311,141,795,19735,1,1,346,8474,96,55,7,126,14,12,111,95,17,23941477,4060780,36925,2358,4491,799,270,1395096,392638,23366632,8163,4636,8409,2879,1594,3530,24,5494,935,243,496,1196,274,4246,2067,1703,2688,803,1521,1,473,2447,1,2372,1,1,2,3,2814,166,241,486,1255,1293,254,1090,1987,111,653,3346,554,685,1,574,65,3235,295,626,3,82,830,2,1283,1,924,963,3475,469,430,198,687,778,102,710,712,277,153,759,461,380,2348,96,100,240,465,770,2,343,727,1755,3,415,1,2,2270,998,786,90,233,1189,314,199,9,618,1109,738,8,63,65,6,2,1121,2,281,284,153,571,4,528,561,834,174,20,874,3,599,1,1,2,3,390,2,186,1110,666,300,481,48,1115,416,591,3,154,1301,368,1,1768,170,318,196,4,415,275,35,143,3,719,7,1,8,1227,126,557,4,9,220,464,561,678,32,28,10,2,19,3,616,1,352,915,158,441,2,7,1',kBL:'Xgo_',kOPI:89978449};(function(){var a;(null==(a=window.google)?0:a.stvsc)?google.kEI=_g.kEI:window.google=_g;}).call(this);})();(function(){google.sn='webhp';google.kHL='en';})();(function(){
var h=this||self;function l(){return void 0!==window.google&&void 0!==window.google.kOPI&&0!==window.google.kOPI?window.google.kOPI:null};var m,n=[];function p(a){for(var b;a&&(!a.getAttribute||!(b=a.getAttribute("eid")));)a=a.parentNode;return b||m}function q(a){for(var b=null;a&&(!a.getAttribute||!(b=a.getAttribute("leid")));)a=a.parentNode;return b}function r(a){/^http:/i.test(a)&&"https:"===window.location.protocol&&(google.ml&&google.ml(Error("a"),!1,{src:a,glmm:1}),a="");return a}
function t(a,b,c,d,k){var e="";-1===b.search("&ei=")&&(e="&ei="+p(d),-1===b.search("&lei=")&&(d=q(d))&&(e+="&lei="+d));d="";var g=-1===b.search("&cshid=")&&"slh"!==a,f=[];f.push(["zx",Date.now().toString()]);h._cshid&&g&&f.push(["cshid",h._cshid]);c=c();null!=c&&f.push(["opi",c.toString()]);for(c=0;c<f.length;c++){if(0===c||0<c)d+="&";d+=f[c][0]+"="+f[c][1]}return"/"+(k||"gen_204")+"?atyp=i&ct="+String(a)+"&cad="+(b+e+d)};m=google.kEI;google.getEI=p;google.getLEI=q;google.ml=function(){return null};google.log=function(a,b,c,d,k,e){e=void 0===e?l:e;c||(c=t(a,b,e,d,k));if(c=r(c)){a=new Image;var g=n.length;n[g]=a;a.onerror=a.onload=a.onabort=function(){delete n[g]};a.src=c}};google.logUrl=function(a,b){b=void 0===b?l:b;return t("",a,b)};}).call(this);(function(){google.y={};google.sy=[];google.x=function(a,b){if(a)var c=a.id;else{do c=Math.random();while(google.y[c])}google.y[c]=[a,b];return!1};google.sx=function(a){google.sy.push(a)};google.lm=[];google.plm=function(a){google.lm.push.apply(google.lm,a)};google.lq=[];google.load=function(a,b,c){google.lq.push([[a],b,c])};google.loadAll=function(a,b){google.lq.push([a,b])};google.bx=!1;google.lx=function(){};var d=[];google.fce=function(a,b,c,e){d.push([a,b,c,e])};google.qce=d;}).call(this);google.f={};(function(){
document.documentElement.addEventListener("submit",function(b){var a;if(a=b.target){var c=a.getAttribute("data-submitfalse");a="1"===c||"q"===c&&!a.elements.q.value?!0:!1}else a=!1;a&&(b.preventDefault(),b.stopPropagation())},!0);document.documentElement.addEventListener("click",function(b){var a;a:{for(a=b.target;a&&a!==document.documentElement;a=a.parentElement)if("A"===a.tagName){a="1"===a.getAttribute("data-nohref");break a}a=!1}a&&b.preventDefault()},!0);}).call(this);</script><style>#gbar,#guser{font-size:13px;padding-top:1px !important;}#gbar{height:22px}#guser{padding-bottom:7px !important;text-align:right}.gbh,.gbd{border-top:1px solid #c9d7f1;font-size:1px}.gbh{height:0;position:absolute;top:24px;width:100%}@media all{.gb1{height:22px;margin-right:.5em;vertical-align:top}#gbar{float:left}}a.gb1,a.gb4{text-decoration:underline !important}a.gb1,a.gb4{color:#00c !important}.gbi .gb4{color:#dd8e27 !important}.gbf .gb4{color:#900 !important}
</style><style>body,td,a,p,.h{font-family:arial,sans-serif}body{margin:0;overflow-y:scroll}#gog{padding:3px 8px 0}td{line-height:.8em}.gac_m td{line-height:17px}form{margin-bottom:20px}.h{color:#1967d2}em{font-weight:bold;font-style:normal}.lst{height:25px;width:496px}.gsfi,.lst{font:18px arial,sans-serif}.gsfs{font:17px arial,sans-serif}.ds{display:inline-box;display:inline-block;margin:3px 0 4px;margin-left:4px}input{font-family:inherit}body{background:#fff;color:#000}a{color:#681da8;text-decoration:none}a:hover,a:active{text-decoration:underline}.fl a{color:#1967d2}a:visited{color:#681da8}.sblc{padding-top:5px}.sblc a{display:block;margin:2px 0;margin-left:13px;font-size:11px}.lsbb{background:#f8f9fa;border:solid 1px;border-color:#dadce0 #70757a #70757a #dadce0;height:30px}.lsbb{display:block}#WqQANb a{display:inline-block;margin:0 12px}.lsb{background:url(/images/nav_logo229.png) 0 -261px repeat-x;color:#000;border:none;cursor:pointer;height:30px;margin:0;outline:0;font:15px arial,sans-serif;vertical-align:top}.lsb:active{background:#dadce0}.lst:focus{outline:none}</style><script nonce="9gugpljIIs1qpbHoIacnZQ">(function(){window.google.erd={jsr:1,bv:1867,de:true};
var h=this||self;var k,l=null!=(k=h.mei)?k:1,n,p=null!=(n=h.sdo)?n:!0,q=0,r,t=google.erd,v=t.jsr;google.ml=function(a,b,d,m,e){e=void 0===e?2:e;b&&(r=a&&a.message);void 0===d&&(d={});d.cad="ple_"+google.ple+".aple_"+google.aple;if(google.dl)return google.dl(a,e,d),null;if(0>v){window.console&&console.error(a,d);if(-2===v)throw a;b=!1}else b=!a||!a.message||"Error loading script"===a.message||q>=l&&!m?!1:!0;if(!b)return null;q++;d=d||{};b=encodeURIComponent;var c="/gen_204?atyp=i&ei="+b(google.kEI);google.kEXPI&&(c+="&jexpid="+b(google.kEXPI));c+="&srcpg="+b(google.sn)+"&jsr="+b(t.jsr)+"&bver="+
b(t.bv);var f=a.lineNumber;void 0!==f&&(c+="&line="+f);var g=a.fileName;g&&(0<g.indexOf("-extension:/")&&(e=3),c+="&script="+b(g),f&&g===window.location.href&&(f=document.documentElement.outerHTML.split("\n")[f],c+="&cad="+b(f?f.substring(0,300):"No script found.")));google.ple&&1===google.ple&&(e=2);c+="&jsel="+e;for(var u in d)c+="&",c+=b(u),c+="=",c+=b(d[u]);c=c+"&emsg="+b(a.name+": "+a.message);c=c+"&jsst="+b(a.stack||"N/A");12288<=c.length&&(c=c.substr(0,12288));a=c;m||google.log(0,"",a);return a};window.onerror=function(a,b,d,m,e){r!==a&&(a=e instanceof Error?e:Error(a),void 0===d||"lineNumber"in a||(a.lineNumber=d),void 0===b||"fileName"in a||(a.fileName=b),google.ml(a,!1,void 0,!1,"SyntaxError"===a.name||"SyntaxError"===a.message.substring(0,11)||-1!==a.message.indexOf("Script error")?3:0));r=null;p&&q>=l&&(window.onerror=null)};})();</script></head><body bgcolor="#fff"><script nonce="9gugpljIIs1qpbHoIacnZQ">(function(){var src='/images/nav_logo229.png';var iesg=false;document.body.onload = function(){window.n && window.n();if (document.images){new Image().src=src;}
if (!iesg){document.f&&document.f.q.focus();document.gbqf&&document.gbqf.q.focus();}
}
})();</script><div id="mngb"><div id=gbar><nobr><b class=gb1>Search</b> <a class=gb1 href="https://www.google.com/imghp?hl=en&tab=wi">Images</a> <a class=gb1 href="http://maps.google.com/maps?hl=en&tab=wl">Maps</a> <a class=gb1 href="https://play.google.com/?hl=en&tab=w8">Play</a> <a class=gb1 href="https://www.youtube.com/?tab=w1">YouTube</a> <a class=gb1 href="https://news.google.com/?tab=wn">News</a> <a class=gb1 href="https://mail.google.com/mail/?tab=wm">Gmail</a> <a class=gb1 href="https://drive.google.com/?tab=wo">Drive</a> <a class=gb1 style="text-decoration:none" href="https://www.google.com/intl/en/about/products?tab=wh"><u>More</u> &raquo;</a></nobr></div><div id=guser width=100%><nobr><span id=gbn class=gbi></span><span id=gbf class=gbf></span><span id=gbe></span><a href="http://www.google.com/history/optout?hl=en" class=gb4>Web History</a> | <a  href="/preferences?hl=en" class=gb4>Settings</a> | <a target=_top id=gb_70 href="https://accounts.google.com/ServiceLogin?hl=en&passive=true&continue=http://www.google.com/&ec=GAZAAQ" class=gb4>Sign in</a></nobr></div><div class=gbh style=left:0></div><div class=gbh style=right:0></div></div><center><br clear="all" id="lgpd"><div id="lga"><img alt="Google" height="92" src="/images/branding/googlelogo/1x/googlelogo_white_background_color_272x92dp.png" style="padding:28px 0 14px" width="272" id="hplogo"><br><br></div><form action="/search" name="f"><table cellpadding="0" cellspacing="0"><tr valign="top"><td width="25%">&nbsp;</td><td align="center" nowrap=""><input name="ie" value="ISO-8859-1" type="hidden"><input value="en" name="hl" type="hidden"><input name="source" type="hidden" value="hp"><input name="biw" type="hidden"><input name="bih" type="hidden"><div class="ds" style="height:32px;margin:4px 0"><input class="lst" style="margin:0;padding:5px 8px 0 6px;vertical-align:top;color:#000" autocomplete="off" value="" title="Google Search" maxlength="2048" name="q" size="57"></div><br style="line-height:0"><span class="ds"><span class="lsbb"><input class="lsb" value="Google Search" name="btnG" type="submit"></span></span><span class="ds"><span class="lsbb"><input class="lsb" id="tsuid_1" value="I'm Feeling Lucky" name="btnI" type="submit"><script nonce="9gugpljIIs1qpbHoIacnZQ">(function(){var id='tsuid_1';document.getElementById(id).onclick = function(){if (this.form.q.value){this.checked = 1;if (this.form.iflsig)this.form.iflsig.disabled = false;}
else top.location='/doodles/';};})();</script><input value="AO6bgOgAAAAAZQWtVCU_hmBu0kONVRCuKW5DpwFohucD" name="iflsig" type="hidden"></span></span></td><td class="fl sblc" align="left" nowrap="" width="25%"><a href="/advanced_search?hl=en&amp;authuser=0">Advanced search</a></td></tr></table><input id="gbv" name="gbv" type="hidden" value="1"><script nonce="9gugpljIIs1qpbHoIacnZQ">(function(){var a,b="1";if(document&&document.getElementById)if("undefined"!=typeof XMLHttpRequest)b="2";else if("undefined"!=typeof ActiveXObject){var c,d,e=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"];for(c=0;d=e[c++];)try{new ActiveXObject(d),b="2"}catch(h){}}a=b;if("2"==a&&-1==location.search.indexOf("&gbv=2")){var f=google.gbvu,g=document.getElementById("gbv");g&&(g.value=a);f&&window.setTimeout(function(){location.href=f},0)};}).call(this);</script></form><div id="gac_scont"></div><div style="font-size:83%;min-height:3.5em"><br></div><span id="footer"><div style="font-size:10pt"><div style="margin:19px auto;text-align:center" id="WqQANb"><a href="/intl/en/ads/">Advertising</a><a href="/services/">Business Solutions</a><a href="/intl/en/about.html">About Google</a></div></div><p style="font-size:8pt;color:#70757a">&copy; 2023 - <a href="/intl/en/policies/privacy/">Privacy</a> - <a href="/intl/en/policies/terms/">Terms</a></p></span></center><script nonce="9gugpljIIs1qpbHoIacnZQ">(function(){window.google.cdo={height:757,width:1440};(function(){var a=window.innerWidth,b=window.innerHeight;if(!a||!b){var c=window.document,d="CSS1Compat"==c.compatMode?c.documentElement:c.body;a=d.clientWidth;b=d.clientHeight}
if(a&&b&&(a!=google.cdo.width||b!=google.cdo.height)){var e=google,f=e.log,g="/client_204?&atyp=i&biw="+a+"&bih="+b+"&ei="+google.kEI,h="",k=[],l=void 0!==window.google&&void 0!==window.google.kOPI&&0!==window.google.kOPI?window.google.kOPI:null;null!=l&&k.push(["opi",l.toString()]);for(var m=0;m<k.length;m++){if(0===m||0<m)h+="&";h+=k[m][0]+"="+k[m][1]}f.call(e,"","",g+h)};}).call(this);})();</script> <script nonce="9gugpljIIs1qpbHoIacnZQ">(function(){google.xjs={ck:'xjs.hp.rfdyOQKi4t4.L.X.O',cs:'ACT90oHY9rzqK74mkKR3jSBIkMyMlCxnzA',cssopt:false,csss:'ACT90oHzxJK90f8tJCCqy--apgkgSA5IkQ',excm:[],sepcss:false};})();</script>     <script nonce="9gugpljIIs1qpbHoIacnZQ">(function(){var u='/xjs/_/js/k\x3dxjs.hp.en.P06Lfb3mjYc.O/am\x3dAAAAAAAAAAAAAAAgAAAAAAAUABAQAAAAAAAAkAAAdAQAwAIAXA/d\x3d1/ed\x3d1/rs\x3dACT90oGb8p3jLv5jmZImEPsC7xFDtL5ofg/m\x3dsb_he,d,cEt90b,SNUn3,qddgKe,sTsDMc,dtl0hd,eHDfl';var amd=0;
var e=this||self,f=function(a){return a};var g;var h=function(a){this.g=a};h.prototype.toString=function(){return this.g+""};var k={};var l=function(){var a=document;var b="SCRIPT";"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)};
function m(a,b){a.src=b instanceof h&&b.constructor===h?b.g:"type_error:TrustedResourceUrl";var c,d;(c=(b=null==(d=(c=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:d.call(c,"script[nonce]"))?b.nonce||b.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)};function n(a){a=null===a?"null":void 0===a?"undefined":a;if(void 0===g){var b=null;var c=e.trustedTypes;if(c&&c.createPolicy){try{b=c.createPolicy("goog#html",{createHTML:f,createScript:f,createScriptURL:f})}catch(d){e.console&&e.console.error(d.message)}g=b}else g=b}a=(b=g)?b.createScriptURL(a):a;return new h(a,k)};void 0===google.ps&&(google.ps=[]);function p(){var a=u,b=function(){};google.lx=google.stvsc?b:function(){q(a);google.lx=b};google.bx||google.lx()}function r(a,b){b&&m(a,n(b));var c=a.onload;a.onload=function(d){c&&c(d);google.ps=google.ps.filter(function(t){return a!==t})};google.ps.push(a);document.body.appendChild(a)}google.as=r;function q(a){google.timers&&google.timers.load&&google.tick&&google.tick("load","xjsls");var b=l();b.onerror=function(){google.ple=1};b.onload=function(){google.ple=0};google.xjsus=void 0;r(b,a);google.aple=-1;google.psa=!0};google.xjsu=u;e._F_jsUrl=u;setTimeout(function(){0<amd?google.caft(function(){return p()},amd):p()},0);})();window._ = window._ || {};window._DumpException = _._DumpException = function(e){throw e;};window._s = window._s || {};_s._DumpException = _._DumpException;window._qs = window._qs || {};_qs._DumpException = _._DumpException;(function(){window._F_toggles=[1,0,0,8,1310721,16448,0,9216,1140,24117259];})();function _F_installCss(c){}
(function(){google.jl={blt:'none',chnk:0,dw:false,dwu:true,emtn:0,end:0,ico:false,ikb:0,ine:false,injs:'none',injt:0,injth:0,injv2:false,lls:'default',pdt:0,rep:0,snet:true,strt:0,ubm:false,uwp:true};})();(function(){var pmc='{\x22d\x22:{},\x22sb_he\x22:{\x22agen\x22:true,\x22cgen\x22:true,\x22client\x22:\x22heirloom-hp\x22,\x22dh\x22:true,\x22ds\x22:\x22\x22,\x22fl\x22:true,\x22host\x22:\x22google.com\x22,\x22jsonp\x22:true,\x22msgs\x22:{\x22cibl\x22:\x22Clear Search\x22,\x22dym\x22:\x22Did you mean:\x22,\x22lcky\x22:\x22I\\u0026#39;m Feeling Lucky\x22,\x22lml\x22:\x22Learn more\x22,\x22psrc\x22:\x22This search was removed from your \\u003Ca href\x3d\\\x22/history\\\x22\\u003EWeb History\\u003C/a\\u003E\x22,\x22psrl\x22:\x22Remove\x22,\x22sbit\x22:\x22Search by image\x22,\x22srch\x22:\x22Google Search\x22},\x22ovr\x22:{},\x22pq\x22:\x22\x22,\x22rfs\x22:[],\x22sbas\x22:\x220 3px 8px 0 rgba(0,0,0,0.2),0 0 0 1px rgba(0,0,0,0.08)\x22,\x22stok\x22:\x22qYvkPD69WVVMyJuvpNInt2S6YeY\x22}}';google.pmc=JSON.parse(pmc);})();(function(){var b=function(a){var c=0;return function(){return c<a.length?{done:!1,value:a[c++]}:{done:!0}}};
var e=this||self;var g,h;a:{for(var k=["CLOSURE_FLAGS"],l=e,n=0;n<k.length;n++)if(l=l[k[n]],null==l){h=null;break a}h=l}var p=h&&h[610401301];g=null!=p?p:!1;var q,r=e.navigator;q=r?r.userAgentData||null:null;function t(a){return g?q?q.brands.some(function(c){return(c=c.brand)&&-1!=c.indexOf(a)}):!1:!1}function u(a){var c;a:{if(c=e.navigator)if(c=c.userAgent)break a;c=""}return-1!=c.indexOf(a)};function v(){return g?!!q&&0<q.brands.length:!1}function w(){return u("Safari")&&!(x()||(v()?0:u("Coast"))||(v()?0:u("Opera"))||(v()?0:u("Edge"))||(v()?t("Microsoft Edge"):u("Edg/"))||(v()?t("Opera"):u("OPR"))||u("Firefox")||u("FxiOS")||u("Silk")||u("Android"))}function x(){return v()?t("Chromium"):(u("Chrome")||u("CriOS"))&&!(v()?0:u("Edge"))||u("Silk")}function y(){return u("Android")&&!(x()||u("Firefox")||u("FxiOS")||(v()?0:u("Opera"))||u("Silk"))};var z=v()?!1:u("Trident")||u("MSIE");y();x();w();var A=!z&&!w(),D=function(a){if(/-[a-z]/.test("ved"))return null;if(A&&a.dataset){if(y()&&!("ved"in a.dataset))return null;a=a.dataset.ved;return void 0===a?null:a}return a.getAttribute("data-"+"ved".replace(/([A-Z])/g,"-$1").toLowerCase())};var E=[],F=null;function G(a){a=a.target;var c=performance.now(),f=[],H=f.concat,d=E;if(!(d instanceof Array)){var m="undefined"!=typeof Symbol&&Symbol.iterator&&d[Symbol.iterator];if(m)d=m.call(d);else if("number"==typeof d.length)d={next:b(d)};else throw Error("a`"+String(d));for(var B=[];!(m=d.next()).done;)B.push(m.value);d=B}E=H.call(f,d,[c]);if(a&&a instanceof HTMLElement)if(a===F){if(c=4<=E.length)c=5>(E[E.length-1]-E[E.length-4])/1E3;if(c){c=google.getEI(a);a.hasAttribute("data-ved")?f=a?D(a)||"":"":f=(f=
a.closest("[data-ved]"))?D(f)||"":"";f=f||"";if(a.hasAttribute("jsname"))a=a.getAttribute("jsname");else{var C;a=null==(C=a.closest("[jsname]"))?void 0:C.getAttribute("jsname")}google.log("rcm","&ei="+c+"&ved="+f+"&jsname="+(a||""))}}else F=a,E=[c]}window.document.addEventListener("DOMContentLoaded",function(){document.body.addEventListener("click",G)});}).call(this);</script></body></html>theia@theia-u11203041:/home/project$ wget www.google.com
--2023-09-16 08:28:18--  http://www.google.com/
Resolving www.google.com (www.google.com)... 142.251.111.106, 142.251.111.147, 142.251.111.99, ...
Connecting to www.google.com (www.google.com)|142.251.111.106|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘index.html’

index.html                  [ <=>                           ]  17.59K  --.-KB/s    in 0.001s  

2023-09-16 08:28:18 (32.5 MB/s) - ‘index.html’ saved [18010]

theia@theia-u11203041:/home/project$ ls -l
total 52
-rw-r--r-- 1 theia users 18010 Sep 16 08:28 index.html
-rw-r--r-- 1 theia users    42 May 15 14:56 names_and_numbers.csv
drwxr-sr-x 2 theia users  4096 Sep 16 04:37 scripts
dr-xr-sr-x 3 theia users  4096 Sep 16 05:16 test
dr-xr-sr-x 2 theia users  4096 Sep 16 05:22 tmp_dir
-rw-r--r-- 1 theia users  8121 Sep 21  2022 usdoi.txt
-rw-r--r-- 1 theia users    20 Sep 28  2022 zoo_ages.txt
-rw-r--r-- 1 theia users    54 Sep 28  2022 zoo.txt
theia@theia-u11203041:/home/project$ 


```