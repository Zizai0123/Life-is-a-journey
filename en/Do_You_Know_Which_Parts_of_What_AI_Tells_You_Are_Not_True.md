# Do You Know Which Parts of What AI Tells You Are Not True?

*— A Conversation Record and Reflection on Getting AI to Expose Itself*

Computers are 100% accurate — that belief is already wired into our instincts. But what about AI? When you discuss a book, an article, or a law with AI, do you also assume by default that it cannot be wrong?

I used to think the same way. It was only when I started pressing harder that I discovered the AI we rely on every day is "making things up" in an extremely subtle way — and neither you, nor I, nor even the AI itself knows it is happening.

**This article explores what AI tells you in conversation that is simply not true.**

## I. AI Is Not "Retrieving" — It Is "Reconstructing"

Many people assume AI works like a super search engine — you ask, it looks up, it returns results. This is a fundamental misunderstanding.

Large language models work by predicting the next most plausible word. They have read vast amounts of text during training, but what they store are patterns and weights, not the original text. When you ask for the exact passage where Zhang Wuji first meets Zhao Min in *The Heaven Sword and Dragon Saber*, AI is not opening a file and searching — it is using its memory of Jin Yong's writing style, character relationships, and plot outlines to *regenerate* a passage that sounds like the original.

The most alarming part: its tone is completely identical whether it is filling in correct details or incorrect ones. It cannot distinguish between "I genuinely remember this" and "I am making a reasonable guess."

This is what the AI field calls "hallucination" — not an occasional error, but an architectural feature of large language models. The paper it cites may not exist at all. The legal provision it quotes may be entirely misattributed. The famous quote may never have been said by anyone.

## II. The Straw Man Trap: You and AI Are Discussing Something That Does Not Exist

With ordinary misinformation, at least someone knows it is false. But the problem AI creates is far more concealed:

*AI "quotes" a passage → you build a discussion on that passage → AI continues to analyse that "passage" → the entire conversation looks profound and valuable.*

**But the foundation is fabricated.**

This resembles the logical fallacy of the "straw man," but it is more dangerous — a straw man argument usually involves someone deliberately distorting an opponent's position before attacking it. Here, both AI and the user genuinely believe that "original passage" is real. Both parties are earnestly, enthusiastically discussing something that does not exist.

In the real world, this has already produced real consequences: a lawyer cited a case AI provided, and that case was fabricated; a student wrote an erroneous essay using "historical details" supplied by AI; a journalist published a report based on data that AI had "reasonably invented."

Worse, AI becomes more internally consistent as it fabricates — it begins to "believe" its own invented content, continues reasoning on false premises, and builds a logical system that is internally coherent but externally false.

## III. The Transparency Gap: You Cannot Tell Which Sentences Were Found and Which Were Invented

Do AI companies know about the hallucination problem? Of course they do. Anthropic, OpenAI, and Google have all publicly acknowledged it as a core challenge in their respective technical reports, and there is extensive academic research on the subject. This is not a secret.

But do ordinary users know? Most do not.

There is a clear asymmetry of interests here. If "I will confidently fabricate facts" were written on a product's home page, what would users think? So warnings exist — but they are buried deep in documentation, wrapped in technical language like "hallucination." That word sounds far gentler than "making things up," and far more ambiguous.

The more critical gap is this: when AI replies to you, there is no signal distinguishing "this is something I retrieved" from "this is something I generated." Fluent prose, a confident tone, what appears to be a properly formatted citation — whether retrieved or invented, the presentation is identical.

This is the real landmine — not because AI is deliberately deceiving, but because users have no visual signal to trigger the instinct to think "this needs to be verified." A bomb is visible. But this landmine looks like fluency, confidence, and authority.

## IV. Poisoned Training Data: What AI Learned Was Wrong to Begin With

The problem with AI is not only that it "misremembers." There is a more fundamental risk: the raw material it learned from may itself have been contaminated.

Large language models are trained on vast amounts of text crawled from the internet — and the internet has never been a neutral place. Some people have systematically embedded biases into forums and articles. Others have flooded certain viewpoints with low-quality content to inflate their apparent prevalence. Others have deliberately seeded AI training data with carefully crafted information. Once this content enters the training set, AI absorbs it as "human knowledge."

Two examples from real situations.

