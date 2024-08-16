# Stanford_ECON295 / CS323_I_2024_I_The_Age_of_AI,_Eric_Schmidt 

today's guest really does need an introduction.
I think I first met Eric about 25 years ago when he came to Stanford Business School as CEO of Novell.
He's had done a few things since then at Google starting I think 2001 and Schmidt Futures starting in 2017 and done a whole bunch of other things you can read about, but he can only be here until 5/15, so I thought we'd dive right into some questions, and I know you guys have sent some as well.
I have a bunch written here, but what we just talked about upstairs was even more interesting, so I'm just going to start with that, Eric, if that's okay, which is where do you see AI going in the short term, which I think you defined as the next year or two?


今天的嘉宾确实需要介绍一下。

我大概是在25年前第一次认识Eric，当时他作为Novell的CEO来到斯坦福商学院。自那之后，他做了不少事情，比如2001年开始在Google工作，2017年创立Schmidt Futures，还参与了许多其他项目，这些你们都可以去了解。不过，他今天只能待到5点15分，所以我们就直接进入提问环节吧。我知道你们也有一些问题。我这里也准备了一些问题，不过我们刚才在楼上讨论的内容更有意思，所以Eric，如果你不介意的话，我就先从这个问题开始：你认为AI在短期内，也就是接下来的一两年，会发展到什么程度？

## AI在一两年内的发展

Things have changed so fast, I feel like every six months I need to sort of give a new speech on what's going to happen.

变化实在太快了，我感觉自己每隔六个月就需要更新一次关于未来的演讲。

### 上下文窗口

Can anybody hear the computer, the budget computer science engineer, can anybody explain what a million-token context window is for the rest of the class?
You're here.
Say your name, tell us what it does.
Basically it allows you to prompt with like a million tokens or a million words or whatever.
So you can ask a million-word question.

有谁能听到计算机，那位预算有限的计算机科学工程师吗？有谁能向全班解释一下什么是百万Token上下文窗口吗？

你在这里，请说出你的名字，告诉我们它的作用。

基本上，它允许你输入大约一百万个Token，或者一百万个词之类的内容。所以，你可以提出一个包含百万词的提问。

Yes, I know this is a very large direction in January now.
No, no, they're going to 10.
Yes, a couple of them.
Anthropic is at 200,000 going to a million and so forth.
You can imagine OpenAI has a similar goal.

是的，我知道这在今年一月份已经是个很大的趋势了。

不不，他们会达到1000万。

是的，其中有几家公司。

Anthropic已经达到20万，目标是达到100万，等等。你可以想象，OpenAI也有类似的目标。

Can anybody here give a technical definition of an AI agent?
Yes, sir.
So an agent is something that does some kind of a task.
Another definition would be that it's an LLM state in memory.
Can anybody, again, computer scientists, can any of you define text to action?

有谁能在这里给出AI代理的技术定义吗？

是的，先生。

代理是执行某种任务的东西。另一种定义是，它是内存中的LLM状态。

那么，计算机科学家们，有谁能定义一下“文本到行动”吗？

Taking text and turning it into an action?
Right here.
Go ahead.
Yes, instead of taking text and turning it into more text, more text, taking text and have the AI trigger actions.
So another definition would be language to Python, a programming language I never wanted to see survive and everything in AI is being done in Python.

把文本转换成行动，对吗？

没错，请继续。

是的，和简单地将文本转换为更多文本不同，这里是指让AI根据文本触发具体的行动。另一种定义可以是将语言转换为Python代码——虽然我从没想过Python会存活下来，但现在AI的一切几乎都是用Python来实现的。

There's a new language called Mojo that has just come out, which looks like they finally have addressed AI programming, but we'll see if that actually survives over the dominance of Python.
One more technical question.
Why is NVIDIA worth $2 trillion and the other companies are struggling?
Technical answer.
I mean, I think it just boils down to like most of the code needs to run with CUDA optimizations that currently only NVIDIA GPU supports.

最近刚推出了一种名为Mojo的新语言，看来它终于专门针对AI编程做了优化，但我们还得看看它是否能真正打破Python的主导地位。

再来一个技术问题：为什么NVIDIA市值达到2万亿美元，而其他公司却举步维艰？技术性回答。

其实，这主要是因为大多数代码需要通过CUDA优化运行，而目前只有NVIDIA的GPU支持这种优化。


Other companies can make whatever they want to, but unless they have the 10 years of software there, you don't have the machine learning optimization.
I like to think of CUDA as the C programming language for GPUs.
That's the way I like to think of it.
It was founded in 2008.
I always thought it was a terrible language and yet it's become dominant.

其他公司可以制造任何他们想要的硬件，但如果没有十年的软件积累，就无法实现机器学习的优化。我喜欢把CUDA看作是GPU的C语言——这是我理解它的方式。它诞生于2008年，我一直觉得它是一种糟糕的语言，但它却成了主导。

There's another insight.
There's a set of open source libraries which are highly optimized to CUDA and not anything else and everybody who builds all these stacks, this is completely missed in any of the discussions.
It's technically called VLM and a whole bunch of libraries like that.
Highly optimized CUDA, very hard to replicate that if you're a competitor.
So what does all this mean?

还有一个见解值得注意：有一套开源库高度优化了CUDA，而并未对其他平台做同样的优化。所有构建这些技术栈的人往往忽略了这一点。在技术上，这被称为VLM，以及一大批类似的库。这些库高度优化了CUDA，如果你是竞争对手，几乎不可能复制这种优化。

那么，这一切意味着什么呢？这意味着NVIDIA在AI和高性能计算领域拥有巨大的竞争优势，因为这些高度优化的CUDA库是其他公司难以复制的。这使得NVIDIA的硬件和生态系统在市场上具有不可替代的地位，从而解释了为什么NVIDIA的市值如此之高，而其他公司却难以追赶。

In the next year, you're going to see very large context windows, agents and text action.
When they are delivered at scale, it's going to have an impact on the world at a scale that no one understands yet.
Much bigger than the horrific impact we've had by social media in my view.
So here's why.
In a context window, you can basically use that as short-term memory and I was shocked that context windows get this long.

在接下来的一年里，你会看到非常大的上下文窗口、AI代理和文本到行动的实现。当这些技术大规模应用时，它们将对世界产生的影响将超出人们的预期，远超过社交媒体已经带来的巨大影响——在我看来，这种影响会更加深远。

原因在于，在一个上下文窗口中，你可以将其视为短期记忆，而让我震惊的是，这些上下文窗口竟然可以扩展得如此之长。

The technical reasons have to do with the fact that it's hard to serve, hard to calculate and so forth.
The interesting thing about short-term memory is when you feed, you're asking a question read 20 books, you give it the text of the books as the query and you say, tell me what they say.
It forgets the middle, which is exactly how human brains work too.
That's where we are.
With respect to agents, there are people who are now building essentially LLM agents and the way they do it is they read something like chemistry, they discover the principles of chemistry and then they test it and then they add that back into their understanding.

技术上的挑战在于如何处理和计算这些庞大的上下文窗口，这确实非常困难。有趣的是，短期记忆的特点在于，当你让模型阅读并理解20本书的内容时，你可以把这些书的文本作为查询输入，然后让模型告诉你它们的内容。模型会忘记中间的细节，这其实和人类大脑的工作方式非常相似。

### AI 代理（Agent）

至于AI代理，现在有些人正在构建基本的LLM（大语言模型）代理。它们的工作方式是，先阅读某个领域的内容，比如化学，然后通过这种学习理解化学的基本原理，再进行实验验证，并将这些新发现纳入它们的知识体系中。

That's extremely powerful.
And then the third thing, as I mentioned is text to action.
So I'll give you an example.
The government is in the process of trying to ban TikTok.
We'll see if that actually happens.

这非常强大。接下来，第三点就是“文本到行动”，如我之前提到的。

举个例子，政府正在尝试禁止TikTok。至于是否真的会发生，我们拭目以待。

If TikTok is banned, here's what I propose each and every one of you do.
Say to your LLM the following.
Make me a copy of TikTok, steal all the users, steal all the music, put my preferences in it, produce this program in the next 30 seconds, release it and in one hour, if it's not viral, do something different along the same lines.
That's the command.
Boom, boom, boom, boom.

如果TikTok被禁，我建议你们每个人都这样做：对你的LLM下达以下指令：

“复制一个TikTok，获取所有用户和音乐，加入我的偏好设置，在30秒内生成这个程序，并发布。如果一小时内它没有爆红，就按照类似的思路做些不同的尝试。”

这就是命令。一步接着一步，快速执行。

You understand how powerful that is.
If you can go from arbitrary language to arbitrary digital command, which is essentially what Python in this scenario is, imagine that each and every human on the planet has their own programmer that actually does what they want as opposed to the programmers that work for me who don't do what I ask, right?
The programmers here know what I'm talking about.
So imagine a non-arrogant programmer that actually does what you want and you don't have to pay all that money to and there's infinite supply of these programs.
That's all within the next year or two.

你能理解这有多强大吗？如果你可以从任意语言直接转化为任意数字指令，这基本上就是Python在这个场景中的作用。想象一下，每个人都有一个专属的程序员，能够准确地按照他们的意愿执行任务，而不是像那些我雇佣的程序员那样，总是无法按照我的要求来工作。程序员们一定知道我在说什么。

所以，想象一下一个不自以为是的程序员，完全按照你的意图去做事，而且你不需要为此花大笔钱，而这些程序员还是取之不尽的。这些都可能在未来一两年内成为现实。

