# My mental model of learning


My current employer has a seemingly inoffensive question in its job applications. "What’s your most memorable meal?" It's an opportunity for applicants to tell us about their personality. These days, most applicants lose points for obvious AI-generated answers. The following is one of the common variants.

"My most memorable meal was at `<SIMPLE OR UNLIKELY LOCATION>`; someone had made a `<OVERLY DETAILED DESCRIPTION OF FOOD>`. Nothing about it was `<DESIRED PROPERTIES>`—`<DETAILED LIST OF PROBLEMS>`—but `<OVERPOLISHED EMOTIONAL REVELATION CAUSED BY THE FOOD>`."

I tested the prompt and noticed how difficult it is to get something that sounds remotely human. Even after detailed prompts and multiple corrections, I barely got something passable. This issue lingered in my mind for a long time and eventually shaped my mental model of learning. It also gave me a habit. Now when I enter a new field, I try to capture my early ideas before expertise edits them out of me. That habit has helped me stay creative and produce output even when entering deep rabbit holes. Here I’ll do my best to explain why.

## Knowledge collapses the search space

Here’s another anecdote. My PhD thesis advisor once told me that I was spending too much time reading papers, and that I was going to learn the bad ways to solve the problem. He also told me that many of the top researchers at Caltech couldn’t care less about what most people write. The advice sounded strange because research is supposed to build on what is already known. 

Let’s **assume** my advisor was right. How is it possible to push the knowledge boundary forward without first reaching it? My working hypothesis is that knowledge doesn't simply give you new options. It also eliminates some of them. More precisely, knowledge constrains the distribution of ideas we are likely to produce.

![[26-05-knowledge-collapse.svg]]

When trying to solve a problem, there's a distribution of ideas or solutions that we can come up with. In the figure, that distribution is represented by the blue blob. Some of those ideas will produce good solutions, represented in green. A much smaller subset are the optimal solutions, represented in red. To make the figure cleaner, all the blobs are drawn in similar sizes. But the probability of a good idea is much smaller than the probability of a bad one. And the probability of an optimal idea is just a drop in the bucket. You can see this whenever you write. There are countless sentences you could put next, many that would be grammatical, fewer that would be good, and very few that would say exactly what you mean.

When we learn a skill or a way to solve problems, that knowledge biases us toward what we already know. Eventually it becomes our natural answer. In a way, we collapse the range of possible ideas into a constrained region. In the figure, the constraint is the dashed ellipse. It sits inside the green blob, which means we can now reliably produce good answers. But it also doesn't overlap with the red blob of better solutions, and it prevents us from reaching unusual possibilities. Thinking outside of that box becomes harder. We get more reliable answers at the cost of variation, and possibly creativity. The same thing happens in writing. Grammar and taste help us produce sentences that work, but they can also quietly censor the ideas that first sound wrong. This may be one reason why, as one article puts it, ["as researchers age, they produce less disruptive work."](https://nautil.us/is-this-why-science-advances-one-funeral-at-a-time-1280650)

## Generalization reopens the search space

Some people do learn almost everything in a field and still produce interesting research, often in the form of generalized theories. To make sense of this, I need one more oversimplification. 

![[26-05-generalization.svg]]

Consider a researcher who knows of two different approaches to solving a problem. These could be known methods from the same field, or ideas borrowed from different fields. In the figure, these methods are represented as two separate constraints. The researcher can draw solutions from either one. But after thinking about them and understanding the commonalities, they may be able to produce a single framework that covers both cases. The larger dashed blob in the figure is this generalization. It contains the ideas in the two constrained spaces, but it is not limited to them. It also lets the researcher try things in between, and sometimes extrapolate to new approaches. Abstracting the two methods relaxed their mental constraints and increased the range of accessible ideas. Maybe this higher level of thought can help them find better solutions than those previously known.

Knowledge also helps when we move into complex topics that involve many steps. Trying to solve all the steps at once is fragile. Roughly speaking, each unreliable step compounds the risk of failure. For example, if each step has a 10% chance of success and there are four steps, the probability of reaching a good solution is 0.01%. Knowledge lets us turn hard and unreliable steps into easier and reliable ones, which allows us to tackle more difficult and important problems.

So I arrive at the "uncontroversial" conclusion that knowledge is good, without having to abandon my hypothesis. Knowledge collapses the search space, but it can also make new search spaces available and easier to find.

## Capture bad ideas before you learn better

Now we are left with a practical problem. We want knowledge because it makes us competent, but we want to preserve access to the strange and simplistic ideas we had before knowledge made us sensible. I don't think that's possible. Once you acquire common sense, it becomes part of you. And after we learn, our ideas become better and also less naive. Every time we study, we destroy the opportunity to produce certain kinds of likely bad ideas.

My compromise is to write down bad ideas as they happen, especially while learning a new topic. I use those learning opportunities to think about how I would solve the problems before getting answers. My solutions are almost always worse than the one I'm given. But within my notes there's a hint of the broad distribution of ideas that I once had. And if only a few of them are better than existing methods, that may be enough to push the boundary of knowledge forward.

## Why this matters more in the age of AI

I can’t prove my hypothesis one way or another, but I like its implications, and I have a Pascal’s Wager-style reason to act as if it is true. If I’m wrong, I’ll have a bunch of useless notes I can discard. If I’m right, I’ll have a treasure trove of interesting ideas. So far, the wager has paid off. Those notes have occasionally helped me find creative solutions to problems I encountered.

My wager also brings me comfort in the age of AI. Will I matter in the future? Yes. Will AI learn to do most of my job? Probably. Will it replace me? I doubt it. I'll always be able to bring originality to the table.

My model also explains why AI struggles to write a good paragraph about a memorable meal. AI has an absurd amount of knowledge, and it can bring up relationships that only a few people could. It can even generalize and compound ideas in record time to produce new knowledge that makes mathematicians uncomfortable. But it can't escape the chains of knowing it all. It cant produce naive ideas that defy common sense and accepted doctrine. At least not in the way we do. It can write the perfect text, but it is up to us to bring back the typos and the new.

---

In Rio de Janeiro we went to a place serving some traditional bean stew. The pig hooves alone made it memorable already, but the highlight was an elderly man who jumped onto the platform where a live band was performing and pretended to be part of the band. He "played" a coat hanger as if it was a guitar while dancing inexplicably well for his age. He quickly won over the crowd, and the band looked at him like they should invite him to play again next time.
