---

layout: post

title: "Startup #1 - Please Remind Me "

feature-img: "https://res.cloudinary.com/cinemakers/image/upload/v1543291720/screely-1542768203102.png"

author: "Ronald Langeveld"

---

I'm currently in Chiang Mai, Thailand. When I left Korea late 2016, I promised myself to be back on this continent (even if it's just for a bit) in less than 2 years. And here I am 22 months later, in Thailand of all places. 

One of the reason's I chose Chiang Mai is due to the large influx of remote workers and startup founders from all around the world living in the city and I knew I'd be having some mates here so it was a pretty obvious choice.

After a few months of freelancing and improving my coding skills, I setup a new challenge for myself whilst I'm in Chiang Mai. I give myself 2 weeks to build and ship a product. While I probably won't launch something every 2 weeks, I will challenge myself with at least a few 2 week challenges over the next few months to force myself. 

For the first startup, I decided to partially scratch a my own itch, as well as building an idea that a family friend of ours hinted before.

It took slightly longer than 2 weeks from the first line of code to launching - or about 52 hours coding time according to [Wakatime.](https://wakatime.com) 

Today I'm launching my first little product, [Please Remind Me](https://www.pleaseremindme.xyz). 

## The Problem
I'm generally quite bad at remembering things. And personally, just setting a Siri reminder isn't effective at all. I tend to kill the reminder and then forget about it again seconds later. Or I tend to factory reset my phone quite often so the reminder goes with that. I really need either an email reminder on the day I need to be reminded and a way to remind other people close to me. I can't rely on myself to remember.

## The Solution
[Please Remind Me](https://www.pleaseremindme.xyz). A simple and easy to use reminder management system that allows you to automate reminder emails to yourself and whoever else you want to be reminded. You simply create a new reminder, write what you want to be reminded about, set a date when you would like to be reminded and it will automatically send on that day. 
So now, if I set a reminder and include my brother's email addresses we will not forget Mothers Day next year. 
Simple example, but this is intended to be used with even more important things that you don't think about everyday, like being reminded before your passport expires, car license, bills that needs to be paid in time, etc.

## The Tech

[Sendgrid](https://sendgrid.com)  is for sending emails.

[Bulma](https://bulma.io/)  is used as the css framework.

[Django](https://www.djangoproject.com)  is used as the web framework, along with Python 3.7

[Vultr](https://vultr.com)  is my VPS host of choice. Running Ubuntu 18.04 LTS.

[Paddle](https://paddle.com) is my payment processor. Stripe would've been the ideal solution, but unfortunately it's not supported in South Africa yet.


## Business Model
Please remind me isn't free, but I've done my best to keep it as cheap as possible, yet with the added value of not forgetting important things.
It's a very simple MVP at the moment but will continuously improve it. 

## Future
At the moment we only support Email reminders but will be implementing WhatsApp, Telegram and SMS reminders soon.