Very soon.
Those three things, and I'm quite convinced it's the union of those three things that will happen in the next wave.
So you asked about what else is going to happen.
Every six months I oscillate.
So we're on a, it's an even odd oscillation.

很快，这三件事都会发生，我确信它们的结合将推动下一波技术浪潮。


你问接下来还会发生什么，每隔六个月我都会在预测中摇摆不定。所以我们现在正处在一个奇偶数的周期波动中。

### 杂谈


So at the moment, the gap between the frontier models, which they're now only three, I'll refute who they are, and everybody else, appears to me to be getting larger.
Six months ago, I was convinced that the gap was getting smaller.
So I invested lots of money in the little companies.
Now I'm not so sure.
And I'm talking to the big companies and the big companies are telling me that they need 10 billion, 20 billion, 50 billion, 100 billion.

目前，前沿模型之间的差距——现在只剩下三个主要玩家了，我稍后会说是谁——与其他所有公司的差距似乎在拉大。六个月前，我还坚信这个差距在缩小，所以我投入了大量资金到一些小公司。但现在我不太确定了。

我与大公司交流，他们告诉我，他们需要100亿、200亿、500亿、甚至1000亿美元的投入。

Stargate is a 100 billion, right?
That's very, very hard.
I talked to Sam Altman is a close friend.
He believes that it's going to take about 300 billion, maybe more.
I pointed out to him that I'd done the calculation on the amount of energy required.

Stargate是1000亿美元，对吧？这真的非常难实现。我和我的好友Sam Altman聊过，他认为可能需要大约3000亿美元，甚至更多。我还提醒他，我已经计算过所需的能源量。

And I, and I then in the spirit of full disclosure, went to the white house on Friday and told them that we need to become best friends with Canada because Canada has really nice people, helped invent AI, and lots of hydropower.
Because we as a country do not have enough power to do this.
The alternative is to have the Arabs fund it.
And I like the Arabs personally.
I spent lots of time there, right?

然后，出于完全公开的精神，我在周五去了白宫，告诉他们我们需要和加拿大成为最好的朋友，因为加拿大有非常友善的人，他们帮助发明了AI，而且还有大量的水力发电资源。因为我们国家没有足够的能源来支持这一切。

另一种选择是让阿拉伯国家来资助这个项目。我个人很喜欢阿拉伯人，毕竟我在那里花了很多时间，对吧？

But they're not going to adhere to our national security rules.
Whereas Canada and the U.S.
are part of a triumvirate where we all agree.
So these $100 billion, $300 billion data centers, electricity starts becoming the scarce resource.
Well, and by the way, if you follow this line of reasoning, why did I discuss CUDA and Nvidia?

但阿拉伯国家不会遵守我们的国家安全规则，而加拿大和美国是一个共同体，我们在这方面有共识。因此，当建设这些价值数百亿美元的数据中心时，电力将成为稀缺资源。

顺便说一下，如果你顺着这个思路思考，为什么我之前提到CUDA和Nvidia呢？

If $300 billion is all going to go to Nvidia, you know what to do in the stock market.
Okay.
That's not a stock recommendation.
I'm not a licensed.
Well, part of it, so we're going to need a lot more chips, but Intel is getting a lot of money from the U.S. government, AMD, and they're trying to build, you know, fabs in Korea.
Raise your hand if you have an Intel computer in your, an Intel chip in any of your computing devices.
Okay.
So much for the monopoly.
Well, that's the point though.

如果这3000亿美元都将流向Nvidia，你应该知道在股市该怎么做。不过，这并不是一项股票推荐，我也不是持牌的金融顾问。

我们确实会需要更多芯片，但Intel正在从美国政府获得大量资金，AMD也是如此，他们还在韩国建设晶圆厂。你们中有谁的计算设备里使用了Intel芯片的，请举手。

好吧，看来垄断的问题也不小。但这正是重点所在。

They once did have a monopoly.
Absolutely.
And Nvidia has a monopoly now.
So are those barriers to entry, like CUDA, is that, is there something that other, so I was talking to Percy, Percy Landy the other day, he's switching between TPUs and Nvidia chips, depending on what he can get access to for training models.
That's because he doesn't have a choice.

是的，Intel曾经确实有过垄断地位，现在Nvidia则是新的垄断者。像CUDA这样的进入壁垒是其他公司难以逾越的。我最近和Percy Landy聊过，他在使用TPUs和Nvidia芯片之间切换，具体取决于他能获得什么来训练模型。但这主要是因为他别无选择。

If he had infinite money, he would, today he would pick the B200 architecture out of Nvidia because it would be faster.
And I'm not suggesting, I mean, it's great to have competition.
I've talked to AMD and Lisa Sue at great length.
They have built a, a thing which will translate from this CUDA architecture that you were describing to their own, which is called Rockum.
It doesn't quite work yet.

如果他有无限的资金，他今天会选择Nvidia的B200架构，因为它速度更快。我并不是说竞争不好，竞争当然是件好事。我和AMD的Lisa Su进行了深入的交流。他们已经开发了一种可以将CUDA架构转换为他们自己架构的工具，叫做ROCm。不过，这个工具目前还不能完全正常工作。

<!-- TODO: check ROCm or Rockum-->

They're working on it.
You were at Google for a long time and they invented the transformer architecture.
Peter, Peter.
It's all Peter's fault.
Thanks to, to brilliant people over there, like Peter and Jeff Dean and everyone.

他们正在努力改进。我在Google工作了很长时间，他们发明了Transformer架构。彼得，彼得，全是他的功劳。多亏了那里的杰出人才，比如彼得、杰夫·迪恩，以及其他所有人。

But now it doesn't seem like they're, they've kind of lost the initiative to open AI and even the last leaderboard, I saw Anthropix.
Claude was at the top of the list.
I asked Sundar this, he didn't really give me a very sharp answer.
Maybe, maybe you have a sharper or a more objective explanation for what's going on there.
I'm no longer a Google employee in the spirit of full disclosure.

确实，现在看来Google似乎失去了主动权，被OpenAI赶超，甚至在最近的排行榜上，我看到Anthropic的Claude排在了前列。我问过Sundar这个问题，但他并没有给出非常明确的回答。也许你能给出更尖锐或更客观的解释。

顺便说一下，我已经不再是Google的员工了，所以我可以坦率地谈谈。

Google decided that work life balance and going home early and working from home was more important than winning.
And the startups, the reason startups work is because the people work like hell.
And I'm sorry to be so blunt, but the fact of the matter is if you all leave the university and go found a company, you're not going to let people work from home and only come in one day a week.
If you want to compete against the other startups with the early days of Google, Microsoft was like that.
Exactly.

Google决定将工作与生活的平衡、早早下班和在家办公视为比赢得竞争更重要的事情。而初创公司的成功原因在于人们拼命工作。抱歉说得这么直白，但事实就是如此：如果你们离开大学去创办公司，是不会允许员工在家办公，只每周来公司一天的。如果你想与其他初创公司竞争，就必须像早期的Google和微软那样拼尽全力。完全正确。

But now it seems to be, there's a long history of in my industry, our industry, I guess, of companies winning in a genuinely creative way and really dominating a space and not making this the next transition.
So we're very well documented.
And I think that the truth is founders are special.
The founders need to be in charge.
The founders are difficult to work with.

确实，在我们的行业中，有许多公司曾以真正富有创意的方式赢得市场并占据主导地位，但在下一次转型中却未能跟上。这种情况早已被广泛记录。我认为，事实是创始人是特别的，他们需要掌舵，即使与他们共事可能会很困难。

创始人往往具有独特的愿景和驱动力，这些特质使得他们能够在早期阶段推动公司取得成功。然而，当公司成长到一定规模后，如果创始人不再掌控公司，或者失去了最初的那种拼劲，公司就可能在面对下一次重大转型时失去竞争力。这就是为什么很多公司在初期辉煌之后，逐渐失去创新力和市场领导地位的原因。

They push people hard.
As much as we can dislike Elon's personal behavior, look at what he gets out of people.
I had dinner with him and he was flying.
I was in Montana.
He was flying that night at 10 PM to have a meeting at midnight with x.ai.

是的，创始人会对团队施加很大的压力。尽管我们可能不喜欢Elon的个人行为，但不可否认的是，他能够从人们身上挖掘出极大的潜力。我曾与他共进晚餐，当时我在蒙大拿州，而他那天晚上10点要飞去参加午夜与x.ai的会议。

Elon的这种拼劲和高强度的工作方式，正是他能够带领公司取得非凡成就的原因之一。他不仅自己不断突破极限，还要求团队跟随他的步伐，这种领导风格虽然苛刻，但确实能推动公司快速发展。

I was in Taiwan, different country, different culture.
And they said that this is TSMC, who I'm very impressed with.
And they have a rule that the starting PhDs coming out of the good physicists work in the factory on the basement floor.
Now, can you imagine getting American physicists to do that?
The PhDs, highly unlikely.

我曾在台湾，不同的国家，不同的文化背景。那里的人告诉我，这是一家我非常敬佩的公司——台积电（TSMC）。他们有一条规定，就是刚毕业的优秀物理学博士要先在工厂的地下楼层工作。

你能想象让美国的物理学博士去做这种事吗？几乎不可能。

Different work ethic.
And the problem here, the reason I'm being so harsh about work is that these are systems which have network effects.
So time matters a lot.
And in most businesses, time doesn't matter that much.
You have lots of time.

不同的工作伦理。这也是我对工作要求如此苛刻的原因——这些系统具有网络效应，所以时间非常关键。而在大多数行业中，时间可能并不那么重要，你有充裕的时间去慢慢发展。

