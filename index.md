---
layout: default
title: kaitlin solimine
lnav: homepage
---

<div class="kato-info clearfix">
  <image src="/images/katohp.jpg" alt="logo" class="logo" />
  <p>Raised in New England, Kaitlin Solimine has considered China a second home for almost two decades. While majoring in East Asian Studies at Harvard University, she was a Harvard-Yenching scholar and wrote and edited <em>Let's Go: China</em> (St. Martin's Press). In 2006-2007, she was a U.S. Department of State Fulbright Creative Arts Fellow in China. She was the Donald E. Axinn Scholar in Fiction at the Bread Loaf Writers' Conference (2010) and graduated from the MFA program in writing at UC-San Diego (2011). An excerpt from her first novel, <em>Empire of Glass</em>, won the 2012 Dzanc Books/Disquiet International Literary Program award judged by Colson Whitehead. Her fiction and non-fiction has been published in National Geographic News, Guernica Magazine, Kartika Review, The Huffington Post, The World of Chinese Magazine, China Daily, and numerous anthologies. Kaitlin is co-founder of <a href="http://www.hipporeads.com/" target="_blank"> HIPPO Reads</a>, a literary-based media start-up that curates and delivers high quality, previously published long reads with an academic bent. She lives in Singapore and is represented by the <a href="http://www.wmclark.com/" target="_blank">William Clark Associates</a>.</p>
</div>

<br />

## News

<ul class="posts">
  {% for post in site.posts limit:3 %}
  	<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>

<!-- Begin MailChimp Signup Form -->
<div id="mc_embed_signup">
  <form action="http://kaitlinsolimine.us5.list-manage.com/subscribe/post?u=56ce8c2a0429ded30e91b1274&amp;id=901576d8c4" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank">
    <div class="mc-field-group">
      <label for="mce-EMAIL">Leave Your Email for Updates  <span class="asterisk">*</span></label>
      <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
    </div>
    <div id="mce-responses" class="clear">
      <div class="response" id="mce-error-response" style="display:none"></div>
      <div class="response" id="mce-success-response" style="display:none"></div>
    </div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
  </form>
</div>

<!--End mc_embed_signup-->
