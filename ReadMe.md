# Solarwinds Vulnerablity Info
Repository with all the Solarwinds Vulnerability information I've been tracking and using for communications, review, and technical understanding.

It's devided into four sections: <a href="#news">News Reports</a>, <a href="#public">Public Information / Alerts</a>, <a href="#analysis">Technical Analysis</a>, <a href="#iocs">Additional IOCs</a>, and <a href="#fud">Unsubstantiated Conspiracy, FUD, or Selective Manipulation of Information</a>. There is some overlap where a few links may be a long for technical analysis, but may also include IOCs. Others may be advisories that also qualify as news. This is all public information and is provided freely for use. 

Previously I was tracking all of this in a Twitter thread located here: https://twitter.com/EanMeyer/status/1338324466808590345?s=20

I will post this GitHub repo to that Twitter thread and ongoing updates will be here.
Each section is now sorted by date - The date is not necessarily when the news became available, it's when it was added so you can quickly see any updates from the days you missed. Where articles were published on an earlier date and updated I will try to move them to the new date. 

Hashtags for use in TweetDeck and Twitter. Paired with with AND/OR to tune results for more or less FUD copy and past everyting after the dash into search.<br>
<b>Less FUD</b> - #UNC2452 OR #Solorigate OR #Sunburst <br>
<b>With FUD</b> - #SolarWinds OR #solarwinds123 OR #SolarWindsOrion OR #UNC2452 OR #Solorigate OR #Sunburst <br>
<b>All FUD</b> - #solarwinds AND #RiggedElection OR #DominionVotingSystems OR #KrakenReleased <br>

<a id="news"><h2>News Reports</h2></a>

12/17/2020

<b>Details on Death Star Sinkhole deployed by Microsoft to stop C2 traffic</b>
https://www.geekwire.com/2020/microsoft-unleashes-death-star-solarwinds-hackers-extraordinary-response-breach/

12/16/2020

<b>SolarWinds Advisory - First Posted 12/13 Updated 12/16 - 9:30am CT</b>
https://www.solarwinds.com/securityadvisory

<b>TheHackerNews reports on Reversing Labs analysis showing the flaw was likely introduced by a compromised build pipeline</b>
https://thehackernews.com/2020/12/new-evidence-suggests-solarwinds.html

<b>Washington Post reports $280 million in Solarwinds stock was traded days before breach announcement</b>
https://twitter.com/washingtonpost/status/1339059943442419714?s=20

<b>KrebsOnSecurity reports domain takeover of malicious C2 now, in some cases, includes a kill switch</b>
https://krebsonsecurity.com/2020/12/malicious-domain-in-solarwinds-hack-turned-into-killswitch/

12/15/2020

<b>KrebsOnSecurity - Solarwinds Breach Effects 18k Customers, Microsoft takes control of domains</b> 
https://krebsonsecurity.com/2020/12/solarwinds-hack-could-affect-18k-customers/

<b>Reuters Story confirming Solarwinds FTP CDN password was "solarwinds123"</b>
https://www.reuters.com/article/global-cyber-solarwinds/hackers-at-center-of-sprawling-spy-campaign-turned-solarwinds-dominance-against-it-idUSKBN28P2N8

<b>Microsofts role in recent high profile breaches called into question as O365 MFA bypass looked at as intial compromise channel</b> 
https://www.crn.com/news/security/microsoft-s-role-in-solarwinds-breach-comes-under-scrutiny?itc=refresh

12/14/2020

<b>Washington Post ties Solarwinds breach to all recent major breaches</b> 
https://www.washingtonpost.com/national-security/russian-government-spies-are-behind-a-broad-hacking-campaign-that-has-breached-us-agencies-and-a-top-cyber-firm/2020/12/13/d5a53b88-3d7d-11eb-9453-fc36ba051781_story.html

<b>ZDNet reporting on Solarwinds 8K filing </b>
https://www.zdnet.com/article/sec-filings-solarwinds-says-18000-customers-are-impacted-by-recent-hack/

12/13/2020

<b>KrebsOnSecurity - US Treasury Breach and Solarwinds</b>
https://krebsonsecurity.com/2020/12/u-s-treasury-commerce-depts-hacked-through-solarwinds-compromise/



<a id="public"><h2>Public Information / Alerts</h2></a>

12/17/2020

<b>CISA Alert 12/17 - Technical Breakdown of Threat Actor - Includes Report which will be under technical analysis</b>
https://us-cert.cisa.gov/ncas/alerts/aa20-352a

12/16/2020

<b>SolarWinds Advisory - First Posted 12/13 Updated 12/16 - 9:30am CT</b>
https://www.solarwinds.com/securityadvisory

<b>@chrismerkel - Chart of Solarwinds Version Timeline and Mallicious Versions</b>
https://twitter.com/chrismerkel/status/1339296920666304519?s=20