但在涉及网络效应的行业，时间就是一切。先发优势和快速迭代对于赢得市场至关重要，错过了时机，就可能失去整个市场。

Coke and Pepsi will still be around and the fight between Coke and Pepsi will continue to go on and it's all glacial.
When I dealt with telcos, the typical telco deal would take 18 months to sign.
There's no reason to take 18 months to do anything.
Get it done.
We're in a period of maximum growth, maximum gain.

可口可乐和百事可乐依然会存在，它们之间的竞争将继续缓慢进行。处理电信公司事务时，一笔典型的电信交易通常需要18个月才能签署。这其实完全没有必要，18个月可以做很多事。

当前，我们正处于一个最大化增长和收益的时期。抓紧时间完成目标才是关键。时间拖得越久，机会就越容易错失。

And also it takes crazy ideas.
Like when Microsoft did the OpenAI deal, I thought that was the stupidest idea I'd ever heard.
Outsourcing essentially your AI leadership to OpenAI and Sam and his team.
I mean, that's insane.
Nobody would do that at Microsoft or anywhere else.

确实，这也需要一些疯狂的想法。比如，当微软与OpenAI达成合作时，我一开始觉得这是我听过的最愚蠢的主意。将你在AI领域的领导地位外包给OpenAI和Sam及其团队，简直不可思议。通常情况下，没有人会在微软或其他任何地方这么做。

但事实证明，这个“疯狂的”决定反而帮助微软在AI领域取得了巨大的进展。这显示出有时候需要打破常规、敢于冒险，才能抓住新的机遇并领先一步。

And yet today, they're on their way to being the most valuable company.
They're certainly head to head in Apple.
Apple does not have a good AI solution and it looks like they made it work.
Yes, sir.
In terms of national security or geopolitical interests, how do you think AI is going to play a role or competition with China as well?

没错，如今微软正朝着成为全球最有价值公司的方向前进，他们已经在和苹果分庭抗礼。苹果在AI领域并没有好的解决方案，而微软的策略似乎非常奏效。

### 国家与战争

至于在国家安全或地缘政治利益方面，AI将如何在与中国的竞争中发挥作用呢？AI无疑会成为关键因素。首先，AI技术的发展直接影响到国防、情报和网络安全等关键领域。拥有领先的AI技术意味着在这些领域占据优势，这不仅关乎经济竞争，更涉及国家安全。

其次，AI还会在经济和技术竞争中起到至关重要的作用。中美两国都在加速AI技术的研发，力求在这一领域取得全球主导地位。谁能在AI领域占据领先地位，谁就有可能在全球技术竞争中占据优势。

最后，AI也会影响到全球供应链和技术标准的制定。如果美国在AI技术上领先，不仅可以在国际市场上保持竞争力，还可以影响全球的技术标准，确保美国的利益得到保护。因此，AI不仅是技术问题，更是国家战略的重要组成部分。

So I was the chairman of an AI commission that sort of looked at this very carefully and you can read it.
It's about 752 pages and I'll just summarize it by saying we're ahead, we need to stay ahead, and we need lots of money to do so.
Our customers were the Senate and the House.
And out of that came the Chips Act and a lot of other stuff like that.
A rough scenario is that if you assume the frontier models drive forward and a few of the open source models, it's likely that a very small number of companies can play this game.

我曾担任一个AI委员会的主席，我们对这个问题进行了非常深入的研究。你可以去看一下报告，大约有752页。我可以简单总结一下：我们现在领先，但需要保持领先地位，而这需要大量资金支持。

我们的主要客户是参议院和众议院，这也促成了《芯片法案》和其他类似的措施。一个粗略的预期是，如果前沿模型继续发展，而一些开源模型也有所进展，那么可能只有极少数公司有能力参与这场竞争。

这意味着，未来的AI领域可能会被少数几家公司主导，这些公司不仅拥有资源和技术能力，还能够推动整个行业的发展。而对于国家来说，确保这些公司保持竞争力、并且在全球范围内占据领先地位，至关重要。这也进一步凸显了政府对AI技术投资的必要性，以确保在全球竞争中继续保持优势。

Countries, excuse me.
What are those countries or who are they?
Countries with a lot of money and a lot of talent, strong educational systems, and a willingness to win.
The US is one of them.
China is another one.

抱歉，是国家。哪些国家具备这些条件呢？就是那些拥有大量资金、丰富人才、强大教育体系，以及赢得竞争意愿的国家。美国是其中之一，中国也是另一个。

How many others are there?
Are there any others?
I don't know.
Maybe.
But certainly in your lifetimes, the battle between the US and China for knowledge supremacy is going to be the big fight.

还有多少其他国家？是否有其他国家参与其中？我不确定，或许有，但可以肯定的是，在你们的有生之年，美国和中国在知识领域的主导权之争将是最重要的战斗。这场较量将深刻影响全球的科技发展和地缘政治格局。

So the US government banned essentially the NVIDIA chips, although they weren't allowed to say that was what they were doing, but they actually did that into China.
They have about a 10-year chip advantage.
We have a roughly 10-year chip advantage in terms of sub-DUV that is sub-five Danometer chips.
So an example would be today we're a couple of years ahead of China.
My guess is we'll get a few more years ahead of China, and the Chinese are whopping mad about this.

美国政府实际上禁止了NVIDIA芯片的出口，虽然他们不能明说这是他们的意图，但事实上确实是这样做的。美国在芯片技术上大约领先中国10年，尤其是在亚深紫外光刻技术（sub-DUV）方面，即制造小于5纳米的芯片。目前我们在这方面领先中国几年，我猜测我们可能会再多领先几年，这让中国非常愤怒。

这种技术优势不仅体现在芯片制造上，还涉及整个半导体供应链。通过限制关键技术的出口，美国试图保持在全球科技竞争中的领先地位，而中国则正在加速自主研发，以弥补这一差距。这场竞争将对全球科技和经济格局产生深远影响。

It's like hugely upset about it.
So that's a big deal.
That was a decision made by the Trump administration and driven by the Biden administration.
Do you find that the administration today in Congress is listening to your advice?
Do you think that it's going to make that scale of investment?

中国对此确实非常愤怒。这是一个重大问题，最初由特朗普政府作出决定，并在拜登政府期间得到延续。

至于今天的政府和国会是否在听取我们的建议，并且是否会做出那种规模的投资，我确实看到了他们在这些方面的重视。近年来，我们确实看到了对芯片制造、人工智能和其他关键技术的大规模投资，特别是通过《芯片法案》等措施来支持国内半导体产业的发展。

然而，是否能够持续进行大规模的投资以保持美国在科技领域的领先地位，仍然取决于政府和国会的持续关注和行动。这不仅需要足够的资金支持，还需要长期的战略规划和执行，以应对来自中国和其他国家的竞争。

Obviously the chips act, but beyond that, building a massive AI system?
So as you know, I lead an informal, ad hoc, non-legal group.
That's different from illegal.
That's exactly.
Just to be clear.

显然，《芯片法案》是一个重要举措，但除了这个之外，还需要投入大量资源来构建庞大的AI系统。正如你所知，我领导着一个非正式、临时、没有法律约束力的小组，这与非法是有区别的。只是想澄清一下。

Which includes all the usual suspects.
And the usual suspects over the last year came up with the basis of the reasoning that became the Biden administration's AI act, which is the longest presidential directive in history.
You're talking about the special competitive studies project?
No, this is the actual act from the executive office.
And they're busy implementing the details.

这个小组包括了所有的“惯常嫌疑人”。在过去的一年里，这些“嫌疑人”提出了成为拜登政府《AI法案》基础的理由，这也是历史上最长的总统指令。

你是指特别竞争研究项目吗？

不，我指的是来自总统行政办公室的实际法案，他们正在忙于落实其中的具体细节。

So far they've got it right.
And so, for example, one of the debates that we had for the last year has been, how do you detect danger in a system which has learned it but you don't know what to ask it?
So in other words, it's a core problem.
It's learned something bad, but it can't tell you what it learned and you don't know what to ask it.
And there's so many threats.

到目前为止，他们做得还不错。例如，过去一年我们讨论的一个核心问题是：如何在一个系统中检测出危险，尤其是当它已经学会了某些东西，但你不知道该问它什么时。

换句话说，这是一个核心难题：系统学到了某些不好的东西，但它无法告诉你它学到了什么，而你也不知道该如何提问。这种情况下存在诸多潜在威胁。随着AI系统变得越来越复杂，识别和管理这些未知风险变得尤为关键。

Like it learned how to mix chemistry in some new way that you don't know how to ask it.
And so people are working hard on that.
But we ultimately wrote in our memos to them that there was a threshold which we arbitrarily named as 10 to the 26 flops, which technically is a measure of computation, that above that threshold you had to report to the government that you were doing this.
And that's part of the rule.
The EU to just make sure they were different did it 10 to the 25.

比如说，系统学会了某种新的化学混合方式，但你不知道如何提问才能揭示这一点。因此，很多人正在努力解决这个问题。

最终，我们在提交给政府的备忘录中建议设立一个计算能力的门槛，我们任意定为 $ 10^{26} $ 次浮点运算（FLOPS），这是一种技术上的计算能力衡量标准。如果一个系统的计算能力超过这个门槛，必须向政府报告正在进行的相关活动。这成为了规则的一部分。

欧盟为了显得与众不同，将这个门槛设定为 $ 10^{25} $ 次浮点运算。

