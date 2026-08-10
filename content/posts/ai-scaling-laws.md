+++
date = '2026-07-20T20:37:10+08:00'
draft = false
title = "A Skeptic's Opinion on Neural Scaling Laws"
+++

> A plurality is not to be posited without necessity
>
> — William of Ockham

I was recently reminded of the [AI scaling problem](https://www.theatlantic.com/technology/2026/07/generative-ai-engineering-disaster/687901/), which is an argument against the premise that AI will continuously get better. Unless there is a major improvement in architecture, it is unlikely that AI will progress meaningfully (let alone revolutionarily) in the foreseeable future.

This might be a hot take, and certainly more of an educated guess rather than a theory-backed one, but perhaps it is time to rethink our approach in AI architecture. I am always reminded of [Occam's razor](https://en.wikipedia.org/wiki/Occam's_razor) whenever I think about *the* prominent LLM architecture used today, i.e., the [Transformer](https://arxiv.org/pdf/1706.03762) model. Of course, I lack the rigorous (and incredibly difficult) understanding of the most cutting-edge AI skillsets and knowledge. However, the entire architecture just seems overly convoluted with its massive scale. Not even leading AI researchers can concretely explain the precise efficacy of each transformer block. Although active research is being done on mechanistic interpretability, the landscape of this field is immature at best.

Because we still lack an understanding of the exact mechanisms behind the modern Transformer architecture, it can be said that we are currently 'blindly' improving AI, i.e., guessing which variables work and scaling them up infinitely. And yet it has also been shown by the [Neural Scaling Laws](https://arxiv.org/pdf/2001.08361) that this variable, namely the number of parameters, shows diminishing gains in terms of performance, but scales *exponentially* in terms of energy and environmental costs. The question is, how much economic and environmental damage are stakeholders willing to endure for a marginal gain in performance? OpenAI’s [GPT-4 (2023)](https://arxiv.org/pdf/2303.08774) is estimated to have cost over [$100M and over 50 gigawatt-hours](https://www.technologyreview.com/2025/05/20/1116327/ai-energy-usage-climate-footprint-big-tech/) to train—enough to power San Francisco for three days. With frontier models getting larger and larger, this number is expected to be much more significant today and will continue to increase in the future.

Another problem is—as is currently trending in the news (See [Anthropic's $965B valuation](https://www.anthropic.com/news/series-h))—the main companies involved in improving AI are now Wall Street-backed trillion dollar companies. They have less of an incentive to actually completely rework their architecture as valuations keep going higher and higher. And why should they? They can keep exponentially increasing their parameters to keep up with the diminishing gains, then tell the shareholders that they have now achieved an $x\%$ improvement over last-gen models. Yes, Big Tech is still actively conducting research on novel AI architectures, but AI research is notoriously expensive and time-consuming (it costs hundreds of millions of dollars to train a frontier model!). What about its responsibility to its all-powerful shareholders? Unfortunately, the AI industry is currently in its transitionary phase from its startup roots into a more mature industry, and with that comes more bureaucracy, regulations, and slower growth.

Therefore, while I am not fully convinced of alternative models yet, such as [LeCun's JEPA model](https://arxiv.org/pdf/2301.08243), I also do not think that the current LLM architecture will lead us to AGI anytime soon.
