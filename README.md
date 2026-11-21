# Case-3-Test-Site

<h2>Interviewer script</h2>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="robots" content="noindex,nofollow">
<meta name="color-scheme" content="light dark">
<title>Interviewer cue cards</title>
<style>
:root{color-scheme:light dark;--bg:#fff;--fg:#1f2328;--muted:#59636e;--line:#d0d7de;--card:#f6f8fa;--say-bg:#eaf2fb;--say-line:#2b6cb0;--accent:#0969da;--warn:#fff4d6;--warn-line:#c99a00}
@media (prefers-color-scheme:dark){:root{--bg:#0d1117;--fg:#e6edf3;--muted:#9198a1;--line:#30363d;--card:#161b22;--say-bg:#12233a;--say-line:#58a6ff;--accent:#58a6ff;--warn:#2d2508;--warn-line:#d4a72c}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--fg);font:16px/1.5 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;padding:0 max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px))}
main{max-width:860px;margin:0 auto;padding:24px 0 64px}
h1{font-size:1.7rem;margin:0 0 4px}
h2{font-size:1.2rem;margin:0;display:flex;gap:.6rem;align-items:baseline;flex-wrap:wrap}
h2 small{font-size:.8rem;font-weight:500;color:var(--muted)}
h3{font-size:1rem;margin:1.2rem 0 .4rem}
.sub{color:var(--muted);margin:0 0 16px}
.card{border:1px solid var(--line);border-radius:10px;padding:14px 16px;margin:14px 0;background:var(--card)}
.legend{display:grid;gap:6px;margin:12px 0 4px}
.say{background:var(--say-bg);border-left:4px solid var(--say-line);padding:8px 12px;margin:8px 0;border-radius:0 6px 6px 0;font-weight:700;font-style:italic}
.sugg{font-style:italic}
.act{margin:.4rem 0}
.warn{background:var(--warn);border-left:4px solid var(--warn-line);padding:8px 12px;margin:8px 0;border-radius:0 6px 6px 0}
table{border-collapse:collapse;width:100%;margin:8px 0;background:var(--bg)}
th,td{border:1px solid var(--line);padding:6px 10px;text-align:left;vertical-align:top;color:var(--fg)}
td{background:var(--bg)}
tr:nth-child(odd) td,tr:nth-child(even) td{background:var(--bg);color:var(--fg)}
th{background:var(--card);font-size:.85rem;text-transform:uppercase;letter-spacing:.03em}
td *,th *{color:inherit}
.tw{overflow-x:auto}
ul{margin:.3rem 0;padding-left:1.2rem}
a{color:var(--accent)}
.nums td:first-child{width:2.2rem;color:var(--muted)}
</style>
</head>
<body>
<main>
<h1>Interviewer cue cards</h1>

<div class="card">
<h2>Links</h2>
<ul>
<li><a href="https://docs.google.com/forms/d/e/1FAIpQLSeok2nbN-E6R2zKpRNv0_kGEClY4ZbMz7Vtx2fFvwpjUFEtdQ/viewform?usp=dialog">GDPR form</a> (before the session)</li>
<li><a href="https://forms.gle/wfFPgBoJKJLGPKWj8">UES-SF</a> (link 1)</li>
<li><a href="https://forms.gle/AoGbdH4jq9maggZE7">EMCB</a> (link 2)</li>
</ul>
</div>

<div class="card">
<h2>Timeline</h2>
<div class="tw"><table>
<tr><th>#</th><th>Step</th><th>Where</th><th>Min</th></tr>
<tr><td>1</td><td>Welcome</td><td>Spoken</td><td>2</td></tr>
<tr><td>2</td><td>GDPR check and recording</td><td>Teams</td><td>3</td></tr>
<tr><td>3</td><td>Think-aloud</td><td>Spoken</td><td>2</td></tr>
<tr><td>4</td><td>ID, screen sharing, shop link</td><td>Prototype</td><td>2</td></tr>
<tr><td>5</td><td>Scenario and task</td><td>Spoken</td><td>2</td></tr>
<tr><td>6</td><td>Shopping task</td><td>Prototype (Clarity)</td><td>9</td></tr>
<tr><td>7</td><td>UES-SF</td><td>Google Form</td><td>2</td></tr>
<tr><td>8</td><td>Interview</td><td>Spoken</td><td>6–8</td></tr>
<tr><td>9</td><td>Observer questions</td><td>Spoken</td><td>2</td></tr>
<tr><td>10</td><td>EMCB</td><td>Google Form</td><td>2</td></tr>
<tr><td>11</td><td>Debrief and renewed consent</td><td>Spoken</td><td>4</td></tr>
</table></div>
</div>

<div class="card">
<h2>1. Welcome <small>2 min</small></h2>
<div class="say">"Hi, and thank you for your time. I'm [name], and this is [name], who will be taking notes. We're Information Science students at Aalborg University Copenhagen, and this is part of our student project."</div>
<div class="say">"Today we're testing the search function of an online shop prototype that we built ourselves. It isn't connected to any real shop, and no real purchases are made. The session takes about 30 to 40 minutes. You'll do a short shopping task, where you pick three products, fill in two short questionnaires and answer a few questions about your experience. There are no right or wrong answers. We're testing the shop, not you. Taking part is voluntary, and you can stop at any time without giving a reason."</div>
<div class="say">"Before we start, I'll explain one thing about how we'd like you to work."</div>
</div>

<div class="card">
<h2>2. GDPR and recording <small>3 min</small></h2>
<p class="act">1. Ask:</p>
<div class="say">"Did you receive and read the GDPR information and consent we sent you, and do you have any questions?"</div>
<p class="act">If not: share the GDPR link in the chat and let them fill it in now. No written consent, no test.</p>
<p class="act">2. Start the Teams recording and say: <b><i>"I'm starting the recording now. Only your screen and your voice are recorded, not your face. Please keep your camera off."</i></b></p>
<p class="act">3. Confirm on the recording:</p>
<div class="say">"Do you agree that your screen and your voice are recorded in this meeting during the whole session, and that your clicks and mouse movements in the shop prototype are recorded with a tool called Microsoft Clarity? Please say yes out loud."</div>
<div class="warn">No, or unsure: stop and delete the recording. No consent, no test.</div>
</div>

<div class="card">
<h2>3. Think-aloud <small>2 min</small></h2>
<div class="say">"While you shop, we'd like you to think out loud. That means saying whatever goes through your mind as you go: what you're looking for, what you notice, why you click something, and what you find confusing or easy. Just talk as if you were alone, and don't worry about explaining yourself or sounding smart. If you go quiet, I may remind you to keep talking. I won't answer questions or help while you shop, but that's only so everyone gets the same experience."</div>
<p class="sugg">Optional 30-second warm-up: "Try it now: describe what you see on this screen."</p>
</div>

<div class="card">
<h2>4. ID, screen sharing, shop link <small>2 min</small></h2>
<div class="say">"Do you remember your participant ID from the email?"</div>
<p class="act">If not, give it and note it. Age group and gender are already in the GDPR form.</p>
<div class="say">"You'll need your participant ID again to start in the shop and for the questionnaires, so please keep the email open."</div>
<div class="say">"Please share your entire screen now: click Share in the Teams toolbar and choose your screen. Before you do, please close anything private, like other tabs, messages or notifications."</div>
<p class="act">Entire screen, not one window.</p>
<div class="say">"Now please open the link called "Shop prototype" in your email. On the first page, type in your participant ID to start. Tell me when you can see the shop."</div>
<p class="act">Check that the ID typed is the right one.</p>
</div>

<div class="card">
<h2>5. Scenario and task <small>2 min</small></h2>
<p class="act">Relaxed tone. Say it once. Don't mention sustainability. Also post the task in the chat.</p>
<div class="say">"Imagine that tomorrow you want to take lunch and something to drink with you. You open the cupboard and realise you don't have a water bottle, a lunch box or anything to carry food in. The shops are closed, and you have no time to go out tomorrow, so you decide to order everything tonight in the online shop. You need all three for tomorrow, but you still want to end up with things you're happy with."</div>
<div class="say">"You need three things: a water bottle, a lunch box and a food container. I'll say it once now and also post it in the chat. Use the search bar to find each product and choose whatever you'd really pick if you were buying it for yourself. Put all three in your cart, and when you have them all, buy the cart once. When you see the order confirmation, say "done". I can't repeat the instructions during the task, so please ask now if anything is unclear. Any questions before we start?"</div>
</div>

<div class="card">
<h2>6. Shopping task <small>about 9 min</small></h2>
<ul>
<li>Stay silent. Don't help, don't answer questions about the task.</li>
<li>Quiet for a while: <b><i>"Please keep talking."</i></b></li>
<li>Note: what is typed, which suggestion is clicked and its position, which products are chosen, order of the searches, total time.</li>
<li>Note anything to ask about in step 9.</li>
<li>The task ends on the order confirmation page, when they say "done".</li>
</ul>
<div class="say">"Thank you, that was the shopping part. You can close the shop now. Next we have a short questionnaire."</div>
</div>

<div class="card">
<h2>7. UES-SF <small>2 min</small></h2>
<div class="say">"Please go back to the email and open link 1. The first question asks for your participant ID. Fill it in now, and tell me when you're done."</div>
<p class="act">Can't find the email: share link 1 in the chat. Stay quiet.</p>
</div>

<div class="card">
<h2>8. Interview <small>6 to 8 min</small></h2>
<div class="warn">Don't say sustainable, eco, green, plastic-free or stainless steel before the participant does. If they say such a word, pick it up and ask what it meant to them. Use their own words and your notes ("I noticed you clicked… what was going through your mind?").</div>

<h3>How they decided (about 2 min)</h3>
<div class="tw"><table>
<tr><th>Question</th><th>Prompt if short or vague</th></tr>
<tr><td>"How did you find searching in this shop?"</td><td><span class="sugg">Can you say more about that? / What made it feel [easy / fine / confusing]?</span></td></tr>
<tr><td>"Can you take me through the three products you chose, and why you chose each one?"</td><td><span class="sugg">What mattered most to you when you chose? / Can you give me an example from when you were shopping?</span></td></tr>
<tr><td>"Was there anything that stood out to you?"</td><td><span class="sugg">What were you thinking at that moment?</span></td></tr>
</table></div>

<h3>The wording of suggestions and products (2 to 3 min)</h3>
<p class="act">In order. Stop at the first answer that gives a lot to follow up on.</p>
<div class="tw"><table>
<tr><th>Question</th><th>Prompt</th></tr>
<tr><td>"What did you notice about the suggestions that came up when you typed?"</td><td><span class="sugg">Tell me more about that.</span></td></tr>
<tr><td>"Were there any words or labels in the suggestions or the product names that caught your eye? Which ones?"</td><td><span class="sugg">What did that word mean to you?</span></td></tr>
<tr><td>"Did any of those words affect what you clicked or bought? How?"</td><td><span class="sugg">Did it change which product you picked? Did it matter more or less than price, brand or look?</span></td></tr>
<tr><td>"What did that word mean to you?" (any word they mentioned)</td><td><span class="sugg">Do you think such words are always true, or is it more of a sales message?</span></td></tr>
<tr><td>"Did any wording make you trust a product more, or less?"</td><td><span class="sugg">Tell me more about that.</span></td></tr>
<tr><td>"If the suggestions had used different words, do you think you would have chosen differently?"</td><td><span class="sugg">Why / why not?</span></td></tr>
</table></div>

<h3>Topics for their version (2 to 3 min)</h3>
<p class="act">Pick the block for their version. Use two or three topics in your own words and follow what they say. Labels as in the README: A control, B mixed in, C ranked at the top, D mixed in with green highlight <b>[check with the group: the long script labels B and C the other way round]</b>.</p>
<div class="tw"><table>
<tr><th>Version</th><th>Topics</th></tr>
<tr><td><b>A</b> Normal suggestions (control)</td><td><span class="sugg">What they compared first: price, brand, size, material, look. Whether this is how they normally choose. How much they relied on the suggestions.</span></td></tr>
<tr><td><b>B</b> Sustainable suggestions mixed into the list</td><td><span class="sugg">How they scanned the list. What stood out among the suggestions, and why. Any moment they changed their mind.</span></td></tr>
<tr><td><b>C</b> Sustainable suggestions at the top</td><td><span class="sugg">Why they clicked the suggestion they did. What being at the top meant to them (popular, recommended, an advert?). Whether they looked further down.</span></td></tr>
<tr><td><b>D</b> Sustainable suggestions highlighted in green</td><td><span class="sugg">Whether anything about how the suggestions looked caught their eye (only then ask about colours or highlighting). What the colour meant to them. Whether it made them click more or less, and whether they trusted it.</span></td></tr>
</table></div>

<h3>Close</h3>
<div class="say">"Is there anything else that influenced your choices?"</div>
<p class="act">Short on time: "how they decided" question 2, "wording" questions 2 and 3, and two version topics.</p>
</div>

<div class="card">
<h2>9. Observer questions <small>2 min</small></h2>
<div class="say">"[Name], is there anything you'd like to ask?"</div>
<p class="act">Observer asks about what they noticed (a hesitation, a repeated search, an unexpected choice). Neutral and open, no hint of the purpose.</p>
</div>

<div class="card">
<h2>10. EMCB <small>2 min</small></h2>
<div class="say">"Thank you. One more short questionnaire. Please go back to the email and open link 2. Again, the first question asks for your participant ID. Tell me when you're done."</div>
</div>

<div class="card">
<h2>11. Debrief and renewed consent <small>4 min</small></h2>
<div class="say">"Thank you very much. We would now like to tell you more about the study. We did not tell you everything at the start, because it could have influenced how you shopped. The study is about sustainable shopping. Some participants saw search suggestions for sustainable products, such as stainless steel or plastic-free products, mixed into the list, placed at the top, or highlighted in green. Others saw the normal suggestions. We want to find out whether the way suggestions are shown influences what people click on and choose. Your choices were not right or wrong, and they will only be analysed together with those of other participants."</div>
<div class="tw"><table class="nums">
<tr><th>#</th><th>Ask</th></tr>
<tr><td>1</td><td>"Did you notice anything about the search suggestions while you were shopping?"</td></tr>
<tr><td>2</td><td>"How do you feel about search suggestions being used to steer your choices in this way? Do you find it helpful, neutral or disturbing?"</td></tr>
<tr><td>3</td><td>"Would you accept this kind of suggestion in a real online shop? Why or why not?"</td></tr>
<tr><td>4</td><td>"Do you have any questions about the study?"</td></tr>
</table></div>
<p class="act">Renewed consent, a spoken yes on the recording:</p>
<div class="say">"Now that you know the purpose, do you still agree that your data, including this recording and your clicks in the shop, may be used as described in the information we sent you? Please say yes or no out loud."</div>
<div class="warn">Withdraws: delete the Teams recording, their Clarity session, their questionnaire answers and all other data the same day.</div>
<div class="say">"That's the end of the session. I'm stopping the recording now. Thank you very much."</div>
</div>
</main>
</body>
</html>
<h2>Final Test pages connected to Clarity</h2>
To open a shop without a code, add ?admin to the address, for example shop-3.html?admin. This also opens the hidden researcher panel. For a normal pilot run, use TEST1 to TEST4 on the start page instead.
<ul>
  <li><a href="shop-1.html">Shop 1. A (Control)</a></li>
  <li><a href="shop-2.html">Shop 2. B (Mixed)</a></li>
  <li><a href="shop-3.html">Shop 3. C (Sustainable top)</a></li>
  <li><a href="shop-4.html">Shop 4. D (Static highlight & hover highlight)</a></li>
</ul>


<h2>Old Test Pages</h2>
<ul>
  <li><a href="groceries-togo-site-A-control.html">Version A (Control)</a></li>
  <li><a href="groceries-togo-site-B-mixed.html">Version B (Mixed)</a></li>
  <li><a href="groceries-togo-site-C-sustainable-top">Version C (Sustainable top)</a></li>
  <li><a href="groceries-togo-site-Db-static-highlight.html">Version D b. (Static highlight & hover highlight)</a></li>
</ul>

<br><br>

<ul>
  <li><a href="groceries-togo-site-D-mixed-highlight-options.html">Version D (all highlight options we pre-tested)</a></li>
   <li><a href="groceries-togo-site-Da-hover-highlight"><del>Version D a. (Only Hover highlight)</del></a></li>
</ul>
