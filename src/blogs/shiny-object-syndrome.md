_*Was thinking about this randomly at 12am and decided to journal it down before it slipped my mind (which happens quite often!)*_

_*Disclaimer: these are just my personal thoughts, I don't represent anyone or any entity. Treat it as a random junior engineer's rants, thoughts and observations about AI*_

---

# Don't forget your roots

Walk into the tech world right now and the noise is deafening. A few years ago, the joke was that a new JavaScript framework dropped every week. Today, it’s a new LLM, a new "agentic" workflow, or another AI wrapper claiming to revolutionize engineering.

Technology is moving fast - real fast. And in the last few years with the advent of AI, there has been a real gold rush in our industry. Just look around your workplace or in the open-source space, unless you are living under a rock, you wouldn't have missed the buzz in the industry surrounding the latest AI or LLM tools.

But recently, the honeymoon phase hit a speed bump. As providers crank up their API charges (classic venture capitalism tactic to lock you in before squeezing profits lol), people are suddenly forced to question the true cost of this emerging technology.

## Resume-Driven Development, Groupthink

People are forcing/experimenting using AI into every corner of their applications and programming workflow, forming a dangerous dependence and risk on it.

`It looks like everyone is using AI, will I fall behind if I don't embrace it?`

Yes you will fall behind, because AI is providing real value in today's world and introducing a whole new paradigm in the space. But there is a time and place for everything, and choosing which tool to use in your toolbox is an important skillset. You wouldn't use a kitchen knife to trim your fingernails right? (Or in more technical terms, building out Kubernetes + Multi AZ cloud setup for a hello world static HTML page lol.)

![Pokemon Emerald](/blogs/shiny-object-syndrome/pokemon-emerald.png)
_Using Key Items incorrectly in the game Pokemon Emerald_

Sometimes we need to ask the boring engineering questions (in the context of introducing LLMs into our applications):

- Isn't a simple algorithm enough to solve the underlying problem?
- Why are we introducing an expensive blackbox when a clean, predictable and unit-testable algorithm solves the problem?

Software engineering thrives on determinism. LLMs are, by their very nature, non-deterministic statistical engines. Trading stable, predictable code for unpredictable non-deterministic workflows isn't a good tradeoff. There is a beauty in simplicity (**_less is more_**).

This era of software engineering has a deadly trap - groupthink. Are we blindly following what the "tech influencers"
are pushing? Or are we actually applying this new paradigm to solve the problem at hand better? Think critically and apply your craft.

## Talent, atrophy

I feel like we are at a crossroads when it comes to our industry's engineering culture. **Are we using AI to help us think? Or are we leveraging AI to help us think better?** By offloading our cognitive thinking to AI, we are skipping the actual motions of engineering. Instead of understanding the underlying concepts and forming a solution, we turn to AI to help us create quick solutions without fully understanding them.

**_The journey is more important than the destination._** Fixating solely on the end goal means we missed out on all the experiences and learnings from the process. This short-circuiting has broken the talent pipeline in our industry. We are seeing a stalling generation of juniors who are struggling to transition into senior roles.

You cannot develop senior-level intuition without diving deep into the messy parts of software. When you let a model bypass the friction for you, you miss out on the vital experience of hitting a wall, making stupid mistakes, and staying up late to fix the things you broke.

![Naruto](/blogs/shiny-object-syndrome/naruto.jpg)
_Pushing your limits_

If you never go through that pain, you never build the deep technical muscle required to solve even harder problems. It's like going to the gym and lifting that same 5KG dumbbell without any progressive overload over a year. You need to push your limits (LIMIT TEST!!) to get better at what you do.

## Judgement, wisdom

![Dunning Kruger Effect](/blogs/shiny-object-syndrome/dunning-kruger-effect.png)
_A graph illustrating the dunning kruger effect_

I'm saying it. We are trapped in a massive **Dunning Kruger cycle**. Because AI tools can spit out functional code in seconds, it creates a really dangerous illusion of competence. It's really good at making people believe its 100% there when it's not.

How can we judge to be correct what we do not know? Especially something that does not work 100% of the time.

Ironically, I think building engineering judgment begins with this Socrates quote: **"I know that I know nothing"**. Acknowledging what you don't know is the prerequisite for building genuine taste. You cannot develop engineering intuition or taste by accepting a model's output blindly. You build it by being skeptical, looking at the code, and realizing that you need to understand why and how it works, not just that it works.

Because when the abstraction inevitably leaks, a prompt won't save you. If you don't know how things work under the hood, you are completely helpless in production. How do you fix a system when you dont understand the underlying nuts and bolts?

Our value today as engineers is bringing good taste, judgement and engineering context to the problem. This is what exactly allows you to leverage AI to its highest potential, allowing you to spot flaws and apply a "systems thinking" mindset.

Boom. Thats force multiplication right there.

## Crushing the facade of abstractions, accquring good taste

It all begins by crushing the facade of high-level abstractions. We need to stop treating the stack lilke a collection of black boxes and learn to tinker again.

![Circle of Life](/blogs/shiny-object-syndrome/circle-of-life.jpg)
_Circle of life - philosophical concept symbolizing how everything in the universe is interconnected_

When you allow yourself to be genuinely curious (intrinsic rather than extrinsic), you realize that learning a single concept isn't an isolated event. **Everything is related**. A single concept can form its own massive sub-knowledge graph and interlink across multiple graphs. Let me explain with a simple context.

![Knowledge Graph](/blogs/shiny-object-syndrome/knowledge-graph.png)
_JWT Knowledge graph_

JWTs or JSON Web Tokens, this is what we commonly use to authenticate HTTP requests across the web these days. This was one of my concepts that I had trouble wrapping my head around early on in my career (I think like 4-5 years ago at the point of writing this blog)

It started with a basic question: What is a JWT? That immediately forced me to understand the parent concepts of Authentication vs. Authorization as well as Encoding (base64).

To figure out why we use it, I had to look backward at historical session-based auth and the architectural pain of scaling stateful sessions across multiple servers.

Once I understood the stateless nature of JWTs, the question of how to use JWTs and store them on the browser, leading to exploring JWT in a software program (node.js libraries, storing securely using HTTP cookies, HTTP Headers Bearer Auth).

Eventually, I "expanded my knowledge graph" with concepts like Symmetric/Asymmetric encryption, JWKs, protocols like OAuth 2.0, OIDC and more.

Of course, all of this didn't happen overnight. It happened over years. But that is exactly the point: you have to build your knowledge graph, extend it over time, and actively connect the links to other sub-graphs. That is what I found to help me build mastery.

## Closing thoughts

Now after all the doom and gloom, I'm not saying that using GenAI is bad - moreover I feel like it's actually a productivity booster and probably here to stay.

But I think it's important to take a stance of: **"Yes, I will use AI to boost my productivity, while understanding what it is actually generating. AI is another tool in my toolkit."**.

Avoid shiny object syndrome by sticking to the fundamentals!

### Don't forget to apply the "engineer" part of being a software engineer :)
