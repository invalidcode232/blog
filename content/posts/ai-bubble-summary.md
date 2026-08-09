+++
date = '2026-08-09T21:08:01+08:00'
draft = false
title = 'My Notes on Speculative Growth and the AI “Bubble”'
+++

_Original reading [here](https://economics.mit.edu/sites/default/files/2026-07/speculative_growth_AI_public.pdf)._

_My notes here are a massive oversimplification with a lot of content and details cut off. These are just what I, someone with no economics background, find interesting._

# Assumptions

## Productivity of AI

> AI capital performs tasks previously done by labor. As it accumulates, <u>productive capacity expands</u> and income shifts toward capital owners, who have a stronger saving motive.

This only holds true if AI does actually expand ‘productive capacity,’ but then I suppose if there is no productivity increase then the entire mechanism, which is mainly economic, falls apart.
- If AI usefulness (represented as $\gamma$) is insufficient, then the **entire three-state system fails**.

## Current Bubble State

We establish that current capitalist *belief* $x_0$ is higher than its actual *value*. 

Thus it is assumed that $x_t < x_0$, and that $x_t$ will continue to diminish until it reaches a certain point which I will discuss later. 

# The Three State System

The wealth of a capitalist is determined by:
$$
W=qK
$$
Where:
- $q$ (aka Tobin’s $q$) represents the *value* (or price) of the hardware installed:
    - The price of an item is determined by the actual cost (or more specifically, *replacement cost* $\bar{q}$), the *utility* $d(K)$, *and the future beliefs of capitalists* $x$.
- $K$ represents the actual amount of capital.
    - In the case of AI companies, this means (mostly) the amount of physical AI hardware infrastructure installed.

> As a side note, bubbles happen if there is a large discrepancy between replacement cost $\bar{q}$ and capitalist’s belief $x$. 
> That is, if the **actual** cost of an item is far lower than what the capitalist’s think it actually is, a bubble occurs.

## Proposition

Let AI physical hardware infrastructure be the **capital** $K$, the paper’s central argument is that there are three states, determined by how much the current installed $K$ is:
- $K^L$: Where $K$ is not sufficient enough and thus capitalists will have less wealth ($W=qK$), hence they will demand **higher interest** to sustain their investments.
    - They require higher interest because capitalists that have less wealth have a higher _marginal propensity_ to consume i.e. they would rather buy (consume) now than to invest. 
- $K^M$: Threshold between $K^L$ and $K^H$.
- $K^H$: Where enough capital is deployed such that capitalists’ wealth is high enough to lower interest rate demands.
    - Conversely to earlier, if a capitalist is wealthier, then they would have a higher tendency to save.

# Arrival and Exit Time

We define two time periods:
- $\tau_V$ is known as the **arrival time**: represents the first time $t$ where capital is enough to be self-sufficient i.e. *Rational high-capital continuation*.
- $\tau_*$ is known as the **exit time**: represents the first time $t$ where the fading belief becomes too small to sustain required capital growth to pass the $K^M$ threshold.

We previously defined capitalist belief $x$, and how $x_t<x_0$, and how it will continually diminish until a certain point is reached.

With the two time periods defined in this section, $x_t$ will *continuously diminish until* $t\geq\tau_V$.

The rate in which $x$ diminishes $\dot{x}$ is governed by learning gain $h_t$:

$$
\dot{x}_t=-h_tx_t
$$

Learning gain is the market's reaction 'speed' to the latest news.
- In our assumption that AI is indeed a bubble, we therefore also assume that these news will generally lead capitalists to believe that AI is overvalued, and lower their confidence.
- Thus with $h_t$ is directly proportional to $\dot{x}_t$.

To conclude:
- The bubble will burst if $\tau_*<\tau_V$.
- And will survive if $\tau_V<\tau_*$.

# Capital Growth

## Growth Rate

$$
\frac{\dot{K}_t}{K_t}=\psi\log{q_t}-\delta
$$
Where:
- Valuation ($q_t$): Higher optimism $x_t$ drives up higher $q_t$.
- Depreciation ($\delta$): Hardware obsolete, wear-and-tear and other factors that ‘drags’ down growth.
- Adjustment sensitivity ($\psi$): How fast firms react to valuation (and when it increases/decreases).
    - Some cases, even more money cannot solve instantly!
    - Such as manpower/land requirements, or legal restrictions, organisational management, etc.

## Escape Threshold


$$
K^M=\frac{1}{\theta\bar{q}}\left[\frac{\bar{q}\rho}{d_{\text{flat}}-\bar{q}\delta}-1\right]
$$

In short, this ‘escape’ threshold is determined by:
- **Wealth-Saving Motive ($\theta$):** How much more capitalists save as they get richer. A stronger motive (higher *θ*) lowers the threshold, making escape velocity easier to reach.
- **AI Productivity ($d_\text{flat}$)**: The dividend rate during the buildout. Higher productivity makes the transition more affordable, lowering the required threshold.
- **The Cost of Capital ($\bar{q},\rho,\delta$)**: Higher interest rates ($\rho$), faster depreciation ($\delta$), or higher replacement costs $\bar{q}$ push the threshold further away, requiring more belief to get there.

### Wealth-Saving Motive $\theta$

Wealthier individuals tend to save more than less wealthy ones. 

- This economic assumption is mostly modelled under the ***Wealth-In-Utility*** framework, where wealthy individuals derive pleasure from owning money.  
- Thus, lower interest rates are observed in countries/regions where there is a high concentration of wealthy individuals (and therefore also high wealth inequality).
	- Since they control most of the economy, their tendency to save will also majorly increase $\theta$.
- Furthermore, individuals that are wealthy sometimes may not be able to spend all their wealth even if they want to.

# Conclusion

While the paper operates under the *assumption* that AI is currently in a bubble, it argues that the bubble *can be* beneficial:
- This happens because when investor belief $x$ is high, which drives up overall wealth, and higher wealth can then be used to increase capital $K$.
- Once $K$ is sufficiently high, then *even if* the bubble pops, the existing capital it has already accumulated can make up for it.

The paper also lists down the various factors in capital growth as well as conditions for mitigating the impending AI bubble.

## What I can use this for

Analysing if/when the AI bubble pops (and whether or not the costs will be great) by looking at the ***individual factors*** affecting each key variable.

- Is the market currently optimistic?
    - How are people responding to news? Are the news heavy-hitting? (e.g. wars, new AI models, etc)
- How do local regulations affect firm growth (e.g. $\psi$)
    - e.g. immigration laws affecting talent hiring.
- How effective is AI growth? And the *trend* of AI productivity growth?