<b>Joint Statement from the FBI, ODNI, and CISA</b>
https://www.cisa.gov/news/2020/12/16/joint-statement-federal-bureau-investigation-fbi-cybersecurity-and-infrastructure

12/15/2020

<b>Microsoft now in Control of C2 domains </b>
https://twitter.com/briankrebs/status/1338840527169613824?s=20

<b>Reuters Story confirming Solarwinds FTP CDN password was "solarwinds123"</b>
https://www.reuters.com/article/global-cyber-solarwinds/hackers-at-center-of-sprawling-spy-campaign-turned-solarwinds-dominance-against-it-idUSKBN28P2N8

<b>Solarwinds Best Practice had users disable the folders where the malware resided for all AV and Security products</b>
https://support.solarwinds.com/SuccessCenter/s/login/?language=en_US&startURL=%2FSuccessCenter%2Fs%2Farticle%2FFiles-and-directories-to-exclude-from-antivirus-scanning-for-Orion-Platform-products%3Flanguage%3Den_US&ec=302

<b>Screenshot of Solarwinds Best Practice if you do not have support portal access </b>
https://twitter.com/ffforward/status/1338785034375999491/photo/1

12/14/2020

<b>Solarwinds SEC 8K Filings</b>
https://www.sec.gov/ix?doc=/Archives/edgar/data/1739942/000162828020017451/swi-20201214.htm

<b>Vinoth Kumar shares information about their responsible disclosure of Solarwinds FTP account password to their CDN password "solarwinds123"</b>
https://twitter.com/vinodsparrow/status/1338431183588188160?s=20

<b>Kyle Hanslovan discovers SolarWinds is still listing the vulnerable package 24 hours after disclosure (Update: Package was removed) </b>
https://twitter.com/KyleHanslovan/status/1338360093767823362?s=20

<b>CISA Directive to shutdown and remove Solarwinds from all Federal Civilian Agencies </b>
https://www.cisa.gov/news/2020/12/13/cisa-issues-emergency-directive-mitigate-compromise-solarwinds-orion-network

12/13/2020

<b>CISA Alert</b>
https://us-cert.cisa.gov/ncas/current-activity/2020/12/13/active-exploitation-solarwinds-software

<b>CISA Emergency Directive 21-01 - This is the actual directive ordering the shutdown of Solarwinds on Federal systems</b>
https://cyber.dhs.gov/ed/21-01/



<a id="analysis"><h2>Technical Analysis</h2></a>

12/17/2020

<b>CISA Technical Analysis of Threat Actor Group</b>
https://us-cert.cisa.gov/sites/default/files/publications/AA20-352A-APT_Compromise_of_Government_Agencies%2C_Critical%20Infrastructure%2C_and_Private_Sector_Organizations.pdf

<b>Malware Bytes Analysis of Sunburst</b>
https://blog.malwarebytes.com/threat-analysis/2020/12/advanced-cyber-attack-hits-private-and-public-sector-via-supply-chain-software-update/

<b>@Mubix's Technical Analysis including Solarflare tool for extracting passwords from Orion</b>
https://malicious.link/post/2020/solarflare-release-password-dumper-for-solarwinds-orion/

<b>Cloudflare analysis of Sunburst traffic on networks they have visibility to</b>
https://blog.cloudflare.com/solarwinds-orion-compromise-trend-data/

<b>Atlantic Council report on other supply chain attacks to give context to Solarwinds</b>
https://www.atlanticcouncil.org/in-depth-research-reports/report/breaking-trust-shades-of-crisis-across-an-insecure-software-supply-chain/

12/16/2020

<b>FireEye GitHub with Detections - Updated 12/16/2020</b>
https://github.com/fireeye/sunburst_countermeasures

<b>@webjedi - Amélie E. Koran's Blog post looking at the big picture tying together technical information, news, recent history, analysis of the attack, and more</b> 
https://webjedi.net/2020/12/16/fighting-the-fire-bucket-brigade-not-more-matches/

<b>SolarWinds Post-Compromise Hunting with Azure Sentinel</b>
https://techcommunity.microsoft.com/t5/azure-sentinel/solarwinds-post-compromise-hunting-with-azure-sentinel/ba-p/1995095

<b>Splunk Blog Post on using Splunk to detect Sunburst - Incredible amount of detail on utilizing Splunk</b>
https://www.splunk.com/en_us/blog/security/sunburst-backdoor-detections-in-splunk.html
Thanks for bringing this to my attention @phil_b_reed

<b>Ryan Kovar - @meansec - Splunk Queries for Sunburst</b>
https://github.com/rkovar/sunburstlookups

<b>TrendMicro Analysis</b>
https://www.trendmicro.com/en_us/research/20/l/overview-of-recent-sunburst-targeted-attacks.html