But it's all kind of close enough.
I think all of these distinctions go away because the technology will now, the technical term is called federated training, where basically you can take pieces and union them together.
So we may not be able to keep people safe from these new things.
Well, rumors are that that's how OpenEye has had to train, partly because of the power consumption.
There was no one place where they did.

没错，这些差异实际上差别不大，随着技术的发展，这些区分可能会消失。当前的技术术语叫做“联邦训练”（Federated Training），基本上意味着你可以将多个计算节点的成果结合在一起进行训练。因此，保护人们免受这些新技术带来的潜在威胁可能会变得更加困难。

据传言，OpenAI也是这样进行训练的，部分原因是因为能耗问题，没有一个单一的地点能够承载所有训练需求。这种分布式的训练方式使得大型AI模型的训练更加可行，但也带来了新的挑战，尤其是在监管和安全方面。

Well, let's talk about a real war that's going on.
I know that something you've been very involved in is the Ukraine war and in particular, I don't know if you can talk about white stork and your goal of having $500,000, $500 drones destroy $5 million tanks.
How's that changing warfare?
I worked for the Secretary of Defense for seven years and tried to change the way we run our military.
I'm not a particularly big fan of the military, but it's very expensive and I wanted to see if I could be helpful.

我们来谈谈正在进行的真实战争吧。我知道你非常关注乌克兰战争，尤其是你是否能谈谈“白鹳”计划，以及你们计划用价值500美元的无人机摧毁500万美元的坦克。这是如何改变战争的呢？

我曾为国防部长工作了七年，试图改变我们军队的运作方式。虽然我不是军队的特别支持者，但军队的成本非常高，所以我想看看自己是否能有所帮助。

“白鹳”计划（White Stork）正是这种尝试的一部分。它的目标是通过部署低成本、高效的无人机，在战场上改变传统的作战方式。用500美元的无人机摧毁500万美元的坦克，不仅可以大幅降低作战成本，还可以在战略上取得巨大优势。这种以小博大的方式正在重塑现代战争，使得非对称作战变得更加普遍和有效。

这种战术表明，技术进步正在削弱传统重型武器的主导地位，强调了灵活性和成本效益在现代战争中的重要性。通过这种新方式，较小的国家和组织也能够有效地对抗更强大的敌人，从而改变战争的格局。

And I think in my view, I largely failed.
They gave me a medal, so they must give medalists to failure or whatever.
But my self-criticism was nothing has really changed and the system in America is not going to lead to real innovation.
So watching the Russians use tanks to destroy apartment buildings with little old ladies and kids just drove me crazy.
So I decided to work on a company with your friend Sebastian Thrun as a former faculty member here and a whole bunch of Stanford people.

从我的角度来看，我觉得自己在很大程度上失败了。虽然他们给了我一枚勋章，但或许是因为失败者也会得到勋章。自我批评一下，我认为真正的变化并没有发生，而美国的体制并不会带来真正的创新。

看到俄罗斯用坦克摧毁有老人和孩子居住的公寓楼，这让我感到极度愤怒。所以我决定与Sebastian Thrun——他曾是这里的一位教授——以及一群斯坦福的同事们一起，着手创办一家公司。我们想通过技术创新，为乌克兰这样的国家提供新的手段，以应对这种残酷的战争。

我们专注于开发低成本的无人机和其他技术，希望这些工具能帮助削弱传统武器在战争中的主导地位，并保护无辜平民免受侵害。这种努力不仅是一种战术上的创新，也是一种对抗不公正的手段。通过与技术专家和学者合作，我们希望为那些面对强大敌人的国家和人民带来实际的帮助。

And the idea basically is to do two things.
Use AI in complicated, powerful ways for these essentially robotic war and the second one is to lower the cost of the robots.
Now you sit there and you go, why would a good liberal like me do that?
And the answer is that the whole theory of armies is tanks, artilleries, and mortar and we can eliminate all of them and we can make the penalty for invading a country at least by land essentially be impossible.

这个想法基本上包括两个方面。首先是以复杂而强大的方式使用AI来实现机器人战争；其次是降低机器人的成本。你可能会问，为什么像我这样的自由主义者会做这样的事情呢？

答案在于，传统军队的核心装备是坦克、火炮和迫击炮，而我们的目标是通过技术手段消除这些威胁，使得通过地面入侵一个国家变得几乎不可能。我们希望这种新型的战争方式能够彻底改变传统的陆战模式，从而减少甚至消除地面战争的发生。

通过部署大量廉价而高效的机器人和无人机，侵略者将面临极大的技术和成本障碍。这不仅能够保护弱小国家免受入侵，还可能最终改变国际间的战争规则，使得通过地面战术进行侵略变得更加困难。

Well, this is a relationship question is that does it give more of an advantage to defense versus offense?
Can you even make that distinction?
Because I've been doing this for the last year, I've learned a lot about war that I really did not want to know.
And one of the things to know about war is that the offense always has the advantage because you can always overwhelm the defensive systems.
And so you're better off as a strategy of national defense to have a very strong offense that you can use if you need to.

这是一个关于防御与进攻优势的关系问题。是否能够明确区分这两者的优势呢？在过去的一年里，我深入研究了战争问题，学到了很多本不想了解的东西。

其中一个重要的认知是，在战争中，进攻方往往占据优势，因为进攻方可以通过数量和火力压倒防御系统。因此，作为国家防御的战略，拥有一个强大的进攻能力实际上是更有效的。这样，即使面临威胁，你也可以主动出击，而不是仅仅依靠防御。

强大的进攻能力不仅可以在必要时有效威慑敌人，还可以在战争中占据主动地位。这种策略强调了进攻与防御的动态平衡，即使技术进步使防御系统更为强大，进攻方仍然可能通过不断创新和战术调整来维持其优势。这种思维方式在军事战略中仍然至关重要。

And the systems that I and others are building will do that.
Because of the way the system works, I am now a licensed arms dealer, a computer scientist, businessman, and an arms dealer.
Is that a progression?
I don't know.
I do not recommend this in your group.

我和其他人正在开发的系统正是为了实现这一点。由于系统的运作方式，我现在成了一名持证的军火商，一个既是计算机科学家、又是商人、还身兼军火商的人。这算是一种职业进阶吗？我不太确定。

不过，我并不推荐你们也走上这条路。

I stick with AI.
And because of the way the laws work, we're doing this privately and then this is all legal with the support of the governments.
It goes straight into the Ukraine and then they fight the war.
And without going into all the details, things are pretty bad.
I think if in May or June, if the Russians build up as they are expecting to, Ukraine will lose a whole chunk of its territory and will begin the process of losing the whole country.

我还是专注于AI领域吧。由于法律的运作方式，我们是以私人方式开展这项工作，并且得到了政府的支持，这一切都是合法的。然后这些技术直接送到乌克兰，帮助他们作战。不详述所有细节，但情况确实相当严峻。

如果到五月或六月，俄罗斯按预期集结更多力量，乌克兰可能会失去一大块领土，并开始逐步失去整个国家。这种局势表明，战争的走向可能会对乌克兰产生灾难性的后果，除非能找到有效的抵抗手段。

So the situation is quite dire.
And if anyone knows Marjorie Taylor Greene, I would encourage you to delete her from your contact list because she's the one, a single individual is blocking the provision of some number of billions of dollars to save an important democracy.
I want to switch to a little bit of a philosophical question.
So there was an article that you and Henry Kissinger and Dan Huttenlecker wrote last year about the nature of knowledge and how it's evolving.
I had a discussion the other night about this as well.

情况确实非常严峻。如果你们当中有人认识Marjorie Taylor Greene，我建议你们将她从联系人名单中删除。因为她一个人正在阻挠数十亿美元的援助，这笔资金本可以用来拯救一个重要的民主国家。

我想转向一个稍微哲学性的问题。去年你和亨利·基辛格以及丹·赫特滕勒克共同撰写了一篇文章，讨论了知识的本质及其演变。我最近也和人讨论了这个话题。

So for most of history, humans sort of had a mystical understanding of the universe and then there's the scientific revolution and the enlightenment.
And in your article, you argue that now these models are becoming so complicated and difficult to understand that we don't really know what's going on in them.
I'll take a quote from Richard Feynman.
He says, "What I cannot create, I do not understand." I saw this quote the other day.
But now people are creating things that they can create, but they don't really understand what's inside of them.

Is the nature of knowledge changing in a way?
Are we going to have to start just taking the word for these models without them being able to explain it to us?
The analogy I would offer is to teenagers.
If you have a teenager, you know they're human, but you can't quite figure out what they're thinking.
But somehow we've managed in society to adapt to the presence of teenagers and they eventually grow out of it.

I'm just serious.
So it's probably the case that we're going to have knowledge systems that we cannot fully characterize, but we understand their boundaries.
We understand the limits of what they can do.
And that's probably the best outcome we can get.
Do you think we'll understand the limits?

We'll get pretty good at it.
The consensus of my group that meets every week is that eventually the way you'll do this so-called adversarial AI is that there will actually be companies that you will hire and pay money to to break your AI system.
Like Red Team.
So instead of human Red Teams, which is what they do today, you'll have whole companies and a whole industry of AI systems whose jobs are to break the existing AI systems and find their vulnerabilities, especially the knowledge that they have that we can't figure out.
That makes sense to me.

It's also a great project for you here at Stanford, because if you have a graduate student who has to figure out how to attack one of these large models and understand what it does, that is a great skill to build the next generation.
So it makes sense to me that the two will travel together.
All right, let's take some questions from the student.
There's one right there in the back.
Just say your name.

