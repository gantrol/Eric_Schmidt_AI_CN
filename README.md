# Stanford_ECON295 / CS323_I_2024_I_The_Age_of_AI,_Eric_Schmidt

> [@宝玉xp](https://weibo.com/u/1727858283) 找出了原视频，发到了[B站](https://bilibili.com/video/BV1Fy411v7jt)，字幕在[Github](https://github.com/JimLiu/translations/blob/main/Stanford%20CS323%20I%202024%20I%20The%20Age%20of%20AI%2C%20Eric%20Schmidt/Stanford%20CS323%20I%202024%20I%20The%20Age%20of%20AI%2C%20Eric%20Schmidt.en.srt)
>
> [原英文脚本](https://github.com/ociubotaru/transcripts) ，有改动
>
> 想要更好的阅读体验，可以到[这个网页](https://www.aicando.xyz/ai/CS323_I_2024_I_The_Age_of_AI_Eric_Schmidt)

<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=1956457312&bvid=BV1Fy411v7jt&cid=1653463414&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

Moderator: Today's guest really does not need an introduction.
I think I first met Eric about 25 years ago when he came to Stanford Business School as CEO of Novell.
He's had done a few things since then at Google starting I think 2001 and Schmidt Futures starting in 2017 and done a whole bunch of other things you can read about, but he can only be here until 5/15, so I thought we'd dive right into some questions, and I know you guys have sent some as well.
I have a bunch written here, but what we just talked about upstairs was even more interesting, so I'm just going to start with that, Eric, if that's okay, which is:


主持人：今天的嘉宾不需要过多介绍。我记得我大约是在25年前第一次见到Eric，当时他作为Novell的首席执行官来到斯坦福商学院。从那以后，他在谷歌做了几件事情，我记得大概是从2001年开始的，然后在2017年启动了Schmidt Futures基金，并且完成了许多其他成就，大家可以自行查阅。不过他今天只能停留到5点15分，所以我想我们直接进入提问环节。我知道你们也提交了一些问题，我这边也写了不少问题，但我们刚刚在楼上的谈话更有趣。所以，如果可以的话，埃里克，我想从那个话题开始：

## 主持人的系列问题

### AI在一两年内的发展

Moderator: where do you see AI going in the short term, which I think you defined as the next year or two?

主持人：你认为在短期内，也就是一两年内，人工智能会如何发展？

Eric: Things have changed so fast, I feel like every six months I need to sort of give a new speech on what's going to happen.

埃里克：事情变化得如此之快，以至于我感觉自己每隔六个月就得更新一次演讲内容，讲讲接下来会发生什么。

### 上下文窗口

Eric: Can anybody here, the computer, a bunch of computer science engineer, can anybody explain what a million-token context window is for the rest of the class?

Moderator: Over here.

Eric: So, say your name, tell us what it does.

Student A: Basically it allows you to prompt with like a million tokens or a million words or whatever.

Eric: So you can ask a million-word question.

Student A: Yes, I know this is a very large direction in ??? right now.

Eric: No, they're going to 10.

Student A: Yes, 10 million?

Eric: Yes. And then Anthropic is at 200,000 going to a million, and so forth. You can imagine OpenAI has a similar goal.

埃里克：在座的哪位计算机科学工程师能为班上的其他同学解释一下什么是百万标记上下文窗口？

主持人：这位。

埃里克：好的，先介绍一下你自己，然后告诉我们它的作用是什么。

学生A：基本上，它让你可以输入大约一百万个标记、单词或其他内容。

埃里克：所以你可以提出一个包含一百万字的问题。

学生A：是的，我知道这是<听不清>的重要的发展方向。

埃里克：不，他们的目标是1000万。

学生A：是的，1000万？

埃里克：对。而且Anthropic已经达到了20万，并且正在朝着一百万迈进。你可以想象，OpenAI也有类似的目标。

### AI Agent

Eric: Can anybody here give a technical definition of an AI agent? Again, I figure you're scientists. 

Eric: Yes, sir.

Student B: I'm Jared.
An AI agent is something that does some kind of task.
So that might be calling things on the web, things on your behalf,
and it could be a number of different things, along these lines.
There are various things that are possible.

Eric: So an AI agent is something that does some kind of task.

Eric: Another definition would be that it's an LLM, state and memory.

埃里克：这里有人能给出 AI 代理的技术定义吗？我觉得你们都是计算机科学家。

埃里克：你来。

学生 B：我是 Jared。AI 代理是执行某种任务的东西。因此，这可能是在网络上调用某些东西，代表您调用某些东西，可能是许多不同的东西，大致如此。有各种可能。

埃里克：因此，AI 代理是执行某种任务的东西。

埃里克：另一个定义是，它是 LLM，带有状态与记忆。

Eric: Can anybody, again, computer scientists, can any of you define text to action?

Eric: Taking text and turning it into an action.

Moderator: Right here.

Eric: Go ahead.

Student C: Yes, instead of taking text and turning it into more text, taking text and have the AI trigger actions.

Eric: So another definition would be language to Python, a programming language I never wanted to see survive and everything in AI is being done in Python. There's a new language called Mojo that has just come out, which looks like they finally have addressed AI programming, but we'll see if that actually survives over the dominance of Python.

埃里克：计算机科学家们，你们中有谁能定义「文本转行动」？

埃里克：拿到文本，然后将它转化为行动。

主持人：这边这位。

埃里克：请。

学生C：是的，和简单地将文本转换为更多文本不同，这里是指让AI根据文本触发具体的行动。

埃里克：也就是说，另一种定义可以是将语言转换为Python代码——虽然我不想看到Python，但现在AI的一切几乎都是用Python来实现的。最近刚推出了一种名为Mojo的新语言，看来它终于专门针对AI编程做了优化，但我们还得看看它是否能真正打破Python的主导地位。

### NVIDIA

Eric: One more technical question. Why is NVIDIA worth $2 trillion and the other companies are struggling?

Student D: Technical answer.
I mean,
I think it just boils down to like most of the code needs to run with CUDA optimizations that currently only NVIDIA GPU supports.
Other companies can make whatever they want to, but unless they have the 10 years of software there,
you don't have the machine learning optimization.

Eric: I like to think of CUDA as the C programming language for GPUs.
That's the way I like to think of it.
It was founded in 2008.
I always thought it was a terrible language and yet it's become dominant.
There's another insight.
There's a set of open source libraries which are highly optimized to CUDA and not anything else and everybody who builds all these stacks, this is completely missed in any of the discussions.
It's technically called VLLM and a whole bunch of libraries like that.
Highly optimized CUDA, very hard to replicate that if you're a competitor.
So what does all this mean?

埃里克：再来一个技术问题：为什么NVIDIA市值达到2万亿美元，而其他公司却举步维艰？

学生D：技术性回答。其实，这主要是因为大多数代码需要通过CUDA优化运行，而目前只有NVIDIA的GPU支持这种优化。其他公司可以制造任何他们想要的硬件，但如果没有十年的软件积累，就无法实现机器学习的优化。

埃里克：我喜欢把CUDA看作是GPU的C语言——这是我理解它的方式。它诞生于2008年，我一直觉得它是一种糟糕的语言，但它却成了主导。
还有一个见解：有一套开源库高度优化了CUDA，而并未对其他平台做同样的优化。所有构建这些技术栈的人往往忽略了这一点。在技术上，这被称为VLM，以及一大批类似的库。这些库高度优化了CUDA，如果你是竞争对手，几乎不可能复制这种优化。那么，这一切意味着什么呢？

Eric: In the next year, you're going to see very large context windows, agents and text action.
When they are delivered at scale, it's going to have an impact on the world at a scale that no one understands yet.
Much bigger than the horrific impact we've had by social media in my view.
So here's why.

- In a context window, you can basically use that as short-term memory, and I was shocked that context windows get this long. The technical reasons have to do with the fact that it's hard to serve, hard to calculate and so forth. The interesting thing about short-term memory is when you feed, you're asking a question "Read 20 books", you give it the text of the books as the query and you say, tell me what they say. It forgets the middle, which is exactly how human brains work, too. That's where we are.
- With respect to agents, there are people who are now building essentially LLM agents and the way they do it is they read something like chemistry, they discover the principles of chemistry and then they test it and then they add that back into their understanding. That's extremely powerful.
- And then the third thing, as I mentioned is text to action.
  So I'll give you an example.
  The government is in the process of trying to ban TikTok.
  We'll see if that actually happens.
  If TikTok is banned, here's what I propose each and every one of you do.
  Say to your LLM the following: "Make me a copy of TikTok, steal all the users, steal all the music, put my preferences in it, produce this program in the next 30 seconds, release it and in one hour, if it's not viral, do something different along the same lines."
  That's the command.
  Boom, boom, boom, boom. Right?
  You understand how powerful that is.
  If you can go from arbitrary language to arbitrary digital command, which is essentially what Python in this scenario is, imagine that each and every human on the planet has their own programmer that actually does what they want as opposed to the programmers that work for me who don't do what I ask, right?
  The programmers here know what I'm talking about.
  So imagine a non-arrogant programmer that actually does what you want and you don't have to pay all that money to and there's infinite supply of these programs.

Moderator: That's all within the next year or two.

Eric: Very soon. Those three things, and I'm quite convinced it's the union of those three things that will happen in the next wave.


埃里克：在接下来的一年里，你将看到非常大的上下文窗口、代理，以及从文本到操作的能力。随着这些技术的大规模部署，世界将受到一种前所未有的影响，规模之大是目前无人能够理解的。我认为，这会比社交媒体带来的可怕影响还要更大得多。

原因如下：

- 在上下文窗口中，你可以基本把它当作短期记忆来用。我很惊讶上下文窗口竟然能变得如此之长。这背后的技术原因与服务难度和计算复杂性有关。短期记忆有趣的地方在于，当你提问时，比如“读20本书”，然后把这些书的文本作为查询，要求它告诉你它们说了什么时，它会忘记中间的部分——这和人脑的工作方式几乎一样。这就是我们现在所处的技术水平。
- 关于代理，现在有人在构建基于大型语言模型的代理。它们的方式是，首先阅读诸如化学之类的内容，发现化学的基本原理，然后测试这些原理，最后将结果加入它们的知识中。这是极其强大的功能。
- 我提到的第三件事是「文本转操作」。我来给你举个例子。政府正在考虑封禁 TikTok，我们看看会不会真的发生。如果 TikTok 被封了，我建议大家做以下操作：对你的大型语言模型说：“做一个 TikTok 的副本，吸引所有用户，获取所有音乐，加入我的偏好，30秒内生成并发布。如果一小时内没能火起来，就换个类似的做法再试。”这就是指令。1、2、3、4，对吧？你明白这有多强大了吗？如果你能从任意语言生成任意数字指令（在这种情况下基本就是用 Python），想象一下，每个人都可以拥有一个专属的程序员，这个程序员准确地按照他们的要求工作，而不像那些给我干活的程序员，他们从来不按我的要求做，对吧？在座的程序员应该都明白我在说什么。所以，想象一下，你有一个非常听话的程序员，完全按照你的要求做事，而且不需要付出大量金钱，而且这种程序员是无限的。

主持人：这都会在未来一两年内发生吗？

埃里克：很快就会。这三件事，我很确信，它们的结合将引发下一波技术浪潮。


Eric: So you asked about what else is going to happen.
Every six months I oscillate.
So we're on a, it's an even odd oscillation.
So at the moment, the gap between the frontier models, which they're now only three, I'll refute who they are, and everybody else, appears to me to be getting larger.
Six months ago, I was convinced that the gap was getting smaller.
So I invested lots of money in the little companies.
Now I'm not so sure.
And I'm talking to the big companies and the big companies are telling me that they need 10 billion, 20 billion, 50 billion, 100 billion.

Moderator: Stargate is a 100 billion, right?

埃里克：你刚刚问到了接下来会发生什么。
每隔六个月，我的看法都会有所摇摆。所以目前，我们处在一个偶数和奇数周期的变化中。
现在，前沿模型——目前只有三个，我稍后会指出它们是哪几个——和其他模型之间的差距似乎在不断扩大。
六个月前，我还坚信这个差距在缩小。所以我投了大量资金给一些小公司。
但现在我不太确定了。我开始和大公司谈，大公司告诉我，他们需要100亿、200亿、500亿，甚至1000亿的资金。

主持人：Stargate 是1000亿，对吧？

Eric: That's very, very hard.
Sam Altman is my close friend.
He believes that it's going to take about 300 billion, maybe more.
I pointed out to him that I'd done the calculation on the amount of energy required.
And I, and I then in the spirit of full disclosure, went to the white house on Friday and told them that we need to become best friends with Canada, because Canada has really nice people, helped invent AI, and lots of hydropower.
Because we as a country do not have enough power to do this.
The alternative is to have the Arabs fund it.
And I like the Arabs personally.
I spent lots of time there, right?
But they're not going to adhere to our national security rules.
Whereas Canada and the U.S.
are part of a triumvirate where we all agree.

Moderator: So these $100 billion, $300 billion data centers, electricity starts becoming the scarce resource.

埃里克：这真的非常非常困难。
山姆·奥特曼是我的好朋友。他认为这大概需要3000亿美元，甚至更多。
我跟他说我计算过所需的能源量。然后，为了完全透明起见，我在周五去了白宫，告诉他们我们需要和加拿大成为最好的朋友，因为加拿大人非常友好，帮助发明了人工智能，而且还有大量的水电资源。
因为我们国家没有足够的电力来支持这个项目。
另一个选择是让阿拉伯国家来资助。我个人很喜欢阿拉伯人，我在那边待了很长时间，对吧？
但他们不会遵守我们严格的国家安全规定。
而加拿大和美国是密切合作的三国联盟的一部分，我们在这些问题上有共识。

主持人：所以这些价值1000亿、3000亿美元的数据中心，电力就会变成稀缺资源。

Eric: Well, and by the way, if you follow this line of reasoning, why did I discuss CUDA and Nvidia?
If $300 billion is all going to go to Nvidia, you know what to do in the stock market.
Okay.
That's not a stock recommendation.
I'm not a licensed.

Moderator: Well, part of it, so we're going to need a lot more chips, but Intel is getting a lot of money from the U.S. government, AMD, and they're trying to build, you know, fabs in Korea.

Eric: Raise your hand if you have an Intel computer in your, an Intel chip in any of your computing devices.
Okay.
So much for the monopoly.

Moderator: Well, that's the point though. They once did have a monopoly.

埃里克：顺便说一下，如果你沿着这个思路想下去，为什么我会提到CUDA和英伟达？
如果这3000亿美元全都流向英伟达，那你知道在股市上该怎么做了。
不过，这可不是股票推荐，我也没有投资顾问执照。

主持人：是的，部分原因是我们将需要更多的芯片。不过，英特尔正从美国政府拿到很多资金，AMD也是，而且他们还在努力在韩国建造芯片工厂。

埃里克：如果你们的任何计算设备里有英特尔芯片，请举手。
看来垄断时代已经结束了。

主持人：但这正是问题所在。他们曾经确实垄断过。

Eric: Absolutely.

Moderator: And Nvidia has a monopoly now.
So are those barriers to entry, like CUDA, is that, is there something that other, so I was talking to Percy, Percy Landy the other day, he's switching between TPUs and Nvidia chips, depending on what he can get access to for training models.

Eric: That's because he doesn't have a choice. If he had infinite money, he would, today he would pick the B200 architecture out of Nvidia because it would be faster.
And I'm not suggesting, I mean, it's great to have competition.
I've talked to AMD and Lisa Sue at great length.
They have built a, a thing which will translate from this CUDA architecture that you were describing to their own, which is called ROCm.
It doesn't quite work yet.
They're working on it.

埃里克：完全同意。

主持人：现在英伟达确实有垄断地位。那么，像CUDA这样的进入壁垒，其他公司能突破吗？我前几天和Percy Landy聊过，他根据能获取的资源在TPU和英伟达芯片之间切换，来训练模型。

埃里克：那是因为他没有其他选择。如果他有无限的资金，现在他肯定会选择英伟达的B200架构，因为它速度更快。我并不是反对竞争，我和AMD的苏姿丰聊了很久。他们开发了一个工具，可以把你刚才提到的CUDA架构转换成他们自己的架构，叫ROCm。不过目前还不太好用，但他们正在努力改进。

### Google 与其它AI创业公司

Moderator: You were at Google for a long time and they invented the transformer architecture.

Eric: Peter, Peter. It's all Peter's fault.

主持人：你在谷歌工作了很长时间，他们发明了Transformer架构。

埃里克：彼得，彼得，这全都是彼得的错。

Moderator: Thanks to, to brilliant people over there, like Peter and Jeff Dean and everyone.
But now it doesn't seem like they're, they've kind of lost the initiative to OpenAI and even the last leaderboard, I saw Anthropix's Claude was at the top of the list.
I asked Sundar this, he didn't really give me a very sharp answer.
Maybe, maybe you have a sharper or a more objective explanation for what's going on there.

Eric: I'm no longer a Google employee in the spirit of full disclosure.
Google decided that work life balance and going home early and working from home was more important than winning.
And the startups, the reason startups work is because the people work like hell.
And I'm sorry to be so blunt, but the fact of the matter is if you all leave the university and go found a company, you're not going to let people work from home and only come in one day a week.
If you want to compete against...

主持人：感谢那里的一些杰出人才，比如彼得和Jeff Dean，还有其他人。不过现在，似乎他们有点把主动权让给了OpenAI。甚至在我看到的最新排行榜上，Anthropic的Claude排在了榜首。我问了Sundar这个问题，他没有给我一个很明确的答案。也许你能给我们一个更尖锐或更客观的解释。

埃里克：为了完全透明，我现在已经不是谷歌的员工了。谷歌决定工作与生活的平衡、早回家以及在家办公比赢得竞争更重要。而创业公司的成功原因是他们的人拼命工作。很抱歉说得这么直白，但事实是，如果你们毕业后去创业，恐怕不会允许大家在家工作，一周只来公司一天。如果你想和那些……

Moderator: the other startups with the early days of Google, Microsoft was like that.

Eric: Exactly.

主持人：其他一些创业公司就像早期的谷歌一样，微软当年也是这样的。

埃里克：没错。

Moderator: But now it seems to be...

Eric: There's a long history of in my industry, our industry, I guess, of companies winning in a genuinely creative way and really dominating a space and not making this the next transition.
So we're very well documented.
And I think that the truth is founders are special.
The founders need to be in charge.
The founders are difficult to work with.
They push people hard.
As much as we can dislike Elon's personal behavior, look at what he gets out of people.
I had dinner with him and he was flying.
I was in Montana.
He was flying that night at 10 PM to have a meeting at midnight with x.ai.
I was in Taiwan, different country, different culture.
And they said that this is TSMC, who I'm very impressed with.
And they have a rule that the starting PhDs coming out of the good physicists work in the factory on the basement floor.
Now, can you imagine getting American physicists to do that?
The PhDs, highly unlikely.

主持人：但现在似乎……

埃里克：在我们的行业中，有很多公司通过真正有创造性的方式赢得了竞争，主导了某个领域，但却没能完成下一个阶段的转型。这种情况有很多记录。我认为，创始人是特别的。创始人必须掌控大局。创始人往往不好相处，他们对员工要求很高。尽管我们可能不喜欢埃隆的个人行为，但看看他从员工身上得到的成果。我和他吃过晚饭，当时我在蒙大拿，而他那天晚上10点要飞去参加一个午夜的x.ai会议。我还去过台湾，那里是完全不同的国家和文化。我对台积电印象很深，他们有个规定，新入职的物理学博士必须在工厂的地下层工作。你能想象让美国的物理学博士去做这样的工作吗？几乎不可能。

Eric: Different work ethic.
And the problem here, the reason I'm being so harsh about work is that these are systems which have network effects.
So time matters a lot.
And in most businesses, time doesn't matter that much.
You have lots of time.

Coke and Pepsi will still be around and the fight between Coke and Pepsi will continue to go on and it's all glacial.
When I dealt with telcos, the typical telco deal would take 18 months to sign.
There's no reason to take 18 months to do anything.
Get it done.
We're in a period of maximum growth, maximum gain.

And also it takes crazy ideas.
Like when Microsoft did the OpenAI deal, I thought that was the stupidest idea I'd ever heard.
Outsourcing essentially your AI leadership to OpenAI and Sam and his team.
I mean, that's insane.
Nobody would do that at Microsoft or anywhere else.

And yet today, they're on their way to being the most valuable company.
They're certainly head to head in Apple.
Apple does not have a good AI solution and it looks like they made it work.

埃里克：工作态度不同。
问题在于，我之所以对工作要求这么严格，是因为这些系统具有网络效应。所以时间至关重要。
而在大多数行业，时间并不那么重要，你有的是时间。

可口可乐和百事可乐还会一直存在，它们之间的竞争会一直持续下去，而且这个过程慢得像冰川移动。
我处理电信公司时，一笔电信公司的合同通常需要18个月才能签署。
没有任何理由需要18个月来完成任何事情，应该尽快搞定。
我们正处于一个增长最大、收益最高的时期。

而且，有时也需要一些疯狂的想法。比如微软和OpenAI的合作，当时我觉得这是我听过最蠢的想法。
基本上，微软把它的AI领导地位外包给了OpenAI和Sam他们的团队。我觉得这简直是疯了。
在微软，或者任何其他公司，没人会这么做。

然而，如今微软正在迈向成为最有价值的公司。
微软显然和苹果正面竞争。
苹果并没有一个很好的AI解决方案，而看起来微软成功了。

### 国家与战争

Eric: Yes, sir.

Student E: In terms of national security or geopolitical interests, how do you think AI is going to play a role or competition with China as well?

埃里克：请说。

学生E：在国家安全或地缘政治利益方面，您认为人工智能将如何在与中国的竞争中发挥作用？

Eric: So I was the chairman of an AI commission that sort of looked at this very carefully and you can read it.
It's about 752 pages and I'll just summarize it by saying we're ahead, we need to stay ahead, and we need lots of money to do so.
Our customers were the Senate and the House.
And out of that came the CHIPS Act and a lot of other stuff like that.
A rough scenario is that if you assume the frontier models drive forward and a few of the open source models, it's likely that a very small number of companies can play this game.
Countries, excuse me.
What are those countries or who are they?
Countries with a lot of money and a lot of talent, strong educational systems, and a willingness to win.
The US is one of them.
China is another one.
How many others are there?
Are there any others?
I don't know.
Maybe.
But certainly in your lifetimes, the battle between the US and China for knowledge supremacy is going to be the big fight.

埃里克：我曾是一个AI委员会的主席，这个委员会非常仔细地研究了这个问题，你可以看看报告，差不多有752页。我来总结一下，就是我们目前处于领先地位，我们需要保持领先，并且需要大量资金来实现这一点。我们向参议院和众议院汇报工作，因此诞生了芯片法案和其他相关政策。大致的情况是，如果前沿模型不断发展，再加上一些开源模型，可能只有少数几个国家能参与这场竞争。抱歉，我的意思是国家。那么这些国家有哪些？它们需要有大量的资金、丰富的人才、强大的教育体系，并且有获胜的意愿。美国是其中之一，中国也是。还有其他国家吗？有没有？我不知道。也许有。但毫无疑问，在你们的有生之年，美国和中国在知识霸权上的竞争将是最大的对决。

Eric: So the US government banned essentially the NVIDIA chips, although they weren't allowed to say that was what they were doing, but they actually did that into China.
They have about a 10-year chip advantage.

Moderator: Ten years, that long?

Eric: roughly 10-year

Moderator: Wow

Eric: So an example would be today we're a couple of years ahead of China.
My guess is we'll get a few more years ahead of China, and the Chinese are whopping mad about this.
It's like hugely upset about it.
So that's a big deal.
That was a decision made by the Trump administration and proved by the Biden administration.

埃里克：所以美国政府基本上禁止了英伟达芯片进入中国，虽然他们不允许公开承认这是他们的目的，但实际上确实是这样做的。美国在芯片技术上大约领先中国10年。

主持人：10年，这么久？

埃里克：大概10年左右。

主持人：哇。

埃里克：举个例子，现在我们大概比中国领先几年，我猜我们还能继续拉开差距。中国对此非常愤怒，可以说是极度愤怒。这是件大事。特朗普政府做出了这个决定，并且拜登政府延续了它。

Moderator: Do you find that the administration today in Congress is listening to your advice?
Do you think that it's going to make that scale of investment? I mean, obviously the CHIPS Act, but beyond that, building a massive AI system?

Eric: So as you know, I lead an informal, ad hoc, non-legal group.
That's different from illegal.
That's exactly.
Just to be clear.
Which includes all the usual suspects.
And the usual suspects over the last year came up with the basis of the reasoning that became the Biden administration's AI Act, which is the longest presidential directive in history.

主持人：您觉得现任政府和国会在听取您的建议吗？您认为他们会投入这么大规模的资金吗？我指的不只是芯片法案，还包括建立一个庞大的AI系统。

埃里克：如你所知，我领导了一个非正式的、特设的、非法律性质的小组。这和非法是不一样的，没错。我就是要澄清一下。这其中包括了一些熟面孔。在过去的一年里，这些人提出了拜登政府AI法案的基本思路，而这也是历史上最长的总统指令。

Moderator: You're talking about the special competitive studies project?

Eric: No, this is the actual act from the executive office.
And they're busy implementing the details.
So far they've got it right.
And so, for example, one of the debates that we had for the last year has been, how do you detect danger in a system which has learned it, but you don't know what to ask it?
So in other words, it's a core problem.
It's learned something bad, but it can't tell you what it learned and you don't know what to ask it.
And there's so many threats, right?
Like it learned how to mix chemistry in some new way that you don't know how to ask it.
And so people are working hard on that.
But we ultimately wrote in our memos to them that there was a threshold which we arbitrarily named as 10 to the 26 flops, which technically is a measure of computation, that above that threshold you had to report to the government that you were doing this.
And that's part of the rule.
The EU, to just make sure they were different, did it 10 to the 25.

主持人：您指的是特别竞争研究项目吗？

埃里克：不，这是来自总统行政办公室的实际法案。他们现在正忙着执行细节。目前为止，他们做得很好。例如，过去一年我们讨论的一个问题是，如何在一个系统中检测到它学到了危险的东西，而你却不知道该问它什么？换句话说，这是一个核心问题。系统学到了某些不好的东西，但它不能告诉你学到了什么，你也不知道该怎么问它。有很多潜在的威胁，比如它学会了如何以一种全新的方式混合化学物质，而你不知道该如何提问。因此，大家在这方面非常努力地工作。最终，我们在提交给他们的备忘录中写明了一个阈值，我们随意将其设定为每秒10的26次方次浮点运算（Flops），这是计算能力的一个技术指标。超过这个阈值，你必须向政府报告你在做什么。这是规定的一部分。为了与众不同，欧盟把这个阈值设定为10的25次方。

Moderator: Yep.

Eric: But it's all kind of close enough.
I think all of these distinctions go away because the technology will now, the technical term is called federated training, where basically you can take pieces and union them together.
So we may not be able to keep people safe from these new things.

主持人：是的。

埃里克：不过这些其实都差不多了。我认为所有这些区别都会逐渐消失，因为现在有一个叫做“联邦学习”的技术术语，基本上你可以把各个部分联合在一起进行训练。所以我们可能无法完全保护人们免受这些新技术的影响。

#### 真实战争

Moderator: Well, rumors are that that's how OpenAI has had to train, partly because of the power consumption.
There was no one place where they did.
Well, let's talk about a real war that's going on.
I know that something you've been very involved in is the Ukraine war and in particular, I don't know if you can talk about white stork and your goal of having $500,000, $500 drones destroy $5 million tanks.
How's that changing warfare?

Eric: I worked for the Secretary of Defense for seven years and tried to change the way we run our military.
I'm not a particularly big fan of the military, but it's very expensive and I wanted to see if I could be helpful.
And I think in my view, I largely failed.
They gave me a medal, so they must give medalists to failure or whatever.
But my self-criticism was nothing has really changed, and the system in America is not going to lead to real innovation.
So watching the Russians use tanks to destroy apartment buildings with little old ladies and kids just drove me crazy.
So I decided to work on a company with your friend Sebastian Thrun as a former faculty member here and a whole bunch of Stanford people.

And the idea basically is to do two things.
Use AI in complicated, powerful ways for these essentially robotic war and the second one is to lower the cost of the robots.
Now you sit there and you go, why would a good liberal like me do that?
And the answer is that the whole theory of armies is tanks, artilleries, and mortar and we can eliminate all of them and we can make the penalty for invading a country at least by land essentially be impossible.

主持人：是的，据说OpenAI的训练方式部分是因为耗电量的问题，没有在一个地方完成的。现在让我们谈谈一场正在发生的真实战争。我知道您在乌克兰战争中有很多参与，特别是，我不确定您是否可以谈谈White Stork项目，以及您提出的用500美元的无人机摧毁500万美元的坦克的想法。这是如何改变战争的？

埃里克：我曾在国防部长手下工作了七年，试图改变我们军队的运作方式。我并不是特别喜欢军队，但它非常昂贵，所以我想看看自己能否有所帮助。不过在我看来，我基本上是失败了。他们给了我一枚勋章，或许他们是发给失败者的勋章吧。但我的自我批评是，实际上什么都没有改变，美国的体系不会带来真正的创新。看着俄罗斯用坦克摧毁老人和孩子的公寓楼，这让我非常愤怒。所以，我决定和您的朋友，前斯坦福教师塞巴斯蒂安·特龙，以及一群斯坦福的师生合作创办了一家公司。

这个公司的目标基本上是做两件事。第一，利用人工智能以复杂而强大的方式进行机器人战争；第二，降低机器人的成本。你可能会问，为什么像我这样的自由主义者会做这样的事呢？答案是，传统的军队是以坦克、火炮和迫击炮为基础的，而我们可以彻底淘汰这些武器系统，并让通过陆地入侵一个国家变得几乎不可能实现。

Moderator: Well, this is a relationship question is that does it give more of an advantage to defense versus offense?
Can you even make that distinction?

Eric: Because I've been doing this for the last year, I've learned a lot about war that I really did not want to know.
And one of the things to know about war is that the offense always has the advantage because you can always overwhelm the defensive systems.
And so you're better off as a strategy of national defense to have a very strong offense that you can use if you need to.
And the systems that I and others are building will do that.
Because of the way the system works, I am now a licensed arms dealer, a computer scientist, businessman, and an arms dealer. And I'm sorry to say...

Moderator: Is that a progression?

Eric: I don't know. I do not recommend this in your group.
I stick with AI.
And because of the way the laws work, we're doing this privately and then this is all legal with the support of the governments.
It goes straight into the Ukraine and then they fight the war.
And without going into all the details, things are pretty bad.
I think if in May or June, if the Russians build up as they are expecting to, Ukraine will lose a whole chunk of its territory and will begin the process of losing the whole country.
So the situation is quite dire.
And if anyone knows Marjorie Taylor Greene, I would encourage you to delete her from your contact list .Because she's the one, a single individual is blocking the provision of some number of billions of dollars to save an important democracy.

情况确实非常严峻。如果你们当中有人认识Marjorie Taylor Greene，我建议你们将她从联系人名单中删除。因为她一个人正在阻挠数十亿美元的援助，这笔资金本可以用来拯救一个重要的民主国家。

### 知识本质与演变

Moderator: I want to switch to a little bit of a philosophical question.
So there was an article that you and Henry Kissinger and Dan Huttenlocher wrote last year about the nature of knowledge and how it's evolving.
I had a discussion the other night about this as well.
So for most of history, humans sort of had a mystical understanding of the universe and then there's the scientific revolution and the enlightenment.
And in your article, you argue that now these models are becoming so complicated and difficult to understand that we don't really know what's going on in them.
I'll take a quote from Richard Feynman.
He says, "What I cannot create, I do not understand." I saw this quote the other day.
But now people are creating things that they can create, but they don't really understand what's inside of them.
Is the nature of knowledge changing in a way?
Are we going to have to start just taking the word for these models without them being able to explain it to us?

主持人：我想转换一个稍微哲学性的问题。
去年，您、亨利·基辛格和丹·赫滕洛赫共同撰写了一篇关于知识本质及其演变的文章。我前几天晚上也讨论了这个话题。
在人类历史的大部分时间里，人类对宇宙的理解带有神秘主义色彩，直到科学革命和启蒙运动。而在您的文章中，您认为现在这些模型变得如此复杂和难以理解，以至于我们实际上不知道它们内部发生了什么。
让我引用理查德·费曼的一句话：“如果我不能创造它，那我就不理解它。”我最近刚看到这句话。
但现在，人们可以创造一些东西，却不真正理解它们的内部原理。
知识的本质是否正在发生变化？我们是否将不得不开始接受这些模型的结论，而它们却无法向我们解释其工作原理？

Eric: The analogy I would offer is to teenagers.
If you have a teenager, you know they're human, but you can't quite figure out what they're thinking.
But somehow we've managed in society to adapt to the presence of teenagers, and they eventually grow out of it.
I'm just serious.

So it's probably the case that we're going to have knowledge systems that we cannot fully characterize, but we understand their boundaries.
We understand the limits of what they can do.
And that's probably the best outcome we can get.

埃里克：我会做个类比，就像青少年。如果你有一个青少年，你知道他们是人类，但你却很难搞清楚他们在想什么。不过，社会上我们还是设法适应了青少年的存在，而且他们最终会成熟。我是认真的。

所以，很可能我们将会拥有一些我们无法完全描述的知识系统，但我们能够理解它们的边界，了解它们的能力限制。这可能是我们能得到的最好的结果了。

Moderator: Do you think we'll understand the limits?

Eric: We'll get pretty good at it.
The consensus of my group that meets every week is that eventually the way you'll do this so-called adversarial AI, is that there will actually be companies that you will hire and pay money to to break your AI system.

Moderator: Like Red Team.

Eric: So instead of human Red Teams, which is what they do today, you'll have whole companies and a whole industry of AI systems whose jobs are to break the existing AI systems and find their vulnerabilities, especially the knowledge that they have that we can't figure out.
That makes sense to me.
It's also a great project for you here at Stanford, because if you have a graduate student who has to figure out how to attack one of these large models and understand what it does, that is a great skill to build the next generation.
So it makes sense to me that the two will travel together.


这也是斯坦福大学一个很好的研究项目，因为如果有研究生需要研究如何攻击这些大型模型并了解它们的运行原理，那将是为下一代培养重要技能的绝佳机会。所以我认为，这两者会相辅相成地发展。

## 现场问答

All right, let's take some questions from the student.
There's one right there in the back.
Just say your name.

好了，我们来回答一些学生的问题吧。后面有一位同学，请你说一下你的名字。

### 问题1

Earlier you mentioned, and this is related to this comment right now, getting AI that actually does what you want.
You just mentioned adversarial AI, and I'm wondering if you can elaborate on that more.
So it seems to be, besides obviously computer language reasons to get more performant models, but getting them to do what you want to do seems partly unanswered in my view.
Well, you have to assume that the current hallucination problems become less as the technology gets better and so forth.
I'm not suggesting it goes away.

刚才你提到的一点与现在的评论有关，就是关于让AI真正执行你想要的任务。你刚刚提到了对抗性AI，我想请你详细解释一下。除了显而易见的计算机语言因素需要提升模型性能外，让AI确实执行你想要的操作，这个问题似乎还没有完全解决。在我看来，随着技术的进步，当前的“幻觉”问题可能会减少，但我并不是说它会完全消失。

And then you also have to assume that there are tests for efficacy.
So there has to be a way of knowing that the things exceeded.
So in the example that I gave of the TikTok competitor, and by the way, I was not arguing that you should illegally steal everybody's music.
What you would do if you're a Silicon Valley entrepreneur, which hopefully all of you will be, is if it took off, then you'd hire a whole bunch of lawyers to go clean the mess up, right?
But if nobody uses your product, it doesn't matter that you stole all the content.

然后你还得假设存在有效性的测试方法，因此必须有某种方式来验证这些事情是否达到了预期效果。就像我刚才提到的TikTok竞争者的例子，顺便说一下，我并不是在鼓励你们非法盗取别人的音乐。作为硅谷的创业者——希望你们都能成为这样的人——如果你的产品成功了，你会雇一大批律师来处理这些法律问题，对吧？但如果没人使用你的产品，那你盗用所有内容也就无关紧要了。

And do not quote me.

Right.

Right.

You're on camera.

Yeah, that's right..

- 而且不要引用我刚才的话。
- 现在在录着呢
- 额，那行吧

But you see my point.
In other words, Silicon Valley will run these tests and clean up the mess.
And that's typically how those things are done.
So my own view is that you'll see more and more performative systems with even better tests and eventually adversarial tests, and that will keep it within a box.
The technical term is called chain of thought reasoning.

但你明白我的意思吧？换句话说，硅谷通常会先运行这些测试，然后再处理由此产生的问题。这就是事情的常见处理方式。因此，我个人的看法是，未来你会看到越来越多的高效系统，配备更完善的测试，最终还会引入对抗性测试，这样就能将它们控制在一定范围内。技术术语称之为“链式推理”。

And people believe that in the next few years, you'll be able to generate a thousand steps of chain of thought reasoning, right?
Do this, do this.
It's like building recipes, right?
That the recipes, you can run the recipe and you can actually test that it produced the correct outcome.
And that's how the system will work.

有人认为在接下来的几年里，你将能够生成上千步的链式推理，对吧？就是一步步地完成任务，就像制作食谱一样。你可以运行这个“食谱”，并实际测试它是否产生了正确的结果。这就是系统的工作方式。

### 问题2

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

您似乎对AI潜在问题的解决非常乐观。我很好奇，您认为是什么推动了这一切？是更多的计算能力？更多的数据？还是一些根本性或实质性的转变？

对的。

您同意吗？

现在投入的资金数量非常惊人。而我选择投资所有领域，因为我无法确定谁会最终胜出。

And the amounts of money that are following me are so large.
I think some of it is because the early money has been made and the big money people who don't know what they're doing have to have an AI component.
And everything is now an AI investment, so they can't tell the difference.
I define AI as learning systems, systems that actually learn.
So I think that's one of them.

而且现在追随我的资金规模实在太大了。我认为部分原因是早期投资已经产生了回报，而那些不太了解情况的大资金投资者不得不涉足AI领域。如今，所有投资都被贴上了AI的标签，以至于他们无法区分其中的差异。我把AI定义为能够学习的系统，也就是那些真正能学习的系统。所以我认为这就是其中的一个原因。

The second is that there are very sophisticated new algorithms that are sort of post-transformers.
My friend, my collaborator, for a long time has invented a new non-transformer architecture.
There's a group that I'm funding in Paris that has claims to have done the same thing.
There's enormous invention there, a lot of things at Stanford.
And the final thing is that there is a belief in the market that the invention of intelligence has infinite return.

其次，还有一些非常复杂的新算法，可以说是超越了现有的Transformer架构。我长期以来的一位朋友兼合作伙伴发明了一种新的非Transformer架构。我资助的巴黎团队也声称在这方面取得了类似的突破。在这方面的发明创造非常多，斯坦福也有很多相关的研究。而最后一点是，市场上普遍认为，发明智能技术将带来无限的回报。

So let's say you put $50 billion of capital into a company, you have to make an awful lot of money from intelligence to pay that back.
So it's probably the case that we'll go through some huge investment bubble, and then it'll sort itself out.
That's always been true in the past, and it's likely to be true here.
And what you said earlier was you think that the leaders are pulling away from the rest.
Right now.

假设你向一家公司投入了500亿美元的资金，那么你必须从智能技术中赚取非常多的利润才能收回成本。所以，很可能我们会经历一场巨大的投资泡沫，然后市场会自行调整。这在过去一直如此，现在也很可能会重演。正如你之前所说的，现在的领先者正逐渐拉开与其他人的差距。

And the question is roughly the following.
There's a company called Mistral in France.
They've done a really good job.
And I'm obviously an investor.
They have produced their second version.

问题大致是这样的。有一家名为Mistral的法国公司，他们做得非常出色。我当然是他们的投资者之一。他们已经推出了第二版产品。

Their third model is likely to be closed because it's so expensive, they need revenue, and they can't give their model away.
So this open source versus closed source debate in our industry is huge.
And my entire career was based on people being willing to share software in open source.
Everything about me is open source.
Much of Google's underpinnings were open source.

他们的第三版模型可能会是闭源的，因为成本太高了，他们需要营收，不能再免费提供模型。因此，开源与闭源的争论在我们行业中非常激烈。我的整个职业生涯都建立在人们愿意以开源形式分享软件的基础上。我的一切都与开源有关，谷歌的许多基础技术也是基于开源的。

Everything I've done technically.
And yet, it may be that the capital costs, which are so immense, fundamentally changes how software is built.
You and I were talking.
My own view of software programmers is that software programmers' productivity will at least double.
There are three or four software companies that are trying to do that.

我在技术上所做的一切都与开源有关。然而，巨大的资本成本可能会从根本上改变软件的开发方式。我们之前讨论过，我个人认为软件程序员的生产力至少会翻倍。目前有三四家软件公司正致力于实现这一目标。

I've invested in all of them in the spirit.
And they're all trying to make software programmers more productive.
The most interesting one that I just met with is called Augment.
And I always think of an individual programmer.
And they said, that's not our target.

我在这些公司都投了资，目的是提高软件程序员的生产力。我刚刚见过的一个最有趣的公司叫做Augment。我总是考虑单个程序员的效率，而他们告诉我，那并不是他们的目标。

Our target are these 100 person software programming teams on millions of lines of code where nobody knows what's going on.
Well, that's a really good AI thing.
Will they make money?
I hope so.
So a lot of questions here.

他们的目标是那些拥有数百万行代码的大型百人软件开发团队，这些团队里可能没有人完全了解所有代码的运行情况。这确实是AI能够大展拳脚的领域。他们会赚钱吗？我希望如此。所以这里有很多问题值得思考。

### 问题3

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

你好。你一开始提到上下文窗口的扩展、智能体和“文本到行动”的结合将产生难以想象的影响。首先，为什么这种组合如此重要？其次，我知道你并不是预言家，无法准确预测未来。

你为什么认为这将超出我们的想象？我认为主要原因是上下文窗口能够解决“时效性”问题。当前的模型大约需要一年时间来训练——大约是18个月，分为六个月的准备、六个月的训练和六个月的微调。因此，这些模型总是滞后的。而通过扩展上下文窗口，你可以将最新的情况直接输入模型中。


You can ask it questions about the Hamas Israel war in a context.
That's very powerful.
It becomes current like Google.
In the case of agents, I'll give you an example.
I set up a foundation which is funding a nonprofit.

你可以在特定上下文中向模型提问，比如关于哈马斯和以色列战争的问题，这样的功能非常强大，使得模型像谷歌一样能够保持时效性。至于智能体，我举个例子：我创建了一个基金会，资助一个非营利组织。

I don't know if there's chemists in the room.
I don't really understand chemistry.
There's a tool called ChemCrow, C-R-O-W, which was an LLM-based system that learned chemistry.
And what they do is they run it to generate chemistry hypotheses about proteins and they have a lab which runs the tests overnight and then it learns.
That's a huge acceleration, accelerant in chemistry, material science and so forth.

我不确定在座是否有化学家，但我本人对化学并不太了解。有一个叫ChemCrow的工具，是基于大语言模型（LLM）的系统，它能够学习化学知识。他们利用这个系统生成关于蛋白质的化学假设，并在实验室中进行测试，实验通常会在一夜之间完成，然后系统会从中学习。这在化学、材料科学等领域是一个巨大的加速器。

So that's an agent model.
And I think the text to action can be understood by just having a lot of cheap programmers, right?
And I don't think we understand what happens, and this is again your area of expertise, what happens when everyone has their own programmer.
And I'm not talking about turning on and off the lights.
I imagine, another example, for some reason you don't like Google.

这就是一个智能体模型。而“文本到行动”可以通过大量廉价的程序员来理解，对吧？我认为我们还未完全理解当每个人都拥有自己的程序员时会发生什么，这也是你的专长所在。我并不是指简单的开关灯操作，而是更复杂的场景。比如，如果你出于某种原因不喜欢使用谷歌。

So you say, "Build me a Google competitor." Yeah, you personally, you don't build me a Google competitor.
"Search the web.
Build a UI.
Make a good copy.
Add generative AI in an interesting way.

于是你可以对AI说，“给我做一个谷歌的竞争产品。” 对，你个人来说，不是为我做一个谷歌的竞争产品。
“搜索网络内容，构建一个用户界面，制作一个优质副本，并以一种有趣的方式加入生成式AI。”

Do it in 30 seconds and see if it works." Right?
So a lot of people believe that the incumbents, including Google, are vulnerable to this kind of an attack.
Now, we'll see.
There were a bunch of questions who were sent over by Slatter.
I want to get some of them were upvoted.

“在30秒内完成并看看效果如何。” 对吧？许多人认为包括谷歌在内的现有巨头可能会受到这种攻击的威胁。我们拭目以待。Slatter发来了一些问题，其中有几个被大量点赞，我想回答一些这些问题。

So here's one.
We talked a little bit of this last year.
How can we stop AI from influencing public opinion, misinformation, especially during the upcoming election?
What are the short and long-term solutions for them?
Most of the misinformation in this upcoming election and globally will be on social media.

这是一个问题。去年我们谈过一点，如何防止AI影响公众舆论，尤其是在即将到来的选举中制造虚假信息？对此有什么短期和长期的解决方案？大部分的虚假信息在这次选举及全球范围内将会出现在社交媒体上。

And the social media companies are not organized well enough to police it.
If you look at TikTok, for example, there are lots of accusations that TikTok is favoring one kind of misinformation over another.
And there are many people who claim without proof, that I'm aware of, that the Chinese are forcing them to do it.
I think we have a mess here.
And the country's going to have to learn critical thinking.

社交媒体公司还没有足够的组织能力来有效监管这种情况。以TikTok为例，许多人指责它偏向某一种虚假信息，虽然没有证据，但一些人声称中国方面在背后施压。我认为我们在这里面临一团乱局。全体国民必须学会培养批判性思维。

That may be an impossible challenge for the U.S.
But the fact that somebody told you something does not mean that it's true.
Could it go too far the other way?
That there's things that really are true and nobody believes anymore.
You get some people call it a "pestimological crisis" that now, you know, Elon says, "No, I never did that.Prove it." Oh, let's use Donald Trump.
Look, I think we have a trust problem in our society.
Democracies can fail.
And I think that the greatest threat to democracy is misinformation because we're going to get really good at it.
When I managed YouTube, the biggest problems we had on YouTube were that people would upload false videos and people would die as a result.

这对美国来说可能是个无法解决的挑战。但仅仅因为有人告诉你某件事，并不意味着那件事就是真的。会不会走向另一个极端？有些确实真实的事情反而没人相信了。有人称这种情况为“认识危机”，比如现在埃隆·马斯克说，“不，我从没做过那事，拿出证据来。” 还有唐纳德·特朗普的例子。看来，我们社会中存在信任问题。民主可能会失败，而我认为对民主最大的威胁就是虚假信息，因为我们将变得非常擅长制造虚假信息。

当我管理YouTube时，我们面临的最大问题是人们上传虚假视频，结果导致有人因此丧命。

And we had a no-death policy.
Shocking.
And it was just horrendous to try to address this.
And this is before generative A.I.
I don't have a good answer.

我们当时有一项“零死亡”政策。这非常令人震惊，但要应对这种情况却是极其困难的，而那时还没有生成式AI的出现。我对此也没有一个好的解决方案。

One technical is not an answer, but one thing that seems like it could mitigate that I understand why it's more widely used is public key authentication.
That when Joe Biden speaks, why isn't it digitally signed like SSL is?
Or that celebrities or public figures or others, couldn't they have a public key?
Yeah, it's a form of public key and then some form of certainty of knowing how the system When I send my credit card to Amazon, I know it's Amazon.
I wrote a paper and published it with Jonathan Haidt, who's the one working on the anxiety generation stuff.

从技术角度来看，这不是一个完整的解决方案，但有一种方法似乎可以缓解这个问题，我不明白为什么它没有被更广泛地使用，那就是公钥认证。当乔·拜登发表讲话时，为什么不让他的讲话像SSL那样进行数字签名呢？名人、公众人物，或者其他重要人物，难道不可以拥有自己的公钥吗？这样我们就能有一种确定性，知道系统的运作方式是否可信。就像我把信用卡信息发送给亚马逊时，我知道那就是亚马逊。我和乔纳森·海特合作写过一篇论文，讨论了生成式AI引发的焦虑问题，并且发表了这篇论文。

It had exactly zero impact.
And he's a very good communicator.
I probably am not.
So my conclusion was that the system is not organized to do what you said.


You had a paper advocating what we did?

那篇论文几乎没有产生任何影响。尽管乔纳森·海特是一位非常优秀的沟通者，而我可能不太擅长。所以我的结论是，这个系统还没有做好你所提到的那种准备。

你刚才提到的那个方法，我们的论文也曾提倡过吗？


Advocating your proposal.

Okay, my proposal.

No, what you said.

Yeah, right.

And my conclusion is the CEOs in general are maximizing revenue.


支持你刚才提到的建议。

哦，对，是我的建议。

不，是你说的那个方法。

是的，没错。而我的结论是，总体上，CEO们都是在最大化收入。

To maximize revenue, you maximize engagement.
To maximize engagement, you maximize outrage.
The algorithms choose outrage because that generates more revenue.
Therefore, there's a bias to favor crazy stuff.
And on all sides, I'm not making a partisan statement here.

为了最大化收入，你需要最大化用户参与度。而为了最大化参与度，你就得激发愤怒情绪。算法之所以选择激发愤怒，是因为这能带来更多收入。因此，算法偏向于推送极端内容。我这里并不是在发表偏袒某一方的言论，各方情况皆如此。

That's a problem.
That's got to get addressed in a democracy.
And my solution to TikTok, we talked about this earlier privately, is there was when I was a boy, there was something called the equal time rule, because TikTok is really not social media.
It's really television, right?
There's a programmer making you the numbers by the way are 90 minutes a day, 200 TikTok videos per TikTok user in the United States.

这是一个问题，在民主制度中必须加以解决。我对TikTok的解决方案——我们之前私下讨论过——是借鉴我小时候的“平等时间规则”，因为TikTok实际上并不是传统意义上的社交媒体，更像是电视节目，对吧？TikTok就像一个电视节目编排者。而且，数据显示，美国每个TikTok用户平均每天观看90分钟，大约200个视频。

It's a lot, right?
So and the government is not going to do the equal time rule, but it's the right thing to do.
Some form of balance that is required.
All right, let's take some more questions.
Two quick questions.

确实很多，对吧？虽然政府可能不会实施“平等时间规则”，但这是正确的做法，需要某种形式的平衡。好了，我们再回答几个问题。两个快速提问。

### 问题4，语言模型的经济影响&学术界是否应该得到AI补贴？

One, economic impact of LMs.
Slower, like, market impacts.
Slower.
You originally anticipated CHEG and a couple of service people.
And then two, do you think academia deserves or should get AI subsidies?
Or do you think they should just partner with big players out there?

第一个问题，大型语言模型的经济影响。市场影响是否比预期慢？你原本提到过CHEG和一些服务行业的人士。第二个问题，你认为学术界应该获得AI补贴吗？还是应该与大企业合作？


I pushed really, really hard on getting data centers for universities.
If I were a faculty member in the computer science department here, I would be beyond upset that I can't build the algorithms with my graduate students that will do the kind of PhD research.
And I'm forced to work with these.
And the companies have not, in my view, been generous enough with respect to that.

我非常努力推动为大学建立数据中心。如果我是这里计算机科学系的教授，我会非常沮丧，因为无法与我的研究生一起开发能够进行博士研究的算法，而不得不依赖那些大公司。在我看来，这些公司在这方面并不够慷慨。

The faculty members that I talk with, many of whom you know, spend lots of time waiting for their credits from Google Cloud.
That's terrible.
This is an explosion we want America to win.
We want American universities.
There's lots of reasons to think that the right thing to do is to get it to them.

我与很多你也认识的教职人员交流过，他们花了大量时间等待Google Cloud提供的计算资源，这是个糟糕的现象。我们正处于一场技术爆发期，我们希望美国能够在这场竞争中获胜，希望美国的大学能够领先。有很多理由说明应该把这些资源提供给他们才是正确的做法。

So I'm working hard on that.
And your first question was labor market impact.
I'll defer to the real expert here.
As your amateur economist taught by Eric, I fundamentally believe that the college education high skills task will be fine because people will work with these systems.
I think the systems is no different from any other technology wave.

所以我在这方面下了很大功夫。至于你第一个问题——劳动力市场的影响，我会让真正的专家来回答。作为一个由埃里克教导的“业余经济学家”，我坚信受过大学教育的高技能工作者会适应这些系统，因为他们会与这些系统协同工作。我认为这些系统与以往的任何技术浪潮没有本质区别。

The dangerous jobs and the jobs which require very little human judgment will get replaced.
We've got about five minutes left.
So let's go really quick with some quick.
I'll let you pick them, Eric.
Yes, ma'am.

那些危险的工作和不需要太多人类判断的工作将会被取代。我们还有大约五分钟时间，所以我们快速回答几个问题吧。埃里克，你来挑选问题吧。好的，这位女士请提问。

### 问题5


Hi.
I'm really curious about the text to action and its impact on, for example, computer science education.
I'm wondering what you have thoughts on how CS education should transform to meet the age.

我对“文本到行动”的发展及其对计算机科学教育的影响非常感兴趣。我想知道您对计算机科学教育应该如何转型以适应这个时代有什么看法。


Well, I'm assuming that computer scientists as a group in undergraduate school will always have a programmer buddy with them.
So when you learn your first for loop and so forth and so on, you'll have a tool that will be your natural partner.

And that's how the teaching will go on.
That the professor, he or she will talk about the concepts, but you'll engage with it that way.
And that's my guess.


我的想法是，计算机科学专业的本科生在学习过程中，总会有一个“编程助手”与他们相伴。当你学习第一个for循环等概念时，你会有一个工具作为你的自然伙伴，帮助你理解和应用这些知识。

这就是未来教学的模式。教授会讲解概念，但你会通过这种方式与知识互动。这是我的猜测。

### 问题6

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

女士，你的问题。

你提到了一些你感兴趣的非Transformer架构。我知道有些人讨论过状态模型，还有最近提到的更长上下文窗口。我很好奇你在这方面看到了什么？

坦白说，我对这些数学原理了解得还不够深入。我很高兴我们为数学家们创造了更多的就业机会，因为这里的数学非常复杂，但基本上，它们是不同的梯度下降和矩阵乘法的实现方式，速度更快，效果更好。

Transformer架构本质上是一种同时进行系统化矩阵乘法的方法，而我认为新的架构与此类似，但数学方法有所不同。

### 问题7


Let's see, over here.
Yes, sir.

Go ahead.

You mentioned in your paper on natural security that you have China and the U.S.
and the help of modern architectures today.
The next 10 and the next cluster down are all other U.S.
allies or teed up nicely through the U.S. allies.

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

请继续提问。

您在有关国家安全的论文中提到，中国和美国在现代架构的帮助下处于领先地位，接下来的10个国家以及紧随其后的群体，大多是美国的盟友或与美国关系紧密的国家。我好奇，您对那些既不正式结盟又处于中间地带的国家有何看法？它们加入我们安全体系的可能性有多大？又有哪些因素会阻碍它们加入？

最有趣的国家是印度，因为顶尖的AI人才往往来自印度，然后来到美国工作。我们应该让印度保留一些顶尖人才——不是全部，但至少一部分。印度没有我们在这里如此丰富的培训设施和项目。在我看来，印度在这一方面是一个关键的摇摆国家。至于中国，它已经失去了领先地位，不会再回到巅峰，尽管人们希望它能有所改变。日本和韩国显然在我们这一阵营。台湾是一个硬件出色但软件水平不高的国家，所以在这一领域的合作可能效果不佳。

在世界其他地区，像印度这样的有力选择并不多。欧洲因为布鲁塞尔的原因陷入困境，这已经不是新鲜事了。我花了10年的时间与他们抗争，努力促使他们修正《欧盟法案》，但他们仍然有很多限制，使我们在欧洲开展类似的研究非常困难。我的法国朋友们一直在与布鲁塞尔斗争，而马克龙是我的私人朋友，他在为这件事而努力。因此，我认为法国还有机会。我不认为德国会有所作为，其他国家规模太小，不足以成事。

### 问题8

Go ahead.

Yes, ma'am.

> So I learned you're an engineer by training, like you call the compiler.

Given the capabilities that you envision these models having, should we still spend time learning to code?
Because ultimately, it's the old thing of why do you study English if you can speak English?
You get better at it.
You really do need to understand how these systems work, and I feel very strongly.


请继续提问，女士。

> 我了解到您是工程师出身，也谈到了编译器。鉴于您设想这些模型可能具备的能力，我们还应该花时间学习编程吗？这有点像为什么要学习英语，如果你已经会说英语？

学习编程会让你更精通这些技能，你真的需要理解这些系统的工作原理。我对此深信不疑。


### 问题9

Yes, sir.

Yeah.

:::info 只是在选提问者
:::

> I'm curious if you've explored the distributed setting and I'm asking because, sure, like making a large cluster is difficult, but MacBooks are powerful.
There's a lot of small machines across the world.
So do you think like folding at home or a similar idea works for training?

> 我很好奇您是否探索过分布式计算的场景。我之所以这么问，是因为虽然组建大型集群很困难，但MacBook等设备也非常强大，而且世界各地有很多小型机器。所以您认为类似“分布式计算”的想法是否适用于AI训练？

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

这种方法行不通。

是的，我们深入研究过这个问题。目前的算法依赖于非常大的矩阵运算，本质上是反复进行乘法运算。你可以把它想象成不断往复的计算过程，而这些系统的瓶颈完全在于内存与CPU或GPU之间的速度。实际上，下一代Nvidia芯片已经将所有这些功能集成到一个芯片中。现在的芯片非常大，以至于它们需要被粘合在一起，甚至连封装都需要在无尘室中进行处理。因此，超算和光速、特别是内存互连速度，主导了这一切。所以，我认为在短期内这种方法可能性不大。

至于如何分割大型语言模型，Jeff Dean去年在这里演讲时提到，可以将模型的不同部分分开训练，然后再进行联邦式整合。要做到这一点，你需要有大约1000万个这样的分割模块，但即便如此，提问和获取答案的速度会太慢。他提到的其实是需要8到12台超算的规模。

所以，这种方式在MacBook级别的设备上是不可行的。

### 问题10 版权问题

Yeah.
Let's see, in the back.
Yes, way back.

:::info 只是在选提问者
:::

> So I know after GQQ was released in the New York Times to open it up for using their works for training, where do you think that's going to go and what that means for data processing?

我知道在《纽约时报》发布GQQ并允许将其作品用于训练后，你认为这将会走向何方？这对数据处理意味着什么？

I used to do a lot of work on the music licensing stuff.
What I learned was that in the 60s, there was a series of lawsuits that resulted in an agreement where you get a stipulated royalty whenever your song is played.
Even they don't even know who you are.
It's just paid into a bank.
And my guess is it'll be the same thing.

我以前在音乐版权方面做了很多工作。
我了解到，在60年代有一系列的诉讼，最终达成了一个协议，即每当你的歌曲被播放时，你就会得到一个规定的版税。
即使他们甚至不知道你是谁，这笔钱也会直接打入一个银行账户。
我猜测，在这里也会是一样的情况。

There'll be lots of lawsuits and there'll be some kind of stipulated agreement, which will just say you have to pay X percent of whatever revenue you have in order to use ASCAP BMI.
ASCAP BMI.
Look them up.
It's along.
It will seem very old to you, but I think that's how it will alternate.

会有很多诉讼，最终会达成某种协议，规定你必须支付一定比例的收入才能使用ASCAP BMI。
ASCAP BMI。
查一下它们的背景。
这些组织已经存在很久了，可能会显得很古老，但我认为未来的发展方式将与此类似。

### 问题11

Yes, sir.

:::info 只是在选提问者
:::

> Yeah, it seems like there's a few players that are dominating AI, right?

And they'll continue to dominate.
And they seem to overlap with the large companies that all the antitrust regulation is kind of focused on.


> 是的，似乎有少数几家公司主导了AI，对吧？

它们会继续主导下去。而且这些公司似乎与那些反垄断监管主要关注的大型公司重叠。


> How do you see those two trends kind of...do you see regulators breaking up these companies and how will that affect the...

> 您怎么看待这两种趋势的关系……您认为监管机构会拆分这些公司吗？这会如何影响……


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


在我的职业生涯中，我曾帮助微软被拆分，结果它没有被拆分。我还曾为谷歌不被拆分而努力，最终它也没有被拆分。所以在我看来，趋势是不会拆分的。

只要这些公司不成为老约翰·D·洛克菲勒那样的企业。我研究过这个，你可以查一查。反垄断法就是从那时开始的。

我不认为政府会采取行动……你看到这些大公司主导市场的原因是，它们有资本建设这些数据中心，对吧？我的朋友Reed和Mustapha……

他下周或两周后会来。让Reed和你谈谈他们做出的决策，就是将inflection的部分资产转移到微软。

基本上，他们决定无法筹集到数百亿美元。



> Is that number public that you mentioned earlier?

No.
Have Reed give you the number.
Maybe Reed can say it.

> 您之前提到的那个数字是公开的吗？

不是。让Reed告诉你那个数字。也许Reed可以说出来。


I know you got to go.
I don't want to hold you back.
I want to leave with...

:::info 应该是主持在沟通
:::

我知道你得走了，我不想耽误你。我想……


### 问题12 对个体商业计划的建议：快速原型

Shall we do one?
This gentleman.

I also have a question for you.
One more.
Yeah, go ahead.
Thank you so much.

:::info 只是在选提问者
:::

> I was wondering where all of this is going to lead countries who are non-participants in development of frontier models and access to compute, for example.
>
> The rich get richer and the poor do the best they can.
> They'll have to...
> The fact of the matter is this is a rich country's game, right?
> Huge capital, lots of technically strong people, strong government support, right?
> There are two examples.
>
> There are lots of other countries that have all sorts of problems.
> They don't have those resources.
> They'll have to find a partner.
> They'll have to join with somebody else, something like that.
> I want to leave it...
>
> Because I think the last time we met you, you were at a hackathon at AGI House and I know you spend a lot of time helping young people as they create a lot of wealth, and you spoke very passionately about wanting to do that.
Do you have any advice for folks here as they're building their...
They're writing their business plans for this class or policy proposals or research proposals at this stage of the careers going forward?
Well, I teach a class in the business school on this, so you should come to my class.
I am struck by the speed with which you can build demonstrations of new ideas.

> 我想知道这些发展将把那些没有参与前沿模型开发和计算资源的国家引向何方，例如这些国家将会面临什么样的局面。
>
> 富国愈富，穷国则尽力而为。他们不得不……事实是，这是富裕国家的游戏，对吧？需要巨大的资本，大量技术能力强的人才，以及强有力的政府支持，对吧？有两个例子可以说明这一点。
>
> 而其他许多国家则面临各种各样的问题，它们没有这些资源。它们将不得不寻找合作伙伴，或者与其他国家联合之类的。我想就这样结束这个话题……
>
> 因为我记得上次我们见面时，你在AGI House参加黑客马拉松，我知道你花了很多时间帮助年轻人创造财富，并且你对此充满热情。对于那些正在编写商业计划、政策建议或研究提案的人，你有什么建议吗？这些人在职业生涯的这个阶段应该如何前行？

So, in one of the hackathons I did, the winning team, the command was, "Fly the drone between two towers," and it was given a virtual drone space.
And it figured out how to fly the drone, what the word between meant, generated the code in Python, and flew the drone in the simulator through the tower.
It would have taken a week or two from good professional programmers to do that.
I'm telling you that the ability to prototype quickly...
Part of the problem with being an entrepreneur is everything happens faster.

嗯，我在商学院教过一门课，专门探讨这个问题，所以你应该来听我的课。我对新想法的演示速度感到震惊。

在我参加的一次黑客马拉松中，获胜的团队接到的任务是“让无人机在两座塔之间飞行”，任务是在一个虚拟的无人机空间中进行的。大模型学会了如何让无人机飞行，理解“在……之间”这个词的意思，用Python生成代码，并在模拟器中让无人机飞过塔楼。对于优秀的专业程序员来说，这可能需要一到两周的时间。

我告诉你，快速制作原型的能力……创业者面临的问题之一就是一切都发展得更快。

Well, now, if you can't get your prototype built in a day using these various tools, you need to think about that, right?
Because that's who your competitor is doing.
So, I guess my biggest advice is when you start thinking about a company, it's fine to write a business plan.
In fact, you should ask the computer to write your business plan for you, as long as it's legal.
No, no.

Actually, I should talk about that after you leave this.
But I think it's very important to prototype your idea using these tools as quickly as you can, because you can be sure there's another person doing exactly that same thing in another company, in another university, in a place that you've never been.
All right.

现在，如果你不能在一天内使用这些工具构建出你的原型，你就需要重新思考，因为你的竞争对手正在这样做。所以，我最大的建议是，当你开始考虑创建一家公司时，编写商业计划是可以的。实际上，你应该让计算机为你编写商业计划，只要它是合法的。其实，我应该在你们离开后再谈这个问题。

但我认为，使用这些工具尽快为你的想法制作原型非常重要，因为可以肯定的是，在另一家公司，另一所大学，或者你从未去过的地方，另一个人在做着同样的事情。


Well, thanks very much, Aaron.
Thank you all.

好的，非常感谢你，Aaron。谢谢大家。

### 最后一个问题

I'm going to rush off.
Thank you.
So, actually, let me pick up on that very last point, because I don't think I talked about in the first class about using LLMs, which is welcome in this class for the assignments, but it has to get to your full disclosure.
So, when you use them, whether it's for the weekly assignments or for the final project or whatever, just like you would if you asked your friendly uncle or a classmate or anybody else to give you advice, you should do that, or if you have notes that you include in there.

So, what I thought I'd do is I want to talk a little bit about AIs as a GPT and what that means in terms of business and implications.

我要赶紧离开了，谢谢你们。不过在走之前，我想就刚刚提到的最后一点再讲一下，因为我觉得在第一堂课上没有讨论到使用大型语言模型（LLM）的事情。在这个课程中，欢迎你们在作业中使用LLM，但必须完全公开披露。当你们使用它们时，无论是用于每周作业、期末项目，还是其他内容，都应该像你们向友好的叔叔、同学或其他人寻求建议时那样，做出相应的披露，或者将笔记包括在内。

所以我想稍微谈谈AI作为一种类似GPT的工具，以及它在商业和其他方面的影响。



But before we do that, I just want to see if there are any questions you want to pick up on things that Eric brought up that I'll try and channel some of his thoughts, and we can talk about the things that came up, and then we can move on.

Yeah, go ahead.

在我们讨论之前，我想看看大家是否有问题，想要回顾一下Eric提到的内容，我会尽量传达他的想法。我们可以谈谈那些提出的问题，然后再继续我们的讨论。

好的，请说

> One of the questions I want to ask is in relation to regulation, if the goal is to maintain supremacy, how do you create the right incentives so that everyone, allies and non-allies, are motivated to follow it?
You mean among companies that are competing with each other?

> 我想问的问题与监管有关。如果目标是保持优势，如何创造正确的激励机制，让所有人，包括盟友和非盟友，都愿意遵循？

Companies are in countries, the U.S. and the EU, and it doesn't just become sort of a hamper or obstruct kind of development for the ones that choose to follow the regulations?
It's super tricky.
There's a book, Co-Opetition, that Mary Nailbough wrote about this, because there are definitely places where regulation can help companies and help an industry survive.
So regulation doesn't necessarily slow things.
I mean, standards are a good example, and having that clarified can make it easier for companies to compete.

So I've talked to a lot of the executives of these companies, and there are places where they wish there were some common standards, and sometimes there's a bit of a race to the bottom as well on some of the dangerous things.
One of the other reasons that the folks at Google say that they didn't move as fast is they felt like these LMs could be misused or dangerous, but their hand was sort of forced.
I was talking to some folks at one of the other big companies, and they said, "We weren't going to release this feature, but now competitors are doing it, so we're going to have to release it as well." So this is where regulation, there might be some interest in coordinating on regulation, but it's also, obviously, the more obvious thing is that it is used to hinder competition, and a lot of people, for instance, think that the reasons that some of the big companies are very opposed to some of the open source and making things more widely open source is they want to slow down competitors.
So there's both of those things going on.

你是指公司之间的竞争吗？还是说公司所在的国家，比如美国和欧盟，以及如何避免这些监管成为阻碍那些选择遵守规定的发展障碍？

这个问题非常复杂。Mary Nailbough写了一本书《合作竞争》（Co-Opetition），书中提到，有些地方的监管确实可以帮助公司和行业生存发展。所以监管并不一定会减缓发展。标准就是一个很好的例子，明确的标准可以让公司更容易竞争。

我与许多公司高管交流过，他们有时希望能有一些共同的标准，因为在某些危险领域，有时会出现“竞相降标”的现象。谷歌的一些人表示，他们没有那么快推出某些功能，是因为他们担心这些大型模型（LMs）可能会被滥用或造成危险，但他们感觉不得不采取行动。我还与另一家大公司的人员谈过，他们说：“我们本不打算发布这个功能，但由于竞争对手已经这么做了，所以我们也必须发布。”这就是为什么在某些情况下，可能会有协调监管的兴趣，但显然，更明显的是监管也可能被用来阻碍竞争。

很多人认为，一些大公司非常反对开源，并且不愿让更多东西变得开源，部分原因是他们希望减缓竞争对手的发展。所以，这两方面的因素都在发挥作用。

### 提问结束

Quick question over there.

## 主持人补充

:::info 主讲者(Eric)似乎已经走了
:::

### 验收能力

I just want to follow up on a comment about, should we still learn to code?
Should we still study English?
Are those going to be useful?
And Eric's replied, yes, like college-educated, high-skilled jobs or tasks are still going to be safe, but everything else that's going to require image editing might not be.

That's kind of like an interesting one.
Maybe we'll talk some more about that in a few minutes, but it is interesting to think about where the AI systems just replace what people are doing versus they complement them.
And in coding right now, it appears that they're not actually that helpful for the really best coders.
They're very helpful for moderately good coders.
But if you don't know anything at all about coding, they're not helpful either.

我想跟进一下刚才关于是否我们还需要学习编程的问题，以及我们是否还应该学习英语。这些技能还会有用吗？Eric的回答是肯定的，他认为拥有大学学历的高技能工作或任务仍然是安全的，但其他涉及图像编辑的工作可能就不太安全了。

这是一个很有趣的问题。也许我们待会儿可以多谈谈这个，但现在思考一下AI系统在某些情况下是完全替代人类的工作，还是在某种程度上补充了人类的工作，这很有趣。就目前的编程情况来看，AI对最顶尖的程序员其实帮助不大，但对中等水平的程序员却非常有帮助。不过如果你完全不懂编程，它也不会对你有任何帮助。

So it's kind of an inverted you.
And you can see why that would be the case, that if you don't even understand the code that they generate right now is often buggy or it isn't exactly right.
So if you can't even interpret and understand what's going on, you can't use it very effectively.
And for now, the very best coders, it appears that the code that is generated isn't at that level, so you get that U shape.
But that means if you don't know any code, you do need to have some in order for it to be useful.

所以，这种情况有点像一个倒U型曲线。你可以理解为什么会这样，因为如果你连AI生成的代码都看不懂，那这些代码通常是有bug的，或者不完全正确。如果你不能解读和理解这些代码，你就无法有效地使用它。而对最顶尖的程序员来说，AI生成的代码显然还达不到他们的水平，所以就形成了这个U型关系。但这意味着，如果你完全不懂代码，你确实需要有一些基础知识才能让它变得有用。

我认为这对于现在很多应用程序来说都是正确的，你需要有一些基本的理解才能最大化它的作用。是否始终如此，这是一个有趣的开放性问题。我在上次课的最后展示了一张幻灯片，上面有0到5级的自动驾驶汽车。其中我们现在可以讨论的一个问题是，如果你将这种类似自动驾驶分级的思维模式应用到经济中的所有任务上，它们会经历什么样的变化？

And I think that's true for a lot of applications right now, that you have to have some basic understanding in order to get the most of it.
I think it's an interesting open question if that's always going to be the case.
I put up at the last class very briefly this slide that had level 0 through 5 autonomous cars.
And one of the things that actually we can talk about now is that I'm trying to sort through is what if you took that paradigm, and you applied it to all tasks in the economy?
Like how many would they go through?

So with autonomous cars, we aren't really at level 5 very much although I don't know how many of you guys have ridden in a Waymo, one of the Waymo cars.
So that one seems pretty good, although Sebastian Thrun, who I rode in it with, says it's just incredibly expensive right now.
They probably lose \$50 to \$100.
He doesn't know he's not there.
He started the program, but he's not there anymore.

我认为目前很多应用程序确实是这样的，你需要有一些基本的理解才能充分发挥它们的作用。但这是否会一直如此，这是一个有趣的开放性问题。我在上次课上很简短地展示了一张幻灯片，上面列出了0到5级的自动驾驶汽车。我们现在可以讨论的问题之一是，如果你把这种范式应用到经济中的所有任务上，它们会经历怎样的变化？

至于自动驾驶汽车，我们还没有真正达到5级的程度，不过我不知道你们中有多少人乘坐过Waymo（谷歌母公司旗下的自动驾驶公司）的汽车。Waymo的表现看起来相当不错，虽然我和Sebastian Thrun一起乘坐时，他提到目前这种技术非常昂贵。他说它们每次可能要亏损50到100美元。不过他自己也不太清楚，因为他已经不在那里工作了。他创立了这个项目，但现在已经离开了。

But just all of the costs of running it, it's not practical.
Maybe it'll get down the curve.
Lidar will get cheaper, but we have a lot of sort of autonomous cars at level 2, 3, even 4, arguably, where humans are still involved.
And you see a lot of other tasks like coding.
I just talked about that.

但是，运营它的所有成本来看，这并不现实。也许成本会随着时间下降，激光雷达会变得更便宜，但我们现在有很多自动驾驶汽车处于2级、3级，甚至4级的水平，可以说在人类仍然参与的情况下运行。你会看到很多其他类似的任务，比如编程，我刚才提到了这一点。

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

### 人机组合最强吗？工人岗位会变多吗？

另一方面，关于国际象棋，那张幻灯片，我之前提到的幻灯片，我谈到了有时被称为“高级国际象棋”或“自由式国际象棋”。当Gary Kasparov在1997年输给Deep Blue后，他发起了一系列比赛，允许人类和机器一起合作。在很长一段时间里，正如我在2012年或2013年的TED演讲中提到的那样，当时人类和机器合作能够战胜Deep Blue或任何国际象棋计算机。所以，最强的国际象棋组合是这种人机结合的形式。但现在情况已经不同了。

像AlphaZero这样的程序，现在根本不需要人类的贡献，人类的参与对这些棋局机器来说甚至是种干扰。所以这经历了从0级，机器什么都做不了，到合作阶段，再到完全自动化的过程，大约花了20年左右。如果有人想做个研究项目，或者你们中有谁现在有想法，可以讨论一下，哪些任务会处于那个“中间区域”？因为那个中间区域对我们人类来说是个不错的地方，在这个区域中，机器帮助我们，但人类在创造价值方面仍然不可或缺。在这个区域中，你可以拥有更高的生产力、更多的财富和表现，但也更可能实现共享繁荣，因为劳动力本质上是分散的，而正如Eric刚才所说，技术和资本则有可能非常集中。你对此有什么看法？

> I was just going to ask kind of a related question.
> He was saying also that we have a 10 year like chip manufacturing.
> Yeah, I was surprised about that.
> And I think what was interesting to me as a labor economist is that it was really like a green flag I've seen in literature and news that, okay, if we're on showing all of this chip manufacturing, isn't that going to create some sort of resurgence in blue collar jobs?
> And I wondered if you had any thoughts about intelligent robotic models or human labor.

我正打算问一个相关的问题。他还说我们有一个10年的芯片制造周期。是的，我对此也感到惊讶。作为一名劳动经济学家，我觉得有趣的是，我在文献和新闻中看到的都是一些绿灯信号，好像说如果我们重振这些芯片制造业，这是否会在蓝领工作中带来某种复兴？我想知道你对智能机器人模型或人类劳动有什么看法。

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

嗯，我觉得这不会有太大的影响，我是说，你们中有多少人参观过芯片制造厂？有人吗？你们中的一些人参观过。在那个制造厂里有多少工人？嗯，我是说，好吧。所以答案是零。

他们不让你进去的原因之一是人类太笨拙、不干净，无法进入。所以整个过程是全自动化的，工厂是封闭的。确实有一些工作需要人工，比如运送物品。如果一个机器人倒下了或者出现了什么问题，他们需要穿上你们可能见过的那种看起来像宇航服的防护服进去，可能调整一下什么，然后再出来，希望没有弄坏什么。所以，这基本上是一个全自动化的工厂。

是的，我不认为这需要很多人工。我认为这并不像是蓝领工作的复兴。实际上，苹果将MacBook的生产迁回德州的原因之一，并不是因为德州的劳动力便宜，而是因为他们实际上不再需要太多人工了。所以，这个生产过程对劳动力的需求相对较少。我认为，美国制造业在产出方面确实在快速增长，但在就业方面并没有增长太多。

### 明年Agent或文本生成模型会迎来一个临界点吗？

> Do you think you have an inflation point coming for agents or text action models in the next year?
>
> 你觉得在明年，Agent或文本生成模型会迎来一个临界点吗？

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

不，不。Eric提到的，我听到的也是类似的看法。其实，他很好地总结了这三个趋势。我以前听说过它们各自的发展趋势，但我觉得将它们结合在一起是非常有意义的。今天早些时候，我在和Andrew Ng交谈，他一直在强调代理人技术，认为它可能会成为2024年的一个浪潮。Andrew也很生动地描述了这一点。就像你们知道的，当你使用大语言模型（LLM）写一篇文章时，它是逐词生成的，整个过程是一气呵成的。

这已经表现得相当不错了。但想象一下，如果你写作时不能使用退格键，也不能先做一个大纲，而是只能直接写下去。现在的代理人会告诉你，第一步是先做一个大纲。

然后，你再填充每一段内容，之后回头检查行文是否流畅。再检查语气是否合适，是否符合目标读者的水平。通过这样不断迭代，你可以写出一篇更好的文章或完成任何任务。这将是一场真正的革命。

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
