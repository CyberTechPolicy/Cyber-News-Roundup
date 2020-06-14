# Cyber News Roundup June 14, 2020

Happy Sunday, 

It has been another crazy week in cybersecurity! We are seeing some interesting themes around security policy, and how it affects our defensive posture. Additionally, we are seeing multiple changes from social media and tech companies in terms of how they police and identify content on their platform. 

## On Robocalls … 

Robocallers have their reckoning! “[The Federal Communications Commission proposed a $225 million fine for 1 billion spoofed robocalls](https://www.fcc.gov/document/fcc-proposes-record-225-million-fine-1-billion-spoofed-robocalls)” The FCC “proposed” a $225 million fine for robocallers … however according to [Ars Technica](https://arstechnica.com/tech-policy/2020/06/1-billion-robocalls-nets-225m-fcc-fine-that-will-likely-never-be-collected/), the FCC has a [poor track record](https://arstechnica.com/tech-policy/2019/03/fcc-fined-robocallers-208-million-since-2015-but-collected-only-6790/) of collecting fines.

This is notable because $225 million is the largest FCC fine. It is a proposed fine however, because the commission first issues a Notice of Apparent Liability for Forfeiture. The alleged is given an opportunity to respond, and the process can end in a settlement or a fine. However, the settlement or fine cannot exceed $225 million. 

So why is the FCC so bad about collecting these fines? Well, according to a spokesman for the FCC, they lack the authority to enforce the forfeiture orders and unpaid orders get passed to the Justice Department. Paid fines are deposited in the US Treasury. So the [process of collecting fines](https://www.fcc.gov/news-events/blog/2015/11/25/enforcement-fines-collection-process) may be convoluted, because it relies on several different stakeholders. Additionally, most scammers, like Rising Eagle, the Texas-based health insurance telemarketer, may not be able to pay the fine. 

The Federal Trade Commission however has collected far more fines than the FCC. According to a report from [Ars Technica](https://arstechnica.com/tech-policy/2019/03/fcc-fined-robocallers-208-million-since-2015-but-collected-only-6790/), the FTC has collected $121 million out of $1.5 billion worth of penalties against robocallers since 2004. Comparatively, the [FCC has collected](https://www.wsj.com/articles/the-fcc-has-fined-robocallers-208-million-its-collected-6-790-11553770803?shareToken=st470b5cb07bdd4168b7021df9e0a913d5) $6,790 out of $208.4 million fines against robocallers since 2015. It may be hard to make an exact comparison between the two figures, but it seems that FTC may be more effective in collecting fines. The FTC may have [more authority](https://www.ftc.gov/about-ftc/what-we-do/enforcement-authority) than the FCC to levy fines, [collect](https://www.ftc.gov/news-events/media-resources/consumer-finance/debt-collection), and shut down operations. 

I think this story highlights some potential issues with the FCC. While they have the ability to propose fines, their collections capability may be limited. How does that affect robocallers capability to maintain operations, and how that influence the behavior of other robocallers? For example, Rising Eagle made class claims to offer health insurance plans. These are deceptive business practices, from which they likely profited at the expense of individuals that thought they were purchasing limited-duration health insurance plans.

Well, isn’t there a method to better screen callers for robocallers? In March 2020, the FCC finalized an anti-robocall order. According to [the order](https://www.fcc.gov/document/mandating-stirshaken-combat-spoofed-robocalls-0):

>The Commission adopted an item that adopts rules requiring originating and terminating voice service >providers to implement the STIR/SHAKEN caller ID authentication framework in the IP portions of their >networks, and proposes additional measures 

Part of the issue is that many individuals are still relying on landline phones, which makes it more difficult to use caller ID authentication. Additionally, how can phone companies better identify spoofed phone calls? FCC Chairman Ajit Pai announced plans for phone companies to deploy technologies that prevent spoofing of Caller ID. In 2019, the [Traced Act](https://www.congress.gov/bill/116th-congress/senate-bill/151/text) was proposed to prevent robocall abuse from spoofing, however adoption was voluntary, and you can imagine how that went. Again, there have to be incentives or disincentives to enacting any policy. Requiring voluntary implementation will not be effective unless there is some advantage to the stakeholder. 

So why is STIR/SHAKEN effective? It relies on digital certificates and public key cryptography to verify accuracy … something that should also be implemented for email, or identity authentication. These new requirements will finally be implemented by June 30, 2021 … and then our phones will be safe from robocalls, and all will be well with the world. 

Well, this only really affects US phone companies. Similar to our discussion of the effect of the proposed [EARN IT Act of 2020](https://www.congress.gov/bill/116th-congress/senate-bill/3398/text) on child exploitative material, it may drive it towards areas that cannot be easily policed … like overseas. According to [Ars Technica](https://arstechnica.com/tech-policy/2020/04/ajit-pai-follows-congress-instructions-requires-new-anti-robocall-tech/),  "Congress told the FCC to "consider" how the commission can "establish obligations on international gateway providers that are the first point of entry for these calls into the United States, including potential requirements that such providers verify with the foreign originator the nature or purpose of calls before initiating service.”

Can similarly be practices be used to identify phishing emails, or malicious content online? 

## On Facial Recognition … 

Facial recognition is taking a much needed pause! We started the semester talking a lot about [Clearview AI](https://www.nytimes.com/2020/01/18/technology/clearview-privacy-facial-recognition.html), and some of the issues associated with aggregating information from social media (which they deemed was a [first amendment right](https://www.cnet.com/news/clearview-says-first-amendment-lets-it-scrape-the-internet-lawyers-disagree/)). Also … we highlighted that [several other countries](https://nelsonslog.wordpress.com/2020/01/07/facial-recognition-for-the-public-yandex/) had comparable or better facial recognition. 

That aside, several companies stated that they will no longer offer, develop, or research facial recognition. These include IBM, [which stated](https://www.ibm.com/blogs/policy/facial-recognition-susset-racial-justice-reforms/) no more, “general purpose facial recognition” as part of their letter to Congress on Racial Justice Reform. Amazon also wrote a letter announcing “[a one year moratorium on police use of Rekognition](https://blog.aboutamazon.com/policy/we-are-implementing-a-one-year-moratorium-on-police-use-of-rekognition).” Amazon’s pause only applies to police use, they are allowing other organizations to continue using it to help reduce human trafficking victims and reuniting missing children with their families. [Microsoft claimed](https://www.nbcnews.com/tech/internet/microsoft-won-t-sell-facial-recognition-police-without-federal-regulation-n1230286) that they are waiting for federal regulation to begin selling it to police, Microsoft would like their to be a national law to govern facial recognition … will it happen? 

I think that Amazon’s choice of wording is quite apropos, in that they are “hoping” that it "might give Congress enough time to implement appropriate rules.” While I appreciate their optimism, I am not sure if their hopes and desires for national regulation around facial recognition will apply the necessary pressure to create a law. Again, while these companies are limiting the sale … are there other companies that produce this same technology? Does their “pause” eliminates the police need, want, or desire to use this technology, for human trafficking, finding missing children, or otherwise? 

So what ever happened to Clearview AI? Well, they are still around. And their technology may be deemed illegal in Europe. The European Data Protection Board [warned that](https://www.cnbc.com/2020/06/11/clearview-ai-facial-recognition-europe.html), "the use of a service such as Clearview AI by law enforcement authorities in the European Union would, as it stands, likely not be consistent with the EU data protection regime.” To which Clearview AI CEO stated, "Clearview’s image-search technology is not currently available in the European Union."

So why the sudden dialogue on Facial Recognition? Microsoft Research Scientist Timnit Gebru and MIT computer scientist Joy Buolamwini published a paper in 2018 demonstrating a racial bias in facial recognition. According to [the paper](http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf)
machine learning algorithms may discriminate based on race and gender. They presented an approach to evaluate bias … two years ago. 

Groups like [Amnesty International](https://www.amnesty.org/en/latest/research/2020/06/amnesty-international-calls-for-ban-on-the-use-of-facial-recognition-technology-for-mass-surveillance/) have called on a ban for facial recognition for mass surveillance because may exacerbate human rights violations by police. Additionally, they have teamed up with organizations like the [Algorithmic Justice League](https://onezero.medium.com/we-must-fight-face-surveillance-to-protect-black-lives-5ffcd0b4c28a) (cool title), the [ACLU](https://www.aclu.org/letter/coalition-letter-calling-federal-moratorium-face-recognition), and [Electronic Frontier Foundation](https://www.eff.org/aboutface) (also a cool title). 

Bias doesn’t just exist in facial recognition technology, it also exists in the industry. [Here is an account](https://statescoop.com/i-cant-sit-on-the-sideline-black-cios-on-facing-racial-bias/) of one individuals own experience with racial bias. There are systemic issues that we have to deal with as an industry, possibly before we can begin to address the issues with our technology. Ideally, these two issues should be resolved together, but I think we need to understand some of the human issues before we can address algorithmic bias. 

## On Fake News … 

The European Union [wants tech companies](https://www.engadget.com/eu-monthly-fake-news-report-facebook-google-twitter-130737189.html) to counter fake news for Europeans through monthly transparency reports on their efforts to squash disinformation campaigns. TikTok [already joined](https://twitter.com/VeraJourova/status/1270668019191218177) the EU’s voluntary Code of Practice on Disinformation.  

The European Union is also calling out some countries (and not to name names but China and Russia) for [spreading disinformation](https://www.bloomberg.com/news/articles/2020-06-10/eu-points-finger-at-china-russia-for-covid-19-disinformation). Shocking as it may seem, Russia and China were sharing misleading information about COVID-19, which may have exacerbated the public response to the pandemic.  

In May, we spoke about a Bellingcat campaign to uncover a [Pro-Chinese Government Information Operation](https://www.bellingcat.com/news/2020/05/05/uncovering-a-pro-chinese-government-information-operation-on-twitter-and-facebook-analysis-of-the-milesguo-bot-network/). Well, Twitter has followed suited and [taken down campaigns](https://cyber.fsi.stanford.edu/io/news/june-2020-twitter-takedown) related to China, Russia, and Turkey.

## On First Amendment … 

These tech companies have to strike a fine balance between identifying posts as misinformation and disinformation, while finding ways to respect individuals first amendment rights. Ideally, it should be easy to identify misinformation and disinformation based on our understanding of the truth. However as we discussed throughout the semester, their is nuance to social media posts that machines may not be readily able to discern. Additionally, platforms are trying to address the spread of groups that may threaten physical violence. According to the [Guardian](https://www.theguardian.com/uk-news/2019/sep/19/fastest-growing-uk-terrorist-threat-is-from-far-right-say-police), that fastest growing terror threat in the UK is from the Far Right. 

According to [Reuters](https://www.reuters.com/article/us-facebook-boogaloo/facebook-moves-to-limit-spread-of-boogaloo-groups-after-charges-idUSKBN23C011), Facebook will make it harder for individuals to find groups associated with the term “boogaloo.” [What’s a boogaloo](https://www.nbcnews.com/tech/social-media/what-boogaloo-how-online-calls-violent-uprising-are-getting-organized-n1138461)? They are individuals, normally identified through floral patterned shirts, that advocated for violent uprisings against the government and law enforcement. They can also usually be found with flak jackets, and guns. There are several factions of boogaloo movement, and the group that threatens violence is just one. Additionally, boogaloo is an evolving term that these groups have adopted, and my suspicion is that they may choose another term to confuse Facebook.

So are there alternatives to just preventing people from finding these groups? Well, you can deplatform. [Facebook has purged](https://onezero.medium.com/facebook-deplatforms-hundreds-of-anti-racist-skinheads-and-musicians-6b57bef204e1) the accounts of anti-racist skinheads for violating community standards … but may have accidentally targeted communities that oppose white supremacy. One of the groups, being called SHARP (Skinheads Against Racial Prejudice) may have been conflated with a neo-Nazi group according to their use of the term “skinhead” in their title. 

To recover their mistakenly banned accounts, individuals were requested to show their IDs. The last thing a number of individuals would want to send in a photo of their official ID, to recover an account that doesn’t appear to be in violation of any rules. Some users had their account reinstated without providing identification. Some people took it in stride, but it does beg the question how we can better manage digital identities, and create policies around the identification of content that violates community standards. 

## On Corporate Cybersecurity … 

In a surprising and [unprecedented ruling](https://www.cyberscoop.com/capital-one-incident-response-mandiant-decision/), Capital One must provide attorneys representing a group of customers suing the bank with their third-party incident response report from their breach last year. So what? Well, depending on the findings of the company, it may cause customers, and individuals to lose confidence in the company. Additionally, it may put pressure on a lot other companies to shore up their defenses, and better assess their policies. This latest filing follows a judicial panel action to [combine 60 class action suits](https://news.bloomberglaw.com/class-action/capital-one-breach-class-actions-consolidated-near-company-hq) into a single consolidated case. 

# Further Reading …

## A Tale of Two Cybers 

[A tale of two cybers - how threat reporting by cybersecurity firms systematically underrepresents threats to civil society](https://www.tandfonline.com/doi/full/10.1080/19331681.2020.1776658#.XuIjymgX1ds.twitter)

## On Artificial Intelligence  

[The Promise and Risks of Artificial Intelligence: A Brief History]
(https://warontherocks.com/2020/06/the-promise-and-risks-of-artificial-intelligence-a-brief-history/)

## On Data Justice  

[Critical data literacy tools for advancing data justice: A guidebook](https://datajustice.files.wordpress.com/2020/06/djl-data-literacy-guidebook.pdf)

## On Contact Tracing 

[What Happened to Matt Hancock’s Coronavirus Contact-Tracing App](https://www.thebureauinvestigates.com/stories/2020-06-13/where-is-matt-hancocks-contact-tracing-app)

## On Anti-Trust 

[Roadmap for an Antitrust Case Against Facebook](https://www.omidyar.com/sites/default/files/Roadmap%20for%20an%20Antitrust%20Case%20Against%20Facebook.pdf)

# Cyber News Roundup June 7, 2020

Hey everyone, 

Well, it has been the quite the week, and that may be putting it mildly. We’ve (hopefully) learned a lot this week with how we treat others, and how we want to be treated. We also observed a lot of these conversations being translated to cyberspace. 

## On Free Speech … 

In a personal statement on Facebook, CEO Mark Zuckerberg [openly stated](https://www.facebook.com/zuck/posts/10111985969467901) that he supports the Black Lives Matter movement. The statement came shortly after Zuckerberg [defended his decision](https://www.theverge.com/interface/2020/6/3/21278233/mark-zuckerberg-facebook-walkout-employee-meeting-leaked-audio) not to take action against a post from the President that Twitter labeled as “glorifying violence.” Zuckerberg stated, "our position is that we should enable as much expression as possible unless it will cause imminent risk of specific harms or dangers spelled out in clear policies.” This is part of Facebook’s policy of reviewing content instead of making the decision to leave up, or take down. 

If you recall in the first class, we briefly spoke about Alex Jones similarly [getting banned](https://arstechnica.com/gadgets/2018/08/twitter-gives-alex-jones-one-week-time-out-for-inciting-violence/) from various platforms for “glorifying violence.” In August 2018, Jones called out to his supporters to get their “battle rifles” ready against the media and other groups. Now, I say that the circumstances are similar in the terms of their suspension or ban were under the same criteria. However, I think there are also some similarities in the statements they are making.

If we take an objective look at the President’s statement, “When the looting starts, the shooting starts,” does it glorify violence? Or is it an attempt at a creative play on words? Or perhaps an intentional reference to the [civil rights era](https://www.npr.org/2020/05/29/864818368/the-history-behind-when-the-looting-starts-the-shooting-starts)? Was the post (which also mentions the military) a call to action, or a warning about violence that may be associated with looting? And was Twitter’s implementation of their policy decision an attempt to quiet a voice that they didn’t want to hear at a time of increasing tensions? Or was it really glorifying violence? 

These are decisions that I can not readily make. Additionally, I think it is interesting to see both Twitter and Facebook’s response to the post. While this may help to inform acceptable use policies for future posts on these platforms, to also demonstrates that these posts are up to interpretation. Most of these posts still require manual review to properly vet. As we continue to use posts like this to train a model, the method of flagging content may be increasingly different based upon our interpretation.  

Nellie Bowles for [The New York Times](https://www.nytimes.com/2020/06/05/technology/twitter-trump-facebook-moderation.html) provided interesting commentary:

>Civil libertarians caution that adding warning labels or additional context to >posts raises a range of issues — issues that tech companies until recently >had wanted to avoid. New rules often backfire. Fact checks and context, no >matter how sober or accurate they are, can be perceived as politically biased. >More proactive moderation by the platforms could threaten their special >protected legal status. And intervention goes against the apolitical self-image >that some in the tech world have.

Interestingly, the nonprofit Center for Democracy and Technology [claimed in a lawsuit](https://www.nytimes.com/2020/06/02/technology/trump-twitter-free-speech-lawsuit.html) that the President violated social companies’ right to free speech through his executive order. I say interesting because the President alleged that the social media companies were violating his free speech, so he issued the Executive Order. Now, the Center for Democracy and Technology is stating that the increased restrictions on Section 230 would limit the companies’ right to free speech. The Center for Democracy and Technology stated that the EO, "attacks a private company, Twitter, for exercising its First Amendment right to comment on the president’s statements.”

If we think more about this, did Twitter limit the President’s free speech? Was the post removed, or just flagged and the capability of using the platform limited? Are stripping Section 230 protections limiting social media platforms free speech? Does the President have the authority to do that? 

## (More) On Social Media … 

Does Twitter treat all of their users equitably? Senator Ted Cruz is calling for a criminal investigation of Twitter. According to [Axios](https://www.axios.com/exclusive-cruz-calls-for-criminal-investigation-of-twitter-3bec3098-3fbf-45b2-a5bf-cbda7cace940.html), Cruz is alleging that the company violated sanctions against Iran by allowing Iranian leaders to maintain accounts on the service. The US sanctions prohibit American companies from providing goods or services to Iranian officials. Further, Twitter allows Iranian officials speech on the platform for public interest, though some may find their speech objectionable. 

## On Copyright … 

Well, there are always reasons to remove content. If not for the language they are using, then copyright violations. According to [the Verge](https://www.theverge.com/2020/6/6/21282421/twitter-facebook-instagram-remove-trump-campaign-video), President Trump shared a campaign video that contained images of George Floyd. Twitter disabled the video, and Facebook and Instagram both removed the content for violating the DMCA. 

The Internet Archive began to offer scanned copies of books from three libraries, and offered readers unlimited borrowing. While this was a victory for open access, copyright holders did not share the sentiment. Major publishers Hachette Book Group, Inc., HarperCollins Publishers LLC, John Wiley & Sons, Inc., and Penguin Random House LLC filed a copyright infringement lawsuit agains the internet archive. 

# Cyber News Roundup May 31, 2020 

Happy Sunday! 

This week, the internet broke apart! Now when we say the internet broke apart, we are generally referring to changes or pushback to Section 230 of the Communications Decency Act (CDA). 

If you remember, [Section 230 states](https://www.law.cornell.edu/uscode/text/47/230): 

>*No provider or user of an interactive computer service shall be treated as the publisher or speaker of any information provided by another information content provider.*

So what happened with Section 230? 

## On Section 230 … 

The Trump Whitehouse published an [Executive Order on Preventing Online Censorship](https://www.whitehouse.gov/presidential-actions/executive-order-preventing-online-censorship/).
 The order may affect some of the liability protections from the CDA (above), and has had the internet reeling over the last few days. While several people have pushed back against the EO on Twitter ([including Twitter](https://www.nytimes.com/2020/05/28/technology/trump-twitter-fact-check.html)), the National Telecommunication and Information Administration has [60 days to file a petition](https://www.theverge.com/2020/5/28/21273822/trump-signs-executive-order-facebook-twitter-section-230-social-media-companies?utm_campaign=theverge&utm_content=chorus&utm_medium=social&utm_source=twitter) with the Federal Communications Commission (FCC). The issue at play is the “good faith” provision under the civil liability. Basically, no platform can be held lability for any action taken in “[good faith](https://www.law.cornell.edu/uscode/text/47/230)” to restrict access or make content available to information content providers.

So what is the context of this EO? 

The Verge has a [really nice timeline](https://www.theverge.com/21275532/trump-twitter-social-media-tweets), but generally it started on May 26, 2020 when Twitter labeled a [Tweet from the President](https://www.nytimes.com/2020/05/26/technology/twitter-trump-mail-in-ballots.html) as ‘[potentially misleading](https://blog.twitter.com/en_us/topics/product/2020/updating-our-approach-to-misleading-information.html).’ On May 11, 2020, Twitter published a post regarding their updated approach to misleading information. This is an extension of their [March policy](https://blog.twitter.com/en_us/topics/company/2020/An-update-on-our-continuity-strategy-during-COVID-19.html), which labeled Tweets that went against local public health information on COVID-19. The labeling is designed to alert people if content is confusing and/or misleading. 

Twitter (Tweeted that)[https://twitter.com/Policy/status/1266170586197262337], "This EO is a reactionary and politicized approach to a landmark law,” the tweet said. “#Section230 protects American innovation and freedom of expression, and it’s underpinned by democratic values. Attempts to unilaterally erode it threaten the future of online speech and Internet freedoms.” A Facebook spokesperson similarly delivered a statement opposing the order, noting that these measures are being implemented to protect their community from harmful content. 

I won’t get into all of the commentary on Twitter regarding the EO. However, as a number of armchair constitutional law experts have suddenly cropped up on Twitter, there are some [helpful guides](https://twitter.com/tiffanycli/status/1266059544318349313) to understand the current arguments. Just make sure that you are reading [both sides](https://twitter.com/donie/status/1266808857201971201) of the argument. 

Part of the conversation revolves around [Trump accusing social media of anti-conservative bias](https://www.npr.org/2020/05/27/863422722/trump-accuses-social-media-of-anti-conservative-bias-after-twitter-marks-his-twe). The US appeals court in Washington, D.C. [dismissed a lawsuit accusing tech companies of quelling conservative voices](https://techcrunch.com/2020/05/27/appeals-court-rules-in-favor-of-google-apple-facebook-and-twitter-in-anti-conservative-bias-suit/). The suit, Freedom Watch, Inc, v. Google, Inc. was filed by a non-profit, however according to TechCrunch, they failed to support their claim that the companies were “state actors.” TechCrunch also stated, "the companies cannot violate the first amendment, because banning users doesn’t constitute government abridgment of free speech.” 

## On First Amendment … 

A lot happened this week, and a lot happened on social media as a reaction to real world events. Zeynep Tufecki had a really good commentary about the [deterrent factor of social media](https://www.theatlantic.com/technology/archive/2020/05/case-social-media-mobs/612202/). As she mentions in her piece, the social media mob can at times sidestep fairness and due process. But at times, Tufecki continues, they can also protect the victims that may not be able or equipped to protect themselves. 

However, we should still consider the stakeholders at play here. Obviously, there are the users. But the platforms are the major stakeholder here, because the content is ultimately being displayed on their site. This goes back to the Section 230 issue, but how should we react against the voices that are democratic, or not American (or both)? According to the Verge, [YouTube is deleting comments with two phrases that insult China’s Communist Party](https://www.theverge.com/2020/5/26/21270290/youtube-deleting-comments-censorship-chinese-communist-party-ccp). YouTube confirmed that this was happening in error, for words that contained “共匪” (“communist bandit”) or “五毛” (“50-cent party”). According to [the Verge](https://www.theverge.com/2020/5/26/21270290/youtube-deleting-comments-censorship-chinese-communist-party-ccp):

>The term “共匪” is an insult that dates back to China’s Nationalist government, while “五毛,” (or “wu mao”) >is a derogatory slang term for internet users paid to direct online discussion away from criticism of the CCP. >The name comes from claims that such commenters are paid 50 Chinese cents per post.

Twitter and Reddit are challenging a new U.S. ruling that requires visa applications to disclose their social media handles. The decision is part of an “enhanced” screening protocol, and be used to determine that an individual may require more rigorous vetting. According to [Tech Crunch](https://techcrunch.com/2020/05/29/twitter-reddit-visa-social-media-handles/), these rules may affect individuals ability to, "“to speak anonymously and associate privately.”

## On Surveillance … 

House Democrats are pulling a bill to reauthorize the Foreign Intelligence Surveillance Act (FISA) after the President threatened to veto its passage. According to [CNBC](https://www.cnbc.com/2020/05/28/fisa-bill-house-withdraws-surveillance-legislation-amid-trump-veto-threat.html), the "The bill would reauthorize divisive foreign surveillance tools that aim to help U.S. law enforcement officials track suspected terrorists or spies.” Several months ago, an inspector’s general report highlighted that there were issues with FISA’s application in monitoring Trump campaign aide Carter Page. 

The American Civil Liberties Union (ACLU) has [pushed back against the use of stingrays](https://techcrunch.com/2020/05/27/aclu-ice-stingray-documents/), a cell-site simulator, by immigration authorities. Alexia Ramirez, a spokeswoman for the ACLU, stated “When cell site simulators search for an individual, they necessarily also sweep in sensitive, private information about innocent bystanders.” 

Arizona has filed a lawsuit against Google for tracking users, even if they have opted out of location tracking. According to State Attorney General Mark Brnovich, the location tracking is against the [Arizona Consumer Fraud Act](https://nakedsecurity.sophos.com/2020/05/29/google-sued-by-arizona-for-tracking-users-locations-in-spite-of-settings/): 

>While Google users are led to believe they can opt-out of location tracking, the company exploits other >avenues to invade personal privacy. It’s nearly impossible to stop Google from tracking your movements >without your knowledge or consent.

A Princeton postdoctoral researcher Gunes Acar found that turning off location history doesn’t stop Google apps from storing your information. Part of the issue is that users were given a false sense of control over the privacy settings. 

In Minnesota, authorities are using [contact tracing](https://twitter.com/i/events/1266773270939881472) to identify the locations of the arrestees. The Minnesota Public Safety Commission John Harrington stated that a number of the individuals may be from out of state. 

## On Copyright Holders … 

As we discussed in class, one of the principal stakeholders of the internet are the copyright holders. The current law protecting copyright on the internet is the [Digital Millennium Copyright Act (DMCA)](https://www.copyright.gov/legislation/dmca.pdf). The [U.S. Copyright Office](https://www.copyright.gov/policy/section512/section-512-full-report.pdf) is calling for stricter enforcement of the DMCA, specifically by pushing back against Section 512 Safe Harbor Provision. Similar to Section 230, this protects service providers from liability. Specifically, Section 512 protects copyright liability from copyright content that is uploaded onto their platform. Now, this issue may have some crossover with some of the first amendment arguments surrounding the Section 230 conversations in that it enables corporations to potentially censorship and in some instances, deciding fair use of copyrighted material. 

So who are the winners here? Well, it is complicated. The Copyright Office states that rights holders are the ones that are being unduly affected. However, it also presents issues to web users that have experienced “unfair harassment by platforms’ automated rights enforcement systems and copyright trolls.” Tech platforms are alleged to have undue power in determining copyright content, removing it, and removing “repeat infringers,” though I think the cost of this effort should also be noted. I don’t anticipate that it is easy actively identifying content, tracking users that have abused the DMCA, and removing that content. Internet service providers are also suggested to play a role in identifying copyright abusers in downloading peer-to-peer clients. 

So what will change when Congress updates the DMCA later this year? Models for resolving takedown disputes, harsher penalties, and guidelines around losing safe harbor provisions.


## On HBO Max? 

There have been a lot of changes to HBO recently. They recently launched HBO Max … however they don’t make it easy to acquire the service. I am all for [cutting the cord](https://www.techhive.com/article/3346020/cord-cutter-beginners-guide.html), though I feel that we may have moved in the opposite direction. We now have a glut of streaming apps, because instead of providing one alternative, now we have many alternatives. Each with their own exclusive programming and license rights to content. 

Back to HBO Max. I am not sure I fully understand how to get HBO Max, because it seems that HBO Max has agreements with select streaming platforms. Amazon Fire and Roku, while streaming devices, do not appear to support HBO Max. Additionally, depending on the age of your streaming device or television, you may not be able to watch it anyways. Well, who needs HBO when you have Cyber News! 

Anyways, [Edmund Lee @edmundlee](https://twitter.com/ShiraOvide/status/1266069534965981184) published a really great flow chart to let you know if you can actually watch HBO Max.   

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