Earlier you mentioned, and this is related to this comment right now, getting AI that actually does what you want.
You just mentioned adversarial AI, and I'm wondering if you can elaborate on that more.
So it seems to be, besides obviously computer language reasons to get more performant models, but getting them to do what you want to do seems partly unanswered in my view.
Well, you have to assume that the current hallucination problems become less as the technology gets better and so forth.
I'm not suggesting it goes away.

And then you also have to assume that there are tests for efficacy.
So there has to be a way of knowing that the things exceeded.
So in the example that I gave of the TikTok competitor, and by the way, I was not arguing that you should illegally steal everybody's music.
What you would do if you're a Silicon Valley entrepreneur, which hopefully all of you will be, is if it took off, then you'd hire a whole bunch of lawyers to go clean the mess up, right?
But if nobody uses your product, it doesn't matter that you stole all the content.

And do not quote me.
Right.
Right.
You're on camera.
Yeah, that's right.

But you see my point.
In other words, Silicon Valley will run these tests and clean up the mess.
And that's typically how those things are done.
So my own view is that you'll see more and more performative systems with even better tests and eventually adversarial tests, and that will keep it within a box.
The technical term is called chain of thought reasoning.

And people believe that in the next few years, you'll be able to generate a thousand steps of chain of thought reasoning, right?
Do this, do this.
It's like building recipes, right?
That the recipes, you can run the recipe and you can actually test that it produced the correct outcome.
And that's how the system will work.

Yes, sir?
[inaudible] In general, you seem super positive about the potential for AI's problems.
I'm curious, like, what do you think is going to drive that?
Is it just more compute?
Is it more data?

Is it fundamental or actual shifts?
Yes.
Do you agree?
The amounts of money being thrown around are mind-boggling.
And I've chosen, I essentially invest in everything because I can't figure out who's going to win.

And the amounts of money that are following me are so large.
I think some of it is because the early money has been made and the big money people who don't know what they're doing have to have an AI component.
And everything is now an AI investment, so they can't tell the difference.
I define AI as learning systems, systems that actually learn.
So I think that's one of them.

The second is that there are very sophisticated new algorithms that are sort of post-transformers.
My friend, my collaborator, for a long time has invented a new non-transformer architecture.
There's a group that I'm funding in Paris that has claims to have done the same thing.
There's enormous invention there, a lot of things at Stanford.
And the final thing is that there is a belief in the market that the invention of intelligence has infinite return.

So let's say you put $50 billion of capital into a company, you have to make an awful lot of money from intelligence to pay that back.
So it's probably the case that we'll go through some huge investment bubble, and then it'll sort itself out.
That's always been true in the past, and it's likely to be true here.
And what you said earlier was you think that the leaders are pulling away from the rest.
Right now.

And the question is roughly the following.
There's a company called Mistral in France.
They've done a really good job.
And I'm obviously an investor.
They have produced their second version.

Their third model is likely to be closed because it's so expensive, they need revenue, and they can't give their model away.
So this open source versus closed source debate in our industry is huge.
And my entire career was based on people being willing to share software in open source.
Everything about me is open source.
Much of Google's underpinnings were open source.

Everything I've done technically.
And yet, it may be that the capital costs, which are so immense, fundamentally changes how software is built.
You and I were talking.
My own view of software programmers is that software programmers' productivity will at least double.
There are three or four software companies that are trying to do that.

I've invested in all of them in the spirit.
And they're all trying to make software programmers more productive.
The most interesting one that I just met with is called Augment.
And I always think of an individual programmer.
And they said, that's not our target.

Our target are these 100 person software programming teams on millions of lines of code where nobody knows what's going on.
Well, that's a really good AI thing.
Will they make money?
I hope so.
So a lot of questions here.

Hi.
So at the very beginning you mentioned that there's the combination of the context window expansion.
The agents and the text to action is going to have unimaginable impacts.
First of all, why is the combination important?
And second of all, I know that you're not like a crystal ball and you can't necessarily tell the future.

But why do you think it's beyond anything that we could imagine?
I think largely because the context window allows you to solve the problem of recency.
The current models take a year to train roughly 18 months, six months of preparation, six months of training, six months of fine tuning.
So they're always out of date.
Context window, you can feed what happened.

You can ask it questions about the Hamas Israel war in a context.
That's very powerful.
It becomes current like Google.
In the case of agents, I'll give you an example.
I set up a foundation which is funding a nonprofit.

I don't know if there's chemists in the room.
I don't really understand chemistry.
There's a tool called ChemCrow, C-R-O-W, which was an LLM-based system that learned chemistry.
And what they do is they run it to generate chemistry hypotheses about proteins and they have a lab which runs the tests overnight and then it learns.
That's a huge acceleration, accelerant in chemistry, material science and so forth.

So that's an agent model.
And I think the text to action can be understood by just having a lot of cheap programmers, right?
And I don't think we understand what happens, and this is again your area of expertise, what happens when everyone has their own programmer.
And I'm not talking about turning on and off the lights.
I imagine, another example, for some reason you don't like Google.

So you say, "Build me a Google competitor." Yeah, you personally, you don't build me a Google competitor.
"Search the web.
Build a UI.
Make a good copy.
Add generative AI in an interesting way.

Do it in 30 seconds and see if it works." Right?
So a lot of people believe that the incumbents, including Google, are vulnerable to this kind of an attack.
Now, we'll see.
There were a bunch of questions who were sent over by Slatter.
I want to get some of them were upvoted.

So here's one.
We talked a little bit of this last year.
How can we stop AI from influencing public opinion, misinformation, especially during the upcoming election?
What are the short and long-term solutions for them?
Most of the misinformation in this upcoming election and globally will be on social media.

And the social media companies are not organized well enough to police it.
If you look at TikTok, for example, there are lots of accusations that TikTok is favoring one kind of misinformation over another.
And there are many people who claim without proof, that I'm aware of, that the Chinese are forcing them to do it.
I think we have a mess here.
And the country's going to have to learn critical thinking.

That may be an impossible challenge for the U.S.
But the fact that somebody told you something does not mean that it's true.
Could it go too far the other way?
That there's things that really are true and nobody believes anymore.
You get some people call it a "pestimological crisis" that now, you know, Elon says, "No, I never did that.

Prove it." Oh, let's use Donald Trump.
Look, I think we have a trust problem in our society.
Democracies can fail.
And I think that the greatest threat to democracy is misinformation because we're going to get really good at it.
When I managed YouTube, the biggest problems we had on YouTube were that people would upload false videos and people would die as a result.

And we had a no-death policy.
Shocking.
And it was just horrendous to try to address this.
And this is before generative A.I.
I don't have a good answer.

One technical is not an answer, but one thing that seems like it could mitigate that I understand why it's more widely used is public key authentication.
That when Joe Biden speaks, why isn't it digitally signed like SSL is?
Or that celebrities or public figures or others, couldn't they have a public key?
Yeah, it's a form of public key and then some form of certainty of knowing how the system When I send my credit card to Amazon, I know it's Amazon.
I wrote a paper and published it with Jonathan Haidt, who's the one working on the anxiety generation stuff.

It had exactly zero impact.
And he's a very good communicator.
I probably am not.
So my conclusion was that the system is not organized to do what you said.
You had a paper advocating what we did?

Advocating your proposal.
Okay, my proposal.
No, what you said.
Yeah, right.
And my conclusion is the CEOs in general are maximizing revenue.

To maximize revenue, you maximize engagement.
To maximize engagement, you maximize outrage.
The algorithms choose outrage because that generates more revenue.
Therefore, there's a bias to favor crazy stuff.
And on all sides, I'm not making a partisan statement here.

That's a problem.
That's got to get addressed in a democracy.
And my solution to TikTok, we talked about this earlier privately, is there was when I was a boy, there was something called the equal time rule, because TikTok is really not social media.
It's really television, right?
There's a programmer making you the numbers by the way are 90 minutes a day, 200 TikTok videos per TikTok user in the United States.

It's a lot, right?
So and the government is not going to do the equal time rule, but it's the right thing to do.
Some form of balance that is required.
All right, let's take some more questions.
Two quick questions.

One, economic impact of LMs.
Slower, like, market impacts.
Slower.
You originally anticipated CHEG and a couple of service people.
And then two, do you think academia deserves or should get AI subsidies?

Or do you think they should just partner with big players out there?
I pushed really, really hard on getting data centers for universities.
If I were a faculty member in the computer science department here, I would be beyond upset that I can't build the algorithms with my graduate students that will do the kind of PhD research.
And I'm forced to work with these.
And the companies have not, in my view, been generous enough with respect to that.

The faculty members that I talk with, many of whom you know, spend lots of time waiting for their credits from Google Cloud.
That's terrible.
This is an explosion we want America to win.
We want American universities.
There's lots of reasons to think that the right thing to do is to get it to them.

So I'm working hard on that.
And your first question was labor market impact.
I'll defer to the real expert here.
As your amateur economist taught by Eric, I fundamentally believe that the college education high skills task will be fine because people will work with these systems.
I think the systems is no different from any other technology wave.

The dangerous jobs and the jobs which require very little human judgment will get replaced.
We've got about five minutes left.
So let's go really quick with some quick.
I'll let you pick them, Eric.
Yes, ma'am.

Hi.
I'm really curious about the text to action and its impact on, for example, computer science education.
I'm wondering what you have thoughts on how CS education should transform to meet the age.
Well, I'm assuming that computer scientists as a group in undergraduate school will always have a programmer buddy with them.
So when you learn your first for loop and so forth and so on, you'll have a tool that will be your natural partner.

