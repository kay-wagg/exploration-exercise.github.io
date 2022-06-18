## Communicating Digital History - 17 June 2022

### The Idea

Instructed to do so by the outline for the final part of this course, I reviewed Amalia S. Levi's [twitter thread](https://twitter.com/amaliasl/status/1245544256212807680) in search of a digital archive that sparked my interest. I am quite interested in gender and sexuality histories, so the [Digital Transgender Archive](https://www.digitaltransgenderarchive.net/) was immediately intriguing to me.

As I explored the collections and pieces featured in the archive, one that caught my attention was the [FTM International Collection](https://www.digitaltransgenderarchive.net/catalog?f%5Bcollection_name_ssim%5D%5B%5D=FTM+International). I was curious about the various topics that the archive applied to each newsletter contained in the collection. As I read some of the contents, I was especially drawn to the various identities included within the newsletters' "FTM" and how that seemed to influence the conceptions of masculinities contained within the collection. Thinking within the context of this course, I started to ponder how I could interact with various ideas of masculinities that the newsletters present all at once in a way that was both cohesive and creative. [Voyant](https://voyant-tools.org/) immediately sprang to my mind as somewhere to go to visualize these interactions. Thinking about that, I also began to consider the [Twine](https://twinery.org/) tutorial I did not "officially" complete but was familiar with. Since ideas about gender and presentation are so central to most interactions that individuals have with identity and the world as a whole, I thought some sort of simulation-esque prompt game would be a persuasive way to interact with the accounts of masculinity featured in *FTM International* that encouraged the viewer to put as much of their own life into the experience as possible while still being shaped by the contents of the data I would analyze. But, I was getting ahead of myself.

### Shooting for the Stars in An Enthusiastic but Poorly-Crafted Rocket

Initially, I was really thinking about the word clouds that voyant compiles. In my own search through the collection, I'd noticed the use of words like 'man' and 'boy', but I'd also noticed the absence of those terms as some of the authors compiled different perspectives and interactions with what it means to be a man or what it means to be masculine. I was especially curious about where those concepts were tied together and where they were not. I figured the word cloud would be a good visualization of this to guide my thinking and pondering. Perhaps if two words - such as "man" and "masculine" - both appeared, then the size difference between them might indicate what is prioritized in the writing featured in the newsletters. Thus, it might also indicate what was a more prominent concern to the authors of the newsletter - masculinity or manhood. It might also have offered that they were the same, or incredibly similar, sizes.

Of course, as I looked back at my log for the voyant tutorial paired with the tutorial itself on the course website, I quickly realized this was something out of the reach of the knowledge I had gained thus far in the course. I recalled that the voyant tutorial had a section about creating your own corpus based on your own curiosity and so I went back to look into that and saw a note that to do so, you should be familiar with the API tutorial from earlier in the course. Having chosen the newcomer strand, this was not the case for me. I looked over the tutorial, hopeful that it would be manageable in the poorly planned timeline I had allowed myself - at first it seemed like this was the case and I would be able to figure out how to interact with an API and create a corpus based on the FTM International Collection. However, as I delved further into the tutorial, it became apparent that I had two choices for moving forward with this final project: find a set of data material that could be collected with the code for the [Chronicling America website](https://chroniclingamerica.loc.gov/) **or** I could present the work I wanted to do but could not achieve with the skills I currently have.

I pondered this question for a while - probably longer than I should have without reaching out, but by the time I was opening up discord to do so, I already knew the answer I *wanted* to hear and based on Dr. Graham's insistence on the importance of failure and reporting on it in digital history, I figured that presenting the work I might some day be capable of doing or helping someone else do was as appropriate. I am not necessarily calling this a failure, anyway, more so me getting overexcited with possibilities and then forgetting my own skillset. Probably stubbornly, I'd rather assemble this mostly-hypothetical account of a plan that was derailed by a simple lack of knowledge and some unfortunate time management skills than give up on interacting with the Digital Transgender Archive. The archive was one I immediately bookmarked in the first part of this course while reading over Levi's thread since transgender history is one I find deeply moving on both personal and academic levels and I knew I wanted to look into it more. I was incredibly excited for the chance to dive into the Digital Transgender Archive once I reached this part of the course. Someday, hopefully in the near(ish) future, I would really like to come back to this with a little less of "I need to have something to hand in at the end of this semester" attitude going on and really dive into attempting the actuality of this project.

Given that explanation on why this is nearly entirely hypothetical, what follows is an outline of the plan I would use as it exists now.

### The Plan

- Check out the [API Tutorial](https://craftingdh.netlify.app/tutorials/apis/) on the course website! Go through it all, even the parts that aren't directly relevant to the project at hand to practice.

- **THEN** Stay on the tutorial page - we're taking huge steps! In all seriousness, check out the "other APIs" section to figure out how to adjust the python file to suit the Digital Transgender Archive.

- Now, use that knowledge to actually adjust the code to suit the Digital Transgender Archive, specifically for the *FTM International Collection*.

- Run the code to make the json file! Then, because json makes sense but csv is easier to read as less likely to be overwhelming, [convert](json-csv.com) the json to csv.

- Voyant time! Head over to voyant tools and upload that csv and adjust the settings as needed. Then, time to have fun in the name of historical research. Play with the word cloud, figure out what words are near each other sequentially, are there any multiple-term phrases that occur repeatedly, anything that looks like a transcription error?

- Keep asking questions until you don't have any more that voyant can answer, keep the link for that corpus and keep many notes on the answers you could and couldn't find.

- Review your notes. Then return to the corpus, ask those other questions you realized you had.

- Now, what do your notes say, what patterns are there and identify a broader question that ties all the ones you asked together. Then, answer that question.

- Whatever answer you find, review your notes and observations. Then, repeat that process, but this time with a completely different answer to the question that you did not actually think you agree with based on the data you have analyzed. Look through the data with that answer in mind, could the answer seem feasible to someone who did not know the details of the data that you do? Regardless of the result, think about the arrangement of your conclusion and how much it is dependent on assumptions and/or knowledge that existed prior to interacting with the specifics of the data.

- Once you feel confident about the conclusion you have reached and have critically considered the conclusion itself, now start thinking up a plan for the twine game itself informed by your conclusion and the ways that you want a potential player to interact with the game and its content.

> ###### What follows is a mock-up idea based on the reading of 4 out of 67 newsletters contained in the *FTM International Collection*, it likely looks incredibly different from the actuality of a game I would plan with the data analyzed using python and voyant.

> - Given a conclusion that surmised that the notions of masculinity and manhood are inherently linked but have a relationship that is largely informed by the person writing about them, I might design a game that encourages the player to make choices based on the preface that the pc is someone who identifies with the term FTM - but no further specificity than that. In a simulation-like manner, the player would be faced with choices where they bargain with the world around them through the lens of masculinity and its associated terms. Using encounters that mirror the contents of some of the newsletters' articles and interviews, the game would provide options based on different patterns of masculinity featured in tandem with the situations seemingly assumed masculinity. So a situation might look something like:

> "At a family dinner, your father and brother are talking about how it is difficult to feel like a *Real Man* when there is no initiation from boyhood to manhood as there is for girls to women in the biology of their menstrual cycles." [^1]

> "You:
> 1. Join in their conversation, echoing their sentiments.
> 2. Interrupt their conversation, providing your disagreement.
> 3. Counter their conversation, but offer empathy for their experience.
> 4. Disagree, but keep it to yourself.
> 5. Agree, but keep it to yourself."

- Regardless of the specific conclusion, the focus of the game would probably be trying to get the player to consider their answers and how the view they reflect in those answers might limit/change/expand the choices they are permitted to make.

- Once that plan is sketched out, replicate it in twine's interface.

- Then, once that's been sufficiently produced, look into this [repo guide on github](https://github.com/lazerwalker/twine-app-builder) on how to create a website for the game that doubles as a desktop app that is suitable for Mac and PC.

### The Result

Though that is a plan informed by my experience in the six weeks of this course, if I am being realistic, what this course has taught me a lot is that plans are best used for inspiration when it comes to digital history. I am almost confident that a minimum of 80% of these steps would result in something that would make me stare despairingly at my laptop before sending a desperate message to someone I know is much better informed than I am. The things I think are most important in this plan are the questions about the data's content that inform the plan itself - if/when I successfully get that data into a voyant corpus, what frequency of terms denoting masculinity, manhood, etc. are present? Are there discrepancies in those terms, what is there more frequently? Are they used in tandem? Are they always used in serious contexts? Is masculinity something that is joked about in the newsletters or is it restricted to more serious discussions of gender and identity? Is manhood something joyful, is it accompanied by enthusiastic adjectives?

Further, when I have compiled my research, when I have made my observations to conclude something about what I think the interactions between masculinities in *FTM International* indicate and am creating a twine plan, what am I trying to convey to the player? Who am I including when I write specific prompts using personal pronouns? Who am I including? How am I conveying this experience to the player? What do I want to decide for the player? What do I want them to decide for me? How do I want the game to interact with the authority that a player would bring?

More than the actuality of the digital skills themselves - though learning things like markdown, using the command prompt, navigating Github and many more has been extremely valuable - the biggest pieces of this course that I used thinking about this project and what I would want to create, communicate, and accomplish with it were the readings and the attitude that underlined the course's structure. Considering things like accessibility, presentation, and purpose were not new concepts but they were re-contextualized by the interactions had with the digital space. Further, they were both informative and informed, providing me an opportunity to do that work of using knowledge I already had in a new space while also taking new knowledge into pre-existing spaces beyond the so-called 'digital void'.

While this quasi-'final project' for the course hasn't truly resulted in a final project so much as a final reflection, it remains reflective of my learning curve within this course.

In an early reflection, I suggested that by the end of the course I'd like to be in a place where if I came across a survey like the one Kimberley Martin describes, I would be confident about calling myself a digital historian and express comfort (or at least *more* comfort than now) across most digital environments.[^2] I might not absolutely commit to calling myself a digital historian with the completion of this course - though, in truth, that was an optimistic goal since I am not super comfortable calling myself a historian after over three years in the program. But, if someone called me a digital historian, I would not counter that. I am also infinitely more comfortable in the digital spaces that this course has navigated than I was prior to starting the course, specifically tools like R, Voyant, and StoryMaps that manipulate, analyze, and present data. Though there is not much actual ephemera to this exploration beyond a static website and the markdown that defines its presentation, the plan itself is far more than I would have been capable of compiling or thinking of prior to this course. 

[^1]: "FTM Newsletter #11."  Periodical.  1990.  Digital Transgender Archive,  https://www.digitaltransgenderarchive.net/files/w95050678

[^2]: Martin, Kimberley. 2020. *Clio, Rewired: Propositions for the Future of Digital History Pedagogy in Canada.* Canadian Historical Review 101.4, 623-624.
