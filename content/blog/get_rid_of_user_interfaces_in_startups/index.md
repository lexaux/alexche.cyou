---
title: "Early-Stage Startups, Stop Building UI!"
draft: true
date: 2022-12-13
tags:
- Product
- Minimalism
- Startups
- User Experience
---

I would like to urge early-stage startup founders to stop investing into, spending time on, putting efforts into **User Inteface**.

This sounds controversial, as it is meant to be thought-provoking. In this little essay I will try to think about the UI and value, and how this situation might look for early-stage startups. To be clear, let's narrow 'early-stage' to mean bootstrapped companies early in the game, on a short runway, still finding that product-market fit. Where resource is scarce and the majority of the hustle is done by the founders.

## My Bias 

I am a software engineer by training, and most of my life I have been creating software. Moreover, majority of it was work-made-for-hire, and also work made for startups.

At [Logicify](https://clutch.co/profile/logicify#summary) times we worked a lot with bootstrapped, resource-limited startups. We were mostly engaged as a software vendor, building joint teams with clients on their way to find the fit. While we were closer to tech provider, we often participated on product level, forming a kind of 'synthetic product function' across the founders and our tech folks. 

With this background, you might expect that I should have called for building more good tech to make life easier. But I am arguing for exactly the opposite case -- ditch the UI, or at least de-prioritize it. 

# Business and Value
![Business and Value Relationship](customer-value.svg)

This is how I understand the business. Company creates some value for the user. User accesses that value, and is happy to pay something in exchange (money, or revenue). Very high level, is it? 

Key here is how the customer gets access to the value:

* For insurance business, value is in risk management and often peace of mind. User is happy to pay premium for his health insurance knowing they will not stay alone if something big happens. 
* For a coffee shop, value is in the coffee itself and its effect. Customers are happy to get refreshed and enjoy their coffee, and are exchanging money for cup. They are accessing this value via interaction with the barista (which might bear value in itself)

However, means of how one can access the value, or interface, is also very important. Two cases here:

### Case: Currency Exchange

I am in Toronto, Canada now. In addition to banks changing money, there are a few companies providing this service. Core value is money - they just do it with better rates. There are two big players on this market of FX companies. Both of them provide same type of value but in a very different way. First is more traditional - you book transactions via call, speak to your account manager, you don't have an app. Second is more modern: self-registration, automated KYC with ID check, mobile app to exchange money.

Again, the core value they provide is same: better rates than banks. I am buying a car for cash, these guys guys give me CAD $1000 out of thin air when compared to high street bank, quite an incentive to use them? 

But the interface can also impact value itself. 

Naturally, I would prefer the self-service, app approach. You can book transactions on the go. You can see how it progresses. There is no need to wait on the line to get to speak to your account manager. 

There are, however, benefits of old-fashioned service as well. You can negotiate (always when speaking with a live person!). A friend of mine, client of such old-fashioned FX firm, got an advice from his account manager to wait for a week with exchange, as regulator was expected to raise base rate and he would have gotten better off, if not in a rush. Something which would be hard to do with an app, right? 

### Case: Smart Home

Smart home can be approached in different ways. It certainly has a potential to provide value to the customer: from basic things like controlling your blinds with a voice command to dimming the light from your phone to regular scheduled automations. 

There is a myriad of approaches of interfacing with smart home: tablet panels, voice commands and feedback, physical buttons, smartphone app controls and so on. If you look at the ads of smart home appliances, oftentimes it is it - there are pictures of nice apps with lists and buttons and icons and so on. 

There is, however, another interface which is often omitted. Lack of it. Just think about it: 

* User does not want to flip a switch. They want their light to be on to read in bed before they sleep.
* User does not want to rotate a virtual knob to dim light (oh my!). They want to be able to find their way to toilet at night without being blinded. 
* User does not want to constantly tick the thermostat up and down. They just want to feel comfy. 

And the list goes on. Core value does not demand an interface. It is just that we do not have a better means than put this on to the user, and get their inputs from interface, to provide that. 

This thought struck me when Dmitry Berezovsky was showcasing me his smart home, what would then become Jointbox. It was full of automations, very specific to his lifestyle. And eventually it just worked in such a way that he did not have to pull out his phone all the time to control bits and pieces.

# Tech Startups and Value
![Business and Value Relationship](customer-user-interface-value.svg)


- Customer --> UI --> Value

For technology startups, we all got used to users accessing the value via interfaces: smartphone apps, web applications, desktop, hardware and so on. Just remember that Pokémon Go Plus - a button on a leash you would press when in vicinity of, err, a Pokémon, to catch it. 

But is this another thing, User Interface, which is in between the user and the value. Even with its visual position, is it enabler or a blocker? If it limits the access to value, or gives a bad impression, it makes customers unhappy. They would view the value through a hole of UI oftentimes skipping the 'extra' - help, marketing materials, and so on. 

Have you ever been in the situation when you want to try some new tech product, and it does not work? Or when it does work but is subpar - a bit more sluggish than it should be, or glitchy in design or behavior, and so on?  Did you project that on the value itself?

# User Interface

Now is that sad truth: good UI is very expensive to build, and it takes time. It some creative and rigorous processes, QA and user testing, many iterations, performance tuning, extensive checks on all supported platforms, observability and metrics built in and so on and so on. 

UI is also wide in terms of platforms to support, and full of tradeoffs. Mobile app? Need two codebases for sleek experience, Android and iOS. Web app? Let's dive into cross-browser support.

UI quality is mostly a hygienic factor for users. They might get irritated and leave if it is bad. But it is only when the UI is core value when they would be drawn towards the product.Now, there are some products which are UI centric and whose core value is touching upon that - graphical and architectural design systems, competitors on the dense markets who chose to compete with UI, and the like.  For all other cases, very good UI would just be a seamless factor. Like in currency exchange case; the value is in money saved.

# Early stage: product-market fit search

- Goal is to validate that there is enough traction to build further business
- Founders can stretch to cover the gaps. Automated signups might not be needed. 
- Runway is spent on research and learning from the market. 
- Lean: runway is smnall, resource is scarce, force to be effective and do only what's important. 
- What is the most impactful thing one can do today? 


# User Interface as an Obstacle: Example 

Let this just soak in: 

- You do not want to be writing and sending emails, even less so checking. You want to be able to get messages and information across conveniently.  
- When boiling your pasta, you do not want to be spinning number wheels or keying in data. You just want your pasta al-dente, or at least a notification when it is so you can drain it. 
- You probably do not want to fill in a ton of forms and fields, and make a ton of micro-decisions with tradeoffs. You would rather have a simple, understandable subscription to roll in to (preferable single click with G Payment)

You see where this is going? For each of these cases, users often find a way around. I am sharing my workarounds:

- Emails and communications: Sometimes it is much easier to setup a c- Sometimes it is much easier to setup a call, saves 100 emails back and force. Each of us has been in a situation when 'enough of this bouncegame'.  
- Pasta-boiling: Physical, pomodoro-style timer, or 'Hey Siri, timer 10 minutes' makes pasta-boiling easier
- Subscription: If things are complex with subscription, I would often call someone to guide me through, and put the cognitive load on them. I am going to buy a service from company, and they know their product and service line better, why not?

This is why customer support is still a big thing. Whenever I'm feeling friction with the tech, I'd rather early switch to a customer support. I'd switch back to tech if support quality is low and wait is long. 

# Product-Market Fit Startups Again 

Putting the above into the context of lean, resource-stranded startup in product-market fit phase, things become even worse. 

So, as a startup, you would need to divert substantial amount of resource from the core value, and also create a subpar experience for the customers. This also complicates things in a time domain: UI needs support and change just as any other code. All this activity is falling way below the optimal impact/investment treshold. 

But what can we do? Is there a way to build a tech startup without an interface? 

This is a thought-provoking essay. I am not giving away any answers here, just asking you to think about this topic. What can be done to limit the spend on UI? Can something pre-existing be used? Can you start with a typeform, email and phone service to test the hypothesis?