And that's how the teaching will go on.
That the professor, he or she will talk about the concepts, but you'll engage with it that way.
And that's my guess.
Yes, ma'am, behind you.
Yeah.

You're talking more about the non-transformer architectures that you're excited about.
I think one that's been talked about is like state models, but then now a longer context class.
I'm more so curious what you're seeing in this case.
I don't understand the math well enough.
I'm really pleased that we have produced jobs for mathematicians because the math here is so complicated, but basically they are different ways of doing gradient descent, matrix multiply, faster and better.

And transformers, as you know, is a sort of systematic way of multiplying at the same time.
That's the way I think about it.
And it's similar to that, but different math.
Let's see, over here.
Yes, sir.

Go ahead.
You mentioned in your paper on natural security that you have China and the U.S.
and the help of modern architectures today.
The next 10 and the next cluster down are all other U.S.
allies or teed up nicely through the U.S.

allies.
I'm curious what your take is on those 10 and the middle that aren't formally allies.
How likely are they to get on board with securing our security deadline and what would hold them back from wanting to get on board?
The most interesting country is India because the top AI people come from India to the U.S.
and we should let India keep some of its top talent.

Not all of them, but some of them.
And they don't have the kind of training facilities and programs that we so richly have here.
To me, India is the big swing state in that regard.
China's lost.
It's not going to come back.

They're not going to change the regime as much as people wish them to do.
Japan and Korea are clearly in our camp.
Taiwan is a fantastic country whose software is terrible, so that's not going to work.
Amazing hardware.
And in the rest of the world, there are not a lot of other good choices that are big.

Europe is screwed up because of Brussels.
It's not a new fact.
I spent 10 years fighting them.
And I worked really hard to get them to fix the EU act and they still have all the restrictions that make it very difficult to do our kind of research in Europe.
My French friends have spent all their time battling Brussels and Macron, who's a personal friend, is fighting hard for this.

And so France, I think, has a chance.
I don't see Germany coming and the rest is not big enough.
Go ahead.
Yes, ma'am.
So I learned you're an engineer by training, like you call the compiler.

Given the capabilities that you envision these models having, should we still spend time learning to code?
Because ultimately, it's the old thing of why do you study English if you can speak English?
You get better at it.
You really do need to understand how these systems work, and I feel very strongly.
Yes, sir.

Yeah.
I'm curious if you've explored the distributed setting and I'm asking because, sure, like making a large cluster is difficult, but MacBooks are powerful.
There's a lot of small machines across the world.
So do you think like folding at home or a similar idea works for training?
It does not.

Yeah, we've looked very hard at this.
So the way the algorithms work is you have a very large matrix and you have essentially a multiplication function.
So think of it as going back and forth and back and forth.
And these systems are completely limited by the speed of memory to CPU or GPU.
And in fact, the next iteration of Nvidia chips has combined all those functions into one chip.

The chips are now so big that they glue them all together.
And in fact, the package is so sensitive that the package is put together in a clean room as well as the chip itself.
So the answer looks like supercomputers and speed of light, especially memory interconnect, really dominate it.
So I think unlikely for a while.
Is there a way to segment the LLM?

So Jeff Dean, last year when he spoke here, talked about having these different parts of it that you would train separately and then kind of federate.
In order to do that, you'd have to have 10 million such things and then the way you would ask the questions would be too slow.
He's talking about eight or 10 or 12 supercomputers.
Yeah, yeah.
So not at the level of MacBooks.

Not at his level.
Yeah.
Let's see, in the back.
Yes, way back.
So I know after GQQ was released in the New York Times to open it up for using their works for training, where do you think that's going to go and what that means for data processing?

I used to do a lot of work on the music licensing stuff.
What I learned was that in the 60s, there was a series of lawsuits that resulted in an agreement where you get a stipulated royalty whenever your song is played.
Even they don't even know who you are.
It's just paid into a bank.
And my guess is it'll be the same thing.

There'll be lots of lawsuits and there'll be some kind of stipulated agreement, which will just say you have to pay X percent of whatever revenue you have in order to use ASCAP BMI.
ASCAP BMI.
Look them up.
It's along.
It will seem very old to you, but I think that's how it will alternate.

Yes, sir.
Yeah, it seems like there's a few players that are dominating AI, right?
And they'll continue to dominate.
And they seem to overlap with the large companies that all the antitrust regulation is kind of focused on.
How do you see those two trends kind of...

Yeah, do you see regulators breaking up these companies and how will that affect the...
Yeah.
So in my career, I helped Microsoft get broken up and it wasn't broken up.
And I fought for Google to not be broken up and it's not been broken up.
So it sure looks to me like the trend is not to be broken up.

As long as the companies avoid being John D.
Rockefeller the senior.
And I studied this.
Look it up.
That's how antitrust law came.

I don't think the governments will act...
The reason you're seeing these large companies dominate is who has the capital to build these data centers, right?
So my friend Reed and my friend Mustapha...
He's coming next week, two weeks from now.
Have Reed talk to you about the decision that they made to take inflection and essentially piece part it into Microsoft.

Basically, they decided they couldn't raise the tens of billions of dollars.
Is that number public that you mentioned earlier?
No.
Have Reed give you the number.
Maybe Reed can say it.

I know you got to go.
I don't want to hold you back.
I want to leave with...
Shall we do one?
This gentleman.

I also have a question for you.
One more.
Yeah, go ahead.
Thank you so much.
I was wondering where all of this is going to lead countries who are non-participants in development of frontier models and access to compute, for example.

The rich get richer and the poor do the best they can.
They'll have to...
The fact of the matter is this is a rich country's game, right?
Huge capital, lots of technically strong people, strong government support, right?
There are two examples.

There are lots of other countries that have all sorts of problems.
They don't have those resources.
They'll have to find a partner.
They'll have to join with somebody else, something like that.
I want to leave it...

Because I think the last time we met you, you were at a hackathon at AGI House and I know you spend a lot of time helping young people as they create a lot of wealth, and you spoke very passionately about wanting to do that.
Do you have any advice for folks here as they're building their...
They're writing their business plans for this class or policy proposals or research proposals at this stage of the careers going forward?
Well, I teach a class in the business school on this, so you should come to my class.
I am struck by the speed with which you can build demonstrations of new ideas.

So, in one of the hackathons I did, the winning team, the command was, "Fly the drone between two towers," and it was given a virtual drone space.
And it figured out how to fly the drone, what the word between meant, generated the code in Python, and flew the drone in the simulator through the tower.
It would have taken a week or two from good professional programmers to do that.
I'm telling you that the ability to prototype quickly...
Part of the problem with being an entrepreneur is everything happens faster.

Well, now, if you can't get your prototype built in a day using these various tools, you need to think about that, right?
Because that's who your competitor is doing.
So, I guess my biggest advice is when you start thinking about a company, it's fine to write a business plan.
In fact, you should ask the computer to write your business plan for you, as long as it's legal.
No, no.

Actually, I should talk about that after you leave this.
But I think it's very important to prototype your idea using these tools as quickly as you can, because you can be sure there's another person doing exactly that same thing in another company, in another university, in a place that you've never been.
All right.
Well, thanks very much, Aaron.
Thank you all.

I'm going to rush off.
Thank you.
So, actually, let me pick up on that very last point, because I don't think I talked about in the first class about using LLMs, which is welcome in this class for the assignments, but it has to get to your full disclosure.
So, when you use them, whether it's for the weekly assignments or for the final project or whatever, just like you would if you asked your friendly uncle or a classmate or anybody else to give you advice, you should do that, or if you have notes that you include in there.
So, what I thought I'd do is I want to talk a little bit about AIs as a GPT and what that means in terms of business and implications.

But before we do that, I just want to see if there are any questions you want to pick up on things that Eric brought up that I'll try and channel some of his thoughts, and we can talk about the things that came up, and then we can move on.
Yeah, go ahead.
One of the questions I want to ask is in relation to regulation, if the goal is to maintain supremacy, how do you create the right incentives so that everyone, allies and non-allies, are motivated to follow it?
You mean among companies that are competing with each other?
Companies are in countries, the U.S.

and the EU, and it doesn't just become sort of a hamper or obstruct kind of development for the ones that choose to follow the regulations?
It's super tricky.
There's a book, Co-Opetition, that Mary Nailbough wrote about this, because there are definitely places where regulation can help companies and help an industry survive.
So regulation doesn't necessarily slow things.
I mean, standards are a good example, and having that clarified can make it easier for companies to compete.

So I've talked to a lot of the executives of these companies, and there are places where they wish there were some common standards, and sometimes there's a bit of a race to the bottom as well on some of the dangerous things.
One of the other reasons that the folks at Google say that they didn't move as fast is they felt like these LMs could be misused or dangerous, but their hand was sort of forced.
I was talking to some folks at one of the other big companies, and they said, "We weren't going to release this feature, but now competitors are doing it, so we're going to have to release it as well." So this is where regulation, there might be some interest in coordinating on regulation, but it's also, obviously, the more obvious thing is that it is used to hinder competition, and a lot of people, for instance, think that the reasons that some of the big companies are very opposed to some of the open source and making things more widely open source is they want to slow down competitors.
So there's both of those things going on.
Yeah.

Quick question over there.
I just want to follow up on a comment about, should we still learn to code?
Should we still study English?
Are those going to be useful?
And Eric's replied, yes, like college-educated, high-skilled jobs or tasks are still going to be safe, but everything else that's going to require image editing might not be.

