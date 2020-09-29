---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
[What is this?](#what-is-this) | [Who are you?](#who-are-you) | [How can I do this in my own community?](#my-own-community) | [Available Voter Guides](#voter-guides)

<a name="what-is-this"></a>
<h3>What is this?</h3>
<p>Local elections don't get the attention that they deserve. Despite presidential, and sometimes congressional and gubernatorial, races garnering a lot of public and media attention, local elections tend to get glossed over because they aren't sensational. Despite this, it's local elections that will have a daily impact on your own life and it's the effects of local elections that can lead to big change. Instead of picking random names or names that you recognize on a ballot, hopefully this site will help you come to an educated conclusion about which bubbles to fill in on your ballots based on who you actually think would be best in each office.</p>
<p>I personally reached out to every candidate on the local election ballot to ask for their top 3 responses to variants of two simple questions:</p>
<ol>
    <li>Why are you running and what do you stand for?</li>
    <li>Why are you qualified?</li>
</ol>
<p>Unless marked with an asterisk<sup>*</sup>, these are the candidates' own words in response to my questions. This way, you'll have the best and most prioritized information about each candidate on your ballot, and can vote accordingly.</p>

***

<a name="who-are-you"></a>
<h3>Who are you?</h3>
![Suriya!](/assets/suriya_headshot.jpg){: style="float: left; padding-right: 20px;"}
My name is Suriya Kandaswamy and, after graduating from Harvard with a major in computer science and minor in government this May, I immediately moved back home in order to work remotely and return to the community that I've been in for my entire childhood. The very first time I could vote was in my freshman year of college in 2016. At that time, I was guilty of picking random names for local election races, but now that I'm back home for the 2020 election, I'd like to give back to the Montgomery County community and public school system that raised me and give everyone around me the opportunity to truly make the choices that they believe are best for themselves and their community.
<br clear="left" />

***

<a name="my-own-community"></a>
<h3>How can I do this in my own community?</h3>
I'm glad you asked! Right now, there's only a voter guide for the Montgomery County, MD local races because that's my own district! If you want to contact the candidates for local seats in your own district to get their responses to the two simple questions and have your district featured with these responses on its own page on this site, <strong>contact me at <a href="mailto:{{ site.email }}">{{ site.email }}</a></strong>. In your email, tell me about yourself and your district, and I'll walk you through how to do this for your community. It's local voices and actions that matter the most!

***

<a name="voter-guides"></a>
<h3>Available Voter Guides</h3>
One-stop-shop local election voter guides are available for the following regions:
<ul>
    {%- for data_page in site.candidate_data -%}
        <li><a href="{{ data_page.url | relative_url }}">{{ data_page.title }}</a></li>
    {%- endfor -%}
</ul>