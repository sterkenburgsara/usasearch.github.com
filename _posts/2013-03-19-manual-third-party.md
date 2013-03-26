---
permalink: /manual/third-party.html
layout: post
title: "How to Add JavaScript for Your Third Party Web Services"
tags: third-party how-to
---
<p>Do you want your search results page to run web services such as 4Q, AddThis, Foresee, Google Analytics, Omniture, or WebTrends?</p>
<p>Log in to the <a href="http://search.usa.gov/affiliates/home">Admin Center</a> and select the option, Third Party Tracking. Input the JavaScript code you&#8217;d like to call from your search results page. Click submit to send us your request. We&#8217;ll input your code for you and send you an email to confirm that we&#8217;ve done it.</p>
<blockquote>
<p><em><strong>Google Analytics tip:</strong></em> In your Google Analytics JavaScript, be sure to set your domain if you&#8217;ve requested <a href="/blog/how-to-add-our-code-to-your-website#cname.html">domain masking</a> and you want to include your search subdomain (e.g., search.commerce.gov) with your main domain (e.g., commerce.gov).</p>
<p>_gaq.push([&#8216;_setDomainName&#8217;, &#8216;commerce.gov&#8217;]);<br/><br/>For more information, read Google&#8217;s tip, <a href="https://developers.google.com/analytics/devguides/collection/gajs/gaTrackingSite">Tracking Multiple Domains</a>.</p>
<p><em><strong>ForeSee tip:</strong> </em>Coordinate with your ForeSee representative and USASearch to implement your customer satisfaction survey on your results page. The four general steps follow.</p>
<ol><li>Email USASearch to <a href="/blog/how-to-add-our-code-to-your-website#cname.html">set up a CNAME</a> for search.{yourdomain}.gov.</li>
<li>Update the files path in your Foresee code to use an absolute path instead of a relative path. <br/><br/>Find =&gt; &#8216;files&#8217;: &#8216;/fsrscripts/&#8217;,<br/><br/>and replace it with =&gt; &#8216;files&#8217;: &#8216;//{yourdomain}/fsrscripts/&#8217;,<br/><br/>in the following five files.<br/>a. foresee-trigger.js<br/>b. foresee-tracker.js<br/>c. foresee-alive.js<br/>d. foresee-qualifier.js<br/>e. foresee-test.js</li>
<li>Ask ForeSee to send USASearch your foresee-trigger.js file.</li>
<li>USASearch will send you an email to confirm that we&#8217;ve set up your CNAME and installed your foresee-trigger.js file.</li>
</ol></blockquote>
<p><a href="http://usasearch.howto.gov/">USASearch</a> &gt; <a href="http://search.usa.gov/affiliates/home">Admin Center</a> &gt; YourSite &gt; 3rd Party Tracking</p>