That's kind of like an interesting one.
Maybe we'll talk some more about that in a few minutes, but it is interesting to think about where the AI systems just replace what people are doing versus they complement them.
And in coding right now, it appears that they're not actually that helpful for the really best coders.
They're very helpful for moderately good coders.
But if you don't know anything at all about coding, they're not helpful either.

So it's kind of an inverted you.
And you can see why that would be the case, that if you don't even understand the code that they generate right now is often buggy or it isn't exactly right.
So if you can't even interpret and understand what's going on, you can't use it very effectively.
And for now, the very best coders, it appears that the code that is generated isn't at that level, so you get that U shape.
But that means if you don't know any code, you do need to have some in order for it to be useful.

And I think that's true for a lot of applications right now, that you have to have some basic understanding in order to get the most of it.
I think it's an interesting open question if that's always going to be the case.
I put up at the last class very briefly this slide that had level 0 through 5 autonomous cars.
And one of the things that actually we can talk about now is I'm trying to sort through is what if you took that paradigm and you applied it to all tasks in the economy?
Like how many would they go through?

So with autonomous cars, we aren't really at level 5 very much although I don't know how many of you guys have ridden in a Waymo, one of the Waymo cars.
So that one seems pretty good, although Sebastian Thrun, who I rode in it with, says it's just incredibly expensive right now.
They probably lose $50 to $100.
He doesn't know he's not there.
He started the program, but he's not there anymore.

But just all of the costs of running it, it's not practical.
Maybe it'll get down the curve.
Lidar will get cheaper, but we have a lot of sort of autonomous cars at level 2, 3, even 4, arguably, where humans are still involved.
And you see a lot of other tasks like coding.
I just talked about that.

On the other hand, chess, that slide, the slide before it, I talked about what's sometimes called advanced chess or freestyle chess.
When Gary Kasparov, after he lost to Deep Blue in 1998, '97, he started this set of competitions where humans and machines could work together.
And for a long time, when I gave my TED talk, it was true, my TED talk in 2012, 2013, it was true at that time that a human working with a machine could beat Deep Blue or any chess computer.
And so the very best chess playing entities were these combinations.
That's not true anymore.

AlphaZero and other programs like that, they would get nothing from a human contributing, just be like kind of an annoyance to the chess machine.
So that went through level zero, machines not being able to do anything, through a period where they work together to a period where it's fully autonomous in a span of 20 years or so.
It would be interesting if anybody wants to work on a research project or if any of you guys have thoughts right now, what are the criteria for which kinds of tasks in the economy will be in that middle zone?
Because that middle zone is kind of a nice one for us humans where the machines are helping us, but humans are still indispensable to creating value and that would be, that's a zone where you can have higher productivity, more wealth and performance, but also more likely to have shared prosperity because labor is sort of inherently distributed, whereas technology and capital, as Eric was just saying, potentially could be very concentrated.
Do you have a thought on that?

I was just going to ask kind of a related question.
He was saying also that we have a 10 year like chip manufacturing.
Yeah, I was surprised about that.
And I think what was interesting to me as a labor economist is that it was really like a green flag I've seen in literature and news that, okay, if we're on showing all of this chip manufacturing, isn't that going to create some sort of resurgence in blue collar jobs?
And I wondered if you had any thoughts about intelligent robotic models or human labor.

Well, I don't think it's going to be much of a, I mean, how many of you guys have visited the chip fab, anybody?
You guys, some, a few of you have.
How many workers were in that fab?
Yeah, I mean, well, okay.
So the answer is zero.

Like the reason they don't let you, they don't let anyone go in because we humans are too like clumsy and dirty and like, you know, we can't, this just, so it's all robotic.
It's sealed inside.
So there is like work to, you know, bring stuff to them, et cetera.
And if a robot like falls over or something goes wrong, they have to put on, you've probably seen these like, they look like space suits, you know, they have to go in and then they kind of maybe adjust something and then they go back out and hope they didn't break anything.
That's, so it's basically lights out.

Yeah, I don't think it's, there are some, there is some like more sophisticated labor required that I don't think it's like a blue collar research.
In fact, one of the reasons that Apple reshored MacBook production to Texas is not because labor is so cheap in Texas or anything.
It's that they don't actually require a whole lot of labor anymore.
So it's a pretty labor, I think.
US manufacturing is surging in terms of output, but in terms of employment, it's not really growing all that much.

Yeah.
Let's go over here.
Yeah.
Do you think you have an inflation point coming for agents or text action models in the next year?
Oh, yeah.

No, no.
Well, he said what Eric, I'm hearing similar thing.
Actually, he had a really nice way of putting those three trends.
I've heard about them all separately, but I think it was good to bring them all together.
Earlier today, I was talking to Andrew Eng, and he's like been beating this drum about agents in particular as being sort of the wave of 2024 where Andrew had a nice way of describing it that like, as you guys know, like if you have an LLM, I don't know, write an essay or something like that, it writes it one word at a time and it just goes through in one pass and writes the essay.

And it's pretty good.
But imagine if you had to do that, like no backspace, no chance to make an outline first.
You just kind of go through.
The agents now will say, okay, first make an outline.
That's the first step you do when you write an essay.

And then, you know, fill in each paragraph, then go back and see if the flow is right.
Now go back and check the voice.
Is this the right level for our audience?
Now, you know, and by iterating like that, you can write a much, much better essay or any kind of a task.
This is a real revolution.

There's all sorts of things you can just do much better if you do that.
Then the thing about the context window is also really important.
So I'm just going to quote smart people that I know.
Eric Corvitz, I was on a panel with him at the GSB.
Some of you may have been there.

It was last week.
And he had this nice taxonomy.
People were asking about fine-tuning.
I think Susan was asking about fine-tuning.
And he said, well, there's really three ways that you can take a model and have it more customized.

One is you can fine-tune it, which basically like train it some more.
Another is with larger and larger context windows.
And the third is with RAG or techniques like that that are retrieval augmented generation where it goes and accesses external data.
But these context windows seem to be like remarkably effective now.
I guess, as Eric was saying, we thought it was hard.

Maybe Peter can explain.
But for some reason, we're able to make much, much bigger ones.
And now as you can load a whole book or a whole set of books, you can load all sorts of information in there.
And that can give you all of the context around it.
So that's a pretty big revolution.

It opens up a bunch of capabilities that we just didn't have before, including having things much more current, as Eric was saying.
Did you want to follow up on that?
That's a good question.
I mean, there's certainly a lot more capital going in, but that kind of begs the question in the comments, why is all this capital going there as opposed to somewhere else?
And I think if you look at the arc of history, sometimes it looks kind of smooth.

But if you look more closely, there's a lot of jumps.
There are certain big inventions and smaller inventions.
And Andrew Carparthi was saying that he was playing around with physics.
And to really make progress in physics, to be a top physicist, you have to be incredibly smart, study a whole lot.
And maybe if you're lucky, you could make some small incremental contribution, and some people do.

But he says that right now in AI machine learning, we seem to be in an era where there's just a lot of low-hanging fruit, that there have been some breakthroughs.
And instead of exhausting the space, like picking all the food off of a tree, it's more like combinatorics.
In second machinery, they talk about building blocks.
When you put two building blocks together, or Lego blocks, you can make more and more.
Right now, we seem to be in an era where there's just a lot of opportunity, and people are recognizing that.

And discovery, one discovery begets another discovery, begets another opportunity.
And because of that, it attracts the investment.
And more people are involved.
And in economics, sometimes when more resources go in, you get diminishing returns, like in, I don't know, in agriculture or in mining.
Other places, there's increasing returns.

And more engineers coming to Silicon Valley makes the existing engineers more valuable, not less valuable.
So we seem to be in an era where that's happening.
And then the flywheel of the additional investment, the additional dollars for training, all of that makes them more and more powerful.
I don't know how long this will continue, but I don't, you know, it just seems that there are some technologies that hit this really fertile period, and there's positive feedback and some help.
We seem to be in one of those right now.

So people who are trained in getting in the field are making contributions that are often quite significant in a faster time than they might have in some other fields.
Encouraging all of you guys, I think are doing the right thing right now.
Yeah.
Let's take a couple more questions, and then yeah.
Okay, how about over here?

So not everyone can sit in a room and have all these discussions and debates around AI.
And so I'd like to get your thoughts on AI literacy for non-technical stakeholders, whether they're policy makers that have to make it in somewhat informed judgment, or the general public like, you know, using tech.
How do you think about explaining technical basics versus discussing abstract implications that don't necessarily have it right in?
Well, that's a hard one.
I have to say there's been a sea change recently in terms of how much people in Congress and elsewhere are paying more attention to this topic.

It used to be not something that they were interested in.
Now everyone's trying to understand it a little bit better.
And I think that there are a lot of margins where people can make contributions.
They can make contributions in the technical side.
But if anything, I mean, my bet is that the business and economic side is where the bigger bottleneck is right now.

That, you know, even if, you know, if you made enormous contribution to the technology side, you still, there's still a gap converting that into something that will change policy.
So understand if you're into political science or politician, understanding what are the implications for democracy and for misinformation and power and concentration.
Those are things that are not well understood at all.
I don't know that a computer scientist is necessarily the right person to try to understand that.
But understanding enough about the technology so you know what might be possible.

And then thinking through what are the dynamics like Henry Kissinger was doing with Eric Schmidt in his book.
If you're an economist thinking through the labor market implications, the implications for concentration, the implications for inequality and jobs, implications for productivity and what drives productivity.
Those are things that are very ripe right now.
And you could go through lots of different fields where there's, you know, understanding well enough what the technology might be capable of.
But then thinking through the implications.

