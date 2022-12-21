---
title: "A Take on Startups, Value, and User Interface"
draft: true
date: 2022-12-13
tags:
- Product
- Minimalism
- Startups
- User Experience
---

I would like to urge early-stage startup founders to stop investing into, spending time on, putting efforts into **User Inteface**.

This sounds controversial, as it is meant to be thought-provoking. In this little essay I will try to think about the UI and value, and how these look for early-stage startups. To be clear, let's narrow 'early-stage' to mean bootstrapped companies early in the game, on a short runway, still looking that product-market fit. Where resource is scarce and the majority of the hustle is done by the founders.

## My Bias 

I am a software engineer by training, and most of my life I have been creating software. Moreover, majority of it was work-made-for-hire, and also work made for startups.

At [Logicify](https://clutch.co/profile/logicify#summary) we worked a lot with bootstrapped, resource-limited startups. We were mostly engaged as a software vendor, building joint teams with clients on their way to find the fit. While we were closer to tech provider, we often participated on product level, forming a kind of 'synthetic product function' across the founders and our tech folks. 

With this background, you might expect that I should have called for building more good tech to make life easier. 

But I am arguing for exactly the opposite case - ditch the UI, or at least de-prioritize it. 

# Business and Value
![Business and Value Relationship](customer-value.svg)

This is how I understand the concept of business. Company creates some value for the customer. Customer accesses that value, and is happy to pay something in exchange (money, or revenue). This creates economic draft which lets you build things, expand, take money out and so on. Very high level, is not it? 

* For insurance business, value is in risk management and often peace of mind. Customer is happy to pay premium for his health insurance knowing they will not stay alone if they break their leg. 
* For a coffee shop, value is in the coffee itself and its effect. Customers are happy to refresh and enjoy their coffee, and are exchanging money for a cup. They are accessing this value via interaction with the barista (which might bear value in itself, like a friendly nice chat)


# Early Stage Startups

To survive, early-stage startups have to concentrate on a single thing: proving their idea and model. Also, everything is scarce: there is no extra money to spend, there is no extra time to loiter or spend on the 'comfy and nice' work instead of the 'grind-to-be-done-now', there is very little margin for error. 

It is founders against the world, competition, and time. 

I view this as a founders trying to demonstrate value provided to the customers. If they succeed - there is value created, customers recognize it, and are happy to commit or even pay for it, this is a good sign towards traction. 

Every time, starting a new task or switching to something else, founders should ask themselves: 'Is this the single most impactful thing I can do right now? Is the resource spend/return ratio maximal? Does this get me at least one stop closer to getting the validation?'

The value has to be accessed by user somehow, however. Orders need to be placed, problems solved, shipments shipped. 

# Tech Startups and Value
![Business and Value Relationship](customer-user-interface-value.svg)

- Customer --> UI --> Value

In the  technology startups, users often access the value via the interface: smartphone apps, web applications, desktop, even hardware. Remember that Pokémon Go Plus - a button on a leash you would press when in vicinity of, err, a Pokémon, to catch it?

User Interface helps user access the value. It is, however, located between the user and the value. 

Is it enabler or a blocker? If it limits the access to value, or gives a bad impression, it makes customers unhappy. Broken flows, downtimes, incomplete features, makes them not able ot access core value. They view the value through a 'window' of UI oftentimes skipping the 'extra' - help, marketing materials, and so on. 

Have you ever been in the situation when you want to try some new tech product, and it does not work? Or when it does work but is subpar - a bit more sluggish than it should be, or glitchy in design or behavior, and so on?  Did you project that on the value itself?

# User Interface

Going further, here is a sad truth: good UI is very expensive to build, and it takes time. It requires some creative and rigorous processes, QA and user testing, many iterations, performance tuning, extensive checks on all supported platforms, observability and metrics built in and so on and so on. It is a big complex thing, and not so many businesses have done it right despite loads of money piped towards UI.

UI is also 'wide' in terms of platforms to support, and full of tradeoffs. Mobile app? Need two codebases for sleek experience, Android and iOS. Web app? Let's dive into cross-browser support.

UI quality is, however, mostly a hygienic factor for users. They might get irritated and leave if it is bad. But they would only consider UI as a decision factor if their core value is same or higher than competition.  

Think of currency exchange service: the app might be super-convenient and beautiful, but if the exchange rate is much worse, not many users would flow there.

Now, there are some products which are UI centric and whose core value is touching upon that - graphical and architectural design systems, competitors on the dense markets who chose to compete with UI, and the like.  For all other cases, very good UI would just be a seamless factor. Like in currency exchange case; the value is in money saved.

# User Interface as an Obstacle: Example 

Many people with software engineering background (me included) often tend to think in terms of software, products and so on, and not in terms of the value for the customer. But let's look at these examples (probably a little exaggerated): 

- You do not want to be writing and sending emails, even less so checking. You want to be able to get messages and information across conveniently.  
- When boiling your pasta, you do not want to be spinning number wheels or keying in data for a timer app. You just want your pasta al-dente, or at least a notification when it is so you can drain it. 
- When buying insurance, you probably do not want to fill in a ton of forms and fields, and make a hundred of micro-decisions with tradeoffs. You would rather have a simple, understandable subscription to roll in to (preferable single click with G Payment)

You see where this is going? For each of these cases, users often find a way around. My workarounds: 

- Emails and communications: Sometimes it is much easier give someone a call; saves 100 emails back and force. Each of us has been in a situation when 'enough of this bouncegame I am dialing in'.  
- Pasta-boiling: Physical, pomodoro-style timer, or 'Hey Siri, timer 10 minutes' makes it no frills
- Subscription: If things are complex with subscription, I would often call an account manager or a broker to guide me through, and put the cognitive load on them. I am going to buy a service from company, and they know their product and service line better, why not?

This is why customer support is still a big thing. Whenever I'm feeling friction with the tech, I'd rather early switch to a customer support. I'd switch back to tech if support quality is low and wait is long. 

# Product-Market Fit Startups Again

We looked at two separate things: 

* UI is expensive and long to build, and even more so to build well. Bad UI might obscure access to value and complicate validation. 
* Early stage startups need the cleanest and simplest access to the value they provide to learn from early customer interactions. They are also very limited in resource. 

As a startup, you would need to divert substantial amount of resource from the core value, and also create a subpar experience for the customers (because you would only have enough resource later in the game). This also adds tech burden: UI needs support and change just as any other code. All this activity is falling way below the optimal impact filter. 

But what can we do? Is there a way to build a tech startup without an interface? 

This is a thought-provoking piece. I am not giving away any answers here, just asking you to think about this topic. 

* What can be done to limit the spend on UI? 
* Can something pre-existing be used? 
* Can you start with a typeform, email and phone service to test the hypothesis, and build only when you see there is need, scale, or hype?



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
