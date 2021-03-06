---
layout: post
title: "GotToVote! Ghana Launches"
date: 2014-08-10 00:00:00
featured: /img/featured/gtv_ghana_1.png
blog: active
---

<blockquote>
	<p><em>Voting is a fundamental democratic right for every Ghanaian citizen but, without a voter ID, you cannot exercise that right. This project uses simple, cheap tools to make it easier for eligible citizens to register with the Electoral Commission.</em></p>
	<footer>Emmanuel Okyere, <cite title="Source Title">Odekro</cite></footer>
</blockquote>

<p class="lead"><a href="http://ghana.gottovote.cc" target="_blank">GotToVote! Ghana</a> is designed to help citizens find their nearest voter registration centre, so that they can ensure they are eligible to vote in the 2016 general election.</p>

<p>This website, which is optimised for easy mobile access, explains who is eligible to register and gives an overview of the voter registration process. It also tells users what documentation to take with them to register, and helps users easily find their nearest voter registration center.</p>

<p>This information is available elsewhere, but only as difficult-to-access PDF and MS Word or Excel documents that citizens are forced to download from a confusing variety of different ministry or other official websites.</p>

<p>GotToVote! Ghana takes the pain out of finding the information, by bringing it all together in one place and by presenting it in a standardised format that is easily searchable and readable.</p>

<p>Future versions of the site will introduce SMS tools, and will help users verify their registration, find their balloting stations, and track their local election results.</p>

<p>GotToVote! Ghana is not a government website. It was instead built by local social justice watchdog <a href="http://www.odekro.org/info/odekro-overview" target="_blank"> Odekro</a> and the continental open data incubator, <a href="http://www.codeforafrica.org">Code for Africa</a> , in partnership with the new Code for Ghana hub in Accra.</p>

<p>This project took just two days and $500 to execute. All the cleaned-up data and source materials used to power this website are available, free-of-charge, for you to reuse on your own projects.</p>

<p>This GotToVote! Ghana collaboration is the first in a new partnership to create simple digital tools that empower Ghanaian citizens.</p>

<p><a href="mailto:info@codeforafrica.org">Contact us</a> if you'd like our help to build other exciting citizen tools.</p>


<h4>For the Geeks: What GotToVote! Fixes</h4>

<p>Management of Ghana's voter registration data has been devolved to the districts, which means that there isn't a single standard or data schema.</p>

<p>"The lack of a standard schema was a challenge but, adding to this, not even the Electoral Commission's website has all the information. There are big holes in its data. This is a confusing nightmare for ordinary people, because they were expected to download a miss-mash of PDFs, MS Word or MS Excel documents, along with CSVs, to try find where they should register," explains Code for Africa's lead technologist, David Lemayian.</p>

<p>Lemayian and his counterparts at Odekro, Emmanuel Okyere and Nehemiah Attigah, therefore scraped source documents from all available sources and built a standard schema, reconciling often misspelled or missing data points and weeding out replications.</p>

<p>"A lot of the data, particularly for the Ashanti, Eastern, and Northern regions, were in .doc and .docx files. While most of this was in properly formatted tables, some Ashanti documents had really crazy tables that took forever to clean up and that made it difficult to write scrapers to extract the data into a Fusion Table," explains Okyere.</p>

<p>Many of the documents also included extraneous data, such as a list of "Unwieldy Electoral Areas", along with commentaries between Electoral Commission officials about the wisdom of creating additional registration centres because of the distances that voters would have to travel in rural areas to register. The recommendation doesn't appear to have been adopted.</p>

<p>Some of the data was also incomplete. The Ahenbronum electoral area in the Ashanti Region, for example, had no Designated Centre provided. And data for Brong Ahafo turned out to be same data for Volta region. Data for the Central region was not available at all. Regions like Volta were role models, with all their data cleanly formatted on separate spreadsheets within the same Excel workbook/file.</p>

<p>The <a href="http://www.ec.gov.gh/" target="_blank">Electoral Commission</a> was quick to help us when problems were identified, proving the potential for constructive and mutually beneficial partnerships between official agencies and civic technologists.</p>

<p>The Commission and its district agencies will be able to reuse the consolidated GotToVote! datasets.</p>

<p>What advice do we have for the Commission? Officials need to understand that data collection should NEVER be done in a word processing software like Word. Spreadsheets should be the minimum standard, with CSV being preferred but something like Excel is acceptable if nothing else is possible.</p>

<p>"Collaboration rocks! This entire project was done online, across time zones and 4,000km, with teams working in Ghana and Kenya. The Ghanians did all the data processing, at lightning speed, while the Kenyan team focused on setting up the site structure. It's amazing what we were able to achieve in just two days, at virtually no cost," says Lemayian.</p>


<h4>Where Does It Come From? GotToVote's History</h4>

<p>GotToVote! is an example of how open data can be useful to ordinary citizens.</p>

<p>GotToVote! was built at virtually zero cost as a <a href="http://code4kenya.org/" target="_blank">Code for Kenya</a> data journalism experiment ahead of the country's 2013 general elections. It was built in response to the fact that Kenyan citizens -- like Ghanian citizens -- were struggling to find out where to register. You can read <a href="http://ijnet.org/stories/data-journalism-boosts-voter-registration-kenya" target="_blank">a short blog post</a> about the experiment here.</p>

<p>But, why would journalists care? GotToVote! was designed to demonstrate that data-driven tools could help media audiences act on the news they read / watch, by showing how a national event such as the elections affects people's personal lives or local communities.</p>

<p>GotToVote! has since been replicated in Malawi (where electoral authorities adopted it as <a href="https://www.youtube.com/watch?v=hUdCVzxCt_o" target="_blank">the official government solution for voter verification</a>) and Zimbabwe. Ghana is therefore the fourth country to use GotToVote!</p>

<p>Code for Kenya itself was also a success. It started as a pilot programme funded by the <a href="http://africanmediainitiative.org/" target="_blank">Africa Media Initiative</a> (AMI) and its <a href="http://africannewschallenge.org/" target="_blank">African News Innovation Challenge</a> (ANIC). It embedded four Data Fellows into major Kenyan newsrooms and a civil society organisation, for five months, to help kickstart experimentation with data-driven civic engagement tools. The Data Fellows were supported by an external software development team.</p>

<p>Its success has sparked the launch of <a href="http://www.code4sa.org/" target="_blank">Code for South Africa</a>  in early 2014, and now the new Code for Ghana and Code for Nigeria initiatives.</p>

<h4>re/USE manifesto</h4>

<p>Code for Africa and its partners hate seeing civil society or anyone else being duped into wasting money unnecessarily on inappropriate technology or predatory consultancies.</p>

<p>There are thousands of civic apps and other technology solutions already available for reuse, free-of-charge, on communities such as GitHub.</p>

<p>	Code for Africa is committed to help grow these resources and the global civic technology community, by making its <a href="https://github.com/CodeForAfrica" target="_blank">code</a> and <a href="http://africaopendata.org/" target="_blank">data</a> freely available. It is also committed to helping fellow African citizen agency organisations re-purpose and customise existing civic code as cost-effectively as possible.</p>

<p>The code for GotToVote! Ghana is available <a href="http://github.com/CodeForAfrica/GotToVote.Ghana" target="_blank">here</a>.</p>

<p>All the data used by the Ghana project and other initiatives is available for free reuse on the <a href="http://openafrica.net/" target="_blank">openAFRICA.net</a> portal. It is already the continent's largest repository of public data, despite being volunteer run, and offers data ranging from government budget and tender information, to data about parliamentarians and other public officials.</p>
