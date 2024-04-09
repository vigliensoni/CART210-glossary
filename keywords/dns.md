## DNS
The Domain Name System is a system that matches the name in the URL to the IP address of the sites we are looking for on the Internet. This makes it easier for us to navigate to our favorite websites rather than remembering their IP addresses.[^couldflare24what] The DNS provides the corresponding IP address to the domain name for browsers to find the page we are searching for.
In short, the DNS allows a more user-friendly interface for users to navigate the Internet through human-readable host names.[^acm01dns]

![DNS](images/dns-chan.jpg)

### Domain Namespace
#### Search Structure
The DNS is a database that contains information on namespaces and provides the browser with the appropriate information from internet hosts to allow the navigator to reach the right places. It uses the domain namespace, a collection of all the domain names existing on the internet, to perform the search. This system is built on an inverted tree diagram where the initial point splits into several segments that also divide into more subsegments. As the search reaches lower into the tree, the more specific the namespace becomes. The nodes at the root of the tree are referred to as top-level domain names (TLD).[^google06dnsbind]

<img src="https://www.oreilly.com/api/v2/epubs/0596005628/files/httpatomoreillycomsourceoreillyimages137590.png" width="600px" height="auto" alt="Diagram of the struture of the doamin namespace">


#### Seven Top-Level Domain Names (TLD) That Divide The Internet
To host a website on the Internet, we are required to buy a root domain which includes the domain name and the TLD. The combination creates a website address such as _google.com_. Originally, seven top-level domain names reflected the nature of the organization behind the website.
- **.com** : Commercial use.
- **.edu** : Educational organizations.
- **.gov** : Government websites.
- **.mil** : Military websites.
- **.net** : For NSFNET and UUNET, and commercial use after 1996.
- **.org** : Noncommercial organizations (before 1996).
- **.int** : International organizations.

Today, other domains were added with the expansion of the Internet, allowing for a larger pool of available namespaces.[^google06dnsbind] Big companies like Apple, Google, Audible, Amazon, Best Buy, and more own TLDs that are reserved strictly for their use and inaccessible to the public. [E-commerce](../main/glossary.md#E-commerce) businesses rely on the DNS to ensure their clients can easily navigate to their websites.

### DNS and New Media
The obvious relation between the DNS and new media is through everything that needs to connect to the Internet.
Therefore, all new media platforms in the form of websites, applications and other online formats require IP addresses and a corresponding domain name. Without the DNS, it would be much harder to navigate the Web and access new media content.

#### Top-Level Domains and New Media Art
The DNS allows artists to choose namespaces that correspond to their work and specializations. This creates room for artists to express themselves by using the DNS and namespaces as a way to establish a unique name reflecting their brand.

Several examples of top-level domains available for artists, designers and creators to buy include:
[^wiki24list]
- **.actor**
- **.art**
- **.design**
- **.digital**
- **.graphics**
- **.media**
- **.studio**
- **.tech**
- etc.


[^couldflare24what]: CloudFlare. 2024. "What is DNS? | How DNS works." Accessed January 25, 2024. https://www.cloudflare.com/learning/dns/what-is-dns/.
[^acm01dns]: Jung, Jaeyeon, Sit, Emil, Balakrishnan, Hari and Morris, Robert. 2001. "DNS Performance and the Effectiveness of Caching: Proceedings of the 1st ACM SIGCOMM Workshop on Internet Measurement." ACM Conferences. Accessed February 26, 2024. https://dl.acm.org/doi/epdf/10.1145/505202.505223.
[^google06dnsbind]: Liu, Cricket, and Albitz, Paul. 2006. "How Does DNS Work?" DNS and Bind, 11-34. Google Books. Accessed February 26, 2024. https://books.google.ca/books?hl=en&lr=&id=u0GbAgAAQBAJ&oi=fnd&pg=PT4&dq=DNS&ots=6-v2uEt-Oy&sig=wV_8GvQVJJORsEiKSgDny91vV3A#v=onepage&q&f=false. 
[^wiki24list]: 2024. "List of Internet Top-Level Domains." Wikipedia. Accessed February 26, 2024. https://en.wikipedia.org/wiki/List_of_Internet_top-level_domains. 