# Cyber News Roundup May 17, 2020

Hey everyone,

Well the semester is over … by cyber just keeps on happening. 

By popular demand, here is your Cyber News Roundup! 

## On Coronavirus … 

Well, here is an interesting twist on Coronavirus. The [Internet Governance Forum coalition on Net Neutrality and Community Connectivity](https://intgovforum.org/multilingual/content/dynamic-coalition-on-network-neutrality) are assessing the [impacts of Coronavirus](https://www.medianama.com/2020/05/223-covid19-makes-internet-access-and-openness-an-absolute-priority/). Their recent report focuses on Internet Access and Openness, as well as the factors that affect connectivity. These article addresses “zero rating plan,” which may have access to sponsored social networks on a mobile device. This article interestingly addresses the effect of users as they transition from “prosumers,” people that have access but also the ability to proactively contribute, and “consumers,” which only consume content. One is passive, and one is active. Individuals will interact with the internet based upon access (in terms of speed, blocking, throttling), and the services that they interact with. This piece reminded me of Tim Wu’s book, “[The Attention Merchants](https://www.theguardian.com/books/2016/dec/26/the-attention-merchants-tim-wu-review)." 

Regarding contact tracing apps, the UK’s National Health Service plan for an app accidentally leaked … or rather was unsecured on Google Drive. The document reveals that the app asked individuals to reveal precise location data, and coronavirus health status, [according to WIRED](https://www.wired.co.uk/article/nhs-covid-19-app-health-status-future). It appears that the information is sourced from a presentation that was not fully complete, however it may indicate potential privacy concerns regarding the app. The NHS has also released their [ethical principles that are guiding app development](https://faq.covid19.nhs.uk/article/KA-01029/en-us). 

If you’re saying to yourself … how can I learn more about contact tracing because of your own privacy concerns … now there is a course for it! WIRED recently took [the course](https://www.coursera.org/learn/covid-19-contact-tracing?edocomorp=covid-19-contact-tracing) and revealed their findings. I like this aspect of it: 

>"I expected to learn how to calculate infectious periods and draw complicated maps of contagion clusters—and the Johns >Hopkins course did cover all of that. But it also revealed how much of the job is about helping others make sense of a >confusing time, building relationships with people, and encouraging them to keep their communities safe. Contact tracers >might be working the phones from home, but they really are on the front lines.”

There are a number of threats from coronavirus, besides the obvious biological, connectivity, and privacy. Microsoft has open-source their [threat intelligence](https://www.microsoft.com/security/blog/2020/05/14/open-sourcing-covid-threat-intelligence/), so defenders can better understand and curtail some of these threats. 

## On Privacy (and Consent) … 

[Max Schrems](https://search.theregister.co.uk/?q=Max+Schrems), a lawyer and privacy advocate, has filed a [legal complaint](https://noyb.eu/sites/default/files/2020-05/complaint_aaid_redacted.pdf) with the Austrian Data Protection Authority against Google on their method of using Android Advertising IDs. Shrems, and his privacy group Noyb, have claimed that the advertising ID is considered “personal data.” [Shrems lawyer claimed](https://noyb.eu/en/complaint-filed-against-google-tracking-id) that the Android ID is akin to a tracking device, which does not take into account user’s choice. 

Think to the digital identity lesson and what actually comprises a piece of our identity. Can we be identified by a tracking ID? If we can be identified by it, does that make it personally identifiable information? Especially if it can be aggregated with other information, like a phone number. 

This is also an issue of “Opt-out vs Opt-in.” According to [Google’s policy](https://support.google.com/googleplay/android-developer/answer/6048248?hl=en), users are automatically opted-in, however when they opt out, the advertising ID is not deleted. So who is responsible? Well in this instance, it may be the [app developers](https://play.google.com/about/monetization-ads/ads/#!?zippy_activeEl=ad-id%23ad-id). 

According to [the Register](https://www.theregister.co.uk/2020/05/13/google_android_gdpr_complaint/): 

>Article 7 of the GDPR states that "the data subject shall have the right to withdraw his or her consent at any time." >Article 21 is a "right to object at any time to processing of personal data concerning him or her" for marketing and >profiling, following which the law states that "the personal data shall no longer be processed for such purposes.”

But further: 

>GDPR states in Article 12 that "the controller shall not refuse to act... unless the controller demonstrates that it is not >in a position to identify the data subject." 

Interestingly, the complaint also looked to how Apple manages their advertising ID and noted that in iOS, it can be "replaced with a non-unique value of all zeros to prevent the serving of targeted ads.”

The complaint and inquiry was based upon a Norwegian report called, [Out of Control](https://www.forbrukerradet.no/undersokelse/no-undersokelsekategori/report-out-of-control/), not to be confused with [Kevin Kelly’s](https://kk.org/outofcontrol/) book of the same name. 

If you are interested in this topic, please checkout a recent post from the FTC: [Developing a holistic view of complex and constantly evolving digital advertising markets and potential threats to consumers](https://presidentialinnovationfellows.gov/projects/ftc-otech/). This is a call for Presidential Fellows regarding Consumer Protections. 

## On Ransomware … 

We previously discussed the growing issue of ransomware. We talked through some really great blogs from Microsoft called “[Human-Operate Ransomware Attacks: A Preventable Disaster](https://www.microsoft.com/security/blog/2020/03/05/human-operated-ransomware-attacks-a-preventable-disaster/)."  The operative word here is “preventable.” By understanding the attack chain, and mapping it to the [ATT&CK framework](https://attack.mitre.org/), we can understand how adversaries both enter a victim’s environment, and exploit disclosed vulnerabilities, or brute-force [Remote Desktop Protcols](https://www.microsoft.com/security/blog/2020/04/16/security-guidance-remote-desktop-adoption/). (NOTE: See CISA’s recent report on the “[Top 10 Routinely Exploited Vulnerabilities](https://www.us-cert.gov/ncas/alerts/aa20-133a)." One of my former colleagues has recently posted a follow-up post to Microsoft’s piece, laying out the [textbook style](https://qomplx.com/recent-attacks-reveal-human-directed-ransomware-playbook/) of ransomware attacks.

While threat actors have a playbook, so do [defenders](https://github.com/counteractive/incident-response-plan-template/blob/master/playbooks/playbook-ransomware.md). It’s a cat and mouse game, and to quote “Cereal Killer” and “Lord Nikon” from Hackers, “Snoop on to them … As they snoop on to us.” 

So how do we stop this cycle? Well, we can take the FBI’s approach and [not pay](https://www.zdnet.com/article/fbis-new-ransomware-warning-dont-pay-up-but-if-you-do-tell-us-about-it/). Ransom relies on people paying … which propagates this cycle. We can also look at look at [Game Theory](https://academic.oup.com/cybersecurity/article/5/1/tyz009/5554879), and try to figure out from a business perspective how they may try to iterate. For example, charging people additional fees to victims [not to leak](https://www.bleepingcomputer.com/news/security/ransomware-now-demands-extra-payment-to-delete-stolen-files/) their exfiltrated data.

## On Social Media … 

In class, we discussed a Verge article (and [video](https://www.youtube.com/watch?v=bDnjiNCtFk4)) regarding YouTube moderators. Well, other moderators [from Google](https://www.youtube.com/watch?v=bDnjiNCtFk4) also began to speak up. In January, the Verge also published an article regarding the various measure that tech platforms can employ to combat issues with content moderation. These [included](https://www.theverge.com/interface/2020/1/28/21082642/content-moderator-ptsd-facebook-youtube-accenture-solutions): 

* Invest in research 
* Disclose the risk 
* Set a lifetime cap for exposure to disturbing content 
* Develop career paths of content moderators 
* Offer mental health support to workers after they leave the job

While not included in these recommendations, Facebook is paying a [$52 million settlement](https://www.theverge.com/2020/5/12/21255870/facebook-content-moderator-settlement-scola-ptsd-mental-health) for content moderators that developed PTSD. According to the Verge, “each moderator will receive a minimum of $1,000 and will be eligible for additional compensation if they are diagnosed with post-traumatic tree disorder and related conditions.” The article includes that the settlement covers 11,250 moderators. 

The content moderators were hired through Cognizant following the 2016 election, and criticism that Facebook failed to remove harmful content following the 2016 Presidential Election. The contractors were paid $28,800 per year to help proactively identify and remove harmful content. 

There are a few issues here, and none that can be directly tied to these large platforms. First, the growing scale of technology has (for better or for worse) caused technology companies to be reactive. While machine learning is being developed to properly identify this content, it takes human moderation. Second, what content should be moderated? Are there any free speech concerns regarding the content? Or does the content violate the Terms of Service of these platforms. Wall Street Journal published an interesting commentary in 2018 regarding the best way to [regulate social media](https://www.wsj.com/articles/a-better-way-to-regulate-social-media-1534707906). (TLDR: Companies should be proactive in engaging the proper stakeholders in creating solutions BEFORE the government needs to step in.) Third, (but maybe first) Section 230 of the Communications Decency Act (CDA) removes liability for content for posted on these platforms. The Communications Assistance for Law Enforcement Act of 1994 (CALEA) provides wiretapping capabilities to law enforcement, giving rise to the [EARN IT Act](https://www.judiciary.senate.gov/press/rep/releases/graham-blumenthal-hawley-feinstein-introduce-earn-it-act-to-encourage-tech-industry-to-take-online-child-sexual-exploitation-seriously), which targets Child Sex Abuse Material (CSAM), threatens to lessen providers Section 230 immunity in serving this content. 

Think of disincentives and incentives here. Are content providers incentivized to identify CSAM, or disincentivized? What are the factors potentially driving this change? Currently, they are required to remove  CSAM on their content, making them reactive. However, the EARN IT Act requires a more proactive response in identifying and removing content. Unfortunately, this advocates targeting end-to-end encryption since it prevents providers from identifying this content. However, the immunity provided by 230 can be earned through “safe harbors,” by complying to best practices. There is a really good piece from the [Stanford Center for Internet and Society](https://cyberlaw.stanford.edu/blog/2020/01/earn-it-act-how-ban-end-end-encryption-without-actually-banning-it), which I shared earlier in the semester. 

## On COPPA … 

The [Children’s Online Privacy Protection Act](https://www.ftc.gov/enforcement/rules/rulemaking-regulatory-reform-proceedings/childrens-online-privacy-protection-rule) imposes rules for online services that collection information from children under 13 years old. Well [TikTok may be violating](https://arstechnica.com/tech-policy/2020/05/tiktok-accused-of-breaching-us-child-privacy-regulations/) some of these privacy regulations. The Campaign for a Commercial-Free Childhood, the Center for Digital Democracy and the Electronic Privacy Information Center filed a complaint that TikTok is illegally collecting children’s data, as well as failing to provide parental consent for collection of children’s data on the platform.  The Dutch has also levied complaints against TikTok for violating children’s privacy, as well as providing explanation how personal data is collected, processed, and used. 

## On Computer Fraud and Abuse Act (CFAA) … 

Well … not entirely. The Ohio House Representatives has voted on legislation that criminalized malicious hacking attempts in [House Bill 368](https://www.infosecurity-magazine.com/news/ohio-votes-to-outlaw-attempted/). According to [InfoSecurity](https://www.infosecurity-magazine.com/news/ohio-votes-to-outlaw-attempted/), "the new law will prohibit a person from gaining access to, attempting to gain access to, or causing access to be gained to a computer, computer system, or computer network when certain conditions apply.” They also provided harsh penalties for those acting “recklessly” or targeting “elderly or disabled users.” The new guidance would update and expand the CFAA with felony-level expenses. 

We spoke about how the Supreme Court was reviewing the Eleventh Circuit Court’s decision the [broad interpretation](https://www.jdsupra.com/legalnews/supreme-court-to-resolve-circuit-split-66089/) of the CFAA in in United States v. Van Buren.  There are a few issues at hand here, which we discussed in class. Primarily, how well do a lot of these laws and policies keep up with a changing threat landscape. For example, CFAA was amended and codified in 18 U.S.C. § 1030 … which was written in the 1980s! The Communications Decency Act was written in the 1990s, and a lot of other policies and laws that we use to regulate content and police activity was adapted from previous laws and regulations. Additionally, we can see how states like Ohio are taking the proper measures to interpret and adapt the law. When there is contention, the Supreme Court has to review circuit splits. 

## On Surveillance … 

The Senate has voted to [reauthorize the USA Freedom Act](https://www.theverge.com/2020/5/14/21257782/surveillance-bill-congress-senate-pass-usa-freedom-reauthorization-act), which will restore government powers that expired in March. While there was an amendment to expand oversight, it may not restrict warrantless collection of internet search and web browsing data. According to the Verge, the Act will let law enforcement collect “[tangible things](https://www.csis.org/analysis/fact-sheet-section-215-usa-patriot-act)” related to national security investigations without a warrant. The House of Representatives will still need to approve the bill before sending to the President. 

If you want some more background on Surveillance, check out Motherboard’s most recent podcast on “[The Short and Terrifying History of Modern Surveillance](https://play.acast.com/s/cyber/74c4aadf-dd99-4811-baf5-493a04ee35f3).”

## On YouTube videos … 

[John Hultquist](https://twitter.com/JohnHultquist) began sharing videos from [CyberWarCon 2019](https://www.youtube.com/channel/UCBMhGVkkEWSovOTz0Z79kPg) this week. Additionally, someone shared this video from  [David Graeber vs Peter Thiel: Where Did the Future Go](https://youtu.be/eF0cz9OmCGw). Worth a watch for all you retro-futurists! 

## On Unsolicited Advice … 

I recently saw this post titled “[68 Bits of Unsolicited Advice](https://kk.org/thetechnium/68-bits-of-unsolicited-advice/)" from Kevin Kelly. I really enjoy Kelly’s books, like the aforementioned [Out of Control](https://kk.org/outofcontrol/) and [What Technology Wants](https://www.nytimes.com/2010/11/07/books/review/Coyne-t.html). Additionally, Tim Ferris published this video to his YouTube feed this week, titled "[Should You Specialize or Be a Generalist?](https://www.youtube.com/watch?v=wCPbPMRNnvk)” This is GREAT advice for anyone wondering what they should pursue in their career path. 

## On Conclusions … 

I will give a short wrap up of some interesting articles from the past week. I didn’t get into Disinformation here, but I liked the article, [Coronavirus, Conspiracy, and the Limits of Knowledge](https://medium.com/@agwmarten/coronavirus-conspiracy-and-the-limits-of-knowledge-bb3cd0d8d18d). Additionally, checkout this list of really cool [OSINT resources](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=2101593930) … some which may be used to track missing persons or perhaps verify disinformation. 