<b>Reversing Labs analysis of the malcious file build</b>
https://blog.reversinglabs.com/blog/sunburst-the-next-level-of-stealth

<b>RedDrip begins mapping Domain Generation Algorithms to compromised sites used by Solarwinds malware</b>
Includes many large companies and universities.
https://twitter.com/RedDrip7/status/1339168187619790848

12/15/2020

<b>SANS Internet Storm Center Diary - Published 12/14 - Updated 12/15/20</b>
https://isc.sans.edu/diary/rss/26884

<b>PICUS Analysis Map of TTPs to MITRE ATT&CK includes additional hashes </b>
https://www.picussecurity.com/resource/blog/ttps-used-in-the-solarwinds-breach

<b>Bruce Schneier Summary Write-Up of the Duo MFA Bypass from the Voloxity Report</b>
https://www.schneier.com/blog/archives/2020/12/how-the-solarwinds-hackers-bypassed-duo-multi-factor-authentication.html

12/14/2020

<b>Volexity Technical Review of Dark Halo - More detail about O365 DUO MFA Bypass </b>
https://www.volexity.com/blog/2020/12/14/dark-halo-leverages-solarwinds-compromise-to-breach-organizations/

<b>Analysis by Kyle Hanslovan </b>
https://twitter.com/KyleHanslovan/status/1338506923642122243

<b>@Che331o's Summary Thread of Jake Williams @malwarejake's SANS slides related to the breach </b>
https://twitter.com/Ch33r10/status/1338612270033670144

12/13/2020

<b>FireEye Technical Analysis </b>
https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html

<b>Analysis by Kim Zetter </b>
https://twitter.com/KimZetter/status/1338305089597964290



<a id="iocs"><h2>Additional IOCs</h2>

12/16/2020

<b>DLL Locations where the Malicious DLL has been discovered in the file structure - Updated 12/16/20</b>
https://gist.github.com/KyleHanslovan/0c8a491104cc55d6e4bd9bff7214a99e

<b>subdomain & DGA domain names used with Solarwinds Backdoor from @0xrb</b>
https://twitter.com/0xrb/status/1339199268146442241?s=20
https://pastebin.com/6EDgCKxd

<b>IPv4, Ipv6, and DGA domain names useed with Sunburst from @bambenek</b>
https://github.com/bambenek/research/tree/main/sunburst

12/15/2020

<b>PICUS Analysis - Map of TTPs to MITRE ATT&CK includes additional hashes </b>
https://www.picussecurity.com/resource/blog/ttps-used-in-the-solarwinds-breach​​​​​​​​​​​​​​

12/14/2020

<b>Additional Sunburst Hashes from Olaf Hartong</b>
https://gist.github.com/olafhartong/71ffdd4cab4b6acd5cbcd1a0691ff82f

12/13/2020

<b>Microsoft Security Response Center Blog Post </b>
https://msrc-blog.microsoft.com/2020/12/13/customer-guidance-on-recent-nation-state-cyber-attacks/



<a id="fud"><h2>Unsubstantiated Conspiracy, FUD, or Selective Manipulation of Information</h2></a>

This section was added to help address questions that arise during meetings, etc., from individuals with potentially different news sources. This section includes items that are determined to be false or misleading. Hopefully this helps address comments in organizations before they become difficult to remove from internal conversations. 

12/16/2020

<b>Theepochtimes - Dominion Software Intentionally Designed to Influence Election Results: Forensics Report</b>
https://www.theepochtimes.com/dominion-software-intentionally-designed-to-influence-election-results-forensics-report_3617675.html
Report discussing findings from Allied Security Operations Group Forensic report of Antrim County Michigan voting systems. The report can be viewed in a somewhat redacted form here. https://beta.documentcloud.org/documents/20423772-antrim-county-forensics-report. It alleges that findings regarding the voting system software allowed for maniuplation of vote counts. There are many problems with this report. CNN completed fact checking showing this organization has a regular history of misrepresenting information or using inaccurate data - https://www.cnn.com/2020/12/16/politics/antrim-county-michigan-error-trump-tweets-fact-check/index.html Further, Chris Krebs testified before the Senate on the factual innaccuracies of the report. A main point was the reported "68% error reate" which is a misrepresentation. This percentage was likely a percentage of ballots that sent alerts because they may have been a read error, but were not changes in the ballot themselves. Further, where 0's were reported in tabulation this was a placeholder for a parameter and was a misinterpretted by the report. https://www.freep.com/story/news/politics/elections/2020/12/16/antrim-county-report-debunked-by-former-trump-election-official/3923499001/
This is included because the Solarwinds breach, findings regarding Solarwinds (Serv-U software which was uneffected) backdoors, and alleged allection fraud are tied toegther. These is no factual correlation tying these together. 

