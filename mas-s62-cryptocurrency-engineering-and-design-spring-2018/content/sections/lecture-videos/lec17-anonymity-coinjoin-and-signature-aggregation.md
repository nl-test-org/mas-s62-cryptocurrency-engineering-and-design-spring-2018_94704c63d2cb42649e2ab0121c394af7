---
about_this_resource_text: ''
course_id: mas-s62-cryptocurrency-engineering-and-design-spring-2018
embedded_media:
- id: Video-YouTube-Stream
  media_location: BFwc2XA8rSk
  parent_uid: 478d7b4b26f859e2fa14f534f1e1ee77
  title: Video-YouTube-Stream
  type: Video
  uid: 9346cfcfe3694ac68b8afd13049789d2
- id: 3Play-3PlayYouTubeid-MP4
  media_location: BFwc2XA8rSk
  parent_uid: 478d7b4b26f859e2fa14f534f1e1ee77
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: e9311632c11d5915d839d88559bce993
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MITMAS.S62S18/MITMAS_S62S18_lec17_300k.mp4
  parent_uid: 478d7b4b26f859e2fa14f534f1e1ee77
  title: Video-Internet Archive-MP4
  type: Video
  uid: 91be5dd2112efd11994b41e3478268ee
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/BFwc2XA8rSk/default.jpg
  parent_uid: 478d7b4b26f859e2fa14f534f1e1ee77
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d5361004daff524d8db1d80d9d938afe
- id: BFwc2XA8rSk.srt
  parent_uid: 478d7b4b26f859e2fa14f534f1e1ee77
  technical_location: https://ocw.mit.edu/courses/media-arts-and-sciences/mas-s62-cryptocurrency-engineering-and-design-spring-2018/lecture-videos/lec17-anonymity-coinjoin-and-signature-aggregation/BFwc2XA8rSk.srt
  title: 3play caption file
  type: null
  uid: e1599fbe69b0dd2c2b569cfaac876a5b
- id: BFwc2XA8rSk.pdf
  parent_uid: 478d7b4b26f859e2fa14f534f1e1ee77
  technical_location: https://ocw.mit.edu/courses/media-arts-and-sciences/mas-s62-cryptocurrency-engineering-and-design-spring-2018/lecture-videos/lec17-anonymity-coinjoin-and-signature-aggregation/BFwc2XA8rSk.pdf
  title: 3play pdf file
  type: null
  uid: 66cdeceb821fb721421ef88182690786
- id: Caption-3Play YouTube id-SRT
  parent_uid: 478d7b4b26f859e2fa14f534f1e1ee77
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d5ea7c5d9616aaf22720f72fd549bc77
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 478d7b4b26f859e2fa14f534f1e1ee77
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 3b1896fb26a7c45f9957a7e2edd2958b
inline_embed_id: 38397311anonimitycoinjoinandsignatureaggregation5730440
layout: video
order_index: null
parent_uid: 6396b119dea1934ebbe339b1c3062c94
related_resources_text: ''
short_url: lec17-anonymity-coinjoin-and-signature-aggregation
technical_location: https://ocw.mit.edu/courses/media-arts-and-sciences/mas-s62-cryptocurrency-engineering-and-design-spring-2018/lecture-videos/lec17-anonymity-coinjoin-and-signature-aggregation
template_type: Tabbed
title: 'Lecture 17: Anonymity, Coinjoin and Signature Aggregation'
transcript: <p><span m="940">The</span> <span m="1276">following</span> <span m="1612">content</span>
  <span m="1948">is</span> <span m="2284">provided</span> <span m="2620">under</span>
  <span m="2956">a</span> <span m="3293">Creative</span> <span m="3629">Commons</span>
  <span m="3965">license.</span> <span m="4301">Your</span> <span m="4637">support</span>
  <span m="4973">will</span> <span m="5310">help</span> <span m="5818">MIT</span>
  <span m="6326">OpenCourseWare</span> <span m="6834">continue</span> <span m="7342">to</span>
  <span m="7850">offer</span> <span m="8359">high-quality</span> <span m="8867">educational</span>
  <span m="9375">resources</span> <span m="9883">for</span> <span m="10391">free.</span></p><p><span
  m="10900">To</span> <span m="11343">make</span> <span m="11787">a</span> <span m="12230">donation</span>
  <span m="12674">or</span> <span m="13117">to</span> <span m="13561">view</span>
  <span m="14004">additional</span> <span m="14448">materials</span> <span m="14891">from</span>
  <span m="15335">hundreds</span> <span m="15778">of</span> <span m="16222">MIT</span>
  <span m="16665">courses,</span> <span m="17109">visit</span> <span m="17552">MIT</span>
  <span m="17996">OpenCourseWare</span> <span m="18440">at</span> <span m="19315">ocw.mit.edu.</span></p><p><span
  m="20190">TADGE</span> <span m="20786">DRYJA:</span> <span m="21383">OK,</span>
  <span m="21980">so</span> <span m="22577">today</span> <span m="23174">I'll</span>
  <span m="23771">talk</span> <span m="24368">about</span> <span m="24965">CoinJoin,</span>
  <span m="25562">signature</span> <span m="26159">aggregation,</span> <span m="26756">well</span>
  <span m="27353">before</span> <span m="27950">that</span> <span m="28388">privacy,</span>
  <span m="28826">but</span> <span m="29265">privacy,</span> <span m="29703">CoinJoin,</span>
  <span m="30141">CoinShuffle,</span> <span m="30580">signature</span> <span m="31018">aggregation,</span>
  <span m="31457">and</span> <span m="31895">how</span> <span m="32333">these</span>
  <span m="32772">all</span> <span m="33210">connect.</span></p><p><span m="33649">It's</span>
  <span m="33892">a</span> <span m="34136">little</span> <span m="34380">bit</span>
  <span m="34623">of</span> <span m="34867">a</span> <span m="35111">leap</span> <span
  m="35355">to</span> <span m="35598">put</span> <span m="35842">these</span> <span
  m="36086">both</span> <span m="36330">in</span> <span m="36573">the</span> <span
  m="36817">same</span> <span m="37061">class,</span> <span m="37305">but</span> <span
  m="37548">not</span> <span m="37792">really.</span> <span m="38036">They're</span>
  <span m="38280">connected.</span> <span m="38803">But</span> <span m="39327">they</span>
  <span m="39851">are</span> <span m="40375">somewhat</span> <span m="40898">separate</span>
  <span m="41422">things.</span> <span m="41946">Today,</span> <span m="42470">I'll</span>
  <span m="42993">talk</span> <span m="43517">about</span> <span m="44041">privacy,</span>
  <span m="44565">CoinJoin,</span> <span m="45089">and</span> <span m="45504">various</span>
  <span m="45919">ways</span> <span m="46334">to</span> <span m="46749">do</span>
  <span m="47164">that,</span> <span m="47579">and</span> <span m="47994">then</span>
  <span m="48409">aggregate</span> <span m="48824">signatures,</span> <span m="49239">so</span>
  <span m="49654">Schnorr</span> <span m="50069">multi-signatures,</span> <span m="50484">and</span>
  <span m="50899">then</span> <span m="51441">aggregation,</span> <span m="51984">and</span>
  <span m="52527">attacks</span> <span m="53070">on</span> <span m="53613">the</span>
  <span m="54156">system.</span></p><p><span m="54699">OK,</span> <span m="55137">so</span>
  <span m="55576">the</span> <span m="56015">idea</span> <span m="56454">is</span>
  <span m="56893">privacy.</span> <span m="57332">And</span> <span m="57771">there's</span>
  <span m="58210">a</span> <span m="58649">bunch</span> <span m="59088">of</span>
  <span m="59527">terms</span> <span m="59966">we</span> <span m="60405">can</span>
  <span m="60844">use</span> <span m="61283">here,</span> <span m="61722">like</span>
  <span m="62161">anonymity</span> <span m="62600">and</span> <span m="62919">fungibility.</span>
  <span m="63238">And</span> <span m="63558">whatever</span> <span m="63877">the</span>
  <span m="64196">term</span> <span m="64516">for</span> <span m="64835">this,</span>
  <span m="65155">I</span> <span m="65474">don't</span> <span m="65793">need</span>
  <span m="66113">any,</span> <span m="66432">because</span> <span m="66751">I</span>
  <span m="67071">have</span> <span m="67390">nothing</span> <span m="67710">to</span>
  <span m="68215">hide.</span></p><p><span m="68720">So</span> <span m="68959">I</span>
  <span m="69198">don't</span> <span m="69438">need</span> <span m="69677">any</span>
  <span m="69916">privacy.</span> <span m="70156">I</span> <span m="70395">don't</span>
  <span m="70634">need</span> <span m="70874">any</span> <span m="71113">anonymity.</span>
  <span m="71352">I'm</span> <span m="71592">a</span> <span m="71831">good</span>
  <span m="72070">person.</span> <span m="72310">I</span> <span m="72549">don't</span>
  <span m="72789">break</span> <span m="73104">the</span> <span m="73420">law.</span>
  <span m="73736">I'm</span> <span m="74052">a</span> <span m="74368">boring</span>
  <span m="74684">guy.</span> <span m="75000">I</span> <span m="75316">don't</span>
  <span m="75632">do</span> <span m="75948">anything</span> <span m="76264">crazy.</span></p><p><span
  m="76580">I'm</span> <span m="76984">joking,</span> <span m="77388">but--</span>
  <span m="77792">no,</span> <span m="78196">I'm</span> <span m="78600">not</span>
  <span m="79004">joking</span> <span m="79408">about</span> <span m="79812">being</span>
  <span m="80216">boring</span> <span m="80620">and</span> <span m="81024">not</span>
  <span m="81428">doing</span> <span m="81832">anything</span> <span m="82236">crazy.</span></p><p><span
  m="82640">That</span> <span m="83009">is</span> <span m="83378">actually</span>
  <span m="83747">pretty</span> <span m="84116">true.</span> <span m="84485">I</span>
  <span m="84855">mostly</span> <span m="85224">just</span> <span m="85593">work</span>
  <span m="85962">on</span> <span m="86331">this</span> <span m="86700">stuff.</span></p><p><span
  m="87070">But,</span> <span m="87641">yeah,</span> <span m="88212">that's</span>
  <span m="88783">a</span> <span m="89355">fairly</span> <span m="89926">common</span>
  <span m="90497">thing</span> <span m="91068">that</span> <span m="91640">people</span>
  <span m="92211">say.</span> <span m="92782">And</span> <span m="93353">the</span>
  <span m="93925">sort</span> <span m="94496">of</span> <span m="95067">clearest</span>
  <span m="95638">example</span> <span m="96210">is</span> <span m="96507">if</span>
  <span m="96804">you</span> <span m="97102">don't</span> <span m="97399">have</span>
  <span m="97696">anything</span> <span m="97994">to</span> <span m="98291">hide,</span>
  <span m="98588">you</span> <span m="98886">don't</span> <span m="99183">have</span>
  <span m="99480">any</span> <span m="99778">bitcoin,</span> <span m="100075">because</span>
  <span m="100372">literally,</span> <span m="100670">if</span> <span m="100995">you</span>
  <span m="101320">don't</span> <span m="101646">hide</span> <span m="101971">your</span>
  <span m="102296">private</span> <span m="102622">key,</span> <span m="102947">someone</span>
  <span m="103272">will</span> <span m="103598">just</span> <span m="103923">immediately</span>
  <span m="104248">take</span> <span m="104574">your</span> <span m="104899">bitcoin.</span>
  <span m="105224">So</span> <span m="105550">you</span> <span m="106170">do</span>
  <span m="106790">have</span> <span m="107410">secrets.</span></p><p><span m="108030">Your</span>
  <span m="108384">secret</span> <span m="108739">is</span> <span m="109094">your</span>
  <span m="109448">private</span> <span m="109803">key</span> <span m="110158">and</span>
  <span m="110512">your</span> <span m="110867">password.</span> <span m="111222">And</span>
  <span m="111577">if</span> <span m="111931">bitcoin</span> <span m="112286">and</span>
  <span m="112641">these</span> <span m="112995">types</span> <span m="113350">of</span>
  <span m="113705">systems</span> <span m="114060">really</span> <span m="114375">take</span>
  <span m="114690">off,</span> <span m="115005">potentially</span> <span m="115321">most</span>
  <span m="115636">of</span> <span m="115951">your</span> <span m="116267">money</span>
  <span m="116582">and</span> <span m="116897">a</span> <span m="117212">lot</span>
  <span m="117528">of</span> <span m="117843">your</span> <span m="118158">wealth</span>
  <span m="118474">could</span> <span m="118789">be</span> <span m="119104">tied</span>
  <span m="119420">up</span> <span m="119707">in</span> <span m="119994">what</span>
  <span m="120281">is</span> <span m="120568">a</span> <span m="120855">secret.</span>
  <span m="121142">So</span> <span m="121429">if</span> <span m="121716">you're</span>
  <span m="122003">not</span> <span m="122290">able</span> <span m="122577">to</span>
  <span m="122864">keep</span> <span m="123151">your</span> <span m="123438">secrets</span>
  <span m="123725">you</span> <span m="124012">could</span> <span m="124299">lose</span>
  <span m="124586">a</span> <span m="124873">lot</span> <span m="125161">of</span>
  <span m="125608">money.</span> <span m="126055">And</span> <span m="126503">larger,</span>
  <span m="126950">I</span> <span m="127397">sort</span> <span m="127845">of</span>
  <span m="128292">think</span> <span m="128740">that</span> <span m="129187">going</span>
  <span m="129634">forward--</span> <span m="130082">this</span> <span m="130529">is</span>
  <span m="130976">very</span> <span m="131424">thought</span> <span m="131871">leader,</span>
  <span m="132319">future</span> <span m="132681">kind</span> <span m="133044">of</span>
  <span m="133407">thing.</span></p><p><span m="133770">But</span> <span m="134101">going</span>
  <span m="134432">forward,</span> <span m="134763">it</span> <span m="135094">seems</span>
  <span m="135425">like</span> <span m="135756">sort</span> <span m="136087">of</span>
  <span m="136418">all</span> <span m="136750">you</span> <span m="137081">have</span>
  <span m="137412">is</span> <span m="137743">your</span> <span m="138074">secrets.</span>
  <span m="138405">To</span> <span m="138736">the</span> <span m="139067">extent</span>
  <span m="139398">that</span> <span m="139730">you</span> <span m="139940">can</span>
  <span m="140150">own</span> <span m="140360">anything,</span> <span m="140570">the</span>
  <span m="140780">thing</span> <span m="140990">that</span> <span m="141200">you</span>
  <span m="141410">really</span> <span m="141620">have</span> <span m="141830">control</span>
  <span m="142040">of,</span> <span m="142250">you're</span> <span m="142460">like,</span>
  <span m="142670">OK,</span> <span m="142880">I</span> <span m="143090">got</span>
  <span m="143300">these</span> <span m="143510">things</span> <span m="143851">in</span>
  <span m="144192">my</span> <span m="144533">head</span> <span m="144874">that</span>
  <span m="145215">no</span> <span m="145556">one</span> <span m="145897">else</span>
  <span m="146238">knows.</span> <span m="146579">And</span> <span m="146920">maybe</span>
  <span m="147261">I</span> <span m="147602">own</span> <span m="147943">my</span>
  <span m="148284">car.</span> <span m="148625">But</span> <span m="148966">that's</span>
  <span m="149307">also</span> <span m="149648">sort</span> <span m="149990">of</span>
  <span m="150282">property</span> <span m="150575">rights,</span> <span m="150867">and</span>
  <span m="151160">legal</span> <span m="151452">systems,</span> <span m="151745">and</span>
  <span m="152037">maybe</span> <span m="152330">you</span> <span m="152622">can</span>
  <span m="152915">get</span> <span m="153207">repossessed.</span></p><p><span m="153500">Maybe</span>
  <span m="153750">I</span> <span m="154000">own</span> <span m="154250">this</span>
  <span m="154500">land.</span> <span m="154750">But,</span> <span m="155000">again,</span>
  <span m="155250">that's</span> <span m="155500">sort</span> <span m="155750">of</span>
  <span m="156000">this</span> <span m="156250">thing</span> <span m="156500">with</span>
  <span m="156750">the</span> <span m="157000">state.</span> <span m="157250">But</span>
  <span m="157500">I</span> <span m="157750">definitely</span> <span m="158000">really</span>
  <span m="158399">have</span> <span m="158798">the</span> <span m="159198">stuff</span>
  <span m="159597">in</span> <span m="159996">my</span> <span m="160396">head.</span>
  <span m="160795">And</span> <span m="161195">I</span> <span m="161594">can</span>
  <span m="161993">at</span> <span m="162393">least</span> <span m="162792">try</span>
  <span m="163191">to</span> <span m="163591">keep</span> <span m="163990">that.</span></p><p><span
  m="164390">So</span> <span m="164654">even</span> <span m="164918">if</span> <span
  m="165182">you</span> <span m="165446">think</span> <span m="165711">you</span>
  <span m="165975">have</span> <span m="166239">nothing</span> <span m="166503">to</span>
  <span m="166767">hide,</span> <span m="167032">you</span> <span m="167296">do</span>
  <span m="167560">have</span> <span m="167824">your</span> <span m="168088">private</span>
  <span m="168353">keys</span> <span m="168617">to</span> <span m="168881">hide.</span>
  <span m="169145">And</span> <span m="169410">that's</span> <span m="169881">sort</span>
  <span m="170352">of</span> <span m="170824">the</span> <span m="171295">obvious</span>
  <span m="171766">one.</span> <span m="172238">But</span> <span m="172709">larger,</span>
  <span m="173180">you</span> <span m="173652">want</span> <span m="174123">privacy</span>
  <span m="174594">because,</span> <span m="175066">in</span> <span m="175537">general,</span>
  <span m="176008">you</span> <span m="176480">don't</span> <span m="176782">want</span>
  <span m="177084">to</span> <span m="177386">reveal</span> <span m="177689">stuff</span>
  <span m="177991">about</span> <span m="178293">your</span> <span m="178596">coins.</span>
  <span m="178898">This</span> <span m="179200">is</span> <span m="179503">specific</span>
  <span m="179805">to</span> <span m="180107">bitcoin.</span></p><p><span m="180410">But</span>
  <span m="180762">my</span> <span m="181115">philosophy</span> <span m="181468">is</span>
  <span m="181821">I</span> <span m="182173">generally</span> <span m="182526">don't</span>
  <span m="182879">want</span> <span m="183232">to</span> <span m="183585">reveal</span>
  <span m="183937">stuff</span> <span m="184290">ever.</span> <span m="184643">And</span>
  <span m="184996">it's</span> <span m="185348">a</span> <span m="185701">lot</span>
  <span m="186054">of</span> <span m="186407">times</span> <span m="186760">at</span>
  <span m="187027">stores.</span> <span m="187294">I</span> <span m="187562">remember</span>
  <span m="187829">like</span> <span m="188096">Radio</span> <span m="188364">Shack,</span>
  <span m="188631">when</span> <span m="188898">it</span> <span m="189166">was</span>
  <span m="189433">still</span> <span m="189701">a</span> <span m="189968">thing</span>
  <span m="190235">when</span> <span m="190503">I</span> <span m="190770">was</span>
  <span m="191037">in</span> <span m="191305">high</span> <span m="191572">school,</span>
  <span m="191840">they</span> <span m="192071">would</span> <span m="192303">always</span>
  <span m="192535">ask</span> <span m="192767">you</span> <span m="192998">your</span>
  <span m="193230">phone</span> <span m="193462">number</span> <span m="193694">when</span>
  <span m="193925">you</span> <span m="194157">bought</span> <span m="194389">anything.</span>
  <span m="194621">And</span> <span m="194852">when</span> <span m="195084">I</span>
  <span m="195316">was</span> <span m="195548">little,</span> <span m="195780">I</span>
  <span m="196062">would</span> <span m="196345">just</span> <span m="196628">tell</span>
  <span m="196910">them</span> <span m="197193">my</span> <span m="197476">parents</span>
  <span m="197758">phone</span> <span m="198041">number</span> <span m="198324">at</span>
  <span m="198606">my</span> <span m="198889">house,</span> <span m="199172">because</span>
  <span m="199454">they</span> <span m="199737">asked.</span></p><p><span m="200020">But</span>
  <span m="200181">then</span> <span m="200343">once</span> <span m="200505">I</span>
  <span m="200666">was</span> <span m="200828">in</span> <span m="200990">college,</span>
  <span m="201151">I</span> <span m="201313">was</span> <span m="201475">like,</span>
  <span m="201636">wait,</span> <span m="201798">no</span> <span m="201960">I'm</span>
  <span m="202121">just</span> <span m="202283">going</span> <span m="202445">to</span>
  <span m="202606">make</span> <span m="202768">something</span> <span m="202930">up.</span>
  <span m="203290">And</span> <span m="203651">now</span> <span m="204011">I</span>
  <span m="204372">do</span> <span m="204732">that</span> <span m="205093">all</span>
  <span m="205454">the</span> <span m="205814">time.</span> <span m="206175">And</span>
  <span m="206535">it</span> <span m="206896">sometimes</span> <span m="207257">gets</span>
  <span m="207617">annoying</span> <span m="207978">for</span> <span m="208338">other</span>
  <span m="208699">people,</span> <span m="209060">because</span> <span m="209322">I</span>
  <span m="209584">would</span> <span m="209846">like</span> <span m="210108">go</span>
  <span m="210370">to</span> <span m="210632">a</span> <span m="210894">restaurant.</span>
  <span m="211156">They</span> <span m="211418">ask</span> <span m="211681">to</span>
  <span m="211943">put</span> <span m="212205">my</span> <span m="212467">name</span>
  <span m="212729">down.</span> <span m="212991">I'll</span> <span m="213253">say</span>
  <span m="213515">I'm</span> <span m="213777">Fred.</span></p><p><span m="214040">And</span>
  <span m="214332">then</span> <span m="214625">my</span> <span m="214918">other</span>
  <span m="215211">friend</span> <span m="215504">comes.</span> <span m="215797">And</span>
  <span m="216090">she</span> <span m="216383">was</span> <span m="216676">like,</span>
  <span m="216969">wait,</span> <span m="217262">you're</span> <span m="217555">not</span>
  <span m="217848">listed.</span> <span m="218141">And</span> <span m="218434">then</span>
  <span m="218727">she</span> <span m="219020">put</span> <span m="219449">her</span>
  <span m="219878">name</span> <span m="220308">in.</span> <span m="220737">I'm</span>
  <span m="221166">like,</span> <span m="221596">no,</span> <span m="222025">I'm</span>
  <span m="222455">already</span> <span m="222884">there.</span> <span m="223313">I'm</span>
  <span m="223743">Fred,</span> <span m="224172">and</span> <span m="224601">confusing</span>
  <span m="225031">things</span> <span m="225460">like</span> <span m="225890">that.</span></p><p><span
  m="226890">And</span> <span m="227378">I</span> <span m="227866">hope,</span> <span
  m="228355">and</span> <span m="228843">I</span> <span m="229331">sort</span> <span
  m="229820">of</span> <span m="230308">think</span> <span m="230796">that</span>
  <span m="231285">we're</span> <span m="231773">starting</span> <span m="232261">to</span>
  <span m="232750">see</span> <span m="233238">this</span> <span m="233726">kind</span>
  <span m="234215">of</span> <span m="234703">thing.</span> <span m="235191">Like,</span>
  <span m="235680">there's</span> <span m="235953">like</span> <span m="236227">Facebook</span>
  <span m="236500">hearings</span> <span m="236774">now.</span> <span m="237047">And</span>
  <span m="237321">people</span> <span m="237595">are</span> <span m="237868">all</span>
  <span m="238142">shocked</span> <span m="238415">that</span> <span m="238689">the</span>
  <span m="238962">company</span> <span m="239236">Facebook</span> <span m="239510">can</span>
  <span m="239817">read</span> <span m="240124">everyone's</span> <span m="240432">messages</span>
  <span m="240739">and</span> <span m="241046">see</span> <span m="241354">everything.</span>
  <span m="241661">Well,</span> <span m="241968">yeah,</span> <span m="242276">that's</span>
  <span m="242583">how</span> <span m="242890">it</span> <span m="243198">works.</span>
  <span m="243505">You're</span> <span m="243812">giving</span> <span m="244120">it</span>
  <span m="244786">all</span> <span m="245452">to</span> <span m="246118">their</span>
  <span m="246784">servers.</span></p><p><span m="247450">So</span> <span m="247670">I</span>
  <span m="247890">think</span> <span m="248110">it's</span> <span m="248330">starting</span>
  <span m="248550">to</span> <span m="248770">be,</span> <span m="248990">like</span>
  <span m="249210">where</span> <span m="249430">before</span> <span m="249650">companies</span>
  <span m="249870">would</span> <span m="250090">all</span> <span m="250310">be</span>
  <span m="250530">like,</span> <span m="250750">we</span> <span m="250970">just</span>
  <span m="251190">want</span> <span m="251405">to</span> <span m="251621">get</span>
  <span m="251836">all</span> <span m="252052">the</span> <span m="252267">user</span>
  <span m="252483">data</span> <span m="252698">possible,</span> <span m="252914">hopefully</span>
  <span m="253129">going</span> <span m="253345">forward</span> <span m="253560">data</span>
  <span m="253776">will</span> <span m="253991">be</span> <span m="254207">seen</span>
  <span m="254422">more</span> <span m="254638">as</span> <span m="254853">a</span>
  <span m="255069">liability</span> <span m="255469">and</span> <span m="255869">less</span>
  <span m="256269">as</span> <span m="256669">an</span> <span m="257069">asset.</span>
  <span m="257469">We're</span> <span m="257869">not</span> <span m="258269">there</span>
  <span m="258669">yet,</span> <span m="259069">because</span> <span m="259469">the</span>
  <span m="259869">companies</span> <span m="260269">who</span> <span m="260669">get</span>
  <span m="261069">sort</span> <span m="261470">of</span> <span m="261866">hacked</span>
  <span m="262263">and</span> <span m="262660">lose</span> <span m="263057">all</span>
  <span m="263454">this</span> <span m="263851">user</span> <span m="264248">data</span>
  <span m="264645">don't</span> <span m="265041">really</span> <span m="265438">get</span>
  <span m="265835">punished.</span> <span m="266232">So</span> <span m="266629">the</span>
  <span m="267026">Equifax</span> <span m="267423">thing,</span> <span m="267820">and</span>
  <span m="268117">all</span> <span m="268415">these</span> <span m="268713">different</span>
  <span m="269010">data</span> <span m="269308">breaches,</span> <span m="269606">there's</span>
  <span m="269903">not</span> <span m="270201">a</span> <span m="270499">ton</span>
  <span m="270796">of</span> <span m="271094">consequences</span> <span m="271392">yet.</span></p><p><span
  m="271690">Maybe</span> <span m="271875">there</span> <span m="272060">will</span>
  <span m="272245">be</span> <span m="272431">in</span> <span m="272616">the</span>
  <span m="272801">future.</span> <span m="272987">And</span> <span m="273172">maybe</span>
  <span m="273357">companies</span> <span m="273542">will</span> <span m="273728">start</span>
  <span m="273913">to</span> <span m="274098">not</span> <span m="274284">want</span>
  <span m="274469">all</span> <span m="274654">this</span> <span m="274840">data.</span>
  <span m="275279">But</span> <span m="275718">it's</span> <span m="276158">not</span>
  <span m="276597">as</span> <span m="277037">clean</span> <span m="277476">cut</span>
  <span m="277916">as,</span> <span m="278355">well,</span> <span m="278795">I</span>
  <span m="279234">didn't</span> <span m="279673">do</span> <span m="280113">anything</span>
  <span m="280552">wrong,</span> <span m="280992">so</span> <span m="281431">I</span>
  <span m="281871">don't</span> <span m="282310">want</span> <span m="282750">to</span>
  <span m="283083">hide</span> <span m="283416">anything.</span></p><p><span m="283750">Sort</span>
  <span m="284129">of</span> <span m="284508">default</span> <span m="284888">hide</span>
  <span m="285267">is</span> <span m="285646">my</span> <span m="286026">stance.</span>
  <span m="286405">And</span> <span m="286784">there's</span> <span m="287164">so</span>
  <span m="287543">many</span> <span m="287922">conflicting</span> <span m="288302">interests</span>
  <span m="288681">where</span> <span m="289060">every</span> <span m="289440">time</span>
  <span m="289698">you're</span> <span m="289956">on</span> <span m="290214">the</span>
  <span m="290472">websites,</span> <span m="290730">it's</span> <span m="290988">like,</span>
  <span m="291246">this</span> <span m="291504">website</span> <span m="291762">wants</span>
  <span m="292020">your</span> <span m="292278">location.</span> <span m="292536">And</span>
  <span m="292794">you're</span> <span m="293052">like,</span> <span m="293310">wait,</span>
  <span m="293701">how</span> <span m="294092">do</span> <span m="294483">I</span>
  <span m="294875">always</span> <span m="295266">disable</span> <span m="295657">that?</span>
  <span m="296048">I</span> <span m="296440">don't</span> <span m="296831">know</span>
  <span m="297222">the</span> <span m="297613">settings.</span> <span m="298005">But</span>
  <span m="298396">everyone</span> <span m="298787">wants</span> <span m="299178">this</span>
  <span m="299570">stuff.</span></p><p><span m="300570">So</span> <span m="301102">another</span>
  <span m="301635">reason,</span> <span m="302168">specifically</span> <span m="302701">in</span>
  <span m="303234">the</span> <span m="303767">case</span> <span m="304300">of</span>
  <span m="304832">money,</span> <span m="305365">is</span> <span m="305898">what's</span>
  <span m="306431">called</span> <span m="306964">fungibility.</span> <span m="307497">And</span>
  <span m="308030">it</span> <span m="308299">sounds</span> <span m="308568">like</span>
  <span m="308838">a</span> <span m="309107">weird</span> <span m="309377">word.</span>
  <span m="309646">It</span> <span m="309916">just</span> <span m="310185">means</span>
  <span m="310455">that</span> <span m="310724">every</span> <span m="310993">bitcoin</span>
  <span m="311263">is</span> <span m="311532">the</span> <span m="311802">same,</span>
  <span m="312071">or</span> <span m="312341">every</span> <span m="312610">dollar</span>
  <span m="312880">is</span> <span m="313326">the</span> <span m="313773">same.</span></p><p><span
  m="314220">So</span> <span m="314643">dollars</span> <span m="315067">are</span>
  <span m="315491">fungible,</span> <span m="315915">in</span> <span m="316338">that,</span>
  <span m="316762">physically,</span> <span m="317186">this</span> <span m="317610">$20</span>
  <span m="318033">bill</span> <span m="318457">and</span> <span m="318881">this</span>
  <span m="319305">$20</span> <span m="319728">bill</span> <span m="320152">are</span>
  <span m="320576">worth</span> <span m="321000">the</span> <span m="321360">same.</span>
  <span m="321720">And</span> <span m="322080">different</span> <span m="322440">denominations,</span>
  <span m="322800">so</span> <span m="323160">I</span> <span m="323520">will</span>
  <span m="323880">give</span> <span m="324240">you</span> <span m="324600">a</span>
  <span m="324960">20</span> <span m="325320">for</span> <span m="325680">two</span>
  <span m="326040">10's.</span> <span m="326400">And</span> <span m="326760">anyone</span>
  <span m="327120">will</span> <span m="327441">do</span> <span m="327762">that.</span>
  <span m="328084">They're</span> <span m="328405">worth</span> <span m="328727">the</span>
  <span m="329048">same.</span></p><p><span m="329370">You</span> <span m="329726">don't</span>
  <span m="330082">have,</span> <span m="330438">well,</span> <span m="330795">this</span>
  <span m="331151">dollar</span> <span m="331507">is</span> <span m="331863">not</span>
  <span m="332220">worth</span> <span m="332576">quite</span> <span m="332932">as</span>
  <span m="333288">much.</span> <span m="333645">And</span> <span m="334001">sometimes</span>
  <span m="334357">that</span> <span m="334713">happens,</span> <span m="335070">even</span>
  <span m="335431">with</span> <span m="335793">dollar</span> <span m="336155">bills.</span>
  <span m="336517">Like</span> <span m="336878">in</span> <span m="337240">other</span>
  <span m="337602">countries,</span> <span m="337964">I</span> <span m="338325">think</span>
  <span m="338687">in</span> <span m="339049">the</span> <span m="339411">Philippines</span>
  <span m="339772">when</span> <span m="340134">the</span> <span m="340496">new</span>
  <span m="340858">$100</span> <span m="341220">bills</span> <span m="341516">were</span>
  <span m="341813">issued</span> <span m="342109">that</span> <span m="342406">have</span>
  <span m="342703">the</span> <span m="342999">like</span> <span m="343296">little</span>
  <span m="343592">blue</span> <span m="343889">shiny</span> <span m="344186">thing,</span>
  <span m="344482">people</span> <span m="344779">didn't</span> <span m="345075">like</span>
  <span m="345372">them.</span></p><p><span m="345669">And</span> <span m="345884">people</span>
  <span m="346099">were</span> <span m="346314">like,</span> <span m="346530">no,</span>
  <span m="346745">I</span> <span m="346960">won't</span> <span m="347176">trade</span>
  <span m="347391">my</span> <span m="347606">old</span> <span m="347822">$100</span>
  <span m="348037">bill</span> <span m="348252">for</span> <span m="348468">your</span>
  <span m="348683">new</span> <span m="348898">$100</span> <span m="349114">bill.</span>
  <span m="349329">I</span> <span m="349544">don't</span> <span m="349760">trust</span>
  <span m="350038">this</span> <span m="350316">new</span> <span m="350594">one.</span>
  <span m="350872">Eventually,</span> <span m="351150">they</span> <span m="351428">got</span>
  <span m="351706">used</span> <span m="351984">to</span> <span m="352262">it.</span></p><p><span
  m="352540">But</span> <span m="352848">there's</span> <span m="353157">things,</span>
  <span m="353466">that</span> <span m="353775">even</span> <span m="354083">money</span>
  <span m="354392">can</span> <span m="354701">be</span> <span m="355010">not</span>
  <span m="355318">fungible.</span> <span m="355627">So</span> <span m="355936">the</span>
  <span m="356245">classic</span> <span m="356553">example</span> <span m="356862">is,</span>
  <span m="357171">OK,</span> <span m="357480">gold</span> <span m="357885">is</span>
  <span m="358290">fungible.</span> <span m="358695">Diamonds</span> <span m="359100">are</span>
  <span m="359505">not.</span> <span m="359910">Diamonds,</span> <span m="360315">I</span>
  <span m="360720">have</span> <span m="361125">little</span> <span m="361530">experience</span>
  <span m="361935">with</span> <span m="362340">diamonds</span> <span m="362745">they</span>
  <span m="363150">seem</span> <span m="363626">kind</span> <span m="364102">of</span>
  <span m="364578">silly,</span> <span m="365055">but</span> <span m="365531">they're</span>
  <span m="366007">all</span> <span m="366483">unique.</span></p><p><span m="366960">They've</span>
  <span m="367231">got</span> <span m="367503">different</span> <span m="367774">grades,</span>
  <span m="368046">and</span> <span m="368317">different</span> <span m="368589">cuts,</span>
  <span m="368860">and</span> <span m="369132">different</span> <span m="369403">sizes,</span>
  <span m="369675">and</span> <span m="369946">carrots,</span> <span m="370218">and</span>
  <span m="370490">little</span> <span m="370932">inclusions,</span> <span m="371375">and</span>
  <span m="371817">imperfections.</span> <span m="372260">And</span> <span m="372702">you've</span>
  <span m="373145">got</span> <span m="373587">this</span> <span m="374030">whole</span>
  <span m="374472">industry,</span> <span m="374915">where</span> <span m="375357">people</span>
  <span m="375800">with</span> <span m="376010">these</span> <span m="376220">little</span>
  <span m="376430">eye</span> <span m="376640">things</span> <span m="376850">look</span>
  <span m="377060">at</span> <span m="377270">the</span> <span m="377480">diamonds,</span>
  <span m="377690">and</span> <span m="377900">figure</span> <span m="378110">out,</span>
  <span m="378320">oh,</span> <span m="378530">this</span> <span m="378740">is</span>
  <span m="378950">a</span> <span m="379160">good</span> <span m="379370">one.</span>
  <span m="379580">And</span> <span m="379790">this</span> <span m="380127">one</span>
  <span m="380465">is</span> <span m="380803">so,</span> <span m="381141">so.</span></p><p><span
  m="381479">Whereas</span> <span m="381865">gold</span> <span m="382252">is,</span>
  <span m="382639">sort</span> <span m="383025">of</span> <span m="383412">also</span>
  <span m="383799">has</span> <span m="384186">essayists,</span> <span m="384572">and</span>
  <span m="384959">good</span> <span m="385346">delivery</span> <span m="385733">standards,</span>
  <span m="386119">and</span> <span m="386506">all</span> <span m="386893">these</span>
  <span m="387280">things</span> <span m="387538">for</span> <span m="387797">the</span>
  <span m="388056">gold</span> <span m="388314">bars.</span> <span m="388573">But</span>
  <span m="388832">it's</span> <span m="389090">much</span> <span m="389349">more</span>
  <span m="389608">of</span> <span m="389866">a</span> <span m="390125">standard.</span>
  <span m="390384">There's</span> <span m="390642">no</span> <span m="390901">judgment</span>
  <span m="391160">calls.</span></p><p><span m="391419">It's</span> <span m="391730">like,</span>
  <span m="392041">OK,</span> <span m="392352">this</span> <span m="392663">is</span>
  <span m="392974">gold.</span> <span m="393286">It's</span> <span m="393597">99.95%</span>
  <span m="393908">pure.</span> <span m="394219">It</span> <span m="394530">weighs</span>
  <span m="394841">this</span> <span m="395153">much.</span> <span m="395464">This</span>
  <span m="395775">is</span> <span m="396086">how</span> <span m="396397">much</span>
  <span m="396708">it's</span> <span m="397020">worth.</span> <span m="397488">And</span>
  <span m="397957">you</span> <span m="398425">can</span> <span m="398894">chop</span>
  <span m="399362">gold</span> <span m="399831">up</span> <span m="400300">and--</span>
  <span m="400768">sorry,</span> <span m="401237">divisibility</span> <span m="401705">is</span>
  <span m="402174">different</span> <span m="402642">than</span> <span m="403111">fungibility.</span></p><p><span
  m="403580">So</span> <span m="403944">if</span> <span m="404308">diamonds</span>
  <span m="404672">were</span> <span m="405037">all</span> <span m="405401">identical</span>
  <span m="405765">but</span> <span m="406130">not</span> <span m="406494">divisible,</span>
  <span m="406858">they</span> <span m="407222">could</span> <span m="407587">still</span>
  <span m="407951">maybe</span> <span m="408315">function</span> <span m="408680">as</span>
  <span m="408982">money.</span> <span m="409285">You</span> <span m="409587">would</span>
  <span m="409890">just</span> <span m="410193">need</span> <span m="410495">a</span>
  <span m="410798">lot</span> <span m="411101">of</span> <span m="411403">little</span>
  <span m="411706">diamonds.</span> <span m="412008">But</span> <span m="412311">the</span>
  <span m="412614">fact</span> <span m="412916">that</span> <span m="413219">gold</span>
  <span m="413522">is</span> <span m="413824">also</span> <span m="414127">divisible</span>
  <span m="414430">is</span> <span m="414645">really</span> <span m="414860">is</span>
  <span m="415075">a</span> <span m="415291">bonus.</span> <span m="415506">But</span>
  <span m="415721">the</span> <span m="415937">fungibility</span> <span m="416152">is</span>
  <span m="416367">really</span> <span m="416582">what's</span> <span m="416798">nice</span>
  <span m="417013">about</span> <span m="417228">it,</span> <span m="417444">and</span>
  <span m="417659">what</span> <span m="417874">makes</span> <span m="418090">it</span>
  <span m="418688">sort</span> <span m="419286">of</span> <span m="419885">used</span>
  <span m="420483">as</span> <span m="421081">money.</span></p><p><span m="421680">Currency's</span>
  <span m="422166">fungibility</span> <span m="422653">is</span> <span m="423140">actually--</span>
  <span m="423627">I'm</span> <span m="424114">not</span> <span m="424601">a</span>
  <span m="425088">lawyer,</span> <span m="425575">but</span> <span m="426061">I</span>
  <span m="426548">hang</span> <span m="427035">out</span> <span m="427522">with</span>
  <span m="428009">them.</span> <span m="428496">It's</span> <span m="428983">enforced</span>
  <span m="429470">by</span> <span m="429853">the</span> <span m="430237">law</span>
  <span m="430621">itself.</span> <span m="431005">So</span> <span m="431388">there's</span>
  <span m="431772">an</span> <span m="432156">interesting</span> <span m="432540">case,</span>
  <span m="432923">Crawford</span> <span m="433307">v.</span> <span m="433691">The</span>
  <span m="434075">Royal</span> <span m="434458">Bank,</span> <span m="434842">in</span>
  <span m="435226">Scotland</span> <span m="435610">a</span> <span m="435950">couple</span>
  <span m="436290">hundred</span> <span m="436630">years</span> <span m="436970">ago,</span>
  <span m="437310">where</span> <span m="437650">there</span> <span m="437990">was</span>
  <span m="438330">a</span> <span m="438670">guy.</span></p><p><span m="439010">And</span>
  <span m="439301">he</span> <span m="439593">wrote</span> <span m="439884">his</span>
  <span m="440176">name</span> <span m="440468">on</span> <span m="440759">a</span>
  <span m="441051">20</span> <span m="441342">pound</span> <span m="441634">note.</span>
  <span m="441926">It's</span> <span m="442217">like</span> <span m="442509">Crawford.</span>
  <span m="442800">This</span> <span m="443092">is</span> <span m="443384">his</span>
  <span m="443675">money.</span> <span m="443967">And</span> <span m="444259">I</span>
  <span m="444571">think</span> <span m="444884">he</span> <span m="445196">was</span>
  <span m="445509">trying</span> <span m="445821">to</span> <span m="446134">mail</span>
  <span m="446447">it</span> <span m="446759">someone.</span> <span m="447072">He</span>
  <span m="447384">lost</span> <span m="447697">it.</span></p><p><span m="448010">Years</span>
  <span m="448218">later,</span> <span m="448426">the</span> <span m="448634">note</span>
  <span m="448843">shows</span> <span m="449051">up</span> <span m="449259">at</span>
  <span m="449467">a</span> <span m="449676">bank.</span> <span m="449884">And</span>
  <span m="450092">he's</span> <span m="450301">like,</span> <span m="450509">no,</span>
  <span m="450717">see</span> <span m="450925">that</span> <span m="451134">was</span>
  <span m="451342">my</span> <span m="451550">money.</span></p><p><span m="451759">I</span>
  <span m="452131">lost</span> <span m="452503">it.</span> <span m="452876">And</span>
  <span m="453248">he</span> <span m="453620">demands</span> <span m="453993">the</span>
  <span m="454365">money</span> <span m="454737">back.</span></p><p><span m="455110">I</span>
  <span m="455323">lost</span> <span m="455537">that</span> <span m="455751">money.</span>
  <span m="455965">This</span> <span m="456179">is</span> <span m="456393">my</span>
  <span m="456607">property.</span> <span m="456821">Give</span> <span m="457035">it</span>
  <span m="457249">back.</span> <span m="457463">It's</span> <span m="457677">got</span>
  <span m="457891">my</span> <span m="458105">name</span> <span m="458319">on</span>
  <span m="458533">it.</span> <span m="458747">I</span> <span m="458961">can</span>
  <span m="459175">prove</span> <span m="459389">it.</span></p><p><span m="460449">And</span>
  <span m="460676">then</span> <span m="460904">the</span> <span m="461132">court</span>
  <span m="461360">says</span> <span m="461588">no,</span> <span m="461816">no,</span>
  <span m="462043">no,</span> <span m="462271">that's</span> <span m="462499">not</span>
  <span m="462727">how</span> <span m="462955">money</span> <span m="463183">works.</span>
  <span m="463410">The</span> <span m="463638">bank</span> <span m="463866">has</span>
  <span m="464094">the</span> <span m="464322">money.</span></p><p><span m="464550">You</span>
  <span m="465029">can't</span> <span m="465508">just</span> <span m="465987">write</span>
  <span m="466467">your</span> <span m="466946">name</span> <span m="467425">on</span>
  <span m="467905">money</span> <span m="468384">and</span> <span m="468863">then</span>
  <span m="469342">have</span> <span m="469822">it</span> <span m="470301">be</span>
  <span m="470780">yours.</span></p><p><span m="471260">And</span> <span m="471635">this</span>
  <span m="472010">is</span> <span m="472385">very</span> <span m="472760">different</span>
  <span m="473136">from</span> <span m="473511">property.</span> <span m="473886">So</span>
  <span m="474261">if</span> <span m="474637">you</span> <span m="475012">steal</span>
  <span m="475387">a</span> <span m="475762">bicycle,</span> <span m="476138">and</span>
  <span m="476513">then</span> <span m="476888">you</span> <span m="477263">go</span>
  <span m="477639">go</span> <span m="477946">sell</span> <span m="478253">it</span>
  <span m="478560">on--</span> <span m="478867">sorry,</span> <span m="479174">if</span>
  <span m="479481">someone</span> <span m="479788">steals</span> <span m="480095">a</span>
  <span m="480403">bicycle,</span> <span m="480710">sells</span> <span m="481017">it</span>
  <span m="481324">on</span> <span m="481631">Craigslist,</span> <span m="481938">and</span>
  <span m="482245">you</span> <span m="482552">buy</span> <span m="482860">it,</span>
  <span m="483093">and</span> <span m="483327">you</span> <span m="483560">didn't</span>
  <span m="483794">know,</span> <span m="484027">it</span> <span m="484261">was</span>
  <span m="484494">just,</span> <span m="484728">whatever,</span> <span m="484961">some</span>
  <span m="485195">guy's</span> <span m="485428">selling</span> <span m="485662">a</span>
  <span m="485895">bike</span> <span m="486129">on</span> <span m="486362">Craigslist.</span>
  <span m="486596">The</span> <span m="486830">police</span> <span m="487030">show</span>
  <span m="487230">up,</span> <span m="487430">and</span> <span m="487630">say,</span>
  <span m="487830">hey,</span> <span m="488030">that</span> <span m="488230">bicycle</span>
  <span m="488430">was</span> <span m="488630">stolen.</span> <span m="488830">We're</span>
  <span m="489030">taking</span> <span m="489230">it</span> <span m="489430">back.</span></p><p><span
  m="489630">And</span> <span m="489892">you're</span> <span m="490155">like,</span>
  <span m="490418">well,</span> <span m="490681">I</span> <span m="490943">didn't</span>
  <span m="491206">know.</span> <span m="491469">I</span> <span m="491732">just</span>
  <span m="491995">bought</span> <span m="492257">it</span> <span m="492520">on</span>
  <span m="492783">Craigslist.</span> <span m="493046">I</span> <span m="493308">paid</span>
  <span m="493571">a</span> <span m="493834">couple</span> <span m="494097">hundred</span>
  <span m="494360">bucks.</span> <span m="494601">Police</span> <span m="494842">are</span>
  <span m="495084">like,</span> <span m="495325">sorry,</span> <span m="495567">you're</span>
  <span m="495808">not</span> <span m="496049">in</span> <span m="496291">trouble.</span>
  <span m="496532">We're</span> <span m="496774">not</span> <span m="497015">going</span>
  <span m="497256">to</span> <span m="497498">charge</span> <span m="497739">you</span>
  <span m="497981">with</span> <span m="498314">a</span> <span m="498647">crime.</span></p><p><span
  m="498981">But</span> <span m="499269">these</span> <span m="499558">are</span>
  <span m="499847">stolen</span> <span m="500135">goods.</span> <span m="500424">We're</span>
  <span m="500713">taking</span> <span m="501001">them</span> <span m="501290">back,</span>
  <span m="501579">giving</span> <span m="501867">it</span> <span m="502156">to</span>
  <span m="502445">the</span> <span m="502733">rightful</span> <span m="503022">owner.</span>
  <span m="503311">And</span> <span m="503600">that's</span> <span m="503885">how</span>
  <span m="504170">the</span> <span m="504455">law</span> <span m="504740">works.</span>
  <span m="505025">You</span> <span m="505310">can</span> <span m="505595">try</span>
  <span m="505880">to</span> <span m="506165">complain</span> <span m="506450">about</span>
  <span m="506735">it,</span> <span m="507020">but</span> <span m="507305">they're</span>
  <span m="507590">taking</span> <span m="507875">it.</span></p><p><span m="508160">Money</span>
  <span m="508465">is</span> <span m="508770">different.</span> <span m="509075">If</span>
  <span m="509380">you're</span> <span m="509686">running</span> <span m="509991">a</span>
  <span m="510296">pizza</span> <span m="510601">store,</span> <span m="510907">someone</span>
  <span m="511212">comes</span> <span m="511517">in,</span> <span m="511822">gives</span>
  <span m="512128">you</span> <span m="512433">a</span> <span m="512738">20,</span>
  <span m="513043">and</span> <span m="513349">buys</span> <span m="513647">a</span>
  <span m="513945">pizza,</span> <span m="514243">and</span> <span m="514541">then</span>
  <span m="514839">presumably</span> <span m="515138">eats</span> <span m="515436">it</span>
  <span m="515734">or</span> <span m="516032">whatever,</span> <span m="516330">and</span>
  <span m="516629">then</span> <span m="516927">a</span> <span m="517225">couple</span>
  <span m="517523">hours</span> <span m="517821">later</span> <span m="518120">the</span>
  <span m="518430">police</span> <span m="518741">come</span> <span m="519051">in</span>
  <span m="519362">and</span> <span m="519672">say,</span> <span m="519983">hey,</span>
  <span m="520293">that</span> <span m="520604">guy</span> <span m="520914">stole</span>
  <span m="521225">that</span> <span m="521535">$20</span> <span m="521846">bill.</span>
  <span m="522156">And</span> <span m="522467">we're</span> <span m="522777">taking</span>
  <span m="523088">it</span> <span m="523398">back,</span> <span m="523709">and</span>
  <span m="523926">giving</span> <span m="524143">it</span> <span m="524360">to</span>
  <span m="524578">its</span> <span m="524795">rightful</span> <span m="525012">owner.</span></p><p><span
  m="525230">As</span> <span m="525518">the</span> <span m="525806">shopkeeper,</span>
  <span m="526094">you're</span> <span m="526382">like,</span> <span m="526670">I</span>
  <span m="526958">don't</span> <span m="527246">even</span> <span m="527535">know</span>
  <span m="527823">which</span> <span m="528111">$20</span> <span m="528399">bill.</span>
  <span m="528687">Even</span> <span m="528975">though</span> <span m="529263">there</span>
  <span m="529551">are</span> <span m="529840">serial</span> <span m="530088">numbers,</span>
  <span m="530337">and</span> <span m="530586">the</span> <span m="530835">police</span>
  <span m="531083">could</span> <span m="531332">say,</span> <span m="531581">it</span>
  <span m="531830">was</span> <span m="532078">this</span> <span m="532327">$20</span>
  <span m="532576">bill.</span> <span m="532825">We're</span> <span m="533073">taking</span>
  <span m="533322">it</span> <span m="533571">back,</span> <span m="533820">or</span>
  <span m="534415">returning</span> <span m="535010">it</span> <span m="535606">to</span>
  <span m="536201">the</span> <span m="536796">person</span> <span m="537392">he</span>
  <span m="537987">stole</span> <span m="538582">it</span> <span m="539178">from,</span>
  <span m="539773">legally</span> <span m="540368">they</span> <span m="540964">can't</span>
  <span m="541559">do</span> <span m="542154">that.</span></p><p><span m="542750">So</span>
  <span m="543065">this</span> <span m="543380">is</span> <span m="543696">from</span>
  <span m="544011">talking</span> <span m="544326">to</span> <span m="544642">lawyer</span>
  <span m="544957">people.</span> <span m="545272">So</span> <span m="545588">money's</span>
  <span m="545903">different.</span> <span m="546218">Money</span> <span m="546534">is</span>
  <span m="546849">not</span> <span m="547164">property,</span> <span m="547480">in</span>
  <span m="547872">the</span> <span m="548265">same</span> <span m="548657">sense.</span>
  <span m="549050">And</span> <span m="549442">the</span> <span m="549835">fungibility</span>
  <span m="550227">is</span> <span m="550620">enforced</span> <span m="551012">by</span>
  <span m="551405">the</span> <span m="551797">state.</span></p><p><span m="552190">And</span>
  <span m="552765">the</span> <span m="553341">divisibility</span> <span m="553916">and</span>
  <span m="554492">fungibility</span> <span m="555068">are</span> <span m="555643">enforced</span>
  <span m="556219">by</span> <span m="556795">the</span> <span m="557370">banks.</span>
  <span m="557946">The</span> <span m="558521">US</span> <span m="559097">dollar</span>
  <span m="559673">isn't</span> <span m="560248">worth</span> <span m="560824">anything.</span></p><p><span
  m="561400">The</span> <span m="561700">government</span> <span m="562001">and</span>
  <span m="562302">the</span> <span m="562603">banks</span> <span m="562903">don't</span>
  <span m="563204">have</span> <span m="563505">to</span> <span m="563806">give</span>
  <span m="564106">you</span> <span m="564407">anything</span> <span m="564708">for</span>
  <span m="565009">$1.</span></p><p><span m="565310">They</span> <span m="565591">used</span>
  <span m="565872">to</span> <span m="566153">sort</span> <span m="566434">of</span>
  <span m="566715">have</span> <span m="566997">this</span> <span m="567278">agreement,</span>
  <span m="567559">where,</span> <span m="567840">OK</span> <span m="568121">you</span>
  <span m="568402">give</span> <span m="568684">us</span> <span m="568965">$35.</span>
  <span m="569246">And</span> <span m="569527">we'll</span> <span m="569808">give</span>
  <span m="570090">you</span> <span m="570374">an</span> <span m="570659">ounce</span>
  <span m="570944">of</span> <span m="571228">gold.</span> <span m="571513">That</span>
  <span m="571798">agreement</span> <span m="572083">is</span> <span m="572367">longer</span>
  <span m="572652">is</span> <span m="572937">in</span> <span m="573222">place.</span>
  <span m="573506">But</span> <span m="573791">they</span> <span m="574076">do</span>
  <span m="574361">have</span> <span m="574645">to</span> <span m="574930">give</span>
  <span m="575215">you</span> <span m="575500">a</span> <span m="576040">change.</span></p><p><span
  m="576580">So</span> <span m="576825">they</span> <span m="577070">do</span> <span
  m="577315">have</span> <span m="577560">a</span> <span m="577805">duty</span> <span
  m="578050">where</span> <span m="578295">if</span> <span m="578540">you</span> <span
  m="578785">have</span> <span m="579030">a</span> <span m="579275">bunch</span> <span
  m="579520">of</span> <span m="579765">old,</span> <span m="580010">beatup</span>
  <span m="580255">$20</span> <span m="580500">bills,</span> <span m="580745">the</span>
  <span m="580990">bank</span> <span m="581235">sort</span> <span m="581480">of</span>
  <span m="581691">does</span> <span m="581902">have</span> <span m="582113">to</span>
  <span m="582324">honor</span> <span m="582535">those</span> <span m="582746">and</span>
  <span m="582957">give</span> <span m="583168">you</span> <span m="583379">new</span>
  <span m="583590">$20</span> <span m="583801">bills.</span> <span m="584012">And</span>
  <span m="584223">that's</span> <span m="584434">one</span> <span m="584645">of</span>
  <span m="584856">the</span> <span m="585067">things</span> <span m="585278">that</span>
  <span m="585490">the</span> <span m="585728">Bureau</span> <span m="585966">of</span>
  <span m="586204">Engraving</span> <span m="586442">and</span> <span m="586680">Printing,</span>
  <span m="586918">and</span> <span m="587156">the</span> <span m="587395">Fed,</span>
  <span m="587633">they</span> <span m="587871">all</span> <span m="588109">have</span>
  <span m="588347">this</span> <span m="588585">system.</span> <span m="588823">So</span>
  <span m="589061">they</span> <span m="589300">maintain</span> <span m="589925">the</span>
  <span m="590550">currency,</span> <span m="591175">in</span> <span m="591800">that</span>
  <span m="592425">sense.</span></p><p><span m="593050">So</span> <span m="593280">there's</span>
  <span m="593510">all</span> <span m="593740">these</span> <span m="593970">things</span>
  <span m="594200">that</span> <span m="594430">like</span> <span m="594660">you</span>
  <span m="594890">don't</span> <span m="595120">really</span> <span m="595350">think</span>
  <span m="595580">about</span> <span m="595810">in</span> <span m="596040">that</span>
  <span m="596270">how</span> <span m="596500">money</span> <span m="596730">operates.</span>
  <span m="597092">But</span> <span m="597454">fungibility,</span> <span m="597816">divisibility,</span>
  <span m="598178">those</span> <span m="598540">are</span> <span m="598902">really</span>
  <span m="599265">important.</span> <span m="599627">And</span> <span m="599989">most</span>
  <span m="600351">of</span> <span m="600713">it</span> <span m="601075">is</span>
  <span m="601437">enforced</span> <span m="601800">by</span> <span m="602312">the</span>
  <span m="602825">legal</span> <span m="603337">system.</span></p><p><span m="603850">Bitcoin</span>
  <span m="604233">does</span> <span m="604616">not</span> <span m="604999">have</span>
  <span m="605382">these</span> <span m="605765">legal</span> <span m="606148">protections.</span>
  <span m="606531">If</span> <span m="606915">want</span> <span m="607298">bitcoin</span>
  <span m="607681">to</span> <span m="608064">work,</span> <span m="608447">even</span>
  <span m="608830">where</span> <span m="609213">it's</span> <span m="609596">not</span>
  <span m="609980">legally</span> <span m="610420">recognized</span> <span m="610861">as</span>
  <span m="611301">being</span> <span m="611742">money,</span> <span m="612183">and</span>
  <span m="612623">our</span> <span m="613064">goal</span> <span m="613505">is</span>
  <span m="613945">to</span> <span m="614386">make</span> <span m="614827">it</span>
  <span m="615267">like</span> <span m="615708">money.</span> <span m="616149">So</span>
  <span m="616589">if</span> <span m="617030">they're</span> <span m="617471">stolen</span>
  <span m="617812">bitcoins,</span> <span m="618154">and</span> <span m="618496">you</span>
  <span m="618838">can</span> <span m="619180">trace</span> <span m="619522">them,</span>
  <span m="619864">the</span> <span m="620206">law</span> <span m="620548">enforcement</span>
  <span m="620890">can</span> <span m="621232">say,</span> <span m="621574">no,</span>
  <span m="621916">those</span> <span m="622258">bitcoins</span> <span m="622600">are</span>
  <span m="623208">stolen.</span> <span m="623816">We're</span> <span m="624424">recovering</span>
  <span m="625032">them.</span></p><p><span m="625640">So</span> <span m="626116">it's</span>
  <span m="626592">not</span> <span m="627069">treated</span> <span m="627545">as</span>
  <span m="628022">a</span> <span m="628498">currency.</span> <span m="628975">It's</span>
  <span m="629451">also</span> <span m="629928">not</span> <span m="630404">controlled</span>
  <span m="630881">as</span> <span m="631357">fungible.</span> <span m="631834">So</span>
  <span m="632310">in</span> <span m="632787">the</span> <span m="633263">absence</span>
  <span m="633740">of</span> <span m="634071">these</span> <span m="634402">sort</span>
  <span m="634734">of</span> <span m="635065">protections</span> <span m="635396">from</span>
  <span m="635728">the</span> <span m="636059">legal</span> <span m="636390">system,</span>
  <span m="636722">the</span> <span m="637053">software</span> <span m="637384">needs</span>
  <span m="637716">to</span> <span m="638047">help</span> <span m="638378">enforce</span>
  <span m="638710">the</span> <span m="639075">fungibility</span> <span m="639440">and</span>
  <span m="639806">divisibility</span> <span m="640171">of</span> <span m="640536">these</span>
  <span m="640902">things.</span> <span m="641267">So</span> <span m="641632">you</span>
  <span m="641998">can</span> <span m="642363">sort</span> <span m="642728">of</span>
  <span m="643094">treat</span> <span m="643459">the</span> <span m="643824">bitcoin</span>
  <span m="644190">software</span> <span m="644521">and</span> <span m="644853">ruleset</span>
  <span m="645184">as</span> <span m="645516">sort</span> <span m="645847">of</span>
  <span m="646179">a</span> <span m="646510">legal--</span> <span m="646842">it's</span>
  <span m="647173">not</span> <span m="647505">a</span> <span m="647836">legal</span>
  <span m="648168">system.</span></p><p><span m="648500">But</span> <span m="648803">it's</span>
  <span m="649107">a</span> <span m="649411">system</span> <span m="649715">of</span>
  <span m="650018">rules</span> <span m="650322">that</span> <span m="650626">governs</span>
  <span m="650930">how</span> <span m="651233">the</span> <span m="651537">bitcoin</span>
  <span m="651841">transactions</span> <span m="652145">work.</span> <span m="652448">And</span>
  <span m="652752">so</span> <span m="653056">the</span> <span m="653360">fungibility</span>
  <span m="653693">has</span> <span m="654027">got</span> <span m="654360">to</span>
  <span m="654694">be</span> <span m="655027">in</span> <span m="655361">the</span>
  <span m="655694">system.</span> <span m="656028">Right</span> <span m="656361">So</span>
  <span m="656695">gold,</span> <span m="657028">for</span> <span m="657362">example,</span>
  <span m="657695">they</span> <span m="658029">don't</span> <span m="658362">have--</span>
  <span m="658696">I</span> <span m="659030">don't</span> <span m="659237">want</span>
  <span m="659445">to</span> <span m="659652">say</span> <span m="659860">they</span>
  <span m="660068">don't</span> <span m="660275">have</span> <span m="660483">rules</span>
  <span m="660691">about</span> <span m="660898">gold.</span> <span m="661106">There's</span>
  <span m="661314">probably</span> <span m="661521">all</span> <span m="661729">sorts</span>
  <span m="661937">of</span> <span m="662144">old</span> <span m="662352">laws</span>
  <span m="662560">about</span> <span m="663070">gold.</span></p><p><span m="663580">But</span>
  <span m="663964">you</span> <span m="664348">don't</span> <span m="664732">really</span>
  <span m="665116">need</span> <span m="665500">a</span> <span m="665884">law</span>
  <span m="666268">enforcing</span> <span m="666652">the</span> <span m="667037">fungibility</span>
  <span m="667421">of</span> <span m="667805">gold,</span> <span m="668189">in</span>
  <span m="668573">that</span> <span m="668957">you</span> <span m="669341">can</span>
  <span m="669725">sort</span> <span m="670110">of</span> <span m="670393">melt</span>
  <span m="670677">it</span> <span m="670960">down,</span> <span m="671244">and</span>
  <span m="671527">it's</span> <span m="671811">untraceable.</span> <span m="672094">If</span>
  <span m="672378">you</span> <span m="672661">have</span> <span m="672945">this</span>
  <span m="673228">old</span> <span m="673512">gold</span> <span m="673795">coin</span>
  <span m="674079">from</span> <span m="674362">this</span> <span m="674646">empire,</span>
  <span m="674930">and</span> <span m="675187">this</span> <span m="675445">other</span>
  <span m="675703">gold</span> <span m="675961">coin</span> <span m="676219">from</span>
  <span m="676477">this</span> <span m="676735">empire,</span> <span m="676993">you</span>
  <span m="677251">melt</span> <span m="677508">the</span> <span m="677766">gold,</span>
  <span m="678024">you</span> <span m="678282">put</span> <span m="678540">it</span>
  <span m="678798">into</span> <span m="679056">a</span> <span m="679314">new</span>
  <span m="679572">coin,</span> <span m="679830">no</span> <span m="680309">one</span>
  <span m="680788">can</span> <span m="681267">tell.</span> <span m="681746">So,</span>
  <span m="682226">similarly,</span> <span m="682705">bitcoin</span> <span m="683184">needs</span>
  <span m="683663">to</span> <span m="684143">enforce</span> <span m="684622">fungibility</span>
  <span m="685101">that</span> <span m="685580">way.</span></p><p><span m="686060">OK,</span>
  <span m="686410">so</span> <span m="686761">any</span> <span m="687111">questions</span>
  <span m="687462">so</span> <span m="687813">far</span> <span m="688163">about</span>
  <span m="688514">these</span> <span m="688865">definitions</span> <span m="689215">or</span>
  <span m="689566">objections?</span> <span m="689916">I</span> <span m="690267">don't</span>
  <span m="690618">think</span> <span m="690968">bitcoin</span> <span m="691319">should</span>
  <span m="691670">be</span> <span m="692275">fungible.</span></p><p><span m="692880">AUDIENCE:</span>
  <span m="693620">So</span> <span m="694360">bitcoin</span> <span m="695100">is</span>
  <span m="695840">more</span> <span m="696580">like</span> <span m="697320">gold</span>
  <span m="698060">than</span> <span m="698800">diamonds.</span> <span m="699540">But,</span>
  <span m="700280">in</span> <span m="701020">a</span> <span m="701760">sense,</span>
  <span m="702500">right</span> <span m="703240">after</span> <span m="703980">your</span>
  <span m="704720">transaction</span> <span m="705104">happens,</span> <span m="705488">the</span>
  <span m="705872">probability</span> <span m="706257">that</span> <span m="706641">it--</span>
  <span m="707025">say</span> <span m="707410">it's</span> <span m="707794">only</span>
  <span m="708178">one</span> <span m="708562">block</span> <span m="708947">deep.</span>
  <span m="709331">I</span> <span m="709715">don't</span> <span m="710100">think</span>
  <span m="710511">it's</span> <span m="710923">actually</span> <span m="711335">treated</span>
  <span m="711746">this</span> <span m="712158">way.</span></p><p><span m="712570">But</span>
  <span m="713180">someone</span> <span m="713790">could</span> <span m="714400">potentially,</span>
  <span m="715010">oh,</span> <span m="715621">I'll</span> <span m="716231">just</span>
  <span m="716841">consider</span> <span m="717451">that</span> <span m="718061">90%</span>
  <span m="718672">of</span> <span m="719282">one</span> <span m="719892">bitcoin,</span>
  <span m="720502">because</span> <span m="721113">the</span> <span m="721472">probability</span>
  <span m="721831">or</span> <span m="722190">whatever--</span> <span m="722550">TADGE</span>
  <span m="722877">DRYJA:</span> <span m="723205">They're</span> <span m="723533">not</span>
  <span m="723860">valued</span> <span m="724188">the</span> <span m="724516">same,</span>
  <span m="724843">because</span> <span m="725171">they</span> <span m="725499">haven't</span>
  <span m="725826">been</span> <span m="726154">fully</span> <span m="726482">confirmed.</span></p><p><span
  m="726810">Yeah,</span> <span m="727117">that's</span> <span m="727424">an</span>
  <span m="727731">interesting</span> <span m="728038">way</span> <span m="728345">to</span>
  <span m="728652">look</span> <span m="728959">at</span> <span m="729266">it.</span>
  <span m="729573">I'm</span> <span m="729880">not</span> <span m="730187">talking</span>
  <span m="730494">about</span> <span m="730801">sort</span> <span m="731108">of</span>
  <span m="731415">the</span> <span m="731722">time-based</span> <span m="732030">things</span>
  <span m="732323">here,</span> <span m="732617">because</span> <span m="732910">I</span>
  <span m="733204">guess</span> <span m="733497">in</span> <span m="733791">many</span>
  <span m="734084">cases</span> <span m="734378">you</span> <span m="734671">say,</span>
  <span m="734965">OK,</span> <span m="735258">I'm</span> <span m="735552">going</span>
  <span m="735845">to</span> <span m="736139">wait</span> <span m="736432">a</span>
  <span m="736726">day.</span></p><p><span m="737020">If</span> <span m="737293">it's</span>
  <span m="737566">got</span> <span m="737840">100</span> <span m="738113">confirmations,</span>
  <span m="738387">it's</span> <span m="738660">good.</span> <span m="738933">I'll</span>
  <span m="739207">consider</span> <span m="739480">it</span> <span m="739754">full</span>
  <span m="740027">value.</span> <span m="740300">But,</span> <span m="740574">yeah,</span>
  <span m="740847">there</span> <span m="741121">could</span> <span m="741380">be</span>
  <span m="741640">things</span> <span m="741900">where</span> <span m="742160">you</span>
  <span m="742420">look</span> <span m="742680">at</span> <span m="742940">the</span>
  <span m="743200">probability</span> <span m="743460">of</span> <span m="743720">a</span>
  <span m="743980">double</span> <span m="744240">spend,</span> <span m="744500">and</span>
  <span m="744760">then</span> <span m="745020">sort</span> <span m="745280">of</span>
  <span m="745540">assign</span> <span m="745800">value</span> <span m="746189">to</span>
  <span m="746578">it,</span> <span m="746968">increasing</span> <span m="747357">as</span>
  <span m="747746">time</span> <span m="748136">passes</span> <span m="748525">or</span>
  <span m="748915">something.</span> <span m="749304">That's</span> <span m="749693">sort</span>
  <span m="750083">of</span> <span m="750472">a</span> <span m="750861">unique</span>
  <span m="751251">thing</span> <span m="751640">to</span> <span m="752030">bitcoin,</span>
  <span m="752396">where</span> <span m="752763">the</span> <span m="753129">sort</span>
  <span m="753496">of</span> <span m="753863">finality</span> <span m="754229">of</span>
  <span m="754596">the</span> <span m="754962">transfer</span> <span m="755329">increases</span>
  <span m="755696">with</span> <span m="756062">time,</span> <span m="756429">which</span>
  <span m="756795">is</span> <span m="757162">not</span> <span m="757529">really</span>
  <span m="757779">the</span> <span m="758030">case</span> <span m="758281">with</span>
  <span m="758532">gold</span> <span m="758782">or</span> <span m="759033">dollars,</span>
  <span m="759284">where</span> <span m="759535">you're</span> <span m="759786">like,</span>
  <span m="760036">oh,</span> <span m="760287">I</span> <span m="760538">got</span>
  <span m="760789">it.</span></p><p><span m="761040">The</span> <span m="761334">fact</span>
  <span m="761629">that</span> <span m="761924">I've</span> <span m="762218">had</span>
  <span m="762513">it</span> <span m="762808">for</span> <span m="763102">one</span>
  <span m="763397">minute</span> <span m="763692">or</span> <span m="763987">10</span>
  <span m="764281">minutes</span> <span m="764576">doesn't</span> <span m="764871">really</span>
  <span m="765165">change</span> <span m="765460">that</span> <span m="765755">I've</span>
  <span m="766050">got</span> <span m="766501">it.</span> <span m="766953">So</span>
  <span m="767404">that's</span> <span m="767856">an</span> <span m="768307">interesting</span>
  <span m="768759">point.</span> <span m="769210">I'm</span> <span m="769662">not</span>
  <span m="770113">really</span> <span m="770565">addressing</span> <span m="771016">it</span>
  <span m="771468">here.</span></p><p><span m="771920">In</span> <span m="772197">this</span>
  <span m="772475">conversation,</span> <span m="772752">just</span> <span m="773030">assume</span>
  <span m="773307">you</span> <span m="773585">wait</span> <span m="773862">a</span>
  <span m="774140">day.</span> <span m="774417">And</span> <span m="774695">then</span>
  <span m="774972">all</span> <span m="775250">the</span> <span m="775527">probability</span>
  <span m="775805">of</span> <span m="776082">it</span> <span m="776360">going</span>
  <span m="776755">back</span> <span m="777151">is</span> <span m="777546">sort</span>
  <span m="777942">of</span> <span m="778338">negligible.</span> <span m="778733">But</span>
  <span m="779129">it's</span> <span m="779525">more</span> <span m="779920">the</span>
  <span m="780316">fungibility</span> <span m="780711">in</span> <span m="781107">that</span>
  <span m="781503">you</span> <span m="781898">can</span> <span m="782294">trace</span>
  <span m="782690">where</span> <span m="783254">it</span> <span m="783818">came</span>
  <span m="784382">from,</span> <span m="784947">and</span> <span m="785511">so</span>
  <span m="786075">assign</span> <span m="786640">values</span> <span m="787204">to</span>
  <span m="787768">different</span> <span m="788332">coins</span> <span m="788897">based</span>
  <span m="789461">on</span> <span m="790025">that.</span></p><p><span m="790590">So</span>
  <span m="790867">there's</span> <span m="791145">a</span> <span m="791422">real</span>
  <span m="791700">world</span> <span m="791978">example</span> <span m="792255">of</span>
  <span m="792533">this.</span> <span m="792811">I</span> <span m="793088">don't</span>
  <span m="793366">want</span> <span m="793644">to</span> <span m="793921">name</span>
  <span m="794199">specific</span> <span m="794477">names.</span> <span m="794754">But</span>
  <span m="795032">customer</span> <span m="795310">buys</span> <span m="795562">some</span>
  <span m="795815">coins.</span> <span m="796068">You</span> <span m="796321">go</span>
  <span m="796574">to</span> <span m="796827">exchange.</span> <span m="797080">You</span>
  <span m="797332">send</span> <span m="797585">them</span> <span m="797838">a</span>
  <span m="798091">couple</span> <span m="798344">hundred</span> <span m="798597">bucks.</span></p><p><span
  m="798850">You</span> <span m="799120">say,</span> <span m="799390">I</span> <span
  m="799660">want</span> <span m="799930">to</span> <span m="800200">buy</span> <span
  m="800470">some</span> <span m="800740">bitcoins.</span> <span m="801010">And</span>
  <span m="801280">the</span> <span m="801550">customer</span> <span m="801820">buys</span>
  <span m="802090">the</span> <span m="802360">bitcoins,</span> <span m="802630">and</span>
  <span m="802900">then</span> <span m="803170">transfers</span> <span m="803440">the</span>
  <span m="803751">coins</span> <span m="804062">to</span> <span m="804373">a</span>
  <span m="804684">betting</span> <span m="804995">shop,</span> <span m="805306">a</span>
  <span m="805617">betting</span> <span m="805928">company</span> <span m="806239">in</span>
  <span m="806550">the</span> <span m="806861">UK,</span> <span m="807172">and</span>
  <span m="807483">bets</span> <span m="807794">on</span> <span m="808105">a</span>
  <span m="808416">soccer</span> <span m="808727">game,</span> <span m="809038">for</span>
  <span m="809350">example.</span> <span m="809745">And</span> <span m="810140">he</span>
  <span m="810535">wins.</span></p><p><span m="810930">Great,</span> <span m="811281">so</span>
  <span m="811633">he</span> <span m="811985">bought</span> <span m="812336">a</span>
  <span m="812688">coin,</span> <span m="813040">sent</span> <span m="813391">it</span>
  <span m="813743">over</span> <span m="814095">to</span> <span m="814446">this</span>
  <span m="814798">UK</span> <span m="815150">gambling</span> <span m="815501">company,</span>
  <span m="815853">bet</span> <span m="816205">on</span> <span m="816556">a</span>
  <span m="816908">soccer</span> <span m="817260">game,</span> <span m="817616">or</span>
  <span m="817972">football</span> <span m="818329">I</span> <span m="818685">guess</span>
  <span m="819042">they</span> <span m="819398">call</span> <span m="819755">it,</span>
  <span m="820111">wins.</span> <span m="820468">Now,</span> <span m="820824">he</span>
  <span m="821181">has</span> <span m="821537">two</span> <span m="821894">coins.</span>
  <span m="822250">Transfers</span> <span m="822607">those</span> <span m="822963">two</span>
  <span m="823320">coins</span> <span m="823831">back</span> <span m="824343">to</span>
  <span m="824854">the</span> <span m="825366">US</span> <span m="825877">exchange.</span></p><p><span
  m="826389">And</span> <span m="826652">he</span> <span m="826915">wants</span> <span
  m="827179">to</span> <span m="827442">sell</span> <span m="827705">them.</span>
  <span m="827969">Before</span> <span m="828232">he</span> <span m="828496">can</span>
  <span m="828759">click</span> <span m="829022">sell,</span> <span m="829286">his</span>
  <span m="829549">account</span> <span m="829813">is</span> <span m="830076">closed.</span>
  <span m="830339">And</span> <span m="830603">the</span> <span m="830866">exchange</span>
  <span m="831130">website</span> <span m="831429">says,</span> <span m="831728">no,</span>
  <span m="832027">you</span> <span m="832326">violated</span> <span m="832625">our</span>
  <span m="832924">terms</span> <span m="833224">of</span> <span m="833523">service.</span>
  <span m="833822">We're</span> <span m="834121">closing</span> <span m="834420">your</span>
  <span m="834719">account.</span></p><p><span m="835019">Take</span> <span m="835505">your</span>
  <span m="835992">bitcoins.</span> <span m="836479">We've</span> <span m="836965">sent</span>
  <span m="837452">all</span> <span m="837939">your</span> <span m="838426">dollars</span>
  <span m="838912">back</span> <span m="839399">to</span> <span m="839886">your</span>
  <span m="840373">bank.</span> <span m="840859">Withdraw</span> <span m="841346">your</span>
  <span m="841833">bitcoins.</span></p><p><span m="842320">We're</span> <span m="843520">out.</span></p><p><span
  m="844720">This</span> <span m="845341">happens.</span> <span m="845962">So</span>
  <span m="846583">whether</span> <span m="847205">you</span> <span m="847826">agree</span>
  <span m="848447">with</span> <span m="849068">gambling</span> <span m="849690">being</span>
  <span m="850311">legal--</span> <span m="850932">so</span> <span m="851553">in</span>
  <span m="852175">the</span> <span m="852796">UK,</span> <span m="853417">however,</span>
  <span m="854038">there's</span> <span m="854660">no</span> <span m="854959">law</span>
  <span m="855258">violated.</span> <span m="855558">And</span> <span m="855857">as</span>
  <span m="856157">a</span> <span m="856456">United</span> <span m="856756">States--</span>
  <span m="857055">so</span> <span m="857355">this</span> <span m="857654">is</span>
  <span m="857953">sort</span> <span m="858253">of</span> <span m="858552">the</span>
  <span m="858852">gray</span> <span m="859151">area.</span> <span m="859451">I'm</span>
  <span m="859750">pretty</span> <span m="860050">sure</span> <span m="860358">that</span>
  <span m="860666">if</span> <span m="860974">I'm</span> <span m="861282">a</span>
  <span m="861590">US</span> <span m="861898">citizen,</span> <span m="862206">I</span>
  <span m="862515">take</span> <span m="862823">a</span> <span m="863131">plane</span>
  <span m="863439">over</span> <span m="863747">to</span> <span m="864055">London,</span>
  <span m="864363">I</span> <span m="864672">go</span> <span m="864980">to</span>
  <span m="865288">a--</span> <span m="865596">I</span> <span m="865904">don't</span>
  <span m="866212">know</span> <span m="866520">the</span> <span m="866829">lingo,</span>
  <span m="867288">punters</span> <span m="867747">shop,</span> <span m="868207">betting</span>
  <span m="868666">shop?</span> <span m="869125">And</span> <span m="869585">then</span>
  <span m="870044">I</span> <span m="870503">bet</span> <span m="870963">on</span>
  <span m="871422">something,</span> <span m="871881">and</span> <span m="872341">I</span>
  <span m="872800">win.</span></p><p><span m="873260">Well,</span> <span m="873582">I'm</span>
  <span m="873905">pretty</span> <span m="874228">sure</span> <span m="874551">I</span>
  <span m="874873">have</span> <span m="875196">to</span> <span m="875519">pay</span>
  <span m="875842">capital</span> <span m="876165">gains</span> <span m="876487">on</span>
  <span m="876810">those</span> <span m="877133">winnings</span> <span m="877456">to</span>
  <span m="877778">the</span> <span m="878101">US,</span> <span m="878424">IRS.</span>
  <span m="878747">But</span> <span m="879070">I</span> <span m="879400">haven't</span>
  <span m="879731">broken</span> <span m="880061">a</span> <span m="880392">law,</span>
  <span m="880722">because</span> <span m="881053">I'm</span> <span m="881383">not</span>
  <span m="881714">in</span> <span m="882044">the</span> <span m="882375">US</span>
  <span m="882705">when</span> <span m="883036">I'm</span> <span m="883366">doing</span>
  <span m="883697">this</span> <span m="884027">thing.</span> <span m="884358">So,</span>
  <span m="884688">similarly,</span> <span m="885019">if</span> <span m="885280">casino</span>
  <span m="885542">gambling</span> <span m="885804">is</span> <span m="886065">illegal</span>
  <span m="886327">in</span> <span m="886589">Massachusetts,</span> <span m="886851">sort</span>
  <span m="887112">of,</span> <span m="887374">I</span> <span m="887636">can</span>
  <span m="887897">go</span> <span m="888159">to</span> <span m="888421">Las</span>
  <span m="888683">Vegas.</span> <span m="888944">I</span> <span m="889206">can</span>
  <span m="889468">gamble.</span></p><p><span m="889730">And</span> <span m="890177">I</span>
  <span m="890624">can</span> <span m="891071">come</span> <span m="891518">back</span>
  <span m="891965">to</span> <span m="892412">Massachusetts,</span> <span m="892859">and</span>
  <span m="893306">it's</span> <span m="893753">OK.</span></p><p><span m="894200">So</span>
  <span m="894459">this</span> <span m="894718">is</span> <span m="894978">probably</span>
  <span m="895237">a</span> <span m="895497">gray</span> <span m="895756">area.</span>
  <span m="896015">I</span> <span m="896275">don't</span> <span m="896534">know</span>
  <span m="896794">if</span> <span m="897053">there's</span> <span m="897312">actual</span>
  <span m="897572">court</span> <span m="897831">cases</span> <span m="898091">about</span>
  <span m="898350">this,</span> <span m="898610">where</span> <span m="898902">you're</span>
  <span m="899195">still</span> <span m="899488">sitting</span> <span m="899781">in</span>
  <span m="900074">Massachusetts</span> <span m="900367">at</span> <span m="900660">your</span>
  <span m="900952">computer.</span> <span m="901245">But</span> <span m="901538">you've</span>
  <span m="901831">sent</span> <span m="902124">your</span> <span m="902417">money</span>
  <span m="902710">to</span> <span m="903158">the</span> <span m="903607">United</span>
  <span m="904056">Kingdom.</span> <span m="904505">I</span> <span m="904953">don't</span>
  <span m="905402">know.</span> <span m="905851">I</span> <span m="906300">don't</span>
  <span m="906748">know</span> <span m="907197">of</span> <span m="907646">anyone</span>
  <span m="908095">who's</span> <span m="908543">gotten</span> <span m="908992">in</span>
  <span m="909441">trouble</span> <span m="909890">for</span> <span m="910339">this.</span></p><p><span
  m="911339">I</span> <span m="911596">don't</span> <span m="911854">know</span> <span
  m="912112">if</span> <span m="912369">there's</span> <span m="912627">been</span>
  <span m="912885">prosecution</span> <span m="913142">against</span> <span m="913400">UK</span>
  <span m="913658">betting</span> <span m="913916">shops</span> <span m="914173">for</span>
  <span m="914431">this</span> <span m="914689">kind</span> <span m="914946">of</span>
  <span m="915204">thing.</span> <span m="915462">But</span> <span m="915720">this</span>
  <span m="916216">happens.</span> <span m="916712">A</span> <span m="917209">lot</span>
  <span m="917705">of</span> <span m="918201">companies</span> <span m="918698">run</span>
  <span m="919194">betting</span> <span m="919690">shops</span> <span m="920187">like</span>
  <span m="920683">this.</span></p><p><span m="921180">But</span> <span m="921392">I</span>
  <span m="921605">have</span> <span m="921818">seen</span> <span m="922031">that</span>
  <span m="922244">US</span> <span m="922457">exchanges</span> <span m="922670">will</span>
  <span m="922883">shut</span> <span m="923096">down</span> <span m="923309">accounts</span>
  <span m="923522">because</span> <span m="923735">of</span> <span m="923948">this.</span>
  <span m="924161">And</span> <span m="924374">they</span> <span m="924587">say,</span>
  <span m="924800">look,</span> <span m="925044">you</span> <span m="925288">can</span>
  <span m="925532">buy</span> <span m="925776">bitcoins.</span> <span m="926020">But</span>
  <span m="926264">if</span> <span m="926508">you're</span> <span m="926752">using</span>
  <span m="926997">these</span> <span m="927241">to</span> <span m="927485">gamble,</span>
  <span m="927729">we</span> <span m="927973">don't</span> <span m="928217">want</span>
  <span m="928461">to</span> <span m="928705">get</span> <span m="928950">involved.</span>
  <span m="929428">It's</span> <span m="929907">just</span> <span m="930385">more</span>
  <span m="930864">risk</span> <span m="931342">for</span> <span m="931821">us.</span></p><p><span
  m="932300">And</span> <span m="932673">so</span> <span m="933046">they</span> <span
  m="933419">close</span> <span m="933792">the</span> <span m="934165">accounts.</span>
  <span m="934538">So</span> <span m="934911">the</span> <span m="935284">problem</span>
  <span m="935657">here</span> <span m="936031">is--</span> <span m="936404">what</span>
  <span m="936777">did</span> <span m="937150">I</span> <span m="937523">say</span>
  <span m="937896">next?</span> <span m="938269">From</span> <span m="938642">the</span>
  <span m="939015">perspective</span> <span m="939389">of</span> <span m="939685">the</span>
  <span m="939982">legal</span> <span m="940278">system,</span> <span m="940575">for</span>
  <span m="940871">the</span> <span m="941168">user</span> <span m="941464">it's</span>
  <span m="941761">obviously</span> <span m="942057">a</span> <span m="942354">problem,</span>
  <span m="942650">because</span> <span m="942947">it's</span> <span m="943243">annoying.</span></p><p><span
  m="943540">What's</span> <span m="943886">the</span> <span m="944232">problem</span>
  <span m="944578">for</span> <span m="944925">bitcoin</span> <span m="945271">here?</span>
  <span m="945617">Why</span> <span m="945963">should</span> <span m="946310">bitcoin</span>
  <span m="946656">care</span> <span m="947002">about</span> <span m="947348">this,</span>
  <span m="947695">like</span> <span m="948041">as</span> <span m="948387">people</span>
  <span m="948733">working</span> <span m="949080">on</span> <span m="949763">bitcoin?</span>
  <span m="950446">Why</span> <span m="951130">do</span> <span m="951813">I</span>
  <span m="952496">care?</span></p><p><span m="953180">AUDIENCE:</span> <span m="953700">Two</span>
  <span m="954221">reasons.</span> <span m="954742">It's</span> <span m="955262">the</span>
  <span m="955783">usability</span> <span m="956304">of</span> <span m="956825">bitcoin,</span>
  <span m="957345">that</span> <span m="957866">bitcoin</span> <span m="958387">is</span>
  <span m="958907">not</span> <span m="959428">usable</span> <span m="959949">that's</span>
  <span m="960470">public</span> <span m="961082">and</span> <span m="961694">private.</span>
  <span m="962306">So</span> <span m="962918">that's</span> <span m="963530">the</span>
  <span m="964142">different</span> <span m="964755">between</span> <span m="965367">fiat</span>
  <span m="965979">currencies,</span> <span m="966591">that</span> <span m="967203">can</span>
  <span m="967815">be</span> <span m="968427">like</span> <span m="969040">government,</span>
  <span m="969453">state.</span> <span m="969866">But,</span> <span m="970280">two,</span>
  <span m="970693">is</span> <span m="971106">then</span> <span m="971520">what</span>
  <span m="971933">happens</span> <span m="972346">to</span> <span m="972760">these</span>
  <span m="973173">two</span> <span m="973586">bitcoins?</span> <span m="974000">Do</span>
  <span m="974413">they</span> <span m="974826">just</span> <span m="975240">get</span>
  <span m="975740">burned?</span></p><p><span m="976240">They're</span> <span m="976492">suspended</span>
  <span m="976745">until</span> <span m="976997">there's</span> <span m="977250">some</span>
  <span m="977503">decision</span> <span m="977755">as</span> <span m="978008">to</span>
  <span m="978260">what</span> <span m="978513">to</span> <span m="978766">happen.</span>
  <span m="979018">They're</span> <span m="979271">not</span> <span m="979523">owned</span>
  <span m="979776">by</span> <span m="980029">the</span> <span m="980529">exchange.</span></p><p><span
  m="981029">TADGE</span> <span m="981264">DRYJA:</span> <span m="981500">They</span>
  <span m="981736">gave</span> <span m="981972">them</span> <span m="982208">back.</span>
  <span m="982444">But,</span> <span m="982680">yeah,</span> <span m="982916">the</span>
  <span m="983152">real</span> <span m="983388">thing</span> <span m="983624">is</span>
  <span m="983860">these</span> <span m="984096">two</span> <span m="984332">bitcoins</span>
  <span m="984568">are</span> <span m="984804">sort</span> <span m="985040">of</span>
  <span m="985340">worth</span> <span m="985640">less</span> <span m="985940">than</span>
  <span m="986240">two</span> <span m="986540">other</span> <span m="986840">bitcoins.</span>
  <span m="987140">Now,</span> <span m="987440">you've</span> <span m="987740">got</span>
  <span m="988040">a</span> <span m="988340">sort</span> <span m="988640">of</span>
  <span m="988940">different</span> <span m="989240">value</span> <span m="989540">for</span>
  <span m="989840">these,</span> <span m="990140">where</span> <span m="990413">these</span>
  <span m="990686">two</span> <span m="990959">bitcoins</span> <span m="991232">are</span>
  <span m="991505">hot.</span> <span m="991778">And</span> <span m="992052">I</span>
  <span m="992325">need</span> <span m="992598">to</span> <span m="992871">get</span>
  <span m="993144">rid</span> <span m="993417">of</span> <span m="993691">them,</span>
  <span m="993964">and</span> <span m="994237">launder</span> <span m="994510">them,</span>
  <span m="994783">or</span> <span m="995056">something.</span></p><p><span m="995330">AUDIENCE:</span>
  <span m="995472">That</span> <span m="995615">happens</span> <span m="995758">with</span>
  <span m="995901">$100</span> <span m="996044">bills</span> <span m="996187">too.</span></p><p><span
  m="996330">TADGE</span> <span m="996530">DRYJA:</span> <span m="996730">Really?</span>
  <span m="996930">OK,</span> <span m="997130">well.</span></p><p><span m="997330">AUDIENCE:</span>
  <span m="997740">I</span> <span m="998150">had</span> <span m="998560">a</span>
  <span m="998970">suitcase</span> <span m="999380">full</span> <span m="999790">of</span>
  <span m="1000200">them</span> <span m="1000610">in</span> <span m="1001020">Bogota.</span></p><p><span
  m="1001430">TADGE</span> <span m="1002058">DRYJA:</span> <span m="1002686">You</span>
  <span m="1003315">had</span> <span m="1003943">a</span> <span m="1004571">suitcase</span>
  <span m="1005200">full</span> <span m="1005828">of</span> <span m="1006456">hundreds,</span>
  <span m="1007085">and</span> <span m="1007713">you</span> <span m="1008341">just</span>
  <span m="1008970">walk</span> <span m="1009598">to</span> <span m="1010226">the</span>
  <span m="1010855">Bank</span> <span m="1011483">of</span> <span m="1012111">America,</span>
  <span m="1012740">and</span> <span m="1013198">say,</span> <span m="1013656">here,</span>
  <span m="1014115">I</span> <span m="1014573">want</span> <span m="1015031">to</span>
  <span m="1015490">deposit</span> <span m="1015948">this,</span> <span m="1016407">probably</span>
  <span m="1016865">you've</span> <span m="1017323">got</span> <span m="1017782">some</span>
  <span m="1018240">problems.</span></p><p><span m="1018699">AUDIENCE:</span> <span
  m="1019175">[INAUDIBLE]</span> <span m="1019652">1%</span> <span m="1020129">into</span>
  <span m="1020605">the</span> <span m="1021082">banking</span> <span m="1021559">system,</span>
  <span m="1022035">to</span> <span m="1022512">move</span> <span m="1022989">it</span>
  <span m="1023465">from</span> <span m="1023942">fiat</span> <span m="1024419">to</span>
  <span m="1024895">digital,</span> <span m="1025372">digital</span> <span m="1025849">fiat.</span></p><p><span
  m="1026849">TADGE</span> <span m="1026989">DRYJA:</span> <span m="1027129">Yeah,</span>
  <span m="1027269">like</span> <span m="1027409">actual</span> <span m="1027549">physical</span>
  <span m="1027689">currency</span> <span m="1027829">notes.</span></p><p><span m="1027970">AUDIENCE:</span>
  <span m="1028530">That's</span> <span m="1029090">not</span> <span m="1029650">money</span>
  <span m="1030210">laundering.</span></p><p><span m="1030770">TADGE</span> <span
  m="1031121">DRYJA:</span> <span m="1031472">So,</span> <span m="1031823">yeah,</span>
  <span m="1032174">so</span> <span m="1032525">now</span> <span m="1032877">you've</span>
  <span m="1033228">got</span> <span m="1033579">the</span> <span m="1033930">sort</span>
  <span m="1034281">of</span> <span m="1034632">money</span> <span m="1034984">laundering</span>
  <span m="1035335">that</span> <span m="1035686">now</span> <span m="1036037">people</span>
  <span m="1036388">are</span> <span m="1036740">going</span> <span m="1037121">to</span>
  <span m="1037503">try</span> <span m="1037884">to</span> <span m="1038266">do</span>
  <span m="1038647">using</span> <span m="1039029">bitcoin.</span> <span m="1039410">It</span>
  <span m="1039792">would</span> <span m="1040174">be</span> <span m="1040555">preferable</span>
  <span m="1040937">if--</span> <span m="1041318">so</span> <span m="1041700">the</span>
  <span m="1042081">way</span> <span m="1042463">that</span> <span m="1042844">they</span>
  <span m="1043226">can</span> <span m="1043608">tell</span> <span m="1044030">about</span>
  <span m="1044453">this,</span> <span m="1044876">is</span> <span m="1045299">that</span>
  <span m="1045722">people</span> <span m="1046144">reuse</span> <span m="1046567">addresses.</span>
  <span m="1046990">Bitcoin</span> <span m="1047413">is</span> <span m="1047836">not</span>
  <span m="1048258">inherently</span> <span m="1048681">as</span> <span m="1049104">fungible</span>
  <span m="1049527">as,</span> <span m="1049950">say,</span> <span m="1050929">gold.</span></p><p><span
  m="1051909">Dollar</span> <span m="1052174">bills</span> <span m="1052439">have</span>
  <span m="1052704">these</span> <span m="1052969">serial</span> <span m="1053234">numbers.</span>
  <span m="1053499">And</span> <span m="1053764">I</span> <span m="1054029">don't</span>
  <span m="1054294">know</span> <span m="1054559">to</span> <span m="1054824">what</span>
  <span m="1055089">extent</span> <span m="1055354">people</span> <span m="1055619">track</span>
  <span m="1055884">these</span> <span m="1056149">things.</span> <span m="1056460">But</span>
  <span m="1056771">bitcoins</span> <span m="1057083">are</span> <span m="1057394">much</span>
  <span m="1057706">more</span> <span m="1058017">like</span> <span m="1058328">the</span>
  <span m="1058640">dollar</span> <span m="1058951">bills</span> <span m="1059263">with</span>
  <span m="1059574">serial</span> <span m="1059885">numbers.</span> <span m="1060197">And</span>
  <span m="1060508">it's</span> <span m="1060820">all</span> <span m="1061042">on</span>
  <span m="1061265">the</span> <span m="1061488">internet.</span> <span m="1061711">It's</span>
  <span m="1061933">all</span> <span m="1062156">on</span> <span m="1062379">the</span>
  <span m="1062602">computer.</span> <span m="1062825">So</span> <span m="1063047">it's</span>
  <span m="1063270">really</span> <span m="1063493">easy</span> <span m="1063716">to</span>
  <span m="1063938">track</span> <span m="1064161">things</span> <span m="1064384">this</span>
  <span m="1064607">way.</span></p><p><span m="1064830">AUDIENCE:</span> <span m="1065227">[INAUDIBLE]</span>
  <span m="1065625">could</span> <span m="1066023">just</span> <span m="1066420">simply</span>
  <span m="1066818">transfer</span> <span m="1067216">them</span> <span m="1067613">to</span>
  <span m="1068011">a</span> <span m="1068409">new</span> <span m="1068806">address,</span>
  <span m="1069204">and</span> <span m="1069602">no</span> <span m="1069999">one</span>
  <span m="1070397">would</span> <span m="1070795">know</span> <span m="1071193">it</span>
  <span m="1071612">was</span> <span m="1072032">still</span> <span m="1072451">him</span>
  <span m="1072871">until</span> <span m="1073290">it</span> <span m="1073710">was</span>
  <span m="1074129">spent.</span></p><p><span m="1074549">TADGE</span> <span m="1074957">DRYJA:</span>
  <span m="1075366">Well,</span> <span m="1075775">yes</span> <span m="1076184">and</span>
  <span m="1076593">no.</span> <span m="1077002">So</span> <span m="1077411">you</span>
  <span m="1077820">say,</span> <span m="1078229">OK,</span> <span m="1078637">I'm</span>
  <span m="1079046">at</span> <span m="1079455">the</span> <span m="1079864">exchange.</span>
  <span m="1080273">They've</span> <span m="1080682">got</span> <span m="1081091">a</span>
  <span m="1081500">giant</span> <span m="1081909">pool</span> <span m="1082611">of</span>
  <span m="1083314">addresses.</span> <span m="1084016">I</span> <span m="1084719">transfer</span>
  <span m="1085421">to</span> <span m="1086124">the</span> <span m="1086826">casino.</span></p><p><span
  m="1087529">And</span> <span m="1087871">then</span> <span m="1088214">the</span>
  <span m="1088557">casino,</span> <span m="1088899">in</span> <span m="1089242">many</span>
  <span m="1089585">of</span> <span m="1089927">these</span> <span m="1090270">cases,</span>
  <span m="1090613">reuses</span> <span m="1090955">addresses</span> <span m="1091298">extensively.</span>
  <span m="1091641">So</span> <span m="1091983">it's</span> <span m="1092326">really</span>
  <span m="1092669">easy</span> <span m="1092995">to</span> <span m="1093321">see</span>
  <span m="1093647">that</span> <span m="1093973">this</span> <span m="1094299">is</span>
  <span m="1094625">the</span> <span m="1094951">casino.</span> <span m="1095277">And</span>
  <span m="1095604">then</span> <span m="1095930">from</span> <span m="1096256">the</span>
  <span m="1096582">casino,</span> <span m="1096908">goes</span> <span m="1097234">to</span>
  <span m="1097560">the</span> <span m="1097886">exchange</span> <span m="1098212">again.</span></p><p><span
  m="1098539">Exchange</span> <span m="1098745">flags</span> <span m="1098952">that</span>
  <span m="1099159">and</span> <span m="1099366">says,</span> <span m="1099572">hey,</span>
  <span m="1099779">we</span> <span m="1099986">know</span> <span m="1100193">where</span>
  <span m="1100399">this</span> <span m="1100606">came</span> <span m="1100813">from.</span></p><p><span
  m="1101020">Instead,</span> <span m="1101360">you</span> <span m="1101700">say,</span>
  <span m="1102041">OK,</span> <span m="1102381">I</span> <span m="1102722">go</span>
  <span m="1103062">to</span> <span m="1103403">User</span> <span m="1103743">A.</span>
  <span m="1104084">And</span> <span m="1104424">then</span> <span m="1104765">I</span>
  <span m="1105105">go</span> <span m="1105446">to</span> <span m="1105786">the</span>
  <span m="1106127">exchange.</span> <span m="1106467">In</span> <span m="1106808">some</span>
  <span m="1107148">cases,</span> <span m="1107489">that</span> <span m="1107728">might--</span>
  <span m="1107967">if</span> <span m="1108207">their</span> <span m="1108446">algorithm</span>
  <span m="1108686">is,</span> <span m="1108925">hey,</span> <span m="1109165">just</span>
  <span m="1109404">look</span> <span m="1109644">at</span> <span m="1109883">where</span>
  <span m="1110122">it</span> <span m="1110362">came</span> <span m="1110601">from,</span>
  <span m="1110841">sure.</span> <span m="1111080">But</span> <span m="1111320">if</span>
  <span m="1111559">you</span> <span m="1111799">say,</span> <span m="1112195">wait,</span>
  <span m="1112591">there</span> <span m="1112987">was</span> <span m="1113383">one</span>
  <span m="1113780">output.</span> <span m="1114176">This</span> <span m="1114572">transaction</span>
  <span m="1114968">is</span> <span m="1115365">one</span> <span m="1115761">input,</span>
  <span m="1116157">one</span> <span m="1116553">output.</span></p><p><span m="1116950">So</span>
  <span m="1117218">we</span> <span m="1117487">know</span> <span m="1117756">exactly</span>
  <span m="1118025">where</span> <span m="1118294">it</span> <span m="1118563">came</span>
  <span m="1118831">from.</span> <span m="1119100">You</span> <span m="1119369">can</span>
  <span m="1119638">trace</span> <span m="1119907">it</span> <span m="1120176">back</span>
  <span m="1120444">that</span> <span m="1120713">way.</span> <span m="1120982">So</span>
  <span m="1121251">it</span> <span m="1121520">depends.</span></p><p><span m="1121789">Would</span>
  <span m="1122195">the</span> <span m="1122601">coins</span> <span m="1123007">be</span>
  <span m="1123413">worth</span> <span m="1123819">less?</span> <span m="1124225">This</span>
  <span m="1124631">is</span> <span m="1125037">un-money</span> <span m="1125443">like.</span></p><p><span
  m="1125850">And</span> <span m="1126109">since</span> <span m="1126368">legal</span>
  <span m="1126628">tender</span> <span m="1126887">is</span> <span m="1127146">a</span>
  <span m="1127406">whole</span> <span m="1127665">other</span> <span m="1127924">thing.</span>
  <span m="1128184">And</span> <span m="1128443">I'm</span> <span m="1128702">pretty</span>
  <span m="1128962">sure</span> <span m="1129221">bitcoin</span> <span m="1129480">will</span>
  <span m="1129740">never</span> <span m="1129999">be</span> <span m="1130259">legal</span>
  <span m="1130635">tender</span> <span m="1131012">anywhere,</span> <span m="1131389">in</span>
  <span m="1131766">terms</span> <span m="1132143">of</span> <span m="1132520">debts</span>
  <span m="1132897">can</span> <span m="1133274">be</span> <span m="1133650">settled.</span>
  <span m="1134027">But</span> <span m="1134404">at</span> <span m="1134781">least</span>
  <span m="1135158">fungibility,</span> <span m="1135535">we</span> <span m="1135912">want.</span></p><p><span
  m="1136289">So</span> <span m="1136569">we</span> <span m="1136849">want</span>
  <span m="1137129">to</span> <span m="1137409">make</span> <span m="1137689">bitcoin</span>
  <span m="1137969">more</span> <span m="1138249">money</span> <span m="1138529">like,</span>
  <span m="1138809">how</span> <span m="1139089">do</span> <span m="1139369">we</span>
  <span m="1139649">fix</span> <span m="1139929">this?</span> <span m="1140209">The</span>
  <span m="1140489">first,</span> <span m="1140769">and</span> <span m="1141049">simplest,</span>
  <span m="1141330">and</span> <span m="1141703">possibly</span> <span m="1142077">the</span>
  <span m="1142451">biggest</span> <span m="1142824">is,</span> <span m="1143198">address</span>
  <span m="1143572">reuse.</span> <span m="1143945">So</span> <span m="1144319">if</span>
  <span m="1144693">the</span> <span m="1145066">casino</span> <span m="1145440">keeps</span>
  <span m="1145814">using</span> <span m="1146187">the</span> <span m="1146561">same</span>
  <span m="1146935">address</span> <span m="1147309">over</span> <span m="1147854">and</span>
  <span m="1148399">over,</span> <span m="1148944">it's</span> <span m="1149489">really</span>
  <span m="1150034">obvious.</span></p><p><span m="1150580">And</span> <span m="1150847">so</span>
  <span m="1151114">things</span> <span m="1151381">like</span> <span m="1151648">vanity</span>
  <span m="1151915">addresses,</span> <span m="1152182">so</span> <span m="1152449">a</span>
  <span m="1152716">lot</span> <span m="1152983">of</span> <span m="1153250">them</span>
  <span m="1153517">will</span> <span m="1153784">use</span> <span m="1154051">vanity</span>
  <span m="1154318">addresses.</span> <span m="1154585">A</span> <span m="1154852">vanity</span>
  <span m="1155119">address</span> <span m="1155548">is</span> <span m="1155977">when</span>
  <span m="1156407">you</span> <span m="1156836">continually</span> <span m="1157265">perform</span>
  <span m="1157695">computations</span> <span m="1158124">to</span> <span m="1158554">try</span>
  <span m="1158983">to</span> <span m="1159412">get</span> <span m="1159842">a</span>
  <span m="1160271">human</span> <span m="1160700">readable</span> <span m="1161130">address.</span>
  <span m="1161559">The</span> <span m="1161989">addresses</span> <span m="1162284">are</span>
  <span m="1162579">random</span> <span m="1162874">numbers.</span></p><p><span m="1163169">So</span>
  <span m="1163765">for</span> <span m="1164361">example,</span> <span m="1164957">I</span>
  <span m="1165554">ain't</span> <span m="1166150">rich.</span> <span m="1166746">So</span>
  <span m="1167343">Greg</span> <span m="1167939">Maxwell</span> <span m="1168535">has</span>
  <span m="1169132">this</span> <span m="1169728">address,</span> <span m="1170324">which</span>
  <span m="1170921">is</span> <span m="1171517">1gMaxwellbo8.</span> <span m="1172113">So</span>
  <span m="1172710">you</span> <span m="1173032">can</span> <span m="1173354">see</span>
  <span m="1173676">that</span> <span m="1173998">the</span> <span m="1174321">first</span>
  <span m="1174643">part</span> <span m="1174965">of</span> <span m="1175287">that</span>
  <span m="1175610">addresses</span> <span m="1175932">is</span> <span m="1176254">Jim</span>
  <span m="1176576">Maxwell.</span></p><p><span m="1176899">And</span> <span m="1177199">you</span>
  <span m="1177499">get</span> <span m="1177799">that</span> <span m="1178099">just</span>
  <span m="1178399">by</span> <span m="1178699">continually</span> <span m="1178999">attempting</span>
  <span m="1179299">millions</span> <span m="1179599">and</span> <span m="1179899">millions,</span>
  <span m="1180199">or</span> <span m="1180499">billions,</span> <span m="1180799">of</span>
  <span m="1181099">different</span> <span m="1181399">keys,</span> <span m="1181821">and</span>
  <span m="1182244">seeing</span> <span m="1182666">which</span> <span m="1183089">turn</span>
  <span m="1183511">into</span> <span m="1183934">the</span> <span m="1184356">address</span>
  <span m="1184779">you</span> <span m="1185201">want.</span> <span m="1185624">So</span>
  <span m="1186046">people</span> <span m="1186469">do</span> <span m="1186891">that.</span>
  <span m="1187314">People</span> <span m="1187736">spend</span> <span m="1188159">a</span>
  <span m="1188400">lot</span> <span m="1188641">of</span> <span m="1188883">resources</span>
  <span m="1189124">on</span> <span m="1189365">making</span> <span m="1189607">cool</span>
  <span m="1189848">addresses.</span></p><p><span m="1190090">And</span> <span m="1190372">then</span>
  <span m="1190654">the</span> <span m="1190936">casino</span> <span m="1191219">can</span>
  <span m="1191501">say,</span> <span m="1191783">OK,</span> <span m="1192066">this</span>
  <span m="1192348">is</span> <span m="1192630">my</span> <span m="1192912">address.</span>
  <span m="1193195">But</span> <span m="1193477">that</span> <span m="1193759">really</span>
  <span m="1194042">hurts</span> <span m="1194324">the</span> <span m="1194606">fungibility</span>
  <span m="1194889">and</span> <span m="1195326">privacy,</span> <span m="1195763">because</span>
  <span m="1196201">now</span> <span m="1196638">it's</span> <span m="1197076">clear</span>
  <span m="1197513">when</span> <span m="1197950">a</span> <span m="1198388">customer</span>
  <span m="1198825">sends</span> <span m="1199263">to</span> <span m="1199700">that</span>
  <span m="1200137">address,</span> <span m="1200575">everyone</span> <span m="1201012">in</span>
  <span m="1201450">the</span> <span m="1201806">world</span> <span m="1202162">can</span>
  <span m="1202518">see.</span> <span m="1202874">Yeah?</span></p><p><span m="1203230">AUDIENCE:</span>
  <span m="1203741">Does</span> <span m="1204253">the</span> <span m="1204765">casino</span>
  <span m="1205277">just</span> <span m="1205789">do</span> <span m="1206300">this,</span>
  <span m="1206812">because</span> <span m="1207324">it's</span> <span m="1207836">cool?</span>
  <span m="1208348">Because</span> <span m="1208859">it's</span> <span m="1209371">not</span>
  <span m="1209883">like</span> <span m="1210395">it's</span> <span m="1210907">easier</span>
  <span m="1211419">to</span> <span m="1211856">type</span> <span m="1212294">in,</span>
  <span m="1212731">because--</span> <span m="1213169">TADGE</span> <span m="1213523">DRYJA:</span>
  <span m="1213878">You</span> <span m="1214233">still</span> <span m="1214587">have</span>
  <span m="1214942">the</span> <span m="1215297">stuff.</span> <span m="1215651">It's</span>
  <span m="1216006">branding,</span> <span m="1216361">vanity</span> <span m="1216715">address,</span>
  <span m="1217070">it</span> <span m="1217425">cool</span> <span m="1217779">I</span>
  <span m="1218134">guess.</span></p><p><span m="1218489">But,</span> <span m="1219214">yeah,</span>
  <span m="1219939">Satoshi</span> <span m="1220664">Dice</span> <span m="1221389">does</span>
  <span m="1222114">this</span> <span m="1222839">too,</span> <span m="1223564">right?</span>
  <span m="1224289">Or</span> <span m="1225014">did.</span></p><p><span m="1225739">So</span>
  <span m="1226627">the</span> <span m="1227515">Satoshi</span> <span m="1228403">Dice</span>
  <span m="1229291">address</span> <span m="1230179">is--</span> <span m="1231067">yeah,</span>
  <span m="1231955">it</span> <span m="1232843">always</span> <span m="1233731">starts</span>
  <span m="1234619">with</span> <span m="1235507">one</span> <span m="1236395">dice.</span>
  <span m="1237283">So</span> <span m="1238171">branding,</span> <span m="1239059">I</span>
  <span m="1239300">guess,</span> <span m="1239542">makes</span> <span m="1239784">it</span>
  <span m="1240026">easier</span> <span m="1240267">for--</span> <span m="1240509">it</span>
  <span m="1240751">does</span> <span m="1240993">make</span> <span m="1241234">it</span>
  <span m="1241476">easier</span> <span m="1241718">for</span> <span m="1241960">people</span>
  <span m="1242201">to</span> <span m="1242443">recognize.</span> <span m="1242685">If</span>
  <span m="1242927">they</span> <span m="1243169">have</span> <span m="1243354">a</span>
  <span m="1243539">list</span> <span m="1243725">of</span> <span m="1243910">the</span>
  <span m="1244095">addresses,</span> <span m="1244281">they're</span> <span m="1244466">like,</span>
  <span m="1244651">oh,</span> <span m="1244837">that's</span> <span m="1245022">the</span>
  <span m="1245207">casino</span> <span m="1245393">address.</span> <span m="1245578">I</span>
  <span m="1245763">want</span> <span m="1245949">to</span> <span m="1246134">deposit</span>
  <span m="1246320">to</span> <span m="1246659">the</span> <span m="1246998">casino,</span>
  <span m="1247337">and</span> <span m="1247676">just</span> <span m="1248015">copy</span>
  <span m="1248354">and</span> <span m="1248693">paste</span> <span m="1249032">that</span>
  <span m="1249371">in</span> <span m="1249710">there.</span></p><p><span m="1250049">So</span>
  <span m="1250400">it</span> <span m="1250751">does</span> <span m="1251102">help</span>
  <span m="1251454">usability.</span> <span m="1251805">And</span> <span m="1252156">that's</span>
  <span m="1252507">one</span> <span m="1252859">of</span> <span m="1253210">the</span>
  <span m="1253561">issues</span> <span m="1253912">in</span> <span m="1254264">bitcoin.</span>
  <span m="1254615">It's</span> <span m="1254966">like,</span> <span m="1255317">having</span>
  <span m="1255669">these</span> <span m="1256021">giant,</span> <span m="1256373">ugly</span>
  <span m="1256726">addresses</span> <span m="1257078">that</span> <span m="1257430">you</span>
  <span m="1257783">have</span> <span m="1258135">to</span> <span m="1258487">get</span>
  <span m="1258840">right,</span> <span m="1259192">and</span> <span m="1259544">not</span>
  <span m="1259897">sent</span> <span m="1260249">to</span> <span m="1260601">the</span>
  <span m="1260954">wrong,</span> <span m="1261306">it's</span> <span m="1261659">not</span>
  <span m="1261973">a</span> <span m="1262287">great</span> <span m="1262601">user</span>
  <span m="1262915">experience</span> <span m="1263229">kind</span> <span m="1263543">of</span>
  <span m="1263857">thing.</span> <span m="1264171">So</span> <span m="1264486">I</span>
  <span m="1264800">can</span> <span m="1265114">see</span> <span m="1265428">that</span>
  <span m="1265742">vanity</span> <span m="1266056">addresses</span> <span m="1266370">do</span>
  <span m="1266684">improve</span> <span m="1266999">the</span> <span m="1267285">user</span>
  <span m="1267572">experience</span> <span m="1267859">a</span> <span m="1268146">little</span>
  <span m="1268433">bit.</span></p><p><span m="1268720">But</span> <span m="1269109">it</span>
  <span m="1269498">really</span> <span m="1269888">hurts</span> <span m="1270277">the</span>
  <span m="1270667">privacy</span> <span m="1271056">of</span> <span m="1271445">the</span>
  <span m="1271835">system.</span> <span m="1272224">And</span> <span m="1272614">address</span>
  <span m="1273003">reuse</span> <span m="1273392">is</span> <span m="1273782">a</span>
  <span m="1274171">problem,</span> <span m="1274561">because</span> <span m="1274950">people</span>
  <span m="1275340">keep</span> <span m="1276269">using</span> <span m="1277199">it.</span>
  <span m="1278129">It</span> <span m="1279059">looks</span> <span m="1279989">cool.</span>
  <span m="1280919">Also</span> <span m="1281849">web</span> <span m="1282779">explorers,</span>
  <span m="1283709">so</span> <span m="1284639">if</span> <span m="1285569">you</span>
  <span m="1286499">look</span> <span m="1287429">at</span> <span m="1288450">blockchain.info.</span>
  <span m="1289471">This</span> <span m="1290492">is</span> <span m="1291514">advanced</span>
  <span m="1292535">mode,</span> <span m="1293556">enable,</span> <span m="1294577">disable.</span></p><p><span
  m="1295599">Even</span> <span m="1295813">with</span> <span m="1296028">advanced</span>
  <span m="1296242">mode,</span> <span m="1296457">it'll</span> <span m="1296671">give</span>
  <span m="1296886">you</span> <span m="1297100">a</span> <span m="1297315">link</span>
  <span m="1297529">to</span> <span m="1297744">the</span> <span m="1297958">output.</span>
  <span m="1298173">So</span> <span m="1298387">no</span> <span m="1298602">one</span>
  <span m="1298816">is</span> <span m="1299031">going</span> <span m="1299245">to</span>
  <span m="1299460">click</span> <span m="1299802">that.</span> <span m="1300145">Anyway,</span>
  <span m="1300487">so</span> <span m="1300830">the</span> <span m="1301172">idea</span>
  <span m="1301515">is</span> <span m="1301857">this</span> <span m="1302200">shows,</span>
  <span m="1302542">oh,</span> <span m="1302885">here's</span> <span m="1303227">a</span>
  <span m="1303570">transaction.</span> <span m="1303912">It's</span> <span m="1304255">coming</span>
  <span m="1304597">from</span> <span m="1304940">two</span> <span m="1305621">addresses,</span>
  <span m="1306303">sending</span> <span m="1306984">to</span> <span m="1307666">two</span>
  <span m="1308347">addresses.</span></p><p><span m="1309029">And</span> <span m="1309409">it</span>
  <span m="1309789">even</span> <span m="1310169">gives</span> <span m="1310549">you</span>
  <span m="1310929">a</span> <span m="1311309">helpful,</span> <span m="1311689">hey,</span>
  <span m="1312069">this</span> <span m="1312449">is</span> <span m="1312829">Greg</span>
  <span m="1313209">Maxwell.</span> <span m="1313589">And</span> <span m="1313969">I'll</span>
  <span m="1314349">give</span> <span m="1314729">you</span> <span m="1315109">a</span>
  <span m="1315489">link</span> <span m="1315869">to--</span> <span m="1316568">where</span>
  <span m="1317267">does</span> <span m="1317967">this</span> <span m="1318666">link</span>
  <span m="1319365">go?</span> <span m="1320065">You're</span> <span m="1320764">being</span>
  <span m="1321464">redirected.</span> <span m="1322163">OK,</span> <span m="1322862">well,</span>
  <span m="1323562">go</span> <span m="1324261">for</span> <span m="1324960">it.</span>
  <span m="1325660">Gmax--</span> <span m="1326359">OK,</span> <span m="1327059">so</span>
  <span m="1328225">it's</span> <span m="1329391">Greg's</span> <span m="1330557">account</span>
  <span m="1331724">on</span> <span m="1332890">bitcoin</span> <span m="1334056">talk.</span>
  <span m="1335222">Interesting.</span></p><p><span m="1336389">So</span> <span m="1336662">you</span>
  <span m="1336935">guys</span> <span m="1337208">know</span> <span m="1337481">enough</span>
  <span m="1337755">about</span> <span m="1338028">the</span> <span m="1338301">system</span>
  <span m="1338574">now,</span> <span m="1338847">that</span> <span m="1339121">this</span>
  <span m="1339394">is</span> <span m="1339667">not</span> <span m="1339940">true.</span>
  <span m="1340213">If</span> <span m="1340487">you</span> <span m="1340760">click</span>
  <span m="1341033">on</span> <span m="1341306">an</span> <span m="1341580">address,</span>
  <span m="1341854">and</span> <span m="1342129">now</span> <span m="1342403">it</span>
  <span m="1342678">gives</span> <span m="1342953">you</span> <span m="1343227">all</span>
  <span m="1343502">the</span> <span m="1343777">transactions,</span> <span m="1344051">way</span>
  <span m="1344326">too</span> <span m="1344601">many,</span> <span m="1344875">that</span>
  <span m="1345150">were</span> <span m="1345425">involved</span> <span m="1345699">in</span>
  <span m="1345974">this.</span></p><p><span m="1346249">But</span> <span m="1346757">if</span>
  <span m="1347266">you</span> <span m="1347775">click</span> <span m="1348283">on</span>
  <span m="1348792">a</span> <span m="1349301">transaction,</span> <span m="1349809">it's</span>
  <span m="1350318">not</span> <span m="1350827">spending</span> <span m="1351335">from</span>
  <span m="1351844">addresses</span> <span m="1352353">and</span> <span m="1352861">to</span>
  <span m="1353370">addresses.</span></p><p><span m="1353879">It's</span> <span m="1354279">spending</span>
  <span m="1354679">from</span> <span m="1355079">transaction</span> <span m="1355479">outputs,</span>
  <span m="1355879">and</span> <span m="1356279">spending</span> <span m="1356679">to</span>
  <span m="1357079">addresses</span> <span m="1357479">that</span> <span m="1357879">can</span>
  <span m="1358279">later</span> <span m="1358679">be</span> <span m="1359079">consumed.</span></p><p><span
  m="1359480">So</span> <span m="1359807">the</span> <span m="1360134">way</span>
  <span m="1360461">that</span> <span m="1360788">web</span> <span m="1361115">explorers--</span>
  <span m="1361442">and</span> <span m="1361769">it'll</span> <span m="1362096">show</span>
  <span m="1362423">a</span> <span m="1362750">balance.</span> <span m="1363077">If</span>
  <span m="1363404">I</span> <span m="1363731">click</span> <span m="1364058">on</span>
  <span m="1364385">an</span> <span m="1364712">address,</span> <span m="1365039">it</span>
  <span m="1365327">says,</span> <span m="1365616">hey,</span> <span m="1365905">here's</span>
  <span m="1366193">the</span> <span m="1366482">number</span> <span m="1366771">of</span>
  <span m="1367059">transactions</span> <span m="1367348">involved.</span> <span m="1367637">Here's</span>
  <span m="1367925">the</span> <span m="1368214">final</span> <span m="1368503">balance.</span>
  <span m="1368791">And</span> <span m="1369080">you</span> <span m="1369369">can</span>
  <span m="1369767">look</span> <span m="1370165">at</span> <span m="1370563">the</span>
  <span m="1370961">current</span> <span m="1371359">balance,</span> <span m="1371757">and</span>
  <span m="1372155">things</span> <span m="1372553">like</span> <span m="1372951">that.</span></p><p><span
  m="1373350">But</span> <span m="1373627">that's</span> <span m="1373905">not</span>
  <span m="1374183">actually</span> <span m="1374461">how</span> <span m="1374739">the</span>
  <span m="1375017">system</span> <span m="1375295">works.</span> <span m="1375573">And</span>
  <span m="1375851">it</span> <span m="1376129">hurts</span> <span m="1376407">privacy</span>
  <span m="1376685">and</span> <span m="1376963">vulnerability,</span> <span m="1377241">to</span>
  <span m="1377519">have</span> <span m="1377729">this</span> <span m="1377940">idea</span>
  <span m="1378150">of,</span> <span m="1378361">oh,</span> <span m="1378571">this</span>
  <span m="1378782">is</span> <span m="1378993">sort</span> <span m="1379203">of</span>
  <span m="1379414">my</span> <span m="1379624">account.</span> <span m="1379835">And</span>
  <span m="1380045">it's</span> <span m="1380256">got</span> <span m="1380467">a</span>
  <span m="1380677">balance</span> <span m="1380888">that</span> <span m="1381098">can</span>
  <span m="1381309">increase</span> <span m="1381520">and</span> <span m="1381903">decrease,</span>
  <span m="1382286">because</span> <span m="1382669">then</span> <span m="1383053">that</span>
  <span m="1383436">implies</span> <span m="1383819">that</span> <span m="1384202">I'm</span>
  <span m="1384586">going</span> <span m="1384969">to</span> <span m="1385352">keep</span>
  <span m="1385735">using</span> <span m="1386119">it.</span> <span m="1386502">Whereas,</span>
  <span m="1386885">really,</span> <span m="1387269">if</span> <span m="1387662">they're</span>
  <span m="1388055">one-time</span> <span m="1388449">use,</span> <span m="1388842">that</span>
  <span m="1389236">really</span> <span m="1389629">makes</span> <span m="1390022">it</span>
  <span m="1390416">harder</span> <span m="1390809">to</span> <span m="1391203">trace</span>
  <span m="1391596">things.</span></p><p><span m="1391990">So</span> <span m="1392285">another</span>
  <span m="1392580">aspect</span> <span m="1392875">that</span> <span m="1393170">hurts</span>
  <span m="1393466">this,</span> <span m="1393761">if</span> <span m="1394056">you</span>
  <span m="1394351">want</span> <span m="1394647">to</span> <span m="1394942">trace</span>
  <span m="1395237">things--</span> <span m="1395532">so</span> <span m="1395828">if</span>
  <span m="1396123">it's</span> <span m="1396418">one</span> <span m="1396713">input,</span>
  <span m="1397009">one</span> <span m="1397393">output,</span> <span m="1397778">right</span>
  <span m="1398163">here,</span> <span m="1398547">it's</span> <span m="1398932">real</span>
  <span m="1399317">easy.</span> <span m="1399701">But</span> <span m="1400086">even</span>
  <span m="1400471">if</span> <span m="1400856">it's</span> <span m="1401240">not</span>
  <span m="1401625">one</span> <span m="1402010">input,</span> <span m="1402394">one</span>
  <span m="1402779">output--</span> <span m="1403164">so,</span> <span m="1403549">for</span>
  <span m="1403808">example,</span> <span m="1404067">imagine</span> <span m="1404327">a</span>
  <span m="1404586">transaction</span> <span m="1404846">where</span> <span m="1405105">the</span>
  <span m="1405365">input</span> <span m="1405624">has</span> <span m="1405883">10</span>
  <span m="1406143">coins</span> <span m="1406402">in</span> <span m="1406662">it.</span>
  <span m="1406921">There's</span> <span m="1407181">output</span> <span m="1407440">a,</span>
  <span m="1407700">which</span> <span m="1408184">is</span> <span m="1408669">one</span>
  <span m="1409154">coin,</span> <span m="1409639">output</span> <span m="1410124">b,</span>
  <span m="1410609">which</span> <span m="1411094">is</span> <span m="1411579">8.9997</span>
  <span m="1412064">coins.</span></p><p><span m="1412549">Which</span> <span m="1413323">do</span>
  <span m="1414097">you</span> <span m="1414871">think</span> <span m="1415645">is</span>
  <span m="1416419">the</span> <span m="1417193">change</span> <span m="1417967">address?</span>
  <span m="1418741">They're</span> <span m="1419515">all</span> <span m="1420289">different</span>
  <span m="1421063">addresses.</span> <span m="1421837">But</span> <span m="1422611">OK,</span>
  <span m="1423385">whoever</span> <span m="1424159">is</span> <span m="1424557">doing</span>
  <span m="1424955">this,</span> <span m="1425353">they're</span> <span m="1425751">sending</span>
  <span m="1426149">one</span> <span m="1426547">coin.</span> <span m="1426945">And</span>
  <span m="1427343">the</span> <span m="1427741">remainder,</span> <span m="1428139">minus</span>
  <span m="1428537">the</span> <span m="1428935">fee,</span> <span m="1429333">is</span>
  <span m="1429731">this.</span></p><p><span m="1430129">So</span> <span m="1430519">it's</span>
  <span m="1430910">often</span> <span m="1431300">pretty</span> <span m="1431691">clear,</span>
  <span m="1432082">even</span> <span m="1432472">though</span> <span m="1432863">looking</span>
  <span m="1433254">at</span> <span m="1433644">it,</span> <span m="1434035">all</span>
  <span m="1434425">the</span> <span m="1434816">addresses</span> <span m="1435207">are</span>
  <span m="1435597">different.</span> <span m="1435988">OK,</span> <span m="1436379">are</span>
  <span m="1436597">any</span> <span m="1436815">of</span> <span m="1437033">these</span>
  <span m="1437251">change</span> <span m="1437469">addresses?</span> <span m="1437687">Is</span>
  <span m="1437906">it</span> <span m="1438124">just</span> <span m="1438342">a</span>
  <span m="1438560">sending</span> <span m="1438778">to</span> <span m="1438996">b</span>
  <span m="1439214">and</span> <span m="1439433">c?</span> <span m="1439651">Is</span>
  <span m="1439869">it</span> <span m="1440087">a</span> <span m="1440305">sending</span>
  <span m="1440523">to</span> <span m="1440741">b,</span> <span m="1440960">and</span>
  <span m="1441273">back</span> <span m="1441587">to</span> <span m="1441900">a?</span>
  <span m="1442214">Often,</span> <span m="1442527">it's</span> <span m="1442841">pretty</span>
  <span m="1443154">easy</span> <span m="1443468">to</span> <span m="1443781">figure</span>
  <span m="1444095">out.</span></p><p><span m="1444409">And</span> <span m="1444709">you're</span>
  <span m="1445009">guessing.</span> <span m="1445309">But</span> <span m="1445609">you</span>
  <span m="1445909">can</span> <span m="1446209">get</span> <span m="1446509">the</span>
  <span m="1446809">guessing</span> <span m="1447109">pretty</span> <span m="1447409">good.</span>
  <span m="1447709">OK,</span> <span m="1448009">so</span> <span m="1448309">what</span>
  <span m="1448609">we're</span> <span m="1448909">going</span> <span m="1449209">to</span>
  <span m="1449509">talk</span> <span m="1449809">about</span> <span m="1450516">now--</span>
  <span m="1451224">anonymity</span> <span m="1451932">sets.</span></p><p><span m="1452640">So</span>
  <span m="1452965">bitcoin</span> <span m="1453290">is</span> <span m="1453615">not</span>
  <span m="1453941">actually</span> <span m="1454266">anonymous.</span> <span m="1454591">There</span>
  <span m="1454916">are</span> <span m="1455242">sort</span> <span m="1455567">of</span>
  <span m="1455892">identities</span> <span m="1456217">attached</span> <span m="1456543">to</span>
  <span m="1456868">these</span> <span m="1457193">things,</span> <span m="1457519">in</span>
  <span m="1457801">that</span> <span m="1458084">you</span> <span m="1458367">have</span>
  <span m="1458649">addresses.</span> <span m="1458932">The</span> <span m="1459215">addresses</span>
  <span m="1459498">are</span> <span m="1459780">not</span> <span m="1460063">your</span>
  <span m="1460346">name.</span></p><p><span m="1460629">But</span> <span m="1460850">you</span>
  <span m="1461072">can</span> <span m="1461294">think</span> <span m="1461516">of</span>
  <span m="1461737">them</span> <span m="1461959">as</span> <span m="1462181">a</span>
  <span m="1462403">pseudonym.</span> <span m="1462624">And</span> <span m="1462846">you</span>
  <span m="1463068">can</span> <span m="1463290">create</span> <span m="1463511">a</span>
  <span m="1463733">bunch</span> <span m="1463955">of</span> <span m="1464177">pseudonyms.</span></p><p><span
  m="1464399">But</span> <span m="1464898">there</span> <span m="1465397">are</span>
  <span m="1465896">these</span> <span m="1466395">keys.</span> <span m="1466894">There</span>
  <span m="1467393">are</span> <span m="1467892">these</span> <span m="1468391">publicly</span>
  <span m="1468890">known</span> <span m="1469389">addresses.</span></p><p><span m="1469889">And</span>
  <span m="1470246">so</span> <span m="1470604">we</span> <span m="1470962">want</span>
  <span m="1471320">to</span> <span m="1471678">expand</span> <span m="1472036">an</span>
  <span m="1472394">anonymity</span> <span m="1472752">set.</span> <span m="1473110">And</span>
  <span m="1473468">so</span> <span m="1473826">the</span> <span m="1474184">idea</span>
  <span m="1474542">of</span> <span m="1474900">an</span> <span m="1475258">anonymity</span>
  <span m="1475616">set</span> <span m="1475974">is,</span> <span m="1476332">how</span>
  <span m="1476690">many</span> <span m="1477317">possible</span> <span m="1477945">different</span>
  <span m="1478573">identities</span> <span m="1479201">could</span> <span m="1479829">be</span>
  <span m="1480457">the</span> <span m="1481085">owner</span> <span m="1481713">of</span>
  <span m="1482341">these</span> <span m="1482969">coins?</span> <span m="1483597">And</span>
  <span m="1484225">the</span> <span m="1484853">idea</span> <span m="1485481">of</span>
  <span m="1486109">expanding</span> <span m="1486380">your</span> <span m="1486652">anonymity</span>
  <span m="1486923">set--</span> <span m="1487195">so</span> <span m="1487466">even</span>
  <span m="1487738">if</span> <span m="1488009">bitcoin</span> <span m="1488281">were</span>
  <span m="1488552">perfectly</span> <span m="1488824">anonymous,</span> <span m="1489095">in</span>
  <span m="1489367">terms</span> <span m="1489639">of</span> <span m="1489926">the</span>
  <span m="1490213">anonymity</span> <span m="1490501">set</span> <span m="1490788">was</span>
  <span m="1491076">everyone</span> <span m="1491363">who</span> <span m="1491650">had</span>
  <span m="1491938">Bitcoin,</span> <span m="1492225">that's</span> <span m="1492513">still</span>
  <span m="1492800">actually</span> <span m="1493087">not</span> <span m="1493375">that</span>
  <span m="1493662">many</span> <span m="1493950">people.</span></p><p><span m="1494950">So</span>
  <span m="1495152">if</span> <span m="1495354">you</span> <span m="1495556">see</span>
  <span m="1495758">a</span> <span m="1495960">bitcoin,</span> <span m="1496162">you're</span>
  <span m="1496364">like,</span> <span m="1496566">well,</span> <span m="1496768">I</span>
  <span m="1496970">don't</span> <span m="1497172">know</span> <span m="1497374">who</span>
  <span m="1497576">owns</span> <span m="1497778">it.</span> <span m="1497980">But</span>
  <span m="1498182">I</span> <span m="1498384">know</span> <span m="1498586">that</span>
  <span m="1498789">the</span> <span m="1499019">person</span> <span m="1499250">who</span>
  <span m="1499481">owns</span> <span m="1499711">it,</span> <span m="1499942">owns</span>
  <span m="1500173">bitcoin.</span> <span m="1500403">And,</span> <span m="1500634">actually,</span>
  <span m="1500865">there's</span> <span m="1501095">not</span> <span m="1501326">that</span>
  <span m="1501557">many</span> <span m="1501787">people</span> <span m="1502018">who</span>
  <span m="1502249">own</span> <span m="1502629">bitcoin.</span> <span m="1503010">So</span>
  <span m="1503391">I've</span> <span m="1503771">just</span> <span m="1504152">eliminated</span>
  <span m="1504533">99%</span> <span m="1504913">of</span> <span m="1505294">the</span>
  <span m="1505675">people,</span> <span m="1506055">my</span> <span m="1506436">suspects,</span>
  <span m="1506817">just</span> <span m="1507197">by</span> <span m="1507578">doing</span>
  <span m="1507959">that.</span></p><p><span m="1508340">So</span> <span m="1508734">just</span>
  <span m="1509128">having</span> <span m="1509522">more</span> <span m="1509917">people</span>
  <span m="1510311">using</span> <span m="1510705">bitcoin</span> <span m="1511100">makes</span>
  <span m="1511494">it</span> <span m="1511888">more</span> <span m="1512283">anonymous,</span>
  <span m="1512677">in</span> <span m="1513071">that</span> <span m="1513466">sense.</span>
  <span m="1513860">If</span> <span m="1514254">it's</span> <span m="1514649">very</span>
  <span m="1514961">niche</span> <span m="1515274">kind</span> <span m="1515587">of</span>
  <span m="1515900">thing,</span> <span m="1516213">and</span> <span m="1516526">then</span>
  <span m="1516839">the</span> <span m="1517152">police</span> <span m="1517465">say,</span>
  <span m="1517778">OK,</span> <span m="1518091">well</span> <span m="1518404">whoever</span>
  <span m="1518717">did</span> <span m="1519030">this</span> <span m="1519343">crime,</span>
  <span m="1519656">they're</span> <span m="1519969">a</span> <span m="1520226">bitcoin</span>
  <span m="1520483">user.</span> <span m="1520740">Well,</span> <span m="1520997">now</span>
  <span m="1521255">you</span> <span m="1521512">can</span> <span m="1521769">find--</span>
  <span m="1522026">there's</span> <span m="1522284">not</span> <span m="1522541">that</span>
  <span m="1522798">many</span> <span m="1523055">bitcoin</span> <span m="1523312">users.</span>
  <span m="1523570">So</span> <span m="1523827">you</span> <span m="1524084">want</span>
  <span m="1524341">to</span> <span m="1524599">try</span> <span m="1525004">to</span>
  <span m="1525409">increase</span> <span m="1525814">your</span> <span m="1526219">anonymity</span>
  <span m="1526624">set</span> <span m="1527029">for</span> <span m="1527434">a</span>
  <span m="1527839">specific</span> <span m="1528244">transaction.</span></p><p><span
  m="1528649">So</span> <span m="1528939">the</span> <span m="1529230">traditional--</span>
  <span m="1529520">I</span> <span m="1529811">don't</span> <span m="1530101">want</span>
  <span m="1530392">to</span> <span m="1530682">say</span> <span m="1530973">traditional--</span>
  <span m="1531264">the</span> <span m="1531554">way</span> <span m="1531845">you</span>
  <span m="1532135">do</span> <span m="1532426">this</span> <span m="1532716">is</span>
  <span m="1533007">basically</span> <span m="1533297">money</span> <span m="1533588">laundering.</span></p><p><span
  m="1533879">It's</span> <span m="1534325">a</span> <span m="1534772">bitcoin</span>
  <span m="1535219">mixer.</span> <span m="1535665">And</span> <span m="1536112">these</span>
  <span m="1536559">mixers</span> <span m="1537006">still</span> <span m="1537452">exist.</span>
  <span m="1537899">I'm</span> <span m="1538346">pretty</span> <span m="1538793">sure,</span>
  <span m="1539239">right?</span> <span m="1539686">They're</span> <span m="1540133">still</span>
  <span m="1540580">around?</span></p><p><span m="1541580">They're</span> <span m="1541859">still</span>
  <span m="1542139">around.</span> <span m="1542419">I</span> <span m="1542699">don't</span>
  <span m="1542979">know</span> <span m="1543259">why.</span> <span m="1543539">But</span>
  <span m="1543819">a</span> <span m="1544099">lot</span> <span m="1544379">of</span>
  <span m="1544659">times</span> <span m="1544939">they</span> <span m="1545219">use</span>
  <span m="1545499">Tor.</span> <span m="1545779">I</span> <span m="1546059">mean,</span>
  <span m="1546339">I</span> <span m="1546619">know</span> <span m="1546899">why.</span>
  <span m="1547169">But</span> <span m="1547440">it's</span> <span m="1547711">like,</span>
  <span m="1547982">there's</span> <span m="1548253">so</span> <span m="1548524">many</span>
  <span m="1548794">better</span> <span m="1549065">ways</span> <span m="1549336">to</span>
  <span m="1549607">do</span> <span m="1549878">this.</span></p><p><span m="1550149">So</span>
  <span m="1550342">you've</span> <span m="1550535">got</span> <span m="1550728">coins</span>
  <span m="1550921">at</span> <span m="1551115">address</span> <span m="1551308">A.</span>
  <span m="1551501">And</span> <span m="1551694">you</span> <span m="1551887">say,</span>
  <span m="1552081">OK,</span> <span m="1552274">I'm</span> <span m="1552467">going</span>
  <span m="1552660">to</span> <span m="1552853">send</span> <span m="1553047">10</span>
  <span m="1553240">coins</span> <span m="1553433">to</span> <span m="1553626">the</span>
  <span m="1553820">mixer,</span> <span m="1554151">which</span> <span m="1554483">has</span>
  <span m="1554815">address</span> <span m="1555147">me.</span> <span m="1555479">And</span>
  <span m="1555811">then</span> <span m="1556143">later,</span> <span m="1556475">some</span>
  <span m="1556807">different,</span> <span m="1557139">not</span> <span m="1557471">from</span>
  <span m="1557803">that</span> <span m="1558135">output,</span> <span m="1558467">but</span>
  <span m="1558799">somewhere</span> <span m="1559114">else</span> <span m="1559429">in</span>
  <span m="1559744">this</span> <span m="1560059">sort</span> <span m="1560374">of</span>
  <span m="1560689">giant</span> <span m="1561004">mixer</span> <span m="1561319">account,</span>
  <span m="1561634">four</span> <span m="1561949">coins</span> <span m="1562264">get</span>
  <span m="1562579">sent</span> <span m="1562894">to</span> <span m="1563209">address</span>
  <span m="1563524">C,</span> <span m="1563840">and</span> <span m="1564194">six</span>
  <span m="1564548">coins</span> <span m="1564902">to</span> <span m="1565256">address</span>
  <span m="1565610">D.</span> <span m="1565964">So</span> <span m="1566318">you</span>
  <span m="1566672">basically</span> <span m="1567026">pool</span> <span m="1567380">all</span>
  <span m="1567734">the</span> <span m="1568088">coins</span> <span m="1568442">into</span>
  <span m="1568796">this</span> <span m="1569150">mixer,</span> <span m="1569504">which</span>
  <span m="1569859">uses</span> <span m="1570290">lots</span> <span m="1570721">of</span>
  <span m="1571153">different</span> <span m="1571584">addresses,</span> <span m="1572016">and</span>
  <span m="1572447">then</span> <span m="1572879">split</span> <span m="1573310">it</span>
  <span m="1573741">up</span> <span m="1574173">over</span> <span m="1574604">time,</span>
  <span m="1575036">different</span> <span m="1575467">amounts.</span></p><p><span
  m="1575899">And</span> <span m="1576198">it</span> <span m="1576497">gets</span>
  <span m="1576796">really</span> <span m="1577095">hard</span> <span m="1577395">to</span>
  <span m="1577694">figure</span> <span m="1577993">out</span> <span m="1578292">where</span>
  <span m="1578592">the</span> <span m="1578891">coins</span> <span m="1579190">came</span>
  <span m="1579489">from.</span></p><p><span m="1579789">So</span> <span m="1580203">your</span>
  <span m="1580617">anonymity</span> <span m="1581031">set</span> <span m="1581445">is</span>
  <span m="1581859">bigger.</span> <span m="1582273">The</span> <span m="1582687">problem</span>
  <span m="1583101">is</span> <span m="1583515">mixers</span> <span m="1583929">were</span>
  <span m="1584343">well.</span> <span m="1584757">Potential</span> <span m="1585171">anonymity</span>
  <span m="1585585">set</span> <span m="1586000">is</span> <span m="1586255">all</span>
  <span m="1586510">the</span> <span m="1586765">other</span> <span m="1587021">users</span>
  <span m="1587276">of</span> <span m="1587531">the</span> <span m="1587787">mixer,</span>
  <span m="1588042">if</span> <span m="1588297">it's</span> <span m="1588552">well</span>
  <span m="1588808">designed.</span> <span m="1589063">The</span> <span m="1589318">problem,</span>
  <span m="1589574">the</span> <span m="1589829">mixers</span> <span m="1590084">disappear</span>
  <span m="1590340">with</span> <span m="1590883">everyone's</span> <span m="1591427">money,</span>
  <span m="1591971">very</span> <span m="1592515">consistently.</span></p><p><span
  m="1593059">The</span> <span m="1593592">mixers</span> <span m="1594126">are</span>
  <span m="1594659">certainly</span> <span m="1595193">not</span> <span m="1595726">publicly</span>
  <span m="1596260">regulated</span> <span m="1596794">companies.</span> <span m="1597327">I'm</span>
  <span m="1597861">pretty</span> <span m="1598394">sure</span> <span m="1598928">you</span>
  <span m="1599461">couldn't</span> <span m="1599995">do</span> <span m="1600529">that.</span>
  <span m="1600827">So</span> <span m="1601125">they're</span> <span m="1601423">just</span>
  <span m="1601721">sort</span> <span m="1602019">of</span> <span m="1602317">these</span>
  <span m="1602615">anonymous,</span> <span m="1602914">like,</span> <span m="1603212">hey,</span>
  <span m="1603510">I'm</span> <span m="1603808">a</span> <span m="1604106">mixer,</span>
  <span m="1604404">bitcoin</span> <span m="1604702">cloud,</span> <span m="1605000">or</span>
  <span m="1605299">bitcoin</span> <span m="1605546">fog,</span> <span m="1605794">or</span>
  <span m="1606042">whatever.</span> <span m="1606290">And</span> <span m="1606537">a</span>
  <span m="1606785">lot</span> <span m="1607033">of</span> <span m="1607281">times</span>
  <span m="1607529">they're</span> <span m="1607776">on</span> <span m="1608024">Tor.</span>
  <span m="1608272">So</span> <span m="1608520">you</span> <span m="1608767">don't</span>
  <span m="1609015">even</span> <span m="1609263">know</span> <span m="1609511">where</span>
  <span m="1609759">the</span> <span m="1610047">mixer</span> <span m="1610335">exists.</span>
  <span m="1610623">And</span> <span m="1610911">you</span> <span m="1611199">sort</span>
  <span m="1611487">of</span> <span m="1611775">hope</span> <span m="1612064">for</span>
  <span m="1612352">the</span> <span m="1612640">best</span> <span m="1612928">and</span>
  <span m="1613216">send</span> <span m="1613504">your</span> <span m="1613792">money.</span>
  <span m="1614080">Yeah?</span></p><p><span m="1614369">AUDIENCE:</span> <span m="1614693">Do</span>
  <span m="1615017">they</span> <span m="1615342">take</span> <span m="1615666">a</span>
  <span m="1615991">transaction</span> <span m="1616315">fee?</span></p><p><span m="1616640">TADGE</span>
  <span m="1616779">DRYJA:</span> <span m="1616919">Yes,</span> <span m="1617059">of</span>
  <span m="1617199">them</span> <span m="1617339">take</span> <span m="1617479">fees.</span>
  <span m="1617619">The</span> <span m="1617759">big</span> <span m="1617899">fee</span>
  <span m="1618039">is</span> <span m="1618179">when</span> <span m="1618319">they</span>
  <span m="1618459">keep</span> <span m="1618599">all</span> <span m="1618739">your</span>
  <span m="1618879">money</span> <span m="1619019">and</span> <span m="1619159">don't</span>
  <span m="1619299">give</span> <span m="1619726">it</span> <span m="1620153">back.</span>
  <span m="1620581">But</span> <span m="1621008">a</span> <span m="1621435">lot</span>
  <span m="1621863">of</span> <span m="1622290">times,</span> <span m="1622717">they</span>
  <span m="1623145">will</span> <span m="1623572">take</span> <span m="1624000">a</span>
  <span m="1624427">small</span> <span m="1624854">cut.</span> <span m="1625282">But</span>
  <span m="1625709">it's</span> <span m="1626136">not</span> <span m="1626564">actually</span>
  <span m="1626991">hard.</span></p><p><span m="1627419">The</span> <span m="1627699">cost</span>
  <span m="1627980">is</span> <span m="1628260">pretty</span> <span m="1628541">minimal.</span>
  <span m="1628822">Need</span> <span m="1629102">some</span> <span m="1629383">kind</span>
  <span m="1629664">of</span> <span m="1629944">Tor</span> <span m="1630225">service.</span>
  <span m="1630506">And</span> <span m="1630786">then</span> <span m="1631067">you</span>
  <span m="1631348">just</span> <span m="1631628">have</span> <span m="1631909">some</span>
  <span m="1632190">software</span> <span m="1632630">that</span> <span m="1633070">just</span>
  <span m="1633510">runs</span> <span m="1633950">this,</span> <span m="1634390">and</span>
  <span m="1634830">allows</span> <span m="1635270">deposits</span> <span m="1635710">and</span>
  <span m="1636150">withdrawals.</span></p><p><span m="1636590">The</span> <span m="1636915">conference</span>
  <span m="1637240">in</span> <span m="1637565">Puerto</span> <span m="1637890">Rico,</span>
  <span m="1638216">Financial</span> <span m="1638541">Cryptos,</span> <span m="1638866">there</span>
  <span m="1639191">was</span> <span m="1639517">a</span> <span m="1639842">talk</span>
  <span m="1640167">about</span> <span m="1640492">a--</span> <span m="1640818">what</span>
  <span m="1641143">was</span> <span m="1641468">the</span> <span m="1641793">word</span>
  <span m="1642119">they</span> <span m="1642952">used?</span> <span m="1643786">Not</span>
  <span m="1644620">traceable,</span> <span m="1645454">a</span> <span m="1646288">mixer</span>
  <span m="1647121">that</span> <span m="1647955">you</span> <span m="1648789">could</span>
  <span m="1649623">prove</span> <span m="1650457">defrauded</span> <span m="1651290">you.</span>
  <span m="1652124">So</span> <span m="1652958">you</span> <span m="1653792">could</span>
  <span m="1654626">have</span> <span m="1655460">these</span> <span m="1655744">proofs</span>
  <span m="1656028">that,</span> <span m="1656313">oh,</span> <span m="1656597">I</span>
  <span m="1656882">can</span> <span m="1657166">prove</span> <span m="1657451">that</span>
  <span m="1657735">they</span> <span m="1658020">stole</span> <span m="1658304">my</span>
  <span m="1658588">coins,</span> <span m="1658873">which</span> <span m="1659157">is</span>
  <span m="1659442">I</span> <span m="1659726">thought</span> <span m="1660011">was</span>
  <span m="1660295">kind</span> <span m="1660580">of</span> <span m="1660846">useless,</span>
  <span m="1661113">because</span> <span m="1661379">the</span> <span m="1661646">whole</span>
  <span m="1661912">idea</span> <span m="1662179">is</span> <span m="1662445">they're</span>
  <span m="1662712">anonymous.</span></p><p><span m="1662979">And</span> <span m="1663252">maybe</span>
  <span m="1663526">you</span> <span m="1663800">can</span> <span m="1664074">prove</span>
  <span m="1664348">that</span> <span m="1664622">they</span> <span m="1664896">ripped</span>
  <span m="1665170">you</span> <span m="1665444">off.</span> <span m="1665717">But</span>
  <span m="1665991">they</span> <span m="1666265">still</span> <span m="1666539">ripped</span>
  <span m="1666813">you</span> <span m="1667087">off.</span> <span m="1667361">OK,</span>
  <span m="1667635">so</span> <span m="1667909">then</span> <span m="1668346">the</span>
  <span m="1668784">better</span> <span m="1669222">idea</span> <span m="1669660">than</span>
  <span m="1670098">a</span> <span m="1670536">mixer</span> <span m="1670974">is</span>
  <span m="1671412">I</span> <span m="1671850">taint</span> <span m="1672287">rich</span>
  <span m="1672725">was</span> <span m="1673163">a</span> <span m="1673601">blog</span>
  <span m="1674039">post</span> <span m="1674477">from</span> <span m="1674915">Greg.</span>
  <span m="1675353">That's</span> <span m="1675791">why</span> <span m="1676229">I've</span>
  <span m="1676574">got</span> <span m="1676919">this</span> <span m="1677264">up.</span></p><p><span
  m="1677610">In</span> <span m="1677858">2013,</span> <span m="1678107">and</span>
  <span m="1678355">it</span> <span m="1678604">was</span> <span m="1678853">kind</span>
  <span m="1679101">of</span> <span m="1679350">fun.</span> <span m="1679599">Ever</span>
  <span m="1679847">since</span> <span m="1680096">I</span> <span m="1680345">was</span>
  <span m="1680593">a</span> <span m="1680842">wee</span> <span m="1681090">lad,</span>
  <span m="1681339">I</span> <span m="1681588">had</span> <span m="1681836">a</span>
  <span m="1682085">dream,</span> <span m="1682334">a</span> <span m="1682582">dream</span>
  <span m="1682831">of</span> <span m="1683080">being</span> <span m="1683382">incorrectly</span>
  <span m="1683684">assessed</span> <span m="1683986">as</span> <span m="1684289">impossibly</span>
  <span m="1684591">rich</span> <span m="1684893">by</span> <span m="1685196">a</span>
  <span m="1685498">braindead</span> <span m="1685800">automated</span> <span m="1686103">analysis.</span>
  <span m="1686405">Now,</span> <span m="1686707">with</span> <span m="1687010">your</span>
  <span m="1687324">help,</span> <span m="1687638">I</span> <span m="1687952">can</span>
  <span m="1688266">be.</span></p><p><span m="1688580">So</span> <span m="1689115">he</span>
  <span m="1689650">wanted</span> <span m="1690185">to</span> <span m="1690721">mix</span>
  <span m="1691256">inputs</span> <span m="1691791">from</span> <span m="1692326">different</span>
  <span m="1692862">people</span> <span m="1693397">within</span> <span m="1693932">the</span>
  <span m="1694467">same</span> <span m="1695003">transaction.</span> <span m="1695538">So</span>
  <span m="1696073">you</span> <span m="1696609">could</span> <span m="1696854">have</span>
  <span m="1697099">two</span> <span m="1697345">different</span> <span m="1697590">people</span>
  <span m="1697835">in</span> <span m="1698081">the</span> <span m="1698326">same</span>
  <span m="1698571">transaction.</span> <span m="1698817">And</span> <span m="1699062">in</span>
  <span m="1699307">bitcoin,</span> <span m="1699553">this</span> <span m="1699798">is</span>
  <span m="1700043">secure,</span> <span m="1700289">because</span> <span m="1700809">the</span>
  <span m="1701329">signature</span> <span m="1701849">signs</span> <span m="1702369">the</span>
  <span m="1702889">whole</span> <span m="1703409">transaction.</span></p><p><span
  m="1703929">So</span> <span m="1704277">you</span> <span m="1704626">say,</span>
  <span m="1704974">OK,</span> <span m="1705323">I'm</span> <span m="1705672">user</span>
  <span m="1706020">A.</span> <span m="1706369">I</span> <span m="1706717">have</span>
  <span m="1707066">my</span> <span m="1707415">10</span> <span m="1707763">coin</span>
  <span m="1708112">input.</span> <span m="1708461">I'll</span> <span m="1708809">match</span>
  <span m="1709158">up</span> <span m="1709506">with</span> <span m="1709855">user</span>
  <span m="1710204">B,</span> <span m="1710552">who's</span> <span m="1710901">got</span>
  <span m="1711250">his</span> <span m="1711576">two</span> <span m="1711903">coin</span>
  <span m="1712230">input.</span> <span m="1712557">And</span> <span m="1712884">we</span>
  <span m="1713210">both</span> <span m="1713537">sign</span> <span m="1713864">this</span>
  <span m="1714191">whole</span> <span m="1714518">transaction,</span> <span m="1714844">which</span>
  <span m="1715171">sends</span> <span m="1715498">two</span> <span m="1715825">coins</span>
  <span m="1716152">to</span> <span m="1716479">C,</span> <span m="1716953">and</span>
  <span m="1717427">10</span> <span m="1717902">coins</span> <span m="1718376">to</span>
  <span m="1718851">D.</span> <span m="1719325">So</span> <span m="1719800">now,</span>
  <span m="1720274">you</span> <span m="1720749">can't</span> <span m="1721223">trace</span>
  <span m="1721697">where</span> <span m="1722172">these</span> <span m="1722646">coins</span>
  <span m="1723121">went</span> <span m="1723595">right.</span> <span m="1724070">Right?</span>
  <span m="1724544">Well,</span> <span m="1725019">you</span> <span m="1725541">sort</span>
  <span m="1726064">of</span> <span m="1726587">can.</span></p><p><span m="1727110">But</span>
  <span m="1727313">if</span> <span m="1727516">you</span> <span m="1727719">just</span>
  <span m="1727923">look</span> <span m="1728126">at</span> <span m="1728329">the</span>
  <span m="1728532">graph</span> <span m="1728736">of</span> <span m="1728939">transactions,</span>
  <span m="1729142">it's</span> <span m="1729346">not</span> <span m="1729549">as</span>
  <span m="1729752">obvious.</span> <span m="1729955">So</span> <span m="1730159">the</span>
  <span m="1730362">first</span> <span m="1730565">transaction</span> <span m="1730769">is</span>
  <span m="1731434">really</span> <span m="1732100">fun.</span> <span m="1732766">I</span>
  <span m="1733431">remember</span> <span m="1734097">seeing</span> <span m="1734763">this.</span></p><p><span
  m="1735429">So</span> <span m="1736042">there's</span> <span m="1736655">three</span>
  <span m="1737268">inputs,</span> <span m="1737881">40,000</span> <span m="1738494">bitcoins,</span>
  <span m="1739107">0.1337</span> <span m="1739720">bitcoins,</span> <span m="1740333">and</span>
  <span m="1740946">1</span> <span m="1741559">bitcoin</span> <span m="1742172">from</span>
  <span m="1742785">Greg,</span> <span m="1743399">and</span> <span m="1743988">then</span>
  <span m="1744577">40,000,</span> <span m="1745167">and</span> <span m="1745756">31337,</span>
  <span m="1746346">and</span> <span m="1746935">then</span> <span m="1747525">0.82.</span>
  <span m="1748114">For</span> <span m="1748703">some</span> <span m="1749293">reason,</span>
  <span m="1749882">it</span> <span m="1750472">was</span> <span m="1751061">even</span>
  <span m="1751651">more--</span> <span m="1752240">yeah,</span> <span m="1752830">40,000</span>
  <span m="1753191">bitcoins</span> <span m="1753553">is</span> <span m="1753915">pretty</span>
  <span m="1754277">good</span> <span m="1754639">today.</span> <span m="1755000">It</span>
  <span m="1755362">was</span> <span m="1755724">no</span> <span m="1756086">less</span>
  <span m="1756448">impressive</span> <span m="1756810">at</span> <span m="1757171">the</span>
  <span m="1757533">time</span> <span m="1757895">in</span> <span m="1758257">2013,</span>
  <span m="1758619">even</span> <span m="1758981">though</span> <span m="1759296">I</span>
  <span m="1759611">guess</span> <span m="1759926">it</span> <span m="1760242">was</span>
  <span m="1760557">only</span> <span m="1760872">worth</span> <span m="1761187">about</span>
  <span m="1761503">half</span> <span m="1761818">a</span> <span m="1762133">million</span>
  <span m="1762448">dollars</span> <span m="1762764">at</span> <span m="1763079">that</span>
  <span m="1763394">time.</span></p><p><span m="1763710">But</span> <span m="1763923">it</span>
  <span m="1764136">was</span> <span m="1764349">like--</span> <span m="1764563">it</span>
  <span m="1764776">was</span> <span m="1764989">pretty</span> <span m="1765202">cool.</span>
  <span m="1765416">And</span> <span m="1765629">then</span> <span m="1765842">Greg</span>
  <span m="1766056">was</span> <span m="1766269">like,</span> <span m="1766482">wow,</span>
  <span m="1766695">I've</span> <span m="1766909">never</span> <span m="1767122">seen</span>
  <span m="1767335">that</span> <span m="1767549">much</span> <span m="1768179">money.</span>
  <span m="1768810">Yeah,</span> <span m="1769440">so</span> <span m="1770071">the</span>
  <span m="1770702">guy</span> <span m="1771332">who</span> <span m="1771963">posted</span>
  <span m="1772594">the</span> <span m="1773224">40,000</span> <span m="1773855">coins,</span>
  <span m="1774485">he's</span> <span m="1775116">called</span> <span m="1775747">loaded.</span>
  <span m="1776377">And</span> <span m="1777008">nobody</span> <span m="1777639">knows</span>
  <span m="1778000">who</span> <span m="1778361">he</span> <span m="1778722">is.</span>
  <span m="1779083">But</span> <span m="1779444">he</span> <span m="1779805">shows</span>
  <span m="1780166">up</span> <span m="1780527">from</span> <span m="1780889">time</span>
  <span m="1781250">to</span> <span m="1781611">time,</span> <span m="1781972">and</span>
  <span m="1782333">has</span> <span m="1782694">a</span> <span m="1783055">lot</span>
  <span m="1783416">of</span> <span m="1783777">money.</span></p><p><span m="1784139">So,</span>
  <span m="1784509">yeah,</span> <span m="1784879">then</span> <span m="1785249">Greg</span>
  <span m="1785619">made</span> <span m="1785989">a</span> <span m="1786359">transaction</span>
  <span m="1786730">with</span> <span m="1787100">Loaded.</span> <span m="1787470">I've</span>
  <span m="1787840">handled</span> <span m="1788210">pricey</span> <span m="1788580">assets</span>
  <span m="1788950">before,</span> <span m="1789321">the</span> <span m="1789786">most</span>
  <span m="1790252">I've</span> <span m="1790717">ever</span> <span m="1791183">moved</span>
  <span m="1791648">on</span> <span m="1792114">a</span> <span m="1792579">single</span>
  <span m="1793045">key</span> <span m="1793510">press.</span> <span m="1793976">So</span>
  <span m="1794441">it's</span> <span m="1794907">pretty</span> <span m="1795372">cool.</span>
  <span m="1795838">This</span> <span m="1796303">was</span> <span m="1796769">very</span>
  <span m="1797234">manual.</span></p><p><span m="1797700">That</span> <span m="1797985">was</span>
  <span m="1798270">on</span> <span m="1798555">a</span> <span m="1798840">message</span>
  <span m="1799126">board,</span> <span m="1799411">sort</span> <span m="1799696">of</span>
  <span m="1799981">goofing</span> <span m="1800267">around.</span> <span m="1800552">But</span>
  <span m="1800837">there's</span> <span m="1801122">no</span> <span m="1801408">risk.</span>
  <span m="1801693">You're</span> <span m="1801978">not</span> <span m="1802263">sending</span>
  <span m="1802549">money</span> <span m="1802857">to</span> <span m="1803166">someone,</span>
  <span m="1803475">and</span> <span m="1803784">then</span> <span m="1804092">getting</span>
  <span m="1804401">it</span> <span m="1804710">back.</span> <span m="1805019">You're</span>
  <span m="1805327">just</span> <span m="1805636">saying,</span> <span m="1805945">I'll</span>
  <span m="1806254">sign</span> <span m="1806562">off</span> <span m="1806871">on</span>
  <span m="1807180">this</span> <span m="1807489">transaction.</span> <span m="1807875">And</span>
  <span m="1808262">then</span> <span m="1808649">transactions</span> <span m="1809035">are</span>
  <span m="1809422">atomic.</span></p><p><span m="1809809">You</span> <span m="1810019">can't</span>
  <span m="1810230">say,</span> <span m="1810440">oh,</span> <span m="1810651">I'm</span>
  <span m="1810861">going</span> <span m="1811072">to</span> <span m="1811282">cut</span>
  <span m="1811493">off</span> <span m="1811704">this</span> <span m="1811914">bottom</span>
  <span m="1812125">part,</span> <span m="1812335">and</span> <span m="1812546">only</span>
  <span m="1812756">have</span> <span m="1812967">10</span> <span m="1813177">coins</span>
  <span m="1813388">going</span> <span m="1813599">in,</span> <span m="1813872">and</span>
  <span m="1814146">two</span> <span m="1814420">coins</span> <span m="1814694">come</span>
  <span m="1814968">up.</span> <span m="1815242">The</span> <span m="1815516">whole</span>
  <span m="1815790">transaction</span> <span m="1816064">is</span> <span m="1816337">the</span>
  <span m="1816611">thing</span> <span m="1816885">that</span> <span m="1817159">gets</span>
  <span m="1817433">signed.</span> <span m="1817707">OK,</span> <span m="1817981">so</span>
  <span m="1818255">what's</span> <span m="1818529">the</span> <span m="1818869">problem</span>
  <span m="1819209">with</span> <span m="1819549">this</span> <span m="1819889">model?</span></p><p><span
  m="1820229">Any</span> <span m="1820619">way</span> <span m="1821009">to</span>
  <span m="1821399">get</span> <span m="1821789">a</span> <span m="1822179">mapping</span>
  <span m="1822569">from</span> <span m="1822959">C</span> <span m="1823349">and</span>
  <span m="1823739">D,</span> <span m="1824129">to</span> <span m="1824519">A</span>
  <span m="1824909">and</span> <span m="1825299">B?</span> <span m="1825689">There's</span>
  <span m="1826079">one</span> <span m="1826469">really</span> <span m="1826859">obvious</span>
  <span m="1827249">one</span> <span m="1827639">on</span> <span m="1828029">this</span>
  <span m="1828445">screen.</span> <span m="1828862">It's</span> <span m="1829279">an</span>
  <span m="1829696">x,</span> <span m="1830113">right?</span> <span m="1830530">Yeah,</span>
  <span m="1830947">well,</span> <span m="1831364">gee,</span> <span m="1831781">I</span>
  <span m="1832197">think</span> <span m="1832614">it's</span> <span m="1833031">A</span>
  <span m="1833448">goes</span> <span m="1833865">to</span> <span m="1834282">D,</span>
  <span m="1834699">and</span> <span m="1835116">B</span> <span m="1835533">goes</span>
  <span m="1835950">to</span> <span m="1836287">C,</span> <span m="1836624">because</span>
  <span m="1836961">the</span> <span m="1837299">amounts</span> <span m="1837636">are</span>
  <span m="1837973">completely</span> <span m="1838310">different.</span> <span m="1838648">And,</span>
  <span m="1838985">actually,</span> <span m="1839322">we'll</span> <span m="1839659">talk</span>
  <span m="1839997">about</span> <span m="1840334">amounts</span> <span m="1840671">next</span>
  <span m="1841009">week.</span></p><p><span m="1842009">But</span> <span m="1842294">how</span>
  <span m="1842579">about</span> <span m="1842864">this?</span> <span m="1843149">Well,</span>
  <span m="1843434">you've</span> <span m="1843719">got</span> <span m="1844004">10</span>
  <span m="1844289">coins</span> <span m="1844574">coming</span> <span m="1844859">in,</span>
  <span m="1845144">two</span> <span m="1845429">coins</span> <span m="1845714">coming</span>
  <span m="1845999">in</span> <span m="1846284">here.</span> <span m="1846569">And</span>
  <span m="1846854">I've</span> <span m="1847139">got</span> <span m="1847550">address</span>
  <span m="1847962">C,</span> <span m="1848373">D,</span> <span m="1848785">E,</span>
  <span m="1849196">and</span> <span m="1849608">F,</span> <span m="1850019">1,</span>
  <span m="1850431">7,</span> <span m="1850842">1,</span> <span m="1851254">and</span>
  <span m="1851666">3.</span> <span m="1852077">Better,</span> <span m="1852489">maybe?</span>
  <span m="1852900">No,</span> <span m="1853312">nice</span> <span m="1853723">try.</span>
  <span m="1854135">You</span> <span m="1854546">can</span> <span m="1854958">still</span>
  <span m="1855370">easily.</span></p><p><span m="1856370">The</span> <span m="1856723">7</span>
  <span m="1857077">goes</span> <span m="1857430">to</span> <span m="1857784">the</span>
  <span m="1858138">10,</span> <span m="1858491">the</span> <span m="1858845">7</span>
  <span m="1859199">to</span> <span m="1859552">3,</span> <span m="1859906">the</span>
  <span m="1860260">1</span> <span m="1860613">and</span> <span m="1860967">1.</span>
  <span m="1861320">I</span> <span m="1861674">don't</span> <span m="1862028">think</span>
  <span m="1862381">there's</span> <span m="1862735">any</span> <span m="1863089">way</span>
  <span m="1863442">it</span> <span m="1863796">could</span> <span m="1864150">be</span>
  <span m="1864811">anything</span> <span m="1865473">else.</span> <span m="1866134">How</span>
  <span m="1866796">about</span> <span m="1867457">this?</span></p><p><span m="1868119">Address</span>
  <span m="1868327">C</span> <span m="1868536">has</span> <span m="1868745">two</span>
  <span m="1868954">coins.</span> <span m="1869163">Address</span> <span m="1869371">D</span>
  <span m="1869580">has</span> <span m="1869789">two</span> <span m="1869998">coins.</span>
  <span m="1870207">Address</span> <span m="1870416">E</span> <span m="1870624">has</span>
  <span m="1870833">eight</span> <span m="1871042">coins.</span> <span m="1871251">Well,</span>
  <span m="1871460">now,</span> <span m="1871669">that</span> <span m="1872123">actually</span>
  <span m="1872578">works,</span> <span m="1873033">right?</span> <span m="1873487">It's</span>
  <span m="1873942">not</span> <span m="1874397">clear</span> <span m="1874851">if</span>
  <span m="1875306">C</span> <span m="1875761">is</span> <span m="1876216">from</span>
  <span m="1876670">A</span> <span m="1877125">or</span> <span m="1877580">B,</span>
  <span m="1878034">same</span> <span m="1878489">with</span> <span m="1878944">D.</span></p><p><span
  m="1879399">These</span> <span m="1879754">two</span> <span m="1880110">have</span>
  <span m="1880465">some</span> <span m="1880821">anonymity,</span> <span m="1881176">in</span>
  <span m="1881532">that</span> <span m="1881887">you're</span> <span m="1882243">not</span>
  <span m="1882599">sure</span> <span m="1882954">which</span> <span m="1883310">user</span>
  <span m="1883665">it's</span> <span m="1884021">from.</span> <span m="1884376">E,</span>
  <span m="1884732">on</span> <span m="1885087">the</span> <span m="1885443">other</span>
  <span m="1885799">hand,</span> <span m="1886316">is</span> <span m="1886834">obviously</span>
  <span m="1887352">from</span> <span m="1887869">A.</span> <span m="1888387">But</span>
  <span m="1888905">B's</span> <span m="1889422">coins</span> <span m="1889940">are</span>
  <span m="1890458">now</span> <span m="1890976">sort</span> <span m="1891493">of--</span>
  <span m="1892011">the</span> <span m="1892529">anonymity</span> <span m="1893046">set</span>
  <span m="1893564">has</span> <span m="1894082">doubled.</span></p><p><span m="1894600">You</span>
  <span m="1894923">don't</span> <span m="1895247">know</span> <span m="1895571">whether</span>
  <span m="1895895">it's</span> <span m="1896218">C</span> <span m="1896542">or</span>
  <span m="1896866">D.</span> <span m="1897190">B's</span> <span m="1897513">address</span>
  <span m="1897837">is</span> <span m="1898161">now</span> <span m="1898485">unclear.</span></p><p><span
  m="1898809">So</span> <span m="1899190">that's</span> <span m="1899571">kind</span>
  <span m="1899952">of</span> <span m="1900333">cool.</span> <span m="1900714">How</span>
  <span m="1901095">do</span> <span m="1901476">we</span> <span m="1901857">scale</span>
  <span m="1902239">this?</span> <span m="1902620">Well,</span> <span m="1903001">have</span>
  <span m="1903382">more</span> <span m="1903763">users,</span> <span m="1904144">and</span>
  <span m="1904525">a</span> <span m="1904906">bigger</span> <span m="1905287">anonymity</span>
  <span m="1905669">set.</span> <span m="1906001">So</span> <span m="1906334">one</span>
  <span m="1906666">issue</span> <span m="1906999">with</span> <span m="1907332">this</span>
  <span m="1907664">is,</span> <span m="1907997">as</span> <span m="1908330">you</span>
  <span m="1908662">scale</span> <span m="1908995">to</span> <span m="1909327">more</span>
  <span m="1909660">users--</span> <span m="1909993">let's</span> <span m="1910325">say</span>
  <span m="1910658">you</span> <span m="1910991">do</span> <span m="1911323">10</span>
  <span m="1911656">different</span> <span m="1911989">users,</span> <span m="1912322">where</span>
  <span m="1912656">they</span> <span m="1912990">all</span> <span m="1913324">put</span>
  <span m="1913657">in</span> <span m="1913991">their</span> <span m="1914325">inputs.</span></p><p><span
  m="1914659">They</span> <span m="1914999">all</span> <span m="1915339">put</span>
  <span m="1915679">in</span> <span m="1916019">their</span> <span m="1916359">set</span>
  <span m="1916699">of</span> <span m="1917039">outputs.</span> <span m="1917379">And</span>
  <span m="1917719">now,</span> <span m="1918059">you've</span> <span m="1918399">got</span>
  <span m="1918739">this</span> <span m="1919079">big</span> <span m="1919419">transaction,</span>
  <span m="1919759">where</span> <span m="1920099">it's</span> <span m="1920374">hard</span>
  <span m="1920650">to</span> <span m="1920926">tell</span> <span m="1921202">what</span>
  <span m="1921478">the</span> <span m="1921754">mapping</span> <span m="1922030">is.</span>
  <span m="1922306">The</span> <span m="1922581">problem,</span> <span m="1922857">as</span>
  <span m="1923133">you</span> <span m="1923409">gain</span> <span m="1923685">numbers</span>
  <span m="1923961">of</span> <span m="1924237">inputs,</span> <span m="1924513">numbers</span>
  <span m="1924789">of</span> <span m="1925137">users,</span> <span m="1925485">the</span>
  <span m="1925833">users</span> <span m="1926181">themselves</span> <span m="1926529">know</span>
  <span m="1926877">the</span> <span m="1927225">mapping,</span> <span m="1927573">because</span>
  <span m="1927921">someone's</span> <span m="1928269">actually</span> <span m="1928617">doing</span>
  <span m="1928965">the,</span> <span m="1929313">I</span> <span m="1929661">put</span>
  <span m="1930009">in</span> <span m="1930356">my</span> <span m="1930703">thing,</span>
  <span m="1931050">you</span> <span m="1931398">put</span> <span m="1931745">in</span>
  <span m="1932092">yours.</span></p><p><span m="1932440">So</span> <span m="1932663">there's</span>
  <span m="1932886">a</span> <span m="1933110">user</span> <span m="1933333">that</span>
  <span m="1933557">knows</span> <span m="1933780">the</span> <span m="1934004">mapping.</span>
  <span m="1934227">And</span> <span m="1934451">they</span> <span m="1934674">can</span>
  <span m="1934898">leak</span> <span m="1935121">that</span> <span m="1935345">info.</span>
  <span m="1935568">And</span> <span m="1935792">that</span> <span m="1936015">hurts</span>
  <span m="1936239">the</span> <span m="1936969">anonymity.</span> <span m="1937700">So</span>
  <span m="1938431">maybe</span> <span m="1939162">just</span> <span m="1939892">the</span>
  <span m="1940623">transaction</span> <span m="1941354">graph</span> <span m="1942085">itself</span>
  <span m="1942816">won't</span> <span m="1943546">tell</span> <span m="1944277">you,</span>
  <span m="1945008">but</span> <span m="1945739">somebody</span> <span m="1946470">knows.</span></p><p><span
  m="1947470">And</span> <span m="1947819">they</span> <span m="1948169">can</span>
  <span m="1948519">reveal</span> <span m="1948869">that</span> <span m="1949219">at</span>
  <span m="1949569">a</span> <span m="1949919">later</span> <span m="1950269">date.</span>
  <span m="1950619">So</span> <span m="1950969">that's</span> <span m="1951319">not</span>
  <span m="1951669">good.</span> <span m="1952019">So</span> <span m="1952369">there's</span>
  <span m="1952719">a</span> <span m="1953069">really</span> <span m="1953419">cool</span>
  <span m="1953769">protocol</span> <span m="1954290">called</span> <span m="1954812">CoinShuffle,</span>
  <span m="1955334">so</span> <span m="1955855">pre-CoinJoin</span> <span m="1956377">messaging</span>
  <span m="1956899">to</span> <span m="1957420">shuffle</span> <span m="1957942">the</span>
  <span m="1958464">inputs</span> <span m="1958985">and</span> <span m="1959507">outputs.</span></p><p><span
  m="1960029">And</span> <span m="1960350">this</span> <span m="1960671">allows</span>
  <span m="1960992">you</span> <span m="1961313">to</span> <span m="1961634">have</span>
  <span m="1961955">10,</span> <span m="1962276">20,</span> <span m="1962597">30</span>
  <span m="1962918">different</span> <span m="1963239">people</span> <span m="1963560">doing</span>
  <span m="1963881">it.</span> <span m="1964202">And</span> <span m="1964523">if</span>
  <span m="1964844">at</span> <span m="1965165">least</span> <span m="1965486">two</span>
  <span m="1965807">participants</span> <span m="1966129">are</span> <span m="1966542">honest,</span>
  <span m="1966956">then</span> <span m="1967369">the</span> <span m="1967783">mapping</span>
  <span m="1968196">cannot</span> <span m="1968610">be</span> <span m="1969023">determined.</span>
  <span m="1969437">The</span> <span m="1969850">way</span> <span m="1970264">it</span>
  <span m="1970677">works--</span> <span m="1971091">this</span> <span m="1971504">is</span>
  <span m="1971918">super</span> <span m="1972331">quick,</span> <span m="1972745">because</span>
  <span m="1973159">I</span> <span m="1973884">don't</span> <span m="1974609">have</span>
  <span m="1975334">time.</span></p><p><span m="1976059">Everyone</span> <span m="1976323">has</span>
  <span m="1976587">their</span> <span m="1976852">inputs</span> <span m="1977116">that</span>
  <span m="1977380">they</span> <span m="1977645">want</span> <span m="1977909">to</span>
  <span m="1978174">put</span> <span m="1978438">into</span> <span m="1978702">the</span>
  <span m="1978967">transaction.</span> <span m="1979231">And</span> <span m="1979495">they</span>
  <span m="1979760">also</span> <span m="1980024">have</span> <span m="1980289">the</span>
  <span m="1980573">output</span> <span m="1980857">addresses</span> <span m="1981141">that</span>
  <span m="1981425">they</span> <span m="1981709">want</span> <span m="1981994">as</span>
  <span m="1982278">their</span> <span m="1982562">outputs.</span> <span m="1982846">So</span>
  <span m="1983130">they</span> <span m="1983414">make</span> <span m="1983699">a</span>
  <span m="1983983">new</span> <span m="1984267">set</span> <span m="1984551">of</span>
  <span m="1984835">public</span> <span m="1985120">keys</span> <span m="1985369">that</span>
  <span m="1985618">they're</span> <span m="1985867">not</span> <span m="1986116">going</span>
  <span m="1986365">to</span> <span m="1986614">use</span> <span m="1986863">on</span>
  <span m="1987112">bitcoin</span> <span m="1987361">at</span> <span m="1987610">all.</span></p><p><span
  m="1987859">They're</span> <span m="1988311">just</span> <span m="1988763">making</span>
  <span m="1989215">public</span> <span m="1989667">keys</span> <span m="1990119">for</span>
  <span m="1990571">encryption</span> <span m="1991023">purposes</span> <span m="1991475">for</span>
  <span m="1991927">this</span> <span m="1992379">game.</span> <span m="1992831">And</span>
  <span m="1993283">they</span> <span m="1993735">also</span> <span m="1994187">tell</span>
  <span m="1994639">everyone,</span> <span m="1994958">here's</span> <span m="1995277">my</span>
  <span m="1995597">inputs.</span> <span m="1995916">My</span> <span m="1996236">input</span>
  <span m="1996555">is</span> <span m="1996875">A.</span> <span m="1997194">My</span>
  <span m="1997514">input</span> <span m="1997833">is</span> <span m="1998152">B.</span>
  <span m="1998472">So</span> <span m="1998791">the</span> <span m="1999111">inputs</span>
  <span m="1999430">are</span> <span m="1999750">known</span> <span m="2000069">to</span>
  <span m="2000389">the</span> <span m="2000722">people</span> <span m="2001055">participating.</span></p><p><span
  m="2001389">And</span> <span m="2001759">then</span> <span m="2002130">the</span>
  <span m="2002501">idea</span> <span m="2002871">is,</span> <span m="2003242">OK,</span>
  <span m="2003613">I</span> <span m="2003983">know</span> <span m="2004354">everyone's</span>
  <span m="2004725">publicly</span> <span m="2005095">that</span> <span m="2005466">they've</span>
  <span m="2005837">given.</span> <span m="2006207">So</span> <span m="2006578">I</span>
  <span m="2006949">encrypt</span> <span m="2007320">my</span> <span m="2007644">output.</span>
  <span m="2007969">So</span> <span m="2008294">I've</span> <span m="2008619">got</span>
  <span m="2008944">an</span> <span m="2009269">input</span> <span m="2009594">I've</span>
  <span m="2009919">told</span> <span m="2010244">everyone.</span> <span m="2010569">I've</span>
  <span m="2010894">got</span> <span m="2011219">my</span> <span m="2011544">output.</span></p><p><span
  m="2011869">And</span> <span m="2012230">I</span> <span m="2012591">encrypt</span>
  <span m="2012953">that,</span> <span m="2013314">the</span> <span m="2013675">address</span>
  <span m="2014037">itself</span> <span m="2014398">and</span> <span m="2014759">the</span>
  <span m="2015121">amount,</span> <span m="2015482">with</span> <span m="2015843">everyone's</span>
  <span m="2016205">public</span> <span m="2016566">keys</span> <span m="2016927">sequentially.</span></p><p><span
  m="2017289">So,</span> <span m="2017596">for</span> <span m="2017904">example,</span>
  <span m="2018211">I</span> <span m="2018519">use</span> <span m="2018827">encryption</span>
  <span m="2019134">on</span> <span m="2019442">key</span> <span m="2019750">C</span>
  <span m="2020057">to</span> <span m="2020365">encrypt</span> <span m="2020673">the</span>
  <span m="2020980">thing</span> <span m="2021288">on</span> <span m="2021596">encryption</span>
  <span m="2021903">on</span> <span m="2022211">key</span> <span m="2022519">B,</span>
  <span m="2022898">encrypt</span> <span m="2023277">the</span> <span m="2023657">encryption</span>
  <span m="2024036">on</span> <span m="2024416">key</span> <span m="2024795">A</span>
  <span m="2025175">of</span> <span m="2025554">my</span> <span m="2025934">output.</span>
  <span m="2026313">And</span> <span m="2026692">then</span> <span m="2027072">I</span>
  <span m="2027451">hand</span> <span m="2027831">this</span> <span m="2028210">to</span>
  <span m="2028590">user</span> <span m="2028969">A.</span></p><p><span m="2029349">So</span>
  <span m="2029624">this</span> <span m="2029899">is</span> <span m="2030174">like</span>
  <span m="2030449">onion</span> <span m="2030724">routing,</span> <span m="2030999">sort</span>
  <span m="2031274">of</span> <span m="2031549">onion</span> <span m="2031824">encryption,</span>
  <span m="2032099">where</span> <span m="2032374">you</span> <span m="2032649">take</span>
  <span m="2032924">a</span> <span m="2033199">plaintext,</span> <span m="2033474">encrypt</span>
  <span m="2033750">it,</span> <span m="2034378">encrypt</span> <span m="2035006">it</span>
  <span m="2035634">again,</span> <span m="2036262">encrypt</span> <span m="2036890">it</span>
  <span m="2037518">again.</span> <span m="2038146">So</span> <span m="2038774">I</span>
  <span m="2039402">receive</span> <span m="2040030">these</span> <span m="2040658">encrypted</span>
  <span m="2041286">outputs.</span> <span m="2041914">I</span> <span m="2042542">shuffle</span>
  <span m="2043170">them.</span> <span m="2043461">I</span> <span m="2043753">receive</span>
  <span m="2044044">one</span> <span m="2044336">from</span> <span m="2044627">A,</span>
  <span m="2044919">one</span> <span m="2045211">from</span> <span m="2045502">B,</span>
  <span m="2045794">one</span> <span m="2046085">from</span> <span m="2046377">C.</span></p><p><span
  m="2046669">Actually,</span> <span m="2047021">I</span> <span m="2047373">receive</span>
  <span m="2047725">the</span> <span m="2048078">whole</span> <span m="2048430">set.</span>
  <span m="2048782">I</span> <span m="2049134">shuffle</span> <span m="2049487">the</span>
  <span m="2049839">order.</span> <span m="2050191">And</span> <span m="2050544">then</span>
  <span m="2050896">I</span> <span m="2051248">use</span> <span m="2051600">my</span>
  <span m="2051953">key</span> <span m="2052305">to</span> <span m="2052657">decrypt</span>
  <span m="2053010">one</span> <span m="2053325">layer.</span> <span m="2053640">It's</span>
  <span m="2053955">still</span> <span m="2054270">going</span> <span m="2054586">to</span>
  <span m="2054901">be</span> <span m="2055216">encrypted,</span> <span m="2055531">because</span>
  <span m="2055847">I</span> <span m="2056162">just</span> <span m="2056477">see,</span>
  <span m="2056792">here's</span> <span m="2057108">a</span> <span m="2057423">bunch</span>
  <span m="2057738">of</span> <span m="2058053">encrypted</span> <span m="2058369">data.</span></p><p><span
  m="2059369">I</span> <span m="2059590">decrypt</span> <span m="2059812">it.</span>
  <span m="2060034">It's</span> <span m="2060255">still</span> <span m="2060477">encrypted</span>
  <span m="2060699">with</span> <span m="2060920">the</span> <span m="2061142">next</span>
  <span m="2061364">person's</span> <span m="2061585">key.</span> <span m="2061807">And</span>
  <span m="2062029">then</span> <span m="2062250">I</span> <span m="2062472">hand</span>
  <span m="2062694">it</span> <span m="2062915">to</span> <span m="2063137">them,</span>
  <span m="2063359">and</span> <span m="2063765">they</span> <span m="2064172">shuffle,</span>
  <span m="2064579">and</span> <span m="2064985">decrypt.</span> <span m="2065392">So</span>
  <span m="2065799">the</span> <span m="2066205">final</span> <span m="2066612">user</span>
  <span m="2067019">gets</span> <span m="2067425">the</span> <span m="2067832">outputs.</span></p><p><span
  m="2068239">And</span> <span m="2068577">the</span> <span m="2068916">final</span>
  <span m="2069255">user--</span> <span m="2069594">so</span> <span m="2069933">in</span>
  <span m="2070272">this</span> <span m="2070611">case,</span> <span m="2070950">user</span>
  <span m="2071289">C,</span> <span m="2071627">can</span> <span m="2071966">decrypt.</span>
  <span m="2072305">And</span> <span m="2072644">now,</span> <span m="2072983">he's</span>
  <span m="2073322">got</span> <span m="2073661">my</span> <span m="2074000">output.</span></p><p><span
  m="2074339">But</span> <span m="2074733">it's</span> <span m="2075127">been</span>
  <span m="2075521">shuffled</span> <span m="2075915">around</span> <span m="2076309">with</span>
  <span m="2076703">everyone</span> <span m="2077097">else's</span> <span m="2077491">output,</span>
  <span m="2077885">at</span> <span m="2078279">every</span> <span m="2078673">step</span>
  <span m="2079067">of</span> <span m="2079461">the</span> <span m="2079855">way.</span></p><p><span
  m="2080250">So</span> <span m="2080552">they</span> <span m="2080855">can't</span>
  <span m="2081157">tell</span> <span m="2081460">who's</span> <span m="2081762">went</span>
  <span m="2082065">to</span> <span m="2082367">whom.</span> <span m="2082670">And</span>
  <span m="2082972">then</span> <span m="2083275">they</span> <span m="2083577">have</span>
  <span m="2083880">this</span> <span m="2084182">final</span> <span m="2084485">transaction,</span>
  <span m="2084787">which</span> <span m="2085090">has</span> <span m="2085430">all</span>
  <span m="2085770">the</span> <span m="2086110">outputs</span> <span m="2086450">in</span>
  <span m="2086790">some</span> <span m="2087130">random</span> <span m="2087470">order,</span>
  <span m="2087810">because</span> <span m="2088150">everyone</span> <span m="2088490">contributed</span>
  <span m="2088830">to</span> <span m="2089170">randomizing</span> <span m="2089510">the</span>
  <span m="2089864">order</span> <span m="2090218">of</span> <span m="2090572">the</span>
  <span m="2090926">outputs.</span> <span m="2091280">So</span> <span m="2091634">this</span>
  <span m="2091988">is</span> <span m="2092342">really</span> <span m="2092696">cool.</span></p><p><span
  m="2093050">As</span> <span m="2093337">long</span> <span m="2093625">as</span>
  <span m="2093912">two</span> <span m="2094200">parties</span> <span m="2094488">are</span>
  <span m="2094775">honest--</span> <span m="2095063">if</span> <span m="2095351">there's</span>
  <span m="2095638">only</span> <span m="2095926">one</span> <span m="2096214">honest</span>
  <span m="2096501">party,</span> <span m="2096789">it</span> <span m="2097077">doesn't</span>
  <span m="2097364">work,</span> <span m="2097652">because</span> <span m="2097940">then</span>
  <span m="2098399">every</span> <span m="2098858">dishonest</span> <span m="2099317">party</span>
  <span m="2099777">colludes,</span> <span m="2100236">and</span> <span m="2100695">says,</span>
  <span m="2101154">well,</span> <span m="2101614">we</span> <span m="2102073">know</span>
  <span m="2102532">everything</span> <span m="2102991">but</span> <span m="2103451">the</span>
  <span m="2103910">honest</span> <span m="2104369">party's</span> <span m="2104829">output.</span>
  <span m="2105296">So</span> <span m="2105763">we</span> <span m="2106230">can</span>
  <span m="2106697">figure</span> <span m="2107164">out</span> <span m="2107631">which</span>
  <span m="2108098">one</span> <span m="2108565">it</span> <span m="2109032">is.</span>
  <span m="2109499">But</span> <span m="2109966">if</span> <span m="2110433">there's</span>
  <span m="2110900">two</span> <span m="2111367">users</span> <span m="2111834">actually</span>
  <span m="2112301">doing</span> <span m="2112769">this,</span> <span m="2113044">then</span>
  <span m="2113320">you</span> <span m="2113596">can't</span> <span m="2113872">determine</span>
  <span m="2114148">the</span> <span m="2114424">order.</span></p><p><span m="2114700">So</span>
  <span m="2114986">that's</span> <span m="2115273">pretty</span> <span m="2115560">cool.</span>
  <span m="2115847">I</span> <span m="2116134">think</span> <span m="2116420">it's</span>
  <span m="2116707">being</span> <span m="2116994">used</span> <span m="2117281">for</span>
  <span m="2117568">Join</span> <span m="2117854">Market.</span> <span m="2118141">Do</span>
  <span m="2118428">they</span> <span m="2118715">use</span> <span m="2119002">something</span>
  <span m="2119289">like</span> <span m="2119839">this?</span> <span m="2120389">I</span>
  <span m="2120939">don't</span> <span m="2121489">know.</span></p><p><span m="2122040">So</span>
  <span m="2122423">there's</span> <span m="2122806">cool</span> <span m="2123190">techniques</span>
  <span m="2123573">for</span> <span m="2123956">this</span> <span m="2124340">kind</span>
  <span m="2124723">of.</span> <span m="2125106">Thing</span> <span m="2125490">OK,</span>
  <span m="2125873">real</span> <span m="2126256">world,</span> <span m="2126640">though,</span>
  <span m="2127023">some</span> <span m="2127406">people</span> <span m="2127790">use</span>
  <span m="2128164">this.</span> <span m="2128538">Join</span> <span m="2128912">Market</span>
  <span m="2129286">exists.</span> <span m="2129660">I</span> <span m="2130034">don't</span>
  <span m="2130408">know</span> <span m="2130782">how</span> <span m="2131156">popular</span>
  <span m="2131530">it</span> <span m="2131904">is.</span></p><p><span m="2132279">Problem,</span>
  <span m="2132624">which</span> <span m="2132970">people</span> <span m="2133316">use</span>
  <span m="2133662">this.</span> <span m="2134008">Who</span> <span m="2134354">uses</span>
  <span m="2134700">this?</span> <span m="2135046">It's</span> <span m="2135392">got</span>
  <span m="2135738">a</span> <span m="2136084">limited</span> <span m="2136430">anonymity</span>
  <span m="2136776">set</span> <span m="2137122">of</span> <span m="2137468">the</span>
  <span m="2137814">people</span> <span m="2138160">who</span> <span m="2138536">really</span>
  <span m="2138912">want</span> <span m="2139288">anonymity,</span> <span m="2139664">which</span>
  <span m="2140040">is</span> <span m="2140416">not</span> <span m="2140792">the</span>
  <span m="2141168">anonymity</span> <span m="2141544">set</span> <span m="2141920">the</span>
  <span m="2142296">people</span> <span m="2142672">who</span> <span m="2143048">want</span>
  <span m="2143424">anonymity</span> <span m="2143800">want,</span> <span m="2144131">which</span>
  <span m="2144463">is</span> <span m="2144794">kind</span> <span m="2145126">of</span>
  <span m="2145457">confusing.</span> <span m="2145789">But</span> <span m="2146120">the</span>
  <span m="2146452">idea</span> <span m="2146783">is,</span> <span m="2147115">I</span>
  <span m="2147446">don't</span> <span m="2147778">want</span> <span m="2148109">to</span>
  <span m="2148441">just</span> <span m="2148772">be</span> <span m="2149104">in</span>
  <span m="2149435">this</span> <span m="2149767">group</span> <span m="2150099">of</span>
  <span m="2150384">people</span> <span m="2150670">who</span> <span m="2150956">want</span>
  <span m="2151241">anonymity,</span> <span m="2151527">because</span> <span m="2151813">those</span>
  <span m="2152098">are</span> <span m="2152384">the</span> <span m="2152670">people</span>
  <span m="2152955">I</span> <span m="2153241">don't</span> <span m="2153527">want</span>
  <span m="2153812">to</span> <span m="2154098">be</span> <span m="2154384">associated</span>
  <span m="2154670">with.</span></p><p><span m="2155670">I</span> <span m="2156122">would</span>
  <span m="2156575">rather</span> <span m="2157028">associate</span> <span m="2157481">myself</span>
  <span m="2157934">with</span> <span m="2158387">the</span> <span m="2158840">people</span>
  <span m="2159292">who</span> <span m="2159745">don't</span> <span m="2160198">particularly</span>
  <span m="2160651">want</span> <span m="2161104">anonymity.</span> <span m="2161557">This</span>
  <span m="2162010">is</span> <span m="2162488">a</span> <span m="2162967">big</span>
  <span m="2163446">problem.</span> <span m="2163925">People</span> <span m="2164403">don't</span>
  <span m="2164882">care</span> <span m="2165361">about</span> <span m="2165840">privacy.</span>
  <span m="2166318">People</span> <span m="2166797">don't</span> <span m="2167276">want</span>
  <span m="2167755">to</span> <span m="2168233">do</span> <span m="2168712">these</span>
  <span m="2169191">kinds</span> <span m="2169670">of</span> <span m="2170170">things.</span></p><p><span
  m="2170670">And</span> <span m="2170983">this</span> <span m="2171296">costs</span>
  <span m="2171609">money</span> <span m="2171923">too,</span> <span m="2172236">in</span>
  <span m="2172549">this</span> <span m="2172862">case.</span> <span m="2173176">If</span>
  <span m="2173489">you're</span> <span m="2173802">doing</span> <span m="2174115">these</span>
  <span m="2174429">transactions,</span> <span m="2174742">this</span> <span m="2175055">isn't</span>
  <span m="2175369">really</span> <span m="2175705">a</span> <span m="2176041">payment.</span>
  <span m="2176377">This</span> <span m="2176713">is</span> <span m="2177049">just</span>
  <span m="2177385">superfluous</span> <span m="2177721">transaction</span> <span
  m="2178057">to</span> <span m="2178393">turn</span> <span m="2178729">your</span>
  <span m="2179065">money</span> <span m="2179401">around</span> <span m="2179737">to</span>
  <span m="2180073">get</span> <span m="2180410">some</span> <span m="2180780">more</span>
  <span m="2181150">privacy.</span> <span m="2181520">This</span> <span m="2181890">is</span>
  <span m="2182260">one</span> <span m="2182630">of</span> <span m="2183000">the</span>
  <span m="2183370">big</span> <span m="2183740">issues</span> <span m="2184110">with,</span>
  <span m="2184480">OK,</span> <span m="2184850">we</span> <span m="2185220">want</span>
  <span m="2185590">anonymity.</span></p><p><span m="2185960">But</span> <span m="2186367">if</span>
  <span m="2186775">anonymity</span> <span m="2187182">is</span> <span m="2187590">opt</span>
  <span m="2187998">in,</span> <span m="2188405">it's</span> <span m="2188813">not</span>
  <span m="2189221">very</span> <span m="2189628">useful,</span> <span m="2190036">because</span>
  <span m="2190444">then</span> <span m="2190851">it's</span> <span m="2191259">sort</span>
  <span m="2191667">of</span> <span m="2192074">like</span> <span m="2192482">Tor,</span>
  <span m="2192890">where</span> <span m="2193526">if</span> <span m="2194162">I'm</span>
  <span m="2194798">using</span> <span m="2195434">Tor,</span> <span m="2196070">everyone's</span>
  <span m="2196706">like,</span> <span m="2197342">why</span> <span m="2197978">are</span>
  <span m="2198614">you</span> <span m="2199250">using</span> <span m="2199886">Tor?</span>
  <span m="2200522">And</span> <span m="2201158">so</span> <span m="2201794">at</span>
  <span m="2202430">this</span> <span m="2203066">point,</span> <span m="2203702">encryption</span>
  <span m="2204339">is</span> <span m="2204768">now</span> <span m="2205197">sort</span>
  <span m="2205626">of</span> <span m="2206056">ubiquitous.</span> <span m="2206485">And</span>
  <span m="2206914">it's</span> <span m="2207343">like</span> <span m="2207773">the</span>
  <span m="2208202">standard.</span> <span m="2208631">But</span> <span m="2209060">yeah?</span></p><p><span
  m="2209490">AUDIENCE:</span> <span m="2209960">Given</span> <span m="2210431">that</span>
  <span m="2210901">most</span> <span m="2211372">transactions</span> <span m="2211843">happen</span>
  <span m="2212313">on</span> <span m="2212784">exchanges,</span> <span m="2213254">why</span>
  <span m="2213725">not</span> <span m="2214196">just</span> <span m="2214666">lobby</span>
  <span m="2215137">a</span> <span m="2215607">few</span> <span m="2216078">exchanges</span>
  <span m="2216549">to</span> <span m="2217051">try</span> <span m="2217553">and</span>
  <span m="2218055">implement</span> <span m="2218557">this?</span></p><p><span m="2219059">TADGE</span>
  <span m="2219369">DRYJA:</span> <span m="2219680">Well,</span> <span m="2219991">wait,</span>
  <span m="2220302">most</span> <span m="2220612">actual</span> <span m="2220923">bitcoin</span>
  <span m="2221234">transactions</span> <span m="2221545">are</span> <span m="2221856">in</span>
  <span m="2222166">and</span> <span m="2222477">out</span> <span m="2222788">from</span>
  <span m="2223099">exchanges?</span></p><p><span m="2223410">I</span> <span m="2223743">don't</span>
  <span m="2224076">know--</span> <span m="2224410">AUDIENCE:</span> <span m="2224660">If</span>
  <span m="2224910">that's</span> <span m="2225160">true.</span></p><p><span m="2225410">TADGE</span>
  <span m="2225618">DRYJA:</span> <span m="2225826">There's</span> <span m="2226035">a</span>
  <span m="2226243">lot.</span> <span m="2226451">But</span> <span m="2226660">I</span>
  <span m="2226868">don't</span> <span m="2227076">know</span> <span m="2227285">if</span>
  <span m="2227493">it's</span> <span m="2227701">a</span> <span m="2227910">majority.</span>
  <span m="2228118">I</span> <span m="2228326">think</span> <span m="2228535">it's</span>
  <span m="2228743">a</span> <span m="2228951">decent</span> <span m="2229160">percentage.</span>
  <span m="2229379">But</span> <span m="2229598">I</span> <span m="2229817">think</span>
  <span m="2230036">it's</span> <span m="2230256">less</span> <span m="2230475">than</span>
  <span m="2230694">half.</span> <span m="2230913">But,</span> <span m="2231133">yeah,</span>
  <span m="2231352">there's</span> <span m="2231571">a</span> <span m="2231790">lot.</span></p><p><span
  m="2232010">It'd</span> <span m="2232504">be</span> <span m="2232998">awesome.</span>
  <span m="2233492">So</span> <span m="2233986">exchanges</span> <span m="2234480">are</span>
  <span m="2234975">actually</span> <span m="2235469">uniquely</span> <span m="2235963">positioned,</span>
  <span m="2236457">where</span> <span m="2236951">something</span> <span m="2237445">like</span>
  <span m="2237940">CoinShuffle,</span> <span m="2238316">you</span> <span m="2238693">could</span>
  <span m="2239069">really</span> <span m="2239446">easily</span> <span m="2239822">do</span>
  <span m="2240199">an</span> <span m="2240575">oblivious</span> <span m="2240952">withdrawal.</span>
  <span m="2241328">Where</span> <span m="2241705">you</span> <span m="2242081">say,</span>
  <span m="2242458">I</span> <span m="2242834">want</span> <span m="2243211">to</span>
  <span m="2243455">withdraw</span> <span m="2243699">my</span> <span m="2243944">coins.</span>
  <span m="2244188">And</span> <span m="2244432">I'm</span> <span m="2244677">not</span>
  <span m="2244921">going</span> <span m="2245165">to</span> <span m="2245410">tell</span>
  <span m="2245654">you</span> <span m="2245898">where</span> <span m="2246143">to.</span>
  <span m="2246387">But</span> <span m="2246631">I'll</span> <span m="2246876">give</span>
  <span m="2247120">you</span> <span m="2247364">this</span> <span m="2247609">encrypted</span>
  <span m="2247906">thing</span> <span m="2248204">that</span> <span m="2248502">gets</span>
  <span m="2248800">shuffled</span> <span m="2249098">around</span> <span m="2249396">with</span>
  <span m="2249694">different</span> <span m="2249992">users.</span></p><p><span m="2250290">And</span>
  <span m="2250507">then</span> <span m="2250725">at</span> <span m="2250943">the</span>
  <span m="2251161">end,</span> <span m="2251378">I</span> <span m="2251596">sign</span>
  <span m="2251814">off</span> <span m="2252032">on</span> <span m="2252250">it.</span>
  <span m="2252467">And</span> <span m="2252685">the</span> <span m="2252903">exchange</span>
  <span m="2253121">can</span> <span m="2253338">say,</span> <span m="2253556">well,</span>
  <span m="2253774">we're</span> <span m="2253992">fulfilling</span> <span m="2254210">all</span>
  <span m="2254481">our</span> <span m="2254752">customers'</span> <span m="2255023">withdrawals.</span>
  <span m="2255295">But</span> <span m="2255566">we</span> <span m="2255837">don't</span>
  <span m="2256108">know</span> <span m="2256380">where</span> <span m="2256651">the</span>
  <span m="2256922">coins</span> <span m="2257193">are</span> <span m="2257465">going.</span>
  <span m="2257736">You</span> <span m="2258007">could</span> <span m="2258279">totally</span>
  <span m="2258720">do</span> <span m="2259162">that.</span> <span m="2259603">That's</span>
  <span m="2260045">not</span> <span m="2260486">a</span> <span m="2260928">conversation</span>
  <span m="2261369">that</span> <span m="2261811">happens</span> <span m="2262252">at</span>
  <span m="2262694">any</span> <span m="2263135">exchange.</span> <span m="2263577">Yeah?</span></p><p><span
  m="2264019">AUDIENCE:</span> <span m="2264416">I</span> <span m="2264814">also</span>
  <span m="2265212">think</span> <span m="2265609">that</span> <span m="2266007">the</span>
  <span m="2266405">bulk</span> <span m="2266802">of</span> <span m="2267200">exchanges</span>
  <span m="2267598">are</span> <span m="2267996">now</span> <span m="2268393">getting</span>
  <span m="2268791">caught</span> <span m="2269189">up</span> <span m="2269586">in</span>
  <span m="2269984">some</span> <span m="2270382">regulatory,</span> <span m="2270780">in</span>
  <span m="2271312">Japan,</span> <span m="2271845">soon</span> <span m="2272378">to</span>
  <span m="2272911">be</span> <span m="2273444">in</span> <span m="2273977">the</span>
  <span m="2274510">US,</span> <span m="2275043">for</span> <span m="2275575">know</span>
  <span m="2276108">your</span> <span m="2276641">customer,</span> <span m="2277174">anti-money</span>
  <span m="2277707">laundering.</span> <span m="2278240">So</span> <span m="2278773">for</span>
  <span m="2279306">the</span> <span m="2279839">exchange</span> <span m="2280245">business</span>
  <span m="2280652">model,</span> <span m="2281059">they're</span> <span m="2281465">going</span>
  <span m="2281872">to</span> <span m="2282279">have</span> <span m="2282686">to</span>
  <span m="2283092">give</span> <span m="2283499">this</span> <span m="2283906">Coinbase</span>
  <span m="2284313">to</span> <span m="2284719">the</span> <span m="2285126">FBI</span>
  <span m="2285533">some</span> <span m="2285940">data.</span></p><p><span m="2286940">TADGE</span>
  <span m="2287186">DRYJA:</span> <span m="2287433">Yeah,</span> <span m="2287680">and</span>
  <span m="2287927">whether</span> <span m="2288174">that</span> <span m="2288421">data</span>
  <span m="2288668">is,</span> <span m="2288915">here</span> <span m="2289161">is</span>
  <span m="2289408">this</span> <span m="2289655">user's</span> <span m="2289902">name,</span>
  <span m="2290149">and</span> <span m="2290396">address,</span> <span m="2290643">his</span>
  <span m="2290890">house</span> <span m="2291146">home</span> <span m="2291402">address,</span>
  <span m="2291658">and</span> <span m="2291914">his</span> <span m="2292170">social</span>
  <span m="2292426">security</span> <span m="2292682">number,</span> <span m="2292938">and</span>
  <span m="2293194">here's</span> <span m="2293450">what</span> <span m="2293706">he</span>
  <span m="2293962">bought</span> <span m="2294218">and</span> <span m="2294474">sold.</span></p><p><span
  m="2294730">Versus,</span> <span m="2295032">does</span> <span m="2295335">that</span>
  <span m="2295638">also</span> <span m="2295940">have,</span> <span m="2296243">and</span>
  <span m="2296546">here's</span> <span m="2296848">where</span> <span m="2297151">the</span>
  <span m="2297454">addresses</span> <span m="2297756">where</span> <span m="2298059">he</span>
  <span m="2298362">withdrew</span> <span m="2298664">his</span> <span m="2298967">coins</span>
  <span m="2299270">to?</span> <span m="2299683">I</span> <span m="2300097">don't</span>
  <span m="2300511">think</span> <span m="2300924">the</span> <span m="2301338">IRs--</span>
  <span m="2301752">the</span> <span m="2302165">IRS</span> <span m="2302579">thing,</span>
  <span m="2302993">I</span> <span m="2303406">think</span> <span m="2303820">it</span>
  <span m="2304234">was</span> <span m="2304647">mostly</span> <span m="2305061">we</span>
  <span m="2305475">want</span> <span m="2305888">to</span> <span m="2306302">get</span>
  <span m="2306716">people</span> <span m="2307130">for</span> <span m="2307430">not</span>
  <span m="2307730">reporting</span> <span m="2308030">their</span> <span m="2308330">gains.</span></p><p><span
  m="2308630">AUDIENCE:</span> <span m="2308841">That's</span> <span m="2309052">the</span>
  <span m="2309263">IRS</span> <span m="2309474">point,</span> <span m="2309685">but</span>
  <span m="2309896">the</span> <span m="2310107">other</span> <span m="2310318">part--</span>
  <span m="2310529">TADGE</span> <span m="2310779">DRYJA:</span> <span m="2311029">Right,</span>
  <span m="2311279">FinCEN.</span></p><p><span m="2311529">AUDIENCE:</span> <span
  m="2312016">Financial</span> <span m="2312504">Crimes</span> <span m="2312992">Unit,</span>
  <span m="2313480">FinCEN</span> <span m="2313968">would</span> <span m="2314456">want</span>
  <span m="2314944">the</span> <span m="2315432">addresses.</span></p><p><span m="2315920">TADGE</span>
  <span m="2316325">DRYJA:</span> <span m="2316730">FinCEN</span> <span m="2317135">would</span>
  <span m="2317540">want</span> <span m="2317945">to</span> <span m="2318350">map</span>
  <span m="2318755">bitcoin</span> <span m="2319160">addresses</span> <span m="2319565">to</span>
  <span m="2319970">human</span> <span m="2320375">names,</span> <span m="2320780">so</span>
  <span m="2321185">they</span> <span m="2321590">could</span> <span m="2321995">see</span>
  <span m="2322400">who</span> <span m="2322681">did</span> <span m="2322962">what.</span>
  <span m="2323243">IRS</span> <span m="2323524">just</span> <span m="2323805">wants</span>
  <span m="2324086">to</span> <span m="2324367">know</span> <span m="2324648">who</span>
  <span m="2324930">sold</span> <span m="2325211">and</span> <span m="2325492">didn't</span>
  <span m="2325773">report</span> <span m="2326054">gains.</span> <span m="2326335">By</span>
  <span m="2326616">the</span> <span m="2326897">way,</span> <span m="2327178">this</span>
  <span m="2327460">weekend,</span> <span m="2327915">if</span> <span m="2328371">you</span>
  <span m="2328827">sold</span> <span m="2329283">any</span> <span m="2329739">coins</span>
  <span m="2330195">last</span> <span m="2330651">year,</span> <span m="2331107">you</span>
  <span m="2331563">got</span> <span m="2332019">to</span> <span m="2332475">tell</span>
  <span m="2332931">the</span> <span m="2333387">IRS.</span> <span m="2333843">I've</span>
  <span m="2334299">actually</span> <span m="2334755">got</span> <span m="2335211">to</span>
  <span m="2335546">pay</span> <span m="2335881">a</span> <span m="2336217">little</span>
  <span m="2336552">bit</span> <span m="2336888">of</span> <span m="2337223">tax</span>
  <span m="2337559">on</span> <span m="2337894">that.</span></p><p><span m="2338230">Yeah,</span>
  <span m="2338664">so</span> <span m="2339099">anonymity</span> <span m="2339534">is</span>
  <span m="2339968">tricky.</span> <span m="2340403">Like,</span> <span m="2340838">you</span>
  <span m="2341272">could</span> <span m="2341707">try</span> <span m="2342142">to</span>
  <span m="2342576">go</span> <span m="2343011">through</span> <span m="2343446">exchanges,</span>
  <span m="2343880">probably</span> <span m="2344315">not</span> <span m="2344750">the</span>
  <span m="2345125">best.</span> <span m="2345501">They're</span> <span m="2345877">not</span>
  <span m="2346253">going</span> <span m="2346628">to</span> <span m="2347004">do</span>
  <span m="2347380">it.</span> <span m="2347756">It's</span> <span m="2348132">hard</span>
  <span m="2348507">to</span> <span m="2348883">do</span> <span m="2349259">even</span>
  <span m="2349635">research</span> <span m="2350011">on</span> <span m="2350386">this</span>
  <span m="2350762">kind</span> <span m="2351138">of</span> <span m="2351514">stuff</span>
  <span m="2351890">when</span> <span m="2352402">you're</span> <span m="2352915">a</span>
  <span m="2353427">company.</span></p><p><span m="2353940">There's</span> <span m="2354158">a</span>
  <span m="2354377">lot</span> <span m="2354596">of</span> <span m="2354815">sort</span>
  <span m="2355034">of</span> <span m="2355252">chilling</span> <span m="2355471">effects</span>
  <span m="2355690">and</span> <span m="2355909">stuff.</span> <span m="2356128">That's</span>
  <span m="2356347">sort</span> <span m="2356565">of</span> <span m="2356784">why</span>
  <span m="2357003">I</span> <span m="2357222">like</span> <span m="2357441">working</span>
  <span m="2357660">at</span> <span m="2358002">MIT,</span> <span m="2358345">in</span>
  <span m="2358687">that</span> <span m="2359030">if</span> <span m="2359372">I</span>
  <span m="2359715">want</span> <span m="2360057">to</span> <span m="2360400">research</span>
  <span m="2360742">crazy</span> <span m="2361085">anonymity</span> <span m="2361427">stuff,</span>
  <span m="2361770">totally</span> <span m="2362112">fine.</span> <span m="2362455">Whereas</span>
  <span m="2362797">if</span> <span m="2363140">I'm</span> <span m="2363519">working</span>
  <span m="2363898">at</span> <span m="2364277">a</span> <span m="2364657">VC-funded</span>
  <span m="2365036">company</span> <span m="2365415">in</span> <span m="2365794">San</span>
  <span m="2366174">Francisco,</span> <span m="2366553">and</span> <span m="2366932">I'm</span>
  <span m="2367311">like,</span> <span m="2367691">hey,</span> <span m="2368070">we're</span>
  <span m="2368449">making</span> <span m="2368829">these</span> <span m="2369214">anonymity</span>
  <span m="2369599">protocols.</span> <span m="2369985">Are</span> <span m="2370370">you</span>
  <span m="2370756">sure</span> <span m="2371141">you</span> <span m="2371527">want</span>
  <span m="2371912">to</span> <span m="2372298">do</span> <span m="2372683">it?</span></p><p><span
  m="2373069">It</span> <span m="2373613">can</span> <span m="2374157">be</span> <span
  m="2374701">an</span> <span m="2375245">awkward</span> <span m="2375789">conversation,</span>
  <span m="2376333">in</span> <span m="2376877">some</span> <span m="2377421">cases.</span>
  <span m="2377965">So</span> <span m="2378509">people</span> <span m="2379053">don't</span>
  <span m="2379597">care</span> <span m="2380141">about</span> <span m="2380685">privacy.</span></p><p><span
  m="2381230">It's</span> <span m="2381516">sort</span> <span m="2381802">of</span>
  <span m="2382088">an</span> <span m="2382374">externality.</span> <span m="2382660">If</span>
  <span m="2382947">you</span> <span m="2383233">say,</span> <span m="2383519">I'm</span>
  <span m="2383805">reusing</span> <span m="2384091">addresses.</span> <span m="2384378">But</span>
  <span m="2384664">that</span> <span m="2384950">only</span> <span m="2385236">hurts</span>
  <span m="2385522">my</span> <span m="2385809">privacy.</span></p><p><span m="2386809">That's</span>
  <span m="2387212">actually</span> <span m="2387616">not</span> <span m="2388019">true.</span>
  <span m="2388423">In</span> <span m="2388827">the</span> <span m="2389230">simplest</span>
  <span m="2389634">sense,</span> <span m="2390038">you're</span> <span m="2390441">reducing</span>
  <span m="2390845">the</span> <span m="2391249">anonymity</span> <span m="2391652">set</span>
  <span m="2392056">for</span> <span m="2392460">everyone</span> <span m="2392842">else.</span>
  <span m="2393224">So</span> <span m="2393606">if</span> <span m="2393988">I</span>
  <span m="2394370">I</span> <span m="2394753">say,</span> <span m="2395135">OK,</span>
  <span m="2395517">where</span> <span m="2395899">are</span> <span m="2396281">James'</span>
  <span m="2396663">coins?</span> <span m="2397046">Well,</span> <span m="2397428">I</span>
  <span m="2397810">know</span> <span m="2398192">they're</span> <span m="2398574">not</span>
  <span m="2398956">at</span> <span m="2399339">1Gmaxwell909,</span> <span m="2399915">because</span>
  <span m="2400492">that's</span> <span m="2401069">Greg</span> <span m="2401645">Maxwell's</span>
  <span m="2402222">coin.</span></p><p><span m="2402799">So</span> <span m="2403202">when</span>
  <span m="2403605">you</span> <span m="2404008">use</span> <span m="2404411">publicly</span>
  <span m="2404814">identifiable</span> <span m="2405217">addresses,</span> <span
  m="2405621">and</span> <span m="2406024">vanity</span> <span m="2406427">addresses,</span>
  <span m="2406830">you're</span> <span m="2407233">actually</span> <span m="2407636">reducing</span>
  <span m="2408040">the</span> <span m="2408319">anonymity</span> <span m="2408598">set</span>
  <span m="2408878">for</span> <span m="2409157">everyone</span> <span m="2409436">else.</span>
  <span m="2409716">It's</span> <span m="2409995">sort</span> <span m="2410274">of</span>
  <span m="2410554">an</span> <span m="2410833">externality,</span> <span m="2411112">where</span>
  <span m="2411392">the</span> <span m="2411671">people</span> <span m="2411950">who</span>
  <span m="2412230">say,</span> <span m="2412544">I</span> <span m="2412858">don't</span>
  <span m="2413173">care</span> <span m="2413487">about</span> <span m="2413802">privacy</span>
  <span m="2414116">are</span> <span m="2414431">not</span> <span m="2414745">paying</span>
  <span m="2415060">the</span> <span m="2415374">cost</span> <span m="2415688">of</span>
  <span m="2416003">harming</span> <span m="2416317">the</span> <span m="2416632">people</span>
  <span m="2416946">who</span> <span m="2417261">do</span> <span m="2417575">care</span>
  <span m="2417890">about</span> <span m="2418303">privacy.</span> <span m="2418717">So</span>
  <span m="2419131">this</span> <span m="2419545">is</span> <span m="2419958">a</span>
  <span m="2420372">tricky</span> <span m="2420786">problem.</span></p><p><span m="2421200">And</span>
  <span m="2421819">there's</span> <span m="2422438">no</span> <span m="2423058">solution.</span>
  <span m="2423677">But</span> <span m="2424296">one</span> <span m="2424916">cool</span>
  <span m="2425535">thing,</span> <span m="2426154">one</span> <span m="2426774">way</span>
  <span m="2427393">forward,</span> <span m="2428012">is,</span> <span m="2428632">well,</span>
  <span m="2429251">everyone</span> <span m="2429870">likes</span> <span m="2430490">cheaper</span>
  <span m="2431033">transactions.</span> <span m="2431576">Everyone</span> <span m="2432120">likes</span>
  <span m="2432663">saving</span> <span m="2433206">money.</span></p><p><span m="2433750">So</span>
  <span m="2434162">can</span> <span m="2434575">we</span> <span m="2434988">make</span>
  <span m="2435401">it</span> <span m="2435814">cheaper</span> <span m="2436227">to</span>
  <span m="2436640">improve</span> <span m="2437053">anonymity?</span> <span m="2437465">And</span>
  <span m="2437878">so</span> <span m="2438291">privacy</span> <span m="2438704">and</span>
  <span m="2439117">scalability,</span> <span m="2439530">in</span> <span m="2439943">some</span>
  <span m="2440356">cases,</span> <span m="2440769">are</span> <span m="2441140">at</span>
  <span m="2441512">odds.</span> <span m="2441883">So</span> <span m="2442255">in</span>
  <span m="2442626">things</span> <span m="2442998">like</span> <span m="2443370">ring</span>
  <span m="2443741">signatures,</span> <span m="2444113">which</span> <span m="2444484">I</span>
  <span m="2444856">don't</span> <span m="2445227">think</span> <span m="2445599">I</span>
  <span m="2445971">have</span> <span m="2446342">time</span> <span m="2446714">to</span>
  <span m="2447085">go--</span> <span m="2447457">but</span> <span m="2447829">Monero</span>
  <span m="2448180">is</span> <span m="2448531">a</span> <span m="2448883">sort</span>
  <span m="2449234">of</span> <span m="2449585">privacy</span> <span m="2449937">focused</span>
  <span m="2450288">currency</span> <span m="2450639">that</span> <span m="2450991">uses</span>
  <span m="2451342">ring</span> <span m="2451693">signatures</span> <span m="2452045">where,</span>
  <span m="2452396">where</span> <span m="2452747">you</span> <span m="2453099">can</span>
  <span m="2453401">point</span> <span m="2453703">to--</span> <span m="2454005">a</span>
  <span m="2454307">ring</span> <span m="2454609">signature</span> <span m="2454911">is,</span>
  <span m="2455214">I</span> <span m="2455516">can</span> <span m="2455818">point</span>
  <span m="2456120">to</span> <span m="2456422">two</span> <span m="2456724">public</span>
  <span m="2457026">keys.</span></p><p><span m="2457329">And</span> <span m="2457605">say,</span>
  <span m="2457881">OK,</span> <span m="2458157">there's</span> <span m="2458434">public</span>
  <span m="2458710">key</span> <span m="2458986">A</span> <span m="2459263">and</span>
  <span m="2459539">public</span> <span m="2459815">key</span> <span m="2460092">B.</span>
  <span m="2460368">I'm</span> <span m="2460644">signing</span> <span m="2460921">message</span>
  <span m="2461197">M</span> <span m="2461473">on</span> <span m="2461750">one</span>
  <span m="2462026">of</span> <span m="2462302">those</span> <span m="2462579">two</span>
  <span m="2462784">public</span> <span m="2462990">keys.</span> <span m="2463195">But</span>
  <span m="2463401">I'm</span> <span m="2463607">not</span> <span m="2463812">telling</span>
  <span m="2464018">you</span> <span m="2464223">which.</span> <span m="2464429">And</span>
  <span m="2464635">you</span> <span m="2464840">can</span> <span m="2465046">verify</span>
  <span m="2465251">that,</span> <span m="2465457">OK,</span> <span m="2465663">one</span>
  <span m="2465868">of</span> <span m="2466074">these</span> <span m="2466280">keys</span>
  <span m="2466700">signed.</span> <span m="2467120">But</span> <span m="2467540">I</span>
  <span m="2467960">don't</span> <span m="2468380">know</span> <span m="2468800">which.</span></p><p><span
  m="2469220">And</span> <span m="2469466">the</span> <span m="2469713">signer</span>
  <span m="2469960">had</span> <span m="2470207">to</span> <span m="2470454">have</span>
  <span m="2470701">one</span> <span m="2470947">of</span> <span m="2471194">the</span>
  <span m="2471441">private</span> <span m="2471688">keys,</span> <span m="2471935">or</span>
  <span m="2472182">both.</span> <span m="2472428">If</span> <span m="2472675">you</span>
  <span m="2472922">have</span> <span m="2473169">both</span> <span m="2473416">keys,</span>
  <span m="2473663">you</span> <span m="2473910">can</span> <span m="2474233">obviously</span>
  <span m="2474556">make</span> <span m="2474880">a</span> <span m="2475203">ring</span>
  <span m="2475526">signature.</span> <span m="2475850">It</span> <span m="2476173">doesn't</span>
  <span m="2476496">have</span> <span m="2476820">to</span> <span m="2477143">be</span>
  <span m="2477466">two.</span> <span m="2477790">It</span> <span m="2478113">can</span>
  <span m="2478436">5,</span> <span m="2478760">10,</span> <span m="2479083">whatever.</span>
  <span m="2479406">You</span> <span m="2479730">pick</span> <span m="2480006">a</span>
  <span m="2480282">bunch</span> <span m="2480558">of</span> <span m="2480835">public</span>
  <span m="2481111">keys,</span> <span m="2481387">sign</span> <span m="2481663">with</span>
  <span m="2481940">one</span> <span m="2482216">of</span> <span m="2482492">them.</span></p><p><span
  m="2482769">So</span> <span m="2483130">that's</span> <span m="2483492">pretty</span>
  <span m="2483854">cool.</span> <span m="2484216">That</span> <span m="2484578">expands</span>
  <span m="2484939">the</span> <span m="2485301">size</span> <span m="2485663">of</span>
  <span m="2486025">signatures,</span> <span m="2486387">I</span> <span m="2486749">believe,</span>
  <span m="2487110">with</span> <span m="2487472">like</span> <span m="2487834">0</span>
  <span m="2488196">of</span> <span m="2488558">n.</span></p><p><span m="2488920">So</span>
  <span m="2489196">if</span> <span m="2489472">you</span> <span m="2489748">have</span>
  <span m="2490025">10</span> <span m="2490301">keys</span> <span m="2490577">you're</span>
  <span m="2490854">pointing</span> <span m="2491130">to,</span> <span m="2491406">and</span>
  <span m="2491683">you</span> <span m="2491959">make</span> <span m="2492235">a</span>
  <span m="2492512">signature</span> <span m="2492788">on</span> <span m="2493064">one</span>
  <span m="2493341">of</span> <span m="2493617">them,</span> <span m="2493893">the</span>
  <span m="2494170">signature</span> <span m="2494797">actually</span> <span m="2495425">gets</span>
  <span m="2496052">bigger.</span></p><p><span m="2496680">So</span> <span m="2496994">for</span>
  <span m="2497308">Monero,</span> <span m="2497623">they</span> <span m="2497937">use</span>
  <span m="2498251">all</span> <span m="2498566">these</span> <span m="2498880">different</span>
  <span m="2499195">systems.</span> <span m="2499509">And</span> <span m="2499823">scalability</span>
  <span m="2500138">is</span> <span m="2500452">one</span> <span m="2500766">of</span>
  <span m="2501081">the</span> <span m="2501395">biggest</span> <span m="2501710">problems</span>
  <span m="2501940">with</span> <span m="2502170">there--</span> <span m="2502400">I</span>
  <span m="2502630">mean,</span> <span m="2502860">it's</span> <span m="2503090">a</span>
  <span m="2503320">problem</span> <span m="2503550">with</span> <span m="2503780">bitcoin</span>
  <span m="2504010">as</span> <span m="2504240">well.</span> <span m="2504470">It's</span>
  <span m="2504700">a</span> <span m="2504930">problem</span> <span m="2505160">with</span>
  <span m="2505390">everything.</span></p><p><span m="2506390">But</span> <span m="2506672">it's</span>
  <span m="2506954">even</span> <span m="2507236">worse</span> <span m="2507518">in</span>
  <span m="2507800">Monero</span> <span m="2508082">because</span> <span m="2508364">of</span>
  <span m="2508646">the</span> <span m="2508928">choices</span> <span m="2509210">and</span>
  <span m="2509492">the</span> <span m="2509774">different</span> <span m="2510056">algorithms</span>
  <span m="2510338">they</span> <span m="2510620">use.</span> <span m="2510960">So</span>
  <span m="2511300">in</span> <span m="2511640">some</span> <span m="2511980">cases,</span>
  <span m="2512320">privacy</span> <span m="2512660">and</span> <span m="2513000">scalability</span>
  <span m="2513340">are</span> <span m="2513680">at</span> <span m="2514020">odds.</span>
  <span m="2514360">But</span> <span m="2514700">in</span> <span m="2515040">some</span>
  <span m="2515380">cases,</span> <span m="2515720">it</span> <span m="2516060">works</span>
  <span m="2516400">together,</span> <span m="2516740">where</span> <span m="2517033">you</span>
  <span m="2517326">can</span> <span m="2517619">say,</span> <span m="2517912">we</span>
  <span m="2518205">just</span> <span m="2518498">want</span> <span m="2518791">to</span>
  <span m="2519085">have</span> <span m="2519378">less</span> <span m="2519671">information</span>
  <span m="2519964">about</span> <span m="2520257">these</span> <span m="2520550">transactions.</span>
  <span m="2520843">So</span> <span m="2521136">if</span> <span m="2521430">you</span>
  <span m="2521762">have</span> <span m="2522094">less</span> <span m="2522426">information</span>
  <span m="2522758">to</span> <span m="2523090">store,</span> <span m="2523422">there's</span>
  <span m="2523754">less</span> <span m="2524086">information</span> <span m="2524418">to</span>
  <span m="2524750">link</span> <span m="2525082">the</span> <span m="2525414">users</span>
  <span m="2525746">to</span> <span m="2526078">their</span> <span m="2526410">coins.</span></p><p><span
  m="2528190">So</span> <span m="2528710">an</span> <span m="2529231">idea</span>
  <span m="2529751">here</span> <span m="2530272">is</span> <span m="2530792">aggregate</span>
  <span m="2531313">signatures.</span> <span m="2531833">So,</span> <span m="2532354">currently,</span>
  <span m="2532875">when</span> <span m="2533395">you</span> <span m="2533916">sign,</span>
  <span m="2534436">you</span> <span m="2534957">have</span> <span m="2535477">this</span>
  <span m="2535998">input.</span></p><p><span m="2536519">And</span> <span m="2536857">you</span>
  <span m="2537196">say,</span> <span m="2537535">OK,</span> <span m="2537873">here's</span>
  <span m="2538212">user's</span> <span m="2538551">A</span> <span m="2538889">signature,</span>
  <span m="2539228">here's</span> <span m="2539567">user's</span> <span m="2539905">B</span>
  <span m="2540244">signature.</span> <span m="2540583">And</span> <span m="2540921">you're</span>
  <span m="2541260">doing</span> <span m="2541599">this</span> <span m="2542335">ineffective</span>
  <span m="2543071">CoinJoin</span> <span m="2543807">thing</span> <span m="2544543">here.</span></p><p><span
  m="2545279">The</span> <span m="2545598">goal</span> <span m="2545917">would</span>
  <span m="2546237">be</span> <span m="2546556">we</span> <span m="2546876">want</span>
  <span m="2547195">to</span> <span m="2547515">aggregate</span> <span m="2547834">these</span>
  <span m="2548154">signatures.</span> <span m="2548473">So</span> <span m="2548793">we</span>
  <span m="2549112">don't</span> <span m="2549432">have</span> <span m="2549751">a</span>
  <span m="2550071">signature</span> <span m="2550390">for</span> <span m="2550710">this</span>
  <span m="2551161">input.</span> <span m="2551612">We</span> <span m="2552063">just</span>
  <span m="2552514">have</span> <span m="2552965">a</span> <span m="2553417">single</span>
  <span m="2553868">signature</span> <span m="2554319">on</span> <span m="2554770">key</span>
  <span m="2555221">C,</span> <span m="2555672">which</span> <span m="2556124">is</span>
  <span m="2556575">just,</span> <span m="2557026">somehow,</span> <span m="2557477">the</span>
  <span m="2557928">combination</span> <span m="2558380">of</span> <span m="2559052">A</span>
  <span m="2559724">and</span> <span m="2560396">B's</span> <span m="2561068">signature.</span></p><p><span
  m="2561740">And</span> <span m="2562000">then</span> <span m="2562261">you</span>
  <span m="2562521">can</span> <span m="2562782">save</span> <span m="2563043">space,</span>
  <span m="2563303">because</span> <span m="2563564">there's</span> <span m="2563825">only</span>
  <span m="2564085">one</span> <span m="2564346">signature</span> <span m="2564606">that</span>
  <span m="2564867">stays</span> <span m="2565128">the</span> <span m="2565388">same</span>
  <span m="2565649">size,</span> <span m="2565910">but</span> <span m="2566221">still</span>
  <span m="2566532">prove</span> <span m="2566843">that</span> <span m="2567154">both</span>
  <span m="2567465">A--</span> <span m="2567776">so</span> <span m="2568087">this</span>
  <span m="2568398">is</span> <span m="2568709">not</span> <span m="2569020">a</span>
  <span m="2569331">ring</span> <span m="2569642">signature.</span> <span m="2569953">This</span>
  <span m="2570264">is</span> <span m="2570575">aggregate</span> <span m="2570886">is</span>
  <span m="2571197">A</span> <span m="2571508">and</span> <span m="2571819">B</span>
  <span m="2572182">both</span> <span m="2572545">signed,</span> <span m="2572909">and</span>
  <span m="2573272">produced</span> <span m="2573636">a</span> <span m="2573999">single</span>
  <span m="2574362">signature</span> <span m="2574726">together.</span> <span m="2575089">And</span>
  <span m="2575453">that</span> <span m="2575816">can</span> <span m="2576179">validate</span>
  <span m="2576543">the</span> <span m="2576906">whole</span> <span m="2577270">thing.</span></p><p><span
  m="2578270">OK,</span> <span m="2578691">so</span> <span m="2579113">how</span>
  <span m="2579534">can</span> <span m="2579956">we</span> <span m="2580378">make</span>
  <span m="2580799">this</span> <span m="2581221">signature?</span> <span m="2581642">We</span>
  <span m="2582064">know</span> <span m="2582486">pub</span> <span m="2582907">keys</span>
  <span m="2583329">A</span> <span m="2583750">and</span> <span m="2584172">B.</span>
  <span m="2584594">They're</span> <span m="2585015">both</span> <span m="2585437">signing</span>
  <span m="2585859">the</span> <span m="2586252">same</span> <span m="2586645">message,</span>
  <span m="2587038">which</span> <span m="2587431">is</span> <span m="2587824">really</span>
  <span m="2588217">important.</span> <span m="2588611">There's</span> <span m="2589004">other</span>
  <span m="2589397">terms</span> <span m="2589790">for</span> <span m="2590183">these</span>
  <span m="2590576">things.</span></p><p><span m="2590970">There's</span> <span m="2591461">multi-signatures,</span>
  <span m="2591953">aggregate</span> <span m="2592444">signatures,</span> <span m="2592936">key</span>
  <span m="2593427">aggregation.</span> <span m="2593919">And</span> <span m="2594411">no</span>
  <span m="2594902">one</span> <span m="2595394">agrees</span> <span m="2595885">on--</span>
  <span m="2596377">like,</span> <span m="2596869">I've</span> <span m="2597054">had</span>
  <span m="2597240">discussions</span> <span m="2597425">with</span> <span m="2597611">people.</span>
  <span m="2597797">And</span> <span m="2597982">I'm</span> <span m="2598168">like,</span>
  <span m="2598354">wait,</span> <span m="2598539">that's</span> <span m="2598725">what</span>
  <span m="2598910">you</span> <span m="2599096">call</span> <span m="2599282">it?</span>
  <span m="2599467">I</span> <span m="2599653">was</span> <span m="2599839">calling</span>
  <span m="2600179">it</span> <span m="2600520">something</span> <span m="2600861">else.</span>
  <span m="2601202">And</span> <span m="2601543">there's</span> <span m="2601884">not</span>
  <span m="2602225">really</span> <span m="2602566">good</span> <span m="2602907">terms</span>
  <span m="2603248">for</span> <span m="2603589">this.</span></p><p><span m="2603930">But</span>
  <span m="2604176">in</span> <span m="2604423">this</span> <span m="2604669">case,</span>
  <span m="2604916">what</span> <span m="2605163">we</span> <span m="2605409">want</span>
  <span m="2605656">is</span> <span m="2605902">we're</span> <span m="2606149">signing</span>
  <span m="2606396">the</span> <span m="2606642">same</span> <span m="2606889">message.</span>
  <span m="2607135">So</span> <span m="2607382">that</span> <span m="2607629">makes</span>
  <span m="2607875">it</span> <span m="2608122">easier.</span></p><p><span m="2608369">We're</span>
  <span m="2608796">not</span> <span m="2609224">trying</span> <span m="2609652">to</span>
  <span m="2610080">combine</span> <span m="2610508">different</span> <span m="2610936">signatures</span>
  <span m="2611364">on</span> <span m="2611791">different</span> <span m="2612219">messages</span>
  <span m="2612647">from</span> <span m="2613075">different</span> <span m="2613503">pub</span>
  <span m="2613931">keys</span> <span m="2614359">and</span> <span m="2614595">combine</span>
  <span m="2614832">it</span> <span m="2615069">to</span> <span m="2615305">the</span>
  <span m="2615542">same</span> <span m="2615779">signature.</span> <span m="2616016">That's</span>
  <span m="2616252">even</span> <span m="2616489">harder,</span> <span m="2616726">although</span>
  <span m="2616963">that</span> <span m="2617199">is</span> <span m="2617436">possible</span>
  <span m="2617673">in</span> <span m="2617910">some</span> <span m="2619040">ways.</span></p><p><span
  m="2620170">But</span> <span m="2620408">in</span> <span m="2620647">this</span>
  <span m="2620886">case,</span> <span m="2621125">A</span> <span m="2621364">and</span>
  <span m="2621602">B</span> <span m="2621841">are</span> <span m="2622080">signing</span>
  <span m="2622319">the</span> <span m="2622558">same</span> <span m="2622797">message</span>
  <span m="2623035">with</span> <span m="2623274">their</span> <span m="2623513">two</span>
  <span m="2623752">different</span> <span m="2623991">keys.</span></p><p><span m="2624230">And</span>
  <span m="2624549">they</span> <span m="2624869">need</span> <span m="2625189">one</span>
  <span m="2625509">signature.</span> <span m="2625829">And</span> <span m="2626149">the</span>
  <span m="2626469">signature</span> <span m="2626789">is</span> <span m="2627109">going</span>
  <span m="2627429">to</span> <span m="2627749">be</span> <span m="2628069">R</span>
  <span m="2628389">and</span> <span m="2628709">S.</span></p><p><span m="2629029">So</span>
  <span m="2629385">the</span> <span m="2629741">equation</span> <span m="2630097">that</span>
  <span m="2630453">we</span> <span m="2630810">had,</span> <span m="2631166">that</span>
  <span m="2631522">we've</span> <span m="2631878">done</span> <span m="2632235">a</span>
  <span m="2632591">couple</span> <span m="2632947">of</span> <span m="2633303">times,</span>
  <span m="2633659">the</span> <span m="2634016">signature</span> <span m="2634372">is</span>
  <span m="2634728">k,</span> <span m="2635084">some</span> <span m="2635441">random</span>
  <span m="2635877">number,</span> <span m="2636314">minus</span> <span m="2636751">the</span>
  <span m="2637188">hash</span> <span m="2637625">of</span> <span m="2638062">the</span>
  <span m="2638499">message,</span> <span m="2638936">and</span> <span m="2639373">k</span>
  <span m="2639810">times</span> <span m="2640247">gr,</span> <span m="2640684">times</span>
  <span m="2641121">the</span> <span m="2641558">private</span> <span m="2641995">key.</span>
  <span m="2642432">And</span> <span m="2642869">to</span> <span m="2643449">verify,</span>
  <span m="2644029">r</span> <span m="2644609">minus</span> <span m="2645189">the</span>
  <span m="2645769">hash</span> <span m="2646349">of</span> <span m="2646929">the</span>
  <span m="2647509">message</span> <span m="2648089">and</span> <span m="2648669">r,</span>
  <span m="2649249">times</span> <span m="2649829">the</span> <span m="2650409">public</span>
  <span m="2650989">key.</span> <span m="2651569">Now,</span> <span m="2652149">if</span>
  <span m="2652729">you</span> <span m="2653309">share</span> <span m="2653890">the</span>
  <span m="2654346">private</span> <span m="2654802">keys</span> <span m="2655258">with</span>
  <span m="2655714">each</span> <span m="2656170">other,</span> <span m="2656626">it's</span>
  <span m="2657082">kind</span> <span m="2657538">of</span> <span m="2657994">easy.</span></p><p><span
  m="2658450">Alice</span> <span m="2658669">just</span> <span m="2658888">say,</span>
  <span m="2659108">here's</span> <span m="2659327">my</span> <span m="2659547">key,</span>
  <span m="2659766">Bob.</span> <span m="2659985">And</span> <span m="2660205">then</span>
  <span m="2660424">the</span> <span m="2660644">Bob</span> <span m="2660863">can</span>
  <span m="2661082">compute</span> <span m="2661302">everything.</span> <span m="2661521">You</span>
  <span m="2661741">can</span> <span m="2661960">do</span> <span m="2662180">that</span>
  <span m="2662465">with</span> <span m="2662750">ECSA.</span> <span m="2663035">But</span>
  <span m="2663320">you</span> <span m="2663605">really</span> <span m="2663890">don't</span>
  <span m="2664175">want</span> <span m="2664460">to</span> <span m="2664745">share</span>
  <span m="2665030">private</span> <span m="2665315">keys,</span> <span m="2665600">because</span>
  <span m="2665885">as</span> <span m="2666170">soon</span> <span m="2666455">as</span>
  <span m="2666740">you</span> <span m="2667035">give</span> <span m="2667330">someone</span>
  <span m="2667626">else</span> <span m="2667921">your</span> <span m="2668216">private</span>
  <span m="2668512">key,</span> <span m="2668807">maybe</span> <span m="2669102">they</span>
  <span m="2669398">don't</span> <span m="2669693">sign</span> <span m="2669988">this</span>
  <span m="2670284">aggregate</span> <span m="2670579">signature</span> <span m="2670874">of</span>
  <span m="2671170">the</span> <span m="2671377">thing</span> <span m="2671584">you</span>
  <span m="2671791">want</span> <span m="2671998">to</span> <span m="2672206">sign,</span>
  <span m="2672413">they</span> <span m="2672620">sign</span> <span m="2672827">something</span>
  <span m="2673035">else,</span> <span m="2673242">giving</span> <span m="2673449">them</span>
  <span m="2673656">all</span> <span m="2673863">the</span> <span m="2674071">money.</span>
  <span m="2674278">So</span> <span m="2674485">you</span> <span m="2674692">want</span>
  <span m="2674900">to</span> <span m="2675506">be</span> <span m="2676113">involved</span>
  <span m="2676719">in</span> <span m="2677326">this</span> <span m="2677932">process.</span></p><p><span
  m="2678539">So</span> <span m="2679019">the</span> <span m="2679500">simplest</span>
  <span m="2679981">sort</span> <span m="2680461">of</span> <span m="2680942">multi-signature</span>
  <span m="2681423">system</span> <span m="2681904">for</span> <span m="2682384">Schnorr</span>
  <span m="2682865">signatures--</span> <span m="2683346">first,</span> <span m="2683826">you</span>
  <span m="2684307">want</span> <span m="2684788">to</span> <span m="2685269">share</span>
  <span m="2685811">an</span> <span m="2686353">r</span> <span m="2686895">value.</span>
  <span m="2687437">So</span> <span m="2687980">this</span> <span m="2688522">r</span>
  <span m="2689064">is</span> <span m="2689606">also</span> <span m="2690149">going</span>
  <span m="2690691">to</span> <span m="2691233">have</span> <span m="2691775">to</span>
  <span m="2692317">have</span> <span m="2692860">contributions</span> <span m="2693402">from</span>
  <span m="2693944">both</span> <span m="2694486">users.</span></p><p><span m="2695029">Who</span>
  <span m="2695307">comes</span> <span m="2695586">up</span> <span m="2695864">with</span>
  <span m="2696143">what</span> <span m="2696421">here?</span> <span m="2696700">If</span>
  <span m="2696978">c</span> <span m="2697257">is</span> <span m="2697535">the</span>
  <span m="2697814">combination</span> <span m="2698092">of</span> <span m="2698371">both</span>
  <span m="2698649">Alice</span> <span m="2698928">and</span> <span m="2699206">Bob's</span>
  <span m="2699485">public</span> <span m="2699763">key,</span> <span m="2700042">the</span>
  <span m="2700320">message</span> <span m="2700599">we</span> <span m="2701056">have</span>
  <span m="2701514">already</span> <span m="2701971">agreed</span> <span m="2702429">on.</span>
  <span m="2702886">But</span> <span m="2703344">this</span> <span m="2703801">r</span>
  <span m="2704259">value</span> <span m="2704716">is</span> <span m="2705174">the</span>
  <span m="2705631">question.</span></p><p><span m="2706089">So</span> <span m="2706444">the</span>
  <span m="2706800">idea</span> <span m="2707155">is,</span> <span m="2707511">Alice</span>
  <span m="2707866">comes</span> <span m="2708222">up</span> <span m="2708577">with</span>
  <span m="2708933">k</span> <span m="2709288">sub</span> <span m="2709644">a,</span>
  <span m="2710000">computes</span> <span m="2710355">r</span> <span m="2710711">sub</span>
  <span m="2711066">a,</span> <span m="2711422">and</span> <span m="2711777">gives</span>
  <span m="2712133">it</span> <span m="2712488">to</span> <span m="2712844">Bob.</span></p><p><span
  m="2713200">Bob</span> <span m="2713538">makes</span> <span m="2713877">k</span>
  <span m="2714215">sub</span> <span m="2714554">b,</span> <span m="2714892">computes</span>
  <span m="2715231">r</span> <span m="2715569">sub</span> <span m="2715908">b,</span>
  <span m="2716246">and</span> <span m="2716585">gives</span> <span m="2716923">that</span>
  <span m="2717262">to</span> <span m="2717600">Alice.</span> <span m="2717939">Then</span>
  <span m="2718277">both</span> <span m="2718616">of</span> <span m="2718954">them</span>
  <span m="2719293">can</span> <span m="2719631">say,</span> <span m="2719970">OK,</span>
  <span m="2720206">well,</span> <span m="2720442">we</span> <span m="2720678">know</span>
  <span m="2720914">the</span> <span m="2721150">real</span> <span m="2721387">r</span>
  <span m="2721623">that</span> <span m="2721859">we're</span> <span m="2722095">going</span>
  <span m="2722331">to</span> <span m="2722568">use</span> <span m="2722804">for</span>
  <span m="2723040">the</span> <span m="2723276">signature</span> <span m="2723512">is</span>
  <span m="2723749">the</span> <span m="2723985">sum</span> <span m="2724221">of</span>
  <span m="2724457">r</span> <span m="2724693">sub</span> <span m="2724930">a</span>
  <span m="2725130">and</span> <span m="2725330">r</span> <span m="2725530">sub</span>
  <span m="2725730">b.</span></p><p><span m="2725930">Then,</span> <span m="2726478">they</span>
  <span m="2727026">want</span> <span m="2727575">to</span> <span m="2728123">compute</span>
  <span m="2728671">their</span> <span m="2729220">own</span> <span m="2729768">s's.</span>
  <span m="2730316">So</span> <span m="2730865">for</span> <span m="2731413">Alice,</span>
  <span m="2731962">s</span> <span m="2732510">sub</span> <span m="2733058">a</span>
  <span m="2733607">is</span> <span m="2734155">going</span> <span m="2734703">to</span>
  <span m="2735252">be</span> <span m="2735800">equal</span> <span m="2736349">to</span>
  <span m="2736617">k</span> <span m="2736885">sub</span> <span m="2737153">a,</span>
  <span m="2737421">that</span> <span m="2737689">only</span> <span m="2737957">she</span>
  <span m="2738226">knows.</span> <span m="2738494">She</span> <span m="2738762">shared</span>
  <span m="2739030">r</span> <span m="2739298">sub</span> <span m="2739566">a,</span>
  <span m="2739834">but</span> <span m="2740103">not</span> <span m="2740371">k</span>
  <span m="2740639">sub</span> <span m="2740907">a,</span> <span m="2741175">with</span>
  <span m="2741443">Bob.</span> <span m="2741711">Minus</span> <span m="2741980">the</span>
  <span m="2742321">hash</span> <span m="2742663">of</span> <span m="2743005">the</span>
  <span m="2743347">message,</span> <span m="2743689">and</span> <span m="2744031">this</span>
  <span m="2744373">aggregate,</span> <span m="2744715">this</span> <span m="2745057">summed</span>
  <span m="2745399">r,</span> <span m="2745741">times</span> <span m="2746083">her</span>
  <span m="2746425">private</span> <span m="2746767">key.</span></p><p><span m="2747109">For</span>
  <span m="2747466">Bob,</span> <span m="2747823">it's</span> <span m="2748180">s</span>
  <span m="2748537">sub</span> <span m="2748894">b,</span> <span m="2749251">equals</span>
  <span m="2749608">k</span> <span m="2749965">sub</span> <span m="2750322">b,</span>
  <span m="2750679">minus</span> <span m="2751036">the</span> <span m="2751393">hash</span>
  <span m="2751750">of</span> <span m="2752107">the</span> <span m="2752464">message,</span>
  <span m="2752821">and</span> <span m="2753178">r,</span> <span m="2753535">times</span>
  <span m="2753892">little</span> <span m="2754250">be.</span> <span m="2754588">And</span>
  <span m="2754927">then</span> <span m="2755266">they</span> <span m="2755605">give</span>
  <span m="2755944">each</span> <span m="2756283">other</span> <span m="2756621">a</span>
  <span m="2756960">really--</span> <span m="2757299">only</span> <span m="2757638">one</span>
  <span m="2757977">party</span> <span m="2758316">needs</span> <span m="2758654">to</span>
  <span m="2758993">do</span> <span m="2759332">this,</span> <span m="2759671">right?</span>
  <span m="2760010">Either</span> <span m="2760349">Alice</span> <span m="2760617">gives</span>
  <span m="2760886">s</span> <span m="2761154">sub</span> <span m="2761423">a</span>
  <span m="2761692">to</span> <span m="2761960">Bob,</span> <span m="2762229">or</span>
  <span m="2762497">Bob</span> <span m="2762766">gives</span> <span m="2763035">s</span>
  <span m="2763303">sub</span> <span m="2763572">a</span> <span m="2763841">to</span>
  <span m="2764109">Alice.</span> <span m="2764378">But</span> <span m="2764646">they</span>
  <span m="2764915">don't</span> <span m="2765184">have</span> <span m="2765452">them</span>
  <span m="2765721">both</span> <span m="2765990">do</span> <span m="2766362">it,</span>
  <span m="2766734">because</span> <span m="2767106">then</span> <span m="2767478">the</span>
  <span m="2767851">final</span> <span m="2768223">step</span> <span m="2768595">is</span>
  <span m="2768967">you</span> <span m="2769340">just</span> <span m="2769712">add</span>
  <span m="2770084">the</span> <span m="2770456">s's.</span></p><p><span m="2770829">So</span>
  <span m="2771223">this</span> <span m="2771618">aggregate</span> <span m="2772013">s</span>
  <span m="2772408">is</span> <span m="2772803">s</span> <span m="2773197">sub</span>
  <span m="2773592">a,</span> <span m="2773987">plus</span> <span m="2774382">s</span>
  <span m="2774777">sub</span> <span m="2775172">b,</span> <span m="2775566">which</span>
  <span m="2775961">is</span> <span m="2776356">k</span> <span m="2776751">sub</span>
  <span m="2777146">a,</span> <span m="2777541">plus</span> <span m="2777935">k</span>
  <span m="2778330">sub</span> <span m="2778725">b,</span> <span m="2779120">minus</span>
  <span m="2779515">the</span> <span m="2779910">hash</span> <span m="2780238">of</span>
  <span m="2780566">m</span> <span m="2780894">and</span> <span m="2781222">r,</span>
  <span m="2781550">times</span> <span m="2781879">a,</span> <span m="2782207">minus</span>
  <span m="2782535">the</span> <span m="2782863">hash</span> <span m="2783191">of</span>
  <span m="2783520">m</span> <span m="2783848">and</span> <span m="2784176">r,</span>
  <span m="2784504">times</span> <span m="2784832">b,</span> <span m="2785160">which</span>
  <span m="2785489">is,</span> <span m="2785817">you</span> <span m="2786145">can</span>
  <span m="2786473">call</span> <span m="2786801">this</span> <span m="2787130">k.</span>
  <span m="2787435">That's</span> <span m="2787741">the</span> <span m="2788046">discrete</span>
  <span m="2788352">log</span> <span m="2788657">of</span> <span m="2788963">r,</span>
  <span m="2789268">because</span> <span m="2789574">they</span> <span m="2789880">summed</span>
  <span m="2790185">it.</span> <span m="2790491">And</span> <span m="2790796">then</span>
  <span m="2791102">you</span> <span m="2791407">can</span> <span m="2791713">factor</span>
  <span m="2792018">out</span> <span m="2792324">the</span> <span m="2792630">a</span>
  <span m="2793100">and</span> <span m="2793570">b</span> <span m="2794040">here.</span></p><p><span
  m="2794510">And</span> <span m="2794816">so</span> <span m="2795122">this</span>
  <span m="2795428">is</span> <span m="2795734">the</span> <span m="2796040">sum</span>
  <span m="2796346">of</span> <span m="2796652">their</span> <span m="2796958">private</span>
  <span m="2797264">keys.</span> <span m="2797570">This</span> <span m="2797876">is</span>
  <span m="2798182">the</span> <span m="2798488">sum</span> <span m="2798794">of</span>
  <span m="2799100">their</span> <span m="2799406">k</span> <span m="2799712">values.</span>
  <span m="2800018">And</span> <span m="2800324">then</span> <span m="2800630">this</span>
  <span m="2801260">single</span> <span m="2801890">verification</span> <span m="2802520">step</span>
  <span m="2803150">will</span> <span m="2803780">work.</span> <span m="2804410">And</span>
  <span m="2805040">that</span> <span m="2805670">works.</span> <span m="2806300">Awesome.</span>
  <span m="2806930">OK,</span> <span m="2807560">questions</span> <span m="2808190">about</span>
  <span m="2808820">this?</span></p><p><span m="2809450">Basically</span> <span m="2810207">make</span>
  <span m="2810964">sense?</span> <span m="2811721">There's</span> <span m="2812478">all</span>
  <span m="2813235">sorts</span> <span m="2813992">of</span> <span m="2814749">minefield</span>
  <span m="2815506">caveat</span> <span m="2816263">sort</span> <span m="2817020">of</span>
  <span m="2817777">watch</span> <span m="2818534">out</span> <span m="2819291">things.</span></p><p><span
  m="2820049">For</span> <span m="2820423">example,</span> <span m="2820797">if</span>
  <span m="2821171">they</span> <span m="2821545">learn</span> <span m="2821919">your</span>
  <span m="2822294">k</span> <span m="2822668">value,</span> <span m="2823042">they</span>
  <span m="2823416">will</span> <span m="2823790">learn</span> <span m="2824164">your</span>
  <span m="2824539">private</span> <span m="2824913">key,</span> <span m="2825287">once</span>
  <span m="2825661">they</span> <span m="2826035">get</span> <span m="2826410">this.</span>
  <span m="2827088">Normally,</span> <span m="2827767">you</span> <span m="2828446">make</span>
  <span m="2829125">deterministic</span> <span m="2829804">k</span> <span m="2830482">values,</span>
  <span m="2831161">where</span> <span m="2831840">you</span> <span m="2832519">compute</span>
  <span m="2833198">k</span> <span m="2833877">as</span> <span m="2834555">the</span>
  <span m="2835234">hash</span> <span m="2835913">of</span> <span m="2836592">your</span>
  <span m="2837271">message</span> <span m="2837950">being</span> <span m="2838220">signed</span>
  <span m="2838491">and</span> <span m="2838762">your</span> <span m="2839032">private</span>
  <span m="2839303">key.</span> <span m="2839574">That's</span> <span m="2839845">dangerous</span>
  <span m="2840115">to</span> <span m="2840386">do</span> <span m="2840657">in</span>
  <span m="2840928">this</span> <span m="2841198">case,</span> <span m="2841469">because</span>
  <span m="2841740">they</span> <span m="2842011">might</span> <span m="2842326">get</span>
  <span m="2842641">a</span> <span m="2842956">k</span> <span m="2843271">value</span>
  <span m="2843586">from</span> <span m="2843901">you,</span> <span m="2844217">and</span>
  <span m="2844532">then</span> <span m="2844847">give</span> <span m="2845162">you</span>
  <span m="2845477">a</span> <span m="2845792">different</span> <span m="2846108">r</span>
  <span m="2846423">value,</span> <span m="2846738">and</span> <span m="2847053">get</span>
  <span m="2847368">another</span> <span m="2847683">k</span> <span m="2847999">value,</span>
  <span m="2848322">and</span> <span m="2848646">find</span> <span m="2848969">your</span>
  <span m="2849293">private</span> <span m="2849616">key.</span></p><p><span m="2849940">So</span>
  <span m="2850386">there's</span> <span m="2850832">all</span> <span m="2851278">sorts</span>
  <span m="2851724">of</span> <span m="2852170">watch</span> <span m="2852616">out</span>
  <span m="2853062">things.</span> <span m="2853508">So</span> <span m="2853955">the</span>
  <span m="2854401">idea</span> <span m="2854847">is,</span> <span m="2855293">OK,</span>
  <span m="2855739">now</span> <span m="2856185">cool,</span> <span m="2856631">we've</span>
  <span m="2857077">got</span> <span m="2857523">output,</span> <span m="2857970">which</span>
  <span m="2858181">needs</span> <span m="2858393">a</span> <span m="2858605">signature</span>
  <span m="2858817">from</span> <span m="2859029">a.</span> <span m="2859240">We've</span>
  <span m="2859452">got</span> <span m="2859664">an</span> <span m="2859876">output</span>
  <span m="2860088">which</span> <span m="2860299">needs</span> <span m="2860511">a</span>
  <span m="2860723">signature</span> <span m="2860935">from</span> <span m="2861147">b.</span></p><p><span
  m="2861359">We'll</span> <span m="2861676">use</span> <span m="2861993">those</span>
  <span m="2862310">as</span> <span m="2862627">inputs,</span> <span m="2862944">and</span>
  <span m="2863261">just</span> <span m="2863578">have</span> <span m="2863895">this</span>
  <span m="2864213">sum</span> <span m="2864530">c</span> <span m="2864847">signature.</span>
  <span m="2865164">And</span> <span m="2865481">that</span> <span m="2865798">shows</span>
  <span m="2866115">that</span> <span m="2866432">both</span> <span m="2866750">parties</span>
  <span m="2867375">signed.</span></p><p><span m="2868000">So</span> <span m="2868552">we're</span>
  <span m="2869104">good.</span> <span m="2869657">Now,</span> <span m="2870209">we</span>
  <span m="2870761">have</span> <span m="2871314">way</span> <span m="2871866">less</span>
  <span m="2872418">data.</span> <span m="2872971">These</span> <span m="2873523">signatures</span>
  <span m="2874075">are</span> <span m="2874628">like</span> <span m="2875180">65</span>
  <span m="2875732">bytes.</span> <span m="2876285">So</span> <span m="2876837">instead</span>
  <span m="2877390">of</span> <span m="2877725">having</span> <span m="2878061">it</span>
  <span m="2878396">twice,</span> <span m="2878732">you</span> <span m="2879068">just</span>
  <span m="2879403">have</span> <span m="2879739">one</span> <span m="2880075">that</span>
  <span m="2880410">covers</span> <span m="2880746">the</span> <span m="2881082">whole</span>
  <span m="2881417">transaction.</span> <span m="2881753">Great.</span></p><p><span
  m="2882089">And</span> <span m="2882374">it</span> <span m="2882660">doesn't</span>
  <span m="2882946">have</span> <span m="2883232">to</span> <span m="2883517">be</span>
  <span m="2883803">two.</span> <span m="2884089">You</span> <span m="2884375">can</span>
  <span m="2884661">see</span> <span m="2884946">how</span> <span m="2885232">this</span>
  <span m="2885518">would</span> <span m="2885804">extend</span> <span m="2886090">to</span>
  <span m="2886375">three,</span> <span m="2886661">four,</span> <span m="2886947">or</span>
  <span m="2887233">five</span> <span m="2887519">different</span> <span m="2887879">people.</span>
  <span m="2888240">They</span> <span m="2888600">would</span> <span m="2888961">all</span>
  <span m="2889322">have</span> <span m="2889682">to</span> <span m="2890043">compute</span>
  <span m="2890404">their</span> <span m="2890764">own</span> <span m="2891125">k</span>
  <span m="2891486">value,</span> <span m="2891846">give</span> <span m="2892207">it</span>
  <span m="2892568">to</span> <span m="2892928">everyone</span> <span m="2893289">else,</span>
  <span m="2893650">everyone</span> <span m="2894055">computes</span> <span m="2894461">this</span>
  <span m="2894866">combined</span> <span m="2895272">r</span> <span m="2895678">value,</span>
  <span m="2896083">and</span> <span m="2896489">then</span> <span m="2896895">does</span>
  <span m="2897300">their</span> <span m="2897706">own</span> <span m="2898111">s's,</span>
  <span m="2898517">and</span> <span m="2898923">then</span> <span m="2899328">sums</span>
  <span m="2899734">them</span> <span m="2900140">all</span> <span m="2900536">up.</span>
  <span m="2900932">And</span> <span m="2901328">this</span> <span m="2901725">would</span>
  <span m="2902121">work</span> <span m="2902517">with</span> <span m="2902913">any</span>
  <span m="2903310">number</span> <span m="2903706">of</span> <span m="2904102">participants.</span></p><p><span
  m="2904499">Problem--</span> <span m="2904839">you've</span> <span m="2905180">got</span>
  <span m="2905521">a</span> <span m="2905861">bunch</span> <span m="2906202">of</span>
  <span m="2906543">coins,</span> <span m="2906883">that</span> <span m="2907224">40,000</span>
  <span m="2907565">coins</span> <span m="2907905">from</span> <span m="2908246">before.</span>
  <span m="2908587">And</span> <span m="2908927">then</span> <span m="2909268">one</span>
  <span m="2909609">day,</span> <span m="2909950">you</span> <span m="2910292">see,</span>
  <span m="2910635">wait,</span> <span m="2910977">I'm</span> <span m="2911320">user</span>
  <span m="2911662">A.</span> <span m="2912005">User</span> <span m="2912347">B</span>
  <span m="2912690">came</span> <span m="2913032">up</span> <span m="2913375">with</span>
  <span m="2913717">a</span> <span m="2914060">user</span> <span m="2914402">A</span>
  <span m="2914745">and</span> <span m="2915087">B</span> <span m="2915430">signature</span>
  <span m="2915772">and</span> <span m="2916115">sent</span> <span m="2916457">it</span>
  <span m="2916800">all</span> <span m="2917240">to</span> <span m="2917681">address</span>
  <span m="2918122">E.</span> <span m="2918562">I</span> <span m="2919003">never</span>
  <span m="2919444">signed</span> <span m="2919884">anything.</span> <span m="2920325">I</span>
  <span m="2920766">didn't</span> <span m="2921206">do</span> <span m="2921647">this</span>
  <span m="2922088">process</span> <span m="2922528">with</span> <span m="2922969">him.</span></p><p><span
  m="2923410">How</span> <span m="2923665">did</span> <span m="2923921">he</span>
  <span m="2924177">steal</span> <span m="2924433">all</span> <span m="2924689">my</span>
  <span m="2924945">coins?</span> <span m="2925201">This</span> <span m="2925457">is</span>
  <span m="2925713">bad.</span> <span m="2925969">So</span> <span m="2926225">any</span>
  <span m="2926481">idea</span> <span m="2926737">of</span> <span m="2926993">how</span>
  <span m="2927249">you</span> <span m="2927505">could</span> <span m="2927761">do</span>
  <span m="2928017">this</span> <span m="2928273">with</span> <span m="2928529">the</span>
  <span m="2929526">equations</span> <span m="2930523">we?</span></p><p><span m="2931520">OK,</span>
  <span m="2931936">so</span> <span m="2932352">what</span> <span m="2932768">you</span>
  <span m="2933185">do</span> <span m="2933601">is</span> <span m="2934017">you</span>
  <span m="2934434">say,</span> <span m="2934850">hey,</span> <span m="2935266">here's</span>
  <span m="2935683">key</span> <span m="2936099">A</span> <span m="2936515">on</span>
  <span m="2936932">the</span> <span m="2937348">network.</span> <span m="2937764">And,</span>
  <span m="2938181">normally,</span> <span m="2938597">you</span> <span m="2939013">see</span>
  <span m="2939430">pub</span> <span m="2939612">key</span> <span m="2939794">hashes.</span>
  <span m="2939976">But</span> <span m="2940159">a</span> <span m="2940341">lot</span>
  <span m="2940523">of</span> <span m="2940706">times</span> <span m="2940888">you</span>
  <span m="2941070">see</span> <span m="2941252">pub</span> <span m="2941435">keys.</span>
  <span m="2941617">And,</span> <span m="2941799">anyway,</span> <span m="2941982">you</span>
  <span m="2942164">definitely</span> <span m="2942346">see</span> <span m="2942529">the</span>
  <span m="2942869">pub</span> <span m="2943209">key</span> <span m="2943549">once</span>
  <span m="2943889">people</span> <span m="2944229">try</span> <span m="2944569">to</span>
  <span m="2944909">spend</span> <span m="2945249">it.</span></p><p><span m="2945589">So</span>
  <span m="2945784">maybe</span> <span m="2945980">you</span> <span m="2946176">have</span>
  <span m="2946372">to</span> <span m="2946567">do</span> <span m="2946763">this</span>
  <span m="2946959">quickly.</span> <span m="2947155">But</span> <span m="2947351">you</span>
  <span m="2947546">can</span> <span m="2947742">do</span> <span m="2947938">this</span>
  <span m="2948134">real</span> <span m="2948330">quick.</span> <span m="2948525">So</span>
  <span m="2948721">you</span> <span m="2948917">say,</span> <span m="2949113">OK,</span>
  <span m="2949309">I'm</span> <span m="2949647">going</span> <span m="2949985">to</span>
  <span m="2950323">make</span> <span m="2950661">Q,</span> <span m="2950999">a</span>
  <span m="2951337">random</span> <span m="2951675">private</span> <span m="2952013">key,</span>
  <span m="2952351">compute</span> <span m="2952689">q</span> <span m="2953027">times</span>
  <span m="2953365">G</span> <span m="2953703">to</span> <span m="2954041">be</span>
  <span m="2954379">big</span> <span m="2954717">Q.</span> <span m="2955055">And</span>
  <span m="2955393">then</span> <span m="2955731">I'll</span> <span m="2956069">compute</span>
  <span m="2956442">key</span> <span m="2956816">B,</span> <span m="2957190">which</span>
  <span m="2957564">is</span> <span m="2957937">q</span> <span m="2958311">minus</span>
  <span m="2958685">A.</span> <span m="2959059">Then</span> <span m="2959432">I</span>
  <span m="2959806">will</span> <span m="2960180">send</span> <span m="2960554">some</span>
  <span m="2960927">coins</span> <span m="2961301">to</span> <span m="2961675">B.</span></p><p><span
  m="2962049">And</span> <span m="2962312">now,</span> <span m="2962576">note</span>
  <span m="2962840">that</span> <span m="2963103">I</span> <span m="2963367">don't</span>
  <span m="2963631">know</span> <span m="2963894">the</span> <span m="2964158">private</span>
  <span m="2964422">key</span> <span m="2964685">for</span> <span m="2964949">B.</span>
  <span m="2965213">The</span> <span m="2965476">private</span> <span m="2965740">key</span>
  <span m="2966004">for</span> <span m="2966267">B</span> <span m="2966531">is</span>
  <span m="2966795">going</span> <span m="2967059">to</span> <span m="2967315">be</span>
  <span m="2967571">this</span> <span m="2967828">little</span> <span m="2968084">q,</span>
  <span m="2968340">minus</span> <span m="2968597">little</span> <span m="2968853">a.</span>
  <span m="2969109">I</span> <span m="2969366">don't</span> <span m="2969622">know</span>
  <span m="2969879">little</span> <span m="2970135">a,</span> <span m="2970391">so</span>
  <span m="2970648">I</span> <span m="2970904">don't</span> <span m="2971160">know</span>
  <span m="2971417">what</span> <span m="2971673">little</span> <span m="2971930">b</span>
  <span m="2972960">is.</span></p><p><span m="2973990">But</span> <span m="2974370">that's</span>
  <span m="2974751">OK.</span> <span m="2975131">I</span> <span m="2975512">don't</span>
  <span m="2975892">send</span> <span m="2976273">too</span> <span m="2976653">many</span>
  <span m="2977034">coins</span> <span m="2977414">to</span> <span m="2977795">key</span>
  <span m="2978175">b.</span> <span m="2978556">And,</span> <span m="2978936">anyway,</span>
  <span m="2979317">I'll</span> <span m="2979697">get</span> <span m="2980078">them</span>
  <span m="2980458">back.</span></p><p><span m="2980839">I</span> <span m="2981063">don't</span>
  <span m="2981287">know</span> <span m="2981512">b.</span> <span m="2981736">I</span>
  <span m="2981961">can't</span> <span m="2982185">sign</span> <span m="2982410">with</span>
  <span m="2982634">it.</span></p><p><span m="2982859">However,</span> <span m="2983179">I</span>
  <span m="2983499">want</span> <span m="2983819">to</span> <span m="2984139">spend</span>
  <span m="2984459">from</span> <span m="2984779">b</span> <span m="2985099">and</span>
  <span m="2985419">a</span> <span m="2985739">together.</span> <span m="2986059">I</span>
  <span m="2986379">don't</span> <span m="2986699">know</span> <span m="2987019">a</span>
  <span m="2987339">little</span> <span m="2987659">b.</span> <span m="2987979">I</span>
  <span m="2988299">don't</span> <span m="2988619">little</span> <span m="2988939">a.</span></p><p><span
  m="2989259">I</span> <span m="2989449">don't</span> <span m="2989639">know</span>
  <span m="2989829">the</span> <span m="2990019">private</span> <span m="2990209">key</span>
  <span m="2990399">for</span> <span m="2990589">either.</span> <span m="2990779">But</span>
  <span m="2990969">I</span> <span m="2991159">do</span> <span m="2991349">know</span>
  <span m="2991539">the</span> <span m="2991729">private</span> <span m="2991919">key</span>
  <span m="2992109">for</span> <span m="2992299">both,</span> <span m="2992489">which</span>
  <span m="2992680">is</span> <span m="2992972">sort</span> <span m="2993264">of</span>
  <span m="2993556">confusing.</span></p><p><span m="2993849">But</span> <span m="2994048">the</span>
  <span m="2994247">idea</span> <span m="2994446">is,</span> <span m="2994645">well,</span>
  <span m="2994844">C,</span> <span m="2995043">is</span> <span m="2995243">going</span>
  <span m="2995442">to</span> <span m="2995641">be</span> <span m="2995840">a</span>
  <span m="2996039">plus</span> <span m="2996238">b,</span> <span m="2996437">which</span>
  <span m="2996637">is</span> <span m="2996836">a,</span> <span m="2997035">plus</span>
  <span m="2997234">q</span> <span m="2997433">minus</span> <span m="2997632">a,</span>
  <span m="2997831">which</span> <span m="2998031">is</span> <span m="2998565">just</span>
  <span m="2999100">q.</span> <span m="2999635">So</span> <span m="3000169">in</span>
  <span m="3000704">this</span> <span m="3001239">case,</span> <span m="3001773">I</span>
  <span m="3002308">can</span> <span m="3002843">observe</span> <span m="3003377">a</span>
  <span m="3003912">key,</span> <span m="3004447">make</span> <span m="3004981">this</span>
  <span m="3005516">rogue</span> <span m="3006051">key,</span> <span m="3006585">and</span>
  <span m="3007120">then</span> <span m="3007655">spend</span> <span m="3008190">from</span>
  <span m="3008523">both</span> <span m="3008856">of</span> <span m="3009190">them,</span>
  <span m="3009523">without</span> <span m="3009856">knowing</span> <span m="3010190">the</span>
  <span m="3010523">actual</span> <span m="3010856">key</span> <span m="3011190">that</span>
  <span m="3011523">I</span> <span m="3011856">wanted</span> <span m="3012190">to</span>
  <span m="3012523">steal</span> <span m="3012856">from.</span> <span m="3013190">So</span>
  <span m="3013523">this</span> <span m="3013856">is</span> <span m="3014190">a</span>
  <span m="3014514">huge</span> <span m="3014839">problem.</span> <span m="3015163">You</span>
  <span m="3015488">can't</span> <span m="3015813">have</span> <span m="3016137">this.</span>
  <span m="3016462">This</span> <span m="3016786">would</span> <span m="3017111">make</span>
  <span m="3017436">signature</span> <span m="3017760">aggregation</span> <span m="3018085">completely</span>
  <span m="3018410">insecure.</span> <span m="3019419">What</span> <span m="3020429">are</span>
  <span m="3021439">some</span> <span m="3022449">ideas</span> <span m="3023459">of</span>
  <span m="3024469">how</span> <span m="3025479">to</span> <span m="3026489">fix</span>
  <span m="3027499">that?</span></p><p><span m="3028509">So</span> <span m="3028892">the</span>
  <span m="3029275">interesting</span> <span m="3029659">thing</span> <span m="3030042">is</span>
  <span m="3030425">in</span> <span m="3030809">all</span> <span m="3031192">the</span>
  <span m="3031575">literature</span> <span m="3031959">about</span> <span m="3032342">multi-signature,</span>
  <span m="3032725">this</span> <span m="3033109">problem</span> <span m="3033492">sort</span>
  <span m="3033875">of</span> <span m="3034259">still</span> <span m="3034562">persists.</span>
  <span m="3034865">And</span> <span m="3035169">the</span> <span m="3035472">new</span>
  <span m="3035775">papers</span> <span m="3036079">about</span> <span m="3036382">how</span>
  <span m="3036686">to</span> <span m="3036989">use</span> <span m="3037292">this</span>
  <span m="3037596">in</span> <span m="3037899">bitcoin</span> <span m="3038203">are</span>
  <span m="3038506">the</span> <span m="3038809">ones</span> <span m="3039113">that</span>
  <span m="3039416">are</span> <span m="3039720">actually</span> <span m="3040208">addressing</span>
  <span m="3040697">it.</span> <span m="3041186">So</span> <span m="3041674">the</span>
  <span m="3042163">general</span> <span m="3042652">idea</span> <span m="3043140">was,</span>
  <span m="3043629">well,</span> <span m="3044118">make</span> <span m="3044606">b</span>
  <span m="3045095">sign.</span> <span m="3045584">Make</span> <span m="3046072">b</span>
  <span m="3046561">prove</span> <span m="3047050">that</span> <span m="3047539">he</span>
  <span m="3047910">actually</span> <span m="3048282">can</span> <span m="3048653">sign</span>
  <span m="3049025">with</span> <span m="3049396">key</span> <span m="3049768">b.</span></p><p><span
  m="3050140">Before</span> <span m="3050405">you</span> <span m="3050671">start</span>
  <span m="3050936">doing</span> <span m="3051202">these</span> <span m="3051468">things,</span>
  <span m="3051733">have</span> <span m="3051999">Alice</span> <span m="3052265">and</span>
  <span m="3052530">Bob</span> <span m="3052796">talk</span> <span m="3053061">to</span>
  <span m="3053327">each</span> <span m="3053593">other.</span> <span m="3053858">And</span>
  <span m="3054124">Bob</span> <span m="3054390">says,</span> <span m="3054636">OK,</span>
  <span m="3054882">here's</span> <span m="3055129">a</span> <span m="3055375">signature</span>
  <span m="3055622">with</span> <span m="3055868">key</span> <span m="3056114">b.</span>
  <span m="3056361">And</span> <span m="3056607">Alice</span> <span m="3056854">says,</span>
  <span m="3057100">OK,</span> <span m="3057346">here's</span> <span m="3057593">a</span>
  <span m="3057839">signature</span> <span m="3058086">with</span> <span m="3058332">key</span>
  <span m="3058579">a.</span> <span m="3058822">And,</span> <span m="3059065">now</span>
  <span m="3059308">you've</span> <span m="3059551">proven</span> <span m="3059794">that</span>
  <span m="3060038">they</span> <span m="3060281">actually</span> <span m="3060524">can</span>
  <span m="3060767">sign,</span> <span m="3061010">and</span> <span m="3061254">they're</span>
  <span m="3061497">not</span> <span m="3061740">doing</span> <span m="3061983">these</span>
  <span m="3062226">kinds</span> <span m="3062470">of</span> <span m="3063306">rogue</span>
  <span m="3064143">attacks.</span></p><p><span m="3064980">So</span> <span m="3065309">that's</span>
  <span m="3065638">the</span> <span m="3065968">straight</span> <span m="3066297">straightforward</span>
  <span m="3066626">way</span> <span m="3066956">to</span> <span m="3067285">do</span>
  <span m="3067614">it,</span> <span m="3067944">where,</span> <span m="3068273">OK,</span>
  <span m="3068602">if</span> <span m="3068932">you</span> <span m="3069261">don't</span>
  <span m="3069590">know</span> <span m="3069920">b</span> <span m="3070249">and</span>
  <span m="3070579">can't</span> <span m="3070928">sign,</span> <span m="3071277">we're</span>
  <span m="3071626">not</span> <span m="3071975">going</span> <span m="3072325">to</span>
  <span m="3072674">continue</span> <span m="3073023">with</span> <span m="3073372">this</span>
  <span m="3073722">process.</span> <span m="3074071">That's</span> <span m="3074420">interactive,</span>
  <span m="3074769">though.</span></p><p><span m="3075119">So</span> <span m="3075419">make</span>
  <span m="3075720">b</span> <span m="3076021">sign</span> <span m="3076321">a</span>
  <span m="3076622">message</span> <span m="3076923">before</span> <span m="3077223">combining</span>
  <span m="3077524">keys.</span> <span m="3077825">Easy,</span> <span m="3078125">that's</span>
  <span m="3078426">what</span> <span m="3078727">people</span> <span m="3079027">sort</span>
  <span m="3079328">of</span> <span m="3079629">thought</span> <span m="3079930">about</span>
  <span m="3080533">for</span> <span m="3081136">years.</span></p><p><span m="3081740">But</span>
  <span m="3081949">the</span> <span m="3082158">whole</span> <span m="3082368">point</span>
  <span m="3082577">here</span> <span m="3082787">is</span> <span m="3082996">to</span>
  <span m="3083206">aggregate</span> <span m="3083415">signatures.</span> <span m="3083625">And</span>
  <span m="3083834">so</span> <span m="3084044">if</span> <span m="3084253">you</span>
  <span m="3084463">require</span> <span m="3084672">b</span> <span m="3084882">to</span>
  <span m="3085091">create</span> <span m="3085301">a</span> <span m="3085510">signature</span>
  <span m="3085720">and</span> <span m="3086098">post</span> <span m="3086476">it</span>
  <span m="3086854">into</span> <span m="3087232">the</span> <span m="3087610">transaction,</span>
  <span m="3087988">you've</span> <span m="3088366">just</span> <span m="3088745">eliminated</span>
  <span m="3089123">all</span> <span m="3089501">the</span> <span m="3089879">gains,</span>
  <span m="3090257">all</span> <span m="3090635">the</span> <span m="3091013">space</span>
  <span m="3091391">saving,</span> <span m="3091770">for</span> <span m="3092095">this</span>
  <span m="3092421">technique.</span> <span m="3092747">So</span> <span m="3093072">we</span>
  <span m="3093398">can't</span> <span m="3093724">have</span> <span m="3094050">that.</span>
  <span m="3094375">We</span> <span m="3094701">want</span> <span m="3095027">it</span>
  <span m="3095352">to</span> <span m="3095678">be</span> <span m="3096004">non-interactive.</span></p><p><span
  m="3096330">We</span> <span m="3096829">want</span> <span m="3097329">any</span>
  <span m="3097829">existing</span> <span m="3098329">keys</span> <span m="3098829">to</span>
  <span m="3099329">be</span> <span m="3099829">usable</span> <span m="3100329">in</span>
  <span m="3100829">this</span> <span m="3101329">system,</span> <span m="3101829">without</span>
  <span m="3102329">pre-committing</span> <span m="3102829">to</span> <span m="3103329">anything.</span></p><p><span
  m="3103829">You</span> <span m="3104247">can</span> <span m="3104666">also</span>
  <span m="3105084">make</span> <span m="3105503">it</span> <span m="3105922">interactive,</span>
  <span m="3106340">where--</span> <span m="3106759">well,</span> <span m="3107178">anyway,</span>
  <span m="3107596">there's</span> <span m="3108015">actually</span> <span m="3108434">a</span>
  <span m="3108852">better</span> <span m="3109271">way</span> <span m="3109690">to</span>
  <span m="3110079">do</span> <span m="3110468">it.</span> <span m="3110857">You</span>
  <span m="3111246">de-linearize</span> <span m="3111635">the</span> <span m="3112024">signatures.</span>
  <span m="3112413">So</span> <span m="3112802">you</span> <span m="3113191">redefine</span>
  <span m="3113580">the</span> <span m="3113969">signatures.</span></p><p><span m="3114359">You</span>
  <span m="3114723">still</span> <span m="3115087">send</span> <span m="3115451">to,</span>
  <span m="3115815">for</span> <span m="3116180">example,</span> <span m="3116544">key</span>
  <span m="3116908">a</span> <span m="3117272">or</span> <span m="3117636">key</span>
  <span m="3118001">b.</span> <span m="3118365">Your</span> <span m="3118729">outputs</span>
  <span m="3119093">are</span> <span m="3119457">still</span> <span m="3119822">pub</span>
  <span m="3120186">keys.</span> <span m="3120550">But</span> <span m="3120914">when</span>
  <span m="3121279">you</span> <span m="3121684">require</span> <span m="3122089">a</span>
  <span m="3122495">signature,</span> <span m="3122900">you</span> <span m="3123305">don't</span>
  <span m="3123711">require</span> <span m="3124116">a</span> <span m="3124521">signature</span>
  <span m="3124927">from</span> <span m="3125332">that</span> <span m="3125737">pub</span>
  <span m="3126143">key.</span> <span m="3126548">You</span> <span m="3126953">require</span>
  <span m="3127359">a</span> <span m="3127699">signature</span> <span m="3128040">from</span>
  <span m="3128381">that</span> <span m="3128722">pub</span> <span m="3129063">key,</span>
  <span m="3129404">times</span> <span m="3129744">the</span> <span m="3130085">hash</span>
  <span m="3130426">of</span> <span m="3130767">that</span> <span m="3131108">pub</span>
  <span m="3131449">key.</span></p><p><span m="3131790">So</span> <span m="3132110">you</span>
  <span m="3132430">say,</span> <span m="3132750">OK,</span> <span m="3133070">I'm</span>
  <span m="3133390">sending</span> <span m="3133710">to</span> <span m="3134030">a.</span>
  <span m="3134350">But</span> <span m="3134670">when</span> <span m="3134990">normally</span>
  <span m="3135310">I</span> <span m="3135630">have</span> <span m="3135950">sig</span>
  <span m="3136270">a,</span> <span m="3136590">signature</span> <span m="3136910">from</span>
  <span m="3137230">key</span> <span m="3137550">a.</span> <span m="3138146">Instead,</span>
  <span m="3138743">I</span> <span m="3139340">say,</span> <span m="3139937">no,</span>
  <span m="3140534">I</span> <span m="3141131">want</span> <span m="3141728">a</span>
  <span m="3142325">signature</span> <span m="3142922">from</span> <span m="3143518">a,</span>
  <span m="3144115">times</span> <span m="3144712">the</span> <span m="3145309">hash</span>
  <span m="3145906">of</span> <span m="3146503">a.</span> <span m="3147100">So</span>
  <span m="3147697">anyone</span> <span m="3148294">who</span> <span m="3148891">knows</span>
  <span m="3149242">the</span> <span m="3149593">private</span> <span m="3149944">key</span>
  <span m="3150295">for</span> <span m="3150646">a</span> <span m="3150997">will</span>
  <span m="3151348">know</span> <span m="3151699">the</span> <span m="3152050">private</span>
  <span m="3152401">key</span> <span m="3152752">for</span> <span m="3153103">this,</span>
  <span m="3153454">because</span> <span m="3153805">this</span> <span m="3154156">is</span>
  <span m="3154507">public.</span></p><p><span m="3154859">Everyone</span> <span m="3155155">can</span>
  <span m="3155452">see</span> <span m="3155749">what</span> <span m="3156045">the</span>
  <span m="3156342">hash</span> <span m="3156639">of</span> <span m="3156935">a</span>
  <span m="3157232">is.</span></p><p><span m="3157529">And</span> <span m="3158015">then</span>
  <span m="3158501">so</span> <span m="3158987">it's</span> <span m="3159473">just</span>
  <span m="3159959">little</span> <span m="3160445">a,</span> <span m="3160931">times</span>
  <span m="3161417">the</span> <span m="3161904">has</span> <span m="3162390">of</span>
  <span m="3162876">little</span> <span m="3163362">a.</span> <span m="3163848">This</span>
  <span m="3164334">is</span> <span m="3164820">a</span> <span m="3165306">scalar</span>
  <span m="3165792">multiplication.</span></p><p><span m="3166279">So</span> <span
  m="3166703">the</span> <span m="3167128">scalar</span> <span m="3167553">multiplication</span>
  <span m="3167977">works</span> <span m="3168402">the</span> <span m="3168827">same</span>
  <span m="3169252">for</span> <span m="3169676">the--</span> <span m="3170101">sorry,</span>
  <span m="3170526">this</span> <span m="3170951">is</span> <span m="3171375">the</span>
  <span m="3171800">point</span> <span m="3172225">multiplication.</span></p><p><span
  m="3172650">And</span> <span m="3172918">it</span> <span m="3173187">works</span>
  <span m="3173456">the</span> <span m="3173725">same</span> <span m="3173994">for</span>
  <span m="3174263">the</span> <span m="3174532">scalar</span> <span m="3174801">down</span>
  <span m="3175070">here.</span></p><p><span m="3175339">So</span> <span m="3175554">this</span>
  <span m="3175769">doesn't</span> <span m="3175984">hurt.</span> <span m="3176199">It</span>
  <span m="3176414">doesn't</span> <span m="3176629">make</span> <span m="3176844">it</span>
  <span m="3177059">any</span> <span m="3177274">harder</span> <span m="3177489">to</span>
  <span m="3177704">sign.</span> <span m="3177919">You</span> <span m="3178134">just</span>
  <span m="3178349">have</span> <span m="3178564">to</span> <span m="3178779">perform</span>
  <span m="3178994">a</span> <span m="3179210">hash</span> <span m="3179614">operation</span>
  <span m="3180019">and</span> <span m="3180423">a</span> <span m="3180828">multiplication,</span>
  <span m="3181233">which</span> <span m="3181637">is</span> <span m="3182042">quick.</span>
  <span m="3182446">But</span> <span m="3182851">what</span> <span m="3183256">it</span>
  <span m="3183660">does</span> <span m="3184065">is</span> <span m="3184469">it</span>
  <span m="3184874">prevents</span> <span m="3185279">this</span> <span m="3185634">kind</span>
  <span m="3185989">of</span> <span m="3186344">attack.</span></p><p><span m="3186700">So</span>
  <span m="3186976">instead</span> <span m="3187253">of</span> <span m="3187530">signing</span>
  <span m="3187807">with</span> <span m="3188084">a</span> <span m="3188361">plus</span>
  <span m="3188637">b,</span> <span m="3188914">sign</span> <span m="3189191">with</span>
  <span m="3189468">a,</span> <span m="3189745">times</span> <span m="3190022">the</span>
  <span m="3190298">hash</span> <span m="3190575">of</span> <span m="3190852">a,</span>
  <span m="3191129">plus</span> <span m="3191406">b</span> <span m="3191683">times</span>
  <span m="3191960">the</span> <span m="3192361">hash</span> <span m="3192763">of</span>
  <span m="3193164">b.</span> <span m="3193566">Since,</span> <span m="3193967">in</span>
  <span m="3194369">this</span> <span m="3194771">case,</span> <span m="3195172">in</span>
  <span m="3195574">bitcoin,</span> <span m="3195975">you</span> <span m="3196377">can</span>
  <span m="3196778">see</span> <span m="3197180">what</span> <span m="3197582">public</span>
  <span m="3197983">keys</span> <span m="3198385">are</span> <span m="3198786">being</span>
  <span m="3199188">signed</span> <span m="3199590">and</span> <span m="3199845">aggregated,</span>
  <span m="3200100">so</span> <span m="3200355">you</span> <span m="3200611">say,</span>
  <span m="3200866">OK,</span> <span m="3201121">well</span> <span m="3201376">I'm</span>
  <span m="3201632">going</span> <span m="3201887">to</span> <span m="3202142">try</span>
  <span m="3202397">to</span> <span m="3202653">do</span> <span m="3202908">this</span>
  <span m="3203163">technique</span> <span m="3203418">again.</span> <span m="3203674">c</span>
  <span m="3203929">is</span> <span m="3204184">a,</span> <span m="3204440">times</span>
  <span m="3204701">the</span> <span m="3204963">hash</span> <span m="3205224">of</span>
  <span m="3205486">a,</span> <span m="3205747">plus</span> <span m="3206009">b</span>
  <span m="3206271">times</span> <span m="3206532">the</span> <span m="3206794">hash</span>
  <span m="3207055">of</span> <span m="3207317">b.</span></p><p><span m="3207579">The</span>
  <span m="3207870">private</span> <span m="3208162">key</span> <span m="3208453">is</span>
  <span m="3208745">going</span> <span m="3209036">to</span> <span m="3209328">be</span>
  <span m="3209619">a,</span> <span m="3209911">times</span> <span m="3210202">the</span>
  <span m="3210494">hash</span> <span m="3210786">of</span> <span m="3211077">the</span>
  <span m="3211369">pub</span> <span m="3211660">key,</span> <span m="3211952">plus</span>
  <span m="3212243">little</span> <span m="3212535">b</span> <span m="3212826">times</span>
  <span m="3213118">the</span> <span m="3213410">hash</span> <span m="3213924">of</span>
  <span m="3214439">pub</span> <span m="3214954">key</span> <span m="3215469">big</span>
  <span m="3215983">B.</span> <span m="3216498">I</span> <span m="3217013">know</span>
  <span m="3217528">b,</span> <span m="3218042">which</span> <span m="3218557">is</span>
  <span m="3219072">q</span> <span m="3219587">minus</span> <span m="3220101">a--</span>
  <span m="3220616">sorry,</span> <span m="3221131">I</span> <span m="3221646">don't</span>
  <span m="3222160">know</span> <span m="3222675">b.</span> <span m="3223190">I</span>
  <span m="3223705">know</span> <span m="3224220">q.</span> <span m="3224848">And</span>
  <span m="3225476">I</span> <span m="3226104">constructed</span> <span m="3226732">sort</span>
  <span m="3227361">of</span> <span m="3227989">this</span> <span m="3228617">b</span>
  <span m="3229245">is</span> <span m="3229874">q</span> <span m="3230502">minus</span>
  <span m="3231130">a.</span> <span m="3231758">But</span> <span m="3232387">I</span>
  <span m="3233015">don't</span> <span m="3233643">know</span> <span m="3234271">it.</span></p><p><span
  m="3234900">So</span> <span m="3235233">c</span> <span m="3235566">is</span> <span
  m="3235899">now</span> <span m="3236232">going</span> <span m="3236565">to</span>
  <span m="3236899">be</span> <span m="3237232">a,</span> <span m="3237565">times</span>
  <span m="3237898">the</span> <span m="3238231">hash</span> <span m="3238565">of</span>
  <span m="3238898">a,</span> <span m="3239231">plus</span> <span m="3239564">q</span>
  <span m="3239897">minus</span> <span m="3240230">a,</span> <span m="3240564">times</span>
  <span m="3240897">the</span> <span m="3241230">hash</span> <span m="3241563">of</span>
  <span m="3241896">q</span> <span m="3242230">minus</span> <span m="3242691">a.</span>
  <span m="3243152">That's</span> <span m="3243613">what</span> <span m="3244074">b</span>
  <span m="3244535">is.</span> <span m="3244996">I</span> <span m="3245457">can't</span>
  <span m="3245918">cancel</span> <span m="3246380">out</span> <span m="3246841">this</span>
  <span m="3247302">little</span> <span m="3247763">a</span> <span m="3248224">anymore,</span>
  <span m="3248685">because</span> <span m="3249146">it's</span> <span m="3249607">got</span>
  <span m="3250069">a</span> <span m="3250385">different</span> <span m="3250702">coefficient.</span>
  <span m="3251019">Maybe</span> <span m="3251336">it's</span> <span m="3251653">easier</span>
  <span m="3251970">if</span> <span m="3252287">you</span> <span m="3252604">sort</span>
  <span m="3252921">of</span> <span m="3253238">move</span> <span m="3253555">them</span>
  <span m="3253872">on</span> <span m="3254189">the</span> <span m="3254506">other</span>
  <span m="3254823">side.</span></p><p><span m="3255140">I've</span> <span m="3255426">now</span>
  <span m="3255712">got</span> <span m="3255999">these</span> <span m="3256285">coefficients</span>
  <span m="3256572">in</span> <span m="3256858">front</span> <span m="3257145">of</span>
  <span m="3257431">my</span> <span m="3257718">private</span> <span m="3258004">keys</span>
  <span m="3258291">that</span> <span m="3258577">are</span> <span m="3258864">not</span>
  <span m="3259150">the</span> <span m="3259437">same,</span> <span m="3259723">and</span>
  <span m="3260010">won't</span> <span m="3260740">cancel</span> <span m="3261470">out</span>
  <span m="3262200">anymore.</span></p><p><span m="3262930">Before,</span> <span m="3263342">the</span>
  <span m="3263754">system</span> <span m="3264166">is</span> <span m="3264578">times</span>
  <span m="3264990">1.</span> <span m="3265402">So</span> <span m="3265814">the</span>
  <span m="3266226">idea</span> <span m="3266638">was</span> <span m="3267050">a,</span>
  <span m="3267462">times</span> <span m="3267874">1,</span> <span m="3268286">plus</span>
  <span m="3268698">q</span> <span m="3269110">minus</span> <span m="3269522">a,</span>
  <span m="3269934">times</span> <span m="3270346">1.</span> <span m="3270758">Since</span>
  <span m="3271171">the</span> <span m="3271535">coefficients</span> <span m="3271899">are</span>
  <span m="3272263">the</span> <span m="3272627">same,</span> <span m="3272991">1,</span>
  <span m="3273355">I</span> <span m="3273719">can</span> <span m="3274083">factor</span>
  <span m="3274447">them</span> <span m="3274811">out,</span> <span m="3275175">and</span>
  <span m="3275539">now</span> <span m="3275903">apply</span> <span m="3276267">these,</span>
  <span m="3276631">and</span> <span m="3276995">remove</span> <span m="3277359">the</span>
  <span m="3277859">a.</span></p><p><span m="3278359">So</span> <span m="3278575">if</span>
  <span m="3278792">the</span> <span m="3279008">coefficients</span> <span m="3279225">are</span>
  <span m="3279442">the</span> <span m="3279658">same--</span> <span m="3279875">if</span>
  <span m="3280091">it</span> <span m="3280308">was</span> <span m="3280525">a,</span>
  <span m="3280741">times</span> <span m="3280958">the</span> <span m="3281174">hash</span>
  <span m="3281391">of</span> <span m="3281608">a,</span> <span m="3281824">plus</span>
  <span m="3282041">q</span> <span m="3282257">minus</span> <span m="3282474">a</span>
  <span m="3282691">times</span> <span m="3282947">the</span> <span m="3283203">hash</span>
  <span m="3283460">of</span> <span m="3283716">a,</span> <span m="3283972">I'm</span>
  <span m="3284229">good.</span> <span m="3284485">I</span> <span m="3284741">can</span>
  <span m="3284998">still</span> <span m="3285254">factor</span> <span m="3285510">out</span>
  <span m="3285767">that</span> <span m="3286023">coefficient</span> <span m="3286279">and</span>
  <span m="3286536">cancel</span> <span m="3286792">out</span> <span m="3287049">a.</span>
  <span m="3287412">But</span> <span m="3287776">now,</span> <span m="3288140">the</span>
  <span m="3288504">coefficients</span> <span m="3288867">are</span> <span m="3289231">different.</span>
  <span m="3289595">And</span> <span m="3289959">so</span> <span m="3290322">I</span>
  <span m="3290686">can't</span> <span m="3291050">do</span> <span m="3291414">that</span>
  <span m="3291777">subtraction.</span> <span m="3292141">And</span> <span m="3292505">now,</span>
  <span m="3292869">I'm</span> <span m="3293302">stuck.</span> <span m="3293735">I</span>
  <span m="3294168">cannot</span> <span m="3294601">sign</span> <span m="3295034">with</span>
  <span m="3295468">this</span> <span m="3295901">little</span> <span m="3296334">c,</span>
  <span m="3296767">just</span> <span m="3297200">from</span> <span m="3297634">knowing</span>
  <span m="3298067">q.</span> <span m="3298500">Questions</span> <span m="3298933">about</span>
  <span m="3299366">this?</span></p><p><span m="3299800">AUDIENCE:</span> <span m="3300623">So</span>
  <span m="3301447">how</span> <span m="3302271">do</span> <span m="3303095">come</span>
  <span m="3303918">up</span> <span m="3304742">with</span> <span m="3305566">q?</span></p><p><span
  m="3306390">TADGE</span> <span m="3306976">DRYJA:</span> <span m="3307563">In</span>
  <span m="3308150">this</span> <span m="3308736">attack,</span> <span m="3309323">q</span>
  <span m="3309910">is</span> <span m="3310496">just</span> <span m="3311083">any</span>
  <span m="3311670">random</span> <span m="3312256">number.</span> <span m="3312843">But</span>
  <span m="3313430">the</span> <span m="3314016">idea</span> <span m="3314603">is</span>
  <span m="3315190">here,</span> <span m="3315776">q</span> <span m="3316363">being</span>
  <span m="3316950">any</span> <span m="3317283">random</span> <span m="3317616">number</span>
  <span m="3317949">doesn't</span> <span m="3318282">help</span> <span m="3318615">you,</span>
  <span m="3318948">because</span> <span m="3319281">you've</span> <span m="3319614">sent</span>
  <span m="3319947">money</span> <span m="3320280">to</span> <span m="3320613">b.</span>
  <span m="3320946">You're</span> <span m="3321279">trying</span> <span m="3321612">to</span>
  <span m="3321945">sign</span> <span m="3322279">with</span> <span m="3322660">q</span>
  <span m="3323041">minus</span> <span m="3323422">a.</span> <span m="3323803">But</span>
  <span m="3324184">you</span> <span m="3324566">don't</span> <span m="3324947">actually</span>
  <span m="3325328">know</span> <span m="3325709">the</span> <span m="3326090">private</span>
  <span m="3326471">key,</span> <span m="3326853">q</span> <span m="3327234">minus</span>
  <span m="3327615">a.</span> <span m="3327996">So</span> <span m="3328377">you're</span>
  <span m="3328758">stuck.</span></p><p><span m="3329140">Even</span> <span m="3329456">if</span>
  <span m="3329772">you</span> <span m="3330088">did,</span> <span m="3330405">in</span>
  <span m="3330721">this</span> <span m="3331037">case,</span> <span m="3331353">it</span>
  <span m="3331670">wouldn't</span> <span m="3331986">help,</span> <span m="3332302">because</span>
  <span m="3332618">you</span> <span m="3332935">still</span> <span m="3333251">have</span>
  <span m="3333567">that</span> <span m="3333883">either.</span></p><p><span m="3334200">So</span>
  <span m="3334636">this</span> <span m="3335072">prevents</span> <span m="3335509">that</span>
  <span m="3335945">kind</span> <span m="3336382">of</span> <span m="3336818">straightforward</span>
  <span m="3337254">attack.</span> <span m="3337691">You</span> <span m="3338127">can't</span>
  <span m="3338564">get</span> <span m="3339000">rid</span> <span m="3339436">of</span>
  <span m="3339873">the</span> <span m="3340309">a</span> <span m="3340746">times</span>
  <span m="3341182">h</span> <span m="3341619">term.</span></p><p><span m="3342670">This</span>
  <span m="3343124">actually</span> <span m="3343578">is</span> <span m="3344032">not</span>
  <span m="3344486">enough.</span> <span m="3344940">There's</span> <span m="3345394">a</span>
  <span m="3345848">paper</span> <span m="3346302">called</span> <span m="3346756">Wagner,</span>
  <span m="3347210">Wagner's</span> <span m="3347664">paper,</span> <span m="3348118">some</span>
  <span m="3348572">guy</span> <span m="3349026">at</span> <span m="3349480">California,</span>
  <span m="3349934">UC</span> <span m="3350388">Berkeley,</span> <span m="3350842">I</span>
  <span m="3351296">think,</span> <span m="3351750">a</span> <span m="3352204">generalized</span>
  <span m="3352658">birthday</span> <span m="3353112">problem.</span> <span m="3353566">And</span>
  <span m="3354020">it's</span> <span m="3354474">a</span> <span m="3354928">hard</span>
  <span m="3355382">paper</span> <span m="3355836">to</span> <span m="3356290">read.</span>
  <span m="3356538">But</span> <span m="3356786">if</span> <span m="3357034">you're</span>
  <span m="3357282">working</span> <span m="3357530">on</span> <span m="3357779">these</span>
  <span m="3358027">kinds</span> <span m="3358275">of</span> <span m="3358523">things,</span>
  <span m="3358771">it's</span> <span m="3359019">a</span> <span m="3359268">good</span>
  <span m="3359516">paper</span> <span m="3359764">to</span> <span m="3360012">read,</span>
  <span m="3360260">because</span> <span m="3360509">it</span> <span m="3360893">comes</span>
  <span m="3361278">up</span> <span m="3361662">again</span> <span m="3362047">and</span>
  <span m="3362432">again</span> <span m="3362816">with</span> <span m="3363201">these</span>
  <span m="3363586">kinds</span> <span m="3363970">of</span> <span m="3364355">attacks.</span></p><p><span
  m="3364740">Collisions--</span> <span m="3365177">I</span> <span m="3365615">don't</span>
  <span m="3366053">think</span> <span m="3366491">we</span> <span m="3366929">ever</span>
  <span m="3367367">talked</span> <span m="3367805">about.</span> <span m="3368243">So</span>
  <span m="3368681">the</span> <span m="3369119">idea</span> <span m="3369557">of</span>
  <span m="3369995">colliding,</span> <span m="3370433">for</span> <span m="3370871">example,</span>
  <span m="3371309">a</span> <span m="3371850">hash</span> <span m="3372392">function,</span>
  <span m="3372934">or</span> <span m="3373475">in</span> <span m="3374017">this</span>
  <span m="3374559">case</span> <span m="3375100">a</span> <span m="3375642">public</span>
  <span m="3376184">key,</span> <span m="3376725">usually</span> <span m="3377267">it</span>
  <span m="3377809">takes</span> <span m="3378350">half</span> <span m="3378892">the</span>
  <span m="3379434">work</span> <span m="3379975">that</span> <span m="3380517">you--</span>
  <span m="3381059">the</span> <span m="3381581">reason</span> <span m="3382104">it's</span>
  <span m="3382627">called</span> <span m="3383150">a</span> <span m="3383673">birthday</span>
  <span m="3384196">paradox</span> <span m="3384719">is</span> <span m="3385242">because--</span>
  <span m="3385765">do</span> <span m="3386288">people</span> <span m="3386811">know</span>
  <span m="3387334">this</span> <span m="3387857">birthday</span> <span m="3388380">thing.</span>
  <span m="3388614">Like,</span> <span m="3388848">how</span> <span m="3389083">many</span>
  <span m="3389317">people</span> <span m="3389551">need</span> <span m="3389786">to</span>
  <span m="3390020">be</span> <span m="3390255">in</span> <span m="3390489">a</span>
  <span m="3390723">room</span> <span m="3390958">before</span> <span m="3391192">two</span>
  <span m="3391427">people</span> <span m="3391661">have</span> <span m="3391895">the</span>
  <span m="3392130">same</span> <span m="3392364">birthday?</span></p><p><span m="3392599">And</span>
  <span m="3392915">it's</span> <span m="3393232">like</span> <span m="3393549">22</span>
  <span m="3393866">or</span> <span m="3394183">something.</span></p><p><span m="3394500">It's</span>
  <span m="3394863">really</span> <span m="3395226">low.</span> <span m="3395589">And</span>
  <span m="3395952">it's</span> <span m="3396315">surprising,</span> <span m="3396678">because</span>
  <span m="3397041">you</span> <span m="3397405">think,</span> <span m="3397768">well,</span>
  <span m="3398131">maybe</span> <span m="3398494">365</span> <span m="3398857">divided</span>
  <span m="3399220">by</span> <span m="3399583">2,</span> <span m="3399946">so</span>
  <span m="3400310">like</span> <span m="3400836">180</span> <span m="3401362">or</span>
  <span m="3401889">something.</span> <span m="3402415">But</span> <span m="3402942">it's</span>
  <span m="3403468">actually</span> <span m="3403995">22,</span> <span m="3404521">I</span>
  <span m="3405048">think,</span> <span m="3405574">because</span> <span m="3406101">of</span>
  <span m="3406627">the</span> <span m="3407154">way</span> <span m="3407680">like</span>
  <span m="3408207">for</span> <span m="3408733">every</span> <span m="3409260">new</span>
  <span m="3409727">person</span> <span m="3410195">added,</span> <span m="3410662">there's</span>
  <span m="3411130">a</span> <span m="3411598">possibility</span> <span m="3412065">they</span>
  <span m="3412533">collide</span> <span m="3413000">with</span> <span m="3413468">every</span>
  <span m="3413936">already</span> <span m="3414403">existing</span> <span m="3414871">person's</span>
  <span m="3415339">birthday.</span></p><p><span m="3416609">And</span> <span m="3416918">so</span>
  <span m="3417228">the</span> <span m="3417537">collisions</span> <span m="3417847">are</span>
  <span m="3418156">more</span> <span m="3418466">common</span> <span m="3418775">than</span>
  <span m="3419085">you</span> <span m="3419394">think.</span> <span m="3419704">So</span>
  <span m="3420013">in</span> <span m="3420323">the</span> <span m="3420632">case</span>
  <span m="3420942">of</span> <span m="3421251">colliding</span> <span m="3421561">a</span>
  <span m="3421870">hash</span> <span m="3422180">function,</span> <span m="3422623">even</span>
  <span m="3423067">if</span> <span m="3423511">the</span> <span m="3423955">hash</span>
  <span m="3424399">function</span> <span m="3424843">is</span> <span m="3425287">2</span>
  <span m="3425731">to</span> <span m="3426175">the</span> <span m="3426619">256</span>
  <span m="3427063">bits,</span> <span m="3427507">you</span> <span m="3427951">only</span>
  <span m="3428395">need</span> <span m="3428839">2</span> <span m="3429283">of</span>
  <span m="3429727">the</span> <span m="3430171">128</span> <span m="3430615">attempts</span>
  <span m="3431059">to</span> <span m="3431335">collide</span> <span m="3431611">and</span>
  <span m="3431887">find</span> <span m="3432163">two</span> <span m="3432439">that</span>
  <span m="3432716">are</span> <span m="3432992">the</span> <span m="3433268">same.</span>
  <span m="3433544">And</span> <span m="3433820">that's</span> <span m="3434096">if</span>
  <span m="3434373">you</span> <span m="3434649">store</span> <span m="3434925">all</span>
  <span m="3435201">the</span> <span m="3435477">old</span> <span m="3435753">hashes.</span></p><p><span
  m="3436030">And</span> <span m="3436291">so</span> <span m="3436552">keep</span>
  <span m="3436813">coming</span> <span m="3437074">up</span> <span m="3437335">with</span>
  <span m="3437597">new</span> <span m="3437858">ones</span> <span m="3438119">after</span>
  <span m="3438380">the</span> <span m="3438641">square</span> <span m="3438902">root</span>
  <span m="3439164">of</span> <span m="3439425">the</span> <span m="3439686">number</span>
  <span m="3439947">of</span> <span m="3440208">attempts,</span> <span m="3440470">you'll</span>
  <span m="3440741">find</span> <span m="3441012">it.</span> <span m="3441283">And</span>
  <span m="3441555">then</span> <span m="3441826">there's</span> <span m="3442097">some</span>
  <span m="3442368">techniques</span> <span m="3442640">with</span> <span m="3442911">cycle</span>
  <span m="3443182">finding,</span> <span m="3443453">where</span> <span m="3443725">you</span>
  <span m="3443996">don't</span> <span m="3444267">have</span> <span m="3444538">to</span>
  <span m="3444810">store</span> <span m="3445115">them</span> <span m="3445420">all,</span>
  <span m="3445725">things</span> <span m="3446030">like</span> <span m="3446335">that.</span>
  <span m="3446640">So</span> <span m="3446945">usually,</span> <span m="3447250">you</span>
  <span m="3447555">think,</span> <span m="3447860">OK,</span> <span m="3448165">2</span>
  <span m="3448470">to</span> <span m="3448775">the</span> <span m="3449080">n</span>
  <span m="3449385">over</span> <span m="3449690">2</span> <span m="3449995">time</span>
  <span m="3450300">to</span> <span m="3450605">find</span> <span m="3450910">a</span>
  <span m="3451321">collision.</span> <span m="3451732">But</span> <span m="3452143">that's</span>
  <span m="3452554">a</span> <span m="3452965">collision</span> <span m="3453376">between</span>
  <span m="3453787">two</span> <span m="3454198">things.</span></p><p><span m="3454609">And</span>
  <span m="3454993">Wagner's</span> <span m="3455377">attack</span> <span m="3455761">is</span>
  <span m="3456146">sort</span> <span m="3456530">of,</span> <span m="3456914">yeah,</span>
  <span m="3457298">find</span> <span m="3457683">a</span> <span m="3458067">and</span>
  <span m="3458451">b,</span> <span m="3458835">such</span> <span m="3459220">that</span>
  <span m="3459604">a</span> <span m="3459988">equals</span> <span m="3460372">b,</span>
  <span m="3460757">kind</span> <span m="3461141">of</span> <span m="3461525">the</span>
  <span m="3461910">normal</span> <span m="3462324">collision.</span> <span m="3462739">Now,</span>
  <span m="3463154">find</span> <span m="3463568">a0,</span> <span m="3463983">a1,</span>
  <span m="3464398">up</span> <span m="3464812">to</span> <span m="3465227">ai.</span>
  <span m="3465642">So</span> <span m="3466056">find</span> <span m="3466471">i</span>
  <span m="3466886">things</span> <span m="3467300">on</span> <span m="3467715">this</span>
  <span m="3468130">side,</span> <span m="3468544">and</span> <span m="3468959">j</span>
  <span m="3469374">things</span> <span m="3469789">on</span> <span m="3470141">this</span>
  <span m="3470493">side,</span> <span m="3470845">such</span> <span m="3471197">that</span>
  <span m="3471549">the</span> <span m="3471901">sum</span> <span m="3472253">of</span>
  <span m="3472605">a</span> <span m="3472957">equals</span> <span m="3473309">the</span>
  <span m="3473661">sum</span> <span m="3474013">of</span> <span m="3474365">b.</span>
  <span m="3474717">And</span> <span m="3475069">in</span> <span m="3475421">the</span>
  <span m="3475773">case</span> <span m="3476125">of</span> <span m="3476477">elliptic</span>
  <span m="3476830">curve</span> <span m="3477063">points,</span> <span m="3477297">it</span>
  <span m="3477530">would</span> <span m="3477764">actually</span> <span m="3477998">be</span>
  <span m="3478231">the</span> <span m="3478465">sum.</span> <span m="3478699">You'd</span>
  <span m="3478932">do</span> <span m="3479166">addition.</span></p><p><span m="3479400">In</span>
  <span m="3479686">the</span> <span m="3479972">case</span> <span m="3480258">of</span>
  <span m="3480545">hashes,</span> <span m="3480831">it</span> <span m="3481117">might</span>
  <span m="3481404">be</span> <span m="3481690">xor,</span> <span m="3481976">or</span>
  <span m="3482263">some</span> <span m="3482549">other</span> <span m="3482835">operation.</span>
  <span m="3483122">But</span> <span m="3483408">the</span> <span m="3483694">idea</span>
  <span m="3483981">is</span> <span m="3484267">if</span> <span m="3484553">you</span>
  <span m="3484840">have</span> <span m="3485117">a</span> <span m="3485395">lot</span>
  <span m="3485673">of</span> <span m="3485950">different</span> <span m="3486228">things</span>
  <span m="3486506">that</span> <span m="3486784">you</span> <span m="3487061">can</span>
  <span m="3487339">pick</span> <span m="3487617">and</span> <span m="3487894">choose</span>
  <span m="3488172">on</span> <span m="3488450">both</span> <span m="3488728">sides,</span>
  <span m="3489005">you</span> <span m="3489283">can</span> <span m="3489561">potentially</span>
  <span m="3489839">find</span> <span m="3490221">collisions</span> <span m="3490604">with</span>
  <span m="3490986">much</span> <span m="3491369">less</span> <span m="3491751">time.</span>
  <span m="3492134">And</span> <span m="3492516">in</span> <span m="3492899">the</span>
  <span m="3493282">case</span> <span m="3493664">of</span> <span m="3494047">these</span>
  <span m="3494429">elliptic</span> <span m="3494812">curve</span> <span m="3495194">points,</span>
  <span m="3495577">it</span> <span m="3495960">probably</span> <span m="3496455">would</span>
  <span m="3496951">be</span> <span m="3497447">practical.</span> <span m="3497943">You'd</span>
  <span m="3498439">need</span> <span m="3498935">dozens,</span> <span m="3499430">20,</span>
  <span m="3499926">30,</span> <span m="3500422">40,</span> <span m="3500918">different</span>
  <span m="3501414">keys.</span></p><p><span m="3501910">But</span> <span m="3502241">you</span>
  <span m="3502572">could</span> <span m="3502903">potentially</span> <span m="3503234">say,</span>
  <span m="3503565">OK,</span> <span m="3503896">there's</span> <span m="3504227">a</span>
  <span m="3504558">key</span> <span m="3504889">with</span> <span m="3505220">a</span>
  <span m="3505551">lot</span> <span m="3505882">of</span> <span m="3506213">coins.</span>
  <span m="3506544">I'm</span> <span m="3506875">going</span> <span m="3507206">to</span>
  <span m="3507537">find</span> <span m="3507869">a</span> <span m="3508108">set</span>
  <span m="3508347">of</span> <span m="3508586">a</span> <span m="3508825">whole</span>
  <span m="3509064">bunch</span> <span m="3509303">of</span> <span m="3509542">keys,</span>
  <span m="3509781">such</span> <span m="3510020">that</span> <span m="3510259">that</span>
  <span m="3510498">I</span> <span m="3510737">can</span> <span m="3510976">cancel</span>
  <span m="3511215">that</span> <span m="3511454">key</span> <span m="3511693">out,</span>
  <span m="3511932">even</span> <span m="3512171">with</span> <span m="3512410">this</span>
  <span m="3513108">multiplying</span> <span m="3513807">by</span> <span m="3514505">a</span>
  <span m="3515204">different</span> <span m="3515902">coefficient,</span> <span m="3516601">because</span>
  <span m="3517300">I've</span> <span m="3517998">got</span> <span m="3518697">so</span>
  <span m="3519395">much</span> <span m="3520094">search</span> <span m="3520792">space.</span>
  <span m="3521491">It's</span> <span m="3522190">a</span> <span m="3522492">cool</span>
  <span m="3522795">paper.</span> <span m="3523097">You</span> <span m="3523400">should</span>
  <span m="3523703">look</span> <span m="3524005">through</span> <span m="3524308">it,</span>
  <span m="3524611">if</span> <span m="3524913">you're</span> <span m="3525216">interested.</span></p><p><span
  m="3525519">But</span> <span m="3525889">that's</span> <span m="3526259">a</span>
  <span m="3526629">problem.</span> <span m="3526999">You</span> <span m="3527369">can</span>
  <span m="3527739">sort</span> <span m="3528109">of</span> <span m="3528479">make</span>
  <span m="3528849">progress,</span> <span m="3529219">is</span> <span m="3529589">the</span>
  <span m="3529959">basic</span> <span m="3530329">idea.</span> <span m="3530699">I</span>
  <span m="3531069">can</span> <span m="3531439">keep</span> <span m="3531809">getting</span>
  <span m="3532180">closer</span> <span m="3532563">and</span> <span m="3532947">closer</span>
  <span m="3533330">to</span> <span m="3533714">canceling</span> <span m="3534098">this</span>
  <span m="3534481">thing</span> <span m="3534865">out.</span></p><p><span m="3535249">So</span>
  <span m="3535735">instead,</span> <span m="3536222">we</span> <span m="3536709">have</span>
  <span m="3537196">this</span> <span m="3537683">improved</span> <span m="3538170">delinearization.</span>
  <span m="3538657">And</span> <span m="3539144">this</span> <span m="3539631">is</span>
  <span m="3540118">talked</span> <span m="3540605">about</span> <span m="3541092">in</span>
  <span m="3541579">the</span> <span m="3542066">paper</span> <span m="3542553">from</span>
  <span m="3543040">like</span> <span m="3543451">January.</span> <span m="3543862">You</span>
  <span m="3544274">take</span> <span m="3544685">the</span> <span m="3545096">hash</span>
  <span m="3545508">of</span> <span m="3545919">all</span> <span m="3546330">the</span>
  <span m="3546742">keys</span> <span m="3547153">concatenated</span> <span m="3547564">together,</span>
  <span m="3547976">in</span> <span m="3548387">some</span> <span m="3548798">specified</span>
  <span m="3549210">order.</span> <span m="3549508">So</span> <span m="3549807">you</span>
  <span m="3550105">sort</span> <span m="3550404">the</span> <span m="3550703">keys</span>
  <span m="3551001">some</span> <span m="3551300">way.</span> <span m="3551599">And</span>
  <span m="3551897">you</span> <span m="3552196">say</span> <span m="3552495">OK,</span>
  <span m="3552793">z</span> <span m="3553092">is</span> <span m="3553390">the</span>
  <span m="3553689">hash</span> <span m="3553988">of</span> <span m="3554286">a</span>
  <span m="3554585">and</span> <span m="3554884">b,</span> <span m="3555182">or</span>
  <span m="3555481">if</span> <span m="3555780">there's</span> <span m="3556063">more</span>
  <span m="3556347">keys</span> <span m="3556630">a,</span> <span m="3556914">and</span>
  <span m="3557198">b,</span> <span m="3557481">and</span> <span m="3557765">c,</span>
  <span m="3558049">just</span> <span m="3558332">all</span> <span m="3558616">concatenated.</span></p><p><span
  m="3558900">And</span> <span m="3559189">then</span> <span m="3559479">you</span>
  <span m="3559768">sign</span> <span m="3560058">with</span> <span m="3560347">a,</span>
  <span m="3560637">times</span> <span m="3560926">the</span> <span m="3561216">hash</span>
  <span m="3561505">of</span> <span m="3561795">z,</span> <span m="3562084">and</span>
  <span m="3562374">a</span> <span m="3562663">0,</span> <span m="3562953">plus</span>
  <span m="3563242">b</span> <span m="3563532">times</span> <span m="3563821">the</span>
  <span m="3564111">hash</span> <span m="3564400">of</span> <span m="3564690">z,</span>
  <span m="3564979">and</span> <span m="3565269">a</span> <span m="3565607">1.</span>
  <span m="3565946">So</span> <span m="3566285">you</span> <span m="3566623">make</span>
  <span m="3566962">the</span> <span m="3567301">coefficients</span> <span m="3567639">distinct.</span>
  <span m="3567978">But</span> <span m="3568317">you</span> <span m="3568655">also</span>
  <span m="3568994">make</span> <span m="3569333">the</span> <span m="3569671">coefficients</span>
  <span m="3570010">commit</span> <span m="3570349">to</span> <span m="3570739">every</span>
  <span m="3571130">single</span> <span m="3571520">part</span> <span m="3571911">of</span>
  <span m="3572302">the</span> <span m="3572692">set.</span> <span m="3573083">Every</span>
  <span m="3573473">key</span> <span m="3573864">in</span> <span m="3574255">the</span>
  <span m="3574645">set</span> <span m="3575036">needs</span> <span m="3575426">to</span>
  <span m="3575817">be</span> <span m="3576208">in</span> <span m="3576598">this</span>
  <span m="3576989">coefficient.</span></p><p><span m="3577380">And</span> <span m="3577980">the</span>
  <span m="3578581">MuSig</span> <span m="3579181">sort</span> <span m="3579782">of</span>
  <span m="3580382">explains</span> <span m="3580983">why</span> <span m="3581583">that</span>
  <span m="3582184">works.</span> <span m="3582785">So</span> <span m="3583385">the</span>
  <span m="3583986">attack</span> <span m="3584586">in</span> <span m="3585187">this</span>
  <span m="3585787">case</span> <span m="3586388">is,</span> <span m="3586988">well,</span>
  <span m="3587589">I've</span> <span m="3588190">got</span> <span m="3588555">these</span>
  <span m="3588920">different</span> <span m="3589286">coefficients.</span> <span
  m="3589651">But</span> <span m="3590016">the</span> <span m="3590382">coefficient</span>
  <span m="3590747">here</span> <span m="3591113">only</span> <span m="3591478">depends</span>
  <span m="3591843">on</span> <span m="3592209">this</span> <span m="3592574">key</span>
  <span m="3592940">here.</span></p><p><span m="3593960">So</span> <span m="3594242">maybe</span>
  <span m="3594525">I</span> <span m="3594807">can</span> <span m="3595090">find</span>
  <span m="3595372">a</span> <span m="3595655">bunch</span> <span m="3595937">of</span>
  <span m="3596220">different</span> <span m="3596502">keys</span> <span m="3596785">with</span>
  <span m="3597067">different</span> <span m="3597350">coefficients,</span> <span
  m="3597632">such</span> <span m="3597915">that</span> <span m="3598197">these</span>
  <span m="3598480">coefficients</span> <span m="3598974">will</span> <span m="3599468">cancel</span>
  <span m="3599962">out,</span> <span m="3600456">or</span> <span m="3600950">these</span>
  <span m="3601444">coefficients</span> <span m="3601938">will</span> <span m="3602432">sum,</span>
  <span m="3602927">or</span> <span m="3603421">multiply,</span> <span m="3603915">or</span>
  <span m="3604409">sum</span> <span m="3604903">up</span> <span m="3605397">to</span>
  <span m="3605891">hash</span> <span m="3606385">of</span> <span m="3606880">a.</span>
  <span m="3607257">So</span> <span m="3607634">it</span> <span m="3608011">seems</span>
  <span m="3608388">hard.</span> <span m="3608766">I</span> <span m="3609143">can't</span>
  <span m="3609520">find</span> <span m="3609897">different</span> <span m="3610275">hashes</span>
  <span m="3610652">that</span> <span m="3611029">will</span> <span m="3611406">equal</span>
  <span m="3611783">the</span> <span m="3612161">hash</span> <span m="3612538">of</span>
  <span m="3612915">a.</span> <span m="3613292">That's</span> <span m="3613670">a</span>
  <span m="3614206">hash</span> <span m="3614742">collision.</span></p><p><span m="3615279">But</span>
  <span m="3615608">if</span> <span m="3615937">I</span> <span m="3616266">have</span>
  <span m="3616595">any</span> <span m="3616924">number</span> <span m="3617253">of</span>
  <span m="3617582">different</span> <span m="3617911">things,</span> <span m="3618240">I</span>
  <span m="3618569">may</span> <span m="3618899">be</span> <span m="3619228">able</span>
  <span m="3619557">to.</span> <span m="3619886">And</span> <span m="3620215">so</span>
  <span m="3620544">the</span> <span m="3620873">idea</span> <span m="3621202">is,</span>
  <span m="3621531">if</span> <span m="3621860">you</span> <span m="3622190">do</span>
  <span m="3622624">this,</span> <span m="3623058">now</span> <span m="3623492">every</span>
  <span m="3623926">time</span> <span m="3624361">I'm</span> <span m="3624795">adding</span>
  <span m="3625229">or</span> <span m="3625663">removing</span> <span m="3626097">a</span>
  <span m="3626532">key</span> <span m="3626966">from</span> <span m="3627400">my</span>
  <span m="3627834">attempt,</span> <span m="3628268">I</span> <span m="3628703">have</span>
  <span m="3629137">to</span> <span m="3629571">change</span> <span m="3630005">z.</span></p><p><span
  m="3630440">So</span> <span m="3630723">I</span> <span m="3631006">can't</span>
  <span m="3631289">leave</span> <span m="3631572">this</span> <span m="3631855">here,</span>
  <span m="3632138">and</span> <span m="3632422">start</span> <span m="3632705">adding</span>
  <span m="3632988">things,</span> <span m="3633271">and</span> <span m="3633554">try</span>
  <span m="3633837">to</span> <span m="3634121">work</span> <span m="3634404">on</span>
  <span m="3634687">it</span> <span m="3634970">that</span> <span m="3635253">way,</span>
  <span m="3635536">because</span> <span m="3635820">every</span> <span m="3636194">time</span>
  <span m="3636569">I</span> <span m="3636944">add</span> <span m="3637319">a</span>
  <span m="3637694">c</span> <span m="3638069">or</span> <span m="3638444">d,</span>
  <span m="3638819">z</span> <span m="3639194">changes.</span></p><p><span m="3639569">And</span>
  <span m="3639930">so</span> <span m="3640291">I</span> <span m="3640652">have</span>
  <span m="3641014">to</span> <span m="3641375">start</span> <span m="3641736">over</span>
  <span m="3642097">from</span> <span m="3642459">scratch.</span> <span m="3642820">So</span>
  <span m="3643181">anyway,</span> <span m="3643542">that's</span> <span m="3643904">my</span>
  <span m="3644265">general</span> <span m="3644626">intuition</span> <span m="3644987">of</span>
  <span m="3645349">how</span> <span m="3645746">the</span> <span m="3646144">delinearization</span>
  <span m="3646541">works</span> <span m="3646939">for</span> <span m="3647337">MuSig.</span>
  <span m="3647734">And</span> <span m="3648132">then,</span> <span m="3648530">yeah,</span>
  <span m="3648927">it</span> <span m="3649325">used</span> <span m="3649723">to</span>
  <span m="3650120">be</span> <span m="3650518">like</span> <span m="3650916">z,</span>
  <span m="3651313">and</span> <span m="3651711">then</span> <span m="3652109">put</span>
  <span m="3652403">a</span> <span m="3652698">in</span> <span m="3652993">here,</span>
  <span m="3653287">because</span> <span m="3653582">now</span> <span m="3653877">that</span>
  <span m="3654171">makes</span> <span m="3654466">it</span> <span m="3654761">unique.</span>
  <span m="3655056">But</span> <span m="3655350">you</span> <span m="3655645">can</span>
  <span m="3655940">actually</span> <span m="3656234">just</span> <span m="3656529">number</span>
  <span m="3656824">them.</span></p><p><span m="3657119">You</span> <span m="3657326">just</span>
  <span m="3657533">need</span> <span m="3657740">them</span> <span m="3657947">to</span>
  <span m="3658155">be</span> <span m="3658362">distinct.</span> <span m="3658569">And</span>
  <span m="3658776">since</span> <span m="3658984">it's</span> <span m="3659191">hash,</span>
  <span m="3659398">function</span> <span m="3659605">just</span> <span m="3659812">say</span>
  <span m="3660020">like</span> <span m="3660227">0,</span> <span m="3660434">1,</span>
  <span m="3660641">2,</span> <span m="3660849">3,</span> <span m="3661329">4,</span>
  <span m="3661809">is</span> <span m="3662289">good</span> <span m="3662769">enough.</span>
  <span m="3663249">OK,</span> <span m="3663729">any</span> <span m="3664209">questions</span>
  <span m="3664689">about</span> <span m="3665169">this?</span></p><p><span m="3665650">I</span>
  <span m="3665949">realize</span> <span m="3666248">it's</span> <span m="3666548">kind</span>
  <span m="3666847">of</span> <span m="3667147">complicated,</span> <span m="3667446">and</span>
  <span m="3667745">the</span> <span m="3668045">software</span> <span m="3668344">is</span>
  <span m="3668644">kind</span> <span m="3668943">of</span> <span m="3669242">crazy.</span>
  <span m="3669542">But</span> <span m="3669841">the</span> <span m="3670141">idea</span>
  <span m="3670440">is</span> <span m="3670740">that</span> <span m="3671349">it</span>
  <span m="3671959">prevents</span> <span m="3672569">a</span> <span m="3673179">bunch</span>
  <span m="3673789">of</span> <span m="3674399">these</span> <span m="3675009">attacks</span>
  <span m="3675619">so</span> <span m="3676229">that</span> <span m="3676839">you</span>
  <span m="3677449">can</span> <span m="3678059">securely</span> <span m="3678669">use</span>
  <span m="3679279">aggregate</span> <span m="3679889">signatures.</span></p><p><span
  m="3680499">Questions?</span></p><p><span m="3683749">And</span> <span m="3684297">you</span>
  <span m="3684846">wouldn't</span> <span m="3685395">have</span> <span m="3685944">to</span>
  <span m="3686493">program</span> <span m="3687042">it.</span> <span m="3687591">Yeah</span>
  <span m="3688140">so</span> <span m="3688689">you</span> <span m="3689238">could</span>
  <span m="3689787">say,</span> <span m="3690336">OK,</span> <span m="3690885">it</span>
  <span m="3691434">saves</span> <span m="3691983">face.</span> <span m="3692532">The</span>
  <span m="3693081">first</span> <span m="3693630">use</span> <span m="3694068">case</span>
  <span m="3694506">will</span> <span m="3694945">be</span> <span m="3695383">in</span>
  <span m="3695822">single</span> <span m="3696260">wallets.</span> <span m="3696698">It's</span>
  <span m="3697137">interactive.</span> <span m="3697575">So</span> <span m="3698014">you</span>
  <span m="3698452">have</span> <span m="3698891">to</span> <span m="3699329">do</span>
  <span m="3699767">that</span> <span m="3700206">thing</span> <span m="3700644">where</span>
  <span m="3701083">I</span> <span m="3701521">come</span> <span m="3701960">up</span>
  <span m="3702196">with</span> <span m="3702433">different</span> <span m="3702669">k</span>
  <span m="3702906">values,</span> <span m="3703142">I</span> <span m="3703379">share</span>
  <span m="3703615">the</span> <span m="3703852">different</span> <span m="3704088">r</span>
  <span m="3704325">values.</span> <span m="3704561">I</span> <span m="3704798">come</span>
  <span m="3705034">up</span> <span m="3705271">with</span> <span m="3705507">the</span>
  <span m="3705744">s</span> <span m="3705980">values.</span> <span m="3706217">I</span>
  <span m="3706453">add</span> <span m="3706690">those</span> <span m="3707460">up,</span>
  <span m="3708230">sure.</span></p><p><span m="3709000">If</span> <span m="3709278">it's</span>
  <span m="3709556">all</span> <span m="3709834">doing</span> <span m="3710112">it</span>
  <span m="3710390">yourself,</span> <span m="3710668">where</span> <span m="3710946">it's</span>
  <span m="3711225">just</span> <span m="3711503">there</span> <span m="3711781">happened</span>
  <span m="3712059">to</span> <span m="3712337">be</span> <span m="3712615">two</span>
  <span m="3712893">different</span> <span m="3713171">pub</span> <span m="3713450">keys</span>
  <span m="3713718">that</span> <span m="3713986">you</span> <span m="3714255">control</span>
  <span m="3714523">both</span> <span m="3714791">of,</span> <span m="3715060">you</span>
  <span m="3715328">can</span> <span m="3715596">basically</span> <span m="3715865">skip</span>
  <span m="3716133">all</span> <span m="3716402">of</span> <span m="3716670">that.</span>
  <span m="3716938">And</span> <span m="3717207">you</span> <span m="3717475">can</span>
  <span m="3717743">just</span> <span m="3718012">say,</span> <span m="3718280">no,</span>
  <span m="3718549">I'm</span> <span m="3718864">just</span> <span m="3719180">going</span>
  <span m="3719495">to</span> <span m="3719811">add</span> <span m="3720126">the</span>
  <span m="3720442">two</span> <span m="3720757">points</span> <span m="3721073">here.</span>
  <span m="3721389">And</span> <span m="3721704">I'll</span> <span m="3722020">use</span>
  <span m="3722335">the</span> <span m="3722651">same</span> <span m="3722966">k</span>
  <span m="3723282">value.</span> <span m="3723597">That's</span> <span m="3723913">just</span>
  <span m="3724229">me.</span></p><p><span m="3725249">So</span> <span m="3725631">this</span>
  <span m="3726014">happens</span> <span m="3726397">a</span> <span m="3726779">lot</span>
  <span m="3727162">in</span> <span m="3727545">bitcoin</span> <span m="3727927">wallets,</span>
  <span m="3728310">where</span> <span m="3728693">you're</span> <span m="3729075">making</span>
  <span m="3729458">a</span> <span m="3729841">transaction</span> <span m="3730223">with</span>
  <span m="3730606">multiple</span> <span m="3730989">inputs.</span> <span m="3731262">They're</span>
  <span m="3731535">all</span> <span m="3731808">controlled</span> <span m="3732081">by</span>
  <span m="3732354">you.</span> <span m="3732627">But</span> <span m="3732900">you</span>
  <span m="3733174">might</span> <span m="3733447">have</span> <span m="3733720">two</span>
  <span m="3733993">coins</span> <span m="3734266">here,</span> <span m="3734539">and</span>
  <span m="3734812">three</span> <span m="3735085">coins</span> <span m="3735359">there,</span>
  <span m="3735582">and</span> <span m="3735805">you</span> <span m="3736029">want</span>
  <span m="3736252">to</span> <span m="3736475">send</span> <span m="3736699">someone</span>
  <span m="3736922">four</span> <span m="3737146">coins.</span> <span m="3737369">So</span>
  <span m="3737592">you've</span> <span m="3737816">got</span> <span m="3738039">to</span>
  <span m="3738263">use</span> <span m="3738486">both</span> <span m="3738709">of</span>
  <span m="3738933">these</span> <span m="3739156">inputs.</span></p><p><span m="3739380">Currently,</span>
  <span m="3739851">in</span> <span m="3740323">bitcoin</span> <span m="3740794">you're</span>
  <span m="3741266">going</span> <span m="3741737">to</span> <span m="3742209">have</span>
  <span m="3742680">multiple</span> <span m="3743152">signatures.</span> <span m="3743623">With</span>
  <span m="3744095">this</span> <span m="3744566">new</span> <span m="3745038">signature</span>
  <span m="3745510">aggregation,</span> <span m="3745854">you</span> <span m="3746199">can</span>
  <span m="3746544">say,</span> <span m="3746889">OK,</span> <span m="3747234">I'm</span>
  <span m="3747579">picking</span> <span m="3747924">these</span> <span m="3748269">two</span>
  <span m="3748614">inputs.</span> <span m="3748959">I'm</span> <span m="3749304">signing</span>
  <span m="3749649">for</span> <span m="3749994">all</span> <span m="3750339">of</span>
  <span m="3750684">them</span> <span m="3751029">with</span> <span m="3751267">a</span>
  <span m="3751506">single</span> <span m="3751745">signature.</span> <span m="3751984">And</span>
  <span m="3752223">in</span> <span m="3752462">the</span> <span m="3752701">case</span>
  <span m="3752940">of</span> <span m="3753179">it</span> <span m="3753418">all</span>
  <span m="3753657">being</span> <span m="3753896">years,</span> <span m="3754135">you</span>
  <span m="3754374">don't</span> <span m="3754613">even</span> <span m="3754852">have</span>
  <span m="3755091">to</span> <span m="3755330">do</span> <span m="3755787">the</span>
  <span m="3756244">two</span> <span m="3756701">operations</span> <span m="3757158">and</span>
  <span m="3757615">add</span> <span m="3758072">them,</span> <span m="3758529">because</span>
  <span m="3758986">you</span> <span m="3759443">know</span> <span m="3759900">the</span>
  <span m="3760357">all</span> <span m="3760814">the</span> <span m="3761271">keys.</span>
  <span m="3761728">So</span> <span m="3762185">that's</span> <span m="3762642">going</span>
  <span m="3763099">to</span> <span m="3763300">be</span> <span m="3763502">the</span>
  <span m="3763704">first</span> <span m="3763906">use</span> <span m="3764108">case.</span></p><p><span
  m="3764310">And</span> <span m="3764676">that's</span> <span m="3765042">much</span>
  <span m="3765408">easier</span> <span m="3765774">to</span> <span m="3766140">program,</span>
  <span m="3766506">because</span> <span m="3766872">it's</span> <span m="3767238">all</span>
  <span m="3767604">just</span> <span m="3767970">within</span> <span m="3768336">the</span>
  <span m="3768702">same</span> <span m="3769068">computer.</span> <span m="3769434">And</span>
  <span m="3769800">this</span> <span m="3770163">is</span> <span m="3770527">easy.</span>
  <span m="3770891">That's</span> <span m="3771255">cool.</span></p><p><span m="3771619">And</span>
  <span m="3772107">then</span> <span m="3772595">a</span> <span m="3773083">cooler</span>
  <span m="3773571">use</span> <span m="3774059">is,</span> <span m="3774547">OK,</span>
  <span m="3775035">use</span> <span m="3775523">it</span> <span m="3776011">with</span>
  <span m="3776499">CoinJoin,</span> <span m="3776987">where</span> <span m="3777475">users</span>
  <span m="3777963">A,</span> <span m="3778451">B,</span> <span m="3778939">C,</span>
  <span m="3779427">and</span> <span m="3779915">D</span> <span m="3780403">all</span>
  <span m="3780891">contribute.</span></p><p><span m="3781380">They</span> <span m="3781723">all</span>
  <span m="3782066">have</span> <span m="3782409">an</span> <span m="3782752">input</span>
  <span m="3783095">with</span> <span m="3783438">the</span> <span m="3783781">same</span>
  <span m="3784124">amount</span> <span m="3784467">of</span> <span m="3784810">coins,</span>
  <span m="3785153">great.</span> <span m="3785496">And</span> <span m="3785839">they're</span>
  <span m="3786182">doing</span> <span m="3786525">CoinShuffle</span> <span m="3786869">to</span>
  <span m="3787174">shuffle</span> <span m="3787480">the</span> <span m="3787786">order</span>
  <span m="3788091">of</span> <span m="3788397">these</span> <span m="3788703">outputs.</span></p><p><span
  m="3789009">So</span> <span m="3789288">A</span> <span m="3789567">knows,</span>
  <span m="3789846">oh,</span> <span m="3790125">mine</span> <span m="3790404">is</span>
  <span m="3790683">G.</span> <span m="3790962">But</span> <span m="3791242">I</span>
  <span m="3791521">have</span> <span m="3791800">no</span> <span m="3792079">idea</span>
  <span m="3792358">about</span> <span m="3792637">E,</span> <span m="3792916">F,</span>
  <span m="3793196">and</span> <span m="3793475">H.</span> <span m="3793754">I</span>
  <span m="3794033">don't</span> <span m="3794312">know</span> <span m="3794591">the</span>
  <span m="3794870">mapping</span> <span m="3795150">other</span> <span m="3795528">than</span>
  <span m="3795906">my</span> <span m="3796284">own.</span> <span m="3796662">But,</span>
  <span m="3797040">hey,</span> <span m="3797419">my</span> <span m="3797797">output</span>
  <span m="3798175">is</span> <span m="3798553">in</span> <span m="3798931">there.</span>
  <span m="3799309">So</span> <span m="3799688">whatever</span> <span m="3800066">everyone</span>
  <span m="3800444">else</span> <span m="3800822">is</span> <span m="3801200">doing,</span>
  <span m="3801579">I</span> <span m="3801912">don't</span> <span m="3802245">care.</span></p><p><span
  m="3802579">But</span> <span m="3802872">I'm</span> <span m="3803165">good</span>
  <span m="3803458">with</span> <span m="3803751">this</span> <span m="3804044">transaction.</span>
  <span m="3804338">And</span> <span m="3804631">they</span> <span m="3804924">can</span>
  <span m="3805217">contribute</span> <span m="3805510">their</span> <span m="3805804">own</span>
  <span m="3806097">k</span> <span m="3806390">value</span> <span m="3806683">on</span>
  <span m="3806976">their</span> <span m="3807270">own</span> <span m="3807635">s</span>
  <span m="3808000">value.</span> <span m="3808365">And</span> <span m="3808730">then,</span>
  <span m="3809096">finally,</span> <span m="3809461">you</span> <span m="3809826">put</span>
  <span m="3810191">the</span> <span m="3810557">signature</span> <span m="3810922">at</span>
  <span m="3811287">the</span> <span m="3811652">bottom.</span> <span m="3812018">And</span>
  <span m="3812383">it</span> <span m="3812748">verifies</span> <span m="3813113">that</span>
  <span m="3813479">all</span> <span m="3814039">these</span> <span m="3814599">participants</span>
  <span m="3815159">have</span> <span m="3815719">signed.</span></p><p><span m="3816279">And</span>
  <span m="3816887">this</span> <span m="3817495">is</span> <span m="3818103">really</span>
  <span m="3818711">nice</span> <span m="3819319">because</span> <span m="3819928">it's</span>
  <span m="3820536">smaller.</span> <span m="3821144">This</span> <span m="3821752">would</span>
  <span m="3822360">be</span> <span m="3822969">250</span> <span m="3823577">bytes</span>
  <span m="3824185">worth</span> <span m="3824793">of</span> <span m="3825401">signature</span>
  <span m="3826010">data.</span> <span m="3826294">Now,</span> <span m="3826579">it's</span>
  <span m="3826864">just</span> <span m="3827148">65</span> <span m="3827433">bytes</span>
  <span m="3827718">sorts</span> <span m="3828003">of</span> <span m="3828287">signature</span>
  <span m="3828572">data</span> <span m="3828857">at</span> <span m="3829142">the</span>
  <span m="3829426">bottom.</span> <span m="3829711">So</span> <span m="3829996">you</span>
  <span m="3830281">save</span> <span m="3830565">on</span> <span m="3830850">fees.</span>
  <span m="3831135">You</span> <span m="3831420">save</span> <span m="3832156">on</span>
  <span m="3832893">space.</span></p><p><span m="3833630">Everyone</span> <span m="3834072">likes</span>
  <span m="3834515">this.</span> <span m="3834958">Yeah,</span> <span m="3835401">it's</span>
  <span m="3835843">cheaper</span> <span m="3836286">than</span> <span m="3836729">a</span>
  <span m="3837172">solo</span> <span m="3837615">transaction.</span> <span m="3838057">And</span>
  <span m="3838500">so</span> <span m="3838943">that</span> <span m="3839386">potentially</span>
  <span m="3839829">helps</span> <span m="3840109">scalability</span> <span m="3840390">and</span>
  <span m="3840670">privacy,</span> <span m="3840951">in</span> <span m="3841232">that</span>
  <span m="3841512">if</span> <span m="3841793">people</span> <span m="3842073">say,</span>
  <span m="3842354">I</span> <span m="3842635">want</span> <span m="3842915">to</span>
  <span m="3843196">do</span> <span m="3843476">something</span> <span m="3843757">cheaply,</span>
  <span m="3844038">I</span> <span m="3844478">will</span> <span m="3844918">connect</span>
  <span m="3845358">to</span> <span m="3845798">other</span> <span m="3846238">people</span>
  <span m="3846678">and</span> <span m="3847118">aggregate</span> <span m="3847558">my</span>
  <span m="3847998">signature</span> <span m="3848438">with</span> <span m="3848878">theirs.</span></p><p><span
  m="3849319">And</span> <span m="3849590">so</span> <span m="3849861">we'd</span>
  <span m="3850132">save</span> <span m="3850403">some</span> <span m="3850675">space</span>
  <span m="3850946">and</span> <span m="3851217">save</span> <span m="3851488">some</span>
  <span m="3851760">money.</span> <span m="3852031">And</span> <span m="3852302">maybe</span>
  <span m="3852573">I</span> <span m="3852845">don't</span> <span m="3853116">really</span>
  <span m="3853387">care</span> <span m="3853658">about</span> <span m="3853930">the</span>
  <span m="3854392">anonymity</span> <span m="3854854">thing.</span> <span m="3855316">Maybe</span>
  <span m="3855778">I'm</span> <span m="3856240">entering</span> <span m="3856702">into</span>
  <span m="3857165">a</span> <span m="3857627">transaction,</span> <span m="3858089">and</span>
  <span m="3858551">there's</span> <span m="3859013">some</span> <span m="3859475">people</span>
  <span m="3859937">doing</span> <span m="3860400">shady</span> <span m="3860756">deals</span>
  <span m="3861113">in</span> <span m="3861469">this</span> <span m="3861826">transaction.</span>
  <span m="3862182">But</span> <span m="3862539">I</span> <span m="3862895">don't</span>
  <span m="3863252">care.</span></p><p><span m="3863609">My</span> <span m="3863883">thing</span>
  <span m="3864157">gets</span> <span m="3864431">in</span> <span m="3864706">and</span>
  <span m="3864980">out.</span> <span m="3865254">And</span> <span m="3865528">I</span>
  <span m="3865803">save</span> <span m="3866077">money.</span> <span m="3866351">So</span>
  <span m="3866625">the</span> <span m="3866900">extension</span> <span m="3867174">of</span>
  <span m="3867448">this</span> <span m="3867722">would</span> <span m="3867997">be,</span>
  <span m="3868271">what</span> <span m="3868545">if</span> <span m="3868820">you</span>
  <span m="3869125">had</span> <span m="3869430">just</span> <span m="3869735">one</span>
  <span m="3870041">giant</span> <span m="3870346">transaction</span> <span m="3870651">in</span>
  <span m="3870957">every</span> <span m="3871262">block,</span> <span m="3871567">which</span>
  <span m="3871872">is</span> <span m="3872178">all</span> <span m="3872483">the</span>
  <span m="3872788">inputs</span> <span m="3873094">and</span> <span m="3873399">all</span>
  <span m="3873704">the</span> <span m="3874010">outputs,</span> <span m="3874573">and</span>
  <span m="3875137">there's</span> <span m="3875700">a</span> <span m="3876264">single</span>
  <span m="3876828">signature?</span> <span m="3877391">That</span> <span m="3877955">would</span>
  <span m="3878519">be</span> <span m="3879082">really</span> <span m="3879646">cool.</span></p><p><span
  m="3880210">There</span> <span m="3880904">are</span> <span m="3881599">techniques</span>
  <span m="3882294">to</span> <span m="3882989">do</span> <span m="3883684">that.</span>
  <span m="3884379">Maybe</span> <span m="3885074">next</span> <span m="3885769">time.</span>
  <span m="3886464">So</span> <span m="3887159">the</span> <span m="3887854">issue</span>
  <span m="3888549">is</span> <span m="3889244">it's</span> <span m="3889939">interactive,</span>
  <span m="3890634">in</span> <span m="3891329">that</span> <span m="3891626">you</span>
  <span m="3891923">have</span> <span m="3892221">to</span> <span m="3892518">know</span>
  <span m="3892816">about</span> <span m="3893113">all</span> <span m="3893410">the</span>
  <span m="3893708">other</span> <span m="3894005">inputs</span> <span m="3894303">and</span>
  <span m="3894600">all</span> <span m="3894897">the</span> <span m="3895195">other</span>
  <span m="3895492">outputs.</span></p><p><span m="3895790">So</span> <span m="3896098">if</span>
  <span m="3896407">it</span> <span m="3896716">were</span> <span m="3897024">non-interactive,</span>
  <span m="3897333">then</span> <span m="3897642">I</span> <span m="3897950">could</span>
  <span m="3898259">say,</span> <span m="3898568">oh,</span> <span m="3898876">well</span>
  <span m="3899185">there's</span> <span m="3899494">this</span> <span m="3899802">transaction</span>
  <span m="3900111">where</span> <span m="3900420">D</span> <span m="3900738">is</span>
  <span m="3901056">sending</span> <span m="3901374">coins</span> <span m="3901692">to</span>
  <span m="3902010">H.</span> <span m="3902328">And</span> <span m="3902646">there's</span>
  <span m="3902964">also</span> <span m="3903282">this</span> <span m="3903600">other</span>
  <span m="3903918">transaction</span> <span m="3904236">where</span> <span m="3904554">C</span>
  <span m="3904872">sounds</span> <span m="3905190">going</span> <span m="3905509">to</span>
  <span m="3906127">G.</span> <span m="3906746">And</span> <span m="3907365">they've</span>
  <span m="3907984">got</span> <span m="3908603">their</span> <span m="3909222">own</span>
  <span m="3909841">signatures.</span></p><p><span m="3910460">I'm</span> <span m="3910664">not</span>
  <span m="3910868">either</span> <span m="3911072">of</span> <span m="3911276">these</span>
  <span m="3911480">people.</span> <span m="3911684">I</span> <span m="3911888">didn't</span>
  <span m="3912092">do</span> <span m="3912297">anything</span> <span m="3912501">with</span>
  <span m="3912705">these</span> <span m="3912909">signatures.</span> <span m="3913113">But</span>
  <span m="3913317">if</span> <span m="3913521">I</span> <span m="3913725">could</span>
  <span m="3913930">take</span> <span m="3914303">those</span> <span m="3914677">two</span>
  <span m="3915050">things</span> <span m="3915424">and</span> <span m="3915797">combine</span>
  <span m="3916171">the</span> <span m="3916545">signature</span> <span m="3916918">non-interactively,</span>
  <span m="3917292">then</span> <span m="3917665">I</span> <span m="3918039">could</span>
  <span m="3918412">just</span> <span m="3918786">basically</span> <span m="3919160">take</span>
  <span m="3919423">all</span> <span m="3919687">the</span> <span m="3919951">transactions</span>
  <span m="3920215">in</span> <span m="3920479">my</span> <span m="3920743">meme</span>
  <span m="3921007">pool,</span> <span m="3921271">squish</span> <span m="3921535">them</span>
  <span m="3921799">into</span> <span m="3922063">one</span> <span m="3922327">transaction</span>
  <span m="3922591">with</span> <span m="3922855">one</span> <span m="3923119">signature,</span>
  <span m="3923537">and</span> <span m="3923955">put</span> <span m="3924374">that</span>
  <span m="3924792">in</span> <span m="3925211">my</span> <span m="3925629">block.</span>
  <span m="3926047">That</span> <span m="3926466">would</span> <span m="3926884">be</span>
  <span m="3927303">really</span> <span m="3927721">cool.</span></p><p><span m="3928140">But</span>
  <span m="3928468">the</span> <span m="3928797">issue</span> <span m="3929126">there</span>
  <span m="3929454">is,</span> <span m="3929783">one,</span> <span m="3930112">the</span>
  <span m="3930440">signatures</span> <span m="3930769">have</span> <span m="3931098">to</span>
  <span m="3931426">be</span> <span m="3931755">interactive.</span> <span m="3932084">And,</span>
  <span m="3932412">two,</span> <span m="3932741">they're</span> <span m="3933070">on</span>
  <span m="3933383">different</span> <span m="3933697">messages.</span> <span m="3934011">So</span>
  <span m="3934325">in</span> <span m="3934639">the</span> <span m="3934953">case</span>
  <span m="3935267">of</span> <span m="3935581">C</span> <span m="3935895">sending</span>
  <span m="3936209">to</span> <span m="3936523">G,</span> <span m="3936837">it's</span>
  <span m="3937151">a</span> <span m="3937465">message</span> <span m="3937779">of</span>
  <span m="3938093">C</span> <span m="3938407">to</span> <span m="3938721">G.</span>
  <span m="3939035">And</span> <span m="3939349">then</span> <span m="3939753">D</span>
  <span m="3940157">sending</span> <span m="3940562">to</span> <span m="3940966">H,</span>
  <span m="3941371">It's</span> <span m="3941775">on</span> <span m="3942180">that</span>
  <span m="3942584">message.</span></p><p><span m="3942989">There</span> <span m="3943599">are</span>
  <span m="3944210">techniques,</span> <span m="3944821">though.</span> <span m="3945431">So</span>
  <span m="3946042">BLS</span> <span m="3946653">signatures</span> <span m="3947264">do</span>
  <span m="3947874">allow</span> <span m="3948485">you</span> <span m="3949096">to</span>
  <span m="3949707">do</span> <span m="3950317">this,</span> <span m="3950928">so</span>
  <span m="3951539">non-interactive</span> <span m="3952150">aggregation</span> <span
  m="3952453">of</span> <span m="3952757">signatures.</span> <span m="3953060">Which</span>
  <span m="3953364">would</span> <span m="3953667">be</span> <span m="3953971">really</span>
  <span m="3954275">cool,</span> <span m="3954578">because</span> <span m="3954882">then</span>
  <span m="3955185">a</span> <span m="3955489">block</span> <span m="3955792">would</span>
  <span m="3956096">only</span> <span m="3956400">need</span> <span m="3956754">one</span>
  <span m="3957109">signature.</span> <span m="3957464">And</span> <span m="3957818">then</span>
  <span m="3958173">BLS</span> <span m="3958528">signatures</span> <span m="3958882">themselves</span>
  <span m="3959237">are</span> <span m="3959592">a</span> <span m="3959946">single</span>
  <span m="3960301">point,</span> <span m="3960656">not</span> <span m="3961010">a</span>
  <span m="3961365">point</span> <span m="3961720">in</span> <span m="3962083">a</span>
  <span m="3962447">scalar.</span> <span m="3962811">So</span> <span m="3963175">it</span>
  <span m="3963539">would</span> <span m="3963903">just</span> <span m="3964267">be</span>
  <span m="3964631">32</span> <span m="3964995">bytes.</span></p><p><span m="3965359">Well,</span>
  <span m="3965730">you'd</span> <span m="3966102">probably</span> <span m="3966474">use</span>
  <span m="3966846">a</span> <span m="3967218">different</span> <span m="3967590">curve.</span>
  <span m="3967962">You'd</span> <span m="3968334">have</span> <span m="3968705">to.</span>
  <span m="3969077">But,</span> <span m="3969449">yeah,</span> <span m="3969821">the</span>
  <span m="3970193">idea</span> <span m="3970565">of</span> <span m="3970937">having</span>
  <span m="3971309">these</span> <span m="3971899">tiny</span> <span m="3972489">signatures</span>
  <span m="3973079">that's</span> <span m="3973669">satisfy</span> <span m="3974259">proof</span>
  <span m="3974849">for</span> <span m="3975439">the</span> <span m="3976029">entire</span>
  <span m="3976619">set</span> <span m="3977209">is</span> <span m="3977799">really</span>
  <span m="3978389">cool.</span></p><p><span m="3978979">So</span> <span m="3979594">this</span>
  <span m="3980209">is</span> <span m="3980825">a</span> <span m="3981440">cool</span>
  <span m="3982055">idea.</span> <span m="3982671">So</span> <span m="3983286">you</span>
  <span m="3983901">saying</span> <span m="3984517">there</span> <span m="3985132">isn't</span>
  <span m="3985747">software?</span> <span m="3986363">Or</span> <span m="3986978">it's</span>
  <span m="3987593">not</span> <span m="3988209">on</span> <span m="3988824">GitHub?</span></p><p><span
  m="3989440">OK,</span> <span m="3989909">so</span> <span m="3990378">the</span>
  <span m="3990848">idea</span> <span m="3991317">is,</span> <span m="3991787">there</span>
  <span m="3992256">is</span> <span m="3992725">a</span> <span m="3993195">bunch</span>
  <span m="3993664">of</span> <span m="3994134">software</span> <span m="3994603">for</span>
  <span m="3995073">this</span> <span m="3995542">that</span> <span m="3996011">mostly</span>
  <span m="3996481">SIPPA--</span> <span m="3996950">or</span> <span m="3997420">Peter</span>
  <span m="3997889">Wool,</span> <span m="3998359">his</span> <span m="3998629">name</span>
  <span m="3998899">on</span> <span m="3999169">the</span> <span m="3999439">internet</span>
  <span m="3999709">is</span> <span m="3999979">SIPPA.</span> <span m="4000249">And</span>
  <span m="4000519">he</span> <span m="4000789">told</span> <span m="4001059">me</span>
  <span m="4001329">what</span> <span m="4001599">that</span> <span m="4001869">stood</span>
  <span m="4002139">for.</span> <span m="4002409">And</span> <span m="4002679">it</span>
  <span m="4002949">was</span> <span m="4003219">some</span> <span m="4003490">like</span>
  <span m="4003806">super</span> <span m="4004123">cheesy</span> <span m="4004439">thing</span>
  <span m="4004756">he</span> <span m="4005072">made</span> <span m="4005389">when</span>
  <span m="4005705">he</span> <span m="4006022">was</span> <span m="4006338">in</span>
  <span m="4006655">middle</span> <span m="4006971">school.</span></p><p><span m="4007288">Anyway,</span>
  <span m="4007664">he</span> <span m="4008040">has</span> <span m="4008416">been</span>
  <span m="4008792">working</span> <span m="4009168">on</span> <span m="4009545">this</span>
  <span m="4009921">kind</span> <span m="4010297">of</span> <span m="4010673">software.</span>
  <span m="4011049">So</span> <span m="4011425">has</span> <span m="4011802">Greg,</span>
  <span m="4012178">that</span> <span m="4012554">guy</span> <span m="4012930">who</span>
  <span m="4013306">five</span> <span m="4013682">years</span> <span m="4014059">ago</span>
  <span m="4014510">wrote</span> <span m="4014962">about</span> <span m="4015413">this</span>
  <span m="4015865">stuff.</span> <span m="4016316">A</span> <span m="4016768">couple</span>
  <span m="4017219">of</span> <span m="4017671">people</span> <span m="4018122">have</span>
  <span m="4018574">been</span> <span m="4019025">working</span> <span m="4019477">on</span>
  <span m="4019928">this.</span></p><p><span m="4020380">It's</span> <span m="4020657">not</span>
  <span m="4020935">publicly</span> <span m="4021212">available</span> <span m="4021490">code,</span>
  <span m="4021767">which</span> <span m="4022045">is</span> <span m="4022322">kind</span>
  <span m="4022600">of</span> <span m="4022877">weird.</span> <span m="4023155">But</span>
  <span m="4023432">the</span> <span m="4023710">reason</span> <span m="4023987">is</span>
  <span m="4024265">that</span> <span m="4024542">they're</span> <span m="4024820">working</span>
  <span m="4025159">on</span> <span m="4025499">Schnorr</span> <span m="4025839">signatures</span>
  <span m="4026179">and</span> <span m="4026519">aggregation.</span> <span m="4026859">And</span>
  <span m="4027199">it</span> <span m="4027539">was</span> <span m="4027879">on</span>
  <span m="4028219">GitHub</span> <span m="4028559">in</span> <span m="4028899">like</span>
  <span m="4029239">a</span> <span m="4029579">branch</span> <span m="4029919">of</span>
  <span m="4030259">lib</span> <span m="4030599">sec</span> <span m="4030957">p,</span>
  <span m="4031316">the</span> <span m="4031675">repo</span> <span m="4032034">they're</span>
  <span m="4032393">using.</span> <span m="4032752">And</span> <span m="4033111">then</span>
  <span m="4033470">all</span> <span m="4033828">these</span> <span m="4034187">altcoins</span>
  <span m="4034546">were</span> <span m="4034905">taking</span> <span m="4035264">the</span>
  <span m="4035623">code,</span> <span m="4035982">and</span> <span m="4036341">putting</span>
  <span m="4036700">it</span> <span m="4037121">into</span> <span m="4037543">their</span>
  <span m="4037965">altcoins,</span> <span m="4038386">and</span> <span m="4038808">saying,</span>
  <span m="4039230">hey,</span> <span m="4039652">we</span> <span m="4040073">support</span>
  <span m="4040495">Schnorr</span> <span m="4040917">signatures.</span></p><p><span
  m="4041339">So</span> <span m="4041610">for</span> <span m="4041882">example</span>
  <span m="4042154">the</span> <span m="4042426">rogue</span> <span m="4042698">key</span>
  <span m="4042970">attack,</span> <span m="4043242">it</span> <span m="4043514">was</span>
  <span m="4043786">the</span> <span m="4044058">simple</span> <span m="4044330">version,</span>
  <span m="4044602">which</span> <span m="4044874">didn't</span> <span m="4045146">have</span>
  <span m="4045418">this</span> <span m="4045690">multiplied</span> <span m="4046018">by</span>
  <span m="4046347">the</span> <span m="4046676">hash</span> <span m="4047005">of</span>
  <span m="4047333">the</span> <span m="4047662">pub</span> <span m="4047991">key.</span>
  <span m="4048320">And</span> <span m="4048648">they</span> <span m="4048977">were</span>
  <span m="4049306">like,</span> <span m="4049635">wait,</span> <span m="4049963">no,</span>
  <span m="4050292">don't,</span> <span m="4050621">we're</span> <span m="4050950">working</span>
  <span m="4051279">on</span> <span m="4051615">this</span> <span m="4051952">software.</span>
  <span m="4052289">But</span> <span m="4052626">we</span> <span m="4052962">know</span>
  <span m="4053299">all</span> <span m="4053636">of</span> <span m="4053973">these</span>
  <span m="4054309">problems</span> <span m="4054646">with</span> <span m="4054983">it.</span></p><p><span
  m="4055320">You</span> <span m="4055642">can't</span> <span m="4055964">actually</span>
  <span m="4056286">use</span> <span m="4056608">this</span> <span m="4056930">for</span>
  <span m="4057252">signature</span> <span m="4057574">aggregation.</span> <span m="4057896">We're</span>
  <span m="4058218">just</span> <span m="4058540">sort</span> <span m="4058862">of</span>
  <span m="4059184">playing</span> <span m="4059506">around,</span> <span m="4059829">and</span>
  <span m="4060370">trying</span> <span m="4060912">different</span> <span m="4061454">things.</span>
  <span m="4061995">And</span> <span m="4062537">so</span> <span m="4063079">they</span>
  <span m="4063620">actually</span> <span m="4064162">pulled</span> <span m="4064704">it</span>
  <span m="4065245">from</span> <span m="4065787">GitHub.</span></p><p><span m="4066329">And</span>
  <span m="4066762">so</span> <span m="4067195">I</span> <span m="4067628">have</span>
  <span m="4068061">seen</span> <span m="4068494">it.</span> <span m="4068927">You</span>
  <span m="4069361">can</span> <span m="4069794">see</span> <span m="4070227">the</span>
  <span m="4070660">old</span> <span m="4071093">stuff.</span> <span m="4071526">Yeah,</span>
  <span m="4071960">the</span> <span m="4072393">three</span> <span m="4072826">years</span>
  <span m="4073259">ago</span> <span m="4073692">stuff</span> <span m="4074125">that</span>
  <span m="4074559">doesn't</span> <span m="4074943">have</span> <span m="4075328">any</span>
  <span m="4075712">of</span> <span m="4076097">this</span> <span m="4076482">delinearization,</span>
  <span m="4076866">or</span> <span m="4077251">this</span> <span m="4077635">thing</span>
  <span m="4078020">that</span> <span m="4078405">prevent</span> <span m="4078789">Wagner's</span>
  <span m="4079174">attack,</span> <span m="4079559">all</span> <span m="4080122">of</span>
  <span m="4080686">that</span> <span m="4081250">stuff</span> <span m="4081814">is</span>
  <span m="4082377">not</span> <span m="4082941">in</span> <span m="4083505">there.</span></p><p><span
  m="4084069">AUDIENCE:</span> <span m="4084509">That's</span> <span m="4084949">something</span>
  <span m="4085389">that</span> <span m="4085829">sounds</span> <span m="4086269">really</span>
  <span m="4086709">cool.</span> <span m="4087149">But</span> <span m="4087589">that's</span>
  <span m="4088029">something</span> <span m="4088469">[INAUDIBLE].</span></p><p><span
  m="4088910">TADGE</span> <span m="4089298">DRYJA:</span> <span m="4089687">No</span>
  <span m="4090076">that's</span> <span m="4090465">not</span> <span m="4090853">what</span>
  <span m="4091242">they--</span> <span m="4091631">OK,</span> <span m="4092020">maybe</span>
  <span m="4092408">that's</span> <span m="4092797">a</span> <span m="4093186">cool</span>
  <span m="4093575">attack.</span> <span m="4093963">But</span> <span m="4094352">they</span>
  <span m="4094741">were</span> <span m="4095130">like,</span> <span m="4095401">oh,</span>
  <span m="4095672">shoot,</span> <span m="4095943">no.</span> <span m="4096214">But</span>
  <span m="4096485">it</span> <span m="4096756">said</span> <span m="4097027">in</span>
  <span m="4097298">their</span> <span m="4097570">repo,</span> <span m="4097841">do</span>
  <span m="4098112">not</span> <span m="4098383">use</span> <span m="4098654">this.</span>
  <span m="4098925">This</span> <span m="4099196">is</span> <span m="4099467">research</span>
  <span m="4099738">code.</span></p><p><span m="4100010">Do</span> <span m="4100373">not</span>
  <span m="4100737">use</span> <span m="4101101">this</span> <span m="4101465">in</span>
  <span m="4101829">production.</span> <span m="4102193">There</span> <span m="4102557">are</span>
  <span m="4102921">known</span> <span m="4103285">vulnerabilities.</span></p><p><span
  m="4103649">But</span> <span m="4104012">people</span> <span m="4104376">are</span>
  <span m="4104739">like,</span> <span m="4105103">whatever,</span> <span m="4105466">people</span>
  <span m="4105830">didn't</span> <span m="4106193">care.</span> <span m="4106557">Well,</span>
  <span m="4106920">yeah,</span> <span m="4107284">there's</span> <span m="4107647">some</span>
  <span m="4108011">esoteric</span> <span m="4108374">edge</span> <span m="4108738">case</span>
  <span m="4109035">vulnerability,</span> <span m="4109332">but</span> <span m="4109629">I'm</span>
  <span m="4109926">going</span> <span m="4110224">to</span> <span m="4110521">solve</span>
  <span m="4110818">that,</span> <span m="4111115">because</span> <span m="4111412">xyz.</span>
  <span m="4111710">So</span> <span m="4112007">they</span> <span m="4112304">actually</span>
  <span m="4112601">pulled</span> <span m="4112899">the</span> <span m="4113919">code.</span></p><p><span
  m="4114940">They</span> <span m="4115303">are</span> <span m="4115666">working</span>
  <span m="4116029">on</span> <span m="4116393">the</span> <span m="4116756">code.</span>
  <span m="4117119">I</span> <span m="4117482">mean,</span> <span m="4117846">the</span>
  <span m="4118209">code</span> <span m="4118572">works.</span> <span m="4118936">I've</span>
  <span m="4119299">seen</span> <span m="4119662">it.</span> <span m="4120025">But</span>
  <span m="4120389">they</span> <span m="4120752">are</span> <span m="4121115">very</span>
  <span m="4121479">sort</span> <span m="4121730">of</span> <span m="4121982">like,</span>
  <span m="4122234">we</span> <span m="4122485">don't</span> <span m="4122737">want</span>
  <span m="4122989">to</span> <span m="4123240">put</span> <span m="4123492">it</span>
  <span m="4123744">publicly</span> <span m="4123995">until</span> <span m="4124247">we're</span>
  <span m="4124499">sort</span> <span m="4124750">of</span> <span m="4125002">saying,</span>
  <span m="4125254">OK,</span> <span m="4125505">here's</span> <span m="4125757">our</span>
  <span m="4126009">final</span> <span m="4126211">version</span> <span m="4126413">that</span>
  <span m="4126615">we</span> <span m="4126817">want</span> <span m="4127020">to</span>
  <span m="4127222">put</span> <span m="4127424">in</span> <span m="4127626">bitcoin,</span>
  <span m="4127829">because</span> <span m="4128031">they</span> <span m="4128233">know</span>
  <span m="4128435">as</span> <span m="4128637">soon</span> <span m="4128840">as</span>
  <span m="4129042">they</span> <span m="4129244">sort</span> <span m="4129446">of</span>
  <span m="4129649">put</span> <span m="4129954">it</span> <span m="4130260">out</span>
  <span m="4130566">there</span> <span m="4130871">for</span> <span m="4131177">review,</span>
  <span m="4131483">all</span> <span m="4131788">these</span> <span m="4132094">altcoins</span>
  <span m="4132400">will</span> <span m="4132705">take--</span> <span m="4133011">I</span>
  <span m="4133317">mean,</span> <span m="4133622">you've</span> <span m="4133928">implemented</span>
  <span m="4134234">this</span> <span m="4134540">in--</span> <span m="4135209">yeah.</span>
  <span m="4135879">Not</span> <span m="4136549">in</span> <span m="4137219">vertcoin,</span>
  <span m="4137889">in</span> <span m="4138559">crypto</span> <span m="4139229">kernel.</span>
  <span m="4139899">And</span> <span m="4140569">you</span> <span m="4141239">do</span>
  <span m="4141909">use</span> <span m="4142579">the</span> <span m="4143249">u</span>
  <span m="4143919">sig?</span></p><p><span m="4144589">AUDIENCE:</span> <span m="4145005">I</span>
  <span m="4145421">will</span> <span m="4145837">do</span> <span m="4146253">now.</span></p><p><span
  m="4146670">TADGE</span> <span m="4146983">DRYJA:</span> <span m="4147297">Oh,</span>
  <span m="4147611">OK,</span> <span m="4147925">cool,</span> <span m="4148238">let</span>
  <span m="4148552">me</span> <span m="4148866">know.</span> <span m="4149180">So</span>
  <span m="4149494">they</span> <span m="4149807">know</span> <span m="4150121">that</span>
  <span m="4150435">people</span> <span m="4150749">are</span> <span m="4151062">going</span>
  <span m="4151376">to</span> <span m="4151690">use</span> <span m="4152004">this,</span>
  <span m="4152318">because</span> <span m="4152683">it's</span> <span m="4153049">a</span>
  <span m="4153415">cool</span> <span m="4153781">signature</span> <span m="4154147">scheme.</span>
  <span m="4154513">And</span> <span m="4154879">I've</span> <span m="4155244">talked</span>
  <span m="4155610">about</span> <span m="4155976">this</span> <span m="4156342">multiple</span>
  <span m="4156708">times</span> <span m="4157074">before.</span></p><p><span m="4157440">Once</span>
  <span m="4157692">you</span> <span m="4157944">have</span> <span m="4158196">this</span>
  <span m="4158448">Schnorr</span> <span m="4158700">signature</span> <span m="4158952">equation,</span>
  <span m="4159204">there's</span> <span m="4159456">all</span> <span m="4159708">these</span>
  <span m="4159960">other</span> <span m="4160212">cool</span> <span m="4160464">things</span>
  <span m="4160716">you</span> <span m="4160968">can</span> <span m="4161220">do</span>
  <span m="4161727">with</span> <span m="4162234">your</span> <span m="4162742">addresses</span>
  <span m="4163249">and</span> <span m="4163756">things</span> <span m="4164264">like</span>
  <span m="4164771">that.</span></p><p><span m="4165279">And</span> <span m="4165610">so</span>
  <span m="4165942">the</span> <span m="4166274">idea</span> <span m="4166606">here</span>
  <span m="4166938">is</span> <span m="4167269">scalability</span> <span m="4167601">is</span>
  <span m="4167933">one</span> <span m="4168265">that,</span> <span m="4168597">OK,</span>
  <span m="4168929">now</span> <span m="4169260">we</span> <span m="4169592">can</span>
  <span m="4169924">combine</span> <span m="4170256">things,</span> <span m="4170588">make</span>
  <span m="4170920">it</span> <span m="4171210">smaller.</span> <span m="4171501">And</span>
  <span m="4171791">also,</span> <span m="4172082">we</span> <span m="4172372">can</span>
  <span m="4172663">hopefully</span> <span m="4172953">help</span> <span m="4173244">privacy</span>
  <span m="4173534">this</span> <span m="4173825">way,</span> <span m="4174115">in</span>
  <span m="4174406">that</span> <span m="4174696">people</span> <span m="4174987">who</span>
  <span m="4175277">are</span> <span m="4175568">not</span> <span m="4175859">particularly</span>
  <span m="4176157">concerned</span> <span m="4176456">with</span> <span m="4176755">their</span>
  <span m="4177053">anonymity</span> <span m="4177352">will</span> <span m="4177651">say,</span>
  <span m="4177949">yeah,</span> <span m="4178248">I</span> <span m="4178547">still</span>
  <span m="4178845">want</span> <span m="4179144">to</span> <span m="4179443">use</span>
  <span m="4179741">it,</span> <span m="4180040">because</span> <span m="4180339">I</span>
  <span m="4180704">can</span> <span m="4181070">save</span> <span m="4181435">$1</span>
  <span m="4181801">on</span> <span m="4182167">fees.</span> <span m="4182532">So,</span>
  <span m="4182898">yeah,</span> <span m="4183263">I'll</span> <span m="4183629">join</span>
  <span m="4183995">this</span> <span m="4184360">transaction</span> <span m="4184726">with</span>
  <span m="4185091">a</span> <span m="4185457">bunch</span> <span m="4185823">of</span>
  <span m="4186188">other</span> <span m="4186554">people.</span></p><p><span m="4186920">And</span>
  <span m="4187186">then</span> <span m="4187453">you've</span> <span m="4187720">got</span>
  <span m="4187986">the</span> <span m="4188253">people</span> <span m="4188520">who</span>
  <span m="4188786">actually</span> <span m="4189053">want</span> <span m="4189320">anonymity</span>
  <span m="4189586">are</span> <span m="4189853">like,</span> <span m="4190120">great,</span>
  <span m="4190386">these</span> <span m="4190653">are</span> <span m="4190920">exactly</span>
  <span m="4191242">the</span> <span m="4191565">people</span> <span m="4191888">I</span>
  <span m="4192210">want</span> <span m="4192533">to</span> <span m="4192856">be</span>
  <span m="4193178">associated</span> <span m="4193501">with,</span> <span m="4193824">the</span>
  <span m="4194146">people</span> <span m="4194469">who</span> <span m="4194792">don't</span>
  <span m="4195114">particularly</span> <span m="4195437">care</span> <span m="4195760">about</span>
  <span m="4196200">anonymity.</span> <span m="4196640">So</span> <span m="4197080">it</span>
  <span m="4197520">seems</span> <span m="4197960">like</span> <span m="4198400">a</span>
  <span m="4198840">win-win.</span></p><p><span m="4199280">Right</span> <span m="4199910">now,</span>
  <span m="4200540">all</span> <span m="4201170">the</span> <span m="4201800">software</span>
  <span m="4202430">requires</span> <span m="4203060">a</span> <span m="4203690">regular</span>
  <span m="4204320">old</span> <span m="4204950">signature.</span> <span m="4205580">So,</span>
  <span m="4206210">for</span> <span m="4206840">example,</span> <span m="4207470">if</span>
  <span m="4208100">these</span> <span m="4208730">are</span> <span m="4209360">outputs</span>
  <span m="4209691">that</span> <span m="4210023">are</span> <span m="4210355">currently</span>
  <span m="4210687">being</span> <span m="4211019">used,</span> <span m="4211351">and</span>
  <span m="4211683">you</span> <span m="4212015">do</span> <span m="4212347">this,</span>
  <span m="4212679">I'd</span> <span m="4213011">validate</span> <span m="4213343">the</span>
  <span m="4213675">output</span> <span m="4214007">one</span> <span m="4214339">at</span>
  <span m="4214671">a</span> <span m="4215171">time.</span></p><p><span m="4215671">And</span>
  <span m="4215876">I</span> <span m="4216082">say,</span> <span m="4216287">OK,</span>
  <span m="4216493">I'm</span> <span m="4216698">looking</span> <span m="4216904">at</span>
  <span m="4217109">this</span> <span m="4217315">output,</span> <span m="4217521">looking</span>
  <span m="4217726">at</span> <span m="4217932">this</span> <span m="4218137">input,</span>
  <span m="4218343">there's</span> <span m="4218548">no</span> <span m="4218754">signature</span>
  <span m="4218960">at</span> <span m="4219265">all,</span> <span m="4219570">fail.</span>
  <span m="4219875">OK,</span> <span m="4220181">the</span> <span m="4220486">whole</span>
  <span m="4220791">transaction</span> <span m="4221097">fails.</span> <span m="4221402">So</span>
  <span m="4221707">you</span> <span m="4222012">need</span> <span m="4222318">a</span>
  <span m="4222623">new</span> <span m="4222928">output</span> <span m="4223234">type,</span>
  <span m="4223539">which</span> <span m="4223844">says,</span> <span m="4224150">OK,</span>
  <span m="4224615">I'm</span> <span m="4225080">using</span> <span m="4225546">this</span>
  <span m="4226011">new</span> <span m="4226477">aggregate</span> <span m="4226942">signature.</span>
  <span m="4227407">So,</span> <span m="4227873">actually,</span> <span m="4228338">look</span>
  <span m="4228804">at</span> <span m="4229269">all</span> <span m="4229734">the</span>
  <span m="4230200">inputs.</span> <span m="4230665">Don't</span> <span m="4231131">validate</span>
  <span m="4231526">them</span> <span m="4231921">at</span> <span m="4232316">all,</span>
  <span m="4232712">and</span> <span m="4233107">just</span> <span m="4233502">validate</span>
  <span m="4233898">at</span> <span m="4234293">the</span> <span m="4234688">end</span>
  <span m="4235084">at</span> <span m="4235479">the</span> <span m="4235874">bottom.</span></p><p><span
  m="4236270">So</span> <span m="4236772">that's</span> <span m="4237274">going</span>
  <span m="4237777">to</span> <span m="4238279">be</span> <span m="4238782">some</span>
  <span m="4239284">different</span> <span m="4239787">code.</span> <span m="4240289">And</span>
  <span m="4240791">you</span> <span m="4241294">can't</span> <span m="4241796">retroactively</span>
  <span m="4242299">say,</span> <span m="4242801">OK,</span> <span m="4243304">all</span>
  <span m="4243806">the</span> <span m="4244309">existing</span> <span m="4244531">outputs</span>
  <span m="4244753">we</span> <span m="4244975">can</span> <span m="4245197">now</span>
  <span m="4245419">spend</span> <span m="4245641">with</span> <span m="4245863">this</span>
  <span m="4246085">new</span> <span m="4246307">signature</span> <span m="4246529">scheme.</span>
  <span m="4246751">You</span> <span m="4246973">can't</span> <span m="4247195">really</span>
  <span m="4247417">do</span> <span m="4247639">that.</span> <span m="4248076">So</span>
  <span m="4248514">we'll</span> <span m="4248951">have</span> <span m="4249389">to</span>
  <span m="4249826">make</span> <span m="4250264">new</span> <span m="4250701">addresses.</span></p><p><span
  m="4251139">And</span> <span m="4251489">the</span> <span m="4251839">new</span>
  <span m="4252189">addresses</span> <span m="4252539">will</span> <span m="4252889">be</span>
  <span m="4253239">bc1v,</span> <span m="4253589">instead</span> <span m="4253939">of</span>
  <span m="4254289">q,</span> <span m="4254639">new</span> <span m="4254989">address</span>
  <span m="4255339">type.</span> <span m="4255689">And</span> <span m="4256039">then</span>
  <span m="4256389">we</span> <span m="4256739">send</span> <span m="4257089">to</span>
  <span m="4257440">that.</span> <span m="4257715">And</span> <span m="4257990">now,</span>
  <span m="4258266">you're</span> <span m="4258541">allowed</span> <span m="4258816">to</span>
  <span m="4259092">spend</span> <span m="4259367">from</span> <span m="4259642">it</span>
  <span m="4259918">using</span> <span m="4260193">aggregate</span> <span m="4260468">signatures.</span>
  <span m="4260744">So</span> <span m="4261019">all</span> <span m="4261294">that</span>
  <span m="4261570">software</span> <span m="4262122">is</span> <span m="4262675">mostly</span>
  <span m="4263227">there.</span></p><p><span m="4263780">But</span> <span m="4264100">it</span>
  <span m="4264421">might</span> <span m="4264741">take</span> <span m="4265062">a</span>
  <span m="4265382">while.</span> <span m="4265703">You've</span> <span m="4266023">got</span>
  <span m="4266344">to</span> <span m="4266665">get</span> <span m="4266985">everyone</span>
  <span m="4267306">on</span> <span m="4267626">board.</span> <span m="4267947">I'm</span>
  <span m="4268267">curious</span> <span m="4268588">to</span> <span m="4268908">see</span>
  <span m="4269229">what</span> <span m="4269550">people</span> <span m="4269925">will</span>
  <span m="4270300">complain</span> <span m="4270675">about.</span> <span m="4271050">Segwit</span>
  <span m="4271426">was</span> <span m="4271801">a</span> <span m="4272176">little</span>
  <span m="4272551">bit</span> <span m="4272927">more</span> <span m="4273302">like,</span>
  <span m="4273677">there's</span> <span m="4274052">a</span> <span m="4274428">lot</span>
  <span m="4274803">to</span> <span m="4275178">complain</span> <span m="4275553">about.</span></p><p><span
  m="4275929">Even</span> <span m="4276326">I</span> <span m="4276723">don't</span>
  <span m="4277120">like</span> <span m="4277517">parts</span> <span m="4277915">of</span>
  <span m="4278312">Segwit.</span> <span m="4278709">There's</span> <span m="4279106">a</span>
  <span m="4279504">lot</span> <span m="4279901">of</span> <span m="4280298">parts</span>
  <span m="4280695">I</span> <span m="4281092">don't</span> <span m="4281490">like</span>
  <span m="4281887">and</span> <span m="4282284">won't</span> <span m="4282681">use.</span></p><p><span
  m="4283079">But</span> <span m="4283285">this</span> <span m="4283492">seems</span>
  <span m="4283698">like</span> <span m="4283905">a</span> <span m="4284111">sort</span>
  <span m="4284318">of</span> <span m="4284524">clear</span> <span m="4284731">win,</span>
  <span m="4284937">where</span> <span m="4285144">it's</span> <span m="4285350">like,</span>
  <span m="4285557">great,</span> <span m="4285763">you</span> <span m="4285970">can</span>
  <span m="4286176">aggregate</span> <span m="4286383">signatures,</span> <span m="4286590">do</span>
  <span m="4286980">all</span> <span m="4287371">these</span> <span m="4287761">cool</span>
  <span m="4288152">things.</span> <span m="4288542">I'm</span> <span m="4288933">guessing</span>
  <span m="4289324">there</span> <span m="4289714">will</span> <span m="4290105">be</span>
  <span m="4290495">people</span> <span m="4290886">saying,</span> <span m="4291277">this</span>
  <span m="4291667">is</span> <span m="4292058">bad.</span> <span m="4292448">And</span>
  <span m="4292839">saying,</span> <span m="4293230">no,</span> <span m="4293781">because</span>
  <span m="4294332">Satoshi's</span> <span m="4294883">vision</span> <span m="4295435">is</span>
  <span m="4295986">one</span> <span m="4296537">signature,</span> <span m="4297088">one</span>
  <span m="4297640">input.</span> <span m="4298191">A</span> <span m="4298742">coin</span>
  <span m="4299293">is</span> <span m="4299845">a</span> <span m="4300396">chain</span>
  <span m="4300947">of</span> <span m="4301498">signatures.</span></p><p><span m="4302050">And</span>
  <span m="4302316">this</span> <span m="4302583">coin</span> <span m="4302850">has</span>
  <span m="4303116">no</span> <span m="4303383">signatures.</span></p><p><span m="4303650">I'm</span>
  <span m="4303980">guessing.</span> <span m="4304310">I</span> <span m="4304640">don't</span>
  <span m="4304970">know</span> <span m="4305300">what'll</span> <span m="4305630">happen.</span>
  <span m="4305960">Or</span> <span m="4306290">maybe</span> <span m="4306620">it</span>
  <span m="4306950">might</span> <span m="4307280">be</span> <span m="4307610">smooth,</span>
  <span m="4307940">and</span> <span m="4308270">everyone</span> <span m="4308600">is</span>
  <span m="4308966">sort</span> <span m="4309333">of</span> <span m="4309700">like,</span>
  <span m="4310067">yeah,</span> <span m="4310434">this</span> <span m="4310800">is</span>
  <span m="4311167">obviously</span> <span m="4311534">better,</span> <span m="4311901">great</span>
  <span m="4312268">paper,</span> <span m="4312634">great</span> <span m="4313001">math,</span>
  <span m="4313368">great</span> <span m="4313735">idea.</span> <span m="4314102">Let's</span>
  <span m="4314469">all</span> <span m="4314933">activate</span> <span m="4315397">it</span>
  <span m="4315861">and</span> <span m="4316325">use</span> <span m="4316789">bitcoin</span>
  <span m="4317253">this</span> <span m="4317717">way.</span> <span m="4318181">Who</span>
  <span m="4318645">knows?</span></p><p><span m="4319110">So</span> <span m="4319509">we'll</span>
  <span m="4319908">see.</span> <span m="4320308">It's</span> <span m="4320707">pretty</span>
  <span m="4321107">cool</span> <span m="4321506">software,</span> <span m="4321906">though.</span>
  <span m="4322305">And</span> <span m="4322705">you</span> <span m="4323104">can</span>
  <span m="4323503">use</span> <span m="4323903">it</span> <span m="4324302">in</span>
  <span m="4324702">other</span> <span m="4325101">projects.</span> <span m="4325501">So</span>
  <span m="4325900">Crypto</span> <span m="4326300">Kernel</span> <span m="4326587">is</span>
  <span m="4326874">using</span> <span m="4327162">Schnorr</span> <span m="4327449">signatures,</span>
  <span m="4327736">probably</span> <span m="4328024">a</span> <span m="4328311">bunch</span>
  <span m="4328598">of</span> <span m="4328886">different</span> <span m="4329173">coins</span>
  <span m="4329460">who</span> <span m="4329748">are</span> <span m="4330035">sort</span>
  <span m="4330322">of</span> <span m="4330610">more</span> <span m="4330907">agile,</span>
  <span m="4331205">in</span> <span m="4331503">that</span> <span m="4331801">it's</span>
  <span m="4332099">easier</span> <span m="4332397">to</span> <span m="4332695">make</span>
  <span m="4332992">changes,</span> <span m="4333290">will</span> <span m="4333588">probably</span>
  <span m="4333886">start</span> <span m="4334184">using</span> <span m="4334482">this.</span></p><p><span
  m="4334780">Ethereum</span> <span m="4335385">is</span> <span m="4335991">still</span>
  <span m="4336597">ECDSA</span> <span m="4337202">though,</span> <span m="4337808">right?</span>
  <span m="4338414">There's</span> <span m="4339020">no</span> <span m="4339625">coins</span>
  <span m="4340231">that</span> <span m="4340837">are</span> <span m="4341442">actually</span>
  <span m="4342048">implementing</span> <span m="4342654">this</span> <span m="4343260">yet.</span>
  <span m="4343786">Monera</span> <span m="4344312">uses</span> <span m="4344838">ED25509,</span>
  <span m="4345364">which</span> <span m="4345890">is</span> <span m="4346416">essentially</span>
  <span m="4346942">a</span> <span m="4347468">Schnorr</span> <span m="4347994">signature.</span>
  <span m="4348520">And</span> <span m="4349046">I</span> <span m="4349572">think</span>
  <span m="4350098">Ripple</span> <span m="4350624">can</span> <span m="4351150">use</span>
  <span m="4351590">ED25509.</span> <span m="4352031">So</span> <span m="4352471">there's</span>
  <span m="4352912">some</span> <span m="4353352">different</span> <span m="4353793">schemes</span>
  <span m="4354233">that</span> <span m="4354674">are</span> <span m="4355115">more</span>
  <span m="4355555">similar</span> <span m="4355996">to</span> <span m="4356436">this,</span>
  <span m="4356877">but</span> <span m="4357317">still</span> <span m="4357758">don't</span>
  <span m="4358199">have</span> <span m="4358557">the</span> <span m="4358915">definitions</span>
  <span m="4359273">for</span> <span m="4359631">aggregation.</span></p><p><span m="4359989">So,</span>
  <span m="4360419">anyway,</span> <span m="4360849">so</span> <span m="4361279">this</span>
  <span m="4361709">is</span> <span m="4362139">cool</span> <span m="4362569">stuff.</span>
  <span m="4362999">Next</span> <span m="4363429">time,</span> <span m="4363859">I</span>
  <span m="4364289">will</span> <span m="4364719">talk</span> <span m="4365149">about--</span>
  <span m="4365579">next</span> <span m="4366009">one,</span> <span m="4366439">I'm</span>
  <span m="4366869">not</span> <span m="4367299">looking</span> <span m="4367730">forward</span>
  <span m="4367984">to</span> <span m="4368238">making</span> <span m="4368492">slides,</span>
  <span m="4368746">because</span> <span m="4369000">it's</span> <span m="4369254">like</span>
  <span m="4369508">a</span> <span m="4369762">really</span> <span m="4370016">complicated</span>
  <span m="4370270">one</span> <span m="4370524">that</span> <span m="4370778">I</span>
  <span m="4371032">don't</span> <span m="4371286">even</span> <span m="4371540">understand.</span>
  <span m="4371890">Like,</span> <span m="4372240">I</span> <span m="4372590">sort</span>
  <span m="4372940">of</span> <span m="4373290">get</span> <span m="4373640">it,</span>
  <span m="4373990">but</span> <span m="4374340">it's</span> <span m="4374690">like,</span>
  <span m="4375040">wait,</span> <span m="4375390">how?</span> <span m="4375740">OK,</span>
  <span m="4376090">but</span> <span m="4376440">how</span> <span m="4376790">to</span>
  <span m="4377140">mix</span> <span m="4377490">different</span> <span m="4377840">amounts.</span></p><p><span
  m="4382570">In</span> <span m="4382992">this</span> <span m="4383414">case,</span>
  <span m="4383836">hey,</span> <span m="4384258">it's</span> <span m="4384680">great.</span>
  <span m="4385102">But</span> <span m="4385524">in</span> <span m="4385946">many</span>
  <span m="4386368">cases,</span> <span m="4386791">you</span> <span m="4387213">can</span>
  <span m="4387635">see,</span> <span m="4388057">I</span> <span m="4388479">said</span>
  <span m="4388901">the</span> <span m="4389323">reason</span> <span m="4389745">it</span>
  <span m="4390167">doesn't</span> <span m="4390590">work</span> <span m="4391036">is</span>
  <span m="4391482">because</span> <span m="4391929">it's</span> <span m="4392375">really</span>
  <span m="4392822">obvious.</span> <span m="4393268">But</span> <span m="4393714">what</span>
  <span m="4394161">if</span> <span m="4394607">you</span> <span m="4395054">could</span>
  <span m="4395500">hide</span> <span m="4395946">the</span> <span m="4396393">amounts,</span>
  <span m="4396839">but</span> <span m="4397286">still</span> <span m="4397732">enforce</span>
  <span m="4398179">that</span> <span m="4398565">the</span> <span m="4398951">amounts</span>
  <span m="4399337">were</span> <span m="4399723">correct?</span></p><p><span m="4400110">So</span>
  <span m="4400426">that's</span> <span m="4400743">the</span> <span m="4401060">idea</span>
  <span m="4401376">of</span> <span m="4401693">confidential</span> <span m="4402010">transactions,</span>
  <span m="4402326">which</span> <span m="4402643">I'll</span> <span m="4402960">talk</span>
  <span m="4403276">about</span> <span m="4403593">next</span> <span m="4403910">time.</span>
  <span m="4404226">And</span> <span m="4404543">then</span> <span m="4404860">it</span>
  <span m="4405199">leads</span> <span m="4405538">to</span> <span m="4405877">MimbleWimble,</span>
  <span m="4406217">which</span> <span m="4406556">is</span> <span m="4406895">even</span>
  <span m="4407234">more</span> <span m="4407574">complicated.</span> <span m="4407913">I'm</span>
  <span m="4408252">not</span> <span m="4408591">going</span> <span m="4408931">to</span>
  <span m="4409270">promise</span> <span m="4409609">that</span> <span m="4409949">I'll</span>
  <span m="4410284">explain</span> <span m="4410620">the</span> <span m="4410955">whole</span>
  <span m="4411291">thing.</span> <span m="4411626">But</span> <span m="4411962">I'll</span>
  <span m="4412297">touch</span> <span m="4412633">on</span> <span m="4412968">the</span>
  <span m="4413304">ideas.</span></p>
type: course
uid: 478d7b4b26f859e2fa14f534f1e1ee77

---
None