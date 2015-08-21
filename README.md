# Apache-Nutch-Crawler
Analysis of Crawling Google_Play_Store using Apache Nutch Web Crawler</br>

<b>Introduction</b></br>
A web crawler is an automated program that scans through internet webpages to collect information from the internet.We have used Apache Nutch Crawler
to crawl <i>Google play store</i>.From the information available in <i>robots.txt</i> file for google play store,it allows us to crawl books,music only.
The url seed list contains google play store url.Nutch crawler injets this url and generates the list of urls that has to be generated.Crawl fetches the urls and updates the <i>Crawldb</i>.
We have colleted 790.07 MB of data which has 133754 documents over 22 hours with level of depth as 9.The local system configuration is
<ul>
<li>12 GB RAM</li>
<li>750 GB HDD </li>
<li>intel i7 processor</li>
</ul>
From the webgraphdb, we have extracted the list of urls with top scores.We have also analysed the inlinks and outlinks from every url.We have also parsed the text content in every web page collected and list of all word count has been documented.
The crawldb urls have also been indexed using <i>SOLR </i>.

<img src="https://cloud.githubusercontent.com/assets/9910374/9415075/c288b6c4-480a-11e5-9bbc-b3bb8b69be4b.png"/>