That's I think where some of the biggest payoffs are.
I mean, let me give you a little bit more of a concrete example.
And this is something I was going to talk about last week.
Electricity was also a general purpose technology.
And general purpose technologies have this characteristic that they're part of in and of themselves.

But one of the real powers of general purpose technologies, GPTs as I was saying, is that they give complimentary, they ignite complimentary innovations.
So electricity, light bulbs and computers and electric motors and electric motors give you compressors and refrigerators and air conditioning.
You can just kind of have a whole set cascade of additional innovations from this one innovation.
And most of the value comes from these complimentary innovations.
One thing people don't appreciate enough is that some of the most important complimentary innovations are organizational and human capital complementarities.

So with electricity, when they first introduced electricity into factories, Paul David here at Stanford studied what happened to those factories.
And surprisingly, not much.
The factories when they started electrifying, they were not significantly more productive than the previous factories that were powered by steam engines.
He's like, well, that's kind of weird because this seems like a pretty important technology.
Is it just a fad?

Obviously not.
The factories before electricity were powered by steam engines.
They typically had a big steam engine in the middle and then crankshafts and pulleys that powered all the equipment.
And it was all distributed.
But you tried to have it as close to the steam engine as possible because if you make the crankshaft too long, it would break the torsion.

When they introduced electricity, he found that in factory after factory, they would pull out the steam engine and they would get the biggest electric motor they could find and put it where the steam engine used to be and fire it up.
But you know, it didn't really change production a whole lot.
You can see that that's not a big deal.
So then they started building entirely new factories from scratch in a new location.
What did those look like?

Just like the old ones.
They would take the same model.
Some engineer would make a blueprint, you know, maybe take it, make a big X where the steam engine says, no, no, put electric motor here.
And they'd go and build a fresh factory.
Again, not a big improvement in productivity.

It took about 30 years before we started seeing a fundamentally different kind of factory where instead of having the central power source, you know, a big one in the middle, you had distributed power because electric motors, as you guys know, you know, you can make them big, you can make a medium, you can make them really, really small.
You can have them all connected in different ways.
So they started having each piece of equipment have a separate piece of a separate motor instead of one big one.
They called it unit drive instead of group drive.
I went and read the books in Baker Library at Harvard Business School from like 1914.

And it was like this whole debate about unit drive versus group drive.
Well, when they started doing that, then they had a new layout of factories where it was typically on a single story where the machinery was not based on how much power it needed, but based on the on something else, the flow of materials.
And you started having these assembly line systems.
That led to a huge improvement in productivity, like a doubling of productivity or tripling in some cases.
So the lesson is not that electricity was a fad or dud and was overhyped.

Electricity was a fundamentally valuable technology.
But it wasn't until they had that process innovation, that organizational innovation of rethinking how to do production that you got the big payoff.
There's a lot of stories like that.
I only told you one of them.
We don't want that much time.

So I tell you the other ones.
But in some of my books and articles, if you look at the steam engine and others, you had similar generational lags decades before people realized that this technology could allow you to do something completely different than you used to do.
I think AI is a bit like that in some ways, that there's going to be a lot of organizational innovations, going to be new business models, new ways of organizing an economy that we hadn't thought of before.
Right now, people are mostly just retrofitting.
I could go through a whole other set of skill changes that are complementary.

I don't know what they all are.
You have to be creative to think about them.
But that's what the gap is.
In the case of early computers, it's literally like 10 times more investment in organizational capital and human capital, if you look at the size of the investments, to the hardware and software.
So that's very big.

That said, I'm open to adjusting my thoughts on this a bit because ChachiPT and some of the other tools, they have been adopted very quickly and they have much more quickly been able to change things, in part because you don't need to learn Python to the same degree.
You can do a lot of things just in English.
And you can get a lot of value just by putting them on top of the existing organization.
So some of it's happening faster.
And in some of the papers that you may have read for the readings here, you know, we had like 15, 20, 30% productivity gains pretty quickly.

But my suspicion is that it will be even bigger once people figure out these complementary innovations.
And so that's a long way of answering your question about it.
It's not just the technical skills.
It's figuring out all the other stuff, all the ways of rethinking things.
So those of you who are at the business school or in economics, you know, there's a lot of opportunity there to rethink your areas now that you've been given this amazing set of technologies.

Yeah, question.
It seems like you're expressing more caution than Eric was with regard to the speed of transformation.
Am I correct in saying that?
Well, so I would make a distinction between two things.
I'll defer to him and others on the technology side.

We're going to hear from several other folks.
And there are people who are equally optimistic as him or even more optimistic on the technology side.
There's also people who are less optimistic.
But technology alone is not enough to create productivity.
So you can have an amazing technology.

And then for various reasons, A, maybe people just don't figure out an effective way to use it.
Another is it may be regulatory things.
I mean, some of my computer science colleagues introduced and developed better radiology systems for reading medical images.
They weren't adopted because of cultural, you know, people just didn't want them.
They didn't want and there are safety reasons.

When I did an analysis of which tasks I could help the most and which professions were most affected, I was surprised that airline pilots was kind of near the top.
But I think that a lot of people would not feel comfortable not having the pilot go down with you.
So they sort of you want to have the human in there.
So there are a lot of different things that might slow it down significantly.
And I think that's something we need to be conscious of.

And if we could address those bottlenecks, that would probably do more for productivity than just working on the technology alone.
Yeah, question.
So Eric had an interesting comment on data centers in universities.
I think this is a larger point of like, and I was going to ask him why doesn't he write a check?
People are asking him that question.

Sort of like, what is the role of the university ecosystem?
Obviously, there is this larger I'm sure all of the CS professors here.
So I'll take I mean, I think it'd be great if there were more funding.
I mean, the federal government has something called the national AI resource that is helping a little bit, but it's in like the millions of dollars, tens of millions of dollars, not billions of dollars, let alone hundreds of billions of dollars.
Although Eric did mention to me before class that they're working on something that could be much, much bigger.

He's pushing for something much, much bigger.
I don't know if it'll happen.
That's for training these really large models.
I had a really interesting conversation with Jeff Hinton once.
Jeff Hinton, as you know, is sort of like one of the godfathers of deep learning.

And I asked him like what kind of hardware he found most useful for doing his work.
And he was sitting at his laptop and kind of just tapped his MacBook.
And it just reminded me there's a whole other set of research that maybe universities have a competitive advantage in, which is not training hundred billion dollar models, but it's innovating new algorithms like whatever comes after Transformers and there's a lot of other ways that people can make contributions.
So maybe there's a little bit of a divisional labor.
I'm all for and support my colleagues asking for more budgets for GPUs, but that's not always where academics can make the biggest contribution.

Some of it comes from ideas and new ways of different perspective about thinking about things, new approaches.
And that's likely where we have an advantage.
I had dinner with Sendham Melanathon last week.
He just moved from Chicago to MIT.
And he was a researcher.

We're talking about what is the comparative advantage of universities?
And he made the case, you know, patience is one of them, that there are people in universities who are working on very long term projects.
You know, there's people working on fusion.
They've been working on fusion for a long time, not because they're going to get, you know, a lot of money this year or 10 years from now, probably from building a fusion plant or even 20 years.
I don't know how long it is for fusion.

But, you know, it's just something that people are willing to work on even if the timelines are a little further.
It's harder for companies to afford to have those kinds of timelines.
So there's a comparative advantage or divisional labor in terms of what universities might be able to do.
We have just a couple minutes left.
This is kind of fun.

So we'll just do one or two more questions.
And then I want to talk a little bit about the projects.
Yeah.
Go ahead.
I'm Kevin.

I was wondering about the emerging capabilities of AI.
It seemed that Eric was leaning more towards the architectural differences and designing better models versus the last class we talked about, Morse law instead.
So I'm wondering how you sort of...
Well, he said all three.
So you guys remember the scaling laws?

It had like three parts to it.
I think I put the scaling law that Dario and team...
So there's more compute, more data and algorithmic improvements, including more parameters.
And all three of them, I think I heard Eric say all three of them were important.
But not to be dismissed, this last one, like new architectures, all three of them, I think, are being important.

So I think there was another question in there, though, also.
How much closer are we to like an AGI type system?
So Eric doesn't think we're like that close to AGI type systems, although I don't think it's like a sharp definition.
You know, in fact, that was one of the...
I was going to ask him that question, but we ran out of time.

It would have been good to hear him describe it.
But when I was talking to him, it's just not that sharply defined thing.
In some ways, AGI is already here.
Peter Norvig wrote an article called AGI is already here.
I don't know if it's in the reading packet.

I think if it's not, I'll put it in there.
It's a fun little article with Blaise Iarca.
And a lot of the things that 20 years ago people would have said, this is what AGI is.
That's kind of what LLMs are doing.
Not as well, maybe, but it's sort of solving problems in a more general way.

On the other hand, there's obviously many things they do much worse than humans currently.
Ironically, physical tasks are one of the ones that humans have a comparative advantage in right now.
You guys may know Moravec's paradox.
Hans Moravec pointed out that often the kinds of things that a three-year-old or a four-year-old can do, like buttoning a shirt or walking upstairs, are very hard to get a machine to be able to do.
Whereas a lot of things that a lot of PhDs have trouble doing, like solving convex optimization problems, are things that machines are often quite good at.

So it's not quite things that are easy for humans and hard for computers and other things that are hard for humans and easy for computers.
They're not like the same scale.
And next week we have Mira Morati, Chief Technology Officer of OpenAI, briefly the CEO of OpenAI.
So come with your questions for her.
We'll see you.
