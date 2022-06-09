# Securing Netflix Studios at Scale Netflix TechBlog | Netflix TechBlog

![rw-book-cover](https://readwise-assets.s3.amazonaws.com/static/images/article2.74d541386bbf.png)

## Metadata
- Author: [[Netflix Technology Blog]]
- Full Title: Securing Netflix Studios at Scale Netflix TechBlog | Netflix TechBlog
- Category: #articles
- Document Tags: [[prodsec]] 
- URL: https://netflixtechblog.com/the-show-must-go-on-securing-netflix-studios-at-scale-19b801c86479

## Highlights
- 1) streamline any security processes so that we could get applications built and deployed to the public internet faster 2) raise the overall security bar so that the accumulated risk of this giant and growing portfolio of newly internet-facing, high-sensitivity assets didn’t exceed its value
    - Tags: [[prodsec]] 
- There were security checklists for developers, but they were lengthy and mostly manual, neither of which contributed to the goal of accelerating development. Adding to the complexity, many of the checklist items themselves had a variety of different options to fulfill them (“new apps do this, but legacy apps do that”; “Java apps should use this approach, but Ruby apps should try one of these four things”… yes, there were flowcharts inside checklists. Ouch.). For development teams, just working through the flowcharts of requirements and options was a monumental task.
    - Tags: [[prodsec]] 
- Our second observation centered on strong authentication as our highest-leverage control. Missing or incomplete authentication in an application was the most critical type of issue we regularly faced, while at the same time, an application that had a bulletproof authentication story was an application we considered to be lower risk.
    - Tags: [[prodsec]] 
- Netflix engineers talk a lot about the concept of a “Paved Road”. One especially attractive part of a Paved Road approach for security teams with a large portfolio is that it helps turn lots of questions into a boolean proposition: Instead of “Tell me how your app does this important security thing?”, it’s just “Are you using this paved road product that handles that?”. So, what would a product look like that could tackle most of the security checklist for a team, and that also could give us that architectural property of guaranteed authentication?
    - Tags: [[prodsec]] 
- For adoption, both the security team and our team were asking the same question of developers: Is there anything that prevents you from using Wall-E? Each time we got an answer to that question, we tried to figure out how we could address it.
    - Tags: [[prodsec]] 
- Also, with fewer exceptions and clearer criteria for apps that should adopt this paved road, our AppSec Engineering and User Focused Security Engineering (UFSE) teams could automate security guidance to give more appropriate automated nudges for adoption. Every leader’s security risk dashboard now includes a Wall-E adoption metric, and roughly ⅔ of recommended apps have chosen to adopt it. Wall-E now fronts over 350 applications, and is adding roughly 3 new production applications (mostly internet-facing) per week.
    - Tags: [[prodsec]] 
- The difference between 2–4 “right-ish” ways and a single paved road one is powerful.
    - Tags: [[prodsec]] 
- These applications have fewer, less severe, and less exploitable bugs compared to non-Wall-E apps, and we rarely need an urgent response from app owners (we call this not-getting-paged-at-midnight-as-a-service).
    - Tags: [[prodsec]] 
- If you can do one thing to manage a large product security portfolio, do bulletproof authentication; preferably as a property of the architecture
    - Tags: [[prodsec]] 
- Security teams and central engineering teams can and should have a collaborative, mutually supportive partnership
    - Tags: [[prodsec]] 
- “Productizing” a capability (eg: clearly articulated; defined value proposition; branded; measured), even for internal tools, is useful to drive adoption and find further value
    - Tags: [[prodsec]] 
- A specific product makes the “paved road” clearer; a boolean “uses/doesn’t use” is strongly preferable to various options with subtle caveats
    - Tags: [[prodsec]] 
- Hitch the security wagon to developer productivity
    - Tags: [[prodsec]] 
- Harvesting intent is powerful; it lets many teams add value
    - Tags: [[prodsec]] 
- To briefly recap, here’s a few of the things that we take away from this journey:
  If you can do one thing to manage a large product security portfolio, do bulletproof authentication; preferably as a property of the architecture
  Security teams and central engineering teams can and should have a collaborative, mutually supportive partnership
  “Productizing” a capability (eg: clearly articulated; defined value proposition; branded; measured), even for internal tools, is useful to drive adoption and find further value
  A specific product makes the “paved road” clearer; a boolean “uses/doesn’t use” is strongly preferable to various options with subtle caveats
  Hitch the security wagon to developer productivity
  Harvesting intent is powerful; it lets many teams add value
    - Tags: [[prodsec]] [[favorite]] 
