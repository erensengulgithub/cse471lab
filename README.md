# cse471lab
Labwork CSE471
-------------------

- ping google.com | network test
PING google.com (142.250.184.142) 56(84) bytes of data.
64 bytes from sof02s43-in-f14.1e100.net (142.250.184.142): icmp_seq=1 ttl=115 time=26.5 ms
64 bytes from sof02s43-in-f14.1e100.net (142.250.184.142): icmp_seq=2 ttl=115 time=17.3 ms
64 bytes from sof02s43-in-f14.1e100.net (142.250.184.142): icmp_seq=3 ttl=115 time=26.5 ms
--- google.com ping statistics ---
3 packets transmitted, 3 received, 0% packet loss, time 2002ms
rtt min/avg/max/mdev = 17.380/23.492/26.574/4.321 ms

- curl www.google.com | data exchange btwn client and server/HTTP req |
<!doctype html><html itemscope="" itemtype="http://schema.org/WebPage" lang="tr"><head><meta content="text/html; charset=UTF-8" http-equiv="Content-Type"><meta content="/images/branding/googleg/1x/googleg_standard_color_128dp.png" itemprop="image"><title>Google</title><script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){var _g={kEI:'LUPcZaLuMv3lkvQPp5SL4Ao',kEXPI:'0,1303564,61903,207,4804,1132070,1962,1195742,697,362,379727,44799,23792,12311,17588,4998,17075,38444,2872,2891,3926,7828,606,29877,30813,16105,230,20583,4,86661,6633,7593,1,42154,2,39761,6700,31122,4567,6253,24676,33064,2,2,1,26632,8155,23351,8701,13734,9779,42459,20198,73179,3030,6610,4541,4665,1804,21011,14257,11814,1632,5259560,6941,2,296,1809,107,75,5992678,412,2798212,8042,32274,10,7443176,16496299,4058008,2375,43886,3,1603,3,2121778,2585,22636437,398338,7375,8408,16103,2,560,13023,3608,820,10576,5878,17458,13534,1923,7287,1301,2370,4832,1575,10460,3386,1074,1972,2474,2222,5210,2212,153,2067,5962,4724,3192,218,3,363,4743,2782,1714,5,4152,4,952,4,106,1989,263,1901,1877,95,2246,300,162,879,1137,11523,728,180,4,1137,252,1794,1406,321,909,579,3127,466,2064,1213,4158,9,6465,359,296,292,8,1262,3,77,462,72,419,866,1228,737,896,338,392,155,205,184,10,1076,1009,5,70,162,183,388,703,1314,18,2,2,2,495,434,1,323,234,1,63,588,50,1517,11,1,1461,919,790,15,274,244,1040,1138,120,62,10,480,245,139,261,168,369,170,2503,148,27,275,50,88,1100,239,1208,51,291,462,325,8,74,238,14,4586,5,266,343,612,21,160,247,7,573,507,143,62,156,4,57,67,318,116,540,40,634,4,237,69,76,1678,259,172,140,248,133,902,664,117,138,667,973,221,48,21689054,3,5571,541,276,486',kBL:'svZs',kOPI:89978449};(function(){var a;(null==(a=window.google)?0:a.stvsc)?google.kEI=_g.kEI:window.google=_g;}).call(this);})();(function(){google.sn='webhp';google.kHL='tr';})();(function(){
var h=this||self;function l(){return void 0!==window.google&&void 0!==window.google.kOPI&&0!==window.google.kOPI?window.google.kOPI:null};var m,n=[];function p(a){for(var b;a&&(!a.getAttribute||!(b=a.getAttribute("eid")));)a=a.parentNode;return b||m}function q(a){for(var b=null;a&&(!a.getAttribute||!(b=a.getAttribute("leid")));)a=a.parentNode;return b}function r(a){/^http:/i.test(a)&&"https:"===window.location.protocol&&(google.ml&&google.ml(Error("a"),!1,{src:a,glmm:1}),a="");return a}
function t(a,b,c,d,k){var e="";-1===b.search("&ei=")&&(e="&ei="+p(d),-1===b.search("&lei=")&&(d=q(d))&&(e+="&lei="+d));d="";var g=-1===b.search("&cshid=")&&"slh"!==a,f=[];f.push(["zx",Date.now().toString()]);h._cshid&&g&&f.push(["cshid",h._cshid]);c=c();null!=c&&f.push(["opi",c.toString()]);for(c=0;c<f.length;c++){if(0===c||0<c)d+="&";d+=f[c][0]+"="+f[c][1]}return"/"+(k||"gen_204")+"?atyp=i&ct="+String(a)+"&cad="+(b+e+d)};m=google.kEI;google.getEI=p;google.getLEI=q;google.ml=function(){return null};google.log=function(a,b,c,d,k,e){e=void 0===e?l:e;c||(c=t(a,b,e,d,k));if(c=r(c)){a=new Image;var g=n.length;n[g]=a;a.onerror=a.onload=a.onabort=function(){delete n[g]};a.src=c}};google.logUrl=function(a,b){b=void 0===b?l:b;return t("",a,b)};}).call(this);(function(){google.y={};google.sy=[];google.x=function(a,b){if(a)var c=a.id;else{do c=Math.random();while(google.y[c])}google.y[c]=[a,b];return!1};google.sx=function(a){google.sy.push(a)};google.lm=[];google.plm=function(a){google.lm.push.apply(google.lm,a)};google.lq=[];google.load=function(a,b,c){google.lq.push([[a],b,c])};google.loadAll=function(a,b){google.lq.push([a,b])};google.bx=!1;google.lx=function(){};var d=[];google.fce=function(a,b,c,e){d.push([a,b,c,e])};google.qce=d;}).call(this);google.f={};(function(){
document.documentElement.addEventListener("submit",function(b){var a;if(a=b.target){var c=a.getAttribute("data-submitfalse");a="1"===c||"q"===c&&!a.elements.q.value?!0:!1}else a=!1;a&&(b.preventDefault(),b.stopPropagation())},!0);document.documentElement.addEventListener("click",function(b){var a;a:{for(a=b.target;a&&a!==document.documentElement;a=a.parentElement)if("A"===a.tagName){a="1"===a.getAttribute("data-nohref");break a}a=!1}a&&b.preventDefault()},!0);}).call(this);</script><style>#gbar,#guser{font-size:13px;padding-top:1px !important;}#gbar{height:22px}#guser{padding-bottom:7px !important;text-align:right}.gbh,.gbd{border-top:1px solid #c9d7f1;font-size:1px}.gbh{height:0;position:absolute;top:24px;width:100%}@media all{.gb1{height:22px;margin-right:.5em;vertical-align:top}#gbar{float:left}}a.gb1,a.gb4{text-decoration:underline !important}a.gb1,a.gb4{color:#00c !important}.gbi .gb4{color:#dd8e27 !important}.gbf .gb4{color:#900 !important}
</style><style>body,td,a,p,.h{font-family:arial,sans-serif}body{margin:0;overflow-y:scroll}#gog{padding:3px 8px 0}td{line-height:.8em}.gac_m td{line-height:17px}form{margin-bottom:20px}.h{color:#1967d2}em{font-weight:bold;font-style:normal}.lst{height:25px;width:496px}.gsfi,.lst{font:18px arial,sans-serif}.gsfs{font:17px arial,sans-serif}.ds{display:inline-box;display:inline-block;margin:3px 0 4px;margin-left:4px}input{font-family:inherit}body{background:#fff;color:#000}a{color:#681da8;text-decoration:none}a:hover,a:active{text-decoration:underline}.fl a{color:#1967d2}a:visited{color:#681da8}.sblc{padding-top:5px}.sblc a{display:block;margin:2px 0;margin-left:13px;font-size:11px}.lsbb{background:#f8f9fa;border:solid 1px;border-color:#dadce0 #70757a #70757a #dadce0;height:30px}.lsbb{display:block}#WqQANb a{display:inline-block;margin:0 12px}.lsb{background:url(/images/nav_logo229.png) 0 -261px repeat-x;color:#000;border:none;cursor:pointer;height:30px;margin:0;outline:0;font:15px arial,sans-serif;vertical-align:top}.lsb:active{background:#dadce0}.lst:focus{outline:none}.Ucigb{width:458px}</style><script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){window.google.erd={jsr:1,bv:1961,de:true};
var h=this||self;var k,l=null!=(k=h.mei)?k:1,n,p=null!=(n=h.sdo)?n:!0,q=0,r,t=google.erd,v=t.jsr;google.ml=function(a,b,d,m,e){e=void 0===e?2:e;b&&(r=a&&a.message);void 0===d&&(d={});d.cad="ple_"+google.ple+".aple_"+google.aple;if(google.dl)return google.dl(a,e,d),null;b=d;if(0>v){window.console&&console.error(a,b);if(-2===v)throw a;b=!1}else b=!a||!a.message||"Error loading script"===a.message||q>=l&&!m?!1:!0;if(!b)return null;q++;d=d||{};b=encodeURIComponent;var c="/gen_204?atyp=i&ei="+b(google.kEI);google.kEXPI&&(c+="&jexpid="+b(google.kEXPI));c+="&srcpg="+b(google.sn)+"&jsr="+b(t.jsr)+"&bver="+
b(t.bv);var f=a.lineNumber;void 0!==f&&(c+="&line="+f);var g=a.fileName;g&&(0<g.indexOf("-extension:/")&&(e=3),c+="&script="+b(g),f&&g===window.location.href&&(f=document.documentElement.outerHTML.split("\n")[f],c+="&cad="+b(f?f.substring(0,300):"No script found.")));google.ple&&1===google.ple&&(e=2);c+="&jsel="+e;for(var u in d)c+="&",c+=b(u),c+="=",c+=b(d[u]);c=c+"&emsg="+b(a.name+": "+a.message);c=c+"&jsst="+b(a.stack||"N/A");12288<=c.length&&(c=c.substr(0,12288));a=c;m||google.log(0,"",a);return a};window.onerror=function(a,b,d,m,e){r!==a&&(a=e instanceof Error?e:Error(a),void 0===d||"lineNumber"in a||(a.lineNumber=d),void 0===b||"fileName"in a||(a.fileName=b),google.ml(a,!1,void 0,!1,"SyntaxError"===a.name||"SyntaxError"===a.message.substring(0,11)||-1!==a.message.indexOf("Script error")?3:0));r=null;p&&q>=l&&(window.onerror=null)};})();</script></head><body bgcolor="#fff"><script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){var src='/images/nav_logo229.png';var iesg=false;document.body.onload = function(){window.n && window.n();if (document.images){new Image().src=src;}
if (!iesg){document.f&&document.f.q.focus();document.gbqf&&document.gbqf.q.focus();}
}
})();</script><div id="mngb"><div id=gbar><nobr><b class=gb1>Arama</b> <a class=gb1 href="https://www.google.com/imghp?hl=tr&tab=wi">Grseller</a> <a class=gb1 href="http://maps.google.com.tr/maps?hl=tr&tab=wl">Haritalar</a> <a class=gb1 href="https://play.google.com/?hl=tr&tab=w8">Play</a> <a class=gb1 href="https://www.youtube.com/?tab=w1">YouTube</a> <a class=gb1 href="https://news.google.com/?tab=wn">Haberler</a> <a class=gb1 href="https://mail.google.com/mail/?tab=wm">Gmail</a> <a class=gb1 href="https://drive.google.com/?tab=wo">Drive</a> <a class=gb1 style="text-decoration:none" href="https://www.google.com.tr/intl/tr/about/products?tab=wh"><u>Daha fazlas&#305;</u> &raquo;</a></nobr></div><div id=guser width=100%><nobr><span id=gbn class=gbi></span><span id=gbf class=gbf></span><span id=gbe></span><a href="http://www.google.com.tr/history/optout?hl=tr" class=gb4>Web Gemi&#351;i</a> | <a  href="/preferences?hl=tr" class=gb4>Ayarlar</a> | <a target=_top id=gb_70 href="https://accounts.google.com/ServiceLogin?hl=tr&passive=true&continue=http://www.google.com/&ec=GAZAAQ" class=gb4>Oturum a&#305;n</a></nobr></div><div class=gbh style=left:0></div><div class=gbh style=right:0></div></div><center><br clear="all" id="lgpd"><div id="lga"><img alt="Google" height="92" src="/images/branding/googlelogo/1x/googlelogo_white_background_color_272x92dp.png" style="padding:28px 0 14px" width="272" id="hplogo"><br><br></div><form action="/search" name="f"><table cellpadding="0" cellspacing="0"><tr valign="top"><td width="25%">&nbsp;</td><td align="center" nowrap=""><input name="ie" value="ISO-8859-1" type="hidden"><input value="tr" name="hl" type="hidden"><input name="source" type="hidden" value="hp"><input name="biw" type="hidden"><input name="bih" type="hidden"><div class="ds" style="height:32px;margin:4px 0"><div style="position:relative;zoom:1"><input class="lst Ucigb" style="margin:0;padding:5px 8px 0 6px;vertical-align:top;color:#000;padding-right:38px" autocomplete="off" value="" title="Google'da Ara" maxlength="2048" name="q" size="57"><img src="/textinputassistant/tia.png" style="position:absolute;cursor:pointer;right:5px;top:4px;z-index:300" data-script-url="/textinputassistant/13/tr_tia.js" id="tsuid_1" alt="" height="23" width="27"><script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){var id='tsuid_1';document.getElementById(id).onclick = function(){var s = document.createElement('script');s.src = this.getAttribute('data-script-url');document.body.appendChild(s);};})();</script></div></div><br style="line-height:0"><span class="ds"><span class="lsbb"><input class="lsb" value="Google'da Ara" name="btnG" type="submit"></span></span><span class="ds"><span class="lsbb"><input class="lsb" id="tsuid_2" value="Kendimi &#350;ansl&#305; Hissediyorum" name="btnI" type="submit"><script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){var id='tsuid_2';document.getElementById(id).onclick = function(){if (this.form.q.value){this.checked = 1;if (this.form.iflsig)this.form.iflsig.disabled = false;}
else top.location='/doodles/';};})();</script><input value="ANes7DEAAAAAZdxRPVtTcgR_5ye9rltxLxw3vNR7dbVi" name="iflsig" type="hidden"></span></span></td><td class="fl sblc" align="left" nowrap="" width="25%"><a href="/advanced_search?hl=tr&amp;authuser=0">Geli&#351;mi&#351; arama</a></td></tr></table><input id="gbv" name="gbv" type="hidden" value="1"><script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){var a,b="1";if(document&&document.getElementById)if("undefined"!=typeof XMLHttpRequest)b="2";else if("undefined"!=typeof ActiveXObject){var c,d,e=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"];for(c=0;d=e[c++];)try{new ActiveXObject(d),b="2"}catch(h){}}a=b;if("2"==a&&-1==location.search.indexOf("&gbv=2")){var f=google.gbvu,g=document.getElementById("gbv");g&&(g.value=a);f&&window.setTimeout(function(){location.href=f},0)};}).call(this);</script></form><div id="gac_scont"></div><div style="font-size:83%;min-height:3.5em"><br></div><span id="footer"><div style="font-size:10pt"><div style="margin:19px auto;text-align:center" id="WqQANb"><a href="/intl/tr/ads/">Reklam</a><a href="http://www.google.com.tr/intl/tr/services/">&#304;&#351;letme zmleri</a><a href="/intl/tr/about.html">Google Hakk&#305;nda</a><a href="http://www.google.com/setprefdomain?prefdom=TR&amp;prev=http://www.google.com.tr/&amp;sig=K_pI9vTyvPot-zh1-58oMapB0dy1M%3D">Google.com.tr</a></div></div><p style="font-size:8pt;color:#70757a">&copy; 2024 - <a href="/intl/tr/policies/privacy/">Gizlilik</a> - <a href="/intl/tr/policies/terms/">&#350;artlar</a></p></span></center><script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){window.google.cdo={height:757,width:1440};(function(){var a=window.innerWidth,b=window.innerHeight;if(!a||!b){var c=window.document,d="CSS1Compat"==c.compatMode?c.documentElement:c.body;a=d.clientWidth;b=d.clientHeight}
if(a&&b&&(a!=google.cdo.width||b!=google.cdo.height)){var e=google,f=e.log,g="/client_204?&atyp=i&biw="+a+"&bih="+b+"&ei="+google.kEI,h="",k=[],l=void 0!==window.google&&void 0!==window.google.kOPI&&0!==window.google.kOPI?window.google.kOPI:null;null!=l&&k.push(["opi",l.toString()]);for(var m=0;m<k.length;m++){if(0===m||0<m)h+="&";h+=k[m][0]+"="+k[m][1]}f.call(e,"","",g+h)};}).call(this);})();</script> <script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){google.xjs={ck:'xjs.hp.wbOBFWnEId4.L.X.O',combam:'AAAAAAAAAAAAAAAAAAAAAAAAAIAAAAAAAAAOAAAgAAgAAAAwAAAAAAAAABAAHERHADAARwAA8AI',cs:'ACT90oGBZQ2C6FIu18BJYjen1n2TOFVTkw',cssam:'AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAgAAgAAAAAAAAAAAAAABA',cssopt:true,csss:'ACT90oFLh1ADDneiR4VRIBvu0io-lXySQw',excm:[],jsam:'AAAAAAAAAAAAAAAAAAAAAAAAAIAAAAAAAAAOAAAAAAAAAAAwAAAAAAAAAAAAHERHADAARwAA8AI',jss:'ACT90oFt3g0eCpku2GdNQBL8-NHtnMU22w',noinlinecss:false,sepam:true,sepcss:true};})();</script>     <script nonce="el4UdWDImOy0EEfkd6sjEA">(function(){var u='/xjs/_/js/k\x3dxjs.hp.en.nUL_jPOf-18.O/am\x3dAAAAAAAAAAAAAAAAAAAAAAAAAIAAAAAAAAAOAAAgAAgAAAAwAAAAAAAAABAAHERHADAARwAA8AI/d\x3d1/ed\x3d1/rs\x3dACT90oGxV25pRcgYOXtVwCmnYmHc35UfuA/m\x3dsb_he,d';var amd=0;
var e=this||self,f=function(a){return a};var g;var h=function(a){this.g=a};h.prototype.toString=function(){return this.g+""};var k={};var l=function(){var a=document;var b="SCRIPT";"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)};
function m(a,b){a.src=b instanceof h&&b.constructor===h?b.g:"type_error:TrustedResourceUrl";var c,d;(c=(b=null==(d=(c=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:d.call(c,"script[nonce]"))?b.nonce||b.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)};function n(a){a=null===a?"null":void 0===a?"undefined":a;if(void 0===g){var b=null;var c=e.trustedTypes;if(c&&c.createPolicy){try{b=c.createPolicy("goog#html",{createHTML:f,createScript:f,createScriptURL:f})}catch(d){e.console&&e.console.error(d.message)}g=b}else g=b}a=(b=g)?b.createScriptURL(a):a;return new h(a,k)};void 0===google.ps&&(google.ps=[]);function p(){var a=u,b=function(){};google.lx=google.stvsc?b:function(){q(a);google.lx=b};google.bx||google.lx()}function r(a,b){b&&m(a,n(b));var c=a.onload;a.onload=function(d){c&&c(d);google.ps=google.ps.filter(function(t){return a!==t})};google.ps.push(a);document.body.appendChild(a)}google.as=r;function q(a){google.timers&&google.timers.load&&google.tick&&google.tick("load","xjsls");var b=l();b.onerror=function(){google.ple=1};b.onload=function(){google.ple=0};google.xjsus=void 0;r(b,a);google.aple=-1;google.psa=!0};google.xjsu=u;e._F_jsUrl=u;setTimeout(function(){0<amd?google.caft(function(){return p()},amd):p()},0);})();window._ = window._ || {};window._DumpException = _._DumpException = function(e){throw e;};window._s = window._s || {};_s._DumpException = _._DumpException;window._qs = window._qs || {};_qs._DumpException = _._DumpException;(function(){var t=[1,2,0,0,0,640,536870912,134218243,264192,16826368,8388608,360448,4670492,18628800,3080192];window._F_toggles = window._xjs_toggles = t;})();function _F_installCss(c){}
(function(){google.jl={bfl:0,blt:'none',chnk:0,dw:false,dwu:true,emtn:0,end:0,ico:false,ikb:0,ine:false,injs:'none',injt:0,injth:0,injv2:false,lls:'default',pdt:0,rep:0,snet:true,strt:0,ubm:false,uwp:true};})();(function(){var pmc='{\x22d\x22:{},\x22sb_he\x22:{\x22agen\x22:false,\x22cgen\x22:false,\x22client\x22:\x22heirloom-hp\x22,\x22dh\x22:true,\x22ds\x22:\x22\x22,\x22fl\x22:true,\x22host\x22:\x22google.com\x22,\x22jsonp\x22:true,\x22msgs\x22:{\x22cibl\x22:\x22Aramay\\u0131 Temizle\x22,\x22dym\x22:\x22Bunu mu demek istediniz?\x22,\x22lcky\x22:\x22Kendimi \\u015eansl\\u0131 Hissediyorum\x22,\x22lml\x22:\x22Daha fazla bilgi edinin\x22,\x22psrc\x22:\x22Bu arama \\u003Ca href\x3d\\\x22/history\\\x22\\u003EWeb Ge\\u00e7mi\\u015finizden\\u003C/a\\u003E kald\\u0131r\\u0131ld\\u0131\x22,\x22psrl\x22:\x22Kald\\u0131r\x22,\x22sbit\x22:\x22G\\u00f6rselle ara\x22,\x22srch\x22:\x22Google\\u0026#39;da Ara\x22},\x22ovr\x22:{},\x22pq\x22:\x22\x22,\x22rfs\x22:[],\x22sbas\x22:\x220 3px 8px 0 rgba(0,0,0,0.2),0 0 0 1px rgba(0,0,0,0.08)\x22,\x22stok\x22:\x22e4e4SBFwOVi5zv2IPFUvq1cTLYE\x22}}';google.pmc=JSON.parse(pmc);})();(function(){var b=function(a){var c=0;return function(){return c<a.length?{done:!1,value:a[c++]}:{done:!0}}};
var e=this||self;var g,h;a:{for(var k=["CLOSURE_FLAGS"],l=e,n=0;n<k.length;n++)if(l=l[k[n]],null==l){h=null;break a}h=l}var p=h&&h[610401301];g=null!=p?p:!1;var q,r=e.navigator;q=r?r.userAgentData||null:null;function t(a){return g?q?q.brands.some(function(c){return(c=c.brand)&&-1!=c.indexOf(a)}):!1:!1}function u(a){var c;a:{if(c=e.navigator)if(c=c.userAgent)break a;c=""}return-1!=c.indexOf(a)};function v(){return g?!!q&&0<q.brands.length:!1}function w(){return u("Safari")&&!(x()||(v()?0:u("Coast"))||(v()?0:u("Opera"))||(v()?0:u("Edge"))||(v()?t("Microsoft Edge"):u("Edg/"))||(v()?t("Opera"):u("OPR"))||u("Firefox")||u("FxiOS")||u("Silk")||u("Android"))}function x(){return v()?t("Chromium"):(u("Chrome")||u("CriOS"))&&!(v()?0:u("Edge"))||u("Silk")}function y(){return u("Android")&&!(x()||u("Firefox")||u("FxiOS")||(v()?0:u("Opera"))||u("Silk"))};var z=v()?!1:u("Trident")||u("MSIE");y();x();w();Object.freeze(new function(){});Object.freeze(new function(){});var A=!z&&!w(),D=function(a){if(/-[a-z]/.test("ved"))return null;if(A&&a.dataset){if(y()&&!("ved"in a.dataset))return null;a=a.dataset.ved;return void 0===a?null:a}return a.getAttribute("data-"+"ved".replace(/([A-Z])/g,"-$1").toLowerCase())};var E=[],F=null;function G(a){a=a.target;var c=performance.now(),f=[],H=f.concat,d=E;if(!(d instanceof Array)){var m="undefined"!=typeof Symbol&&Symbol.iterator&&d[Symbol.iterator];if(m)d=m.call(d);else if("number"==typeof d.length)d={next:b(d)};else throw Error("a`"+String(d));for(var B=[];!(m=d.next()).done;)B.push(m.value);d=B}E=H.call(f,d,[c]);if(a&&a instanceof HTMLElement)if(a===F){if(c=4<=E.length)c=5>(E[E.length-1]-E[E.length-4])/1E3;if(c){c=google.getEI(a);a.hasAttribute("data-ved")?f=a?D(a)||"":"":f=(f=
a.closest("[data-ved]"))?D(f)||"":"";f=f||"";if(a.hasAttribute("jsname"))a=a.getAttribute("jsname");else{var C;a=null==(C=a.closest("[jsname]"))?void 0:C.getAttribute("jsname")}google.log("rcm","&ei="+c+"&ved="+f+"&jsname="+(a||""))}}else F=a,E=[c]}window.document.addEventListener("DOMContentLoaded",function(){document.body.addEventListener("click",G)});}).call(this);</script></body></html>

- wget dosya.link | download file

- tc | traffic control / control the packet flow

- dig/nslookup www.google.com TYPE | DNS query |
; <<>> DiG 9.18.18-0ubuntu0.22.04.1-Ubuntu <<>> www.google.com
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 14767
;; flags: qr rd ad; QUERY: 1, ANSWER: 1, AUTHORITY: 0, ADDITIONAL: 0
;; WARNING: recursion requested but not available

;; QUESTION SECTION:
;www.google.com.                        IN      A

;; ANSWER SECTION:
www.google.com.         0       IN      A       142.250.187.132

;; Query time: 0 msec
;; SERVER: 172.21.144.1#53(172.21.144.1) (UDP)
;; WHEN: Sat Mar 02 20:12:48 +03 2024
;; MSG SIZE  rcvd: 62

whois 8.8.8.8 | asking internet domain names/IPs |
#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2024, American Registry for Internet Numbers, Ltd.
#


NetRange:       8.8.8.0 - 8.8.8.255
CIDR:           8.8.8.0/24
NetName:        GOGL
NetHandle:      NET-8-8-8-0-2
Parent:         NET8 (NET-8-0-0-0-0)
NetType:        Direct Allocation
OriginAS:
Organization:   Google LLC (GOGL)
RegDate:        2023-12-28
Updated:        2023-12-28
Ref:            https://rdap.arin.net/registry/ip/8.8.8.0



OrgName:        Google LLC
OrgId:          GOGL
Address:        1600 Amphitheatre Parkway
City:           Mountain View
StateProv:      CA
PostalCode:     94043
Country:        US
RegDate:        2000-03-30
Updated:        2019-10-31
Comment:        Please note that the recommended way to file abuse complaints are located in the following links.
Comment:
Comment:        To report abuse and illegal activity: https://www.google.com/contact/
Comment:
Comment:        For legal requests: http://support.google.com/legal
Comment:
Comment:        Regards,
Comment:        The Google Team
Ref:            https://rdap.arin.net/registry/entity/GOGL


OrgTechHandle: ZG39-ARIN
OrgTechName:   Google LLC
OrgTechPhone:  +1-650-253-0000
OrgTechEmail:  arin-contact@google.com
OrgTechRef:    https://rdap.arin.net/registry/entity/ZG39-ARIN

OrgAbuseHandle: ABUSE5250-ARIN
OrgAbuseName:   Abuse
OrgAbusePhone:  +1-650-253-0000
OrgAbuseEmail:  network-abuse@google.com
OrgAbuseRef:    https://rdap.arin.net/registry/entity/ABUSE5250-ARIN


#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2024, American Registry for Internet Numbers, Ltd.


- ssh | Secure remote access

- scp | file transfer using ssh

- rsync | sync files etc.

- ngrep | grep on network

- tcpdump | captures and analyzes packets on network

- wireshark | tcpdump packets in gui

- tshark | cmdline wireshark

- tcpflow | capture tcp stream

- ifconfig | info's of network config |
eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 172.21.145.234  netmask 255.255.240.0  broadcast 172.21.159.255
        inet6 fe80::215:5dff:fe55:5d95  prefixlen 64  scopeid 0x20<link>
        ether 00:15:5d:55:5d:95  txqueuelen 1000  (Ethernet)
        RX packets 48592  bytes 69558825 (69.5 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 17798  bytes 1280463 (1.2 MB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 0  bytes 0 (0.0 B)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 0  bytes 0 (0.0 B)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0


- route -n | route table |
Kernel IP routing table
Destination     Gateway         Genmask         Flags Metric Ref    Use Iface
0.0.0.0         172.21.144.1    0.0.0.0         UG    0      0        0 eth0
172.21.144.0    0.0.0.0         255.255.240.0   U     0      0        0 eth0


- ip | ifconfig / network configuration/management |
-- ip link show
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN mode DEFAULT group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc mq state UP mode DEFAULT group default qlen 1000
    link/ether 00:15:5d:55:5d:95 brd ff:ff:ff:ff:ff:ff
-- ip route show
default via 172.21.144.1 dev eth0 proto kernel
172.21.144.0/20 dev eth0 proto kernel scope link src 172.21.145.234


- arp | ARP table |
Address                  HWtype  HWaddress           Flags Mask            Iface
Eren                     ether   00:15:5d:84:c5:74   C                     eth0


- mitmproxy | view the network traffic

- nmap | scan ports

- zenmap | gui nmap

- p0f | detect os of devices on network

- openvpn/wireguard | vpn

- nc | manual TCP conn

- socat | establish socket for connection

- telnet | insecure ssh

- ftp/sftp | file operations / sftp(ssh)

- netstat/ss/lsof/fuser | network info |
-- netstat -s
Ip:
    Forwarding: 2
    28518 total packets received
    0 forwarded
    0 incoming packets discarded
    27956 incoming packets delivered
    17927 requests sent out
Icmp:
    2 ICMP messages received
    1 input ICMP message failed
    ICMP input histogram:
        destination unreachable: 2
    15 ICMP messages sent
    0 ICMP messages failed
    ICMP output histogram:
        destination unreachable: 15
IcmpMsg:
        InType3: 2
        OutType3: 15
Tcp:
    42 active connection openings
    0 passive connection openings
    11 failed connection attempts
    1 connection resets received
    0 connections established
    27867 segments received
    17844 segments sent out
    5 segments retransmitted
    1 bad segments received
    17 resets sent
Udp:
    72 packets received
    15 packets to unknown port received
    0 packet receive errors
    72 packets sent
    0 receive buffer errors
    0 send buffer errors
UdpLite:
TcpExt:
    14 TCP sockets finished time wait in fast timer
    5 delayed acks sent
    22468 packet headers predicted
    44 acknowledgments not containing data payload received
    56 predicted acknowledgments
    TCPLostRetransmit: 2
    TCPTimeouts: 5
    TCPBacklogCoalesce: 1
    3 connections reset due to unexpected data
    1 connections reset due to early user close
    TCPRcvCoalesce: 6685
    TCPOFOQueue: 4597
    TCPChallengeACK: 1
    TCPSYNChallenge: 1
    TCPAutoCorking: 4
    TCPSynRetrans: 5
    TCPOrigDataSent: 165
    TCPDelivered: 184
    TCPAckCompressed: 3692
    TcpTimeoutRehash: 5
IpExt:
    InOctets: 68127654
    OutOctets: 1039257
    InNoECTPkts: 49262
Sctp:
    0 Current Associations
    0 Active Associations
    0 Passive Associations
    0 Number of Aborteds
    0 Number of Graceful Terminations
    0 Number of Out of Blue packets
    0 Number of Packets with invalid Checksum
    0 Number of control chunks sent
    0 Number of ordered chunks sent
    0 Number of Unordered chunks sent
    0 Number of control chunks received
    0 Number of ordered chunks received
    0 Number of Unordered chunks received
    0 Number of messages fragmented
    0 Number of messages reassembled
    0 Number of SCTP packets sent
    0 Number of SCTP packets received


- iptables | linux firewall setup

- nftables | new iptables

- hping3 | send custom packet

- traceroute/mtr 8.8.8.8 | send to ping to find availabilty |
traceroute to 8.8.8.8 (8.8.8.8), 30 hops max, 60 byte packets
 1  Eren (172.21.144.1)  0.389 ms  0.348 ms  0.330 ms
 2  192.168.1.1 (192.168.1.1)  1.022 ms  0.999 ms  1.923 ms
 3  100.125.0.1 (100.125.0.1)  4.518 ms  3.738 ms  3.772 ms
 4  172.25.34.102 (172.25.34.102)  4.416 ms  4.889 ms  8.157 ms


- tcptraceroute | using TCP packets instead of ICMP

- ethtool eth0 | eth config |
Settings for eth0:
        Supported ports: [ ]
        Supported link modes:   Not reported
        Supported pause frame use: No
        Supports auto-negotiation: No
        Supported FEC modes: Not reported
        Advertised link modes:  Not reported
        Advertised pause frame use: No
        Advertised auto-negotiation: No
        Advertised FEC modes: Not reported
        Speed: 10000Mb/s
        Duplex: Full
        Port: Other
        PHYAD: 0
        Transceiver: internal
        Auto-negotiation: off
Cannot get wake-on-lan settings: Operation not permitted
        Current message level: 0x000000f7 (247)
                               drv probe link ifdown ifup rx_err tx_err
        Link detected: yes


- iw | wifi config

- sysctl -a | Linux kernel parameter config
abi.vsyscall32 = 1
debug.exception-trace = 1
debug.kprobes-optimization = 1
dev.raid.speed_limit_max = 200000
dev.raid.speed_limit_min = 1000
dev.scsi.logging_level = 0
dev.tty.ldisc_autoload = 0
fs.aio-max-nr = 65536
fs.aio-nr = 0
.... It goes over 1000 lines

  
- openssl | SSL certificates

- stunnel | secure connection using SSL protocols

- iptraf/nethogs/iftop/ntop | seeing network traffic

- ab/nload/iperf | realtime network traffic

- python3 -m http.server | starting HTTP server |
Serving HTTP on 0.0.0.0 port 8080 (http://0.0.0.0:8080/) ...

- ipcalc 192.168.1.0/24 | shows IP adrrs | 
Address:   192.168.1.0          11000000.10101000.00000001. 00000000
Netmask:   255.255.255.0 = 24   11111111.11111111.11111111. 00000000
Wildcard:  0.0.0.255            00000000.00000000.00000000. 11111111
=>
Network:   192.168.1.0/24       11000000.10101000.00000001. 00000000
HostMin:   192.168.1.1          11000000.10101000.00000001. 00000001
HostMax:   192.168.1.254        11000000.10101000.00000001. 11111110
Broadcast: 192.168.1.255        11000000.10101000.00000001. 11111111
Hosts/Net: 254                   Class C, Private Internet

- nsenter | executes program in the namespaces
