---
about_this_resource_text: ''
course_id: mas-s62-cryptocurrency-engineering-and-design-spring-2018
embedded_media:
- id: Video-YouTube-Stream
  media_location: yKa-KxY-YJk
  parent_uid: 25b467f2a10ad50edf19075f14450646
  title: Video-YouTube-Stream
  type: Video
  uid: 6ce40f51369654c1e5579a816d5c9d8b
- id: 3Play-3PlayYouTubeid-MP4
  media_location: yKa-KxY-YJk
  parent_uid: 25b467f2a10ad50edf19075f14450646
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: bbad4ee2c30f489c71c3b8298df8e68d
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MITMAS.S62S18/MITMAS_S62S18_lec24_300k.mp4
  parent_uid: 25b467f2a10ad50edf19075f14450646
  title: Video-Internet Archive-MP4
  type: Video
  uid: 169959e58aec30f1fb27e7a03623476a
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/yKa-KxY-YJk/default.jpg
  parent_uid: 25b467f2a10ad50edf19075f14450646
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 478686cc60df89e895f308361f1f4035
- id: yKa-KxY-YJk.srt
  parent_uid: 25b467f2a10ad50edf19075f14450646
  technical_location: https://ocw.mit.edu/courses/media-arts-and-sciences/mas-s62-cryptocurrency-engineering-and-design-spring-2018/lecture-videos/lec24-zkledger/yKa-KxY-YJk.srt
  title: 3play caption file
  type: null
  uid: c15a3ca278364def5f34051fb77d8bc9
- id: yKa-KxY-YJk.pdf
  parent_uid: 25b467f2a10ad50edf19075f14450646
  technical_location: https://ocw.mit.edu/courses/media-arts-and-sciences/mas-s62-cryptocurrency-engineering-and-design-spring-2018/lecture-videos/lec24-zkledger/yKa-KxY-YJk.pdf
  title: 3play pdf file
  type: null
  uid: 8b5d3a8cfad018adfa59605b05b06b66
- id: Caption-3Play YouTube id-SRT
  parent_uid: 25b467f2a10ad50edf19075f14450646
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 6f0eb5438609e5ef3759e7a5026fa4fb
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 25b467f2a10ad50edf19075f14450646
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: e76a5c7f3ede2d4ff399265207dfb9fe
inline_embed_id: 93175589zkledger55634903
layout: video
order_index: null
parent_uid: 6396b119dea1934ebbe339b1c3062c94
related_resources_text: ''
short_url: lec24-zkledger
technical_location: https://ocw.mit.edu/courses/media-arts-and-sciences/mas-s62-cryptocurrency-engineering-and-design-spring-2018/lecture-videos/lec24-zkledger
template_type: Tabbed
title: 'Lecture 24: zkLedger'
transcript: <p><span m="950">The</span> <span m="1040">following</span> <span m="1490">content</span>
  <span m="2000">is</span> <span m="2120">provided</span> <span m="2570">under</span>
  <span m="2780">a</span> <span m="2840">Creative</span> <span m="3320">Commons</span>
  <span m="3710">license.</span> <span m="4710">Your</span> <span m="4790">support</span>
  <span m="5300">will</span> <span m="5450">help</span> <span m="5720">MIT</span>
  <span m="6170">OpenCourseWare</span> <span m="6920">continue</span> <span m="7430">to</span>
  <span m="7580">offer</span> <span m="7910">high</span> <span m="8119">quality</span>
  <span m="8600">educational</span> <span m="9260">resources</span> <span m="9830">for</span>
  <span m="9950">free.</span> <span m="11010">To</span> <span m="11030">make</span>
  <span m="11240">a</span> <span m="11300">donation</span> <span m="12050">or</span>
  <span m="12200">to</span> <span m="12350">view</span> <span m="12560">additional</span>
  <span m="12950">materials</span> <span m="13580">from</span> <span m="13760">hundreds</span>
  <span m="14090">of</span> <span m="14180">MIT</span> <span m="14570">courses,</span>
  <span m="15870">visit</span> <span m="16070">MIT</span> <span m="16580">OpenCourseWare</span>
  <span m="17540">at</span> <span m="17690">ocw.mit.edu.</span></p><p><span m="23950">NEHA
  NARULA:</span> <span m="24160">OK,</span> <span m="24370">let's</span> <span m="24580">go</span>
  <span m="24700">ahead</span> <span m="25060">and</span> <span m="25870">get</span>
  <span m="26050">started.</span> <span m="26750">So</span> <span m="27160">Tadge</span>
  <span m="27940">is</span> <span m="28240">in</span> <span m="28540">California</span>
  <span m="29170">today,</span> <span m="30040">so</span> <span m="30310">he</span>
  <span m="30520">asked</span> <span m="30730">me</span> <span m="30940">to</span>
  <span m="31420">give</span> <span m="31690">today's</span> <span m="31990">lecture,</span>
  <span m="32980">which</span> <span m="33220">will</span> <span m="33340">be</span>
  <span m="33460">based</span> <span m="33820">on</span> <span m="33970">a</span>
  <span m="34030">research</span> <span m="34390">project</span> <span m="34750">that</span>
  <span m="34840">we're</span> <span m="34960">working</span> <span m="35320">on</span>
  <span m="35610">at</span> <span m="35860">the</span> <span m="35980">DCI.</span>
  <span m="37630">This</span> <span m="37840">is</span> <span m="37990">actually</span>
  <span m="38530">really</span> <span m="38860">connected</span> <span m="39430">to</span>
  <span m="39820">confidential</span> <span m="40780">transactions</span> <span m="41500">and</span>
  <span m="41590">confidential</span> <span m="42190">assets,</span> <span m="42610">which</span>
  <span m="42790">I</span> <span m="42850">think</span> <span m="43030">that</span>
  <span m="43150">you</span> <span m="43270">guys</span> <span m="43480">covered</span>
  <span m="44380">in</span> <span m="44700">a</span> <span m="44770">previous</span>
  <span m="45250">class.</span> <span m="45760">So</span> <span m="46060">Pedersen</span>
  <span m="46510">commitments</span> <span m="46990">will</span> <span m="47140">play</span>
  <span m="47500">a</span> <span m="47560">very</span> <span m="47890">important</span>
  <span m="48280">role</span> <span m="48970">in</span> <span m="49240">the</span>
  <span m="49330">work</span> <span m="49630">I'm</span> <span m="49750">about</span>
  <span m="49960">to</span> <span m="50050">present.</span></p><p><span m="50560">I</span>
  <span m="50680">want</span> <span m="50800">to</span> <span m="50860">present</span>
  <span m="51460">this</span> <span m="52030">work</span> <span m="52360">that</span>
  <span m="52600">we've</span> <span m="52840">been</span> <span m="52990">doing.</span>
  <span m="54280">This</span> <span m="54460">is</span> <span m="54580">joint</span>
  <span m="54850">work</span> <span m="55090">with</span> <span m="55240">Willy</span>
  <span m="55480">Vasquez,</span> <span m="56150">who</span> <span m="56260">was</span>
  <span m="56830">an</span> <span m="57120">MIT</span> <span m="57550">M.Eng.</span>
  <span m="58630">He</span> <span m="58780">graduated</span> <span m="59230">and</span>
  <span m="59320">moved</span> <span m="59500">to</span> <span m="59660">UT-Austin,</span>
  <span m="60760">and</span> <span m="61270">Madars</span> <span m="61700">Virza,</span>
  <span m="62060">who</span> <span m="62200">is</span> <span m="62350">a</span> <span
  m="62380">research</span> <span m="62710">scientist</span> <span m="63220">with</span>
  <span m="63370">the</span> <span m="63460">DCI.</span></p><p><span m="64420">And</span>
  <span m="64629">this</span> <span m="64750">project</span> <span m="65080">is</span>
  <span m="65200">called</span> <span m="65470">zkLedger.</span> <span m="66640">It's</span>
  <span m="66940">about</span> <span m="67300">privacy-preserving</span> <span m="68800">auditing</span>
  <span m="69460">for</span> <span m="69790">distributed</span> <span m="70270">ledgers.</span>
  <span m="71470">So</span> <span m="72940">to</span> <span m="73060">start</span>
  <span m="73480">with,</span> <span m="74000">I</span> <span m="74140">am</span>
  <span m="74260">not</span> <span m="74440">sure</span> <span m="74590">how</span>
  <span m="74770">much</span> <span m="74980">work</span> <span m="75190">you</span>
  <span m="75280">guys</span> <span m="75520">have</span> <span m="75640">done</span>
  <span m="75940">on</span> <span m="76120">permissioned</span> <span m="77020">blockchains</span>
  <span m="77710">so</span> <span m="77920">far.</span> <span m="78610">How</span>
  <span m="78760">much</span> <span m="79030">have</span> <span m="79120">you</span>
  <span m="79240">covered</span> <span m="79660">with</span> <span m="79840">respect</span>
  <span m="80140">to</span> <span m="80230">permissioned</span> <span m="80610">blockchains?</span>
  <span m="81340">Nothing</span> <span m="81760">at</span> <span m="81850">all?</span>
  <span m="82750">OK.</span></p><p><span m="85660">Should</span> <span m="85810">we</span>
  <span m="85900">start</span> <span m="86170">with</span> <span m="86320">what</span>
  <span m="86500">is</span> <span m="86740">a</span> <span m="86800">permissioned</span>
  <span m="87250">blockchain,</span> <span m="87700">or</span> <span m="87760">do</span>
  <span m="87850">you</span> <span m="87910">guys</span> <span m="88120">feel</span>
  <span m="88330">like</span> <span m="88480">you</span> <span m="88600">have</span>
  <span m="88990">a</span> <span m="89050">handle</span> <span m="89620">on</span>
  <span m="89860">what</span> <span m="90100">that</span> <span m="90280">means</span>
  <span m="90670">or</span> <span m="90730">what</span> <span m="90880">that</span>
  <span m="91060">is?</span> <span m="91400">In its</span> <span m="91630">most</span>
  <span m="91870">generic,</span> <span m="92470">abstract</span> <span m="92950">sense?</span>
  <span m="94010">Yes?</span></p><p><span m="94780">AUDIENCE:</span> <span m="94810">Does</span>
  <span m="94840">it</span> <span m="94870">just</span> <span m="95050">mean</span>
  <span m="95320">that</span> <span m="95890">different</span> <span m="96250">people</span>
  <span m="96820">have</span> <span m="97180">access</span> <span m="97600">to</span>
  <span m="97760">see</span> <span m="98080">parts of</span> <span m="98460">the chain?</span></p><p><span
  m="99220">NEHA NARULA:</span> <span m="99365">Yeah.</span> <span m="99790">So,</span>
  <span m="100600">good</span> <span m="100750">question.</span> <span m="101230">OK,</span>
  <span m="101590">so</span> <span m="102520">these</span> <span m="102730">words</span>
  <span m="103060">that</span> <span m="103180">we</span> <span m="103270">use--</span>
  <span m="103570">permissioned</span> <span m="104230">versus</span> <span m="104620">permissionless--</span>
  <span m="105760">usually</span> <span m="106240">refer</span> <span m="106660">to</span>
  <span m="106990">who</span> <span m="107170">has</span> <span m="107410">right</span>
  <span m="107950">access</span> <span m="108550">to</span> <span m="108700">the</span>
  <span m="108790">chain.</span></p><p><span m="109780">So</span> <span m="110620">in</span>
  <span m="110860">cryptocurrencies</span> <span m="111730">like</span> <span m="111910">Bitcoin</span>
  <span m="112450">and</span> <span m="112600">Ethereum,</span> <span m="113560">theoretically,</span>
  <span m="114610">any</span> <span m="114850">one</span> <span m="115030">of</span>
  <span m="115150">us</span> <span m="115600">could</span> <span m="115930">spin</span>
  <span m="116230">up</span> <span m="116350">our</span> <span m="116470">own</span>
  <span m="116620">ASIC,</span> <span m="117490">get</span> <span m="117730">really</span>
  <span m="118000">lucky,</span> <span m="118510">mine a</span> <span m="118930">block,</span>
  <span m="119410">and</span> <span m="119530">put</span> <span m="120310">the</span>
  <span m="120460">transactions</span> <span m="121270">that</span> <span m="121360">we</span>
  <span m="121600">are</span> <span m="121720">interested</span> <span m="122290">in</span>
  <span m="122710">into</span> <span m="123100">the</span> <span m="123190">chain.</span>
  <span m="124060">Now</span> <span m="124240">of</span> <span m="124330">course,</span>
  <span m="124810">no</span> <span m="125250">one's</span> <span m="125690">going</span>
  <span m="126160">to</span> <span m="126670">accept</span> <span m="127000">that</span>
  <span m="127150">block</span> <span m="127510">if</span> <span m="127600">it</span>
  <span m="127690">violates</span> <span m="128889">the</span> <span m="128949">majority</span>
  <span m="129400">consensus</span> <span m="129970">rules</span> <span m="130360">of</span>
  <span m="130449">the</span> <span m="130509">chain.</span> <span m="131260">But</span>
  <span m="131470">assuming</span> <span m="131980">that</span> <span m="132310">it</span>
  <span m="132460">follows</span> <span m="132850">the</span> <span m="132940">rules,</span>
  <span m="133450">it's</span> <span m="133570">well</span> <span m="133780">formatted,</span>
  <span m="134710">it</span> <span m="134770">has</span> <span m="135040">the</span>
  <span m="135130">appropriate</span> <span m="135520">proof</span> <span m="135760">of</span>
  <span m="135850">work,</span> <span m="136220">et</span> <span m="136470">cetera,</span>
  <span m="137170">any</span> <span m="137470">one</span> <span m="137710">of</span>
  <span m="137830">us</span> <span m="138220">could</span> <span m="138430">submit</span>
  <span m="138700">a</span> <span m="138760">block</span> <span m="139090">to</span>
  <span m="139210">the</span> <span m="139300">Bitcoin</span> <span m="139900">blockchain.</span>
  <span m="140480">Right?</span> <span m="141310">There's</span> <span m="141550">no</span>
  <span m="142270">permissions</span> <span m="143350">on</span> <span m="143560">who</span>
  <span m="143770">is</span> <span m="143920">allowed</span> <span m="145180">and</span>
  <span m="145360">who</span> <span m="145540">isn't</span> <span m="145900">allowed</span>
  <span m="146440">to</span> <span m="146620">write</span> <span m="147040">to</span>
  <span m="147700">the</span> <span m="147790">Bitcoin</span> <span m="148215">blockchain.</span></p><p><span
  m="151720">Permissioned</span> <span m="152530">blockchains</span> <span m="153160">are</span>
  <span m="153280">a</span> <span m="153310">different</span> <span m="153610">story.</span>
  <span m="154640">These</span> <span m="154810">are</span> <span m="154870">more</span>
  <span m="155170">like</span> <span m="155470">distributed</span> <span m="156040">databases.</span>
  <span m="157210">The</span> <span m="157330">idea</span> <span m="157690">behind</span>
  <span m="158050">permissioned</span> <span m="158670">blockchains</span> <span m="159490">is</span>
  <span m="159670">that</span> <span m="159880">you</span> <span m="160000">choose</span>
  <span m="160480">a</span> <span m="160540">set</span> <span m="160810">of</span>
  <span m="160960">actors</span> <span m="161500">ahead</span> <span m="161740">of</span>
  <span m="161830">time,</span> <span m="162670">and</span> <span m="162880">only</span>
  <span m="163360">those</span> <span m="163660">actors</span> <span m="164410">are</span>
  <span m="164530">allowed</span> <span m="165430">to</span> <span m="165610">write</span>
  <span m="166390">to</span> <span m="166570">the</span> <span m="166660">blockchain.</span>
  <span m="167590">So</span> <span m="167950">you</span> <span m="168070">can't</span>
  <span m="168310">just</span> <span m="168520">have</span> <span m="168790">anyone</span>
  <span m="169240">willy-nilly</span> <span m="169870">spinning</span> <span m="170320">up</span>
  <span m="170680">a</span> <span m="170740">mining</span> <span m="171100">node,</span>
  <span m="171490">or</span> <span m="171580">spinning</span> <span m="171940">up</span>
  <span m="172060">a</span> <span m="172120">node</span> <span m="172330">in</span>
  <span m="172420">the</span> <span m="172480">system,</span> <span m="173440">and</span>
  <span m="173740">submitting</span> <span m="174340">transactions</span> <span m="175090">and</span>
  <span m="175180">things</span> <span m="175390">to</span> <span m="175450">the</span>
  <span m="175550">blockchain.</span></p><p><span m="176530">Usually,</span> <span
  m="177070">permissioned</span> <span m="177580">versus</span> <span m="177910">permissionless</span>
  <span m="178450">doesn't</span> <span m="178690">say</span> <span m="178810">anything</span>
  <span m="179080">about</span> <span m="179320">reads,</span> <span m="179950">and</span>
  <span m="180040">who</span> <span m="180160">can</span> <span m="180340">read</span>
  <span m="180550">the</span> <span m="180640">blockchain.</span> <span m="181030">We're</span>
  <span m="181120">really</span> <span m="181450">just</span> <span m="181600">talking</span>
  <span m="181960">about</span> <span m="182230">rights.</span> <span m="183400">So</span>
  <span m="184120">an</span> <span m="184240">important</span> <span m="184660">use--</span>
  <span m="185470">permissioned</span> <span m="185920">blockchains,</span> <span
  m="186730">I</span> <span m="186790">think,</span> <span m="187060">are</span> <span
  m="187150">not</span> <span m="187480">really</span> <span m="187690">the</span>
  <span m="187750">focus</span> <span m="188350">of</span> <span m="188500">this</span>
  <span m="188740">course,</span> <span m="190210">in</span> <span m="190390">part</span>
  <span m="190780">because</span> <span m="191830">we</span> <span m="193000">take</span>
  <span m="193240">the</span> <span m="193330">position</span> <span m="193840">that</span>
  <span m="194110">the</span> <span m="194230">technology</span> <span m="194920">behind</span>
  <span m="195280">them</span> <span m="196410">is</span> <span m="196570">essentially</span>
  <span m="196990">distributed</span> <span m="197470">databases.</span> <span m="198490">And</span>
  <span m="198820">there's</span> <span m="199210">lovely</span> <span m="199630">courses</span>
  <span m="200110">out</span> <span m="200230">there</span> <span m="200470">on</span>
  <span m="200560">distributed</span> <span m="200980">databases.</span> <span m="201640">And</span>
  <span m="202240">there's</span> <span m="202390">a</span> <span m="202450">lot</span>
  <span m="202630">to</span> <span m="202750">learn</span> <span m="202930">about</span>
  <span m="203140">them,</span> <span m="203260">and</span> <span m="203350">they're</span>
  <span m="203440">very</span> <span m="203680">interesting,</span> <span m="204520">but</span>
  <span m="204730">they're</span> <span m="205000">not</span> <span m="205240">necessarily</span>
  <span m="206800">very</span> <span m="207130">closely</span> <span m="207700">related</span>
  <span m="208120">to</span> <span m="208300">cryptocurrencies</span> <span m="209200">and</span>
  <span m="209560">the</span> <span m="209680">designs</span> <span m="210100">of</span>
  <span m="210160">the</span> <span m="210250">past</span> <span m="210490">decade.</span></p><p><span
  m="213040">So</span> <span m="213100">that's</span> <span m="213370">the</span>
  <span m="213490">idea</span> <span m="213730">behind</span> <span m="213970">permissioned</span>
  <span m="214390">blockchains.</span> <span m="215200">Now,</span> <span m="216220">as</span>
  <span m="216400">I</span> <span m="216460">was</span> <span m="216580">saying,</span>
  <span m="216940">I</span> <span m="217000">think</span> <span m="217150">that</span>
  <span m="217340">there's</span> <span m="217660">a</span> <span m="217720">lot</span>
  <span m="218020">of</span> <span m="218110">use</span> <span m="218350">cases</span>
  <span m="218860">for</span> <span m="219010">permissioned</span> <span m="219450">blockchains.</span>
  <span m="219950">They're</span> <span m="220060">very</span> <span m="220270">useful.</span>
  <span m="221140">Distributed</span> <span m="221590">databases,</span> <span m="222130">in</span>
  <span m="222220">general,</span> <span m="222610">are</span> <span m="222700">very</span>
  <span m="222940">useful.</span> <span m="223450">And</span> <span m="223690">so</span>
  <span m="223900">let's</span> <span m="224140">talk</span> <span m="224350">about</span>
  <span m="224530">one</span> <span m="224650">of</span> <span m="224740">them.</span></p><p><span
  m="225190">And</span> <span m="225310">I'm</span> <span m="225400">going</span>
  <span m="225580">to</span> <span m="225970">interchangeably</span> <span m="226900">use</span>
  <span m="227200">permissioned</span> <span m="227800">blockchain</span> <span m="228460">and</span>
  <span m="228730">distributed</span> <span m="229420">ledger,</span> <span m="229780">here.</span>
  <span m="230470">Distributed</span> <span m="230950">ledger,</span> <span m="231730">permissioned</span>
  <span m="232120">blockchain,</span> <span m="232540">I'm</span> <span m="233230">sort</span>
  <span m="233410">of</span> <span m="233470">saying</span> <span m="233680">the</span>
  <span m="233740">same</span> <span m="233920">thing.</span> <span m="236400">So</span>
  <span m="236560">permissioned</span> <span m="236950">blockchains--</span> <span
  m="237400">any</span> <span m="237550">questions,</span> <span m="238150">before</span>
  <span m="238540">we</span> <span m="239020">dive</span> <span m="239410">into</span>
  <span m="239860">the</span> <span m="239980">use</span> <span m="240220">case</span>
  <span m="240520">in</span> <span m="240640">zkLedger,</span> <span m="241720">about</span>
  <span m="241930">permissioned</span> <span m="242320">blockchains?</span> <span
  m="244610">Get</span> <span m="244700">the</span> <span m="244820">idea?</span>
  <span m="245510">It's</span> <span m="245630">a</span> <span m="245690">whole</span>
  <span m="245810">bunch</span> <span m="246020">of</span> <span m="246080">people</span>
  <span m="246380">working</span> <span m="246680">together</span> <span m="247070">to</span>
  <span m="247160">construct</span> <span m="247610">a</span> <span m="247670">ledger.</span></p><p><span
  m="249560">So</span> <span m="249740">let's</span> <span m="249920">start</span>
  <span m="250310">with</span> <span m="250520">the</span> <span m="250610">structure</span>
  <span m="251180">of</span> <span m="251420">the</span> <span m="251540">financial</span>
  <span m="251990">system.</span> <span m="252750">And</span> <span m="252860">this</span>
  <span m="253040">is</span> <span m="253490">setting</span> <span m="253970">the</span>
  <span m="254090">use</span> <span m="254360">case</span> <span m="254780">for</span>
  <span m="254960">zkLedger,</span> <span m="255560">and</span> <span m="255680">what</span>
  <span m="255860">we</span> <span m="256010">were</span> <span m="256130">trying</span>
  <span m="256399">to</span> <span m="256490">do,</span> <span m="256700">and</span>
  <span m="256790">what</span> <span m="256910">we</span> <span m="257000">were</span>
  <span m="257089">trying</span> <span m="257329">to</span> <span m="257450">address.</span>
  <span m="258390">So</span> <span m="258529">to</span> <span m="258649">start</span>
  <span m="258920">with,</span> <span m="259279">there</span> <span m="259519">are</span>
  <span m="259700">dozens</span> <span m="260300">of</span> <span m="260420">very</span>
  <span m="260750">large</span> <span m="261380">investment</span> <span m="261860">banks</span>
  <span m="262790">that</span> <span m="263180">are</span> <span m="263300">trading</span>
  <span m="263930">securities,</span> <span m="264860">currencies,</span> <span m="265670">commodities,</span>
  <span m="266330">derivatives.</span> <span m="267770">Many</span> <span m="268220">of</span>
  <span m="268310">these</span> <span m="268490">things</span> <span m="268700">are</span>
  <span m="268760">traded</span> <span m="269270">on</span> <span m="269750">exchanges,</span>
  <span m="270470">regulated</span> <span m="270980">exchanges</span> <span m="271700">like</span>
  <span m="271970">NASDAQ</span> <span m="272570">or</span> <span m="272660">the</span>
  <span m="272720">New</span> <span m="272810">York</span> <span m="272960">Stock</span>
  <span m="273060">Exchange.</span></p><p><span m="274100">But</span> <span m="275000">up</span>
  <span m="275150">to</span> <span m="275330">40%</span> <span m="276530">are</span>
  <span m="276830">actually</span> <span m="277220">traded</span> <span m="277580">in</span>
  <span m="277790">unregulated</span> <span m="278420">fashion.</span> <span m="278870">They're</span>
  <span m="279020">done</span> <span m="279770">in</span> <span m="279890">a</span>
  <span m="279920">way</span> <span m="280070">that's</span> <span m="280250">called</span>
  <span m="280540">over-the-counter,</span> <span m="281690">meaning</span> <span
  m="282020">that</span> <span m="282200">there</span> <span m="282380">is</span>
  <span m="282650">no</span> <span m="282980">regulated</span> <span m="283760">exchange</span>
  <span m="284450">sitting</span> <span m="284690">in</span> <span m="284750">the</span>
  <span m="284840">middle</span> <span m="285560">facilitating</span> <span m="286400">these</span>
  <span m="286580">trades.</span> <span m="287090">Instead,</span> <span m="288530">the</span>
  <span m="288680">banks,</span> <span m="289070">the</span> <span m="289220">entities,</span>
  <span m="289850">trade</span> <span m="290270">amongst</span> <span m="290660">themselves</span>
  <span m="291140">in</span> <span m="291480">a</span> <span m="291530">slightly</span>
  <span m="291890">more</span> <span m="292100">ad</span> <span m="292310">hoc</span>
  <span m="292520">fashion.</span></p><p><span m="294260">This</span> <span m="294440">represents</span>
  <span m="295010">trillions</span> <span m="295490">of</span> <span m="295580">dollars</span>
  <span m="296240">of</span> <span m="296390">the</span> <span m="296480">economy.</span>
  <span m="297920">And</span> <span m="298220">just</span> <span m="298460">to</span>
  <span m="298550">give</span> <span m="298730">you</span> <span m="298910">a</span>
  <span m="298970">sense</span> <span m="299270">of</span> <span m="299330">scale,</span>
  <span m="300140">the</span> <span m="300230">time</span> <span m="300620">frequency</span>
  <span m="301070">we're</span> <span m="301190">dealing,</span> <span m="301460">with</span>
  <span m="301580">we're</span> <span m="301700">not</span> <span m="302030">talking</span>
  <span m="302420">about</span> <span m="302600">high-frequency</span> <span m="303230">trading.</span>
  <span m="303800">That's</span> <span m="304010">not</span> <span m="304310">the</span>
  <span m="304430">use</span> <span m="304670">case</span> <span m="304930">that</span>
  <span m="305070">zkLedger</span> <span m="305330">is</span> <span m="305660">targeting.</span>
  <span m="306960">We're</span> <span m="307100">thinking</span> <span m="307400">like</span>
  <span m="307580">10s</span> <span m="307910">of</span> <span m="308000">trades</span>
  <span m="308360">a</span> <span m="308390">minute.</span></p><p><span m="308780">These</span>
  <span m="308960">are</span> <span m="309020">things</span> <span m="309260">that</span>
  <span m="310430">are</span> <span m="310640">done</span> <span m="310820">electronically.</span>
  <span m="311690">It's</span> <span m="311900">not</span> <span m="312110">like</span>
  <span m="312200">people</span> <span m="312470">are--</span> <span m="312980">people</span>
  <span m="313250">might</span> <span m="313460">be</span> <span m="313550">calling</span>
  <span m="313850">each</span> <span m="314030">other</span> <span m="314240">up</span>
  <span m="314330">to</span> <span m="314450">arrange</span> <span m="314720">these</span>
  <span m="314870">trades,</span> <span m="315230">but</span> <span m="315500">oftentimes</span>
  <span m="316010">they're</span> <span m="316100">done</span> <span m="316250">electronically.</span>
  <span m="317250">But</span> <span m="317330">we're</span> <span m="317450">not</span>
  <span m="317870">considering</span> <span m="318410">high-frequency</span> <span
  m="318950">trading.</span></p><p><span m="320540">So</span> <span m="321980">a</span>
  <span m="322040">useful</span> <span m="322670">abstraction</span> <span m="324650">for</span>
  <span m="324860">thinking</span> <span m="325190">about</span> <span m="325760">a</span>
  <span m="326180">table</span> <span m="326660">of</span> <span m="326750">these</span>
  <span m="326960">trades</span> <span m="327950">is</span> <span m="328310">a</span>
  <span m="328370">transaction</span> <span m="328910">ledger.</span> <span m="329510">So</span>
  <span m="329900">each</span> <span m="330170">row</span> <span m="330800">in</span>
  <span m="331310">the</span> <span m="331430">ledger</span> <span m="331850">is</span>
  <span m="332210">a</span> <span m="332300">transaction,</span> <span m="333170">transferring</span>
  <span m="333890">assets</span> <span m="334310">from</span> <span m="334490">one</span>
  <span m="334700">bank</span> <span m="334910">to</span> <span m="335060">another.</span>
  <span m="335690">So</span> <span m="335810">this</span> <span m="335930">should</span>
  <span m="336110">be</span> <span m="336260">very</span> <span m="336500">familiar</span>
  <span m="336890">to</span> <span m="336980">everyone.</span></p><p><span m="337970">It</span>
  <span m="338090">looks</span> <span m="338300">a</span> <span m="338360">little</span>
  <span m="338600">bit</span> <span m="338720">different</span> <span m="339170">than</span>
  <span m="339620">things</span> <span m="339890">like</span> <span m="340070">Bitcoin,</span>
  <span m="340640">because</span> <span m="342560">since</span> <span m="342890">this</span>
  <span m="343250">is</span> <span m="345080">a</span> <span m="345110">ledger</span>
  <span m="345590">designed</span> <span m="346340">for</span> <span m="346490">the</span>
  <span m="346970">existing</span> <span m="347420">financial</span> <span m="347930">system,</span>
  <span m="348740">we</span> <span m="348860">know</span> <span m="349160">who</span>
  <span m="349280">the</span> <span m="349430">entities</span> <span m="349880">are.</span>
  <span m="350510">They</span> <span m="350660">have</span> <span m="350840">names.</span>
  <span m="351530">They're</span> <span m="351680">regulated.</span> <span m="353165">They</span>
  <span m="353660">have</span> <span m="353810">companies</span> <span m="354260">behind</span>
  <span m="354590">them.</span> <span m="354740">We're</span> <span m="354830">not</span>
  <span m="355010">talking</span> <span m="355730">just</span> <span m="356150">about</span>
  <span m="357140">arbitrary</span> <span m="357590">public</span> <span m="357920">keys.</span></p><p><span
  m="359180">So</span> <span m="359390">each</span> <span m="359630">row in</span>
  <span m="359840">the</span> <span m="359900">ledger</span> <span m="360170">is</span>
  <span m="360260">a</span> <span m="360320">transaction.</span> <span m="361190">So</span>
  <span m="361400">here,</span> <span m="361680">Citibank</span> <span m="362240">is</span>
  <span m="362390">transferring</span> <span m="363560">a</span> <span m="363620">million</span>
  <span m="364100">dollars.</span> <span m="364730">So</span> <span m="364880">that's</span>
  <span m="365120">another</span> <span m="365390">thing</span> <span m="365540">that's</span>
  <span m="365690">very</span> <span m="365870">different</span> <span m="366140">than</span>
  <span m="366230">cryptocurrencies.</span> <span m="367190">Here</span> <span m="367370">we</span>
  <span m="367520">have</span> <span m="367670">multiple</span> <span m="368240">different</span>
  <span m="368570">assets</span> <span m="369020">being</span> <span m="369230">recorded</span>
  <span m="369620">in</span> <span m="369680">the</span> <span m="369770">ledger.</span></p><p><span
  m="370530">So</span> <span m="370970">we're</span> <span m="371120">not</span> <span
  m="371510">talking</span> <span m="371930">about</span> <span m="372320">a</span>
  <span m="372380">ledger</span> <span m="373280">with</span> <span m="373490">a</span>
  <span m="373520">native</span> <span m="374090">asset,</span> <span m="374480">necessarily.</span>
  <span m="375080">This</span> <span m="375230">is</span> <span m="375320">not</span>
  <span m="375500">a</span> <span m="375560">cryptocurrency.</span> <span m="376250">Really</span>
  <span m="376670">think</span> <span m="376880">about</span> <span m="377090">this</span>
  <span m="377300">like</span> <span m="377570">a</span> <span m="377630">table</span>
  <span m="378320">in</span> <span m="378440">a</span> <span m="378500">database</span>
  <span m="379370">recording</span> <span m="379940">transactions.</span> <span m="380720">Those</span>
  <span m="380900">transactions</span> <span m="382100">might</span> <span m="382310">be</span>
  <span m="382430">in</span> <span m="382520">dollars,</span> <span m="383030">or</span>
  <span m="383120">euros,</span> <span m="383780">or</span> <span m="384410">municipal</span>
  <span m="384860">bonds,</span> <span m="385610">or</span> <span m="386000">securities,</span>
  <span m="386810">or</span> <span m="386900">shares--</span> <span m="387780">they</span>
  <span m="387920">could</span> <span m="388040">be</span> <span m="388160">anything,</span>
  <span m="388640">right?</span> <span m="388940">So</span> <span m="389060">we're</span>
  <span m="389150">just</span> <span m="389540">recording</span> <span m="390380">transactions.</span></p><p><span
  m="391610">So</span> <span m="391910">Citibank</span> <span m="392420">is</span>
  <span m="392570">transferring</span> <span m="392990">a</span> <span m="393050">million
  dollars</span> <span m="393320">to</span> <span m="393800">Goldman</span> <span
  m="394070">Sachs.</span> <span m="394550">JP</span> <span m="394910">Morgan</span>
  <span m="395780">is</span> <span m="396170">transferring</span> <span m="396620">money</span>
  <span m="396890">to</span> <span m="397250">UBS</span> <span m="398000">and</span>
  <span m="398360">to</span> <span m="398600">Barclays.</span> <span m="399590">OK?</span>
  <span m="400970">So</span> <span m="402530">as</span> <span m="402800">with</span>
  <span m="402920">cryptocurrencies,</span> <span m="404030">I</span> <span m="404120">think,</span>
  <span m="404810">cryptocurrencies</span> <span m="405680">have</span> <span m="406310">inspired</span>
  <span m="407060">people</span> <span m="407900">to</span> <span m="408110">reconsider</span>
  <span m="408890">the</span> <span m="409010">case</span> <span m="409520">of</span>
  <span m="410570">a</span> <span m="410600">distributed</span> <span m="411080">database</span>
  <span m="411620">as</span> <span m="411890">a</span> <span m="411950">ledger</span>
  <span m="412460">that</span> <span m="412640">multiple</span> <span m="413030">entities</span>
  <span m="413390">can</span> <span m="413540">write</span> <span m="413750">to.</span></p><p><span
  m="414410">And</span> <span m="415490">part</span> <span m="415700">of</span> <span
  m="415760">that</span> <span m="415880">consideration</span> <span m="416690">involves</span>
  <span m="417260">thinking</span> <span m="417560">about</span> <span m="417950">digital</span>
  <span m="418370">signatures.</span> <span m="419330">So</span> <span m="420590">maybe</span>
  <span m="420860">these</span> <span m="421040">banks</span> <span m="421400">have</span>
  <span m="422580">public,</span> <span m="422870">private</span> <span m="423200">key</span>
  <span m="423380">pairs.</span> <span m="424400">And</span> <span m="424880">perhaps</span>
  <span m="425480">they</span> <span m="425690">use</span> <span m="426080">their</span>
  <span m="426620">keys</span> <span m="427070">to</span> <span m="427250">indicate</span>
  <span m="428090">consent</span> <span m="428720">on</span> <span m="428840">the</span>
  <span m="428930">transaction,</span> <span m="429710">right?</span> <span m="430400">This</span>
  <span m="430610">is</span> <span m="430700">something</span> <span m="431000">that's</span>
  <span m="431540">done</span> <span m="431840">under</span> <span m="432080">the</span>
  <span m="432170">hood</span> <span m="432380">right</span> <span m="432590">now,</span>
  <span m="433340">when</span> <span m="433520">you</span> <span m="433610">think</span>
  <span m="433790">about</span> <span m="433970">the</span> <span m="434060">protocols</span>
  <span m="434600">we</span> <span m="434720">use</span> <span m="434900">to</span>
  <span m="434990">exchange</span> <span m="435410">data.</span></p><p><span m="435760">But</span>
  <span m="435890">it's</span> <span m="436010">not</span> <span m="436160">necessarily</span>
  <span m="436640">done</span> <span m="436850">explicitly</span> <span m="438110">when</span>
  <span m="438260">creating</span> <span m="438710">these</span> <span m="438890">distributed</span>
  <span m="439340">databases.</span> <span m="439850">So</span> <span m="440600">they</span>
  <span m="440750">can</span> <span m="440870">use</span> <span m="441200">their</span>
  <span m="442430">keys</span> <span m="442940">to</span> <span m="443810">attach</span>
  <span m="444170">signatures</span> <span m="444680">to</span> <span m="444770">the</span>
  <span m="444860">transaction</span> <span m="445490">to</span> <span m="445640">indicate</span>
  <span m="446450">a</span> <span m="446540">consent</span> <span m="447020">to</span>
  <span m="447170">transfer</span> <span m="447800">for</span> <span m="447950">security.</span>
  <span m="449150">Now,</span> <span m="449570">this</span> <span m="449750">ledger</span>
  <span m="451220">might</span> <span m="451580">be</span> <span m="451700">maintained</span>
  <span m="452360">by</span> <span m="452570">a</span> <span m="452600">third</span>
  <span m="452870">party,</span> <span m="453380">or</span> <span m="454160">it</span>
  <span m="454310">could</span> <span m="454550">be</span> <span m="454860">a distributed</span>
  <span m="455270">database,</span> <span m="455690">a</span> <span m="455750">permissioned</span>
  <span m="456530">blockchain</span> <span m="457280">that</span> <span m="457430">is</span>
  <span m="458060">run</span> <span m="458420">by</span> <span m="458720">the</span>
  <span m="458810">transacting</span> <span m="459380">parties.</span></p><p><span
  m="462800">So</span> <span m="463130">there</span> <span m="463340">are</span> <span
  m="463430">some</span> <span m="464030">important</span> <span m="464540">financial</span>
  <span m="465170">invariants</span> <span m="465830">that</span> <span m="466280">you</span>
  <span m="466370">want</span> <span m="466580">to</span> <span m="466640">maintain</span>
  <span m="467030">here</span> <span m="467270">to</span> <span m="467570">verify</span>
  <span m="468080">that</span> <span m="468260">transactions</span> <span m="468830">are</span>
  <span m="468890">happening</span> <span m="469160">correctly,</span> <span m="471670">that</span>
  <span m="472190">they're</span> <span m="472310">valid,</span> <span m="472940">that</span>
  <span m="473150">assets</span> <span m="473500">aren't</span> <span m="473620">created</span>
  <span m="473900">out</span> <span m="473990">of</span> <span m="474080">nowhere.</span>
  <span m="475030">So</span> <span m="476900">one</span> <span m="477110">of</span>
  <span m="477200">them</span> <span m="477440">is</span> <span m="477620">consent</span>
  <span m="477950">to</span> <span m="478040">transfer.</span> <span m="478610">And</span>
  <span m="478730">we</span> <span m="478880">use</span> <span m="479150">these</span>
  <span m="479300">signatures</span> <span m="479810">for</span> <span m="479930">that.</span></p><p><span
  m="481070">Another</span> <span m="481460">important</span> <span m="482240">thing</span>
  <span m="482450">to</span> <span m="482570">verify,</span> <span m="483150">another</span>
  <span m="483380">important</span> <span m="483680">invariant,</span> <span m="484130">is</span>
  <span m="484310">that</span> <span m="484460">the</span> <span m="484550">person</span>
  <span m="484940">doing</span> <span m="485150">the</span> <span m="485210">transacting</span>
  <span m="485900">actually</span> <span m="486410">has</span> <span m="486830">the</span>
  <span m="486980">assets</span> <span m="487430">to</span> <span m="487550">transfer.</span>
  <span m="488450">That</span> <span m="489200">they're</span> <span m="489380">not</span>
  <span m="489620">making</span> <span m="489950">up</span> <span m="490070">assets</span>
  <span m="490400">out</span> <span m="490490">of</span> <span m="490550">nowhere,</span>
  <span m="490950">or</span> <span m="491000">they're</span> <span m="491120">not</span>
  <span m="491330">double-spending--</span> <span m="492110">that</span> <span m="492230">there</span>
  <span m="492350">isn't</span> <span m="492530">something</span> <span m="492800">incorrect</span>
  <span m="493220">happening.</span> <span m="495440">And</span> <span m="495560">then,</span>
  <span m="495890">that</span> <span m="496100">assets</span> <span m="496460">are</span>
  <span m="496550">neither</span> <span m="496820">created</span> <span m="497300">nor</span>
  <span m="497510">destroyed.</span> <span m="497910">That</span> <span m="498020">we</span>
  <span m="498080">have</span> <span m="498200">conservation</span> <span m="498860">of</span>
  <span m="498950">assets.</span></p><p><span m="499360">So</span> <span m="499460">these</span>
  <span m="499520">are</span> <span m="499580">important</span> <span m="500300">financial</span>
  <span m="500780">invariants</span> <span m="501260">to</span> <span m="501350">maintain.</span>
  <span m="502580">This</span> <span m="502730">looks</span> <span m="503030">a</span>
  <span m="503060">lot</span> <span m="503360">like</span> <span m="503720">what</span>
  <span m="504800">the</span> <span m="504990">invariants</span> <span m="505430">are</span>
  <span m="505580">that</span> <span m="505700">we're</span> <span m="505790">trying</span>
  <span m="506060">to</span> <span m="506120">maintain</span> <span m="506520">in</span>
  <span m="506600">a</span> <span m="506630">cryptocurrency</span> <span m="507380">like</span>
  <span m="507560">Bitcoin</span> <span m="507890">or</span> <span m="507950">Ethereum,</span>
  <span m="508490">except</span> <span m="508790">this</span> <span m="508970">was</span>
  <span m="509300">with</span> <span m="509480">multiple</span> <span m="509960">assets,</span>
  <span m="510830">and</span> <span m="511250">we</span> <span m="511760">know</span>
  <span m="512030">who</span> <span m="512179">the</span> <span m="512270">people</span>
  <span m="512600">are</span> <span m="513140">involved.</span></p><p><span m="514350">Now,</span>
  <span m="517340">if</span> <span m="517880">this</span> <span m="518059">ledger</span>
  <span m="518600">were</span> <span m="518780">being</span> <span m="519049">maintained</span>
  <span m="519650">by</span> <span m="520130">an</span> <span m="520280">exchange,</span>
  <span m="521429">then</span> <span m="521929">the</span> <span m="522049">exchange</span>
  <span m="522710">would</span> <span m="522890">be</span> <span m="523010">responsible</span>
  <span m="524150">for</span> <span m="524540">verifying</span> <span m="525050">and</span>
  <span m="525140">validating</span> <span m="525650">that</span> <span m="525770">all</span>
  <span m="525890">of</span> <span m="525980">these</span> <span m="526130">transactions</span>
  <span m="526670">are</span> <span m="526760">correct.</span> <span m="527810">If</span>
  <span m="528200">this</span> <span m="528410">ledger</span> <span m="528800">is</span>
  <span m="528950">being</span> <span m="529160">maintained</span> <span m="529640">by</span>
  <span m="530030">the</span> <span m="530120">participants,</span> <span m="530960">it's</span>
  <span m="531140">a</span> <span m="531170">permissioned</span> <span m="531560">blockchain,</span>
  <span m="532520">then</span> <span m="533360">everyone</span> <span m="533960">can</span>
  <span m="534140">verify</span> <span m="534740">and</span> <span m="534830">validate</span>
  <span m="535400">that</span> <span m="535550">these</span> <span m="535760">invariants</span>
  <span m="536210">are</span> <span m="536300">being</span> <span m="536480">maintained</span>
  <span m="537290">by</span> <span m="537470">looking</span> <span m="538040">at</span>
  <span m="538220">the</span> <span m="538310">blockchain,</span> <span m="538940">by</span>
  <span m="539060">checking</span> <span m="539480">the</span> <span m="539570">signatures,</span>
  <span m="540320">right?</span></p><p><span m="542210">So</span> <span m="542360">that's</span>
  <span m="542630">great,</span> <span m="543590">except</span> <span m="544250">for</span>
  <span m="544460">the</span> <span m="544550">fact</span> <span m="545240">that</span>
  <span m="547690">privacy</span> <span m="548470">is</span> <span m="548650">really,</span>
  <span m="549230">really</span> <span m="549520">important.</span> <span m="550480">And</span>
  <span m="551080">quite</span> <span m="551560">a</span> <span m="551620">bit</span>
  <span m="551830">of</span> <span m="551920">data,</span> <span m="552760">and</span>
  <span m="552940">quite</span> <span m="553210">a</span> <span m="553270">bit</span>
  <span m="553360">of</span> <span m="553450">sensitive</span> <span m="553870">information,</span>
  <span m="554530">is</span> <span m="554710">actually</span> <span m="555070">leaked</span>
  <span m="555490">by</span> <span m="555640">looking</span> <span m="556090">at</span>
  <span m="556180">these</span> <span m="556360">transactions.</span> <span m="557320">So</span>
  <span m="557530">if</span> <span m="557680">we</span> <span m="557800">want</span>
  <span m="558070">to</span> <span m="558190">be</span> <span m="558340">able</span>
  <span m="558610">to</span> <span m="558730">maintain</span> <span m="559210">financial</span>
  <span m="559720">invariants,</span> <span m="560350">if</span> <span m="560410">we</span>
  <span m="560500">want</span> <span m="560680">to</span> <span m="560740">be</span>
  <span m="560830">able</span> <span m="561010">to</span> <span m="561160">check</span>
  <span m="561430">and</span> <span m="561520">make</span> <span m="561670">sure</span>
  <span m="562240">that</span> <span m="562390">the</span> <span m="562450">ledger</span>
  <span m="562650">is</span> <span m="562780">correct--</span> <span m="563390">and</span>
  <span m="563500">I</span> <span m="563560">mean,</span> <span m="563780">this</span>
  <span m="563830">is</span> <span m="564130">the</span> <span m="564220">whole</span>
  <span m="564460">point</span> <span m="564880">of</span> <span m="564970">blockchains,</span>
  <span m="565550">is</span> <span m="565720">that</span> <span m="565810">everyone</span>
  <span m="566200">can</span> <span m="566530">verify,</span> <span m="567070">and</span>
  <span m="567160">validate,</span> <span m="568060">and</span> <span m="568210">reconcile</span>
  <span m="569920">real</span> <span m="570190">time.</span> <span m="571030">Then</span>
  <span m="572400">in</span> <span m="572560">the</span> <span m="572680">act</span>
  <span m="573010">of</span> <span m="573130">looking</span> <span m="573490">at</span>
  <span m="573550">those</span> <span m="574150">transactions,</span> <span m="575020">you're</span>
  <span m="575440">actually</span> <span m="575740">finding</span> <span m="576070">out</span>
  <span m="576280">really</span> <span m="576730">sensitive</span> <span m="577300">information</span>
  <span m="578320">about</span> <span m="578620">banks'</span> <span m="578890">trading</span>
  <span m="579280">strategy--</span> <span m="579790">about</span> <span m="579970">their</span>
  <span m="580090">intellectual</span> <span m="580600">property.</span> <span m="581340">OK?</span></p><p><span
  m="582910">For</span> <span m="583060">example,</span> <span m="583700">a</span>
  <span m="583800">large</span> <span m="584110">trade</span> <span m="584530">might</span>
  <span m="584770">indicate</span> <span m="585280">that</span> <span m="585430">a</span>
  <span m="585490">bank</span> <span m="585820">has</span> <span m="586660">decided</span>
  <span m="587230">to</span> <span m="587560">get</span> <span m="587740">out</span>
  <span m="588040">of</span> <span m="588190">a</span> <span m="588250">position.</span>
  <span m="589450">Other</span> <span m="589690">banks</span> <span m="589990">could</span>
  <span m="590140">learn</span> <span m="590350">about</span> <span m="590590">this,</span>
  <span m="591250">notice</span> <span m="591670">it</span> <span m="591760">on</span>
  <span m="591850">the</span> <span m="591940">blockchain</span> <span m="592370">as</span>
  <span m="592440">they're</span> <span m="592500">validating</span> <span m="592960">transactions,</span>
  <span m="593680">and</span> <span m="593920">try</span> <span m="594100">to</span>
  <span m="594190">follow</span> <span m="594490">suit,</span> <span m="595750">driving</span>
  <span m="596110">down</span> <span m="596290">the</span> <span m="596350">price.</span>
  <span m="597280">So</span> <span m="598000">privacy,</span> <span m="598510">especially</span>
  <span m="598990">in</span> <span m="599110">this</span> <span m="599260">type</span>
  <span m="599440">of</span> <span m="599500">context,</span> <span m="599980">is</span>
  <span m="600070">really</span> <span m="600280">important.</span> <span m="600730">And</span>
  <span m="601120">I'm</span> <span m="601270">sure</span> <span m="601510">you</span>
  <span m="601660">can</span> <span m="601810">imagine</span> <span m="602830">a</span>
  <span m="602890">lot</span> <span m="603100">of</span> <span m="603310">other</span>
  <span m="603610">different</span> <span m="603940">types</span> <span m="604240">of</span>
  <span m="604300">context</span> <span m="604810">in</span> <span m="604930">which</span>
  <span m="605110">privacy</span> <span m="605590">is</span> <span m="605680">important</span>
  <span m="606070">as</span> <span m="606190">well,</span> <span m="606640">right?</span></p><p><span
  m="608380">So</span> <span m="608890">we</span> <span m="609040">don't</span> <span
  m="609220">want</span> <span m="609400">to</span> <span m="609460">be</span> <span
  m="609760">in</span> <span m="609940">this</span> <span m="610420">situation</span>
  <span m="611650">where</span> <span m="612250">we</span> <span m="612430">have</span>
  <span m="612670">to</span> <span m="612760">choose</span> <span m="613540">between</span>
  <span m="614830">privacy</span> <span m="616000">and</span> <span m="616720">being</span>
  <span m="617050">able</span> <span m="617410">to</span> <span m="617590">validate</span>
  <span m="618160">what's</span> <span m="618340">going</span> <span m="618640">on.</span>
  <span m="619100">Right?</span> <span m="619720">So</span> <span m="620860">even</span>
  <span m="621190">if</span> <span m="621280">we</span> <span m="621430">were</span>
  <span m="621520">to</span> <span m="621640">use</span> <span m="621940">a</span>
  <span m="622000">trusted</span> <span m="622360">third</span> <span m="622540">party</span>
  <span m="622870">like</span> <span m="623080">an</span> <span m="623170">exchange,</span>
  <span m="624130">we</span> <span m="624280">still</span> <span m="624580">wouldn't</span>
  <span m="625090">have</span> <span m="625600">privacy,</span> <span m="626230">necessarily,</span>
  <span m="626740">because</span> <span m="626950">the</span> <span m="627040">exchange</span>
  <span m="627580">would</span> <span m="627730">be</span> <span m="627880">looking</span>
  <span m="628210">at</span> <span m="628270">everything</span> <span m="628660">in</span>
  <span m="628780">the</span> <span m="628870">ledger.</span></p><p><span m="629660">So</span>
  <span m="630040">that's</span> <span m="630790">the</span> <span m="630880">goal</span>
  <span m="631180">here</span> <span m="631450">that</span> <span m="631600">we're</span>
  <span m="631690">trying</span> <span m="632110">to</span> <span m="632590">achieve.</span>
  <span m="632960">We're</span> <span m="633070">trying</span> <span m="633280">to</span>
  <span m="633340">achieve</span> <span m="634120">this</span> <span m="634300">goal</span>
  <span m="634510">where</span> <span m="634630">we</span> <span m="634750">want</span>
  <span m="634960">to</span> <span m="635020">be</span> <span m="635170">able</span>
  <span m="635380">to</span> <span m="635500">publicly</span> <span m="636010">verify</span>
  <span m="636520">and</span> <span m="636640">validate</span> <span m="637510">what's</span>
  <span m="637720">happening</span> <span m="638110">in</span> <span m="638200">the</span>
  <span m="638290">ledger,</span> <span m="639070">and</span> <span m="639400">at</span>
  <span m="639520">the</span> <span m="639640">same</span> <span m="640000">time,</span>
  <span m="641350">obtain</span> <span m="641800">some</span> <span m="642250">amount</span>
  <span m="642490">of</span> <span m="642550">privacy</span> <span m="643240">for</span>
  <span m="643390">transactions.</span> <span m="643990">We</span> <span m="644080">don't</span>
  <span m="644230">want</span> <span m="644410">all</span> <span m="644560">transactions</span>
  <span m="645130">to</span> <span m="645220">be</span> <span m="645340">public</span>
  <span m="645760">to</span> <span m="646000">whoever</span> <span m="646480">is</span>
  <span m="646600">maintaining</span> <span m="647110">the</span> <span m="647200">ledger,</span>
  <span m="647590">be</span> <span m="647770">that</span> <span m="648280">a</span>
  <span m="648430">third</span> <span m="648640">party</span> <span m="648910">exchange</span>
  <span m="649600">or</span> <span m="650020">a</span> <span m="650080">set</span>
  <span m="650260">of</span> <span m="650320">banks.</span></p><p><span m="651880">So</span>
  <span m="652180">I'm</span> <span m="652300">just</span> <span m="652420">going</span>
  <span m="652490">to</span> <span m="652570">pause</span> <span m="652870">right</span>
  <span m="653050">there</span> <span m="653530">and--</span> <span m="656911">do</span>
  <span m="657330">we</span> <span m="657660">get</span> <span m="657930">the</span>
  <span m="658050">setup,</span> <span m="658470">here?</span> <span m="658710">Privacy</span>
  <span m="659790">versus</span> <span m="660150">verification--</span> <span m="661530">we</span>
  <span m="661680">want</span> <span m="661860">both.</span> <span m="663030">Any</span>
  <span m="663180">questions</span> <span m="663750">about</span> <span m="663990">that?</span>
  <span m="665220">Yes?</span></p><p><span m="665940">AUDIENCE:</span> <span m="665995">I</span>
  <span m="666050">was</span> <span m="666210">confused</span> <span m="666580">as
  to how you</span> <span m="667320">verify</span> <span m="668535">that</span> <span
  m="668970">people--</span> <span m="669330">transactions</span> <span m="669810">are</span>
  <span m="670270">correct</span> <span m="670420">in their</span> <span m="670865">account
  balances?</span> <span m="671310">It's like there's</span> <span m="671755">no</span>
  <span m="672200">native assets</span> <span m="672645">supplied.</span></p><p><span
  m="673090">NEHA NARULA:</span> <span m="673285">Yeah,</span> <span m="673480">that's</span>
  <span m="673690">a</span> <span m="673750">great</span> <span m="673930">question.</span>
  <span m="674690">So</span> <span m="675940">I</span> <span m="676390">have</span>
  <span m="676630">dollars</span> <span m="677050">and</span> <span m="677140">euros</span>
  <span m="677500">here,</span> <span m="677830">right?</span> <span m="678160">How</span>
  <span m="678430">do</span> <span m="678490">you</span> <span m="678610">know</span>
  <span m="678850">that</span> <span m="679030">Citibank</span> <span m="679480">actually</span>
  <span m="679900">has</span> <span m="680170">those</span> <span m="680380">dollars</span>
  <span m="680830">to</span> <span m="680950">transfer</span> <span m="681820">to</span>
  <span m="681940">Goldman</span> <span m="682300">Sachs?</span> <span m="682950">Right?</span>
  <span m="683320">Where</span> <span m="683530">does</span> <span m="683680">that</span>
  <span m="683830">come</span> <span m="684040">from?</span></p><p><span m="684910">Notice</span>
  <span m="685240">how</span> <span m="685360">this</span> <span m="685540">is</span>
  <span m="685660">transaction</span> <span m="686200">number</span> <span m="686440">90.</span>
  <span m="688090">I'm</span> <span m="688240">assuming</span> <span m="688870">that</span>
  <span m="689020">there's</span> <span m="689230">a</span> <span m="689260">transaction</span>
  <span m="689950">up</span> <span m="690120">here--</span> <span m="690340">this</span>
  <span m="690490">is</span> <span m="690580">just</span> <span m="690760">a</span>
  <span m="690790">subset</span> <span m="691210">of</span> <span m="691270">the</span>
  <span m="691360">ledger.</span> <span m="692080">But</span> <span m="692710">as</span>
  <span m="692890">you'll</span> <span m="693040">see</span> <span m="693280">in</span>
  <span m="693370">a</span> <span m="693400">moment,</span> <span m="694900">we</span>
  <span m="695260">think</span> <span m="695530">about</span> <span m="697060">this</span>
  <span m="697270">role</span> <span m="697750">of</span> <span m="698050">depositors</span>
  <span m="698920">who</span> <span m="699070">are</span> <span m="699130">allowed</span>
  <span m="699610">to</span> <span m="699790">deposit</span> <span m="700480">assets</span>
  <span m="700900">into</span> <span m="701080">the</span> <span m="701200">ledger.</span>
  <span m="701860">And</span> <span m="701980">so</span> <span m="702100">I'm</span>
  <span m="702250">assuming</span> <span m="702760">there's</span> <span m="702910">a</span>
  <span m="702970">transaction</span> <span m="703780">up</span> <span m="703960">here</span>
  <span m="704170">somewhere</span> <span m="705070">which</span> <span m="705790">in</span>
  <span m="705940">a</span> <span m="706930">provable</span> <span m="707440">way</span>
  <span m="707740">shows</span> <span m="708580">that</span> <span m="708760">someone</span>
  <span m="709240">we</span> <span m="709360">trust</span> <span m="710200">to</span>
  <span m="710320">deposit</span> <span m="710890">assets</span> <span m="711280">into</span>
  <span m="711460">the</span> <span m="711550">ledger</span> <span m="712260">gave</span>
  <span m="712590">Citibank</span> <span m="713440">the</span> <span m="713530">dollars</span>
  <span m="714070">necessary</span> <span m="714700">for</span> <span m="714850">them</span>
  <span m="715240">to</span> <span m="715600">give</span> <span m="715780">to</span>
  <span m="715900">Goldman</span> <span m="716200">Sachs.</span></p><p><span m="716710">But</span>
  <span m="716860">you're</span> <span m="716980">absolutely</span> <span m="717460">right.</span>
  <span m="718070">If</span> <span m="718120">the</span> <span m="718270">asset</span>
  <span m="718780">isn't</span> <span m="719110">native</span> <span m="719800">to</span>
  <span m="719980">the</span> <span m="720100">ledger,</span> <span m="721000">then</span>
  <span m="721600">you</span> <span m="721930">do</span> <span m="722140">have</span>
  <span m="722350">that</span> <span m="722530">connection</span> <span m="722980">to</span>
  <span m="723100">the</span> <span m="723190">real</span> <span m="723430">world,</span>
  <span m="723820">where</span> <span m="723940">you</span> <span m="724060">do</span>
  <span m="724210">need</span> <span m="724360">to</span> <span m="724420">apply</span>
  <span m="724720">some</span> <span m="724960">level</span> <span m="725260">of</span>
  <span m="725350">trust.</span> <span m="725680">The</span> <span m="725770">question,</span>
  <span m="726260">is</span> <span m="726520">it</span> <span m="726640">auditable?</span>
  <span m="727450">Can</span> <span m="727570">you</span> <span m="727660">at</span>
  <span m="727720">least</span> <span m="727930">track</span> <span m="728290">it</span>
  <span m="728380">back</span> <span m="728650">up</span> <span m="728770">to</span>
  <span m="728890">that</span> <span m="729040">point?</span> <span m="731440">Any</span>
  <span m="731590">other</span> <span m="731740">questions?</span></p><p><span m="734620">OK,</span>
  <span m="734840">great.</span> <span m="737575">So</span> <span m="737840">we</span>
  <span m="737990">want</span> <span m="738560">to</span> <span m="739070">do</span>
  <span m="739250">the</span> <span m="739340">following.</span> <span m="739800">We</span>
  <span m="739900">want</span> <span m="740000">to</span> <span m="740100">be</span>
  <span m="740200">able</span> <span m="740300">to</span> <span m="740400">verify</span>
  <span m="741320">that</span> <span m="741980">financial</span> <span m="742520">invariants</span>
  <span m="742970">are</span> <span m="743030">maintained,</span> <span m="743420">that</span>
  <span m="743510">things</span> <span m="743720">are</span> <span m="743810">correct</span>
  <span m="744260">while</span> <span m="744650">achieving</span> <span m="745040">privacy.</span>
  <span m="746180">So</span> <span m="746510">one</span> <span m="747140">good</span>
  <span m="747350">technique</span> <span m="747890">for</span> <span m="748040">achieving</span>
  <span m="748400">privacy</span> <span m="749210">is</span> <span m="749420">simply</span>
  <span m="749840">to</span> <span m="750290">encrypt</span> <span m="751100">or</span>
  <span m="751370">hide</span> <span m="752000">the</span> <span m="752690">transactions</span>
  <span m="753380">in</span> <span m="753470">the</span> <span m="753530">ledger,</span>
  <span m="754370">OK?</span> <span m="755250">So</span> <span m="757100">surprisingly,</span>
  <span m="758090">maybe,</span> <span m="758630">we</span> <span m="758930">actually</span>
  <span m="759530">know</span> <span m="760040">how</span> <span m="760460">to</span>
  <span m="760610">do</span> <span m="760880">this.</span> <span m="761780">And</span>
  <span m="762050">to,</span> <span m="762500">at</span> <span m="762620">the</span>
  <span m="762710">same</span> <span m="763070">time,</span> <span m="763970">still</span>
  <span m="764840">achieve</span> <span m="766160">checking</span> <span m="766550">of</span>
  <span m="766640">the</span> <span m="766730">financial</span> <span m="767120">invariants.</span></p><p><span
  m="768590">Here</span> <span m="768800">are</span> <span m="768860">two</span> <span
  m="769100">systems</span> <span m="769820">that</span> <span m="770120">actually</span>
  <span m="770510">achieve</span> <span m="770810">this.</span> <span m="771150">The</span>
  <span m="771250">first</span> <span m="771680">is</span> <span m="771980">Zerocash,</span>
  <span m="773120">which</span> <span m="773360">was</span> <span m="773600">implemented</span>
  <span m="774410">inside</span> <span m="774920">of</span> <span m="775040">Zcash,</span>
  <span m="775820">an</span> <span m="775940">anonymous</span> <span m="776440">cryptocurrency.</span>
  <span m="777650">In</span> <span m="777830">Zcash,</span> <span m="779030">transactions</span>
  <span m="779930">are</span> <span m="781670">completely</span> <span m="782090">hidden.</span>
  <span m="782460">They're</span> <span m="782480">completely</span> <span m="782840">opaque</span>
  <span m="783350">shielded</span> <span m="783740">transactions</span> <span m="784310">in</span>
  <span m="784420">Zcash.</span></p><p><span m="784550">Zcash</span> <span m="785120">has</span>
  <span m="785270">two</span> <span m="785990">transactions.</span> <span m="787190">Once</span>
  <span m="787490">set</span> <span m="787670">is</span> <span m="787850">public,</span>
  <span m="788270">like</span> <span m="788450">in</span> <span m="788540">Bitcoin.</span>
  <span m="788960">The</span> <span m="789080">other</span> <span m="789260">set</span>
  <span m="789620">are</span> <span m="789740">called</span> <span m="790220">shielded</span>
  <span m="790670">transactions.</span> <span m="791870">And</span> <span m="792590">in</span>
  <span m="792710">a</span> <span m="792770">shielded</span> <span m="793190">transaction,</span>
  <span m="793850">you</span> <span m="793970">don't</span> <span m="794150">know</span>
  <span m="794240">who</span> <span m="794330">the</span> <span m="794420">parties</span>
  <span m="794810">are</span> <span m="794930">who</span> <span m="795740">are</span>
  <span m="795860">involved.</span> <span m="796730">You</span> <span m="796850">don't</span>
  <span m="797030">know</span> <span m="797330">the</span> <span m="797480">amount</span>
  <span m="798020">of</span> <span m="798140">the</span> <span m="798260">asset</span>
  <span m="798740">that's</span> <span m="798980">transferred.</span> <span m="800630">But</span>
  <span m="800810">you</span> <span m="800930">can</span> <span m="801560">validate</span>
  <span m="802400">that</span> <span m="803060">this</span> <span m="803240">was</span>
  <span m="803420">correct,</span> <span m="803990">that</span> <span m="804740">financial</span>
  <span m="805190">invariants</span> <span m="805520">were</span> <span m="805640">maintained.</span></p><p><span
  m="807020">Zerocash</span> <span m="807890">and</span> <span m="808100">Zcash</span>
  <span m="808670">use</span> <span m="809120">a</span> <span m="809330">primitive</span>
  <span m="809720">called</span> <span m="811190">zero-knowledge</span> <span m="811610">proofs,</span>
  <span m="812060">and</span> <span m="812180">in</span> <span m="812270">particular,</span>
  <span m="812910">zk-SNARKS--</span> <span m="814250">zero</span> <span m="814490">knowledge</span>
  <span m="814940">succinct</span> <span m="815540">arguments</span> <span m="816080">of</span>
  <span m="816200">knowledge.</span> <span m="817520">Those</span> <span m="817710">were</span>
  <span m="817790">actually</span> <span m="818030">developed</span> <span m="819200">in</span>
  <span m="819320">part</span> <span m="819740">here</span> <span m="820040">at</span>
  <span m="820190">MIT.</span> <span m="822830">So</span> <span m="823790">using</span>
  <span m="824510">these</span> <span m="825080">really</span> <span m="825350">interesting</span>
  <span m="825770">cryptographic</span> <span m="826310">primitives,</span> <span
  m="827930">we're</span> <span m="828050">able</span> <span m="828350">to</span>
  <span m="828440">maintain</span> <span m="828890">financial</span> <span m="829310">invariance</span>
  <span m="829850">in</span> <span m="830030">Zcash.</span></p><p><span m="830750">There's</span>
  <span m="830900">another</span> <span m="831230">system</span> <span m="831890">called</span>
  <span m="832190">Solidus,</span> <span m="832940">which</span> <span m="833150">is</span>
  <span m="833780">out</span> <span m="833930">of</span> <span m="834020">Cornell,</span>
  <span m="835080">which</span> <span m="835160">also</span> <span m="835490">achieves</span>
  <span m="835820">this.</span> <span m="836750">You</span> <span m="836900">can't</span>
  <span m="837260">tell</span> <span m="837650">who</span> <span m="837770">the</span>
  <span m="837860">participants</span> <span m="838430">are.</span> <span m="839150">And</span>
  <span m="839660">you</span> <span m="840770">can</span> <span m="840890">still</span>
  <span m="841250">maintain</span> <span m="842000">financial</span> <span m="842540">invariants.</span>
  <span m="843360">Solidus</span> <span m="843920">uses</span> <span m="844220">a</span>
  <span m="844280">completely</span> <span m="844730">different</span> <span m="845030">cryptographic</span>
  <span m="845570">primitive</span> <span m="846950">called</span> <span m="847650">PVORM.</span>
  <span m="849770">So</span> <span m="849950">you</span> <span m="850040">should</span>
  <span m="850160">check</span> <span m="850340">out</span> <span m="850460">both</span>
  <span m="850580">these</span> <span m="850730">papers</span> <span m="851120">if</span>
  <span m="851210">you're</span> <span m="851330">interested.</span> <span m="852830">It's</span>
  <span m="853040">definitely</span> <span m="853490">still</span> <span m="853730">possible</span>
  <span m="855860">to</span> <span m="856010">accomplish</span> <span m="856480">this,</span>
  <span m="856700">right?</span></p><p><span m="857690">However,</span> <span m="859430">there's</span>
  <span m="859610">still</span> <span m="859850">a</span> <span m="859910">problem</span>
  <span m="860330">here.</span> <span m="861300">Both</span> <span m="861590">of</span>
  <span m="861680">these</span> <span m="861860">systems</span> <span m="863090">hide</span>
  <span m="863720">everything.</span> <span m="864890">You</span> <span m="865220">get</span>
  <span m="865670">no</span> <span m="866150">insight</span> <span m="866960">into</span>
  <span m="867830">the</span> <span m="867950">economy,</span> <span m="868460">into</span>
  <span m="868640">the</span> <span m="868730">blockchain,</span> <span m="869420">into</span>
  <span m="869750">what's</span> <span m="870080">actually</span> <span m="870500">happening</span>
  <span m="871100">in</span> <span m="871220">the</span> <span m="871310">system.</span></p><p><span
  m="874250">Regulators,</span> <span m="875060">in</span> <span m="875180">particular,</span>
  <span m="876230">need</span> <span m="876650">insight</span> <span m="877370">into</span>
  <span m="877610">markets</span> <span m="878360">in</span> <span m="878480">order</span>
  <span m="878780">to</span> <span m="878960">maintain</span> <span m="879350">financial</span>
  <span m="879830">stability</span> <span m="880610">and</span> <span m="880730">in</span>
  <span m="880820">order</span> <span m="881000">to</span> <span m="881090">protect</span>
  <span m="881450">investors.</span> <span m="883430">Even</span> <span m="884030">considering</span>
  <span m="884660">non-financial</span> <span m="885410">use</span> <span m="885650">cases,</span>
  <span m="886520">it's</span> <span m="886700">oftentimes</span> <span m="887330">the</span>
  <span m="887390">case</span> <span m="887930">that</span> <span m="888470">people</span>
  <span m="888770">who</span> <span m="888890">might</span> <span m="889130">be</span>
  <span m="889250">using</span> <span m="890180">a</span> <span m="890270">blockchain,</span>
  <span m="891410">or</span> <span m="891560">distributed</span> <span m="892010">ledger,</span>
  <span m="892310">or</span> <span m="892340">distributed</span> <span m="892820">database</span>
  <span m="893510">want</span> <span m="893930">to</span> <span m="894110">be</span>
  <span m="894350">able</span> <span m="894800">to</span> <span m="896660">maintain</span>
  <span m="897260">that</span> <span m="897410">certain</span> <span m="897710">things</span>
  <span m="897950">are</span> <span m="898040">true</span> <span m="899210">and</span>
  <span m="899330">to</span> <span m="899420">get</span> <span m="899630">some</span>
  <span m="899870">insight</span> <span m="900410">into</span> <span m="900620">the</span>
  <span m="900710">system</span> <span m="903270">that</span> <span m="903650">they're</span>
  <span m="903800">a</span> <span m="903830">part</span> <span m="904070">of.</span></p><p><span
  m="907510">Lack</span> <span m="907780">of</span> <span m="907870">insight</span>
  <span m="908230">can</span> <span m="908440">actually</span> <span m="908800">have</span>
  <span m="908950">devastating</span> <span m="909520">effects,</span> <span m="911140">as</span>
  <span m="911290">we</span> <span m="911410">saw</span> <span m="911650">with</span>
  <span m="911830">toxic</span> <span m="912220">assets</span> <span m="912610">in</span>
  <span m="912700">2008.</span> <span m="914140">One</span> <span m="915280">part</span>
  <span m="915970">of</span> <span m="916360">the</span> <span m="916480">problem,</span>
  <span m="916930">one</span> <span m="917170">contributor</span> <span m="917860">to</span>
  <span m="918400">the</span> <span m="918520">crisis,</span> <span m="919000">was</span>
  <span m="919180">the</span> <span m="919300">issue</span> <span m="919600">that</span>
  <span m="920650">people</span> <span m="920950">didn't</span> <span m="921130">really</span>
  <span m="921340">have</span> <span m="921490">confidence</span> <span m="922150">or</span>
  <span m="922240">insight</span> <span m="922750">into</span> <span m="922960">exactly</span>
  <span m="924400">what</span> <span m="924670">assets</span> <span m="925750">banks</span>
  <span m="926080">had</span> <span m="926560">on</span> <span m="926680">their</span>
  <span m="926800">books.</span> <span m="927430">It</span> <span m="927520">was</span>
  <span m="927700">a</span> <span m="927760">bit</span> <span m="927880">confusing.</span></p><p><span
  m="929410">And</span> <span m="929590">surprisingly,</span> <span m="930310">this</span>
  <span m="930610">happens</span> <span m="931240">to</span> <span m="931390">this</span>
  <span m="931600">day</span> <span m="932500">I</span> <span m="932590">think</span>
  <span m="932710">there</span> <span m="932830">was</span> <span m="932950">a</span>
  <span m="933010">case</span> <span m="933310">with</span> <span m="934570">Dow</span>
  <span m="935200">Chemical</span> <span m="935920">where</span> <span m="936100">they</span>
  <span m="937420">didn't</span> <span m="937840">actually</span> <span m="938260">know</span>
  <span m="938560">how</span> <span m="938740">many</span> <span m="938980">outstanding</span>
  <span m="939640">shares</span> <span m="940180">that</span> <span m="940330">they</span>
  <span m="940450">had</span> <span m="940600">issued.</span> <span m="941200">They</span>
  <span m="941290">just</span> <span m="941590">didn't</span> <span m="941830">know.</span>
  <span m="942160">And</span> <span m="943870">they</span> <span m="943990">had</span>
  <span m="944110">to</span> <span m="944200">give</span> <span m="944380">out</span>
  <span m="944530">a</span> <span m="944590">dividend,</span> <span m="945040">and</span>
  <span m="946810">they</span> <span m="946960">gave</span> <span m="947170">out</span>
  <span m="947290">too</span> <span m="947440">much</span> <span m="947620">money</span>
  <span m="947830">or</span> <span m="947920">too</span> <span m="948070">little</span>
  <span m="948220">money</span> <span m="948460">or</span> <span m="948550">something</span>
  <span m="948850">like</span> <span m="948970">that.</span></p><p><span m="951160">So</span>
  <span m="952230">here</span> <span m="952700">are</span> <span m="952810">some</span>
  <span m="952960">examples</span> <span m="953830">of</span> <span m="954070">things</span>
  <span m="954340">that</span> <span m="954430">we</span> <span m="954550">might</span>
  <span m="954790">want</span> <span m="955030">to</span> <span m="955240">measure</span>
  <span m="955870">and</span> <span m="956230">understand.</span> <span m="956890">We</span>
  <span m="957040">might</span> <span m="957310">want</span> <span m="957580">to</span>
  <span m="957730">get</span> <span m="957910">a</span> <span m="957940">sense</span>
  <span m="958210">of</span> <span m="958330">leverage</span> <span m="958930">in</span>
  <span m="959050">the</span> <span m="959110">system.</span> <span m="959630">So,</span>
  <span m="961300">the</span> <span m="961420">participants</span> <span m="962320">who</span>
  <span m="962470">are</span> <span m="962530">holding</span> <span m="962830">assets,</span>
  <span m="963580">how</span> <span m="963730">much</span> <span m="963910">do</span>
  <span m="964000">they</span> <span m="964120">have</span> <span m="965610">en</span>
  <span m="965770">masse?</span> <span m="966100">We</span> <span m="966190">want</span>
  <span m="966520">to</span> <span m="966580">understand</span> <span m="966970">exposure.</span>
  <span m="967990">We</span> <span m="968110">might</span> <span m="968350">want</span>
  <span m="968560">to</span> <span m="968620">get</span> <span m="968740">a</span>
  <span m="968770">sense</span> <span m="969010">of</span> <span m="969100">market</span>
  <span m="969400">concentration.</span></p><p><span m="971350">It's</span> <span
  m="971710">pretty</span> <span m="971920">useful</span> <span m="972310">to</span>
  <span m="972460">know</span> <span m="972670">things</span> <span m="973030">like,</span>
  <span m="973330">OK,</span> <span m="973540">this</span> <span m="973690">bank,</span>
  <span m="975220">this</span> <span m="975460">asset</span> <span m="975790">in</span>
  <span m="975880">particular</span> <span m="976420">is</span> <span m="976570">very</span>
  <span m="976750">highly</span> <span m="977020">concentrated.</span> <span m="978190">Or</span>
  <span m="978370">this</span> <span m="978610">asset</span> <span m="978940">is</span>
  <span m="979060">more</span> <span m="979210">distributed</span> <span m="979840">amongst</span>
  <span m="980170">the</span> <span m="980260">participants</span> <span m="981250">of</span>
  <span m="981430">the</span> <span m="981520">system.</span> <span m="982210">So</span>
  <span m="983200">there</span> <span m="983380">are</span> <span m="983410">things</span>
  <span m="983650">that</span> <span m="983740">we</span> <span m="984190">might</span>
  <span m="984400">want</span> <span m="984550">to</span> <span m="984610">learn</span>
  <span m="985210">about</span> <span m="985600">the</span> <span m="985720">economy</span>
  <span m="986440">represented</span> <span m="987280">by</span> <span m="987460">the</span>
  <span m="987580">assets</span> <span m="987940">in</span> <span m="988030">the</span>
  <span m="988120">blockchain.</span> <span m="989550">And</span> <span m="989740">that</span>
  <span m="990070">if</span> <span m="990370">the</span> <span m="990490">entire</span>
  <span m="990910">thing</span> <span m="991240">is</span> <span m="991810">encrypted</span>
  <span m="992710">or</span> <span m="992980">completely</span> <span m="993490">opaque,</span>
  <span m="993880">we're</span> <span m="994000">not</span> <span m="994150">going</span>
  <span m="994270">to</span> <span m="994360">be</span> <span m="994450">able</span>
  <span m="994750">to</span> <span m="994870">really</span> <span m="995140">gain</span>
  <span m="995380">this</span> <span m="995530">insight.</span> <span m="997040">And</span>
  <span m="997230">toxic</span> <span m="997620">assets,</span> <span m="997920">like
  I said.</span></p><p><span m="999180">So</span> <span m="999300">here's</span> <span
  m="999600">a</span> <span m="999660">specific</span> <span m="1000170">example</span>
  <span m="1000980">of</span> <span m="1001100">something</span> <span m="1001370">we</span>
  <span m="1001490">might</span> <span m="1001670">want</span> <span m="1001820">to</span>
  <span m="1001880">learn.</span> <span m="1004550">Here's</span> <span m="1004730">a</span>
  <span m="1004790">bank.</span> <span m="1005600">Here's</span> <span m="1005810">an</span>
  <span m="1005900">auditor.</span> <span m="1006740">And</span> <span m="1007130">the</span>
  <span m="1007280">auditor</span> <span m="1007580">might</span> <span m="1007820">want</span>
  <span m="1007970">to--</span> <span m="1008330">let's</span> <span m="1008540">assume</span>
  <span m="1008780">the</span> <span m="1008840">bank</span> <span m="1009050">is</span>
  <span m="1009170">using</span> <span m="1009620">a</span> <span m="1009680">system</span>
  <span m="1010310">like</span> <span m="1010550">zkLedger,</span> <span m="1010850">a</span>
  <span m="1011210">permissioned</span> <span m="1011600">blockchain.</span> <span
  m="1013160">An</span> <span m="1013310">auditor</span> <span m="1013580">might</span>
  <span m="1013790">want</span> <span m="1013940">to</span> <span m="1014000">know</span>
  <span m="1014270">how</span> <span m="1014690">exposed</span> <span m="1015620">is</span>
  <span m="1015800">this</span> <span m="1016010">bank</span> <span m="1016730">to</span>
  <span m="1016880">a</span> <span m="1016940">drop</span> <span m="1017420">in</span>
  <span m="1017540">the</span> <span m="1017630">euro?</span> <span m="1018200">So</span>
  <span m="1018350">if</span> <span m="1018440">the</span> <span m="1019010">euro</span>
  <span m="1019280">versus</span> <span m="1019610">the</span> <span m="1019700">dollar</span>
  <span m="1020450">changes</span> <span m="1020870">dramatically,</span> <span m="1021770">what's</span>
  <span m="1022070">going</span> <span m="1022190">to</span> <span m="1022250">happen</span>
  <span m="1022550">to</span> <span m="1022640">this</span> <span m="1022790">bank's</span>
  <span m="1023000">balance</span> <span m="1023300">sheet?</span></p><p><span m="1024530">So</span>
  <span m="1025339">in</span> <span m="1025670">zkLedger,</span> <span m="1026240">the</span>
  <span m="1026359">auditor</span> <span m="1026630">can</span> <span m="1026810">ask</span>
  <span m="1027020">a</span> <span m="1027050">question</span> <span m="1027410">like</span>
  <span m="1027560">what</span> <span m="1027800">fraction</span> <span m="1028400">of</span>
  <span m="1028550">your</span> <span m="1028700">assets</span> <span m="1029420">are</span>
  <span m="1029720">in</span> <span m="1029900">euros?</span> <span m="1030980">And</span>
  <span m="1031849">the</span> <span m="1031940">bank</span> <span m="1032150">might</span>
  <span m="1032300">respond,</span> <span m="1034130">3</span> <span m="1034369">million</span>
  <span m="1034819">out</span> <span m="1035000">of</span> <span m="1035060">100</span>
  <span m="1035359">million.</span> <span m="1035680">So,</span> <span m="1036220">3</span>
  <span m="1036440">million</span> <span m="1036680">euros,</span> <span m="1037069">100</span>
  <span m="1037280">million</span> <span m="1037460">dollars.</span> <span m="1037940">Something</span>
  <span m="1038240">like</span> <span m="1038390">that.</span> <span m="1039740">But</span>
  <span m="1040460">just</span> <span m="1040640">simply</span> <span m="1040970">asking</span>
  <span m="1041420">this</span> <span m="1041540">question,</span> <span m="1041960">the</span>
  <span m="1042079">auditor</span> <span m="1042380">doesn't</span> <span m="1042619">really</span>
  <span m="1042770">get</span> <span m="1043400">any</span> <span m="1044810">assurance</span>
  <span m="1045500">that</span> <span m="1045650">this</span> <span m="1045829">answer</span>
  <span m="1046220">is</span> <span m="1046460">correct.</span> <span m="1047310">And</span>
  <span m="1047329">so</span> <span m="1047450">this</span> <span m="1047690">is</span>
  <span m="1048530">the</span> <span m="1048620">nugget</span> <span m="1048980">of</span>
  <span m="1049070">the</span> <span m="1049130">problem</span> <span m="1049550">that</span>
  <span m="1049640">we</span> <span m="1049790">are</span> <span m="1049880">trying</span>
  <span m="1050270">to</span> <span m="1050420">solve</span> <span m="1050780">and</span>
  <span m="1050900">achieve.</span></p><p><span m="1052700">So</span> <span m="1053090">this</span>
  <span m="1053240">talk</span> <span m="1053540">presents</span> <span m="1053930">zkLedger.</span>
  <span m="1054890">And</span> <span m="1055370">it's</span> <span m="1056000">a</span>
  <span m="1056060">private,</span> <span m="1056630">auditable</span> <span m="1057110">transaction</span>
  <span m="1057650">ledger.</span> <span m="1058610">The</span> <span m="1058760">idea</span>
  <span m="1059090">behind</span> <span m="1059360">zkLedger</span> <span m="1060020">is</span>
  <span m="1061370">like</span> <span m="1061610">other</span> <span m="1061790">systems.</span>
  <span m="1062330">We</span> <span m="1062510">also</span> <span m="1062840">hide</span>
  <span m="1063680">the</span> <span m="1063800">transacting</span> <span m="1064490">banks</span>
  <span m="1065090">and</span> <span m="1065450">the</span> <span m="1065600">amounts</span>
  <span m="1066200">involved.</span> <span m="1068360">We</span> <span m="1068690">provide</span>
  <span m="1069140">integrity</span> <span m="1069740">with</span> <span m="1069890">public</span>
  <span m="1070220">verification.</span></p><p><span m="1071360">So</span> <span m="1071540">despite</span>
  <span m="1071990">the</span> <span m="1072080">fact</span> <span m="1072410">that</span>
  <span m="1072530">you</span> <span m="1072620">can't</span> <span m="1072890">really</span>
  <span m="1073100">see</span> <span m="1073310">the</span> <span m="1073400">details</span>
  <span m="1073910">of</span> <span m="1074000">the</span> <span m="1074090">transaction,</span>
  <span m="1075110">anyone,</span> <span m="1075870">not</span> <span m="1075950">just</span>
  <span m="1076130">the</span> <span m="1076220">participants,</span> <span m="1076790">but</span>
  <span m="1076970">anyone</span> <span m="1077450">you</span> <span m="1077570">want</span>
  <span m="1077780">to</span> <span m="1078350">show</span> <span m="1078530">this</span>
  <span m="1078740">to,</span> <span m="1079310">can</span> <span m="1079550">publicly</span>
  <span m="1080120">verify</span> <span m="1080750">and</span> <span m="1080870">convince</span>
  <span m="1081410">themselves</span> <span m="1082430">that</span> <span m="1083240">transactions</span>
  <span m="1083870">are</span> <span m="1083970">well-formed</span> <span m="1084680">and</span>
  <span m="1084800">financial</span> <span m="1085470">invariants</span> <span m="1085970">are</span>
  <span m="1086060">maintained.</span> <span m="1087200">And</span> <span m="1088070">an</span>
  <span m="1088220">auditor</span> <span m="1089090">can</span> <span m="1089450">interactively</span>
  <span m="1090200">compute</span> <span m="1090800">provably</span> <span m="1091460">correct</span>
  <span m="1092090">linear</span> <span m="1092480">functions</span> <span m="1093380">over</span>
  <span m="1093650">the</span> <span m="1093740">transactions.</span> <span m="1094820">So</span>
  <span m="1094970">things</span> <span m="1095240">like</span> <span m="1095540">trying</span>
  <span m="1095770">to</span> <span m="1095850">understand</span> <span m="1096290">market</span>
  <span m="1096740">concentration,</span> <span m="1097610">or</span> <span m="1097760">leverage,</span>
  <span m="1098240">or</span> <span m="1098300">exposure--</span> <span m="1099450">they</span>
  <span m="1099470">can</span> <span m="1099620">compute</span> <span m="1100310">a</span>
  <span m="1100370">set</span> <span m="1100550">of</span> <span m="1100610">queries</span>
  <span m="1101480">over</span> <span m="1102290">the</span> <span m="1102620">contents</span>
  <span m="1103130">of</span> <span m="1103220">the</span> <span m="1103310">transactions</span>
  <span m="1104090">in</span> <span m="1104240">the</span> <span m="1104330">ledger.</span></p><p><span
  m="1106390">OK,</span> <span m="1107010">so</span> <span m="1107740">I'm</span>
  <span m="1107850">going</span> <span m="1107950">to</span> <span m="1108030">describe</span>
  <span m="1108420">to</span> <span m="1108540">you</span> <span m="1108690">how</span>
  <span m="1108990">zkLedger</span> <span m="1109440">works.</span> <span m="1109860">I'm</span>
  <span m="1109920">going to</span> <span m="1110400">give</span> <span m="1110580">you</span>
  <span m="1110730">a</span> <span m="1110790">brief</span> <span m="1111000">overview</span>
  <span m="1111360">of</span> <span m="1111450">the</span> <span m="1111540">system</span>
  <span m="1111870">model.</span> <span m="1113080">And</span> <span m="1113100">then</span>
  <span m="1113220">I'm</span> <span m="1113310">going</span> <span m="1113430">to</span>
  <span m="1113490">start</span> <span m="1113700">to</span> <span m="1113820">go</span>
  <span m="1114030">into</span> <span m="1114390">some</span> <span m="1114630">of</span>
  <span m="1114750">the</span> <span m="1115230">more</span> <span m="1115380">interesting</span>
  <span m="1115800">pieces</span> <span m="1117060">inside</span> <span m="1117450">zkLedger.</span>
  <span m="1118380">So</span> <span m="1119100">the</span> <span m="1119190">commitments</span>
  <span m="1119790">that</span> <span m="1119940">we</span> <span m="1120060">use</span>
  <span m="1120370">to</span> <span m="1120480">hide</span> <span m="1120750">things,</span>
  <span m="1121470">the</span> <span m="1121860">way</span> <span m="1122190">the</span>
  <span m="1122310">ledger</span> <span m="1122640">is</span> <span m="1122760">constructed.</span></p><p><span
  m="1124390">And</span> <span m="1125140">I'm</span> <span m="1125210">going</span>
  <span m="1125390">to</span> <span m="1125460">tell</span> <span m="1125670">you</span>
  <span m="1125760">a</span> <span m="1125820">little</span> <span m="1126030">bit</span>
  <span m="1126270">about</span> <span m="1126930">the</span> <span m="1127020">primitives</span>
  <span m="1127470">that</span> <span m="1127560">we</span> <span m="1127680">use,</span>
  <span m="1128140">which</span> <span m="1128250">are</span> <span m="1128400">zero-knowledge</span>
  <span m="1128910">proofs.</span> <span m="1129570">Not</span> <span m="1130020">SNARKs,</span>
  <span m="1130530">which</span> <span m="1130680">I</span> <span m="1130740">talked</span>
  <span m="1130920">about</span> <span m="1131100">earlier--</span> <span m="1131400">a</span>
  <span m="1131460">different</span> <span m="1131730">type</span> <span m="1131940">of</span>
  <span m="1132030">zero-knowledge</span> <span m="1132360">proof.</span> <span m="1132630">But</span>
  <span m="1132750">I'll</span> <span m="1133260">give</span> <span m="1133440">you</span>
  <span m="1133890">a</span> <span m="1133920">little</span> <span m="1134160">bit</span>
  <span m="1134310">of</span> <span m="1134400">a</span> <span m="1134430">flavor</span>
  <span m="1134970">of</span> <span m="1135120">what</span> <span m="1135300">those</span>
  <span m="1135540">things</span> <span m="1135780">look</span> <span m="1135960">like.</span>
  <span m="1137290">And</span> <span m="1137310">then</span> <span m="1137460">I'll</span>
  <span m="1137580">show</span> <span m="1137790">you</span> <span m="1138180">the</span>
  <span m="1138270">performance</span> <span m="1138930">of</span> <span m="1139020">zkLedger.</span></p><p><span
  m="1140890">So</span> <span m="1141450">whether</span> <span m="1141750">you</span>
  <span m="1141840">buy</span> <span m="1142230">this</span> <span m="1142440">use</span>
  <span m="1142620">case</span> <span m="1142890">or</span> <span m="1142980">not,</span>
  <span m="1144090">I</span> <span m="1144210">think</span> <span m="1144450">that</span>
  <span m="1145020">you</span> <span m="1145180">will</span> <span m="1145320">see</span>
  <span m="1145740">these</span> <span m="1145980">topics</span> <span m="1146610">come</span>
  <span m="1146850">up</span> <span m="1147420">over</span> <span m="1147660">and</span>
  <span m="1147750">over</span> <span m="1147990">again</span> <span m="1148570">as</span>
  <span m="1148650">you're</span> <span m="1148770">looking</span> <span m="1149040">at</span>
  <span m="1149100">cryptocurrencies.</span> <span m="1150330">People</span> <span
  m="1150630">are</span> <span m="1150720">quite</span> <span m="1151110">interested</span>
  <span m="1151530">in</span> <span m="1151600">zero-knowledge</span> <span m="1152070">proofs</span>
  <span m="1152460">and</span> <span m="1152580">how</span> <span m="1153240">they</span>
  <span m="1153390">can</span> <span m="1153540">use</span> <span m="1153870">them</span>
  <span m="1154080">to</span> <span m="1154200">provide</span> <span m="1154560">privacy</span>
  <span m="1155970">inside</span> <span m="1156420">of</span> <span m="1156570">cryptocurrencies.</span>
  <span m="1159720">OK,</span> <span m="1160110">before</span> <span m="1160380">we</span>
  <span m="1161250">jump</span> <span m="1161460">into</span> <span m="1161610">the</span>
  <span m="1161680">system</span> <span m="1161970">model,</span> <span m="1162240">any</span>
  <span m="1162390">questions?</span> <span m="1166540">OK,</span> <span m="1166870">let's</span>
  <span m="1167020">go.</span></p><p><span m="1167740">So</span> <span m="1169150">let's</span>
  <span m="1169270">start</span> <span m="1169480">with</span> <span m="1169570">the</span>
  <span m="1169630">system</span> <span m="1169900">model.</span> <span m="1170650">So</span>
  <span m="1170890">here's</span> <span m="1171160">the</span> <span m="1171250">system</span>
  <span m="1171580">model.</span> <span m="1171970">We</span> <span m="1172120">have</span>
  <span m="1172270">a</span> <span m="1172300">set</span> <span m="1172450">of</span>
  <span m="1172510">banks.</span> <span m="1173170">These</span> <span m="1173350">banks</span>
  <span m="1173860">have</span> <span m="1174550">generated</span> <span m="1175930">public</span>
  <span m="1176260">keys</span> <span m="1176440">and</span> <span m="1176530">secret</span>
  <span m="1176800">keys,</span> <span m="1177400">which</span> <span m="1177610">they</span>
  <span m="1177730">have.</span> <span m="1178360">And</span> <span m="1178510">these</span>
  <span m="1178690">banks</span> <span m="1178960">are</span> <span m="1179050">working</span>
  <span m="1179380">together</span> <span m="1179860">to</span> <span m="1180010">construct</span>
  <span m="1180730">a</span> <span m="1180820">ledger.</span></p><p><span m="1182530">And</span>
  <span m="1182890">the</span> <span m="1182980">way</span> <span m="1183130">that</span>
  <span m="1183280">this</span> <span m="1183430">ledger</span> <span m="1183670">works</span>
  <span m="1184030">is</span> <span m="1184150">that</span> <span m="1184270">they</span>
  <span m="1184450">are</span> <span m="1184540">determining</span> <span m="1185020">transactions</span>
  <span m="1185650">amongst</span> <span m="1185950">themselves.</span> <span m="1186440">So</span>
  <span m="1186460">they're</span> <span m="1186580">deciding,</span> <span m="1187190">OK,</span>
  <span m="1188200">I'm</span> <span m="1188320">going</span> <span m="1188440">to</span>
  <span m="1188500">transfer</span> <span m="1188950">this</span> <span m="1189130">amount</span>
  <span m="1189370">to</span> <span m="1189460">that</span> <span m="1189610">bank.</span>
  <span m="1190210">And</span> <span m="1190330">then</span> <span m="1190480">once</span>
  <span m="1190780">they've</span> <span m="1191200">decided</span> <span m="1192010">on</span>
  <span m="1192310">a</span> <span m="1192370">transaction,</span> <span m="1193270">they</span>
  <span m="1193420">append</span> <span m="1193870">that</span> <span m="1194050">transaction</span>
  <span m="1194980">to</span> <span m="1195310">the</span> <span m="1195430">ledger.</span></p><p><span
  m="1195940">And</span> <span m="1196060">again,</span> <span m="1196420">remember,</span>
  <span m="1196750">this</span> <span m="1196930">ledger</span> <span m="1197200">could</span>
  <span m="1197380">be</span> <span m="1197470">maintained</span> <span m="1197950">by</span>
  <span m="1198880">a</span> <span m="1198940">third</span> <span m="1199150">party.</span>
  <span m="1200090">It</span> <span m="1200190">could</span> <span m="1200200">be</span>
  <span m="1200320">maintained</span> <span m="1200680">by</span> <span m="1200770">the</span>
  <span m="1200860">banks</span> <span m="1201130">themselves</span> <span m="1201550">on</span>
  <span m="1201640">a</span> <span m="1201670">blockchain.</span> <span m="1202570">They</span>
  <span m="1202720">could</span> <span m="1202900">be</span> <span m="1203050">using</span>
  <span m="1203380">a</span> <span m="1203440">public</span> <span m="1203920">bulletin</span>
  <span m="1204340">board.</span> <span m="1204670">They</span> <span m="1204790">could</span>
  <span m="1204910">be</span> <span m="1205000">posting</span> <span m="1205360">transactions</span>
  <span m="1205870">to</span> <span m="1205960">Twitter.</span> <span m="1206320">It</span>
  <span m="1206370">doesn't</span> <span m="1206590">matter.</span> <span m="1206960">We're</span>
  <span m="1206980">not</span> <span m="1207430">really</span> <span m="1207640">concerned</span>
  <span m="1208000">about</span> <span m="1208180">that</span> <span m="1208360">right</span>
  <span m="1208510">now.</span> <span m="1208900">The</span> <span m="1209020">point</span>
  <span m="1209260">is</span> <span m="1209830">that</span> <span m="1209980">there</span>
  <span m="1210130">is</span> <span m="1210330">an</span> <span m="1211060">append-only</span>
  <span m="1211660">ledger</span> <span m="1212950">that's</span> <span m="1213400">orthogonal</span>
  <span m="1214090">to</span> <span m="1214480">our</span> <span m="1214570">techniques--</span>
  <span m="1215320">how</span> <span m="1215620">exactly</span> <span m="1216100">it's</span>
  <span m="1216190">maintained.</span></p><p><span m="1219910">An</span> <span m="1220090">auditor,</span>
  <span m="1220960">a</span> <span m="1221020">third</span> <span m="1221260">party</span>
  <span m="1221530">auditor,</span> <span m="1222010">can</span> <span m="1222580">obtain</span>
  <span m="1223000">correct</span> <span m="1223600">answers</span> <span m="1224170">to</span>
  <span m="1224290">questions</span> <span m="1224830">based</span> <span m="1225070">on</span>
  <span m="1225160">ledger</span> <span m="1225400">contents.</span> <span m="1226030">So</span>
  <span m="1226450">note</span> <span m="1226660">that</span> <span m="1226810">auditing</span>
  <span m="1227200">is</span> <span m="1227350">interactive.</span> <span m="1228550">It's</span>
  <span m="1228730">not</span> <span m="1229030">the</span> <span m="1229120">case</span>
  <span m="1229420">that</span> <span m="1229570">someone</span> <span m="1229870">can</span>
  <span m="1230080">just</span> <span m="1230560">take</span> <span m="1230830">this</span>
  <span m="1231010">ledger</span> <span m="1231790">and</span> <span m="1231940">compute</span>
  <span m="1232360">things</span> <span m="1232810">over</span> <span m="1233080">it.</span>
  <span m="1233560">They</span> <span m="1233890">can't</span> <span m="1234160">do</span>
  <span m="1234340">that.</span> <span m="1235270">There's</span> <span m="1235450">not</span>
  <span m="1235570">enough</span> <span m="1235780">information</span> <span m="1236290">here</span>
  <span m="1236470">to</span> <span m="1236590">reveal</span> <span m="1236890">the</span>
  <span m="1237010">answers</span> <span m="1237310">to</span> <span m="1237370">queries.</span>
  <span m="1238090">The</span> <span m="1238180">auditor</span> <span m="1238450">has</span>
  <span m="1238780">to</span> <span m="1239320">actually</span> <span m="1240310">talk</span>
  <span m="1241030">to</span> <span m="1241360">the</span> <span m="1241450">participants</span>
  <span m="1242110">in</span> <span m="1242260">the</span> <span m="1242350">ledger.</span></p><p><span
  m="1243110">So</span> <span m="1243310">you</span> <span m="1243430">might</span>
  <span m="1243670">say,</span> <span m="1244070">well,</span> <span m="1244490">we</span>
  <span m="1244540">didn't</span> <span m="1244720">trust</span> <span m="1245110">the</span>
  <span m="1245200">participants</span> <span m="1245980">to</span> <span m="1246160">give</span>
  <span m="1246340">the</span> <span m="1246460">auditor</span> <span m="1246790">the</span>
  <span m="1246880">right</span> <span m="1247150">answer.</span> <span m="1248140">Why</span>
  <span m="1248470">would</span> <span m="1248620">we</span> <span m="1248740">trust</span>
  <span m="1249040">them</span> <span m="1249220">to</span> <span m="1249370">answer</span>
  <span m="1250000">the</span> <span m="1250150">auditor</span> <span m="1250510">at</span>
  <span m="1250600">all?</span> <span m="1251200">Well</span> <span m="1251620">in</span>
  <span m="1251680">the</span> <span m="1251770">setting</span> <span m="1252100">that</span>
  <span m="1252220">we've</span> <span m="1252400">set</span> <span m="1252580">up</span>
  <span m="1252700">for</span> <span m="1252880">ourselves,</span> <span m="1253300">if</span>
  <span m="1253390">they</span> <span m="1253540">don't</span> <span m="1253810">answer</span>
  <span m="1254050">the</span> <span m="1254170">auditor,</span> <span m="1254570">they</span>
  <span m="1254590">can</span> <span m="1254680">go</span> <span m="1254800">to</span>
  <span m="1254860">jail.</span> <span m="1255670">OK?</span> <span m="1256240">So</span>
  <span m="1256510">at</span> <span m="1256600">least</span> <span m="1257050">you</span>
  <span m="1257170">can</span> <span m="1257320">tell</span> <span m="1257650">whether</span>
  <span m="1257860">the</span> <span m="1257950">bank</span> <span m="1258190">is</span>
  <span m="1258310">answering</span> <span m="1258730">you</span> <span m="1258850">or</span>
  <span m="1258910">not.</span> <span m="1259240">If</span> <span m="1259360">the</span>
  <span m="1259450">bank</span> <span m="1259690">were</span> <span m="1259810">to</span>
  <span m="1259900">lie</span> <span m="1260200">to</span> <span m="1260290">you,</span>
  <span m="1260440">you</span> <span m="1260560">might</span> <span m="1260740">not</span>
  <span m="1260890">be</span> <span m="1260980">able</span> <span m="1261190">to</span>
  <span m="1261280">tell</span> <span m="1261640">whether--</span> <span m="1262090">this</span>
  <span m="1262870">allows</span> <span m="1263170">you</span> <span m="1263260">to</span>
  <span m="1263320">be</span> <span m="1263440">able</span> <span m="1263620">to--</span>
  <span m="1264400">if</span> <span m="1264580">you</span> <span m="1264700">get</span>
  <span m="1264820">an</span> <span m="1264910">answer,</span> <span m="1265210">you</span>
  <span m="1265300">know</span> <span m="1265450">that</span> <span m="1265570">that</span>
  <span m="1265690">answer</span> <span m="1265950">is</span> <span m="1266080">correct.</span></p><p><span
  m="1268580">So</span> <span m="1268730">the</span> <span m="1268850">auditor</span>
  <span m="1269210">will</span> <span m="1269330">query</span> <span m="1269660">the</span>
  <span m="1269750">bank</span> <span m="1270410">and</span> <span m="1270650">ask</span>
  <span m="1270920">a</span> <span m="1270950">question</span> <span m="1271340">similar</span>
  <span m="1271670">to</span> <span m="1271820">what</span> <span m="1271970">we</span>
  <span m="1272090">were</span> <span m="1272180">asking</span> <span m="1272450">before--</span>
  <span m="1272810">what</span> <span m="1272990">fraction</span> <span m="1273320">of</span>
  <span m="1273410">your</span> <span m="1273500">assets</span> <span m="1273860">are</span>
  <span m="1273890">in</span> <span m="1273980">euros?</span> <span m="1274880">The</span>
  <span m="1274970">bank</span> <span m="1275180">can</span> <span m="1275330">respond.</span>
  <span m="1276140">But</span> <span m="1276320">this</span> <span m="1276530">time,</span>
  <span m="1276960">instead</span> <span m="1277190">of</span> <span m="1277280">just</span>
  <span m="1277610">getting</span> <span m="1277880">an</span> <span m="1277970">answer,</span>
  <span m="1279050">the</span> <span m="1279170">auditor</span> <span m="1280070">also</span>
  <span m="1280430">gets</span> <span m="1280910">a</span> <span m="1281000">small</span>
  <span m="1281720">part</span> <span m="1282050">of</span> <span m="1282170">a</span>
  <span m="1282230">proof</span> <span m="1282770">from</span> <span m="1283070">the</span>
  <span m="1283160">bank</span> <span m="1284030">and</span> <span m="1284570">can</span>
  <span m="1285200">confirm</span> <span m="1286340">that</span> <span m="1286490">that</span>
  <span m="1286670">proof</span> <span m="1287120">is</span> <span m="1287240">correct</span>
  <span m="1287810">based</span> <span m="1288320">on</span> <span m="1288950">these</span>
  <span m="1289130">opaque</span> <span m="1289460">transaction</span> <span m="1290030">details</span>
  <span m="1290390">in</span> <span m="1290480">the</span> <span m="1290540">ledger.</span></p><p><span
  m="1291860">So</span> <span m="1292280">the</span> <span m="1292430">auditor</span>
  <span m="1292770">still</span> <span m="1293240">needs</span> <span m="1293630">to</span>
  <span m="1295880">talk</span> <span m="1296150">to</span> <span m="1296240">the</span>
  <span m="1296330">bank,</span> <span m="1298040">but</span> <span m="1298460">using</span>
  <span m="1299210">the</span> <span m="1299330">bank's</span> <span m="1299690">response,</span>
  <span m="1300680">they</span> <span m="1300830">can</span> <span m="1300980">compute</span>
  <span m="1301220">a</span> <span m="1301340">proof</span> <span m="1301820">that</span>
  <span m="1301970">shows</span> <span m="1302360">that</span> <span m="1302450">this</span>
  <span m="1302600">answer</span> <span m="1302840">must</span> <span m="1303020">be</span>
  <span m="1303110">correct.</span> <span m="1303770">OK?</span> <span m="1304940">So</span>
  <span m="1305240">auditing</span> <span m="1305570">is</span> <span m="1305660">interactive.</span>
  <span m="1306200">Like</span> <span m="1306350">I</span> <span m="1306410">said,</span>
  <span m="1306770">it's</span> <span m="1306890">possible</span> <span m="1307340">a
  bank</span> <span m="1307580">might</span> <span m="1307760">choose</span> <span
  m="1308210">not</span> <span m="1308420">to</span> <span m="1308510">respond.</span>
  <span m="1309110">That</span> <span m="1309320">could</span> <span m="1309500">happen.</span></p><p><span
  m="1310580">Also</span> <span m="1310910">I</span> <span m="1310970">want</span>
  <span m="1311120">to</span> <span m="1311180">point</span> <span m="1311420">out</span>
  <span m="1311900">that</span> <span m="1312200">if</span> <span m="1312350">the</span>
  <span m="1312500">auditor</span> <span m="1312920">is</span> <span m="1313040">constantly</span>
  <span m="1313970">auditing</span> <span m="1314660">this</span> <span m="1314900">ledger--</span>
  <span m="1315580">is</span> <span m="1315710">constantly</span> <span m="1316460">asking</span>
  <span m="1317180">how</span> <span m="1317300">many</span> <span m="1317480">euros</span>
  <span m="1317750">do you</span> <span m="1317840">have?</span> <span m="1318020">How</span>
  <span m="1318110">many</span> <span m="1318260">euros</span> <span m="1318560">do
  you</span> <span m="1318680">have?</span> <span m="1318800">How</span> <span m="1318920">many</span>
  <span m="1319070">euros</span> <span m="1319340">do you</span> <span m="1319460">have?</span>
  <span m="1320090">Then</span> <span m="1320990">if</span> <span m="1321200">that</span>
  <span m="1321350">number</span> <span m="1321650">changes,</span> <span m="1322730">it's</span>
  <span m="1322910">reasonable</span> <span m="1323390">to</span> <span m="1323510">assume</span>
  <span m="1324170">that</span> <span m="1324350">that</span> <span m="1324530">change</span>
  <span m="1324920">happened</span> <span m="1325220">in</span> <span m="1325310">the</span>
  <span m="1325400">last</span> <span m="1325670">transaction</span> <span m="1326240">appended</span>
  <span m="1326570">to</span> <span m="1326660">the</span> <span m="1326750">ledger.</span>
  <span m="1327230">Right?</span></p><p><span m="1327800">So</span> <span m="1329600">if</span>
  <span m="1330260">the</span> <span m="1330560">bank</span> <span m="1330890">continually</span>
  <span m="1331850">answers</span> <span m="1332270">the</span> <span m="1332390">auditor's</span>
  <span m="1332750">questions,</span> <span m="1333230">this</span> <span m="1333350">will</span>
  <span m="1333720">leak</span> <span m="1334070">transaction</span> <span m="1334700">contents.</span>
  <span m="1335480">This</span> <span m="1335720">doesn't</span> <span m="1336020">provide</span>
  <span m="1336800">what's</span> <span m="1336980">known</span> <span m="1337160">as</span>
  <span m="1337250">differential</span> <span m="1337730">privacy.</span> <span m="1338480">OK?</span>
  <span m="1339170">And</span> <span m="1339290">so</span> <span m="1340280">the</span>
  <span m="1340340">setup</span> <span m="1340670">here</span> <span m="1340880">is</span>
  <span m="1341030">that</span> <span m="1341480">the</span> <span m="1341600">auditor</span>
  <span m="1342050">and</span> <span m="1342620">the</span> <span m="1342710">bank</span>
  <span m="1342950">should</span> <span m="1343250">come</span> <span m="1343490">to</span>
  <span m="1343580">some</span> <span m="1343760">agreement</span> <span m="1344270">about</span>
  <span m="1344540">the</span> <span m="1344600">appropriate</span> <span m="1345020">level</span>
  <span m="1345560">of</span> <span m="1346760">frequency</span> <span m="1347240">of</span>
  <span m="1347330">auditing</span> <span m="1348110">such</span> <span m="1348380">that</span>
  <span m="1348680">both</span> <span m="1349130">the</span> <span m="1349280">auditor</span>
  <span m="1349520">gets</span> <span m="1349730">the</span> <span m="1349850">data</span>
  <span m="1350060">that</span> <span m="1350180">they</span> <span m="1350300">need,</span>
  <span m="1350600">and</span> <span m="1350720">the</span> <span m="1350780">bank</span>
  <span m="1351380">maintains</span> <span m="1351830">the</span> <span m="1351920">privacy</span>
  <span m="1352550">that</span> <span m="1352700">it</span> <span m="1352790">needs</span>
  <span m="1353030">to</span> <span m="1353090">maintain.</span></p><p><span m="1355300">OK,</span>
  <span m="1355910">so</span> <span m="1356810">as</span> <span m="1356960">I</span>
  <span m="1357050">said</span> <span m="1357200">before,</span> <span m="1357530">zkLedger</span>
  <span m="1358130">supports</span> <span m="1358670">any</span> <span m="1358970">linear</span>
  <span m="1359450">function</span> <span m="1360560">over</span> <span m="1360800">transaction</span>
  <span m="1361400">values.</span> <span m="1362310">So</span> <span m="1362540">we</span>
  <span m="1362720">can</span> <span m="1362870">do</span> <span m="1363170">ratios,</span>
  <span m="1363920">sums,</span> <span m="1364610">averages,</span> <span m="1365390">variance,</span>
  <span m="1365990">skews</span> <span m="1366920">outliers.</span> <span m="1368600">By</span>
  <span m="1368840">outliers,</span> <span m="1369410">I</span> <span m="1369500">mean</span>
  <span m="1370460">give</span> <span m="1370670">me</span> <span m="1370880">all</span>
  <span m="1371210">the</span> <span m="1371330">transactions</span> <span m="1372290">that</span>
  <span m="1373010">have</span> <span m="1373880">amounts</span> <span m="1374450">outside</span>
  <span m="1375170">of</span> <span m="1375320">this</span> <span m="1375530">range.</span>
  <span m="1376130">So</span> <span m="1376280">you</span> <span m="1376350">want</span>
  <span m="1376540">all</span> <span m="1376670">high-value</span> <span m="1377150">transactions,</span>
  <span m="1377720">you</span> <span m="1377780">can</span> <span m="1377900">provably,</span>
  <span m="1378380">correctly</span> <span m="1378940">give</span> <span m="1379460">that.</span>
  <span m="1380560">Approximation--</span> <span m="1381440">so</span> <span m="1381680">orders</span>
  <span m="1382070">of</span> <span m="1382130">magnitude</span> <span m="1383030">of</span>
  <span m="1383120">my</span> <span m="1383270">trades,</span> <span m="1383720">without</span>
  <span m="1383990">revealing</span> <span m="1384710">the</span> <span m="1384800">precise</span>
  <span m="1385220">number.</span> <span m="1386090">Changes</span> <span m="1386570">over</span>
  <span m="1386840">time,</span> <span m="1387770">and</span> <span m="1388130">also</span>
  <span m="1388430">well-known</span> <span m="1389090">financial</span> <span m="1389630">risk</span>
  <span m="1389900">measurements</span> <span m="1390410">like</span> <span m="1390650">the</span>
  <span m="1390740">Herfindahl-Hirschman</span> <span m="1391880">Index.</span></p><p><span
  m="1392870">So</span> <span m="1393080">in</span> <span m="1393200">this</span>
  <span m="1393380">talk--</span> <span m="1394230">oh,</span> <span m="1394370">sorry.</span>
  <span m="1394850">Yes,</span> <span m="1395240">there</span> <span m="1395480">are</span>
  <span m="1395810">small</span> <span m="1396440">amounts</span> <span m="1396950">of</span>
  <span m="1397100">well-defined</span> <span m="1397880">leakage</span> <span m="1398390">for</span>
  <span m="1398570">some</span> <span m="1398750">of</span> <span m="1398840">these</span>
  <span m="1399020">measurements.</span> <span m="1401660">So</span> <span m="1401900">for</span>
  <span m="1402020">example,</span> <span m="1402950">in</span> <span m="1403100">order</span>
  <span m="1403280">to</span> <span m="1403370">compute</span> <span m="1403700">the</span>
  <span m="1403820">average,</span> <span m="1404750">we</span> <span m="1405200">actually</span>
  <span m="1405620">compute</span> <span m="1406010">the</span> <span m="1406100">sum</span>
  <span m="1406790">and</span> <span m="1407060">the</span> <span m="1407150">number</span>
  <span m="1407450">of</span> <span m="1407540">transactions.</span> <span m="1408330">So</span>
  <span m="1408740">we</span> <span m="1408890">leak</span> <span m="1409220">a</span>
  <span m="1409280">little</span> <span m="1409580">bit</span> <span m="1409670">more</span>
  <span m="1409850">information</span> <span m="1410600">than</span> <span m="1410810">just</span>
  <span m="1411230">the</span> <span m="1411410">average,</span> <span m="1412930">but</span>
  <span m="1413090">it's</span> <span m="1413210">very</span> <span m="1413510">well-defined.</span></p><p><span
  m="1415070">And</span> <span m="1415190">in</span> <span m="1415280">this</span>
  <span m="1415460">talk,</span> <span m="1415700">I'm</span> <span m="1416030">only</span>
  <span m="1416270">really</span> <span m="1416600">going</span> <span m="1416720">to</span>
  <span m="1416780">talk</span> <span m="1417050">about</span> <span m="1417290">sums.</span>
  <span m="1419150">But</span> <span m="1419630">our</span> <span m="1419750">paper,</span>
  <span m="1420320">which</span> <span m="1420590">I'll</span> <span m="1421160">put</span>
  <span m="1421280">a</span> <span m="1421340">point</span> <span m="1421610">or</span>
  <span m="1421670">two</span> <span m="1422210">on</span> <span m="1422330">the</span>
  <span m="1422460">website,</span> <span m="1424040">explains</span> <span m="1424580">how</span>
  <span m="1424640">to</span> <span m="1424730">do</span> <span m="1425060">more</span>
  <span m="1425240">complex</span> <span m="1425720">things.</span> <span m="1426430">And</span>
  <span m="1427690">everything's</span> <span m="1428360">built</span> <span m="1428840">on</span>
  <span m="1429050">the</span> <span m="1429170">sums</span> <span m="1429800">primitive.</span></p><p><span
  m="1431960">So</span> <span m="1432800">let's</span> <span m="1433310">talk</span>
  <span m="1433520">about</span> <span m="1433730">the</span> <span m="1433820">security</span>
  <span m="1434270">goals.</span> <span m="1434540">So</span> <span m="1434720">what</span>
  <span m="1434870">are</span> <span m="1434930">we</span> <span m="1434990">trying</span>
  <span m="1435260">to</span> <span m="1435350">achieve</span> <span m="1435800">with</span>
  <span m="1435950">the</span> <span m="1436040">system?</span> <span m="1437910">So</span>
  <span m="1438170">first</span> <span m="1438410">of</span> <span m="1438470">all,</span>
  <span m="1438530">we're</span> <span m="1438620">trying</span> <span m="1438860">to</span>
  <span m="1438920">achieve</span> <span m="1439190">privacy.</span> <span m="1440810">We</span>
  <span m="1440960">want</span> <span m="1441170">to</span> <span m="1441290">make</span>
  <span m="1441530">sure</span> <span m="1441710">that</span> <span m="1441830">the</span>
  <span m="1441980">auditor</span> <span m="1442520">and</span> <span m="1442630">non-involved</span>
  <span m="1443270">parties</span> <span m="1443780">cannot</span> <span m="1444380">see</span>
  <span m="1444770">transaction</span> <span m="1445370">participants</span> <span
  m="1446030">or</span> <span m="1446150">amounts.</span> <span m="1446990">So</span>
  <span m="1448070">I</span> <span m="1448130">don't</span> <span m="1448250">know</span>
  <span m="1448310">if</span> <span m="1448370">I</span> <span m="1448430">made</span>
  <span m="1448580">this</span> <span m="1448730">clear</span> <span m="1448940">before,</span>
  <span m="1450470">but</span> <span m="1450620">it's</span> <span m="1450770">not</span>
  <span m="1450950">just</span> <span m="1451130">the</span> <span m="1451220">case</span>
  <span m="1451550">that</span> <span m="1451760">this</span> <span m="1452060">third-party</span>
  <span m="1452630">auditor</span> <span m="1452960">can't</span> <span m="1453290">see</span>
  <span m="1454160">who's</span> <span m="1454550">in</span> <span m="1454670">transactions</span>
  <span m="1455420">or</span> <span m="1456080">what</span> <span m="1456290">they're</span>
  <span m="1456860">transacting.</span> <span m="1458270">Anyone</span> <span m="1458690">who's</span>
  <span m="1458900">not</span> <span m="1459170">actually</span> <span m="1459770">involved</span>
  <span m="1460280">in</span> <span m="1460370">the</span> <span m="1460430">transaction,</span>
  <span m="1461060">receiving</span> <span m="1461480">or</span> <span m="1461540">sending</span>
  <span m="1461870">assets,</span> <span m="1462290">also</span> <span m="1462560">can't</span>
  <span m="1462860">see</span> <span m="1463580">inside</span> <span m="1463910">of</span>
  <span m="1463970">a</span> <span m="1464030">transaction.</span></p><p><span m="1466310">Completeness.</span>
  <span m="1467370">So</span> <span m="1467450">what</span> <span m="1467540">do</span>
  <span m="1467600">we</span> <span m="1467690">mean</span> <span m="1467840">by</span>
  <span m="1467960">completeness?</span> <span m="1468560">What</span> <span m="1468680">we</span>
  <span m="1468770">mean</span> <span m="1468920">by</span> <span m="1469070">that</span>
  <span m="1469670">is</span> <span m="1469820">that</span> <span m="1469970">banks</span>
  <span m="1470390">can't</span> <span m="1470990">lie</span> <span m="1471530">to</span>
  <span m="1471680">the</span> <span m="1471830">auditor.</span> <span m="1473770">They</span>
  <span m="1473780">can't</span> <span m="1474110">say</span> <span m="1474350">that</span>
  <span m="1474500">they</span> <span m="1474650">have</span> <span m="1474950">5</span>
  <span m="1475280">million</span> <span m="1475550">euros</span> <span m="1475940">when</span>
  <span m="1476120">actually</span> <span m="1476420">they</span> <span m="1476510">have</span>
  <span m="1476600">3</span> <span m="1476780">million</span> <span m="1477050">euros.</span>
  <span m="1477380">But</span> <span m="1477530">also,</span> <span m="1478370">the</span>
  <span m="1478460">bank</span> <span m="1478790">can't</span> <span m="1479210">selectively</span>
  <span m="1480920">leave</span> <span m="1481430">out</span> <span m="1481760">things.</span>
  <span m="1482630">OK?</span> <span m="1482960">So</span> <span m="1483080">you</span>
  <span m="1483170">could</span> <span m="1483290">imagine</span> <span m="1483830">some</span>
  <span m="1484040">ways</span> <span m="1484250">of</span> <span m="1484340">constructing</span>
  <span m="1484970">this</span> <span m="1485300">in</span> <span m="1485420">which,</span>
  <span m="1486110">if</span> <span m="1486260">a</span> <span m="1486320">bank</span>
  <span m="1486530">was</span> <span m="1486680">really</span> <span m="1486890">clever,</span>
  <span m="1487700">they</span> <span m="1487880">could</span> <span m="1488060">just</span>
  <span m="1489050">not</span> <span m="1489410">include</span> <span m="1490100">some</span>
  <span m="1490340">of</span> <span m="1490430">the</span> <span m="1490520">transactions</span>
  <span m="1491630">that</span> <span m="1491810">they</span> <span m="1492020">had</span>
  <span m="1492530">received,</span> <span m="1493160">and</span> <span m="1493280">thus</span>
  <span m="1493520">change</span> <span m="1493850">their</span> <span m="1494000">answers</span>
  <span m="1494300">to</span> <span m="1494390">the</span> <span m="1494510">auditor.</span>
  <span m="1495110">But</span> <span m="1495830">one</span> <span m="1496130">of</span>
  <span m="1496220">our</span> <span m="1496310">security</span> <span m="1496700">goals</span>
  <span m="1497000">that</span> <span m="1497180">we</span> <span m="1497480">achieve</span>
  <span m="1497900">is</span> <span m="1498140">that</span> <span m="1498680">it's</span>
  <span m="1498860">impossible</span> <span m="1499340">for</span> <span m="1499490">a</span>
  <span m="1499520">bank</span> <span m="1499730">to</span> <span m="1499940">omit</span>
  <span m="1500420">transactions</span> <span m="1501320">when</span> <span m="1501500">responding</span>
  <span m="1501890">to</span> <span m="1501980">the</span> <span m="1502070">auditor.</span></p><p><span
  m="1503930">We</span> <span m="1504140">also</span> <span m="1504920">are</span>
  <span m="1505070">looking</span> <span m="1505310">to</span> <span m="1505430">achieve</span>
  <span m="1505760">integrity,</span> <span m="1506360">so</span> <span m="1506540">banks</span>
  <span m="1506810">can't</span> <span m="1507110">violate</span> <span m="1508040">financial</span>
  <span m="1508550">invariants.</span> <span m="1509060">We</span> <span m="1509180">assume</span>
  <span m="1509750">that</span> <span m="1509990">banks</span> <span m="1510440">are</span>
  <span m="1510890">malicious.</span> <span m="1512300">But</span> <span m="1513410">honest</span>
  <span m="1513830">banks</span> <span m="1514190">should</span> <span m="1514460">always</span>
  <span m="1514910">be</span> <span m="1515060">able</span> <span m="1515270">to</span>
  <span m="1515390">convince</span> <span m="1515930">the</span> <span m="1516080">auditor</span>
  <span m="1516530">of</span> <span m="1516680">a</span> <span m="1516740">correct</span>
  <span m="1517070">answer.</span> <span m="1517890">So</span> <span m="1518150">we</span>
  <span m="1518300">don't</span> <span m="1518540">want</span> <span m="1518690">to</span>
  <span m="1518750">have</span> <span m="1518900">a</span> <span m="1518960">situation</span>
  <span m="1519500">where</span> <span m="1519620">a</span> <span m="1519650">malicious</span>
  <span m="1520130">bank</span> <span m="1520370">screws</span> <span m="1520970">up</span>
  <span m="1521090">the</span> <span m="1521180">ledger</span> <span m="1521870">such</span>
  <span m="1522230">that</span> <span m="1522610">an</span> <span m="1522860">honest</span>
  <span m="1523310">bank</span> <span m="1523700">can't</span> <span m="1524180">respond</span>
  <span m="1524690">to</span> <span m="1524840">the</span> <span m="1524960">auditor</span>
  <span m="1525290">because</span> <span m="1525560">the</span> <span m="1525650">ledger</span>
  <span m="1525890">doesn't</span> <span m="1526130">make</span> <span m="1526280">sense.</span>
  <span m="1527090">So</span> <span m="1527360">we</span> <span m="1527540">also</span>
  <span m="1527750">want</span> <span m="1527900">to</span> <span m="1527960">maintain</span>
  <span m="1528260">that.</span></p><p><span m="1530050">And</span> <span m="1530260">then</span>
  <span m="1530980">progress.</span> <span m="1532100">We</span> <span m="1532300">also</span>
  <span m="1532660">want</span> <span m="1532900">to</span> <span m="1532990">make</span>
  <span m="1533140">sure</span> <span m="1533470">that</span> <span m="1533860">a</span>
  <span m="1533950">malicious</span> <span m="1534310">bank</span> <span m="1534550">can't</span>
  <span m="1535030">block</span> <span m="1535630">other</span> <span m="1535840">banks</span>
  <span m="1536170">from</span> <span m="1536320">transacting--</span> <span m="1536950">that</span>
  <span m="1537070">they</span> <span m="1537190">can't</span> <span m="1537550">hold</span>
  <span m="1538000">up</span> <span m="1538570">the</span> <span m="1538690">entire</span>
  <span m="1539080">ledger.</span> <span m="1539740">And</span> <span m="1539860">I</span>
  <span m="1539920">think</span> <span m="1540400">as</span> <span m="1540820">I</span>
  <span m="1540910">describe</span> <span m="1541330">the</span> <span m="1541420">design,</span>
  <span m="1541990">it'll</span> <span m="1542110">become</span> <span m="1542440">clearer</span>
  <span m="1543040">why</span> <span m="1543550">these</span> <span m="1543760">things</span>
  <span m="1544030">were</span> <span m="1544150">issues</span> <span m="1544630">that</span>
  <span m="1544780">we</span> <span m="1544930">were</span> <span m="1545050">worried</span>
  <span m="1545320">about.</span> <span m="1545740">And</span> <span m="1546340">it's</span>
  <span m="1546490">part</span> <span m="1546730">of</span> <span m="1547030">how</span>
  <span m="1547180">we</span> <span m="1547690">designed</span> <span m="1548080">the</span>
  <span m="1548170">system</span> <span m="1548500">to</span> <span m="1548620">address</span>
  <span m="1548950">these</span> <span m="1549100">problems.</span></p><p><span m="1551470">So,</span>
  <span m="1551670">the</span> <span m="1551790">threat</span> <span m="1552030">model.</span>
  <span m="1553080">And</span> <span m="1553380">the</span> <span m="1553770">threat</span>
  <span m="1553980">model</span> <span m="1554220">describes</span> <span m="1555600">what</span>
  <span m="1555960">kind</span> <span m="1556350">of</span> <span m="1556440">attacks</span>
  <span m="1556980">that</span> <span m="1557130">we</span> <span m="1557280">are</span>
  <span m="1557370">trying</span> <span m="1557790">to</span> <span m="1557880">protect</span>
  <span m="1558270">against</span> <span m="1558750">and</span> <span m="1558870">what</span>
  <span m="1558990">kind</span> <span m="1559170">of</span> <span m="1559230">attacks</span>
  <span m="1559590">we</span> <span m="1559740">don't</span> <span m="1559980">protect</span>
  <span m="1560370">against.</span> <span m="1562230">So</span> <span m="1563790">banks</span>
  <span m="1564300">might</span> <span m="1564780">attempt</span> <span m="1565140">to</span>
  <span m="1565290">steal</span> <span m="1565680">or</span> <span m="1565770">hide</span>
  <span m="1566040">assets,</span> <span m="1567570">manipulate</span> <span m="1568080">balances,</span>
  <span m="1568830">or</span> <span m="1569100">lie</span> <span m="1569430">to</span>
  <span m="1569520">the</span> <span m="1569670">auditor.</span> <span m="1570570">Banks</span>
  <span m="1570840">can</span> <span m="1571020">arbitrarily</span> <span m="1571710">collude,</span>
  <span m="1572460">so</span> <span m="1572610">they</span> <span m="1572700">can</span>
  <span m="1572820">try</span> <span m="1572940">to</span> <span m="1573030">work</span>
  <span m="1573270">together</span> <span m="1573750">to</span> <span m="1573900">do</span>
  <span m="1574080">these</span> <span m="1574290">things.</span> <span m="1575730">And</span>
  <span m="1575880">banks</span> <span m="1576300">or</span> <span m="1576540">the</span>
  <span m="1576660">auditor</span> <span m="1577020">might</span> <span m="1577320">try</span>
  <span m="1577590">to</span> <span m="1577680">learn</span> <span m="1577980">transaction</span>
  <span m="1578580">contents.</span> <span m="1579060">So</span> <span m="1579690">it's</span>
  <span m="1579840">not</span> <span m="1580050">that</span> <span m="1580170">they're</span>
  <span m="1580710">passive.</span> <span m="1581220">They</span> <span m="1581340">might</span>
  <span m="1581550">actually</span> <span m="1581850">be</span> <span m="1581970">trying</span>
  <span m="1582300">to</span> <span m="1582570">actively</span> <span m="1583020">learn</span>
  <span m="1583710">what's</span> <span m="1583950">happening</span> <span m="1584250">in</span>
  <span m="1584340">the</span> <span m="1584430">ledger.</span></p><p><span m="1585840">What's</span>
  <span m="1586140">out</span> <span m="1586410">of</span> <span m="1586500">scope</span>
  <span m="1586860">for</span> <span m="1587040">this</span> <span m="1587250">work</span>
  <span m="1587970">is</span> <span m="1588930">a</span> <span m="1589020">ledger</span>
  <span m="1589470">that</span> <span m="1589650">omits</span> <span m="1589950">transactions</span>
  <span m="1590550">or</span> <span m="1590610">is</span> <span m="1590730">unavailable.</span>
  <span m="1591390">As</span> <span m="1591540">I</span> <span m="1591600">said,</span>
  <span m="1591990">we're</span> <span m="1592560">agnostic</span> <span m="1593160">to</span>
  <span m="1593250">the</span> <span m="1593340">ledger</span> <span m="1593850">implementation</span>
  <span m="1594990">as</span> <span m="1595110">long</span> <span m="1595470">as</span>
  <span m="1596070">it's</span> <span m="1596250">available</span> <span m="1597030">so</span>
  <span m="1597360">it</span> <span m="1597480">accepts</span> <span m="1597810">transactions.</span>
  <span m="1598920">If</span> <span m="1599280">the</span> <span m="1599370">ledger</span>
  <span m="1599640">doesn't</span> <span m="1599850">accept</span> <span m="1600060">transactions,</span>
  <span m="1601410">we</span> <span m="1601530">can't</span> <span m="1601740">provide</span>
  <span m="1602070">our</span> <span m="1602130">goals.</span></p><p><span m="1604240">We</span>
  <span m="1604320">also</span> <span m="1605460">don't</span> <span m="1605850">protect</span>
  <span m="1606270">against</span> <span m="1606510">an</span> <span m="1606630">adversary</span>
  <span m="1607230">who</span> <span m="1607320">might</span> <span m="1607530">be</span>
  <span m="1607650">watching</span> <span m="1608100">network</span> <span m="1608520">traffic.</span>
  <span m="1609220">So</span> <span m="1609870">if</span> <span m="1610440">there's</span>
  <span m="1610590">an</span> <span m="1611610">adversary</span> <span m="1612060">who's</span>
  <span m="1612120">snooping</span> <span m="1612540">on</span> <span m="1612630">the</span>
  <span m="1612720">network</span> <span m="1613500">and</span> <span m="1613620">sees</span>
  <span m="1613950">that</span> <span m="1614070">two</span> <span m="1614250">banks</span>
  <span m="1614580">are</span> <span m="1614640">communicating</span> <span m="1615270">a</span>
  <span m="1615300">lot,</span> <span m="1615720">it's</span> <span m="1615870">reasonable</span>
  <span m="1616260">to</span> <span m="1616410">assume</span> <span m="1616680">that</span>
  <span m="1616800">those</span> <span m="1616980">two</span> <span m="1617100">banks</span>
  <span m="1617400">are</span> <span m="1617460">involved</span> <span m="1617790">in</span>
  <span m="1617880">all the</span> <span m="1618000">transactions.</span> <span m="1619320">There</span>
  <span m="1619470">are</span> <span m="1619530">other</span> <span m="1619830">techniques</span>
  <span m="1620460">to</span> <span m="1620610">deal</span> <span m="1620910">with</span>
  <span m="1621090">these</span> <span m="1621240">problems.</span> <span m="1622780">And</span>
  <span m="1622800">then</span> <span m="1623040">also</span> <span m="1623490">what's</span>
  <span m="1623760">out</span> <span m="1623880">of</span> <span m="1623940">scope</span>
  <span m="1624270">is</span> <span m="1624360">banks</span> <span m="1624720">leaking</span>
  <span m="1625200">their</span> <span m="1625380">own</span> <span m="1625680">transactions.</span>
  <span m="1626400">If</span> <span m="1626520">a</span> <span m="1626580">bank</span>
  <span m="1626790">leaks</span> <span m="1627020">their own</span> <span m="1627240">transactions,</span>
  <span m="1627900">we</span> <span m="1628290">throw</span> <span m="1628440">up</span>
  <span m="1628530">our</span> <span m="1628590">hands.</span> <span m="1629070">Sorry,</span>
  <span m="1629350">we</span> <span m="1629460">tried</span> <span m="1629670">to</span>
  <span m="1629730">give</span> <span m="1629850">you</span> <span m="1629940">privacy.</span></p><p><span
  m="1635570">So</span> <span m="1635720">that's</span> <span m="1635930">the</span>
  <span m="1636020">system</span> <span m="1636380">model</span> <span m="1636920">for</span>
  <span m="1637100">zkLedger.</span> <span m="1637790">That's</span> <span m="1638000">the</span>
  <span m="1638030">threat</span> <span m="1638270">model,</span> <span m="1638870">those</span>
  <span m="1639080">are</span> <span m="1639170">our</span> <span m="1639230">goals,</span>
  <span m="1639690">that's</span> <span m="1639830">what</span> <span m="1639950">we're</span>
  <span m="1640070">trying</span> <span m="1640310">to</span> <span m="1640400">achieve.</span>
  <span m="1641660">Now,</span> <span m="1641930">let's</span> <span m="1642170">get</span>
  <span m="1642440">into</span> <span m="1642710">the</span> <span m="1642830">design</span>
  <span m="1643460">a</span> <span m="1643520">little</span> <span m="1643700">bit.</span></p><p><span
  m="1645260">So</span> <span m="1645620">we're</span> <span m="1645800">going</span>
  <span m="1645930">to</span> <span m="1646010">build</span> <span m="1646310">up</span>
  <span m="1646430">the</span> <span m="1646550">design</span> <span m="1647330">based</span>
  <span m="1647660">on</span> <span m="1647780">this</span> <span m="1647960">example.</span>
  <span m="1648930">So</span> <span m="1649400">here</span> <span m="1649820">is</span>
  <span m="1650000">an</span> <span m="1650090">example</span> <span m="1650840">of</span>
  <span m="1650990">a</span> <span m="1651050">public</span> <span m="1651590">transaction</span>
  <span m="1652820">ledger.</span> <span m="1653510">And</span> <span m="1653660">we're</span>
  <span m="1653840">going</span> <span m="1654110">to</span> <span m="1654200">slowly</span>
  <span m="1654770">start</span> <span m="1655130">to</span> <span m="1655340">mask</span>
  <span m="1655850">things</span> <span m="1656210">in</span> <span m="1656330">this</span>
  <span m="1656480">ledger</span> <span m="1656810">until</span> <span m="1657110">we</span>
  <span m="1657725">end</span> <span m="1658010">up</span> <span m="1658160">with</span>
  <span m="1658310">zkLedger's</span> <span m="1659000">design.</span></p><p><span
  m="1659840">So</span> <span m="1660350">we</span> <span m="1660530">have</span>
  <span m="1661880">four</span> <span m="1662090">transactions</span> <span m="1662660">here.</span>
  <span m="1662900">I'm</span> <span m="1663050">only</span> <span m="1663260">using</span>
  <span m="1663980">one</span> <span m="1664280">asset,</span> <span m="1664820">euros.</span>
  <span m="1665750">You'll</span> <span m="1665960">notice</span> <span m="1666470">that</span>
  <span m="1666590">the</span> <span m="1666680">first</span> <span m="1667070">transaction</span>
  <span m="1668240">addresses</span> <span m="1668750">the</span> <span m="1668840">question</span>
  <span m="1669320">that</span> <span m="1669440">you</span> <span m="1669620">asked,</span>
  <span m="1669890">which</span> <span m="1670040">is,</span> <span m="1670160">well,</span>
  <span m="1670280">where</span> <span m="1670520">do</span> <span m="1670640">funds</span>
  <span m="1670910">come</span> <span m="1671150">from?</span> <span m="1671450">And</span>
  <span m="1671570">here</span> <span m="1671750">we</span> <span m="1671900">have</span>
  <span m="1672470">a</span> <span m="1672530">special</span> <span m="1672980">depositor,</span>
  <span m="1674180">who</span> <span m="1674390">is</span> <span m="1674660">injecting</span>
  <span m="1675470">assets</span> <span m="1676100">into</span> <span m="1676340">the</span>
  <span m="1676460">system.</span> <span m="1677240">This</span> <span m="1677390">depositor</span>
  <span m="1677960">might</span> <span m="1678230">be</span> <span m="1678440">the</span>
  <span m="1678530">central</span> <span m="1678890">bank,</span> <span m="1679250">for</span>
  <span m="1679430">example.</span></p><p><span m="1680150">A</span> <span m="1680210">lot</span>
  <span m="1680420">of</span> <span m="1680510">systems</span> <span m="1680900">are</span>
  <span m="1680990">actually</span> <span m="1681290">designed</span> <span m="1681620">this</span>
  <span m="1681800">way.</span> <span m="1682040">So</span> <span m="1682250">Stellar,</span>
  <span m="1684020">I</span> <span m="1684140">think</span> <span m="1684320">Chains,</span>
  <span m="1686390">Blockchain,</span> <span m="1687680">Ripple--</span> <span m="1689690">these</span>
  <span m="1689870">systems</span> <span m="1690260">are</span> <span m="1690350">all</span>
  <span m="1690500">designed</span> <span m="1691430">with</span> <span m="1691790">the</span>
  <span m="1691940">idea</span> <span m="1692330">of</span> <span m="1693090">a</span>
  <span m="1693380">special</span> <span m="1693800">depositor</span> <span m="1694550">who's</span>
  <span m="1694760">allowed</span> <span m="1695240">to</span> <span m="1695960">create</span>
  <span m="1696350">their</span> <span m="1696560">own</span> <span m="1696740">asset</span>
  <span m="1697190">and</span> <span m="1697340">insert</span> <span m="1697820">it</span>
  <span m="1698000">into</span> <span m="1698240">the</span> <span m="1698360">system.</span>
  <span m="1699210">So</span> <span m="1700300">here,</span> <span m="1700730">maybe</span>
  <span m="1700970">the</span> <span m="1701060">depositor</span> <span m="1701600">is</span>
  <span m="1701960">the</span> <span m="1702140">European</span> <span m="1702560">Central</span>
  <span m="1702830">Bank.</span> <span m="1703460">Maybe</span> <span m="1703760">it's</span>
  <span m="1703880">some</span> <span m="1704090">other</span> <span m="1704270">bank,</span>
  <span m="1704570">who</span> <span m="1704900">provably</span> <span m="1705470">has</span>
  <span m="1706010">a</span> <span m="1706070">lot</span> <span m="1706280">of</span>
  <span m="1706400">euros</span> <span m="1706940">in</span> <span m="1707030">their</span>
  <span m="1707180">account</span> <span m="1707930">and</span> <span m="1708290">puts</span>
  <span m="1708590">them</span> <span m="1708770">onto</span> <span m="1708980">the</span>
  <span m="1709040">ledger.</span></p><p><span m="1710070">So</span> <span m="1710090">there's</span>
  <span m="1710270">a</span> <span m="1710300">depositor</span> <span m="1711170">who's</span>
  <span m="1711380">granting</span> <span m="1711800">30</span> <span m="1712040">million</span>
  <span m="1712310">euros</span> <span m="1712640">to</span> <span m="1712700">Goldman</span>
  <span m="1713030">Sachs.</span> <span m="1714230">And</span> <span m="1714350">then</span>
  <span m="1714500">there</span> <span m="1714620">are</span> <span m="1714710">three</span>
  <span m="1715190">transactions.</span> <span m="1716690">And</span> <span m="1716960">I</span>
  <span m="1717320">think</span> <span m="1717440">it's</span> <span m="1717530">important</span>
  <span m="1717860">to</span> <span m="1718430">get</span> <span m="1718640">a</span>
  <span m="1718700">sense</span> <span m="1718910">of</span> <span m="1719000">what</span>
  <span m="1719120">these</span> <span m="1719240">transactions</span> <span m="1719720">are.</span>
  <span m="1719870">So</span> <span m="1720050">Goldman</span> <span m="1720440">Sachs</span>
  <span m="1720980">is</span> <span m="1721130">transferring</span> <span m="1721760">10</span>
  <span m="1722000">million</span> <span m="1722270">to</span> <span m="1722360">JP</span>
  <span m="1722660">Morgan.</span> <span m="1723770">And</span> <span m="1723920">then</span>
  <span m="1725300">JP</span> <span m="1725630">Morgan,</span> <span m="1726170">in</span>
  <span m="1726350">two</span> <span m="1726770">different</span> <span m="1727340">transactions,</span>
  <span m="1728680">is</span> <span m="1728810">transferring</span> <span m="1729290">money</span>
  <span m="1729500">to</span> <span m="1729620">Barclays.</span> <span m="1730610">OK?</span></p><p><span
  m="1731550">So</span> <span m="1733770">let's</span> <span m="1735000">move</span>
  <span m="1735180">on</span> <span m="1735300">from</span> <span m="1735480">here.</span>
  <span m="1736150">So</span> <span m="1736440">like</span> <span m="1736620">I</span>
  <span m="1736710">said,</span> <span m="1737190">the</span> <span m="1737280">depositor</span>
  <span m="1738090">injects</span> <span m="1738480">assets</span> <span m="1738840">to</span>
  <span m="1738930">ledger,</span> <span m="1739350">and</span> <span m="1739470">that's</span>
  <span m="1739710">the</span> <span m="1739800">way</span> <span m="1740040">of</span>
  <span m="1740160">entering</span> <span m="1740490">transactions.</span> <span m="1741780">That's</span>
  <span m="1742020">the</span> <span m="1742110">depositor,</span> <span m="1742830">right</span>
  <span m="1743010">there.</span></p><p><span m="1744750">Now</span> <span m="1746160">our</span>
  <span m="1746280">goals</span> <span m="1746670">are</span> <span m="1746760">to</span>
  <span m="1746910">achieve</span> <span m="1747240">auditing</span> <span m="1747570">and</span>
  <span m="1747660">privacy.</span> <span m="1748200">What</span> <span m="1748320">do</span>
  <span m="1748380">we</span> <span m="1748470">mean</span> <span m="1748650">by</span>
  <span m="1748800">that?</span> <span m="1749470">Well,</span> <span m="1750060">we</span>
  <span m="1750300">shouldn't--</span> <span m="1751490">someone</span> <span m="1751830">looking</span>
  <span m="1752250">at</span> <span m="1752340">the</span> <span m="1752460">ledger</span>
  <span m="1753570">shouldn't</span> <span m="1754020">be</span> <span m="1754140">able</span>
  <span m="1754320">to</span> <span m="1754440">tell</span> <span m="1755310">these</span>
  <span m="1755520">amounts</span> <span m="1756360">except</span> <span m="1756750">for</span>
  <span m="1756900">the</span> <span m="1756990">depositor</span> <span m="1757800">transaction,</span>
  <span m="1758400">which</span> <span m="1758550">is</span> <span m="1758670">always</span>
  <span m="1758910">public.</span> <span m="1759360">In</span> <span m="1759630">zkLedger,</span>
  <span m="1760320">the</span> <span m="1760410">depositor</span> <span m="1760860">transactions</span>
  <span m="1761340">are</span> <span m="1761400">public.</span> <span m="1762070">But</span>
  <span m="1762120">they</span> <span m="1762240">shouldn't</span> <span m="1762480">be</span>
  <span m="1762570">able</span> <span m="1762750">to</span> <span m="1762840">tell</span>
  <span m="1764070">after</span> <span m="1764430">that</span> <span m="1765110">that</span>
  <span m="1765300">Goldman</span> <span m="1765690">Sachs</span> <span m="1766140">gave</span>
  <span m="1766290">money</span> <span m="1766500">to</span> <span m="1766590">JP</span>
  <span m="1766860">Morgan,</span> <span m="1767220">and that</span> <span m="1767370">JP</span>
  <span m="1767640">Morgan</span> <span m="1767910">gave</span> <span m="1768030">it</span>
  <span m="1768090">to</span> <span m="1768180">Barclays,</span> <span m="1768690">and</span>
  <span m="1768780">what</span> <span m="1768930">the</span> <span m="1768990">amounts</span>
  <span m="1769320">were.</span> <span m="1769740">OK?</span></p><p><span m="1772480">So</span>
  <span m="1774030">in</span> <span m="1774150">this</span> <span m="1774330">example,</span>
  <span m="1775510">we're</span> <span m="1775530">going</span> <span m="1775920">to</span>
  <span m="1776130">try</span> <span m="1776460">to</span> <span m="1776640">provably</span>
  <span m="1777300">audit</span> <span m="1777690">Barclays</span> <span m="1778830">to</span>
  <span m="1779010">figure</span> <span m="1779310">out</span> <span m="1779580">how</span>
  <span m="1779730">many</span> <span m="1779970">euros</span> <span m="1780480">Barclays</span>
  <span m="1781140">is</span> <span m="1781290">holding.</span> <span m="1782520">And</span>
  <span m="1782610">again,</span> <span m="1782910">we</span> <span m="1783030">want</span>
  <span m="1783150">to</span> <span m="1783210">hide</span> <span m="1783360">the</span>
  <span m="1783420">participants,</span> <span m="1784110">amounts,</span> <span m="1784590">and</span>
  <span m="1784710">the</span> <span m="1784770">transaction</span> <span m="1785400">graph.</span>
  <span m="1786000">So</span> <span m="1786750">what</span> <span m="1786900">do</span>
  <span m="1786990">I</span> <span m="1787050">mean</span> <span m="1787230">when</span>
  <span m="1787350">I</span> <span m="1787410">say</span> <span m="1787620">transaction</span>
  <span m="1788400">graph?</span></p><p><span m="1789930">I</span> <span m="1790020">think</span>
  <span m="1790260">you</span> <span m="1790350">guys</span> <span m="1790650">learned</span>
  <span m="1790920">a</span> <span m="1790980">little</span> <span m="1791160">bit</span>
  <span m="1791430">about</span> <span m="1791820">a</span> <span m="1791880">system</span>
  <span m="1792210">called</span> <span m="1792450">confidential</span> <span m="1793110">transactions</span>
  <span m="1794160">a</span> <span m="1794220">few</span> <span m="1794400">weeks</span>
  <span m="1794610">ago.</span> <span m="1795180">Confidential</span> <span m="1795720">transactions</span>
  <span m="1796470">does</span> <span m="1796770">not</span> <span m="1797310">hide</span>
  <span m="1797700">the</span> <span m="1797820">transaction</span> <span m="1798390">graph.</span>
  <span m="1799140">It</span> <span m="1799260">hides</span> <span m="1799770">the</span>
  <span m="1799890">amounts,</span> <span m="1801570">but</span> <span m="1801960">you</span>
  <span m="1802110">can</span> <span m="1802290">tell</span> <span m="1803460">the</span>
  <span m="1803550">source</span> <span m="1804300">of</span> <span m="1804450">the</span>
  <span m="1804540">funds.</span></p><p><span m="1805350">So</span> <span m="1805740">here,</span>
  <span m="1806880">the</span> <span m="1807000">money</span> <span m="1807510">that</span>
  <span m="1807660">Barclays</span> <span m="1808380">got--</span> <span m="1808970">so</span>
  <span m="1810000">if</span> <span m="1810150">we</span> <span m="1810270">were</span>
  <span m="1810390">trying</span> <span m="1810690">to</span> <span m="1811410">attain</span>
  <span m="1811740">privacy</span> <span m="1812220">in</span> <span m="1812310">the</span>
  <span m="1812400">system,</span> <span m="1813310">the</span> <span m="1813330">fact</span>
  <span m="1813690">that</span> <span m="1813810">Goldman</span> <span m="1814200">Sachs</span>
  <span m="1814560">got</span> <span m="1814950">euros,</span> <span m="1815760">and</span>
  <span m="1815940">Goldman</span> <span m="1816270">Sachs</span> <span m="1816540">is</span>
  <span m="1816630">the</span> <span m="1816720">only</span> <span m="1816930">company</span>
  <span m="1817200">that</span> <span m="1817290">got</span> <span m="1817440">euros,</span>
  <span m="1817800">is</span> <span m="1817920">public,</span> <span m="1818370">because</span>
  <span m="1818670">depositor</span> <span m="1819180">transactions</span> <span m="1819720">are</span>
  <span m="1819780">public.</span> <span m="1820720">But</span> <span m="1821250">we</span>
  <span m="1821430">shouldn't</span> <span m="1821730">be</span> <span m="1821880">able</span>
  <span m="1822090">to</span> <span m="1822240">tell</span> <span m="1823290">that</span>
  <span m="1823500">the</span> <span m="1823590">euros</span> <span m="1824280">that</span>
  <span m="1824430">Barclays</span> <span m="1825240">got--</span> <span m="1825690">obviously</span>
  <span m="1826080">they</span> <span m="1826200">must</span> <span m="1826530">have</span>
  <span m="1826620">been</span> <span m="1826770">sourced</span> <span m="1827070">through</span>
  <span m="1827220">Goldman</span> <span m="1827550">Sachs.</span> <span m="1828060">We</span>
  <span m="1828210">shouldn't</span> <span m="1828510">be</span> <span m="1828630">able</span>
  <span m="1828780">to</span> <span m="1828870">tell</span> <span m="1829140">they</span>
  <span m="1829290">went</span> <span m="1829650">through</span> <span m="1830920">anyone,</span>
  <span m="1832020">or</span> <span m="1832170">how</span> <span m="1832380">many</span>
  <span m="1832560">people</span> <span m="1832830">they</span> <span m="1832950">went</span>
  <span m="1833160">through,</span> <span m="1833820">or</span> <span m="1833970">that</span>
  <span m="1834120">it</span> <span m="1834180">was</span> <span m="1834330">JP</span>
  <span m="1834600">Morgan.</span></p><p><span m="1835710">So</span> <span m="1836340">if</span>
  <span m="1836580">we</span> <span m="1836730">leaked</span> <span m="1837060">the</span>
  <span m="1837180">transaction</span> <span m="1837840">graph,</span> <span m="1838620">you</span>
  <span m="1838740">might</span> <span m="1838950">be</span> <span m="1839070">able</span>
  <span m="1839280">to</span> <span m="1839430">tell</span> <span m="1840360">that</span>
  <span m="1840510">there</span> <span m="1840630">was</span> <span m="1840780">an</span>
  <span m="1840900">entity</span> <span m="1841590">that</span> <span m="1842160">the</span>
  <span m="1842280">money</span> <span m="1842580">went</span> <span m="1842880">through</span>
  <span m="1843360">before</span> <span m="1843720">it</span> <span m="1843780">got</span>
  <span m="1843960">to</span> <span m="1844080">Barclays.</span> <span m="1844710">So</span>
  <span m="1844830">when</span> <span m="1844950">we</span> <span m="1845070">say</span>
  <span m="1845220">we</span> <span m="1845340">want</span> <span m="1845490">to</span>
  <span m="1845550">hide</span> <span m="1845880">the</span> <span m="1845970">transaction</span>
  <span m="1846570">graph,</span> <span m="1846870">that's</span> <span m="1847080">what</span>
  <span m="1847200">we</span> <span m="1847290">mean.</span> <span m="1847530">We</span>
  <span m="1847650">want</span> <span m="1847830">to</span> <span m="1847890">be</span>
  <span m="1847980">able</span> <span m="1848100">to</span> <span m="1848190">hide</span>
  <span m="1849300">the</span> <span m="1849420">flow</span> <span m="1850110">of</span>
  <span m="1850200">funds,</span> <span m="1850590">how</span> <span m="1850740">they</span>
  <span m="1850860">move</span> <span m="1851640">through</span> <span m="1851820">the</span>
  <span m="1851910">system.</span></p><p><span m="1856660">We</span> <span m="1857020">hide</span>
  <span m="1857470">the</span> <span m="1857620">amounts</span> <span m="1858490">by</span>
  <span m="1858790">using</span> <span m="1859330">a</span> <span m="1859450">cryptographic</span>
  <span m="1860320">primitive</span> <span m="1860770">called</span> <span m="1861070">Pedersen</span>
  <span m="1861640">commitments.</span> <span m="1863650">So</span> <span m="1863830">Pedersen</span>
  <span m="1864280">commitments,</span> <span m="1865180">as</span> <span m="1865480">you</span>
  <span m="1865600">learned,</span> <span m="1866050">are</span> <span m="1866260">binding</span>
  <span m="1866740">and</span> <span m="1866830">hiding</span> <span m="1867190">commitments</span>
  <span m="1867640">to</span> <span m="1867790">a</span> <span m="1867850">value.</span>
  <span m="1870080">And</span> <span m="1870310">the</span> <span m="1870400">way</span>
  <span m="1870550">that</span> <span m="1870670">they</span> <span m="1870820">work--</span>
  <span m="1871800">and</span> <span m="1871960">I'm</span> <span m="1872200">terribly</span>
  <span m="1872680">sorry,</span> <span m="1873010">but</span> <span m="1873190">I</span>
  <span m="1873340">use</span> <span m="1873520">slightly</span> <span m="1873880">different</span>
  <span m="1874180">notation</span> <span m="1874780">than</span> <span m="1874940">Tadge.</span>
  <span m="1875800">So</span> <span m="1875950">Tadge</span> <span m="1876340">uses</span>
  <span m="1878200">additive</span> <span m="1878620">notation--</span> <span m="1880870">multiplicative</span>
  <span m="1881440">notation,</span> <span m="1881860">and</span> <span m="1881980">I</span>
  <span m="1882070">use</span> <span m="1882250">exponential</span> <span m="1882790">notation.</span>
  <span m="1883700">These</span> <span m="1883780">mean</span> <span m="1883930">exactly</span>
  <span m="1884470">the</span> <span m="1884560">same</span> <span m="1884830">thing.</span>
  <span m="1885370">I</span> <span m="1885490">will</span> <span m="1885640">very</span>
  <span m="1885880">quickly</span> <span m="1887350">write</span> <span m="1887590">down</span>
  <span m="1888070">what</span> <span m="1888220">they</span> <span m="1888370">are.</span></p><p><span
  m="1888970">So</span> <span m="1890140">in Tadge's</span> <span m="1890740">notation,</span>
  <span m="1891910">G</span> <span m="1892360">and</span> <span m="1892570">H</span>
  <span m="1893410">are</span> <span m="1893530">generators</span> <span m="1894430">in</span>
  <span m="1894550">some</span> <span m="1894790">group.</span> <span m="1895820">And</span>
  <span m="1896290">if</span> <span m="1896410">you</span> <span m="1896560">have</span>
  <span m="1896800">some</span> <span m="1897010">value</span> <span m="1897700">and</span>
  <span m="1897850">some</span> <span m="1898060">randomness,</span> <span m="1899290">then</span>
  <span m="1899710">you</span> <span m="1899920">would</span> <span m="1900340">write</span>
  <span m="1900610">a</span> <span m="1900670">Pedersen</span> <span m="1901120">commitment</span>
  <span m="1904095">as</span> <span m="1904560">that,</span> <span m="1905310">OK?</span>
  <span m="1907110">Now,</span> <span m="1907470">whether</span> <span m="1908010">it's</span>
  <span m="1908400">r</span> <span m="1908670">times</span> <span m="1909000">G,</span>
  <span m="1909330">or</span> <span m="1909420">v</span> <span m="1909630">times</span>
  <span m="1909930">H</span> <span m="1910100">isn't</span> <span m="1910350">important.</span>
  <span m="1910930">The</span> <span m="1910950">point</span> <span m="1911220">is</span>
  <span m="1911340">these</span> <span m="1911490">are</span> <span m="1911580">two</span>
  <span m="1913050">generators</span> <span m="1914070">of</span> <span m="1914610">a</span>
  <span m="1914670">group,</span> <span m="1915420">in</span> <span m="1915510">this</span>
  <span m="1915630">case,</span> <span m="1915880">an</span> <span m="1916020">elliptical</span>
  <span m="1916260">curve</span> <span m="1916650">group.</span> <span m="1917430">And</span>
  <span m="1917660">in</span> <span m="1917730">Bitcoin,</span> <span m="1918270">secp256k1.</span></p><p><span
  m="1920140">It</span> <span m="1920460">doesn't</span> <span m="1920820">really</span>
  <span m="1921090">matter</span> <span m="1921360">what</span> <span m="1921510">those</span>
  <span m="1921690">generators</span> <span m="1922260">are.</span> <span m="1922530">You</span>
  <span m="1922680">just</span> <span m="1922860">pick</span> <span m="1923040">any</span>
  <span m="1923220">two.</span> <span m="1924750">You</span> <span m="1924870">could</span>
  <span m="1924990">call</span> <span m="1925170">this</span> <span m="1925310">G1</span>
  <span m="1925710">and</span> <span m="1925800">G2,</span> <span m="1926100">if</span>
  <span m="1926190">you</span> <span m="1926280">wanted</span> <span m="1926520">to.</span>
  <span m="1927390">And</span> <span m="1927540">so</span> <span m="1927780">this</span>
  <span m="1927930">is</span> <span m="1928050">the</span> <span m="1928110">way</span>
  <span m="1928290">that</span> <span m="1928620">Tadge</span> <span m="1928950">would</span>
  <span m="1929070">write</span> <span m="1929310">it.</span></p><p><span m="1930270">The</span>
  <span m="1930390">way</span> <span m="1930540">that</span> <span m="1930660">I</span>
  <span m="1930810">write</span> <span m="1931080">it--</span> <span m="1932200">and</span>
  <span m="1932520">I'm</span> <span m="1932640">sorry</span> <span m="1932820">about</span>
  <span m="1932970">this,</span> <span m="1933250">but</span> <span m="1933270">it's</span>
  <span m="1933360">good</span> <span m="1933630">that</span> <span m="1933780">you</span>
  <span m="1933900">guys</span> <span m="1934170">get</span> <span m="1934320">exposed</span>
  <span m="1934800">to</span> <span m="1934950">both</span> <span m="1935250">ways,</span>
  <span m="1935610">because</span> <span m="1935850">you'll</span> <span m="1935970">find</span>
  <span m="1936390">both</span> <span m="1936660">ways</span> <span m="1937050">in</span>
  <span m="1937170">the</span> <span m="1937230">literature--</span> <span m="1938160">is</span>
  <span m="1938580">in</span> <span m="1938730">exponential</span> <span m="1939300">notation.</span>
  <span m="1939990">So</span> <span m="1940080">I</span> <span m="1940230">would</span>
  <span m="1940350">write</span> <span m="1940560">g</span> <span m="1940950">to</span>
  <span m="1941100">the</span> <span m="1941220">v,</span> <span m="1942070">h</span>
  <span m="1942750">to</span> <span m="1942870">the</span> <span m="1942990">r.</span>
  <span m="1945340">And</span> <span m="1946450">they're</span> <span m="1946600">multiplied</span>
  <span m="1947290">together</span> <span m="1948370">instead</span> <span m="1948790">of</span>
  <span m="1949180">added</span> <span m="1949480">together.</span> <span m="1950510">OK?</span></p><p><span
  m="1951610">So</span> <span m="1951760">this</span> <span m="1951940">is</span>
  <span m="1952060">just</span> <span m="1952400">purely</span> <span m="1953080">a</span>
  <span m="1953230">notational</span> <span m="1953920">thing.</span> <span m="1956460">It's</span>
  <span m="1956860">just,</span> <span m="1957100">instead</span> <span m="1957430">of</span>
  <span m="1957520">the</span> <span m="1958720">multiply</span> <span m="1959290">operator</span>
  <span m="1959680">here,</span> <span m="1959980">we're</span> <span m="1960130">doing</span>
  <span m="1960430">exponentiation.</span> <span m="1961270">Instead</span> <span
  m="1961480">of</span> <span m="1961530">the</span> <span m="1961600">plus</span>
  <span m="1961900">operator</span> <span m="1962260">here,</span> <span m="1962440">we're</span>
  <span m="1962560">doing</span> <span m="1962740">multiplication.</span></p><p><span
  m="1967040">So,</span> <span m="1967830">Pedersen</span> <span m="1968320">commitment.</span>
  <span m="1969520">The</span> <span m="1969640">way</span> <span m="1969940">that</span>
  <span m="1970060">you</span> <span m="1970180">commit</span> <span m="1970630">to</span>
  <span m="1970840">a</span> <span m="1970900">value</span> <span m="1971290">v</span>
  <span m="1972100">is</span> <span m="1973330">everyone</span> <span m="1973750">has</span>
  <span m="1973870">chosen</span> <span m="1974230">these</span> <span m="1974410">generators.</span>
  <span m="1975190">The</span> <span m="1975490">generator</span> <span m="1975910">choice</span>
  <span m="1976190">is</span> <span m="1976330">system-wide.</span> <span m="1977290">This</span>
  <span m="1977440">isn't</span> <span m="1977680">something</span> <span m="1977950">you</span>
  <span m="1978040">pick</span> <span m="1978190">at</span> <span m="1978250">the</span>
  <span m="1978340">time</span> <span m="1978670">you</span> <span m="1978760">make</span>
  <span m="1978910">a</span> <span m="1978970">transaction.</span> <span m="1979510">The</span>
  <span m="1979600">generator</span> <span m="1979800">choice</span> <span m="1980100">is</span>
  <span m="1980230">system-wide.</span></p><p><span m="1981160">However,</span> <span
  m="1981880">the</span> <span m="1982090">r,</span> <span m="1983110">the</span>
  <span m="1983200">randomness,</span> <span m="1984310">you</span> <span m="1984490">do</span>
  <span m="1984700">choose</span> <span m="1985030">fresh</span> <span m="1985570">each</span>
  <span m="1985780">time.</span> <span m="1986200">You</span> <span m="1986290">pick</span>
  <span m="1986440">any</span> <span m="1986580">randomness</span> <span m="1987040">each</span>
  <span m="1987220">time.</span> <span m="1987880">And</span> <span m="1987970">the</span>
  <span m="1988060">way</span> <span m="1988330">that</span> <span m="1988480">you</span>
  <span m="1988600">commit</span> <span m="1988990">to</span> <span m="1989260">a</span>
  <span m="1989350">value</span> <span m="1990130">is</span> <span m="1990370">by</span>
  <span m="1990970">producing</span> <span m="1992410">this</span> <span m="1993010">value</span>
  <span m="1993430">right</span> <span m="1993670">here,</span> <span m="1994490">which</span>
  <span m="1994630">is</span> <span m="1995110">the</span> <span m="1995200">generator</span>
  <span m="1995770">raised</span> <span m="1996340">to</span> <span m="1996760">the</span>
  <span m="1996850">value</span> <span m="1997300">times</span> <span m="1998440">the</span>
  <span m="1998560">second</span> <span m="1998830">generator</span> <span m="1999280">raised</span>
  <span m="1999590">to</span> <span m="1999670">the</span> <span m="1999760">randomness.</span></p><p><span
  m="2000900">And</span> <span m="2001080">what</span> <span m="2001260">this</span>
  <span m="2001410">serves</span> <span m="2001800">to</span> <span m="2001920">do</span>
  <span m="2003480">is</span> <span m="2005010">it's</span> <span m="2005580">binding.</span>
  <span m="2006570">It's</span> <span m="2006720">very</span> <span m="2007050">difficult</span>
  <span m="2007620">to</span> <span m="2007770">come</span> <span m="2008100">up</span>
  <span m="2008280">with,</span> <span m="2009120">later,</span> <span m="2009930">a</span>
  <span m="2010020">different</span> <span m="2010470">and</span> <span m="2010860">a</span>
  <span m="2010920">different</span> <span m="2011250">r</span> <span m="2011910">that</span>
  <span m="2012150">ends</span> <span m="2012390">up</span> <span m="2012540">equaling</span>
  <span m="2012990">the</span> <span m="2013050">same</span> <span m="2013320">commitment.</span>
  <span m="2014790">And</span> <span m="2015000">part</span> <span m="2015240">of</span>
  <span m="2015300">that</span> <span m="2015450">is</span> <span m="2015600">based</span>
  <span m="2015960">on</span> <span m="2016080">an</span> <span m="2016200">assumption</span>
  <span m="2016620">called</span> <span m="2016920">the</span> <span m="2017010">discrete</span>
  <span m="2017430">logarithm--</span> <span m="2018330">the</span> <span m="2018420">hardness</span>
  <span m="2018780">of</span> <span m="2018840">the</span> <span m="2018930">discrete</span>
  <span m="2019260">logarithm</span> <span m="2020130">problem.</span></p><p><span
  m="2022230">And</span> <span m="2022440">also,</span> <span m="2023010">importantly,</span>
  <span m="2024180">these</span> <span m="2024480">things</span> <span m="2024780">can</span>
  <span m="2024990">be</span> <span m="2025350">homomorphically</span> <span m="2026250">combined.</span>
  <span m="2027610">So</span> <span m="2027810">if</span> <span m="2027960">we</span>
  <span m="2028080">have</span> <span m="2028560">these</span> <span m="2028770">commitments</span>
  <span m="2030030">to</span> <span m="2030240">these</span> <span m="2030420">different</span>
  <span m="2030720">values,</span> <span m="2031600">and</span> <span m="2031620">we</span>
  <span m="2031740">multiply</span> <span m="2032340">them</span> <span m="2032490">together,</span>
  <span m="2033500">well,</span> <span m="2033700">when</span> <span m="2033750">you</span>
  <span m="2033870">multiply</span> <span m="2035700">things</span> <span m="2036120">that</span>
  <span m="2036300">are</span> <span m="2037020">raised</span> <span m="2037320">to</span>
  <span m="2037410">an</span> <span m="2037500">exponent,</span> <span m="2038010">you</span>
  <span m="2038160">end</span> <span m="2038400">up</span> <span m="2038670">adding</span>
  <span m="2039180">the</span> <span m="2039360">exponent,</span> <span m="2040440">right?</span>
  <span m="2041100">So</span> <span m="2041460">by</span> <span m="2041640">multiplying</span>
  <span m="2042510">these</span> <span m="2042750">things</span> <span m="2043050">together,</span>
  <span m="2043990">we</span> <span m="2044070">end</span> <span m="2044490">up</span>
  <span m="2044730">with</span> <span m="2045450">a</span> <span m="2045630">valid</span>
  <span m="2046350">commitment</span> <span m="2047430">to</span> <span m="2047640">the</span>
  <span m="2047760">sum</span> <span m="2048750">of</span> <span m="2048900">the</span>
  <span m="2048989">values</span> <span m="2049830">in</span> <span m="2050010">the</span>
  <span m="2050400">individual</span> <span m="2050909">commitments</span> <span m="2051719">that</span>
  <span m="2051870">we</span> <span m="2051960">multiplied</span> <span m="2052440">together.</span>
  <span m="2053670">So</span> <span m="2054150">we</span> <span m="2054300">can</span>
  <span m="2054510">homomorphically</span> <span m="2055980">combine</span> <span
  m="2056580">the</span> <span m="2056670">commitments.</span> <span m="2057750">It</span>
  <span m="2057900">ends</span> <span m="2058260">up</span> <span m="2058739">summing</span>
  <span m="2060500">in</span> <span m="2060690">the</span> <span m="2060810">exponent.</span>
  <span m="2061780">And</span> <span m="2061800">we</span> <span m="2061920">end</span>
  <span m="2062130">up</span> <span m="2062219">with</span> <span m="2062370">a</span>
  <span m="2062400">valid</span> <span m="2062820">commitment</span> <span m="2065010">to</span>
  <span m="2065250">the</span> <span m="2065340">sum</span> <span m="2065730">of</span>
  <span m="2065880">the</span> <span m="2065940">values.</span></p><p><span m="2068770">Another</span>
  <span m="2068969">nice</span> <span m="2069179">property</span> <span m="2070110">of</span>
  <span m="2070320">Pedersen</span> <span m="2070710">commitments</span> <span m="2071489">is</span>
  <span m="2071670">that</span> <span m="2071760">they</span> <span m="2071909">are</span>
  <span m="2072000">very</span> <span m="2072270">fast</span> <span m="2072960">to</span>
  <span m="2073170">create,</span> <span m="2073800">combine,</span> <span m="2074460">and</span>
  <span m="2074790">verify.</span> <span m="2076290">And</span> <span m="2076530">perhaps</span>
  <span m="2076949">surprisingly,</span> <span m="2077860">we</span> <span m="2077909">can</span>
  <span m="2078060">actually</span> <span m="2078420">achieve</span> <span m="2078870">all</span>
  <span m="2079110">of</span> <span m="2079170">the</span> <span m="2079290">auditing</span>
  <span m="2079800">functions</span> <span m="2080310">that</span> <span m="2080429">I</span>
  <span m="2080489">showed</span> <span m="2080730">you</span> <span m="2080850">earlier</span>
  <span m="2081690">just</span> <span m="2082139">using</span> <span m="2082679">Pedersen</span>
  <span m="2083159">commitments.</span></p><p><span m="2084690">So</span> <span m="2084960">before</span>
  <span m="2085290">we</span> <span m="2085380">move</span> <span m="2085620">on,</span>
  <span m="2085889">questions</span> <span m="2086489">on</span> <span m="2086730">Pedersen</span>
  <span m="2087179">commitments?</span> <span m="2087989">I</span> <span m="2088110">know</span>
  <span m="2088260">that</span> <span m="2088350">you</span> <span m="2088440">guys</span>
  <span m="2088679">learned</span> <span m="2088860">about</span> <span m="2089040">this</span>
  <span m="2089190">in</span> <span m="2089280">a</span> <span m="2089340">previous</span>
  <span m="2089699">class,</span> <span m="2090090">but</span> <span m="2091380">they're</span>
  <span m="2091560">pretty</span> <span m="2091800">important.</span> <span m="2095940">They're</span>
  <span m="2096090">used</span> <span m="2096540">in</span> <span m="2096840">confidential</span>
  <span m="2097440">transactions</span> <span m="2098070">as</span> <span m="2098190">well</span>
  <span m="2098820">to</span> <span m="2098940">prove</span> <span m="2099390">that</span>
  <span m="2099570">the</span> <span m="2099720">sum</span> <span m="2099990">of</span>
  <span m="2100080">the</span> <span m="2100200">outputs</span> <span m="2100800">is</span>
  <span m="2101610">less</span> <span m="2101820">than</span> <span m="2101940">or</span>
  <span m="2102030">equal</span> <span m="2102210">to</span> <span m="2102330">the</span>
  <span m="2102390">sum</span> <span m="2102570">of</span> <span m="2102630">the</span>
  <span m="2102720">inputs,</span> <span m="2104010">if</span> <span m="2104160">you</span>
  <span m="2104250">guys</span> <span m="2104490">recall</span> <span m="2104760">that.</span>
  <span m="2105890">So</span> <span m="2106020">any</span> <span m="2106170">questions?</span></p><p><span
  m="2108430">AUDIENCE:</span> <span m="2108540">When</span> <span m="2108650">are</span>
  <span m="2108670">you</span> <span m="2108790">making</span> <span m="2109177">this
  commitment?</span></p><p><span m="2110340">NEHA NARULA:</span> <span m="2110475">Ah,</span>
  <span m="2110830">great</span> <span m="2111040">question.</span> <span m="2112120">You're</span>
  <span m="2112240">making</span> <span m="2112540">this</span> <span m="2112690">commitment</span>
  <span m="2113560">at</span> <span m="2113650">the</span> <span m="2113740">time</span>
  <span m="2114640">that</span> <span m="2114970">the</span> <span m="2115240">transaction</span>
  <span m="2115870">is</span> <span m="2115960">created.</span> <span m="2116590">And</span>
  <span m="2116710">I'll</span> <span m="2116800">get</span> <span m="2116950">into</span>
  <span m="2117130">the</span> <span m="2117220">details</span> <span m="2117700">of</span>
  <span m="2117760">who</span> <span m="2117970">creates</span> <span m="2118300">the</span>
  <span m="2118360">transaction,</span> <span m="2119770">and</span> <span m="2120070">what</span>
  <span m="2120310">do</span> <span m="2120430">they</span> <span m="2120550">choose,</span>
  <span m="2121060">and</span> <span m="2121150">how</span> <span m="2121330">does</span>
  <span m="2121480">that</span> <span m="2121600">happen,</span> <span m="2121940">and</span>
  <span m="2122020">how</span> <span m="2122110">do</span> <span m="2122170">we</span>
  <span m="2122260">make</span> <span m="2122380">sure</span> <span m="2122500">they</span>
  <span m="2122590">don't</span> <span m="2122770">screw</span> <span m="2122980">it</span>
  <span m="2123040">up.</span></p><p><span m="2123520">AUDIENCE:</span> <span m="2123715">So</span>
  <span m="2123910">when</span> <span m="2124030">you</span> <span m="2124150">add</span>
  <span m="2124260">a</span> <span m="2124350">measurement</span> <span m="2124780">to</span>
  <span m="2124930">this</span> <span m="2125120">ledger,</span> <span m="2126030">it</span>
  <span m="2126160">might</span> <span m="2126370">add</span> <span m="2126580">a</span>
  <span m="2126610">number</span> <span m="2126970">of</span> <span m="2127630">commitments</span>
  <span m="2128130">that people make...</span></p><p><span m="2129270">NEHA NARULA:</span>
  <span m="2129465">Well,</span> <span m="2130280">so</span> <span m="2130330">measurements</span>
  <span m="2130840">happen</span> <span m="2131140">on</span> <span m="2131260">top</span>
  <span m="2131560">of</span> <span m="2131680">the</span> <span m="2131770">ledger.</span>
  <span m="2132500">So</span> <span m="2133390">we</span> <span m="2133570">can</span>
  <span m="2133690">actually</span> <span m="2134020">do</span> <span m="2134230">all</span>
  <span m="2134380">of</span> <span m="2134470">our</span> <span m="2134560">measurements</span>
  <span m="2135790">basically</span> <span m="2136300">just</span> <span m="2136510">on</span>
  <span m="2136630">those</span> <span m="2136840">commitments.</span> <span m="2137230">We</span>
  <span m="2137320">don't</span> <span m="2137440">have</span> <span m="2137530">to</span>
  <span m="2137620">add</span> <span m="2138250">anything</span> <span m="2138550">to</span>
  <span m="2138650">ledger.</span> <span m="2140510">OK.</span> <span m="2141310">So,</span>
  <span m="2142300">yes,</span> <span m="2142600">like</span> <span m="2142780">I</span>
  <span m="2142840">said,</span> <span m="2143050">we</span> <span m="2143140">can</span>
  <span m="2143260">achieve</span> <span m="2143650">all</span> <span m="2143860">the</span>
  <span m="2143980">auditing</span> <span m="2144310">functions</span> <span m="2144730">with</span>
  <span m="2144910">Pedersen</span> <span m="2145240">commitments.</span> <span m="2145630">And</span>
  <span m="2145720">I'll</span> <span m="2145810">go</span> <span m="2145930">into</span>
  <span m="2146200">a</span> <span m="2146230">little</span> <span m="2146410">bit</span>
  <span m="2146500">of</span> <span m="2146590">detail.</span> <span m="2147820">OK,</span>
  <span m="2148030">great.</span></p><p><span m="2148270">So</span> <span m="2148390">we</span>
  <span m="2148510">can</span> <span m="2148630">use</span> <span m="2148870">Pearson</span>
  <span m="2149260">commitments</span> <span m="2149680">to</span> <span m="2149770">hide</span>
  <span m="2150730">the</span> <span m="2150850">value.</span> <span m="2151420">So</span>
  <span m="2151600">again,</span> <span m="2153220">by</span> <span m="2153400">using</span>
  <span m="2153730">these</span> <span m="2153880">commitments,</span> <span m="2154510">you</span>
  <span m="2154690">can't--</span> <span m="2155260">looking</span> <span m="2155620">at</span>
  <span m="2155710">this</span> <span m="2155920">right</span> <span m="2156130">here,</span>
  <span m="2157010">if</span> <span m="2157060">you</span> <span m="2157240">don't</span>
  <span m="2157540">know</span> <span m="2157870">r,</span> <span m="2158890">you</span>
  <span m="2159040">can't</span> <span m="2159490">guess--</span> <span m="2160300">if</span>
  <span m="2160450">you</span> <span m="2160540">don't</span> <span m="2160690">know</span>
  <span m="2160840">v</span> <span m="2160960">and r,</span> <span m="2161170">you</span>
  <span m="2161470">can't--</span> <span m="2162250">if</span> <span m="2162370">you</span>
  <span m="2162430">don't</span> <span m="2162580">know</span> <span m="2162670">r,</span>
  <span m="2162790">you</span> <span m="2162880">can't</span> <span m="2163360">guess</span>
  <span m="2163570">what</span> <span m="2163690">v is.</span> <span m="2164350">It</span>
  <span m="2164620">could</span> <span m="2164770">be</span> <span m="2164890">anything.</span>
  <span m="2165750">So</span> <span m="2167140">that's</span> <span m="2167350">what</span>
  <span m="2167470">we</span> <span m="2167560">mean</span> <span m="2167830">when</span>
  <span m="2167980">we</span> <span m="2168100">say</span> <span m="2168820">that</span>
  <span m="2169960">these</span> <span m="2170110">commitments</span> <span m="2170560">are</span>
  <span m="2170650">perfectly</span> <span m="2171100">hiding.</span></p><p><span
  m="2173530">So</span> <span m="2173710">we</span> <span m="2173860">also</span>
  <span m="2174070">want</span> <span m="2174190">to</span> <span m="2174250">hide</span>
  <span m="2174610">the</span> <span m="2174730">participants</span> <span m="2175300">in</span>
  <span m="2175390">the</span> <span m="2175450">transaction,</span> <span m="2176110">obviously.</span>
  <span m="2176560">And</span> <span m="2176650">we're</span> <span m="2176740">going</span>
  <span m="2176840">to</span> <span m="2176950">do</span> <span m="2177130">that</span>
  <span m="2177340">using</span> <span m="2177610">other</span> <span m="2177790">techniques.</span>
  <span m="2178570">Just</span> <span m="2179410">hold</span> <span m="2179650">that</span>
  <span m="2179770">in</span> <span m="2179830">your</span> <span m="2179950">head</span>
  <span m="2180160">for</span> <span m="2180290">a</span> <span m="2180310">moment.</span>
  <span m="2180670">We're</span> <span m="2180820">going</span> <span m="2180940">to</span>
  <span m="2181000">jump</span> <span m="2181180">to</span> <span m="2181300">that.</span></p><p><span
  m="2182690">But</span> <span m="2182800">first,</span> <span m="2183190">quickly,</span>
  <span m="2184130">let's</span> <span m="2184510">take</span> <span m="2184750">a</span>
  <span m="2184810">look</span> <span m="2185050">at</span> <span m="2185140">how</span>
  <span m="2185560">auditing</span> <span m="2185980">might</span> <span m="2186190">work</span>
  <span m="2186910">given</span> <span m="2187300">that</span> <span m="2187390">we're</span>
  <span m="2187510">using</span> <span m="2188140">these</span> <span m="2188320">Pedersen</span>
  <span m="2188740">commitments,</span> <span m="2189440">OK?</span> <span m="2190120">So</span>
  <span m="2190960">assume</span> <span m="2191380">that</span> <span m="2192010">we</span>
  <span m="2192160">have</span> <span m="2192310">hidden</span> <span m="2193360">who</span>
  <span m="2193600">the</span> <span m="2193690">participants</span> <span m="2194290">are</span>
  <span m="2195340">in</span> <span m="2195460">this</span> <span m="2195610">ledger</span>
  <span m="2197036">through a</span> <span m="2197480">technique</span> <span m="2197870">that</span>
  <span m="2197990">I'm</span> <span m="2198080">not</span> <span m="2198260">telling</span>
  <span m="2198500">you</span> <span m="2198590">about,</span> <span m="2198770">yet.</span>
  <span m="2200180">We're</span> <span m="2200330">hiding</span> <span m="2201080">the</span>
  <span m="2201620">values</span> <span m="2202430">in</span> <span m="2202550">the</span>
  <span m="2202640">transactions</span> <span m="2203510">that</span> <span m="2203660">are</span>
  <span m="2203750">not</span> <span m="2204410">inject--</span> <span m="2204890">not</span>
  <span m="2205130">these</span> <span m="2205270">special</span> <span m="2205640">transactions</span>
  <span m="2206150">that</span> <span m="2206240">are</span> <span m="2206270">injecting</span>
  <span m="2206690">assets</span> <span m="2207080">or</span> <span m="2207160">removing</span>
  <span m="2207470">assets,</span> <span m="2207800">but</span> <span m="2208190">just</span>
  <span m="2208370">the</span> <span m="2208430">transfers.</span> <span m="2209210">We're</span>
  <span m="2209350">hiding</span> <span m="2209750">the</span> <span m="2209810">values</span>
  <span m="2210200">using</span> <span m="2210470">Pedersen</span> <span m="2210890">commitments,</span>
  <span m="2211550">OK?</span></p><p><span m="2212330">So</span> <span m="2212480">let's</span>
  <span m="2212690">look</span> <span m="2212900">at</span> <span m="2212990">how</span>
  <span m="2213350">auditing</span> <span m="2213710">might</span> <span m="2213860">work.</span>
  <span m="2214610">So</span> <span m="2214910">an</span> <span m="2215000">auditor</span>
  <span m="2215480">will</span> <span m="2215840">ask</span> <span m="2216170">the</span>
  <span m="2216290">bank--</span> <span m="2217100">in</span> <span m="2217190">this</span>
  <span m="2217340">case,</span> <span m="2217520">it's</span> <span m="2217670">Barclays.</span>
  <span m="2218390">So</span> <span m="2218540">remember,</span> <span m="2218900">Barclays</span>
  <span m="2219710">received</span> <span m="2221720">euros</span> <span m="2222140">in</span>
  <span m="2222230">two</span> <span m="2222410">different</span> <span m="2222650">transactions,</span>
  <span m="2223490">and</span> <span m="2223760">should</span> <span m="2224180">tell</span>
  <span m="2224360">the</span> <span m="2224480">auditor</span> <span m="2224780">3</span>
  <span m="2224990">million.</span> <span m="2226640">The</span> <span m="2226730">auditor</span>
  <span m="2227000">asks</span> <span m="2227210">Barclays,</span> <span m="2227600">how</span>
  <span m="2227660">many</span> <span m="2227840">euros</span> <span m="2228110">do
  you</span> <span m="2228260">hold?</span></p><p><span m="2229160">Barclays</span>
  <span m="2230150">can</span> <span m="2230690">convince</span> <span m="2231470">the</span>
  <span m="2231680">auditor</span> <span m="2232760">that</span> <span m="2233000">3</span>
  <span m="2233330">million</span> <span m="2233810">is</span> <span m="2234020">the</span>
  <span m="2234140">right</span> <span m="2234620">answer</span> <span m="2235280">by</span>
  <span m="2235520">doing</span> <span m="2235790">the</span> <span m="2235850">following.</span>
  <span m="2237110">OK?</span> <span m="2238550">Barclays</span> <span m="2239120">can</span>
  <span m="2239300">say,</span> <span m="2239690">hey,</span> <span m="2240110">auditor,</span>
  <span m="2240980">it's</span> <span m="2241190">3</span> <span m="2241490">million.</span>
  <span m="2242420">OK.</span> <span m="2243200">And</span> <span m="2243320">what</span>
  <span m="2243530">I'm</span> <span m="2243740">going</span> <span m="2244010">to</span>
  <span m="2244100">do</span> <span m="2244910">is</span> <span m="2245150">I'm</span>
  <span m="2245420">going</span> <span m="2245600">to</span> <span m="2245720">actually</span>
  <span m="2246290">open</span> <span m="2246890">up</span> <span m="2248720">the</span>
  <span m="2249230">combined</span> <span m="2250370">commitments</span> <span m="2251690">for</span>
  <span m="2251840">my</span> <span m="2252020">transactions.</span> <span m="2253070">So</span>
  <span m="2253400">I</span> <span m="2253520">don't</span> <span m="2253760">actually</span>
  <span m="2254060">have</span> <span m="2254330">this</span> <span m="2254600">on</span>
  <span m="2254750">a</span> <span m="2254780">slide</span> <span m="2255140">here,</span>
  <span m="2255350">but</span> <span m="2255530">I</span> <span m="2255650">will</span>
  <span m="2256520">write</span> <span m="2256820">out</span> <span m="2257210">what</span>
  <span m="2257420">this</span> <span m="2257660">means.</span> <span m="2258410">OK?</span></p><p><span
  m="2267030">So</span> <span m="2267360">we</span> <span m="2267540">have</span>
  <span m="2267900">two</span> <span m="2268200">transactions</span> <span m="2268890">here</span>
  <span m="2269610">and</span> <span m="2269790">two</span> <span m="2270030">commitments.</span>
  <span m="2270990">And</span> <span m="2271110">one</span> <span m="2271350">of</span>
  <span m="2271440">them</span> <span m="2271740">is</span> <span m="2271950">g</span>
  <span m="2272340">to</span> <span m="2272550">the</span> <span m="2273270">1</span>
  <span m="2273510">million,</span> <span m="2274680">h</span> <span m="2275250">to--</span>
  <span m="2275370">the</span> <span m="2275530">let's</span> <span m="2275760">just</span>
  <span m="2275910">r1.</span> <span m="2277140">And</span> <span m="2277260">then</span>
  <span m="2277380">the</span> <span m="2277530">other</span> <span m="2277890">is</span>
  <span m="2279960">g</span> <span m="2280710">to</span> <span m="2280860">the</span>
  <span m="2280980">2</span> <span m="2281340">million,</span> <span m="2282480">h</span>
  <span m="2283080">to</span> <span m="2283230">the</span> <span m="2283350">r2.</span>
  <span m="2284820">OK?</span> <span m="2285450">These</span> <span m="2285660">are</span>
  <span m="2285720">the</span> <span m="2285810">commitments</span> <span m="2286230">in</span>
  <span m="2286320">the</span> <span m="2286380">ledger.</span> <span m="2287760">Barclays</span>
  <span m="2288300">wants</span> <span m="2288570">to</span> <span m="2288660">convince</span>
  <span m="2289260">the</span> <span m="2289410">auditor</span> <span m="2290310">that</span>
  <span m="2290430">it</span> <span m="2290520">has</span> <span m="2290730">3</span>
  <span m="2290910">million</span> <span m="2291210">euros.</span></p><p><span m="2292260">It</span>
  <span m="2292380">does</span> <span m="2292680">so</span> <span m="2293760">by--</span>
  <span m="2294090">when</span> <span m="2294300">you</span> <span m="2294390">multiply</span>
  <span m="2294930">these</span> <span m="2295110">two</span> <span m="2295290">things</span>
  <span m="2295560">together,</span> <span m="2296460">and</span> <span m="2296820">the</span>
  <span m="2297000">auditor</span> <span m="2297480">can't</span> <span m="2297870">see</span>
  <span m="2298380">what</span> <span m="2298590">these</span> <span m="2298770">two</span>
  <span m="2298920">things</span> <span m="2299190">are,</span> <span m="2299640">but</span>
  <span m="2300270">this</span> <span m="2300480">is--</span> <span m="2304790">or</span>
  <span m="2305200">actually,</span> <span m="2305510">I think</span> <span m="2305680">it's</span>
  <span m="2305800">comm</span> <span m="2307570">2--</span> <span m="2307970">3.</span>
  <span m="2308620">OK,</span> <span m="2308830">comm</span> <span m="2309100">3</span>
  <span m="2309310">times</span> <span m="2309610">comm</span> <span m="2310990">4.</span>
  <span m="2313290">Then</span> <span m="2314070">when</span> <span m="2314280">you</span>
  <span m="2314370">multiply</span> <span m="2314910">these</span> <span m="2315090">two</span>
  <span m="2315210">things</span> <span m="2315450">together,</span> <span m="2316000">you</span>
  <span m="2316050">get</span> <span m="2316260">g</span> <span m="2316650">to</span>
  <span m="2316800">the</span> <span m="2316920">1</span> <span m="2317220">million</span>
  <span m="2318000">plus</span> <span m="2318390">2</span> <span m="2318600">million</span>
  <span m="2319830">h</span> <span m="2320490">to</span> <span m="2320640">the</span>
  <span m="2320760">r1</span> <span m="2321330">plus</span> <span m="2321820">r2,</span>
  <span m="2322890">OK?</span></p><p><span m="2325180">This</span> <span m="2325390">is</span>
  <span m="2325510">3</span> <span m="2325750">million.</span> <span m="2327210">If</span>
  <span m="2328170">Barclays</span> <span m="2329640">gives</span> <span m="2330180">the</span>
  <span m="2330360">auditor</span> <span m="2331880">3</span> <span m="2332190">million</span>
  <span m="2333720">and</span> <span m="2333900">r1</span> <span m="2335070">plus</span>
  <span m="2335440">r2,</span> <span m="2337410">the</span> <span m="2337500">sum,</span>
  <span m="2338560">than</span> <span m="2339030">the</span> <span m="2339750">auditor</span>
  <span m="2340230">can</span> <span m="2340470">confirm</span> <span m="2342150">that</span>
  <span m="2342330">if</span> <span m="2342450">they</span> <span m="2342780">raise</span>
  <span m="2343200">g</span> <span m="2344040">to</span> <span m="2344220">this</span>
  <span m="2344790">and</span> <span m="2344970">h</span> <span m="2345330">to</span>
  <span m="2345510">this,</span> <span m="2346500">that</span> <span m="2346890">it's</span>
  <span m="2347100">equal</span> <span m="2347490">to</span> <span m="2348270">the</span>
  <span m="2348360">multiplication</span> <span m="2349230">of</span> <span m="2349380">the</span>
  <span m="2349470">two</span> <span m="2349710">commitments</span> <span m="2350220">on</span>
  <span m="2350370">the</span> <span m="2350430">ledger.</span> <span m="2355420">And</span>
  <span m="2355870">the</span> <span m="2356050">auditor</span> <span m="2356770">can--</span>
  <span m="2358420">given</span> <span m="2358840">that</span> <span m="2358960">these</span>
  <span m="2359170">two</span> <span m="2359290">things</span> <span m="2359530">are</span>
  <span m="2359620">equal,</span> <span m="2360980">then</span> <span m="2361030">the</span>
  <span m="2361150">auditor</span> <span m="2361510">knows</span> <span m="2362860">that</span>
  <span m="2363190">the</span> <span m="2363340">bank</span> <span m="2363940">in</span>
  <span m="2364150">fact</span> <span m="2365050">did</span> <span m="2365410">commit</span>
  <span m="2365890">to two</span> <span m="2366100">commitments</span> <span m="2367450">that</span>
  <span m="2367630">sum</span> <span m="2367990">to</span> <span m="2368110">$3</span>
  <span m="2368320">million.</span></p><p><span m="2369520">It</span> <span m="2369970">doesn't</span>
  <span m="2370270">know</span> <span m="2370450">if</span> <span m="2370540">that</span>
  <span m="2370720">was</span> <span m="2370900">1.5</span> <span m="2371560">and</span>
  <span m="2371650">1.5,</span> <span m="2372940">or</span> <span m="2374350">1</span>
  <span m="2374830">and</span> <span m="2375280">2</span> <span m="2375520">million,</span>
  <span m="2375850">999--</span> <span m="2377500">it</span> <span m="2378100">doesn't</span>
  <span m="2378400">know</span> <span m="2379270">what</span> <span m="2379540">those</span>
  <span m="2379720">individual</span> <span m="2380140">values</span> <span m="2380560">were.</span>
  <span m="2381400">It</span> <span m="2381520">just</span> <span m="2381850">knows</span>
  <span m="2382540">that</span> <span m="2382690">the</span> <span m="2382810">sum</span>
  <span m="2383320">is</span> <span m="2383470">correct.</span> <span m="2387860">So,</span>
  <span m="2388040">questions</span> <span m="2388730">about</span> <span m="2389000">opening</span>
  <span m="2389330">commitments?</span> <span m="2390810">Yes?</span></p><p><span
  m="2391375">AUDIENCE:</span> <span m="2391547">The</span> <span m="2391720">sub-3,</span>
  <span m="2392170">sub-4--</span> <span m="2392440">those</span> <span m="2392820">are
  the</span> <span m="2393190">IDs?</span></p><p><span m="2394200">NEHA NARULA:</span>
  <span m="2394315">Yeah,</span> <span m="2394430">those</span> <span m="2394640">are</span>
  <span m="2395090">3</span> <span m="2395480">and</span> <span m="2395570">4.</span>
  <span m="2396110">Sorry,</span> <span m="2396560">I'm</span> <span m="2396680">using</span>
  <span m="2396920">different</span> <span m="2397220">numbers.</span> <span m="2397610">They're</span>
  <span m="2397760">r1</span> <span m="2397880">and</span> <span m="2398150">r2.</span>
  <span m="2398450">But</span> <span m="2399140">the</span> <span m="2399270">comm
  3</span> <span m="2399710">and</span> <span m="2399890">comm 4</span> <span m="2400190">are--</span>
  <span m="2401270">this</span> <span m="2401480">is</span> <span m="2401600">literally</span>
  <span m="2402680">a</span> <span m="2403560">elliptic</span> <span m="2403910">curve</span>
  <span m="2404210">point.</span> <span m="2405080">So</span> <span m="2406400">the</span>
  <span m="2406550">point</span> <span m="2407080">is</span> <span m="2407480">posted</span>
  <span m="2407960">to</span> <span m="2408110">the</span> <span m="2408200">ledger.</span>
  <span m="2410100">Yes?</span></p><p><span m="2410460">AUDIENCE:</span> <span m="2410690">Wouldn't</span>
  <span m="2410920">4 million</span> <span m="2412300">and</span> <span m="2412660">minus
  1 million</span> <span m="2413380">also</span> <span m="2413710">do that?</span></p><p><span
  m="2414180">NEHA NARULA:</span> <span m="2414255">It</span> <span m="2414330">would,</span>
  <span m="2414780">yes.</span> <span m="2415110">And</span> <span m="2415230">we'll</span>
  <span m="2415380">talk</span> <span m="2415560">about</span> <span m="2415740">how</span>
  <span m="2415860">we</span> <span m="2415950">address</span> <span m="2416250">that.</span></p><p><span
  m="2417630">AUDIENCE:</span> <span m="2417725">So</span> <span m="2417820">just</span>
  <span m="2418030">to</span> <span m="2418120">confirm,</span> <span m="2418540">the</span>
  <span m="2418640">bank</span> <span m="2419320">provides</span> <span m="2419800">both</span>
  <span m="2420140">the</span> <span m="2420220">3</span> <span m="2420520">million</span>
  <span m="2420880">number</span> <span m="2421330">and--</span></p><p><span m="2421880">NEHA
  NARULA:</span> <span m="2422055">And</span> <span m="2422230">r1</span> <span m="2422640">plus</span>
  <span m="2422920">r2.</span> <span m="2423430">Yes.</span> <span m="2424090">And</span>
  <span m="2424690">those</span> <span m="2425140">two</span> <span m="2425380">pieces</span>
  <span m="2425710">of</span> <span m="2425800">information</span> <span m="2426370">are</span>
  <span m="2426460">enough</span> <span m="2426760">to</span> <span m="2426880">convince</span>
  <span m="2427180">the</span> <span m="2427300">auditor</span> <span m="2427720">that</span>
  <span m="2428110">3</span> <span m="2428320">million</span> <span m="2428620">does</span>
  <span m="2428800">in</span> <span m="2428890">fact</span> <span m="2429190">correspond</span>
  <span m="2429670">to</span> <span m="2429760">the</span> <span m="2429820">commitments</span>
  <span m="2430360">on</span> <span m="2430450">the</span> <span m="2430510">ledger.</span>
  <span m="2431440">Yes?</span></p><p><span m="2431750">AUDIENCE:</span> <span m="2432050">[INAUDIBLE]</span>
  <span m="2433270">so</span> <span m="2433840">you</span> <span m="2433990">will</span>
  <span m="2434140">always</span> <span m="2434530">get</span> <span m="2434800">the</span>
  <span m="2434930">sum</span> <span m="2435420">and</span> <span m="2435820">the</span>
  <span m="2435930">number</span> <span m="2436140">of</span> <span m="2436570">transactions?</span></p><p><span
  m="2438720">NEHA NARULA:</span> <span m="2438890">Sorry?</span></p><p><span m="2439060">AUDIENCE:</span>
  <span m="2439217">You</span> <span m="2439375">will get</span> <span m="2439690">the
  number of</span> <span m="2439980">transactions?</span></p><p><span m="2440200">NEHA
  NARULA:</span> <span m="2440420">Who's</span> <span m="2440640">you?</span></p><p><span
  m="2441100">AUDIENCE:</span> <span m="2441272">Oh,</span> <span m="2441445">[INAUDIBLE]</span>
  <span m="2441790">as</span> <span m="2441940">in</span> <span m="2442950">the</span>
  <span m="2443160">auditor.</span></p><p><span m="2443790">NEHA NARULA:</span> <span
  m="2443850">The</span> <span m="2443910">auditor</span> <span m="2444360">will</span>
  <span m="2444540">get--</span></p><p><span m="2445460">AUDIENCE:</span> <span m="2445550">They</span>
  <span m="2445640">will</span> <span m="2445910">know</span> <span m="2446370">the</span>
  <span m="2446910">number</span> <span m="2447180">of</span> <span m="2447240">transactions?</span></p><p><span
  m="2448110">NEHA NARULA:</span> <span m="2448185">In</span> <span m="2448260">the</span>
  <span m="2448360">straw</span> <span m="2448740">man</span> <span m="2448980">example</span>
  <span m="2449490">that</span> <span m="2449640">I've</span> <span m="2449790">done,</span>
  <span m="2450990">it</span> <span m="2451080">does</span> <span m="2451260">look</span>
  <span m="2451470">that</span> <span m="2451620">way,</span> <span m="2452010">yes.</span>
  <span m="2452790">I'm</span> <span m="2452880">going</span> <span m="2452960">to</span>
  <span m="2453090">build</span> <span m="2453390">up</span> <span m="2453540">to</span>
  <span m="2453780">how</span> <span m="2453960">the</span> <span m="2454080">auditor</span>
  <span m="2454380">won't</span> <span m="2454560">know</span> <span m="2454710">the</span>
  <span m="2454800">number</span> <span m="2454980">of</span> <span m="2455070">transactions.</span>
  <span m="2456330">Did</span> <span m="2456420">you</span> <span m="2456480">have</span>
  <span m="2456570">a</span> <span m="2456600">question?</span></p><p><span m="2459430">AUDIENCE:</span>
  <span m="2459540">So</span> <span m="2459870">as</span> <span m="2460050">a</span>
  <span m="2460200">user,</span> <span m="2460500">you are</span> <span m="2460740">recording</span>
  <span m="2461610">all</span> <span m="2461790">of</span> <span m="2461910">your</span>
  <span m="2462110">randomness?</span> <span m="2462610">You're</span> <span m="2462800">responsible</span>
  <span m="2463080">for</span> <span m="2463350">tracking</span> <span m="2463570">all
  of</span> <span m="2463820">your</span> <span m="2464010">randomness?</span></p><p><span
  m="2464310">NEHA NARULA:</span> <span m="2464410">You're</span> <span m="2464510">responsible</span>
  <span m="2464610">for</span> <span m="2464730">tracking</span> <span m="2465210">your</span>
  <span m="2465300">randomness.</span> <span m="2465960">And</span> <span m="2466230">you're</span>
  <span m="2466470">responsible</span> <span m="2467160">for</span> <span m="2467310">tracking</span>
  <span m="2468720">your</span> <span m="2468960">own</span> <span m="2469200">individual</span>
  <span m="2469680">details.</span> <span m="2470500">You</span> <span m="2470550">have</span>
  <span m="2470700">to</span> <span m="2470790">keep</span> <span m="2471030">that</span>
  <span m="2471300">in</span> <span m="2471390">your</span> <span m="2471540">own</span>
  <span m="2471660">databases.</span> <span m="2472320">Yes?</span></p><p><span m="2473462">AUDIENCE:</span>
  <span m="2473672">If</span> <span m="2473883">somebody</span> <span m="2474304">found</span>
  <span m="2474725">your</span> <span m="2475150">randomness--</span></p><p><span
  m="2476910">NEHA NARULA:</span> <span m="2477000">If</span> <span m="2477090">someone</span>
  <span m="2477360">found</span> <span m="2477570">your</span> <span m="2477660">randomnesses,</span>
  <span m="2478980">then</span> <span m="2480090">they</span> <span m="2480270">could</span>
  <span m="2480540">guess--</span> <span m="2481110">they</span> <span m="2481260">could</span>
  <span m="2481830">backwards-compute</span> <span m="2482790">the</span> <span m="2482910">values</span>
  <span m="2483270">of</span> <span m="2483360">your</span> <span m="2483480">transactions.</span>
  <span m="2484260">Yes.</span> <span m="2487160">OK.</span></p><p><span m="2487650">AUDIENCE:</span>
  <span m="2487710">How</span> <span m="2487770">do</span> <span m="2487830">you</span>
  <span m="2487890">define</span> <span m="2488240">the</span> <span m="2488670">timing?</span></p><p><span
  m="2489530">NEHA NARULA:</span> <span m="2489590">The</span> <span m="2489650">time--</span>
  <span m="2490730">getting</span> <span m="2490970">to</span> <span m="2491060">that.</span>
  <span m="2491980">So</span> <span m="2492190">we'll</span> <span m="2492530">get</span>
  <span m="2492710">to</span> <span m="2492800">that.</span> <span m="2494360">So</span>
  <span m="2495590">just</span> <span m="2496190">in</span> <span m="2496280">figures,</span>
  <span m="2496670">showing</span> <span m="2496910">what</span> <span m="2497030">we</span>
  <span m="2497120">did</span> <span m="2497270">there.</span> <span m="2497630">The</span>
  <span m="2497750">auditor</span> <span m="2498110">can</span> <span m="2498290">look</span>
  <span m="2498620">at</span> <span m="2498710">those</span> <span m="2498920">two</span>
  <span m="2499040">commitments,</span> <span m="2500060">compute</span> <span m="2500390">the</span>
  <span m="2500480">product</span> <span m="2500810">for</span> <span m="2500930">themselves,</span>
  <span m="2502070">and</span> <span m="2502790">confirm</span> <span m="2503390">that</span>
  <span m="2503510">this</span> <span m="2503660">3</span> <span m="2503870">million</span>
  <span m="2504290">lines</span> <span m="2504620">up</span> <span m="2504710">with</span>
  <span m="2504830">what</span> <span m="2504920">they</span> <span m="2505040">see.</span></p><p><span
  m="2505910">However,</span> <span m="2506390">this</span> <span m="2506570">has</span>
  <span m="2506750">the</span> <span m="2506840">problem</span> <span m="2507770">that</span>
  <span m="2508430">it</span> <span m="2508670">reveals</span> <span m="2509450">the</span>
  <span m="2509540">transactions</span> <span m="2510350">in</span> <span m="2510500">which</span>
  <span m="2510740">Barclays</span> <span m="2511220">was</span> <span m="2511370">involved,</span>
  <span m="2512150">right?</span> <span m="2513020">Barclays</span> <span m="2513500">is</span>
  <span m="2513560">saying,</span> <span m="2513980">hey,</span> <span m="2514220">multiply</span>
  <span m="2514670">these</span> <span m="2514880">two</span> <span m="2515030">things</span>
  <span m="2515300">together,</span> <span m="2515840">right?</span></p><p><span m="2516560">And</span>
  <span m="2516710">not</span> <span m="2516860">only</span> <span m="2517070">that,</span>
  <span m="2517640">Barclays</span> <span m="2518660">could</span> <span m="2519020">lie.</span>
  <span m="2520010">OK?</span> <span m="2520430">Barclays</span> <span m="2520970">could</span>
  <span m="2521120">say,</span> <span m="2521540">oh,</span> <span m="2522830">actually,</span>
  <span m="2523670">I</span> <span m="2523910">only</span> <span m="2524330">have</span>
  <span m="2524480">1</span> <span m="2524750">million</span> <span m="2525080">euros.</span>
  <span m="2525700">Here's</span> <span m="2526040">the</span> <span m="2526130">transaction</span>
  <span m="2527030">that</span> <span m="2527180">proves</span> <span m="2527600">that</span>
  <span m="2527720">I</span> <span m="2527810">have</span> <span m="2527960">1</span>
  <span m="2528140">million</span> <span m="2528410">euros.</span> <span m="2529040">I</span>
  <span m="2529160">will</span> <span m="2529280">just</span> <span m="2529460">give</span>
  <span m="2529640">you</span> <span m="2529990">our one.</span> <span m="2530870">I</span>
  <span m="2530920">will</span> <span m="2531020">just</span> <span m="2531260">point</span>
  <span m="2531470">to</span> <span m="2531560">this</span> <span m="2531710">transaction.</span>
  <span m="2532760">Don't</span> <span m="2532970">worry</span> <span m="2533150">about</span>
  <span m="2533330">the</span> <span m="2533450">other</span> <span m="2533630">transactions.</span>
  <span m="2534410">I'm</span> <span m="2534590">not</span> <span m="2534710">involved</span>
  <span m="2535070">in</span> <span m="2535160">them.</span></p><p><span m="2536010">The</span>
  <span m="2537080">bank,</span> <span m="2537470">Barclays,</span> <span m="2538040">could</span>
  <span m="2538220">leave</span> <span m="2538730">out</span> <span m="2539510">relevant</span>
  <span m="2539990">important</span> <span m="2540380">transactions</span> <span m="2541360">in</span>
  <span m="2541730">this</span> <span m="2541940">straw</span> <span m="2542360">man</span>
  <span m="2542990">design.</span> <span m="2544040">OK?</span> <span m="2546660">And</span>
  <span m="2547190">importantly,</span> <span m="2548300">this</span> <span m="2548480">would</span>
  <span m="2548630">match</span> <span m="2548990">up,</span> <span m="2549260">right?</span>
  <span m="2549740">The</span> <span m="2549890">auditor</span> <span m="2550160">would</span>
  <span m="2550310">say,</span> <span m="2550560">OK,</span> <span m="2551600">you've</span>
  <span m="2551750">given</span> <span m="2552020">me--</span> <span m="2553430">Barclays</span>
  <span m="2553910">could</span> <span m="2554060">just</span> <span m="2554420">give--</span>
  <span m="2558650">could</span> <span m="2558800">leave</span> <span m="2559010">this</span>
  <span m="2559130">part</span> <span m="2559310">out</span> <span m="2559430">entirely.</span>
  <span m="2560030">Could</span> <span m="2560210">just</span> <span m="2560510">give</span>
  <span m="2562150">1</span> <span m="2562400">million</span> <span m="2563630">and</span>
  <span m="2564410">r1,</span> <span m="2565490">and</span> <span m="2566780">the</span>
  <span m="2566870">auditor</span> <span m="2567140">would</span> <span m="2567260">say,</span>
  <span m="2567410">why,</span> <span m="2567590">yes,</span> <span m="2567950">that</span>
  <span m="2568130">does</span> <span m="2568370">match</span> <span m="2568610">up</span>
  <span m="2568730">to</span> <span m="2568850">commitment</span> <span m="2569180">three.</span>
  <span m="2569990">Great.</span> <span m="2570470">Good</span> <span m="2570650">work.</span>
  <span m="2571100">And</span> <span m="2571220">they</span> <span m="2571340">wouldn't</span>
  <span m="2571520">even</span> <span m="2571670">know</span> <span m="2572210">that</span>
  <span m="2572330">there</span> <span m="2572420">was</span> <span m="2572570">another</span>
  <span m="2572810">commitment</span> <span m="2573170">out</span> <span m="2573290">there</span>
  <span m="2573530">that</span> <span m="2573680">they</span> <span m="2573800">should</span>
  <span m="2573980">be</span> <span m="2574100">concerned</span> <span m="2574520">about.</span></p><p><span
  m="2576500">So</span> <span m="2578260">how</span> <span m="2578560">do</span> <span
  m="2578650">we</span> <span m="2578800">address</span> <span m="2579070">this</span>
  <span m="2579220">problem?</span> <span m="2583300">And</span> <span m="2583420">this,</span>
  <span m="2583630">I</span> <span m="2583720">think,</span> <span m="2583870">was</span>
  <span m="2584440">the</span> <span m="2584530">key</span> <span m="2584770">insight</span>
  <span m="2585340">in</span> <span m="2585460">the</span> <span m="2585550">design</span>
  <span m="2585940">of</span> <span m="2586060">our</span> <span m="2586150">system.</span>
  <span m="2588510">In</span> <span m="2588660">zkLedger,</span> <span m="2590190">a</span>
  <span m="2590250">transaction</span> <span m="2591690">actually</span> <span m="2592290">has</span>
  <span m="2592800">a</span> <span m="2592860">commitment</span> <span m="2593520">for</span>
  <span m="2593880">every</span> <span m="2594360">participant</span> <span m="2595260">in</span>
  <span m="2595380">the</span> <span m="2595470">system.</span> <span m="2596970">So</span>
  <span m="2597440">let's</span> <span m="2597650">talk</span> <span m="2597830">about</span>
  <span m="2598040">that</span> <span m="2598190">for</span> <span m="2598340">a</span>
  <span m="2598400">second.</span></p><p><span m="2600210">So</span> <span m="2601460">depositor</span>
  <span m="2602060">transactions</span> <span m="2602690">still</span> <span m="2603050">basically</span>
  <span m="2603530">look</span> <span m="2603800">the</span> <span m="2603920">way</span>
  <span m="2604070">that</span> <span m="2604190">they</span> <span m="2604310">did</span>
  <span m="2604610">before</span> <span m="2605030">they're</span> <span m="2605180">public.</span>
  <span m="2606050">But</span> <span m="2606380">transfer</span> <span m="2607070">transactions</span>
  <span m="2607760">now</span> <span m="2607970">look</span> <span m="2608210">quite</span>
  <span m="2608780">different.</span> <span m="2610110">We</span> <span m="2610160">don't</span>
  <span m="2610370">actually</span> <span m="2611060">have</span> <span m="2612200">the</span>
  <span m="2613520">names</span> <span m="2614330">of</span> <span m="2614450">the</span>
  <span m="2614540">participant</span> <span m="2615140">in</span> <span m="2615260">the</span>
  <span m="2615320">transaction.</span> <span m="2616460">The</span> <span m="2616580">names</span>
  <span m="2616940">are</span> <span m="2617030">implied</span> <span m="2618320">by</span>
  <span m="2618920">the</span> <span m="2619040">values</span> <span m="2619550">of</span>
  <span m="2619640">the</span> <span m="2619730">commitments</span> <span m="2620840">in</span>
  <span m="2621680">that</span> <span m="2621830">participants</span> <span m="2622340">column.</span></p><p><span
  m="2623310">So</span> <span m="2623360">now</span> <span m="2623630">we're</span>
  <span m="2624110">looking</span> <span m="2624560">at</span> <span m="2624860">a</span>
  <span m="2624890">transaction</span> <span m="2625850">as</span> <span m="2626030">a</span>
  <span m="2626090">row</span> <span m="2627050">with</span> <span m="2627230">multiple</span>
  <span m="2627680">columns.</span> <span m="2628910">And</span> <span m="2629750">there's</span>
  <span m="2629990">a</span> <span m="2630020">column</span> <span m="2631010">per</span>
  <span m="2631340">participant</span> <span m="2632150">in</span> <span m="2632360">the</span>
  <span m="2632480">system.</span> <span m="2633860">If</span> <span m="2634160">a</span>
  <span m="2634220">bank</span> <span m="2634520">is</span> <span m="2634670">not</span>
  <span m="2635120">involved</span> <span m="2635810">in</span> <span m="2635930">the</span>
  <span m="2635990">transaction</span> <span m="2636770">at</span> <span m="2636950">all,</span>
  <span m="2637790">then</span> <span m="2637970">their</span> <span m="2638090">commitment</span>
  <span m="2638510">is</span> <span m="2638630">to</span> <span m="2638750">the</span>
  <span m="2638840">value</span> <span m="2639260">0.</span> <span m="2640640">If</span>
  <span m="2640880">the</span> <span m="2640970">bank</span> <span m="2641360">is</span>
  <span m="2641720">involved</span> <span m="2642110">in</span> <span m="2642200">a</span>
  <span m="2642260">transaction,</span> <span m="2643400">and</span> <span m="2643760">it's</span>
  <span m="2644000">doing</span> <span m="2644390">the</span> <span m="2644630">spending,</span>
  <span m="2645920">then</span> <span m="2646340">its</span> <span m="2646580">value--</span>
  <span m="2647300">sorry,</span> <span m="2647660">depositor</span> <span m="2648080">transactions.</span>
  <span m="2648590">Yes.</span></p><p><span m="2649580">If</span> <span m="2649750">a</span>
  <span m="2649820">bank</span> <span m="2650120">is</span> <span m="2650450">involved</span>
  <span m="2651440">in</span> <span m="2651680">the</span> <span m="2651800">transaction,</span>
  <span m="2652430">it's</span> <span m="2652580">doing</span> <span m="2653090">the</span>
  <span m="2653240">spending,</span> <span m="2653960">it</span> <span m="2654050">commits</span>
  <span m="2654350">to</span> <span m="2654470">a</span> <span m="2654530">negative</span>
  <span m="2654980">value.</span> <span m="2655940">And</span> <span m="2656060">if</span>
  <span m="2656150">it's</span> <span m="2656300">doing</span> <span m="2656540">the</span>
  <span m="2656600">receiving,</span> <span m="2657290">it</span> <span m="2657380">commits--</span>
  <span m="2658920">sorry,</span> <span m="2659230">not</span> <span m="2659480">it,</span>
  <span m="2659690">but</span> <span m="2659840">the</span> <span m="2659930">creator</span>
  <span m="2660320">of</span> <span m="2660380">the</span> <span m="2660440">transaction,</span>
  <span m="2661010">commits</span> <span m="2661310">to</span> <span m="2661430">a</span>
  <span m="2661490">positive</span> <span m="2661940">value.</span> <span m="2662810">So</span>
  <span m="2662960">the</span> <span m="2663050">way</span> <span m="2663320">that</span>
  <span m="2663440">you</span> <span m="2663560">transfer</span> <span m="2664040">$1</span>
  <span m="2664250">million</span> <span m="2664550">from</span> <span m="2665510">one</span>
  <span m="2665720">bank</span> <span m="2665930">to</span> <span m="2666110">another</span>
  <span m="2666740">is</span> <span m="2666860">committing</span> <span m="2667160">to</span>
  <span m="2667280">a</span> <span m="2667340">negative</span> <span m="2667970">value</span>
  <span m="2668450">in</span> <span m="2668600">the</span> <span m="2668690">spenders</span>
  <span m="2669170">column--</span> <span m="2669590">here,</span> <span m="2669830">JP</span>
  <span m="2670130">Morgan--</span> <span m="2670840">and</span> <span m="2670940">committing</span>
  <span m="2671240">to</span> <span m="2671330">a</span> <span m="2671390">positive</span>
  <span m="2671840">value</span> <span m="2672490">in</span> <span m="2672590">the</span>
  <span m="2672650">receivers</span> <span m="2673130">column--</span> <span m="2673570">here,</span>
  <span m="2674000">Barclays.</span></p><p><span m="2681760">And</span> <span m="2681880">again</span>
  <span m="2682240">for</span> <span m="2682450">non-involved</span> <span m="2683320">banks,</span>
  <span m="2684010">entries</span> <span m="2684370">commit</span> <span m="2684670">to</span>
  <span m="2684790">0.</span> <span m="2685570">But</span> <span m="2685750">one</span>
  <span m="2685960">thing</span> <span m="2686200">I</span> <span m="2686290">want</span>
  <span m="2686590">to</span> <span m="2686770">stress--</span> <span m="2687820">commitments</span>
  <span m="2688360">to</span> <span m="2688540">0</span> <span m="2689110">are</span>
  <span m="2689230">completely</span> <span m="2690010">indistinguishable</span> <span
  m="2691600">from</span> <span m="2691840">commitments</span> <span m="2693160">to</span>
  <span m="2693310">any</span> <span m="2693490">other</span> <span m="2693670">value.</span>
  <span m="2694060">And</span> <span m="2694180">commitments</span> <span m="2694570">to</span>
  <span m="2694690">negative</span> <span m="2695050">values</span> <span m="2695530">are</span>
  <span m="2696070">indistinguishable</span> <span m="2697000">from</span> <span m="2697180">commitments</span>
  <span m="2697540">to</span> <span m="2697660">positive</span> <span m="2698050">values.</span></p><p><span
  m="2698770">So</span> <span m="2698950">someone</span> <span m="2699400">looking</span>
  <span m="2699820">at</span> <span m="2699940">this,</span> <span m="2701670">just</span>
  <span m="2701850">looking</span> <span m="2702270">at</span> <span m="2702360">these</span>
  <span m="2702540">commitments</span> <span m="2703050">posted</span> <span m="2703330">to</span>
  <span m="2703500">the</span> <span m="2703560">ledger,</span> <span m="2703890">has</span>
  <span m="2704130">no</span> <span m="2704520">idea</span> <span m="2704790">which</span>
  <span m="2705000">ones</span> <span m="2705210">are</span> <span m="2705270">0s,</span>
  <span m="2705870">and</span> <span m="2705990">which</span> <span m="2706170">ones</span>
  <span m="2706380">are</span> <span m="2706470">negative,</span> <span m="2706830">and</span>
  <span m="2706920">which</span> <span m="2707070">ones</span> <span m="2707220">are</span>
  <span m="2707280">positive.</span> <span m="2709410">Yes?</span></p><p><span m="2709740">AUDIENCE:</span>
  <span m="2709845">Does</span> <span m="2709950">this</span> <span m="2710090">mean</span>
  <span m="2710300">that</span> <span m="2711030">each</span> <span m="2711240">bank</span>
  <span m="2711570">has</span> <span m="2712020">to keep track</span> <span m="2712470">of
  every</span> <span m="2712830">transaction</span> <span m="2713160">that</span>
  <span m="2713280">is</span> <span m="2713440">done</span> <span m="2713880">in</span>
  <span m="2714060">the</span> <span m="2715350">ledger,</span> <span m="2715860">and</span>
  <span m="2716010">produce</span> <span m="2716300">the</span> <span m="2716590">random</span>
  <span m="2716820">numbers,</span> <span m="2717270">and</span> <span m="2717360">keep</span>
  <span m="2717550">track</span> <span m="2717740">of</span> <span m="2717830">those</span>
  <span m="2717970">numbers, too?</span></p><p><span m="2718390">NEHA NARULA:</span>
  <span m="2718475">Great</span> <span m="2718560">question.</span> <span m="2719920">So,</span>
  <span m="2720990">yeah,</span> <span m="2721440">one</span> <span m="2721830">design</span>
  <span m="2722490">might</span> <span m="2722850">have</span> <span m="2723180">it</span>
  <span m="2723300">be</span> <span m="2723450">the</span> <span m="2723540">case</span>
  <span m="2723840">that</span> <span m="2723960">every</span> <span m="2724470">bank</span>
  <span m="2724800">actually</span> <span m="2725220">has</span> <span m="2725490">to</span>
  <span m="2725610">be</span> <span m="2725760">involved</span> <span m="2726300">in</span>
  <span m="2726390">every</span> <span m="2726600">transaction.</span> <span m="2727590">We</span>
  <span m="2727740">managed</span> <span m="2728310">to</span> <span m="2728580">design</span>
  <span m="2728910">zkLedger</span> <span m="2729900">so</span> <span m="2730110">that</span>
  <span m="2730620">the</span> <span m="2730710">spending</span> <span m="2731430">bank</span>
  <span m="2732030">can</span> <span m="2732240">produce</span> <span m="2732690">one</span>
  <span m="2732870">of</span> <span m="2732960">these</span> <span m="2733230">without</span>
  <span m="2733740">actually</span> <span m="2734310">involving</span> <span m="2734820">any</span>
  <span m="2735000">of</span> <span m="2735060">the</span> <span m="2735150">other</span>
  <span m="2735330">banks.</span> <span m="2737840">And</span> <span m="2738000">I</span>
  <span m="2738090">will</span> <span m="2738180">describe</span> <span m="2738510">how</span>
  <span m="2738600">that</span> <span m="2738720">happens.</span></p><p><span m="2744810">OK,</span>
  <span m="2746570">and</span> <span m="2746720">so,</span> <span m="2747290">given</span>
  <span m="2747770">now</span> <span m="2748280">that</span> <span m="2748460">we've</span>
  <span m="2748670">said,</span> <span m="2749420">essentially,</span> <span m="2749960">every</span>
  <span m="2750290">bank</span> <span m="2750560">is</span> <span m="2750650">involved</span>
  <span m="2751010">in</span> <span m="2751070">every</span> <span m="2751280">transaction,</span>
  <span m="2752450">this</span> <span m="2752600">actually</span> <span m="2752960">makes</span>
  <span m="2753200">life</span> <span m="2753440">easier</span> <span m="2753800">for</span>
  <span m="2753920">the</span> <span m="2754040">auditor.</span> <span m="2754730">Because</span>
  <span m="2754970">now</span> <span m="2755240">when</span> <span m="2755390">the</span>
  <span m="2755480">auditor</span> <span m="2755810">audits</span> <span m="2756110">a</span>
  <span m="2756140">bank,</span> <span m="2756620">they</span> <span m="2756800">audit</span>
  <span m="2757550">every</span> <span m="2757970">transaction.</span> <span m="2759630">So</span>
  <span m="2759680">they</span> <span m="2759800">audit</span> <span m="2760550">the</span>
  <span m="2760700">entire</span> <span m="2761420">column</span> <span m="2762290">for</span>
  <span m="2762710">a</span> <span m="2762770">bank.</span></p><p><span m="2763400">So</span>
  <span m="2763580">here,</span> <span m="2763880">when</span> <span m="2764030">the</span>
  <span m="2764120">auditor</span> <span m="2764480">is</span> <span m="2764630">auditing</span>
  <span m="2764960">Barclays,</span> <span m="2766190">they</span> <span m="2766340">won't</span>
  <span m="2766580">just</span> <span m="2766910">look</span> <span m="2767150">at</span>
  <span m="2767240">whatever</span> <span m="2767600">transactions</span> <span m="2768260">Barclays</span>
  <span m="2768800">tells</span> <span m="2769250">them</span> <span m="2769400">to</span>
  <span m="2769550">look</span> <span m="2769760">at.</span> <span m="2770210">They</span>
  <span m="2770360">will</span> <span m="2770480">look</span> <span m="2770780">at</span>
  <span m="2771170">every</span> <span m="2771710">transaction.</span> <span m="2772770">OK?</span>
  <span m="2773390">And</span> <span m="2773600">this</span> <span m="2773840">is</span>
  <span m="2773990">where--</span> <span m="2774650">I</span> <span m="2774710">think</span>
  <span m="2774830">someone</span> <span m="2775040">asked</span> <span m="2775340">about</span>
  <span m="2775610">timing,</span> <span m="2776300">or</span> <span m="2777260">how</span>
  <span m="2777470">do</span> <span m="2777530">you</span> <span m="2777920">audit</span>
  <span m="2778790">a</span> <span m="2778850">range</span> <span m="2779300">of</span>
  <span m="2779360">transactions?</span> <span m="2780500">The</span> <span m="2780650">auditor</span>
  <span m="2781010">can</span> <span m="2781190">actually</span> <span m="2781730">tell</span>
  <span m="2781910">the</span> <span m="2782000">bank,</span> <span m="2782300">oh,</span>
  <span m="2782480">I</span> <span m="2782570">just</span> <span m="2783020">want</span>
  <span m="2783200">to</span> <span m="2783290">audit</span> <span m="2784160">from</span>
  <span m="2784400">this</span> <span m="2784580">point</span> <span m="2784850">onwards.</span>
  <span m="2785680">Or</span> <span m="2786170">it</span> <span m="2786260">can</span>
  <span m="2786380">say,</span> <span m="2786530">I</span> <span m="2786620">just</span>
  <span m="2786800">want</span> <span m="2786950">to</span> <span m="2787010">audit</span>
  <span m="2787220">your</span> <span m="2787310">transactions</span> <span m="2787820">for</span>
  <span m="2787910">the</span> <span m="2788000">past</span> <span m="2788300">month,</span>
  <span m="2789320">if</span> <span m="2789470">it</span> <span m="2789530">wants</span>
  <span m="2789890">to.</span></p><p><span m="2791030">That</span> <span m="2791240">doesn't</span>
  <span m="2791540">mean</span> <span m="2791660">that</span> <span m="2791750">Barclays</span>
  <span m="2792230">can</span> <span m="2792410">leave</span> <span m="2792710">out</span>
  <span m="2792980">transactions,</span> <span m="2793790">because</span> <span m="2795860">there's</span>
  <span m="2796070">supposed</span> <span m="2796370">to</span> <span m="2796430">be</span>
  <span m="2796490">a</span> <span m="2796550">time</span> <span m="2796700">stamp</span>
  <span m="2797120">column</span> <span m="2797450">in</span> <span m="2797570">here</span>
  <span m="2797720">as</span> <span m="2797810">well.</span> <span m="2798090">So</span>
  <span m="2798110">you</span> <span m="2798170">can</span> <span m="2798290">see</span>
  <span m="2798440">when</span> <span m="2798680">transactions</span> <span m="2799250">happen.</span>
  <span m="2799820">That's</span> <span m="2800000">public.</span></p><p><span m="2801440">So</span>
  <span m="2801830">what</span> <span m="2802010">happens</span> <span m="2802310">here</span>
  <span m="2802850">is</span> <span m="2802970">the</span> <span m="2803060">auditor</span>
  <span m="2803260">is</span> <span m="2803360">going</span> <span m="2803490">to</span>
  <span m="2803570">look</span> <span m="2803720">at</span> <span m="2803810">everything.</span>
  <span m="2804950">They're</span> <span m="2805130">actually</span> <span m="2805580">going</span>
  <span m="2805820">to</span> <span m="2806600">multiply</span> <span m="2807530">three</span>
  <span m="2808160">commitments</span> <span m="2808970">together,</span> <span m="2809990">because</span>
  <span m="2811070">there's</span> <span m="2811280">three</span> <span m="2811490">commitments</span>
  <span m="2811820">in</span> <span m="2811910">that</span> <span m="2812000">column.</span>
  <span m="2812430">And</span> <span m="2812530">it</span> <span m="2812630">doesn't</span>
  <span m="2812750">know</span> <span m="2812870">which</span> <span m="2813080">ones</span>
  <span m="2813260">are</span> <span m="2813350">0</span> <span m="2813650">and</span>
  <span m="2813740">which</span> <span m="2813890">ones</span> <span m="2814070">are</span>
  <span m="2814160">not</span> <span m="2814340">0.</span> <span m="2814970">But</span>
  <span m="2815180">the</span> <span m="2815270">0</span> <span m="2815810">doesn't</span>
  <span m="2816080">contribute</span> <span m="2816470">to</span> <span m="2816560">the</span>
  <span m="2816680">sum.</span></p><p><span m="2820350">And</span> <span m="2820400">so</span>
  <span m="2821060">a</span> <span m="2821120">malicious</span> <span m="2821570">bank</span>
  <span m="2822740">can't</span> <span m="2823250">actually</span> <span m="2824290">lie</span>
  <span m="2824560">to</span> <span m="2824630">the</span> <span m="2824780">auditor,</span>
  <span m="2825620">because</span> <span m="2826490">in</span> <span m="2826640">this</span>
  <span m="2826910">case,</span> <span m="2831950">the</span> <span m="2831970">bank</span>
  <span m="2832240">is</span> <span m="2832390">not</span> <span m="2832780">going</span>
  <span m="2833050">to</span> <span m="2833140">leave</span> <span m="2833440">out</span>
  <span m="2834100">commitment</span> <span m="2834490">four.</span> <span m="2835560">And</span>
  <span m="2835690">in</span> <span m="2835780">fact,</span> <span m="2836080">it's</span>
  <span m="2836230">also</span> <span m="2836530">going</span> <span m="2836740">to</span>
  <span m="2836830">include</span> <span m="2838450">commitment</span> <span m="2838870">two.</span>
  <span m="2849740">So</span> <span m="2853100">the</span> <span m="2853580">bank</span>
  <span m="2853790">is</span> <span m="2853880">going</span> <span m="2854000">to</span>
  <span m="2854090">have</span> <span m="2854330">to</span> <span m="2854870">include</span>
  <span m="2856450">the</span> <span m="2856640">r</span> <span m="2856790">primes</span>
  <span m="2857150">in</span> <span m="2857240">here</span> <span m="2857390">to</span>
  <span m="2857480">get</span> <span m="2857690">all</span> <span m="2857840">of</span>
  <span m="2857930">this</span> <span m="2858200">to</span> <span m="2858350">work</span>
  <span m="2858560">out</span> <span m="2858830">correctly.</span> <span m="2859280">It's</span>
  <span m="2859400">going</span> <span m="2859520">to</span> <span m="2859580">have</span>
  <span m="2859670">to</span> <span m="2859760">include</span> <span m="2860000">everything.</span></p><p><span
  m="2869000">So</span> <span m="2871080">this</span> <span m="2871440">next--</span>
  <span m="2871980">I'm</span> <span m="2872190">actually</span> <span m="2872520">going</span>
  <span m="2872730">to</span> <span m="2872910">skip</span> <span m="2873540">a</span>
  <span m="2873630">little</span> <span m="2873870">bit</span> <span m="2875260">of</span>
  <span m="2875440">this,</span> <span m="2876040">because</span> <span m="2876820">I</span>
  <span m="2876880">think</span> <span m="2877090">we're</span> <span m="2877420">running</span>
  <span m="2877690">a</span> <span m="2877720">bit</span> <span m="2877840">low</span>
  <span m="2878020">on</span> <span m="2878110">time.</span> <span m="2878530">And</span>
  <span m="2878650">I</span> <span m="2878740">do</span> <span m="2878920">want</span>
  <span m="2879070">to</span> <span m="2879130">get</span> <span m="2879250">into</span>
  <span m="2879460">what</span> <span m="2879610">the</span> <span m="2879670">proofs</span>
  <span m="2880000">look</span> <span m="2880180">like.</span> <span m="2880480">So</span>
  <span m="2880840">I'm</span> <span m="2880960">going</span> <span m="2881170">to</span>
  <span m="2881260">skip</span> <span m="2881560">this</span> <span m="2882220">averages</span>
  <span m="2883030">part.</span> <span m="2885370">I'm</span> <span m="2885520">going</span>
  <span m="2885880">to</span> <span m="2886450">go</span> <span m="2886660">back</span>
  <span m="2886960">to</span> <span m="2888310">our</span> <span m="2888430">security</span>
  <span m="2888880">goals.</span></p><p><span m="2891790">What</span> <span m="2891970">I</span>
  <span m="2892060">just</span> <span m="2892270">described</span> <span m="2892720">to</span>
  <span m="2892810">you,</span> <span m="2892960">the</span> <span m="2893380">ledger</span>
  <span m="2893800">table</span> <span m="2894250">construction,</span> <span m="2895360">allows</span>
  <span m="2895780">us</span> <span m="2895960">to</span> <span m="2896140">achieve</span>
  <span m="2896560">our</span> <span m="2896650">first</span> <span m="2897040">two</span>
  <span m="2897400">security</span> <span m="2897850">goals.</span> <span m="2899590">Privacy--</span>
  <span m="2900550">because</span> <span m="2900790">these</span> <span m="2900940">commitments</span>
  <span m="2901360">are</span> <span m="2901420">perfectly</span> <span m="2901810">hiding,</span>
  <span m="2903250">no</span> <span m="2903460">one</span> <span m="2903550">can</span>
  <span m="2903730">see</span> <span m="2904030">transaction</span> <span m="2904570">participants.</span>
  <span m="2905380">They</span> <span m="2905500">can't</span> <span m="2905710">tell</span>
  <span m="2906160">who's</span> <span m="2906370">committing</span> <span m="2906640">to</span>
  <span m="2906700">0,</span> <span m="2907120">and</span> <span m="2907210">who's</span>
  <span m="2907360">not</span> <span m="2907510">committing</span> <span m="2907810">to</span>
  <span m="2907900">0.</span> <span m="2909310">Banks</span> <span m="2909640">can't</span>
  <span m="2909850">lie</span> <span m="2910020">to</span> <span m="2910120">the</span>
  <span m="2910240">auditor,</span> <span m="2910660">because</span> <span m="2911110">the</span>
  <span m="2911230">auditor</span> <span m="2911530">audits</span> <span m="2911890">every</span>
  <span m="2912190">transaction</span> <span m="2912760">for</span> <span m="2912910">a</span>
  <span m="2912940">bank.</span></p><p><span m="2913760">But</span> <span m="2913810">what</span>
  <span m="2913960">I</span> <span m="2914200">haven't</span> <span m="2915430">figured</span>
  <span m="2915730">out</span> <span m="2915880">yet</span> <span m="2916120">is,</span>
  <span m="2916330">well,</span> <span m="2917230">how</span> <span m="2917830">do</span>
  <span m="2917890">we</span> <span m="2917980">maintain</span> <span m="2918370">financial</span>
  <span m="2918820">invariants</span> <span m="2919730">in</span> <span m="2919750">this</span>
  <span m="2919900">scheme?</span> <span m="2920440">How</span> <span m="2920620">do</span>
  <span m="2920710">we</span> <span m="2920830">make</span> <span m="2921010">sure</span>
  <span m="2921190">assets</span> <span m="2921520">aren't</span> <span m="2921610">created</span>
  <span m="2921910">out</span> <span m="2922000">of</span> <span m="2922090">nowhere?</span>
  <span m="2922540">How</span> <span m="2922630">do</span> <span m="2922690">we</span>
  <span m="2922810">make</span> <span m="2922960">sure</span> <span m="2924190">that</span>
  <span m="2924460">whoever is</span> <span m="2924760">spending</span> <span m="2925240">actually</span>
  <span m="2925540">consented</span> <span m="2926020">to</span> <span m="2926110">the</span>
  <span m="2926230">spend?</span> <span m="2927160">And</span> <span m="2927970">how</span>
  <span m="2928300">do</span> <span m="2928390">we</span> <span m="2928540">construct</span>
  <span m="2929230">this</span> <span m="2929410">transaction</span> <span m="2930100">that</span>
  <span m="2930220">involves</span> <span m="2930730">every</span> <span m="2931060">bank</span>
  <span m="2932380">when</span> <span m="2932860">we</span> <span m="2933040">assume</span>
  <span m="2933370">banks</span> <span m="2933640">are</span> <span m="2933700">malicious,</span>
  <span m="2934840">and</span> <span m="2935080">we</span> <span m="2935260">don't</span>
  <span m="2935410">want</span> <span m="2935680">one</span> <span m="2935890">bank</span>
  <span m="2936160">to</span> <span m="2936250">be</span> <span m="2936370">able</span>
  <span m="2936490">to</span> <span m="2936580">hold</span> <span m="2936880">up</span>
  <span m="2937270">everyone</span> <span m="2937660">from</span> <span m="2937840">transacting?</span></p><p><span
  m="2943160">So</span> <span m="2943520">our</span> <span m="2943640">solution</span>
  <span m="2944150">to</span> <span m="2944270">do</span> <span m="2944450">that</span>
  <span m="2945170">is</span> <span m="2945320">to</span> <span m="2945440">use</span>
  <span m="2945860">a</span> <span m="2945950">set</span> <span m="2946580">of</span>
  <span m="2946850">what</span> <span m="2947000">are</span> <span m="2947060">called</span>
  <span m="2947540">NIZKs--</span> <span m="2948080">non-interactive</span> <span
  m="2949130">zero-knowledge</span> <span m="2949910">proofs.</span> <span m="2951890">So</span>
  <span m="2952190">what</span> <span m="2952580">are</span> <span m="2953210">NIZKs?</span>
  <span m="2953720">NIZKs</span> <span m="2954020">are</span> <span m="2954230">short</span>
  <span m="2954890">binary</span> <span m="2955400">strings.</span></p><p><span m="2957670">True</span>
  <span m="2958090">statements</span> <span m="2959080">have</span> <span m="2959500">proofs.</span>
  <span m="2961060">So,</span> <span m="2961330">if</span> <span m="2961480">a</span>
  <span m="2961540">statement</span> <span m="2961840">is</span> <span m="2961960">true,</span>
  <span m="2962320">it</span> <span m="2962410">should</span> <span m="2962590">have</span>
  <span m="2962890">a</span> <span m="2962950">proof</span> <span m="2964410">indicating</span>
  <span m="2964770">that</span> <span m="2964830">it's</span> <span m="2964980">true.</span>
  <span m="2966000">False</span> <span m="2966420">statements</span> <span m="2967830">only</span>
  <span m="2968280">have</span> <span m="2968730">proofs</span> <span m="2969270">with</span>
  <span m="2969420">negligible</span> <span m="2970020">probability.</span> <span
  m="2973450">And</span> <span m="2973900">proofs</span> <span m="2974740">don't</span>
  <span m="2975160">reveal</span> <span m="2976330">why</span> <span m="2977110">they</span>
  <span m="2977320">are</span> <span m="2977440">true.</span></p><p><span m="2978580">So</span>
  <span m="2979150">we're</span> <span m="2979300">going</span> <span m="2979540">to</span>
  <span m="2979660">use</span> <span m="2980020">NIZKs</span> <span m="2980770">to</span>
  <span m="2980950">prove</span> <span m="2981340">things</span> <span m="2981730">like</span>
  <span m="2984320">the</span> <span m="2984410">person</span> <span m="2984800">who</span>
  <span m="2984920">knows</span> <span m="2985220">the</span> <span m="2985280">secret</span>
  <span m="2985640">key</span> <span m="2985850">for</span> <span m="2985970">this</span>
  <span m="2986120">public</span> <span m="2986450">key</span> <span m="2987410">consented</span>
  <span m="2988040">to</span> <span m="2988160">this</span> <span m="2988400">transfer,</span>
  <span m="2989660">without</span> <span m="2990170">indicating</span> <span m="2991550">which</span>
  <span m="2992480">bank</span> <span m="2992840">it</span> <span m="2992960">was</span>
  <span m="2993830">that</span> <span m="2994250">consented</span> <span m="2994760">to</span>
  <span m="2994880">the</span> <span m="2995000">transfer.</span> <span m="2996560">We're</span>
  <span m="2996650">going</span> <span m="2996760">to</span> <span m="2996890">use</span>
  <span m="2997110">NIZKs</span> <span m="2997490">to</span> <span m="2997610">prove</span>
  <span m="2997850">things</span> <span m="2998210">like</span> <span m="3001880">this</span>
  <span m="3002060">bank</span> <span m="3002330">has</span> <span m="3002780">the</span>
  <span m="3002930">assets</span> <span m="3003410">to</span> <span m="3003530">spend,</span>
  <span m="3005500">without</span> <span m="3006250">revealing</span> <span m="3007360">how</span>
  <span m="3007600">many</span> <span m="3007840">assets</span> <span m="3008380">that</span>
  <span m="3008560">bank</span> <span m="3008890">actually</span> <span m="3009280">has.</span></p><p><span
  m="3012750">So</span> <span m="3013590">zkLedger</span> <span m="3014220">uses</span>
  <span m="3014940">a</span> <span m="3015000">set</span> <span m="3015390">of</span>
  <span m="3015540">carefully</span> <span m="3015990">crafted</span> <span m="3016510">NIZKs.</span>
  <span m="3016980">And</span> <span m="3017070">to</span> <span m="3017160">be</span>
  <span m="3017280">clear,</span> <span m="3017470">NIZKs</span> <span m="3017890">are</span>
  <span m="3018630">pretty</span> <span m="3018870">old.</span> <span m="3019270">They
  were</span> <span m="3019770">invented</span> <span m="3020110">in</span> <span
  m="3020340">the</span> <span m="3020400">'80s</span> <span m="3020850">and</span>
  <span m="3020970">the</span> <span m="3021060">'90s.</span> <span m="3022470">And</span>
  <span m="3022680">most</span> <span m="3022950">of</span> <span m="3023010">them</span>
  <span m="3023130">are</span> <span m="3023220">based</span> <span m="3023610">on</span>
  <span m="3023730">the</span> <span m="3023790">hardness</span> <span m="3024240">of</span>
  <span m="3024300">the</span> <span m="3024390">discrete</span> <span m="3024780">log</span>
  <span m="3024990">problem</span> <span m="3025560">in</span> <span m="3026020">elliptic</span>
  <span m="3026200">curve</span> <span m="3026470">cryptography,</span> <span m="3026940">again.</span></p><p><span
  m="3028230">So</span> <span m="3028410">here</span> <span m="3028710">are</span>
  <span m="3029100">the</span> <span m="3029790">properties</span> <span m="3030270">we</span>
  <span m="3030330">want</span> <span m="3030480">to</span> <span m="3030540">achieve</span>
  <span m="3030990">with</span> <span m="3031170">transactions.</span> <span m="3031800">We</span>
  <span m="3031890">want</span> <span m="3032070">transaction</span> <span m="3032610">validity.</span>
  <span m="3033510">We</span> <span m="3033600">want</span> <span m="3033750">to</span>
  <span m="3033810">make</span> <span m="3033960">sure</span> <span m="3034290">whoever</span>
  <span m="3035730">is</span> <span m="3036030">the</span> <span m="3036150">spender,</span>
  <span m="3037170">whoever</span> <span m="3037440">has</span> <span m="3037590">a</span>
  <span m="3037650">negative</span> <span m="3038070">amount</span> <span m="3038310">in</span>
  <span m="3038370">their</span> <span m="3038490">column,</span> <span m="3039000">actually</span>
  <span m="3039330">consented</span> <span m="3039960">to</span> <span m="3040050">the</span>
  <span m="3040140">transfer.</span> <span m="3041070">And</span> <span m="3041310">again,</span>
  <span m="3041670">remember,</span> <span m="3042510">in</span> <span m="3042750">cryptocurrencies</span>
  <span m="3043440">and</span> <span m="3043530">things</span> <span m="3043740">like</span>
  <span m="3043860">that,</span> <span m="3044100">where</span> <span m="3044220">it's</span>
  <span m="3044340">OK</span> <span m="3044610">to</span> <span m="3044670">reveal</span>
  <span m="3045120">who</span> <span m="3045240">the</span> <span m="3045330">person</span>
  <span m="3045660">is who's</span> <span m="3045870">spending,</span> <span m="3046230">we</span>
  <span m="3046350">use</span> <span m="3046530">a</span> <span m="3046560">signature.</span>
  <span m="3047710">In</span> <span m="3047910">this</span> <span m="3048150">case,</span>
  <span m="3048420">we'll</span> <span m="3048570">use</span> <span m="3048780">proof</span>
  <span m="3049080">of</span> <span m="3049200">knowledge</span> <span m="3049770">of</span>
  <span m="3049890">secret</span> <span m="3050190">key.</span> <span m="3051720">So</span>
  <span m="3051810">there's</span> <span m="3051960">a</span> <span m="3052020">consent</span>
  <span m="3052470">NIZK.</span></p><p><span m="3054300">We</span> <span m="3054450">want</span>
  <span m="3054660">to</span> <span m="3054750">be</span> <span m="3054840">able</span>
  <span m="3054990">to</span> <span m="3055080">prove</span> <span m="3055350">that</span>
  <span m="3055470">whoever is</span> <span m="3055770">spending</span> <span m="3056190">actually</span>
  <span m="3056520">has</span> <span m="3056880">the</span> <span m="3057030">assets</span>
  <span m="3057420">to</span> <span m="3057540">transfer--</span> <span m="3058050">that</span>
  <span m="3058200">they're</span> <span m="3058290">not</span> <span m="3058470">going</span>
  <span m="3058710">negative.</span> <span m="3059640">And</span> <span m="3059790">we</span>
  <span m="3059880">use</span> <span m="3060680">an</span> <span m="3060840">assets</span>
  <span m="3061260">NIZK.</span> <span m="3062070">And</span> <span m="3062340">we</span>
  <span m="3062430">want</span> <span m="3062580">to</span> <span m="3062640">make</span>
  <span m="3062760">sure</span> <span m="3062970">that</span> <span m="3063150">assets</span>
  <span m="3063600">are</span> <span m="3063740">neither</span> <span m="3065910">created</span>
  <span m="3066210">nor</span> <span m="3066360">destroyed,</span> <span m="3066810">so</span>
  <span m="3066960">for</span> <span m="3067080">that</span> <span m="3067230">we</span>
  <span m="3067380">use</span> <span m="3067620">a</span> <span m="3067710">balance</span>
  <span m="3068240">NIZK.</span> <span m="3068580">We</span> <span m="3068670">want</span>
  <span m="3068820">to</span> <span m="3068880">show</span> <span m="3069030">that</span>
  <span m="3069720">things</span> <span m="3069930">work</span> <span m="3070170">out,</span>
  <span m="3070470">and</span> <span m="3072270">you</span> <span m="3072480">didn't</span>
  <span m="3072900">create</span> <span m="3073350">more</span> <span m="3073560">euros</span>
  <span m="3073980">than</span> <span m="3074100">you</span> <span m="3074160">were</span>
  <span m="3074280">supposed</span> <span m="3074640">to.</span> <span m="3074790">The</span>
  <span m="3074880">only</span> <span m="3075090">place</span> <span m="3075360">where</span>
  <span m="3075450">you</span> <span m="3075570">can</span> <span m="3075720">do</span>
  <span m="3075870">that</span> <span m="3076050">is</span> <span m="3076200">in</span>
  <span m="3076290">the</span> <span m="3076380">depositor</span> <span m="3077070">transactions,</span>
  <span m="3077760">the</span> <span m="3077850">public</span> <span m="3078120">depositor</span>
  <span m="3078540">transactions.</span></p><p><span m="3080130">We</span> <span m="3080340">also</span>
  <span m="3080700">want</span> <span m="3080940">to</span> <span m="3081000">make</span>
  <span m="3081240">sure</span> <span m="3082020">that</span> <span m="3082680">honest</span>
  <span m="3083130">banks</span> <span m="3083610">can</span> <span m="3083790">make</span>
  <span m="3083970">progress.</span> <span m="3084570">And</span> <span m="3084650">in</span>
  <span m="3084750">order</span> <span m="3084990">to</span> <span m="3085110">do</span>
  <span m="3085320">that,</span> <span m="3086310">creating</span> <span m="3086760">a</span>
  <span m="3086790">transaction</span> <span m="3088140">in</span> <span m="3088260">zkLedger</span>
  <span m="3088920">is</span> <span m="3089070">non-interactive.</span> <span m="3090240">The</span>
  <span m="3090330">banks</span> <span m="3090570">don't</span> <span m="3090690">have</span>
  <span m="3090900">to</span> <span m="3091050">interact</span> <span m="3092610">to</span>
  <span m="3092760">create</span> <span m="3092940">a</span> <span m="3092970">transaction.</span></p><p><span
  m="3093790">This</span> <span m="3093870">is</span> <span m="3094020">exactly</span>
  <span m="3094740">how</span> <span m="3095130">systems</span> <span m="3095640">like</span>
  <span m="3095960">Ethereum</span> <span m="3096510">and</span> <span m="3096630">Bitcoin</span>
  <span m="3097050">work,</span> <span m="3097380">if</span> <span m="3097500">you</span>
  <span m="3097560">think</span> <span m="3097740">about</span> <span m="3097980">it.</span>
  <span m="3098530">I</span> <span m="3098610">can't</span> <span m="3098880">stop</span>
  <span m="3099360">you</span> <span m="3099600">from</span> <span m="3099810">sending</span>
  <span m="3100170">me</span> <span m="3100320">Bitcoin,</span> <span m="3101360">right?</span>
  <span m="3101940">If</span> <span m="3102090">you</span> <span m="3102210">want</span>
  <span m="3102420">to</span> <span m="3102540">send</span> <span m="3102750">me</span>
  <span m="3102870">Bitcoin,</span> <span m="3103410">you</span> <span m="3103530">construct</span>
  <span m="3104010">a</span> <span m="3104040">transaction</span> <span m="3104670">that</span>
  <span m="3104790">sends</span> <span m="3104970">me</span> <span m="3105090">Bitcoin.</span>
  <span m="3105570">You</span> <span m="3105660">submit</span> <span m="3105930">it</span>
  <span m="3106020">to</span> <span m="3106110">the</span> <span m="3106200">blockchain.</span>
  <span m="3106770">I</span> <span m="3106890">have</span> <span m="3107010">nothing</span>
  <span m="3107250">to</span> <span m="3107370">do</span> <span m="3107490">with</span>
  <span m="3107580">that.</span></p><p><span m="3108270">Offline,</span> <span m="3109440">we</span>
  <span m="3109620">might</span> <span m="3109860">have</span> <span m="3109980">agreed</span>
  <span m="3110310">that</span> <span m="3110430">the</span> <span m="3110520">reason</span>
  <span m="3110880">you're</span> <span m="3111000">sending</span> <span m="3111300">me</span>
  <span m="3111420">Bitcoin</span> <span m="3111930">is</span> <span m="3112080">because</span>
  <span m="3112800">I'm</span> <span m="3113070">selling</span> <span m="3113370">you</span>
  <span m="3113490">my</span> <span m="3113640">car</span> <span m="3114180">or</span>
  <span m="3114270">something</span> <span m="3114600">like</span> <span m="3114780">that.</span>
  <span m="3115410">But</span> <span m="3115560">to</span> <span m="3115680">actually</span>
  <span m="3116190">create</span> <span m="3116760">the</span> <span m="3116850">transaction</span>
  <span m="3117990">that</span> <span m="3118200">spends,</span> <span m="3119340">you</span>
  <span m="3119460">don't</span> <span m="3119670">have</span> <span m="3119940">to</span>
  <span m="3120060">talk</span> <span m="3120330">to</span> <span m="3120450">the</span>
  <span m="3120540">other</span> <span m="3120690">participants.</span> <span m="3121800">And</span>
  <span m="3122190">we</span> <span m="3122460">use</span> <span m="3123030">a</span>
  <span m="3124080">consistency</span> <span m="3124890">NIZK</span> <span m="3125670">so</span>
  <span m="3125910">that</span> <span m="3127680">the</span> <span m="3127800">person</span>
  <span m="3128220">creating</span> <span m="3128760">the</span> <span m="3128850">transaction</span>
  <span m="3130140">can</span> <span m="3130370">prove</span> <span m="3131100">in</span>
  <span m="3131220">a</span> <span m="3131280">publicly</span> <span m="3131790">verifiable</span>
  <span m="3132540">way</span> <span m="3133530">that</span> <span m="3134250">everything</span>
  <span m="3134610">matches</span> <span m="3134970">up</span> <span m="3135090">correctly,</span>
  <span m="3136110">that</span> <span m="3136320">all</span> <span m="3136500">of</span>
  <span m="3136560">these</span> <span m="3136890">proofs</span> <span m="3137250">are</span>
  <span m="3137310">correct,</span> <span m="3138210">and</span> <span m="3138360">that</span>
  <span m="3139350">all</span> <span m="3139590">of</span> <span m="3139680">the</span>
  <span m="3139770">banks</span> <span m="3140250">are</span> <span m="3140370">going</span>
  <span m="3140670">to</span> <span m="3140760">be</span> <span m="3140910">able</span>
  <span m="3141180">to</span> <span m="3141360">later</span> <span m="3141690">respond</span>
  <span m="3142140">to</span> <span m="3142260">the</span> <span m="3142380">auditor--</span>
  <span m="3142980">be</span> <span m="3143130">able</span> <span m="3143340">to</span>
  <span m="3143430">respond</span> <span m="3143700">to</span> <span m="3143760">the</span>
  <span m="3143880">auditor</span> <span m="3144210">as</span> <span m="3144330">necessary.</span></p><p><span
  m="3145450">So</span> <span m="3145770">to</span> <span m="3146370">give</span>
  <span m="3146550">you</span> <span m="3146670">a</span> <span m="3146730">little</span>
  <span m="3146910">bit</span> <span m="3147030">of</span> <span m="3147150">insight</span>
  <span m="3147600">into</span> <span m="3147840">why</span> <span m="3148440">this</span>
  <span m="3148590">consistency</span> <span m="3149250">NIZK</span> <span m="3149700">is</span>
  <span m="3149820">necessary,</span> <span m="3152370">over</span> <span m="3152640">here,</span>
  <span m="3153660">I</span> <span m="3153840">was</span> <span m="3153960">speaking</span>
  <span m="3154530">as</span> <span m="3154710">though</span> <span m="3154860">the</span>
  <span m="3154950">bank</span> <span m="3155610">knew</span> <span m="3156630">all</span>
  <span m="3156840">of</span> <span m="3156930">the</span> <span m="3157240">r values,</span>
  <span m="3158430">right?</span> <span m="3161190">Actually,</span> <span m="3161610">in</span>
  <span m="3161700">zkLedger,</span> <span m="3162870">if</span> <span m="3163020">a</span>
  <span m="3163080">bank</span> <span m="3163350">is</span> <span m="3163470">not</span>
  <span m="3163740">involved</span> <span m="3164130">in</span> <span m="3164220">a</span>
  <span m="3164250">transaction,</span> <span m="3164970">if</span> <span m="3165060">their</span>
  <span m="3165180">commitment's</span> <span m="3165600">to</span> <span m="3165720">0,</span>
  <span m="3166530">they</span> <span m="3166680">don't</span> <span m="3166860">know</span>
  <span m="3167250">their</span> <span m="3167430">own</span> <span m="3167610">r</span>
  <span m="3167760">value,</span> <span m="3168510">because</span> <span m="3168780">some</span>
  <span m="3168960">other</span> <span m="3169110">bank</span> <span m="3169380">has</span>
  <span m="3169500">created</span> <span m="3169860">that.</span></p><p><span m="3170910">So</span>
  <span m="3171870">if</span> <span m="3172020">we</span> <span m="3172830">go</span>
  <span m="3172950">backwards</span> <span m="3173370">a</span> <span m="3173400">little</span>
  <span m="3173550">bit</span> <span m="3174980">to</span> <span m="3176910">here,</span>
  <span m="3181180">Barclays</span> <span m="3181810">wasn't</span> <span m="3182170">involved</span>
  <span m="3182530">in</span> <span m="3182620">this</span> <span m="3182740">transaction</span>
  <span m="3183340">at</span> <span m="3183430">all.</span> <span m="3184390">And</span>
  <span m="3184510">in</span> <span m="3184600">fact,</span> <span m="3185000">Barclays--</span>
  <span m="3185800">so</span> <span m="3186910">Goldman</span> <span m="3187330">Sachs</span>
  <span m="3187660">created</span> <span m="3188110">this</span> <span m="3188320">transaction.</span>
  <span m="3189830">JP</span> <span m="3190180">Morgan</span> <span m="3190600">created</span>
  <span m="3190930">this</span> <span m="3191140">one</span> <span m="3191500">and</span>
  <span m="3191620">this</span> <span m="3191830">one.</span> <span m="3193190">Barclays</span>
  <span m="3193670">had</span> <span m="3193760">nothing</span> <span m="3194060">to</span>
  <span m="3194180">do</span> <span m="3194360">with</span> <span m="3194480">them.</span>
  <span m="3195030">They</span> <span m="3195080">weren't</span> <span m="3195350">involved</span>
  <span m="3195680">at</span> <span m="3195770">all.</span> <span m="3196850">And</span>
  <span m="3197090">we</span> <span m="3197210">can't</span> <span m="3197510">assume</span>
  <span m="3198200">that</span> <span m="3198320">Barclays</span> <span m="3198890">knows</span>
  <span m="3199490">what</span> <span m="3199820">the</span> <span m="3200000">rs</span>
  <span m="3200450">are</span> <span m="3201230">in</span> <span m="3201380">its</span>
  <span m="3201590">column.</span></p><p><span m="3202780">Yet</span> <span m="3203360">the</span>
  <span m="3203600">way</span> <span m="3203900">that</span> <span m="3204020">I</span>
  <span m="3204110">told</span> <span m="3204440">you</span> <span m="3204560">that</span>
  <span m="3204680">Barclays'</span> <span m="3205100">response</span> <span m="3205540">to</span>
  <span m="3205640">the</span> <span m="3205760">auditor</span> <span m="3206480">is</span>
  <span m="3206630">by</span> <span m="3206840">revealing</span> <span m="3207350">the</span>
  <span m="3207440">sum</span> <span m="3207650">of</span> <span m="3207740">the</span>
  <span m="3207890">rs.</span> <span m="3208880">So</span> <span m="3209930">that's</span>
  <span m="3210110">actually</span> <span m="3210440">not</span> <span m="3210650">how</span>
  <span m="3210820">zkLedger</span> <span m="3211310">works.</span> <span m="3211580">They</span>
  <span m="3211700">don't</span> <span m="3211910">actually</span> <span m="3212150">reveal</span>
  <span m="3212450">the</span> <span m="3212540">sum</span> <span m="3212690">of</span>
  <span m="3212750">the</span> <span m="3212840">rs.</span></p><p><span m="3213530">The</span>
  <span m="3213680">proof</span> <span m="3215210">is</span> <span m="3215420">a</span>
  <span m="3215450">little</span> <span m="3215630">bit</span> <span m="3215750">more</span>
  <span m="3215900">complicated.</span> <span m="3218720">The</span> <span m="3219020">rs</span>
  <span m="3219410">are</span> <span m="3219560">encoded</span> <span m="3220340">for</span>
  <span m="3220520">Barclays</span> <span m="3221140">in</span> <span m="3221270">a</span>
  <span m="3221330">way</span> <span m="3222110">that</span> <span m="3222440">it</span>
  <span m="3222560">can't</span> <span m="3222890">see</span> <span m="3223100">what</span>
  <span m="3223370">they</span> <span m="3223550">are,</span> <span m="3223790">but</span>
  <span m="3224060">it</span> <span m="3224150">can</span> <span m="3224300">use</span>
  <span m="3224660">them.</span> <span m="3225590">And</span> <span m="3226460">the</span>
  <span m="3226580">consistency</span> <span m="3227240">proof</span> <span m="3227690">is</span>
  <span m="3227870">to</span> <span m="3228080">prove</span> <span m="3229010">that</span>
  <span m="3229160">that</span> <span m="3229310">encoding</span> <span m="3229880">was</span>
  <span m="3230120">done</span> <span m="3230660">correctly.</span></p><p><span m="3235860">So</span>
  <span m="3236040">again,</span> <span m="3236370">you</span> <span m="3236460">can</span>
  <span m="3236580">see</span> <span m="3236700">the</span> <span m="3236760">paper</span>
  <span m="3237000">for</span> <span m="3237120">details,</span> <span m="3237540">but</span>
  <span m="3237660">I'm</span> <span m="3237810">actually</span> <span m="3238050">going</span>
  <span m="3238180">to</span> <span m="3238380">tell</span> <span m="3238650">you</span>
  <span m="3238770">a</span> <span m="3238860">little</span> <span m="3239190">bit</span>
  <span m="3239520">about</span> <span m="3239940">these</span> <span m="3240150">proofs</span>
  <span m="3241500">and</span> <span m="3241620">what</span> <span m="3241770">they</span>
  <span m="3241920">look</span> <span m="3242100">like,</span> <span m="3242760">OK?</span>
  <span m="3243450">So,</span> <span m="3243900">consent.</span> <span m="3245580">The</span>
  <span m="3245700">consent</span> <span m="3246240">proof</span> <span m="3247110">is</span>
  <span m="3247380">proof</span> <span m="3247680">of</span> <span m="3247800">knowledge</span>
  <span m="3248340">of</span> <span m="3248490">secret</span> <span m="3248920">key,</span>
  <span m="3249350">sk.</span> <span m="3251160">So</span> <span m="3251400">what</span>
  <span m="3251550">this</span> <span m="3251730">means</span> <span m="3252090">is</span>
  <span m="3252240">that</span> <span m="3252570">if</span> <span m="3253890">the</span>
  <span m="3254040">value</span> <span m="3255090">in</span> <span m="3255210">the</span>
  <span m="3255300">commitment</span> <span m="3256260">in</span> <span m="3256380">this</span>
  <span m="3256590">entry</span> <span m="3257220">is</span> <span m="3257520">negative,</span>
  <span m="3258910">then</span> <span m="3261000">there</span> <span m="3261210">should</span>
  <span m="3261480">be</span> <span m="3261630">a</span> <span m="3261690">proof</span>
  <span m="3262350">of</span> <span m="3262740">knowledge</span> <span m="3263220">of</span>
  <span m="3263310">secret</span> <span m="3263610">key</span> <span m="3264240">to</span>
  <span m="3264480">indicate</span> <span m="3265050">that</span> <span m="3265440">this</span>
  <span m="3265650">bank</span> <span m="3266370">has</span> <span m="3266550">consented</span>
  <span m="3267570">to</span> <span m="3267750">subtracting</span> <span m="3268560">from</span>
  <span m="3268770">their</span> <span m="3268920">assets.</span></p><p><span m="3272720">Also,</span>
  <span m="3273830">if</span> <span m="3274190">the</span> <span m="3274310">value</span>
  <span m="3274760">is</span> <span m="3274790">negative,</span> <span m="3275690">you</span>
  <span m="3275840">need</span> <span m="3276020">to</span> <span m="3276080">create</span>
  <span m="3276320">a</span> <span m="3276380">proof</span> <span m="3276680">of</span>
  <span m="3276860">assets.</span> <span m="3278900">Technically,</span> <span m="3279380">you</span>
  <span m="3279500">don't</span> <span m="3279740">need</span> <span m="3280070">a</span>
  <span m="3280100">proof</span> <span m="3280370">of</span> <span m="3280460">assets</span>
  <span m="3280940">if</span> <span m="3281060">the</span> <span m="3281150">value</span>
  <span m="3281420">is</span> <span m="3281480">not</span> <span m="3281780">negative,</span>
  <span m="3282510">but</span> <span m="3282780">we're</span> <span m="3283220">trying</span>
  <span m="3283550">not</span> <span m="3283730">to</span> <span m="3283820">reveal,</span>
  <span m="3284630">remember,</span> <span m="3285080">which</span> <span m="3285380">bank</span>
  <span m="3286250">is</span> <span m="3286400">involved</span> <span m="3286790">in</span>
  <span m="3286880">which</span> <span m="3287060">transaction.</span> <span m="3288230">So</span>
  <span m="3288920">I'm</span> <span m="3289040">going</span> <span m="3289250">to</span>
  <span m="3289340">draw</span> <span m="3290780">a</span> <span m="3290840">transaction</span>
  <span m="3291440">up</span> <span m="3291560">here</span> <span m="3293390">and</span>
  <span m="3293780">explain</span> <span m="3294230">a</span> <span m="3294290">little</span>
  <span m="3294500">bit</span> <span m="3295190">about</span> <span m="3295700">where</span>
  <span m="3295880">these</span> <span m="3296120">proofs</span> <span m="3296420">actually</span>
  <span m="3296780">go.</span></p><p><span m="3304930">A</span> <span m="3305000">transaction</span>
  <span m="3307160">is</span> <span m="3307340">a</span> <span m="3307400">row.</span>
  <span m="3314180">And</span> <span m="3314690">there</span> <span m="3314900">is</span>
  <span m="3315050">an</span> <span m="3315140">entry</span> <span m="3320270">for</span>
  <span m="3321890">each</span> <span m="3322130">bank</span> <span m="3323870">in</span>
  <span m="3323990">the</span> <span m="3324080">transaction.</span> <span m="3330080">So</span>
  <span m="3330680">there</span> <span m="3330890">is</span> <span m="3331040">a</span>
  <span m="3331100">commitment.</span> <span m="3332900">So</span> <span m="3333080">let's--</span>
  <span m="3336800">negative</span> <span m="3337930">1</span> <span m="3338210">million.</span>
  <span m="3343190">And</span> <span m="3343340">then</span> <span m="3343490">there</span>
  <span m="3343610">is</span> <span m="3343850">also</span> <span m="3344240">these</span>
  <span m="3344390">sets</span> <span m="3344720">of</span> <span m="3344810">proofs.</span>
  <span m="3345680">So,</span> <span m="3348020">proof</span> <span m="3349460">of</span>
  <span m="3349760">assets,</span> <span m="3350390">in</span> <span m="3350510">particular.</span></p><p><span
  m="3352730">And</span> <span m="3353930">every</span> <span m="3354290">single</span>
  <span m="3354650">entry</span> <span m="3355130">has</span> <span m="3355430">a</span>
  <span m="3355490">proof</span> <span m="3355700">of</span> <span m="3355850">assets,</span>
  <span m="3356780">even</span> <span m="3357080">though,</span> <span m="3357290">really,</span>
  <span m="3357720">this</span> <span m="3357800">is</span> <span m="3357920">the</span>
  <span m="3358040">only</span> <span m="3358250">bank</span> <span m="3358850">that's</span>
  <span m="3359060">spending</span> <span m="3359930">and</span> <span m="3360050">needs</span>
  <span m="3360350">to</span> <span m="3360440">prove</span> <span m="3360710">that</span>
  <span m="3360860">it</span> <span m="3360950">has</span> <span m="3361250">assets.</span>
  <span m="3364190">The</span> <span m="3364280">proof</span> <span m="3364520">of</span>
  <span m="3364640">assets</span> <span m="3366830">is</span> <span m="3367850">constructed</span>
  <span m="3368510">to</span> <span m="3368690">look</span> <span m="3368900">like</span>
  <span m="3369080">this.</span> <span m="3370110">It's</span> <span m="3370190">a</span>
  <span m="3370250">new</span> <span m="3370580">commitment,</span> <span m="3371840">either</span>
  <span m="3372260">to</span> <span m="3372890">the</span> <span m="3373040">sum</span>
  <span m="3373700">of</span> <span m="3373820">the</span> <span m="3373910">values</span>
  <span m="3374330">in</span> <span m="3374390">the</span> <span m="3374480">column,</span>
  <span m="3375500">or,</span> <span m="3376280">if</span> <span m="3376490">you're</span>
  <span m="3376610">not</span> <span m="3376850">the</span> <span m="3376940">spending</span>
  <span m="3377270">bank,</span> <span m="3378350">a</span> <span m="3378410">commitment</span>
  <span m="3378770">to</span> <span m="3378830">the</span> <span m="3378920">value.</span></p><p><span
  m="3379790">And</span> <span m="3380030">it</span> <span m="3380180">also</span>
  <span m="3380570">includes</span> <span m="3382430">a</span> <span m="3382490">proof</span>
  <span m="3383450">that</span> <span m="3383570">the</span> <span m="3383690">value</span>
  <span m="3384500">in</span> <span m="3384680">this</span> <span m="3385460">auxiliary</span>
  <span m="3386000">commitment</span> <span m="3386480">is</span> <span m="3386720">in</span>
  <span m="3386900">range.</span> <span m="3387500">So</span> <span m="3387650">what</span>
  <span m="3387770">do</span> <span m="3387860">I</span> <span m="3387950">mean</span>
  <span m="3388130">by</span> <span m="3388280">that?</span> <span m="3389690">I</span>
  <span m="3390020">think</span> <span m="3390170">you</span> <span m="3390260">guys</span>
  <span m="3390410">should</span> <span m="3390650">have</span> <span m="3390740">covered</span>
  <span m="3391070">this</span> <span m="3391490">in</span> <span m="3391730">the</span>
  <span m="3391820">Pedersen</span> <span m="3392210">commitment</span> <span m="3392600">lecture</span>
  <span m="3392960">with</span> <span m="3393080">confidential</span> <span m="3393560">transactions,</span>
  <span m="3394460">but</span> <span m="3394610">when</span> <span m="3394760">you're</span>
  <span m="3394880">dealing</span> <span m="3395300">with</span> <span m="3395450">cyclic</span>
  <span m="3395870">groups,</span> <span m="3396770">you</span> <span m="3396890">can</span>
  <span m="3397070">wrap</span> <span m="3397400">around</span> <span m="3397760">the</span>
  <span m="3397910">end</span> <span m="3398090">of</span> <span m="3398210">the</span>
  <span m="3398300">group.</span> <span m="3399020">And</span> <span m="3399170">that's</span>
  <span m="3399740">the</span> <span m="3399860">same</span> <span m="3400790">as</span>
  <span m="3401570">if</span> <span m="3401690">you</span> <span m="3401810">hadn't</span>
  <span m="3402110">wrapped</span> <span m="3402380">around.</span> <span m="3402770">There</span>
  <span m="3402890">are</span> <span m="3402950">many</span> <span m="3403220">different</span>
  <span m="3403970">things</span> <span m="3404480">that</span> <span m="3404600">can</span>
  <span m="3404750">occupy</span> <span m="3405290">one</span> <span m="3405530">point</span>
  <span m="3406220">in</span> <span m="3406310">the</span> <span m="3406370">space</span>
  <span m="3406820">of</span> <span m="3406940">a</span> <span m="3407000">cyclic</span>
  <span m="3407300">group.</span></p><p><span m="3408020">So</span> <span m="3408830">we</span>
  <span m="3409040">need</span> <span m="3409250">to</span> <span m="3409370">include</span>
  <span m="3409790">proofs</span> <span m="3411350">that</span> <span m="3411800">your</span>
  <span m="3411920">value</span> <span m="3412370">is</span> <span m="3412490">in</span>
  <span m="3412580">a</span> <span m="3412610">range</span> <span m="3413090">that's</span>
  <span m="3413330">expected.</span> <span m="3414290">And</span> <span m="3414620">in</span>
  <span m="3414710">the</span> <span m="3414800">case</span> <span m="3415040">of</span>
  <span m="3415100">zkLedger,</span> <span m="3416160">we</span> <span m="3416180">need</span>
  <span m="3416330">to</span> <span m="3416390">prove</span> <span m="3416990">that</span>
  <span m="3417200">the</span> <span m="3417320">value</span> <span m="3417640">is</span>
  <span m="3417740">between</span> <span m="3418100">0</span> <span m="3418730">and</span>
  <span m="3418820">a</span> <span m="3418880">certain</span> <span m="3419390">upper</span>
  <span m="3419600">limit</span> <span m="3421010">that</span> <span m="3421130">is</span>
  <span m="3421250">less</span> <span m="3421520">than</span> <span m="3421730">the</span>
  <span m="3421850">order</span> <span m="3422210">of</span> <span m="3422330">the</span>
  <span m="3422420">group.</span> <span m="3423650">And</span> <span m="3425720">we</span>
  <span m="3425870">use</span> <span m="3426020">the</span> <span m="3426080">exact</span>
  <span m="3426470">same</span> <span m="3426620">technique</span> <span m="3426950">that</span>
  <span m="3427070">they</span> <span m="3427190">use</span> <span m="3427370">in</span>
  <span m="3427460">confidential</span> <span m="3427970">transactions</span> <span
  m="3428570">to</span> <span m="3428660">do</span> <span m="3428780">this--</span>
  <span m="3429560">borromean</span> <span m="3430480">ring</span> <span m="3430730">signatures.</span></p><p><span
  m="3432320">What's</span> <span m="3432530">kind</span> <span m="3432740">of</span>
  <span m="3432800">exciting</span> <span m="3433430">is</span> <span m="3433640">that,</span>
  <span m="3435260">a</span> <span m="3435320">few</span> <span m="3435470">months</span>
  <span m="3435680">ago,</span> <span m="3436220">there</span> <span m="3436430">was</span>
  <span m="3436700">some</span> <span m="3436970">work</span> <span m="3437210">done</span>
  <span m="3437630">on</span> <span m="3438020">a</span> <span m="3438650">faster,</span>
  <span m="3439490">smaller,</span> <span m="3440840">more</span> <span m="3441050">aggregatable</span>
  <span m="3441830">version</span> <span m="3442820">of</span> <span m="3443060">range</span>
  <span m="3443330">proofs</span> <span m="3443870">using</span> <span m="3444170">a</span>
  <span m="3444230">system</span> <span m="3444530">called</span> <span m="3444740">bullet</span>
  <span m="3445030">proofs.</span> <span m="3445910">So</span> <span m="3446630">as</span>
  <span m="3446780">you'll</span> <span m="3446900">see</span> <span m="3447290">in</span>
  <span m="3448730">the</span> <span m="3449180">evaluation,</span> <span m="3451250">this</span>
  <span m="3451400">sounds</span> <span m="3451850">like</span> <span m="3452060">such</span>
  <span m="3452330">a</span> <span m="3452390">silly</span> <span m="3452750">little</span>
  <span m="3452960">thing.</span> <span m="3453230">Oh,</span> <span m="3453380">yeah,</span>
  <span m="3453530">also</span> <span m="3453890">prove</span> <span m="3454220">that</span>
  <span m="3454370">the</span> <span m="3454460">value is</span> <span m="3454820">in</span>
  <span m="3454940">range.</span></p><p><span m="3455630">This</span> <span m="3455810">is</span>
  <span m="3455930">like</span> <span m="3456200">90%</span> <span m="3457130">of</span>
  <span m="3457280">all</span> <span m="3457490">of</span> <span m="3457610">the</span>
  <span m="3457700">space</span> <span m="3458240">and</span> <span m="3458390">work</span>
  <span m="3458840">in</span> <span m="3458960">zkLedger.</span> <span m="3459920">These</span>
  <span m="3460100">range</span> <span m="3460430">proofs</span> <span m="3460880">are</span>
  <span m="3461180">the</span> <span m="3461270">bane</span> <span m="3461540">of</span>
  <span m="3461630">our</span> <span m="3461720">existence.</span> <span m="3463140">They</span>
  <span m="3463610">take</span> <span m="3463910">up</span> <span m="3464180">a</span>
  <span m="3464270">lot</span> <span m="3464450">of</span> <span m="3464510">space.</span>
  <span m="3464930">They're</span> <span m="3465080">very</span> <span m="3465320">slow</span>
  <span m="3466220">to</span> <span m="3466370">create</span> <span m="3466790">and</span>
  <span m="3467000">verify,</span> <span m="3467690">but</span> <span m="3468080">they're</span>
  <span m="3468230">necessary.</span> <span m="3469130">So</span> <span m="3470270">making</span>
  <span m="3470570">them</span> <span m="3470690">faster</span> <span m="3471140">is</span>
  <span m="3471590">a</span> <span m="3471620">really</span> <span m="3472100">amazing</span>
  <span m="3472520">thing.</span></p><p><span m="3474620">Then</span> <span m="3475070">the</span>
  <span m="3475220">next</span> <span m="3476180">thing</span> <span m="3476510">is</span>
  <span m="3476780">balance.</span> <span m="3477740">And</span> <span m="3477860">I</span>
  <span m="3477950">think</span> <span m="3478160">this</span> <span m="3478340">one</span>
  <span m="3478580">is</span> <span m="3478790">illustrative,</span> <span m="3479810">because</span>
  <span m="3480920">it</span> <span m="3481070">shows</span> <span m="3481430">that</span>
  <span m="3481580">a</span> <span m="3481610">proof--</span> <span m="3482730">sometimes</span>
  <span m="3483020">you</span> <span m="3483110">have</span> <span m="3483290">a</span>
  <span m="3483320">proof</span> <span m="3483740">not</span> <span m="3483980">by</span>
  <span m="3484100">creating</span> <span m="3484760">an</span> <span m="3484910">additional</span>
  <span m="3485300">binary</span> <span m="3485750">string,</span> <span m="3486110">but</span>
  <span m="3486260">by</span> <span m="3486440">the</span> <span m="3486560">way</span>
  <span m="3486890">you</span> <span m="3487100">choose</span> <span m="3487580">things</span>
  <span m="3488870">in</span> <span m="3489050">your</span> <span m="3489170">transaction.</span>
  <span m="3490190">So</span> <span m="3490460">the</span> <span m="3490580">way</span>
  <span m="3490850">that</span> <span m="3490970">you</span> <span m="3491090">prove</span>
  <span m="3491480">that</span> <span m="3491600">no</span> <span m="3491780">funds</span>
  <span m="3492080">are</span> <span m="3492140">created</span> <span m="3492500">or</span>
  <span m="3492560">destroyed</span> <span m="3493550">is</span> <span m="3493760">as</span>
  <span m="3493880">follows.</span></p><p><span m="3494820">So</span> <span m="3494900">these</span>
  <span m="3495200">are--</span> <span m="3495680">remember</span> <span m="3496010">these</span>
  <span m="3496160">commitments</span> <span m="3496700">are</span> <span m="3497030">g</span>
  <span m="3497270">to</span> <span m="3497360">the</span> <span m="3497480">0.</span>
  <span m="3499030">Let's</span> <span m="3499230">say</span> <span m="3499460">h</span>
  <span m="3499790">the</span> <span m="3499910">r1,</span> <span m="3501590">g</span>
  <span m="3501800">to</span> <span m="3501890">the</span> <span m="3501980">negative</span>
  <span m="3502400">1 million,</span> <span m="3503360">h</span> <span m="3503600">to</span>
  <span m="3503690">the</span> <span m="3503860">r2,</span> <span m="3504920">and</span>
  <span m="3505100">g</span> <span m="3505310">to</span> <span m="3505400">the</span>
  <span m="3505490">1</span> <span m="3505650">million,</span> <span m="3506690">h</span>
  <span m="3506960">to</span> <span m="3507050">the</span> <span m="3507170">r3.</span>
  <span m="3508440">Now,</span> <span m="3508490">given</span> <span m="3508880">that</span>
  <span m="3509000">we</span> <span m="3509120">have</span> <span m="3509660">these</span>
  <span m="3509930">commitments,</span> <span m="3511460">how</span> <span m="3511850">can</span>
  <span m="3512030">we</span> <span m="3512180">prove</span> <span m="3512690">to</span>
  <span m="3512810">someone</span> <span m="3514160">that</span> <span m="3514700">no</span>
  <span m="3515000">assets</span> <span m="3515420">were</span> <span m="3515540">created</span>
  <span m="3515930">or</span> <span m="3516020">destroyed?</span> <span m="3516830">Well,</span>
  <span m="3517160">what</span> <span m="3517400">does</span> <span m="3517520">it</span>
  <span m="3517610">mean</span> <span m="3517970">for</span> <span m="3518120">no</span>
  <span m="3518330">assets</span> <span m="3518780">to</span> <span m="3518870">be</span>
  <span m="3518990">created</span> <span m="3519320">or</span> <span m="3519380">destroyed?</span></p><p><span
  m="3520200">It</span> <span m="3520250">means</span> <span m="3520760">that</span>
  <span m="3520940">the</span> <span m="3521060">sum</span> <span m="3522230">of</span>
  <span m="3522380">the</span> <span m="3522500">vs</span> <span m="3524780">is</span>
  <span m="3524930">equal</span> <span m="3525200">to</span> <span m="3525320">0,</span>
  <span m="3526210">right?</span> <span m="3526940">That's</span> <span m="3527150">what</span>
  <span m="3527270">it</span> <span m="3527330">means</span> <span m="3527510">for</span>
  <span m="3527600">no</span> <span m="3527810">assets</span> <span m="3528140">to</span>
  <span m="3528200">be</span> <span m="3528290">created</span> <span m="3528530">or</span>
  <span m="3528620">destroyed.</span> <span m="3529400">How</span> <span m="3529640">can</span>
  <span m="3529820">we</span> <span m="3529940">prove</span> <span m="3530450">to</span>
  <span m="3530600">someone</span> <span m="3531710">that,</span> <span m="3532520">given</span>
  <span m="3532760">that</span> <span m="3532880">all</span> <span m="3533060">they're</span>
  <span m="3533210">seeing</span> <span m="3533540">are</span> <span m="3533600">these</span>
  <span m="3533810">commitments,</span> <span m="3534800">that</span> <span m="3535010">the</span>
  <span m="3535130">sum</span> <span m="3535520">of</span> <span m="3535640">the</span>
  <span m="3535730">vs</span> <span m="3537050">commit</span> <span m="3537470">to</span>
  <span m="3537650">0?</span></p><p><span m="3538700">Well,</span> <span m="3540170">let's</span>
  <span m="3540410">just</span> <span m="3540620">make</span> <span m="3540830">the</span>
  <span m="3540920">sum</span> <span m="3541190">of</span> <span m="3541280">the</span>
  <span m="3541430">rs</span> <span m="3542660">also</span> <span m="3543380">commit</span>
  <span m="3543650">to</span> <span m="3543770">0.</span> <span m="3544610">So</span>
  <span m="3544760">if</span> <span m="3544850">the</span> <span m="3544970">sum</span>
  <span m="3545210">of</span> <span m="3545270">the</span> <span m="3545420">rs</span>
  <span m="3547160">also</span> <span m="3547730">commits</span> <span m="3548420">to</span>
  <span m="3548570">0,</span> <span m="3549380">then</span> <span m="3549560">when</span>
  <span m="3549710">you</span> <span m="3549830">multiply</span> <span m="3550490">these</span>
  <span m="3550700">things</span> <span m="3550970">together,</span> <span m="3552180">you're</span>
  <span m="3552190">going</span> <span m="3552270">to</span> <span m="3552380">get</span>
  <span m="3552650">g</span> <span m="3553100">to</span> <span m="3553250">the</span>
  <span m="3553370">sum</span> <span m="3553640">of</span> <span m="3553760">the</span>
  <span m="3553880">vs,</span> <span m="3555080">h</span> <span m="3555380">to</span>
  <span m="3555530">the</span> <span m="3555620">sum</span> <span m="3555860">of</span>
  <span m="3555950">the</span> <span m="3556100">rs.</span> <span m="3557540">And</span>
  <span m="3558140">if</span> <span m="3558260">both</span> <span m="3558500">of</span>
  <span m="3558560">these</span> <span m="3558710">things</span> <span m="3558950">are</span>
  <span m="3559010">0,</span> <span m="3560630">you</span> <span m="3560750">get</span>
  <span m="3560960">g</span> <span m="3561230">to</span> <span m="3561350">the 0,</span>
  <span m="3561770">h</span> <span m="3561980">to</span> <span m="3562100">the</span>
  <span m="3562190">0,</span> <span m="3562880">which</span> <span m="3563060">should</span>
  <span m="3563300">equal</span> <span m="3563930">what?</span> <span m="3565080">One,</span>
  <span m="3566300">exactly.</span></p><p><span m="3567470">So</span> <span m="3568640">we</span>
  <span m="3568760">choose</span> <span m="3569180">our</span> <span m="3569380">rs</span>
  <span m="3569780">very</span> <span m="3569990">carefully,</span> <span m="3571040">so</span>
  <span m="3571230">that the</span> <span m="3571400">auditor,</span> <span m="3572270">or</span>
  <span m="3572570">whoever</span> <span m="3572920">is</span> <span m="3573050">verifying</span>
  <span m="3573590">this,</span> <span m="3574190">can</span> <span m="3574350">just</span>
  <span m="3574520">multiply</span> <span m="3575270">all</span> <span m="3575360">the</span>
  <span m="3575450">commitments</span> <span m="3575900">together</span> <span m="3576380">and</span>
  <span m="3576530">verify</span> <span m="3577430">that</span> <span m="3577580">they</span>
  <span m="3577700">equal</span> <span m="3577940">1.</span> <span m="3578480">And</span>
  <span m="3578600">if</span> <span m="3578690">it</span> <span m="3578750">equals</span>
  <span m="3579020">1,</span> <span m="3580301">that</span> <span m="3580730">means</span>
  <span m="3580880">it</span> <span m="3580940">would</span> <span m="3581030">have</span>
  <span m="3581120">been</span> <span m="3581210">very</span> <span m="3581600">difficult</span>
  <span m="3582110">to</span> <span m="3582260">choose</span> <span m="3582710">vs</span>
  <span m="3583070">such</span> <span m="3583430">that</span> <span m="3585430">you</span>
  <span m="3585640">could</span> <span m="3585790">make</span> <span m="3586000">this</span>
  <span m="3586510">come</span> <span m="3586720">out</span> <span m="3587260">to</span>
  <span m="3587410">1</span> <span m="3587830">without</span> <span m="3588130">it</span>
  <span m="3588220">actually</span> <span m="3588490">coming</span> <span m="3588700">out</span>
  <span m="3588810">to</span> <span m="3588870">1.</span> <span m="3590300">So</span>
  <span m="3590450">that's</span> <span m="3590780">the</span> <span m="3591380">proof</span>
  <span m="3591830">of</span> <span m="3592040">balance.</span></p><p><span m="3592970">It's</span>
  <span m="3593090">not</span> <span m="3593300">an</span> <span m="3593390">actual</span>
  <span m="3594050">proof.</span> <span m="3594860">It's</span> <span m="3594980">not</span>
  <span m="3595130">a</span> <span m="3595190">short</span> <span m="3595400">binary</span>
  <span m="3595790">string.</span> <span m="3596690">It's</span> <span m="3596930">literally</span>
  <span m="3597350">choosing</span> <span m="3597830">the</span> <span m="3597950">exponents</span>
  <span m="3598400">in</span> <span m="3598520">a</span> <span m="3598580">clever</span>
  <span m="3598910">way</span> <span m="3599540">to</span> <span m="3600260">show</span>
  <span m="3600620">that</span> <span m="3600800">we</span> <span m="3600920">can</span>
  <span m="3601100">maintain</span> <span m="3601520">the</span> <span m="3601610">invariant</span>
  <span m="3602030">that</span> <span m="3602120">we</span> <span m="3602240">want.</span>
  <span m="3602900">Does</span> <span m="3603020">that</span> <span m="3603140">make</span>
  <span m="3603290">sense?</span> <span m="3608220">Questions</span> <span m="3608570">about</span>
  <span m="3608750">these</span> <span m="3608930">proofs?</span> <span m="3610420">And</span>
  <span m="3610600">I</span> <span m="3610680">didn't</span> <span m="3610890">go</span>
  <span m="3611010">into</span> <span m="3611280">proof</span> <span m="3611490">of</span>
  <span m="3611580">assets</span> <span m="3612180">very</span> <span m="3612390">much.</span>
  <span m="3613320">It's</span> <span m="3613500">the</span> <span m="3613560">most</span>
  <span m="3613740">complicated</span> <span m="3614190">one.</span> <span m="3614400">But</span>
  <span m="3614550">you</span> <span m="3614670">can</span> <span m="3614790">check</span>
  <span m="3614970">out</span> <span m="3615060">the</span> <span m="3615150">paper.</span></p><p><span
  m="3618730">I see</span> <span m="3618930">some</span> <span m="3619080">confused</span>
  <span m="3619560">faces.</span> <span m="3620910">You</span> <span m="3620970">don't</span>
  <span m="3621090">have</span> <span m="3621180">to</span> <span m="3621270">ask</span>
  <span m="3621450">about</span> <span m="3621600">the</span> <span m="3621670">proofs.</span></p><p><span
  m="3622160">AUDIENCE:</span> <span m="3622287">Couldn't you just</span> <span m="3622415">choose
  both</span> <span m="3622670">of</span> <span m="3623060">the exponents?</span>
  <span m="3626020">So</span> <span m="3626230">if</span> <span m="3626490">you're
  choosing</span> <span m="3626770">rs</span> <span m="3627450">in</span> <span m="3627540">a</span>
  <span m="3627600">certain</span> <span m="3627930">way,</span> <span m="3628240">can't</span>
  <span m="3628440">you</span> <span m="3628590">choose</span> <span m="3629010">them</span>
  <span m="3629320">in</span> <span m="3629420">a</span> <span m="3629460">certain</span>
  <span m="3629730">way</span> <span m="3631140">and</span> <span m="3631260">then</span>
  <span m="3631440">choose</span> <span m="3632730">payments</span> <span m="3633610">so</span>
  <span m="3634040">that</span> <span m="3634380">they sum</span> <span m="3634680">to</span>
  <span m="3635880">0?</span></p><p><span m="3636640">NEHA NARULA:</span> <span m="3636755">Well,</span>
  <span m="3636870">we're</span> <span m="3637050">trying</span> <span m="3637380">to</span>
  <span m="3637470">prove</span> <span m="3637770">that</span> <span m="3637920">the</span>
  <span m="3638010">payments</span> <span m="3638330">sum</span> <span m="3638520">to</span>
  <span m="3638610">0.</span> <span m="3638850">That's</span> <span m="3639030">what</span>
  <span m="3639120">we</span> <span m="3639210">want.</span> <span m="3640140">Because</span>
  <span m="3640350">that</span> <span m="3640500">means</span> <span m="3640770">that</span>
  <span m="3642000">assets</span> <span m="3642300">weren't</span> <span m="3642440">created</span>
  <span m="3642690">or</span> <span m="3642750">destroyed.</span> <span m="3643950">And</span>
  <span m="3644280">remember--</span></p><p><span m="3645170">AUDIENCE:</span> <span
  m="3645300">You're</span> <span m="3645430">generating--</span> <span m="3646210">you're</span>
  <span m="3646540">creating</span> <span m="3647310">those</span> <span m="3647720">random</span>
  <span m="3648000">numbers</span> <span m="3648870">in</span> <span m="3648960">a</span>
  <span m="3649020">way</span> <span m="3649230">that</span> <span m="3649350">they</span>
  <span m="3649560">sum to zero.</span> <span m="3651120">So</span> <span m="3651320">if</span>
  <span m="3651360">you</span> <span m="3651480">create</span> <span m="3651810">them
  in</span> <span m="3651930">a</span> <span m="3651960">way</span> <span m="3652110">that</span>
  <span m="3652380">doesn't</span> <span m="3652710">sum to</span> <span m="3653010">0?</span></p><p><span
  m="3653600">NEHA NARULA:</span> <span m="3653710">Then</span> <span m="3653820">every--</span>
  <span m="3654220">ah,</span> <span m="3654430">OK.</span> <span m="3655110">So</span>
  <span m="3655770">this</span> <span m="3655920">is</span> <span m="3656040">an</span>
  <span m="3656130">important--</span></p><p><span m="3656480">AUDIENCE:</span> <span
  m="3656715">Change</span> <span m="3656950">the</span> <span m="3657060">transaction</span>
  <span m="3657750">so</span> <span m="3657900">that</span> <span m="3658110">the</span>
  <span m="3658560">sum</span> <span m="3658950">of</span> <span m="3659100">the</span>
  <span m="3659190">rs</span> <span m="3660200">and</span> <span m="3660360">the sum</span>
  <span m="3660690">of</span> <span m="3660990">the</span> <span m="3661150">values</span>
  <span m="3661680">sum</span> <span m="3662070">to</span> <span m="3662460">0?</span></p><p><span
  m="3662850">NEHA NARULA:</span> <span m="3662925">So</span> <span m="3663000">basically,</span>
  <span m="3663360">what</span> <span m="3663480">you're</span> <span m="3663600">saying--</span>
  <span m="3664020">I</span> <span m="3664080">think</span> <span m="3664290">what</span>
  <span m="3664410">you're</span> <span m="3664500">say--</span> <span m="3664640">OK,</span>
  <span m="3664920">you</span> <span m="3665070">could</span> <span m="3665190">be</span>
  <span m="3665280">saying</span> <span m="3665490">one</span> <span m="3665610">of</span>
  <span m="3665670">two</span> <span m="3665820">things.</span> <span m="3666220">Number</span>
  <span m="3666360">one,</span> <span m="3667830">what</span> <span m="3668100">if</span>
  <span m="3668220">you</span> <span m="3669330">choose</span> <span m="3669750">your</span>
  <span m="3669870">vs</span> <span m="3670200">and rs</span> <span m="3670350">such</span>
  <span m="3670590">that</span> <span m="3670740">it</span> <span m="3670800">doesn't</span>
  <span m="3671040">sum</span> <span m="3671220">to</span> <span m="3671310">0,</span>
  <span m="3671960">right?</span> <span m="3672270">What</span> <span m="3672450">if</span>
  <span m="3672540">you</span> <span m="3672750">produce</span> <span m="3673110">an</span>
  <span m="3673200">invalid</span> <span m="3673650">transaction?</span> <span m="3674760">And</span>
  <span m="3675060">the</span> <span m="3675240">answer</span> <span m="3675630">is</span>
  <span m="3676380">that</span> <span m="3676830">everyone</span> <span m="3677220">will</span>
  <span m="3677340">reject</span> <span m="3677730">it.</span></p><p><span m="3678060">Sort</span>
  <span m="3678240">of</span> <span m="3678330">similar</span> <span m="3678600">to</span>
  <span m="3678720">Bitcoin,</span> <span m="3679290">if</span> <span m="3679410">you</span>
  <span m="3679500">don't</span> <span m="3679650">have</span> <span m="3679770">a</span>
  <span m="3679830">valid</span> <span m="3680040">transaction,</span> <span m="3680940">good</span>
  <span m="3681120">for</span> <span m="3681240">you.</span> <span m="3681690">But</span>
  <span m="3682410">it's</span> <span m="3682530">going</span> <span m="3682620">to</span>
  <span m="3682710">be</span> <span m="3682770">considered</span> <span m="3683130">invalid</span>
  <span m="3683520">by</span> <span m="3683640">everyone</span> <span m="3683940">in</span>
  <span m="3684000">the</span> <span m="3684090">system.</span> <span m="3684360">And</span>
  <span m="3684630">everyone's</span> <span m="3684930">going</span> <span m="3685040">to</span>
  <span m="3685110">skip</span> <span m="3685380">it</span> <span m="3685590">and</span>
  <span m="3685710">ignore</span> <span m="3686010">it.</span> <span m="3686160">It's</span>
  <span m="3686310">not</span> <span m="3686410">going</span> <span m="3686480">to</span>
  <span m="3686580">be</span> <span m="3686640">part</span> <span m="3686940">of</span>
  <span m="3687060">what</span> <span m="3687180">happens,</span> <span m="3687600">right?</span>
  <span m="3688140">So</span> <span m="3688200">this</span> <span m="3688290">is</span>
  <span m="3688380">part</span> <span m="3688650">of</span> <span m="3688740">the</span>
  <span m="3688800">proof</span> <span m="3689070">of</span> <span m="3689130">validity</span>
  <span m="3689610">that</span> <span m="3689760">all</span> <span m="3690000">of</span>
  <span m="3690060">the</span> <span m="3690150">participants</span> <span m="3690660">have</span>
  <span m="3690750">consented</span> <span m="3691170">to.</span></p><p><span m="3691800">The</span>
  <span m="3691890">second</span> <span m="3692160">question</span> <span m="3692490">you</span>
  <span m="3692550">might</span> <span m="3692730">be</span> <span m="3692880">asking</span>
  <span m="3693300">is,</span> <span m="3697050">what</span> <span m="3697200">if</span>
  <span m="3697290">these</span> <span m="3697500">don't</span> <span m="3697860">sum</span>
  <span m="3698100">to</span> <span m="3698190">0,</span> <span m="3699180">but</span>
  <span m="3699390">I</span> <span m="3699510">still</span> <span m="3699900">manage</span>
  <span m="3700410">to</span> <span m="3700560">figure</span> <span m="3700950">out</span>
  <span m="3701250">how</span> <span m="3702120">to</span> <span m="3702240">make</span>
  <span m="3702420">this</span> <span m="3702590">equal</span> <span m="3702810">1,</span>
  <span m="3703300">right?</span> <span m="3703800">That's</span> <span m="3704100">what</span>
  <span m="3704250">you--</span> <span m="3704390">OK,</span> <span m="3704520">so</span>
  <span m="3704610">that's</span> <span m="3704790">the</span> <span m="3704880">question</span>
  <span m="3705120">you're</span> <span m="3705240">asking.</span></p><p><span m="3707280">Based</span>
  <span m="3707580">on</span> <span m="3707700">the</span> <span m="3707760">assumption</span>
  <span m="3708540">that</span> <span m="3708690">the</span> <span m="3708780">discrete</span>
  <span m="3709170">logarithm</span> <span m="3709590">problem</span> <span m="3710250">is</span>
  <span m="3710400">hard--</span> <span m="3713130">this</span> <span m="3713310">is</span>
  <span m="3713400">too</span> <span m="3713580">hard</span> <span m="3713760">to</span>
  <span m="3713820">figure</span> <span m="3714090">out.</span> <span m="3714270">You</span>
  <span m="3714510">literally</span> <span m="3715170">cannot</span> <span m="3715710">find--</span>
  <span m="3718780">there</span> <span m="3719200">is</span> <span m="3719360">an</span>
  <span m="3719480">assumption</span> <span m="3719900">here.</span> <span m="3720800">These</span>
  <span m="3721070">are</span> <span m="3721130">two</span> <span m="3721310">generators</span>
  <span m="3722210">of</span> <span m="3722330">the</span> <span m="3722420">group,</span>
  <span m="3722750">right?</span> <span m="3723380">So</span> <span m="3723500">that</span>
  <span m="3723710">means</span> <span m="3723920">the</span> <span m="3724010">g</span>
  <span m="3724310">is</span> <span m="3724550">equal</span> <span m="3724910">to</span>
  <span m="3725090">h</span> <span m="3725390">to</span> <span m="3725540">the</span>
  <span m="3725690">x,</span> <span m="3727280">that</span> <span m="3727490">there's</span>
  <span m="3727700">some</span> <span m="3727910">way</span> <span m="3728030">to</span>
  <span m="3728120">produce</span> <span m="3728450">one</span> <span m="3728630">generator</span>
  <span m="3729200">from</span> <span m="3729380">the</span> <span m="3729470">other</span>
  <span m="3729650">generator.</span></p><p><span m="3731060">There</span> <span m="3731310">is</span>
  <span m="3731450">an</span> <span m="3731570">assumption</span> <span m="3731990">here</span>
  <span m="3732140">that</span> <span m="3732320">figuring</span> <span m="3732770">out</span>
  <span m="3732890">what</span> <span m="3733040">that</span> <span m="3733280">x</span>
  <span m="3733550">is</span> <span m="3734420">is</span> <span m="3734840">nearly</span>
  <span m="3735110">impossible.</span> <span m="3736590">So</span> <span m="3736640">you</span>
  <span m="3736790">don't</span> <span m="3737240">know</span> <span m="3738560">what</span>
  <span m="3738860">g</span> <span m="3739160">is</span> <span m="3739340">in</span>
  <span m="3739460">terms</span> <span m="3739820">of</span> <span m="3739940">h.</span>
  <span m="3740510">And</span> <span m="3740630">given</span> <span m="3740930">that</span>
  <span m="3741050">you</span> <span m="3741200">don't</span> <span m="3741530">know</span>
  <span m="3741800">this</span> <span m="3741950">relationship</span> <span m="3742670">between</span>
  <span m="3743000">g</span> <span m="3743180">and</span> <span m="3743300">h,</span>
  <span m="3746120">you</span> <span m="3746450">can't</span> <span m="3746870">figure</span>
  <span m="3747110">out</span> <span m="3747200">how</span> <span m="3747290">to</span>
  <span m="3747380">produce</span> <span m="3747800">two</span> <span m="3748190">exponents</span>
  <span m="3749510">that</span> <span m="3750580">sum</span> <span m="3750950">to</span>
  <span m="3751070">what</span> <span m="3751190">you</span> <span m="3751280">want</span>
  <span m="3751490">them</span> <span m="3751640">to</span> <span m="3751940">sum
  to.</span></p><p><span m="3752750">So</span> <span m="3753710">is</span> <span m="3753830">the</span>
  <span m="3754370">hardness</span> <span m="3754940">problem</span> <span m="3757090">that</span>
  <span m="3757310">these</span> <span m="3757490">systems</span> <span m="3757880">are</span>
  <span m="3757970">based</span> <span m="3758270">on.</span> <span m="3760700">If</span>
  <span m="3760820">you</span> <span m="3760940">could</span> <span m="3761120">do</span>
  <span m="3761300">that,</span> <span m="3761570">if</span> <span m="3761690">you</span>
  <span m="3761780">could</span> <span m="3761900">figure</span> <span m="3762230">out</span>
  <span m="3763310">a</span> <span m="3763880">sum</span> <span m="3764180">of</span>
  <span m="3764540">rs</span> <span m="3765200">such</span> <span m="3765470">that</span>
  <span m="3765590">it</span> <span m="3765650">gave</span> <span m="3765920">you</span>
  <span m="3766760">a</span> <span m="3766850">1</span> <span m="3767330">with</span>
  <span m="3767520">the</span> <span m="3767570">vs</span> <span m="3767790">you</span>
  <span m="3767900">wanted,</span> <span m="3768440">then</span> <span m="3768560">you</span>
  <span m="3768650">would</span> <span m="3768740">have</span> <span m="3768830">broken</span>
  <span m="3769190">the</span> <span m="3769310">discrete</span> <span m="3769640">log</span>
  <span m="3769820">problem.</span> <span m="3771860">Yes?</span></p><p><span m="3772050">AUDIENCE:</span>
  <span m="3772246">So</span> <span m="3772442">who</span> <span m="3772834">chooses</span>
  <span m="3773226">the</span> <span m="3773620">[INAUDIBLE]</span> <span m="3774405">we
  know</span> <span m="3774860">that they</span> <span m="3775315">don't know</span>
  <span m="3775770">the relationship</span> <span m="3776225">[INAUDIBLE]</span> <span
  m="3776680">they</span> <span m="3777140">maliciously</span> <span m="3777390">gave</span>
  <span m="3777670">those</span> <span m="3777770">two?</span></p><p><span m="3778080">NEHA
  NARULA:</span> <span m="3778200">Great</span> <span m="3778320">question.</span>
  <span m="3779710">So</span> <span m="3779790">the</span> <span m="3779910">answer</span>
  <span m="3780270">is</span> <span m="3780900">that</span> <span m="3781920">in</span>
  <span m="3782040">our</span> <span m="3782160">system,</span> <span m="3782550">the</span>
  <span m="3782640">way</span> <span m="3782790">that</span> <span m="3782910">we</span>
  <span m="3783000">choose</span> <span m="3783390">g and h</span> <span m="3784530">is</span>
  <span m="3784830">by</span> <span m="3785040">taking</span> <span m="3785400">the</span>
  <span m="3785490">SHA-256</span> <span m="3786480">hash</span> <span m="3787050">of</span>
  <span m="3787230">0</span> <span m="3787710">and</span> <span m="3787890">1.</span>
  <span m="3791310">Those</span> <span m="3791490">are</span> <span m="3791580">numbers</span>
  <span m="3792010">such</span> <span m="3792270">that--</span> <span m="3792900">they're</span>
  <span m="3793020">sufficiently</span> <span m="3793770">random,</span> <span m="3794670">and</span>
  <span m="3795690">they</span> <span m="3795870">show</span> <span m="3796200">that</span>
  <span m="3798060">if</span> <span m="3799650">you</span> <span m="3799860">took</span>
  <span m="3800040">a</span> <span m="3800100">hash</span> <span m="3800340">of</span>
  <span m="3800430">0</span> <span m="3800700">and</span> <span m="3800790">1,</span>
  <span m="3802050">you would</span> <span m="3802290">have</span> <span m="3802440">no</span>
  <span m="3802590">relationship</span> <span m="3803070">between</span> <span m="3803310">those</span>
  <span m="3803490">two.</span> <span m="3805370">And</span> <span m="3805490">everyone</span>
  <span m="3806180">uses</span> <span m="3806600">the</span> <span m="3806690">same</span>
  <span m="3807100">g</span> <span m="3807380">and h,</span> <span m="3807710">right,</span>
  <span m="3808100">from</span> <span m="3808310">the</span> <span m="3808370">beginning.</span>
  <span m="3815240">Any</span> <span m="3815420">other</span> <span m="3815570">questions?</span></p><p><span
  m="3817830">OK,</span> <span m="3818340">so</span> <span m="3819060">we're</span>
  <span m="3819990">running</span> <span m="3820920">low</span> <span m="3821100">on</span>
  <span m="3821190">time,</span> <span m="3821490">but</span> <span m="3821610">I</span>
  <span m="3821700">do</span> <span m="3821820">want</span> <span m="3821940">to</span>
  <span m="3822000">go</span> <span m="3822390">through</span> <span m="3822570">the</span>
  <span m="3822660">evaluation</span> <span m="3823500">really</span> <span m="3823710">quickly,</span>
  <span m="3824040">because--</span> <span m="3825210">so</span> <span m="3825480">this</span>
  <span m="3825610">system,</span> <span m="3825960">this</span> <span m="3826110">paper,</span>
  <span m="3826830">was</span> <span m="3827220">presented</span> <span m="3827790">at</span>
  <span m="3828000">NSDI</span> <span m="3828870">in</span> <span m="3829080">April,</span>
  <span m="3829570">which</span> <span m="3829650">is</span> <span m="3829770">a</span>
  <span m="3829830">systems</span> <span m="3830190">conference.</span> <span m="3830700">And</span>
  <span m="3830820">I</span> <span m="3830880">think</span> <span m="3831000">part</span>
  <span m="3831210">of</span> <span m="3831270">the</span> <span m="3831330">reason</span>
  <span m="3832110">that</span> <span m="3832440">the</span> <span m="3832560">systems</span>
  <span m="3832950">community</span> <span m="3833340">liked</span> <span m="3833580">it</span>
  <span m="3833730">was</span> <span m="3833910">because</span> <span m="3834390">it's</span>
  <span m="3834540">surprisingly</span> <span m="3835110">fast.</span> <span m="3836340">You</span>
  <span m="3836460">might</span> <span m="3836610">have</span> <span m="3836700">heard</span>
  <span m="3836940">that</span> <span m="3837060">computing</span> <span m="3837450">unencrypted</span>
  <span m="3837840">data</span> <span m="3838590">is</span> <span m="3838740">too</span>
  <span m="3838920">slow.</span> <span m="3839820">It's</span> <span m="3840050">infeasible.</span>
  <span m="3840720">You</span> <span m="3840840">can't</span> <span m="3841050">do</span>
  <span m="3841260">it.</span></p><p><span m="3841470">Well,</span> <span m="3841590">the</span>
  <span m="3841710">answer</span> <span m="3841980">is,</span> <span m="3842340">actually,</span>
  <span m="3843030">if</span> <span m="3843180">you</span> <span m="3843330">understand</span>
  <span m="3843780">the</span> <span m="3843870">set</span> <span m="3844290">of</span>
  <span m="3845190">computations</span> <span m="3845910">you</span> <span m="3846000">want</span>
  <span m="3846180">to</span> <span m="3846240">do</span> <span m="3846390">really</span>
  <span m="3846720">well,</span> <span m="3847590">you</span> <span m="3847770">can</span>
  <span m="3847920">structure</span> <span m="3848430">things</span> <span m="3848880">using</span>
  <span m="3849180">things</span> <span m="3849450">like</span> <span m="3849600">these</span>
  <span m="3849810">NIZKs</span> <span m="3850260">and</span> <span m="3850410">the</span>
  <span m="3850530">discrete</span> <span m="3850860">log</span> <span m="3851010">problem</span>
  <span m="3851370">in</span> <span m="3851460">such</span> <span m="3851670">a</span>
  <span m="3851700">way</span> <span m="3851910">that</span> <span m="3852030">you</span>
  <span m="3852120">can</span> <span m="3852270">do</span> <span m="3852450">that</span>
  <span m="3853590">computation</span> <span m="3854130">actually</span> <span m="3854430">pretty</span>
  <span m="3854670">fast.</span> <span m="3856550">So</span> <span m="3856930">zkLedger</span>
  <span m="3857260">is</span> <span m="3857610">written</span> <span m="3857850">in</span>
  <span m="3857940">Go.</span> <span m="3859680">It</span> <span m="3859800">uses</span>
  <span m="3860200">an</span> <span m="3860250">elliptic</span> <span m="3860530">curve</span>
  <span m="3861060">as</span> <span m="3861220">the</span> <span m="3861270">group--</span>
  <span m="3862045">secp256k1,</span> <span m="3863700">which</span> <span m="3863850">is</span>
  <span m="3863970">the</span> <span m="3864060">same</span> <span m="3864420">elliptic</span>
  <span m="3864750">curve</span> <span m="3864990">that</span> <span m="3865170">Bitcoin</span>
  <span m="3865530">uses.</span></p><p><span m="3866970">We</span> <span m="3867150">use</span>
  <span m="3867510">range</span> <span m="3867840">proofs</span> <span m="3868230">to</span>
  <span m="3868410">prevent</span> <span m="3868680">overflow,</span> <span m="3869130">like</span>
  <span m="3869340">I</span> <span m="3869430">said.</span> <span m="3870060">We</span>
  <span m="3870150">use</span> <span m="3870300">the</span> <span m="3870360">same</span>
  <span m="3870570">ones</span> <span m="3870990">as</span> <span m="3871520">in</span>
  <span m="3871710">confidential</span> <span m="3872250">transactions</span> <span
  m="3872850">and</span> <span m="3872940">confidential</span> <span m="3873420">assets.</span>
  <span m="3874290">And</span> <span m="3874710">it's</span> <span m="3874890">around</span>
  <span m="3875220">4,000</span> <span m="3875760">lines</span> <span m="3875970">of</span>
  <span m="3876030">code.</span> <span m="3876510">It's</span> <span m="3876630">mostly</span>
  <span m="3878040">cryptography</span> <span m="3878580">functions.</span> <span
  m="3879390">We</span> <span m="3879540">don't</span> <span m="3880140">actually</span>
  <span m="3880470">implement</span> <span m="3880830">our</span> <span m="3880920">own</span>
  <span m="3881100">ledger,</span> <span m="3881580">because</span> <span m="3881820">we're</span>
  <span m="3881910">ledger</span> <span m="3882180">agnostic.</span></p><p><span m="3884150">So</span>
  <span m="3884600">in</span> <span m="3884720">the</span> <span m="3884810">evaluation</span>
  <span m="3885380">we</span> <span m="3885500">want</span> <span m="3885620">to</span>
  <span m="3885680">understand</span> <span m="3886850">how</span> <span m="3887060">fast</span>
  <span m="3887390">is</span> <span m="3887540">auditing,</span> <span m="3888770">first</span>
  <span m="3889040">of</span> <span m="3889130">all?</span> <span m="3889700">Right?</span>
  <span m="3890390">And</span> <span m="3890510">then</span> <span m="3890660">second,</span>
  <span m="3891590">the</span> <span m="3891920">construction</span> <span m="3892520">I</span>
  <span m="3892610">described</span> <span m="3893150">to</span> <span m="3893270">you,</span>
  <span m="3893510">you</span> <span m="3893630">might</span> <span m="3893840">think</span>
  <span m="3894020">is</span> <span m="3894140">very</span> <span m="3894380">slow,</span>
  <span m="3894830">because</span> <span m="3895160">every</span> <span m="3895460">bank</span>
  <span m="3896210">has</span> <span m="3896480">an</span> <span m="3896570">entry</span>
  <span m="3896870">in</span> <span m="3897020">every</span> <span m="3897260">transaction.</span>
  <span m="3898260">So</span> <span m="3898340">how</span> <span m="3898760">does</span>
  <span m="3898940">this</span> <span m="3899090">actually</span> <span m="3899390">work</span>
  <span m="3899720">in</span> <span m="3899840">practice?</span> <span m="3900710">Can</span>
  <span m="3900860">we</span> <span m="3900950">get</span> <span m="3901070">away</span>
  <span m="3901400">with</span> <span m="3901550">such</span> <span m="3901760">a</span>
  <span m="3901820">construction?</span></p><p><span m="3904100">So</span> <span m="3904280">first,</span>
  <span m="3904580">let's</span> <span m="3904790">talk</span> <span m="3905030">about</span>
  <span m="3905780">the</span> <span m="3906110">auditing.</span> <span m="3907130">Auditing
  is</span> <span m="3907340">really</span> <span m="3907610">fast.</span> <span m="3908210">So</span>
  <span m="3908360">here,</span> <span m="3908540">we</span> <span m="3908630">are</span>
  <span m="3908690">auditing</span> <span m="3909080">four</span> <span m="3909380">banks,</span>
  <span m="3909980">and</span> <span m="3910130">we're</span> <span m="3910400">doing</span>
  <span m="3910760">a</span> <span m="3911090">measurement</span> <span m="3911540">called</span>
  <span m="3911780">the</span> <span m="3911870">Herfindahl-Hirschman</span> <span
  m="3912590">Index,</span> <span m="3912920">so</span> <span m="3912970">we're</span>
  <span m="3913070">trying</span> <span m="3913250">to</span> <span m="3913310">understand</span>
  <span m="3913700">market</span> <span m="3914990">concentration</span> <span m="3915800">for</span>
  <span m="3915920">a</span> <span m="3915980">given</span> <span m="3916250">asset.</span>
  <span m="3917120">And</span> <span m="3917240">what's</span> <span m="3917390">happening</span>
  <span m="3917750">here</span> <span m="3917900">is</span> <span m="3917990">the</span>
  <span m="3918110">auditor</span> <span m="3919700">is</span> <span m="3920210">keeping</span>
  <span m="3920540">up</span> <span m="3920660">with</span> <span m="3920750">the</span>
  <span m="3920840">ledger</span> <span m="3921500">and</span> <span m="3922490">keeping</span>
  <span m="3922820">these</span> <span m="3923000">things</span> <span m="3923270">that</span>
  <span m="3923390">we</span> <span m="3923510">call</span> <span m="3923750">commitment</span>
  <span m="3924170">caches.</span></p><p><span m="3925040">So</span> <span m="3926270">because</span>
  <span m="3926660">of</span> <span m="3926750">the</span> <span m="3926870">design</span>
  <span m="3928280">of</span> <span m="3928850">our</span> <span m="3929000">system</span>
  <span m="3929690">and</span> <span m="3929810">the</span> <span m="3929900">fact</span>
  <span m="3930170">that</span> <span m="3930290">we're</span> <span m="3930410">using</span>
  <span m="3931430">these</span> <span m="3932180">Pedersen</span> <span m="3932660">commitments--</span>
  <span m="3933320">which,</span> <span m="3933830">we</span> <span m="3934040">can</span>
  <span m="3934220">actually</span> <span m="3935030">maintain</span> <span m="3936320">rolling</span>
  <span m="3936920">sums</span> <span m="3937670">going</span> <span m="3938090">down</span>
  <span m="3939080">of</span> <span m="3939260">these</span> <span m="3939500">commitments</span>
  <span m="3940250">and</span> <span m="3940550">use</span> <span m="3940880">them</span>
  <span m="3942020">when</span> <span m="3942350">needing</span> <span m="3942740">to</span>
  <span m="3943100">answer</span> <span m="3943400">the</span> <span m="3943520">auditor</span>
  <span m="3943910">or</span> <span m="3944000">confirm</span> <span m="3944390">that</span>
  <span m="3944510">a</span> <span m="3944570">bank</span> <span m="3944870">has</span>
  <span m="3945260">the</span> <span m="3945350">correct</span> <span m="3945680">answer.</span>
  <span m="3946370">And</span> <span m="3946490">so</span> <span m="3946580">this</span>
  <span m="3946730">means</span> <span m="3946970">that</span> <span m="3947090">auditing</span>
  <span m="3947420">for</span> <span m="3947690">banks</span> <span m="3948080">is</span>
  <span m="3948350">milliseconds.</span> <span m="3949130">It's</span> <span m="3949280">a</span>
  <span m="3949310">few</span> <span m="3949490">milliseconds</span> <span m="3950090">to</span>
  <span m="3950540">audit</span> <span m="3950750">the</span> <span m="3950840">banks.</span></p><p><span
  m="3952130">And</span> <span m="3953390">we</span> <span m="3953660">see</span>
  <span m="3953840">here</span> <span m="3954140">on</span> <span m="3954260">the</span>
  <span m="3954350">x-axis</span> <span m="3954920">we</span> <span m="3955070">have</span>
  <span m="3955310">the</span> <span m="3955370">number</span> <span m="3955580">of</span>
  <span m="3955640">transactions</span> <span m="3956270">in</span> <span m="3956330">the</span>
  <span m="3956390">ledger.</span> <span m="3957080">The</span> <span m="3957170">reason</span>
  <span m="3958130">that</span> <span m="3958700">auditing</span> <span m="3959120">a</span>
  <span m="3959180">bank</span> <span m="3959420">is</span> <span m="3959570">independent</span>
  <span m="3960530">of</span> <span m="3960620">the</span> <span m="3960710">number</span>
  <span m="3960950">of</span> <span m="3961010">transactions</span> <span m="3961580">in</span>
  <span m="3961670">the</span> <span m="3961730">ledger</span> <span m="3962030">is</span>
  <span m="3962150">because</span> <span m="3962540">of</span> <span m="3962600">these</span>
  <span m="3962780">commitment</span> <span m="3963140">caches.</span> <span m="3963860">We</span>
  <span m="3963950">can</span> <span m="3964070">do</span> <span m="3964160">it</span>
  <span m="3964250">really</span> <span m="3964430">fast,</span> <span m="3965210">assuming</span>
  <span m="3965540">an</span> <span m="3965630">online</span> <span m="3966020">auditor</span>
  <span m="3966350">who's</span> <span m="3966770">keeping</span> <span m="3967070">up</span>
  <span m="3967190">with</span> <span m="3967280">things.</span> <span m="3971270">And</span>
  <span m="3971480">part</span> <span m="3971720">of</span> <span m="3971780">the</span>
  <span m="3971840">reason</span> <span m="3972080">for</span> <span m="3972170">that</span>
  <span m="3972260">is</span> <span m="3972380">because</span> <span m="3972710">of</span>
  <span m="3972800">our</span> <span m="3972860">design.</span> <span m="3973070">It's</span>
  <span m="3973220">very</span> <span m="3973400">amenable</span> <span m="3973700">to</span>
  <span m="3973760">caching.</span></p><p><span m="3974510">Now,</span> <span m="3974840">if</span>
  <span m="3974990">the</span> <span m="3975590">auditor</span> <span m="3975920">is</span>
  <span m="3976040">not</span> <span m="3976620">online</span> <span m="3977720">and</span>
  <span m="3977960">hasn't</span> <span m="3978380">been</span> <span m="3978530">maintaining</span>
  <span m="3978950">commitment</span> <span m="3979310">caches,</span> <span m="3980090">then</span>
  <span m="3980540">auditing</span> <span m="3981110">is</span> <span m="3981380">order</span>
  <span m="3981680">the</span> <span m="3981800">number</span> <span m="3982220">of</span>
  <span m="3982370">things</span> <span m="3982850">in</span> <span m="3983030">the</span>
  <span m="3983120">ledger.</span> <span m="3983930">Here,</span> <span m="3984260">we</span>
  <span m="3984470">have</span> <span m="3984680">a</span> <span m="3984740">ledger</span>
  <span m="3985010">with</span> <span m="3985130">100,000</span> <span m="3985730">entries.</span>
  <span m="3986420">It</span> <span m="3986510">takes</span> <span m="3986750">about</span>
  <span m="3987050">3.5</span> <span m="3987860">seconds</span> <span m="3988520">to</span>
  <span m="3988820">audit</span> <span m="3989060">that.</span> <span m="3989650">Still</span>
  <span m="3989870">not</span> <span m="3990020">so</span> <span m="3990170">bad,</span>
  <span m="3990620">really.</span> <span m="3991760">And</span> <span m="3991940">it's</span>
  <span m="3992150">pretty</span> <span m="3992390">linear,</span> <span m="3992840">so</span>
  <span m="3993020">you</span> <span m="3993110">could</span> <span m="3993230">imagine,</span>
  <span m="3994100">well,</span> <span m="3994430">if</span> <span m="3994580">you</span>
  <span m="3994700">had</span> <span m="3994850">a</span> <span m="3994910">million</span>
  <span m="3995240">entries,</span> <span m="3995750">it</span> <span m="3995840">would</span>
  <span m="3995960">be</span> <span m="3996140">10</span> <span m="3996380">times</span>
  <span m="3996680">that.</span> <span m="3996830">It</span> <span m="3996890">would</span>
  <span m="3996980">be</span> <span m="3997070">about</span> <span m="3997220">30</span>
  <span m="3997520">seconds.</span> <span m="3998480">Still</span> <span m="3999350">pretty</span>
  <span m="3999710">reasonable,</span> <span m="4000370">actually.</span></p><p><span
  m="4002510">A</span> <span m="4002620">question</span> <span m="4002980">some</span>
  <span m="4003100">people</span> <span m="4003370">ask</span> <span m="4003700">is,</span>
  <span m="4003820">well,</span> <span m="4004540">do</span> <span m="4004660">we</span>
  <span m="4004750">have</span> <span m="4004870">to</span> <span m="4004960">maintain</span>
  <span m="4005260">this</span> <span m="4005380">ledger</span> <span m="4005650">forever?</span>
  <span m="4006760">How</span> <span m="4006970">do</span> <span m="4007030">you</span>
  <span m="4007360">clean</span> <span m="4007690">up</span> <span m="4007810">the</span>
  <span m="4007900">ledger?</span> <span m="4008680">You</span> <span m="4008830">can</span>
  <span m="4010090">create</span> <span m="4010780">a</span> <span m="4010840">snapshot</span>
  <span m="4012160">of</span> <span m="4012310">the</span> <span m="4012430">state</span>
  <span m="4012880">in</span> <span m="4013000">the</span> <span m="4013060">ledger</span>
  <span m="4013510">and</span> <span m="4013630">get</span> <span m="4013780">rid</span>
  <span m="4013900">of</span> <span m="4013990">the</span> <span m="4014050">past,</span>
  <span m="4014650">assuming</span> <span m="4015040">you know the</span> <span m="4015460">set</span>
  <span m="4015610">of</span> <span m="4015700">auditing</span> <span m="4015970">queries</span>
  <span m="4016320">that</span> <span m="4016420">you're</span> <span m="4016510">going</span>
  <span m="4016590">to</span> <span m="4016690">do</span> <span m="4017050">moving</span>
  <span m="4017320">forward.</span> <span m="4017710">We</span> <span m="4017830">don't</span>
  <span m="4017980">implement</span> <span m="4018310">this,</span> <span m="4018520">but</span>
  <span m="4018670">this</span> <span m="4018760">should</span> <span m="4018910">be</span>
  <span m="4019000">possible.</span> <span m="4021920">Right,</span> <span m="4022280">so</span>
  <span m="4022700">if</span> <span m="4022850">you</span> <span m="4022940">wanted</span>
  <span m="4023180">to</span> <span m="4023300">do</span> <span m="4023480">100</span>
  <span m="4023870">million</span> <span m="4024140">rows,</span> <span m="4024470">it</span>
  <span m="4024560">would</span> <span m="4024650">work</span> <span m="4024830">out</span>
  <span m="4025010">to</span> <span m="4025160">be</span> <span m="4025430">about</span>
  <span m="4025670">an</span> <span m="4025760">hour.</span></p><p><span m="4028190">So</span>
  <span m="4028490">here</span> <span m="4029450">is</span> <span m="4029630">a</span>
  <span m="4029660">graph</span> <span m="4030110">which</span> <span m="4030290">shows</span>
  <span m="4032270">how</span> <span m="4032480">long</span> <span m="4032690">it</span>
  <span m="4032780">takes</span> <span m="4033260">to</span> <span m="4033440">create</span>
  <span m="4034010">and</span> <span m="4034130">verify</span> <span m="4034640">transactions</span>
  <span m="4035360">in</span> <span m="4035510">zkLedger.</span> <span m="4036470">And</span>
  <span m="4036590">this</span> <span m="4036770">is</span> <span m="4036890">varying</span>
  <span m="4037250">the</span> <span m="4037340">number</span> <span m="4037550">of</span>
  <span m="4037610">banks.</span> <span m="4038130">And</span> <span m="4038230">again,</span>
  <span m="4038360">we</span> <span m="4038450">see</span> <span m="4038630">this</span>
  <span m="4038780">is</span> <span m="4038870">linear.</span> <span m="4039500">The</span>
  <span m="4039590">more</span> <span m="4039740">banks,</span> <span m="4041210">the</span>
  <span m="4041330">more</span> <span m="4041720">entries</span> <span m="4042200">per</span>
  <span m="4042380">transaction,</span> <span m="4043010">the</span> <span m="4043100">more</span>
  <span m="4043220">of these</span> <span m="4043400">commitments,</span> <span m="4044360">the</span>
  <span m="4044480">more</span> <span m="4044990">range</span> <span m="4045320">proofs,</span>
  <span m="4045770">quite</span> <span m="4046010">honestly,</span> <span m="4046710">is</span>
  <span m="4046760">the</span> <span m="4046820">problem.</span> <span m="4047270">Because</span>
  <span m="4047480">there's</span> <span m="4047630">a</span> <span m="4047690">range</span>
  <span m="4047900">proof</span> <span m="4048110">per</span> <span m="4048350">entry.</span></p><p><span
  m="4049700">And</span> <span m="4050000">what</span> <span m="4050150">we</span>
  <span m="4050240">see</span> <span m="4050420">here</span> <span m="4050600">is</span>
  <span m="4050750">that</span> <span m="4050840">with</span> <span m="4050960">10</span>
  <span m="4051200">banks,</span> <span m="4052010">it's</span> <span m="4052220">about</span>
  <span m="4053780">a</span> <span m="4053900">second</span> <span m="4054740">or</span>
  <span m="4055190">800</span> <span m="4055520">milliseconds</span> <span m="4056090">to</span>
  <span m="4056420">create</span> <span m="4057050">a</span> <span m="4057140">transaction,</span>
  <span m="4057740">which</span> <span m="4057890">is</span> <span m="4058010">not</span>
  <span m="4058820">unreasonable.</span> <span m="4059570">Again,</span> <span m="4059990">this</span>
  <span m="4060470">achieves</span> <span m="4061060">the</span> <span m="4063080">multiple</span>
  <span m="4063500">per</span> <span m="4063650">second</span> <span m="4064280">things</span>
  <span m="4064550">we</span> <span m="4064640">were</span> <span m="4064760">looking</span>
  <span m="4065030">for,</span> <span m="4065350">depending</span> <span m="4065540">on</span>
  <span m="4065660">the</span> <span m="4065720">number</span> <span m="4065930">of</span>
  <span m="4066020">banks.</span> <span m="4066320">However,</span> <span m="4066650">it</span>
  <span m="4066740">is</span> <span m="4066860">linear</span> <span m="4067760">in</span>
  <span m="4067910">the</span> <span m="4068000">number</span> <span m="4068270">of</span>
  <span m="4068360">participants</span> <span m="4068900">in</span> <span m="4068960">the</span>
  <span m="4069020">system.</span> <span m="4069990">So</span> <span m="4070160">something</span>
  <span m="4070460">like</span> <span m="4070640">this</span> <span m="4070820">is</span>
  <span m="4070910">not</span> <span m="4071120">really</span> <span m="4071330">suitable</span>
  <span m="4071840">for</span> <span m="4073860">a</span> <span m="4074270">setting</span>
  <span m="4074570">like</span> <span m="4074750">Bitcoin,</span> <span m="4075440">where</span>
  <span m="4075710">there</span> <span m="4076010">are</span> <span m="4077300">thousands,</span>
  <span m="4077940">if</span> <span m="4078040">not</span> <span m="4078110">millions,</span>
  <span m="4078560">of</span> <span m="4078620">participants</span> <span m="4079220">in</span>
  <span m="4079280">the</span> <span m="4079370">system.</span></p><p><span m="4081670">This
  graph</span> <span m="4082290">gives</span> <span m="4082530">you</span> <span m="4082620">an</span>
  <span m="4082710">idea</span> <span m="4083160">of</span> <span m="4084330">how</span>
  <span m="4084930">all</span> <span m="4085110">of</span> <span m="4085200">that</span>
  <span m="4085320">cost</span> <span m="4085800">breaks</span> <span m="4086250">down.</span>
  <span m="4087280">So</span> <span m="4088110">these</span> <span m="4088410">are</span>
  <span m="4088470">the</span> <span m="4088560">components</span> <span m="4089730">in</span>
  <span m="4090300">the</span> <span m="4090450">proofs.</span> <span m="4093240">And</span>
  <span m="4093390">again,</span> <span m="4093780">I</span> <span m="4094200">think</span>
  <span m="4094660">the</span> <span m="4094830">thing</span> <span m="4095070">to</span>
  <span m="4095190">get</span> <span m="4095430">from</span> <span m="4095670">here</span>
  <span m="4096630">is</span> <span m="4096899">that</span> <span m="4097350">range</span>
  <span m="4097750">proofs</span> <span m="4098430">are</span> <span m="4098790">the</span>
  <span m="4098939">entirety</span> <span m="4100380">of</span> <span m="4100529">the</span>
  <span m="4100620">problem.</span> <span m="4102000">So</span> <span m="4102330">this</span>
  <span m="4102540">is</span> <span m="4102660">the</span> <span m="4102779">number</span>
  <span m="4103439">in</span> <span m="4103590">a</span> <span m="4103620">transaction</span>
  <span m="4104279">for</span> <span m="4104430">k</span> <span m="4104640">participants.</span></p><p><span
  m="4105390">So</span> <span m="4107250">this</span> <span m="4107460">is</span>
  <span m="4107609">each</span> <span m="4107880">slot.</span> <span m="4108779">There</span>
  <span m="4109020">are</span> <span m="4109319">two</span> <span m="4109529">different</span>
  <span m="4109770">commitments.</span> <span m="4110430">The</span> <span m="4110700">first</span>
  <span m="4110939">commitment,</span> <span m="4111300">and</span> <span m="4111390">then</span>
  <span m="4111479">the</span> <span m="4111600">auxiliary</span> <span m="4111990">commitment.</span>
  <span m="4112470">There's</span> <span m="4112620">two</span> <span m="4112740">different</span>
  <span m="4112950">consistency</span> <span m="4113520">proofs.</span> <span m="4113850">There's</span>
  <span m="4114000">a</span> <span m="4114060">disjunctive</span> <span m="4114510">proof,</span>
  <span m="4114720">and</span> <span m="4114810">there's</span> <span m="4114960">a</span>
  <span m="4115069">range</span> <span m="4115319">proof.</span></p><p><span m="4117010">And</span>
  <span m="4117840">yeah,</span> <span m="4118319">the</span> <span m="4119880">commitment</span>
  <span m="4120359">is</span> <span m="4120540">one</span> <span m="4120920">elliptic</span>
  <span m="4121229">curve</span> <span m="4121529">point,</span> <span m="4122279">which</span>
  <span m="4122490">in</span> <span m="4122640">Go</span> <span m="4123180">is</span>
  <span m="4123660">a</span> <span m="4123840">big</span> <span m="4124109">int--</span>
  <span m="4124850">two</span> <span m="4125130">big ints.</span> <span m="4126630">And</span>
  <span m="4126779">so</span> <span m="4126960">that's</span> <span m="4127130">64</span>
  <span m="4127620">bytes.</span> <span m="4128430">This</span> <span m="4128609">is</span>
  <span m="4128700">something</span> <span m="4129120">that</span> <span m="4129479">is</span>
  <span m="4129779">actually</span> <span m="4130200">highly</span> <span m="4130500">compressable.</span>
  <span m="4132880">We</span> <span m="4133290">didn't</span> <span m="4133950">actually--</span>
  <span m="4135319">oh,</span> <span m="4135950">OK.</span> <span m="4136380">Yeah,</span>
  <span m="4136950">I'll</span> <span m="4137100">get</span> <span m="4137220">to</span>
  <span m="4137279">that</span> <span m="4137399">point</span> <span m="4137609">in</span>
  <span m="4137670">a</span> <span m="4137700">moment.</span></p><p><span m="4138200">But</span>
  <span m="4138490">note</span> <span m="4138750">here</span> <span m="4139050">that</span>
  <span m="4140810">the</span> <span m="4140990">range</span> <span m="4141500">proofs</span>
  <span m="4142520">are</span> <span m="4142910">slower</span> <span m="4143540">and</span>
  <span m="4143660">larger</span> <span m="4144109">than</span> <span m="4144260">everything</span>
  <span m="4144649">else</span> <span m="4144800">combined.</span> <span m="4145490">They</span>
  <span m="4145670">are</span> <span m="4145790">the</span> <span m="4145910">entirety</span>
  <span m="4146479">of</span> <span m="4146600">the</span> <span m="4146689">cost</span>
  <span m="4147229">of</span> <span m="4147380">the</span> <span m="4147470">system.</span>
  <span m="4147979">So</span> <span m="4148460">a</span> <span m="4148520">faster</span>
  <span m="4148970">way</span> <span m="4149120">of</span> <span m="4149180">doing</span>
  <span m="4149390">range</span> <span m="4149630">proofs</span> <span m="4150430">would</span>
  <span m="4150620">really</span> <span m="4150859">help</span> <span m="4151040">a</span>
  <span m="4151100">lot.</span> <span m="4151700">It</span> <span m="4151790">would</span>
  <span m="4152359">make</span> <span m="4152569">us</span> <span m="4152830">be</span>
  <span m="4152979">able</span> <span m="4153170">to</span> <span m="4153260">handle</span>
  <span m="4153920">many,</span> <span m="4154350">many</span> <span m="4154460">more</span>
  <span m="4154609">banks.</span></p><p><span m="4157840">So</span> <span m="4157920">this</span>
  <span m="4158100">is</span> <span m="4158189">the</span> <span m="4158279">cost</span>
  <span m="4159210">in</span> <span m="4159330">a</span> <span m="4159390">transaction</span>
  <span m="4160380">per</span> <span m="4160710">participant</span> <span m="4161370">in</span>
  <span m="4161460">the</span> <span m="4161550">system.</span> <span m="4162029">[AUDIO
  OUT]</span> <span m="4167040">One</span> <span m="4167149">thing</span> <span m="4167600">that</span>
  <span m="4167990">I</span> <span m="4168109">want</span> <span m="4168290">to</span>
  <span m="4168350">point</span> <span m="4168590">out</span> <span m="4169310">is</span>
  <span m="4169520">that</span> <span m="4171439">this</span> <span m="4171620">is</span>
  <span m="4171740">all</span> <span m="4171920">very</span> <span m="4172160">highly</span>
  <span m="4172569">parallelizable.</span> <span m="4174410">And</span> <span m="4175160">like</span>
  <span m="4175370">I</span> <span m="4175430">said,</span> <span m="4175920">we're</span>
  <span m="4176060">using</span> <span m="4176630">Go's</span> <span m="4177170">big</span>
  <span m="4177520">int</span> <span m="4177770">construction,</span> <span m="4178580">which</span>
  <span m="4179600">is</span> <span m="4180229">not</span> <span m="4180560">really</span>
  <span m="4180770">very</span> <span m="4180950">optimized</span> <span m="4181430">at</span>
  <span m="4181520">all.</span></p><p><span m="4181800">So</span> <span m="4181910">I</span>
  <span m="4182000">think</span> <span m="4182149">that</span> <span m="4182270">there</span>
  <span m="4182510">are</span> <span m="4182630">a</span> <span m="4182689">lot</span>
  <span m="4182840">of</span> <span m="4182960">opportunities</span> <span m="4184069">to</span>
  <span m="4184189">make</span> <span m="4184370">this</span> <span m="4184550">faster.</span>
  <span m="4185270">So</span> <span m="4186200">I</span> <span m="4186290">think</span>
  <span m="4187250">if</span> <span m="4187430">we</span> <span m="4188000">put</span>
  <span m="4188149">in</span> <span m="4188240">some</span> <span m="4188750">engineering</span>
  <span m="4189370">legwork,</span> <span m="4190189">we</span> <span m="4190819">could</span>
  <span m="4190939">create</span> <span m="4191180">a</span> <span m="4191240">system</span>
  <span m="4191720">that</span> <span m="4191870">was</span> <span m="4192740">maybe</span>
  <span m="4193040">twice</span> <span m="4193370">as</span> <span m="4193490">fast</span>
  <span m="4193760">as</span> <span m="4193880">what</span> <span m="4194000">we</span>
  <span m="4194120">have</span> <span m="4194270">now,</span> <span m="4195080">and</span>
  <span m="4195410">could</span> <span m="4195560">handle</span> <span m="4196760">maybe</span>
  <span m="4197000">100</span> <span m="4197330">banks.</span></p><p><span m="4200090">So</span>
  <span m="4200420">really</span> <span m="4200630">quickly</span> <span m="4200930">to</span>
  <span m="4201020">wrap</span> <span m="4201260">up,</span> <span m="4201470">related</span>
  <span m="4201860">work.</span> <span m="4203240">If</span> <span m="4203360">you're</span>
  <span m="4203510">interested</span> <span m="4203960">in</span> <span m="4204080">this</span>
  <span m="4204260">topic,</span> <span m="4204870">there's</span> <span m="4205070">a</span>
  <span m="4205130">lot</span> <span m="4205400">of</span> <span m="4205490">different</span>
  <span m="4205790">papers</span> <span m="4206210">to</span> <span m="4206330">read</span>
  <span m="4206540">about</span> <span m="4206780">and</span> <span m="4207080">study.</span>
  <span m="4208280">This</span> <span m="4208430">is</span> <span m="4208550">all--</span>
  <span m="4208790">confidential</span> <span m="4209390">assets</span> <span m="4210320">kicked</span>
  <span m="4210590">off</span> <span m="4210770">this</span> <span m="4210920">line</span>
  <span m="4211190">of</span> <span m="4211250">using</span> <span m="4211520">Pedersen</span>
  <span m="4211910">commitments</span> <span m="4212720">for</span> <span m="4212840">privacy</span>
  <span m="4213500">in</span> <span m="4213620">cryptocurrencies.</span> <span m="4214760">Zerocash</span>
  <span m="4215450">was</span> <span m="4215600">the</span> <span m="4215720">origin</span>
  <span m="4216200">of</span> <span m="4216380">using</span> <span m="4216770">zk-SNARKs.</span>
  <span m="4219680">They</span> <span m="4220160">don't</span> <span m="4220370">really</span>
  <span m="4220670">support</span> <span m="4221180">auditing</span> <span m="4221750">in</span>
  <span m="4221870">any</span> <span m="4222050">fashion.</span></p><p><span m="4223640">Then</span>
  <span m="4224030">there's</span> <span m="4225170">a</span> <span m="4225200">couple</span>
  <span m="4225500">papers</span> <span m="4225980">that</span> <span m="4226070">are</span>
  <span m="4226130">really</span> <span m="4226310">interesting,</span> <span m="4226820">one</span>
  <span m="4227030">from</span> <span m="4227690">Andrew</span> <span m="4228020">Lowe,</span>
  <span m="4228500">actually,</span> <span m="4229340">who's</span> <span m="4229760">in</span>
  <span m="4229940">the</span> <span m="4230090">economics</span> <span m="4230600">department</span>
  <span m="4230990">here</span> <span m="4231140">at</span> <span m="4231200">MIT,</span>
  <span m="4232010">on</span> <span m="4232310">using</span> <span m="4233450">secure</span>
  <span m="4233780">multi-party</span> <span m="4234260">computation</span> <span
  m="4235220">to</span> <span m="4235700">attack</span> <span m="4236000">this</span>
  <span m="4236150">problem.</span> <span m="4238210">The</span> <span m="4239330">issue</span>
  <span m="4239630">with</span> <span m="4239840">that</span> <span m="4240260">sort</span>
  <span m="4240500">of</span> <span m="4240590">design</span> <span m="4241760">is</span>
  <span m="4241910">that</span> <span m="4242290">it</span> <span m="4242420">doesn't</span>
  <span m="4242720">actually</span> <span m="4243110">have</span> <span m="4243350">the</span>
  <span m="4243440">completeness</span> <span m="4244040">guarantee</span> <span m="4244520">that</span>
  <span m="4244670">we</span> <span m="4244820">have.</span></p><p><span m="4245640">So</span>
  <span m="4245900">if</span> <span m="4246260">the</span> <span m="4246380">ledger</span>
  <span m="4246740">really</span> <span m="4247040">represents</span> <span m="4247520">the</span>
  <span m="4247640">assets</span> <span m="4247970">in</span> <span m="4248060">the</span>
  <span m="4248120">system,</span> <span m="4248990">and</span> <span m="4249170">the</span>
  <span m="4249290">assets</span> <span m="4249650">that</span> <span m="4249740">you're</span>
  <span m="4249830">trying</span> <span m="4250100">to</span> <span m="4250190">audit,</span>
  <span m="4250790">then</span> <span m="4251090">there's</span> <span m="4251300">no</span>
  <span m="4251480">way</span> <span m="4251660">for</span> <span m="4251810">a</span>
  <span m="4251840">participant</span> <span m="4252320">to</span> <span m="4252410">lie</span>
  <span m="4252860">in</span> <span m="4252950">a</span> <span m="4252980">multi-party</span>
  <span m="4253400">computation.</span> <span m="4254160">They</span> <span m="4254260">can</span>
  <span m="4254300">use</span> <span m="4254840">the</span> <span m="4254930">wrong</span>
  <span m="4255200">inputs.</span> <span m="4255680">So</span> <span m="4255950">those</span>
  <span m="4256130">systems</span> <span m="4256490">provide</span> <span m="4256850">secrecy,</span>
  <span m="4257720">but</span> <span m="4257900">they</span> <span m="4257990">don't</span>
  <span m="4258140">provide</span> <span m="4258620">completeness.</span></p><p><span
  m="4259640">And</span> <span m="4259760">then</span> <span m="4260720">I</span>
  <span m="4260810">mentioned</span> <span m="4261320">Solidus</span> <span m="4261870">before,</span>
  <span m="4262370">which</span> <span m="4262580">I</span> <span m="4262640">think</span>
  <span m="4262880">our</span> <span m="4263000">techniques</span> <span m="4263390">would</span>
  <span m="4263510">apply</span> <span m="4263810">to</span> <span m="4264020">really</span>
  <span m="4264230">nicely.</span> <span m="4265610">And</span> <span m="4266120">then</span>
  <span m="4267770">there's</span> <span m="4268010">a</span> <span m="4268070">paper,</span>
  <span m="4268550">a</span> <span m="4268610">design</span> <span m="4269720">for</span>
  <span m="4269900">doing</span> <span m="4270200">some</span> <span m="4270410">other</span>
  <span m="4270620">sorts</span> <span m="4270980">of</span> <span m="4271100">accountability</span>
  <span m="4271850">stuff</span> <span m="4272300">with</span> <span m="4272480">cryptocurrencies,</span>
  <span m="4273290">like</span> <span m="4273440">proving</span> <span m="4273800">you</span>
  <span m="4273890">paid</span> <span m="4274100">your</span> <span m="4274220">taxes,</span>
  <span m="4275120">or</span> <span m="4275390">proving</span> <span m="4277250">that</span>
  <span m="4277430">money</span> <span m="4277700">didn't</span> <span m="4277940">go</span>
  <span m="4278150">through</span> <span m="4278480">some</span> <span m="4278960">blacklisted</span>
  <span m="4279890">thing</span> <span m="4280310">using</span> <span m="4280940">zk-SNARKs.</span>
  <span m="4282110">But</span> <span m="4282470">that's</span> <span m="4282680">not</span>
  <span m="4282800">really</span> <span m="4282980">a</span> <span m="4283040">system,</span>
  <span m="4283400">it's</span> <span m="4283550">a</span> <span m="4283610">design.</span>
  <span m="4284000">But</span> <span m="4284090">I</span> <span m="4284150">think</span>
  <span m="4284300">that's</span> <span m="4284450">also</span> <span m="4284660">a</span>
  <span m="4284690">really</span> <span m="4284900">promising</span> <span m="4285860">area</span>
  <span m="4286280">to</span> <span m="4286460">consider.</span></p><p><span m="4288170">So,</span>
  <span m="4289910">future</span> <span m="4290270">work.</span> <span m="4292310">We</span>
  <span m="4292460">want</span> <span m="4292610">to</span> <span m="4292670">consider</span>
  <span m="4292970">more</span> <span m="4293180">applications</span> <span m="4293900">besides</span>
  <span m="4294380">just</span> <span m="4295550">large</span> <span m="4295850">investment</span>
  <span m="4296300">banks</span> <span m="4296660">trading</span> <span m="4297050">securities</span>
  <span m="4297590">and</span> <span m="4297710">assets.</span> <span m="4298520">Can</span>
  <span m="4298670">we</span> <span m="4298790">do</span> <span m="4298910">something</span>
  <span m="4299240">with</span> <span m="4300830">clinical</span> <span m="4301160">trials?</span>
  <span m="4302690">Can</span> <span m="4302840">we</span> <span m="4302930">do</span>
  <span m="4303080">something</span> <span m="4303590">with</span> <span m="4303770">supply</span>
  <span m="4304130">chains?</span></p><p><span m="4305390">I</span> <span m="4305450">think</span>
  <span m="4305630">that</span> <span m="4305900">these</span> <span m="4306140">techniques</span>
  <span m="4306650">can</span> <span m="4306800">be</span> <span m="4306920">applied</span>
  <span m="4307790">to</span> <span m="4307940">a</span> <span m="4307970">lot</span>
  <span m="4308120">more</span> <span m="4308270">areas.</span> <span m="4309260">And</span>
  <span m="4309350">I'd</span> <span m="4309500">love</span> <span m="4309650">to</span>
  <span m="4309740">hear</span> <span m="4309860">from</span> <span m="4310010">you</span>
  <span m="4310100">guys</span> <span m="4310340">if</span> <span m="4310430">you</span>
  <span m="4310520">have</span> <span m="4310670">ideas</span> <span m="4310970">on</span>
  <span m="4311090">that,</span> <span m="4311270">or</span> <span m="4311330">if</span>
  <span m="4311420">you're</span> <span m="4311510">interested</span> <span m="4311840">in</span>
  <span m="4311930">working</span> <span m="4312320">on</span> <span m="4312440">that</span>
  <span m="4313100">and</span> <span m="4313250">want</span> <span m="4313460">to</span>
  <span m="4313580">do</span> <span m="4313850">a</span> <span m="4313910">UROP,</span>
  <span m="4314390">or</span> <span m="4315170">maybe</span> <span m="4315380">even</span>
  <span m="4315590">an</span> <span m="4315710">M.Eng.,</span> <span m="4316100">that's</span>
  <span m="4316310">definitely</span> <span m="4316610">something</span> <span m="4316910">that's</span>
  <span m="4317060">on</span> <span m="4317180">the</span> <span m="4317270">table.</span></p><p><span
  m="4318680">We</span> <span m="4319310">get</span> <span m="4319610">surprisingly</span>
  <span m="4320420">far</span> <span m="4320750">with</span> <span m="4320930">Pedersen</span>
  <span m="4321350">commitments,</span> <span m="4322280">but</span> <span m="4322670">if</span>
  <span m="4322850">we</span> <span m="4323000">included</span> <span m="4324380">more</span>
  <span m="4324740">interesting</span> <span m="4325370">types</span> <span m="4325640">of</span>
  <span m="4325700">cryptographic</span> <span m="4326210">primitives,</span> <span
  m="4326690">we</span> <span m="4326780">could</span> <span m="4326900">probably</span>
  <span m="4327200">get</span> <span m="4327320">more</span> <span m="4327440">functionality.</span>
  <span m="4328460">So</span> <span m="4328700">what's</span> <span m="4329060">the</span>
  <span m="4329180">type--</span> <span m="4329450">we</span> <span m="4329600">know,</span>
  <span m="4329900">given</span> <span m="4330440">that</span> <span m="4330680">we</span>
  <span m="4330800">might</span> <span m="4330980">want</span> <span m="4331130">to</span>
  <span m="4331190">apply</span> <span m="4331430">this</span> <span m="4331580">to</span>
  <span m="4331670">different</span> <span m="4331910">use</span> <span m="4332090">cases,</span>
  <span m="4333590">what</span> <span m="4333980">types</span> <span m="4334280">of</span>
  <span m="4334340">functionality</span> <span m="4334910">might</span> <span m="4335360">we</span>
  <span m="4335510">need?</span></p><p><span m="4336680">There's</span> <span m="4336830">someone</span>
  <span m="4337040">at</span> <span m="4337100">the</span> <span m="4337160">Media</span>
  <span m="4337400">Lab</span> <span m="4337580">here</span> <span m="4337910">who</span>
  <span m="4338240">is</span> <span m="4338450">interested</span> <span m="4338840">in</span>
  <span m="4338900">running</span> <span m="4339200">algorithms</span> <span m="4339920">on</span>
  <span m="4341090">research</span> <span m="4341510">trials.</span> <span m="4342470">And</span>
  <span m="4343220">secrecy</span> <span m="4343790">and</span> <span m="4343880">privacy</span>
  <span m="4344270">is</span> <span m="4344360">really</span> <span m="4344540">important.</span>
  <span m="4346430">I</span> <span m="4346520">haven't</span> <span m="4346700">even</span>
  <span m="4346850">looked</span> <span m="4347150">at</span> <span m="4347240">his</span>
  <span m="4347780">machine-learning</span> <span m="4348290">algorithms</span> <span
  m="4348710">yet,</span> <span m="4348920">but</span> <span m="4349160">can</span>
  <span m="4349370">we</span> <span m="4349490">run</span> <span m="4349790">machine-learning</span>
  <span m="4350360">algorithms</span> <span m="4350990">on</span> <span m="4351290">Pedersen</span>
  <span m="4351680">commitments,</span> <span m="4352340">or</span> <span m="4352400">do</span>
  <span m="4352490">we</span> <span m="4352580">need</span> <span m="4352790">something</span>
  <span m="4353600">else?</span></p><p><span m="4356090">Also,</span> <span m="4356540">another</span>
  <span m="4356900">really</span> <span m="4357080">important</span> <span m="4357440">area</span>
  <span m="4357800">of</span> <span m="4357890">future</span> <span m="4358160">work</span>
  <span m="4358370">is</span> <span m="4358470">to</span> <span m="4358510">optimize</span>
  <span m="4358770">the</span> <span m="4359000">implementation.</span> <span m="4359610">Like</span>
  <span m="4359750">I</span> <span m="4359840">said,</span> <span m="4360180">I</span>
  <span m="4360280">think</span> <span m="4360380">we</span> <span m="4360480">get</span>
  <span m="4360680">at</span> <span m="4360740">least</span> <span m="4361010">twice</span>
  <span m="4361280">as</span> <span m="4361400">fast,</span> <span m="4361820">if</span>
  <span m="4361910">not</span> <span m="4362060">more.</span> <span m="4363500">And</span>
  <span m="4363950">in</span> <span m="4364070">conclusion,</span> <span m="4365370">yeah,</span>
  <span m="4365690">if</span> <span m="4365810">you</span> <span m="4365930">want</span>
  <span m="4366050">to</span> <span m="4366110">work</span> <span m="4366290">on</span>
  <span m="4366380">any</span> <span m="4366560">of</span> <span m="4366620">these</span>
  <span m="4366800">things,</span> <span m="4367490">please</span> <span m="4367730">let</span>
  <span m="4367850">me</span> <span m="4367940">know.</span> <span m="4368300">If</span>
  <span m="4368390">you're</span> <span m="4368510">interested</span> <span m="4368960">in</span>
  <span m="4370040">using</span> <span m="4370280">cryptographic</span> <span m="4370760">primitives</span>
  <span m="4371210">to</span> <span m="4371330">achieve</span> <span m="4371660">privacy</span>
  <span m="4372200">with</span> <span m="4372350">interesting</span> <span m="4372740">functions,</span>
  <span m="4373250">let</span> <span m="4373400">me</span> <span m="4373520">know.</span></p><p><span
  m="4375780">And</span> <span m="4375950">this</span> <span m="4376130">is</span>
  <span m="4376260">the</span> <span m="4376350">website</span> <span m="4376700">for</span>
  <span m="4376830">zkLedger,</span> <span m="4377390">which</span> <span m="4377570">at</span>
  <span m="4377630">the</span> <span m="4377750">moment</span> <span m="4378080">is</span>
  <span m="4378170">really</span> <span m="4378470">just</span> <span m="4378740">the</span>
  <span m="4378830">paper.</span> <span m="4380300">We</span> <span m="4380480">have</span>
  <span m="4380870">a</span> <span m="4381020">code</span> <span m="4381260">base</span>
  <span m="4381560">which</span> <span m="4381800">is</span> <span m="4382910">too</span>
  <span m="4383180">embarrassing</span> <span m="4383690">to</span> <span m="4383780">be</span>
  <span m="4383900">released</span> <span m="4384290">out</span> <span m="4384500">into</span>
  <span m="4384680">the</span> <span m="4384770">real</span> <span m="4384920">world,</span>
  <span m="4385400">but</span> <span m="4386000">we'll</span> <span m="4386150">get</span>
  <span m="4386330">there</span> <span m="4386570">shortly,</span> <span m="4387050">once</span>
  <span m="4387260">we</span> <span m="4387320">clean</span> <span m="4387530">it</span>
  <span m="4387620">up.</span> <span m="4388250">So</span> <span m="4388760">that's</span>
  <span m="4388940">it.</span> <span m="4389590">So</span> <span m="4389780">thanks</span>
  <span m="4390170">for</span> <span m="4390320">listening.</span> <span m="4391220">I
  hope</span> <span m="4391520">you found it</span> <span m="4391820">interesting.</span></p><p><span
  m="4392120">[APPLAUSE]</span></p><p>&nbsp;</p>
type: course
uid: 25b467f2a10ad50edf19075f14450646

---
None