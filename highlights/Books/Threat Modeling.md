# Threat Modeling

![rw-book-cover](https://images-na.ssl-images-amazon.com/images/I/51eOfrrNdYL._SL200_.jpg)

## Metadata
- Author: [[Adam Shostack]]
- Full Title: Threat Modeling
- Category: #books

## Highlights
- Problems where data is treated as code are common. ([Location 945](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=945))
- The first is to look for ways in which frameworks help you keep code and data separate. ([Location 948](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=948))
- You can also look at the data you're passing right before you pass it, so you know what validation you might be expected to perform for the function you're calling. ([Location 950](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=950))
- the nature of “you” and the additional steps are clear in your diagrams. ([Location 956](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=956))
- This set of attacks generally takes advantage of weak typing and static structures in C-like languages to enable an attacker to provide code and then jump to that code. ([Location 957](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=957))
- Modern operating systems tend to contain memory protection and randomization features, ([Location 960](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=960))
- You want to treat these as bugs because if you ship software, you've learned to handle bugs in some way. You presumably have a way to track them, prioritize them, and ensure that you're closing them with an appropriate degree of consistency. ([Location 1017](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1017))
    - Tags: [[favorite]] 
- Anytime you need to qualify your answer with “sometimes” or “also,” you should consider adding more detail to break out the various cases. ([Location 1048](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1048))
- There are two main types of validation activities you should do. The first is checking that you did the right thing with each threat you found. The other is asking if you found all the threats you should find. ([Location 1071](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1071))
- For each threat that you address, ensure you've built a good test to detect the problem. ([Location 1083](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1083))
- Follow this simplified, five-step process as you go:
  Draw a diagram.
  Use the EoP game to find threats.
  Address each threat in some way.
  Check your work with the checklists at the end of this chapter.
  Celebrate and share your work. ([Location 1096](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1096))
    - Tags: [[favorite]] 
- Diagramming Can we tell a story without changing the diagram? Can we tell that story without using words such as “sometimes” or “also”? Can we look at the diagram and see exactly where the software will make a security decision? Does the diagram show all the trust boundaries, such as where different accounts interact? Do you cover all UIDs, all application roles, and all network interfaces? Does the diagram reflect the current or planned reality of the software? Can we see where all the data goes and who uses it? Do we see the processes that move data from one data store to another? ([Location 1115](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1115))
- Threats Have we looked for each of the STRIDE threats? Have we looked at each element of the diagram? Have we looked at each data flow in the diagram? ([Location 1123](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1123))
- Validating Threats
  Have we written down or filed a bug for each threat?
  Is there a proposed/planned/implemented way to address each threat?
  Do we have a test case per threat?
  Has the software passed the test? ([Location 1130](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1130))
- During brainstorming, it is key to have an expert on the technology being modeled in the room. Otherwise, it's easy to make bad assumptions about how it works. ([Location 1203](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1203))
- It may help to focus your brainstorming with scenarios. ([Location 1222](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1222))
- With an “assumption of failure” in mind, the idea is to explore why the participants believe it will go off the rails. The value to calling this a pre-mortem is the framing it brings. ([Location 1236](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1236))
- Another variant of brainstorming is movie plotting. The key difference between “normal brainstorming” and “movie plotting” is that the attack ideas are intended to be outrageous and provocative to encourage the free flow of ideas. ([Location 1241](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1241))
- reviewing threats to systems similar to yours is a helpful starting point in threat modeling. ([Location 1257](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1257))
- It's difficult to know when you're done brainstorming, and whether you're done because you have done a good job or if everyone is just tired. ([Location 1274](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1274))
- Because of the difficulty of addressing threats illuminated with a limitless brainstorming technique and the poorly defined exit criteria to a brainstorming session, it is important to consider other approaches to threat modeling that are more prescriptive, formal, repeatable, or less dependent on the aptitudes and knowledge of the participants. ([Location 1278](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1278))
- As you dig in, the details matter greatly, but you usually start modeling from the conceptual level, ([Location 1308](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1308))
- It turns out that focusing on assets is less useful than you may hope, and is therefore not the best approach to threat modeling. ([Location 1320](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1320))
- From a threat modeling perspective, your reputation is usually too diffuse to be able to technologically mitigate threats against it. Therefore, you want to protect it by protecting the things that matter to your customers. ([Location 1355](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1355))
- There's no direct line from assets to threats, and no prescriptive set of steps. Essentially, effort put into enumerating assets is effort you're not spending finding or fixing threats. ([Location 1388](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1388))
- Unfortunately, like asset-centered threat modeling, attacker-centered threat modeling is less useful than you might anticipate. ([Location 1400](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1400))
- Talking about human threat agents can help make the threats real. ([Location 1419](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1419))
- There's real value in this, but it's not a sufficient argument for centering your approach on those threat agents; you can add that information at a later stage. ([Location 1422](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1422))
- Engineers may subconsciously project their own biases or approaches into what an attacker might do. Given that the attacker has his own motivations, skills, background, and perspective (and possibly organizational priorities), avoiding such projection is tricky. ([Location 1431](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1431))
- The work to create a comprehensive model led to an explicit list of common assumptions that could and could not be made. ([Location 1450](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1450))
- Anytime you find someone saying “sometimes” or “also” you should consider adding more detail to break out the various cases. ([Location 1717](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1717))
- Data can't move itself from one data store to another: Show the process that moves it. ([Location 1725](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1725))
- Don't have data sinks: You write the data for a reason. Show who uses it. ([Location 1725](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1725))
- create an appropriate tracking item to ensure that you recheck your diagrams at a good time. ([Location 1745](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1745))
- The STRIDE threats are the opposite of some of the properties you would like your system to have: authenticity, integrity, non-repudiation, confidentiality, availability, and authorization. ([Location 1804](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1804))
- Note that as you're using STRIDE to look for threats, you're simply enumerating the things that might go wrong. The exact mechanisms for how it can go wrong are something you can develop later. (In practice, this can be easy or it can be very challenging. There might be defenses in place, and if you say, for example, “Someone could modify the management tables,” someone else can say, “No, they can't because…”) It can be useful to record those possible attacks, because even if there is a mitigation in place, that mitigation is a testable feature, and you should ensure that you have a test case. ([Location 1843](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1843))
- STRIDE was not intended as, nor is it generally useful for, categorization. It is easy to find things that are hard to categorize with STRIDE. ([Location 1849](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=1849))
- There are variants of STRIDE that attempt to add focus and attention. STRIDE-per-element is very useful for this purpose, and can be customized to your needs. STRIDE-per-interaction provides more focus, but requires a crib sheet (or perhaps software) to use. ([Location 2359](https://readwise.io/to_kindle?action=open&asin=B00IG71FAS&location=2359))