<b>Just The News Claims Pentagon imposed emergency shutdown of SIPR (The network used to transmit classified information)</b>
https://justthenews.com/government/security/pentagon-imposed-emergency-shutdown-computer-network-handling-classified
The article cites sources stating, "this never happens during the day" with is the strongest evidence offered. There are several sites reporting the emergency shutdown of SIPR, but link back to this story. Further, other posts conflate the CISA order to remove Solarwinds as evidence of the SIPR shutdown. There is no actual evidence or confirmation this actually happened currently. Even this did occur there is no evidence it is directly related to Solarwinds. Even if it occured and was related to Solarwinds the article states it is not unusual for SIPR to be taken offline, just that being done in the middle of the day was unusual. Further, it would seem appropriate to take the network offline until it can be determined there is no impact from the Solarwinds breach and the CISA order can be executed to shutdown Solarwinds systems. These stories misrepresent the availability of facts and make many assumptions about related issues. 

12/15/2020

<b>Gateway Pundit Claims SolarWinds Vulnerability provides Backdoor Access to their Voting Machines</b>
https://www.thegatewaypundit.com/2020/12/dominion-used-version-solarwinds-orion-platform-provides-backdoor-access-voting-machines/
This article takes two disperate facts and tries to connect them directly. Yes, the Solarwinds Orion patch containing malicious code allowed a backdoor. Yes, Dominion Voting Systems used Solarwinds software. However, as stated by Solarwinds they are used in 425 of 500 Fortune 500 companies. They are a fairly ubiqitous IT tool. There is absolute zero evidence the Solarwinds software gives any sort of direct access to voting machines or code running on them. An Internet Archive link shows the Solarwinds tool being used at Dominion Voting Systems as evidence for the assumption regarding voting macine access. The Solarwinds software is the Serv-U file sharing server - https://web.archive.org/web/20201214093452/http://dvsfileshare.dominionvoting.com/Web%20Client/Mobile/MLogin.htm 
The Solarwinds Security advisory from 12/6 states Serv-U products are believed to be unaffected - https://www.solarwinds.com/securityadvisory. The Solarwinds software shown as in use at Dominion Voting Systems is not part of identified vulnerable software making.
Finally, even if direct code access or backdoors were available CISA worked to help advise state and local governments regarding vote security with ~95% of precincts having a verifiable paper ballot system along with their electronic voting. Even if voting software manipulated totals a manual recount of the paper records would identify the error. This is covered on the CISA Rumor Control page - https://www.cisa.gov/rumorcontrol#rumor17. There is no evidence of vote manipulation, especially via the Solarwinds breach. 

<b>Washington Post reports $280 million in Solarwinds stock was traded days before breach announcement</b>
This article is included here because it is being used to defend the potential insider trading and prove there was insider trading. The vast majority of these trades were completed by Thoma Bravo and Silver Lake Partners venture capital. There are some major concerns here as these to VC firms sit on the board of Solarwinds owning a majority of the company. A SEC investigation will likely occur to determine if there was insider trading. However, you will see the trades defended stating the outgoing CEO, Kevin Thompson's trades were planned. Thompson's trades were approximately $15 million, reported, and scheduled as part of a planned sell off. Some articles will conflate the Thoma Bravo and Silver Lake sales with the planned sale by the CEO.  
https://twitter.com/washingtonpost/status/1339059943442419714?s=20

<b>Gateway Pundit claims links to left wing politics, China, and US Elections process tied to Solarwinds Breach</b>
https://www.thegatewaypundit.com/2020/12/breaking-exclusive-owners-solarwinds-related-obama-clintons-china-hong-kong-us-election-process/
This article uses significant circumstantial evidence related to large equity firms and political donations. This article is all speculation with no actual evidence provided showing political influence being used to perpetrate the breach through board members. Further, it links these relationships to Dominion Voting Systems in an attempt to further undermine election results. There is no evidence of this and if there were CISA and Chris Krebs spent significant effort over the last four years working with state and local goverments to advise on the use of paper ballots verification. ~95% of precincts were using systems that had manually auditable paper ballots. There is no way to effectively "hack" this. As of this date all manual recounts matched the machine counts within the margin of error. 

12/14/2020

<b>Gateway Pundit claims there was a raid on Solarwinds headquarters </b>
https://www.thegatewaypundit.com/2020/12/breaking-fbi-texas-rangers-us-marshals-raid-solarwinds-hq-austin/
At the bottom of the article it includes a follow up tweet from the person that made the comment describing a raid at Solarwinds headquarters on Sean Hannity's radio show. They guest later says they never used the word raid. Law Enforcement agents going to the headquarters of an organization involved in a breach that could impact national security is a completely normal occurrence. There is no evidence this was a raid or the agents going to Solarwindsheadquarters were not there by invitation to cooperate with the breach response. 

