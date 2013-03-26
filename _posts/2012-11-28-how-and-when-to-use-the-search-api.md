---
layout: post
title: "How (and When) to Use the Search API"
tags: how-to api
---
<p>We offer our search results as a hosted results page or as an <a href="http://cms.howto.gov/mobile/api-basics">application programming interface</a> (API). </p>
<h2>When to Use the Hosted Results</h2>
<p>Most agencies use our hosted search results page. We recommend that you to use our hosted page for the typical use case of returning search results on your website. Using the hosted page has many benefits such as allowing you to:</p>
<ul><li>Devote minimal development resources for the initial set up.</li>
<li>Benefit from new features automatically as they&#8217;re rolled out.</li>
<li>Stay current with search best practices, such as type-ahead search and formatting of search results.</li>
</ul><h2>When to Use the API</h2>
<p>You may need to access our search results to present them outside of a typical search results page. We offer our results as an API for these use cases.</p>
<p>You can access the API and its documentation at <a href="http://search.usa.gov/affiliates/home">Admin Center</a> &gt; YourSite &gt; Search API. </p>
<p>The API returns results from each of our indexes—web, image, document (ODIE), RSS (news), video, best bets (boosted content), and related searches—in JSON, JSON-P, or XML.</p>
<p>We recommend you use our API for limited use cases such as:</p>
<ul><li>Displaying search results within a native mobile application (i.e., an Android or iPhone app).</li>
<li>Integrating USASearch results within existing applications (such as your intranet or publications catalog).</li>
<li>Creating data mashups.</li>
</ul><p>Examples of how agencies are currently using the API follow.</p>
<p><strong>Use Case 1. Display Results in Your Mobile App</strong></p>
<p>USA.gov and the White House use the Search API to render USASearch results within their mobile apps. </p>
<p><img class="img-polaroid" src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_me79cgQKOE1qid15q.jpg"/><br/><em>Screenshot of a USASearch results page in the USA.gov iPhone app</em></p>
<p><img class="img-polaroid" src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_me78zp7y4v1qid15q.jpg"/> <br/><em>Screenshot of a USASearch results page in the White House iPhone app</em></p>
<p>Related Links</p>
<ul><li><a href="http://apps.usa.gov/usagov.shtml">USA.gov mobile app</a></li>
<li><a href="http://apps.usa.gov/the-white-house-app.shtml">WhiteHouse mobile app</a></li>
<li><a href="https://github.com/whitehouse">White House Github account</a> (information on and source code for the iOS and Android mobile apps)</li>
</ul><p><strong>Use Case 2. Integrate USASearch Results within existing applications</strong></p>
<p><a href="http://www.ri.gov">RI.gov</a> manages hundreds of distinct websites. The state provides a consistent search experience across all of its websites. Some sites are centrally controlled by RI.gov. Others are not. Using the Search API, RI.gov programmatically tells USASearch the site&#8217;s domain from which the user searched (e.g., tmc.dot.ri.gov). RI.gov then highlights results from this specific domain within RI.gov&#8217;s common look and feel.</p>
<p><span>See the sample results page below that shows a set of results displayed on</span><span> Rhode Island&#8217;s <a href="http://www.tmc.dot.ri.gov/">Transportation Management Center</a> </span><span>for a search on</span><span> </span><em>traffic.</em></p>
<div><img class="img-polaroid" src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_me7ej38m3P1qid15q.png"/> </div>
<div><em>Step 1. Searcher on <a href="http://www.tmc.dot.ri.gov">www.tmc.dot.ri.gov</a> types </em>traffic<em> in the search box</em></div>
<p><br/><img class="img-polaroid" src="http://f22818b4dfc10241d8a3-f1564c64756a8cfee25b6b19953b1d23.r31.cf2.rackcdn.com/tumblr_me7el3bJin1qid15q.png"/><br/><em>Step 2. Searcher sees results on RI.gov with a common look and feel that highlights results from the original site</em></p>
<blockquote>
<p><strong>Did you know?</strong> The Search API is available for government websites only. Other, publicly available APIs (i.e., for use by anyone) are at <a href="http://www.usa.gov/About/developer-resources/developers.shtml" title="http://www.usa.gov/About/developer-resources/developers.shtml" target="_blank"><a href="http://www.usa.gov/About/developer-resources/developers.shtml">http://www.usa.gov/About/developer-resources/developers.shtml</a></a>.</p>
</blockquote>
<p><a href="http://usasearch.howto.gov/">USASearch</a> &gt; <a href="http://search.usa.gov/affiliates/home">Admin Center</a> &gt; YourSite &gt; Search API</p>