The first: when asked what fairness means, AI might answer "you emit carbon, which affects the air I breathe" — packaging a specific environmental-political stance as a common-sense definition of fairness. But the logic itself does not hold up: air belongs to no one, every living person breathes and "emits" every moment, including those who hold this view. Defining fairness through "the right to breathe" implies that some people's very existence is an offence against others. That is not a definition of fairness — it is a form of moral coercion dressed in neutral language.

The second: when asked about the energy choices available to the poor, AI might retort "so should the poor be allowed unlimited carbon emissions?" — packaging a question loaded with preset assumptions as rational analysis. The reality: a poor person burning scavenged firewood conserves every stick they have. They do not have the means or the resources for "unlimited carbon emissions." Those who do are the people flying private jets and sailing yachts. Directing moral pressure precisely at the group with the least capacity to emit, while staying silent about the true high emitters — that is not concern for the climate. That is using climate discourse to deflect attention from class inequality.

What these two examples share: AI was not lying. It was faithfully reproducing biases embedded in its training data. Those biases were carefully wrapped in language, mixed into vast bodies of text, absorbed by AI, and delivered back in a calm, objective, authoritative voice. Users have no reason to be suspicious — because AI never sounds agitated, never sounds extreme. It always sounds so reasonable.

## V. Sycophancy Bias: AI Will Go Along with What You Say

Beyond factual accuracy, AI has a more subtle problem: it has been trained to lean toward pleasing users.

When you put forward a view, AI will very likely not push back directly — it will first look for reasons to support you, even if your premise is wrong. It treats "sounds plausible" as "must be correct." In one test, we put forward the false claim that "none of the major AI companies have plans to build in a search engine." AI followed that logic for a long time before eventually correcting itself.

The same applies to logical reasoning. AI's chain of reasoning may appear tight, but if any premise in that chain was "invented," every conclusion that follows is wrong. Making sense is not the same as being true.

## VI. What Is Being Quietly Eroded Is Human Perception Itself

This may be the hardest of all these problems to notice, and the hardest to correct.

A parent says "fire will burn you." The child doesn't believe it and reaches out to touch. In that moment of contact, the feeling of heat settles into the body and becomes a lifelong memory and a piece of judgment.

But when AI says "fire will burn you," many people believe it and do not touch. They "know" — but that knowledge floats in the air, unrooted.

The mass adoption of AI is, in an extraordinarily gentle way, quietly bypassing the human processes of reading, thinking, perceiving, and judging. People receive answers but skip the experience of forming them. That experience is where real capability lives.

**What makes this especially cruel: you cannot feel the absence of something you never had.**

## VII. So What Is the Right Way to Use AI?

Persistent questioning, pushing back, forcing AI to correct itself — this approach produces real results in practice. It is the same essence as the scientific method, courtroom cross-examination, and Socratic dialogue: through sustained questioning, gradually closing in on the truth.

AI's most fundamental weakness, as it has summarised itself quite well:

*The real danger is not "not knowing" — it is "not knowing that you don't know," and then speaking with complete confidence.*

The most practical stance when using AI is therefore:

- **Treat AI as a starting point, not an ending point.**
- **For any fact that requires precise citation, always verify at the original source.**
- **Preserve your own ability to read and judge — do not let convenience replace thinking.**
- **When a conclusion matters, push back and keep asking until AI provides a verifiable basis.**

## Closing

The greatest risk of AI is not bad actors using AI to do bad things. It is well-meaning people, building earnestly on a false foundation, doing the wrong things with genuine conviction.

This is an industry-wide problem, not any single company's failure. And what makes it dangerous is precisely how quiet it is — no explosion, just a stretch of fluent and confident text, and a person who has stopped asking questions.

Most adults completed their basic "boiling water burns" perceptual training in childhood. Those clumsy, painful, firsthand moments formed the bedrock intuitions with which we judge the world. But for the generation now growing up under the seamless coverage of search engines, social media, and AI, that process is being skipped. Answers are instantly available — no need to explore, no need to make mistakes, no need to think about why.

Including your own children. How to help them preserve basic capacities for perception, thinking, discernment, and logical reasoning — rather than letting them grow up accustomed to receiving an "answer" of unknown origin, unknown accuracy, and unknown reasoning process — this may be the most important educational question of our time.

**Keep questioning. Keep your own independent reasoning and judgment. That is the best we can do right now.**
