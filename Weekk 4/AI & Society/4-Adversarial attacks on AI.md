# Adversarial attacks on AI

Even though modern AI is incredibly powerful, one of the limitations of modern AI technologies especially deep learning is that sometimes it can be fooled. In particular, modern AI systems are sometimes susceptible to adversarial attacks, if someone else sets out deliberately to fool your AI system.

Let's take a look. Let's say you give an AI system, this picture of a bird and ask it to classify it. The AI system outputs that this is a hummingbird. But lets we make a minor perturbation to this image. By minor perturbation, I mean to change the pixel values just a little bit and almost imperceptible change to most people. The same AI system then says this is instead a hammer. Now, to a person you might say, "How is this even possible, the picture on the right looks almost identical to the picture on the left?" In fact, the changes are almost imperceptible to the human eye. But an AI system sees the world very differently than you and I do.

So, it is susceptible to if an adversary makes changes to a picture that could be imperceptible to you and me but their results in fooling the AI into thinking this picture is something totally different. We call this an adversarial attack on an AI system. In computer security, an attack against a secure system means an attempt to make it do something other than what it was intended to do. In the same way, an adversarial attack on an AI system is an attempt to make it do something other than what it was intended to do, such as trying to fool it into outputting incorrect classifications. Here's another example. Here's a picture of a hare with just a minor perturbation or a small change to the pixel values, AI instead says this is a desk. The fact that computers see pictures differently than humans do, gives it advantages and disadvantages.

For example, computer systems are much better than you and me at reading barcodes and QR codes. But the way that deep learning systems work also opens us up to these particular forms of attack which no human would be fooled by. Today, AI is being used to filter out spam, to try to filter out hate speech, and attacks like these will diminish the effectiveness of such filters. Now, the attacks on this slide require the ability to modify an image directly. For example, a spammer might directly modify an image before they tried to upload it to a website or send it in an email. There are some attacks that work by changing the physical world as well. For example, a group at Carnegie Mellon University was able to design a funky pair of glasses like this. So, that when does man wears this pair of glasses, he can fool an AI system into thinking that he is actress Milla Jovovich.

I think it's remarkable that just wearing a pair of glasses like this can fool an AI system into thinking that this man is a well-known actress. A different group of researchers from UC Berkeley, University of Michigan and other universities, showed that if you affix stickers like these onto a stop sign, you can fool an AI system into not seeing the stop sign at all. It thinks there's something else there other than a stop sign. One interesting thing about this example is that it looks like the stop sign just had some graffiti applied on top of it. Most humans will still see this as a stop sign quite easily. But if you have a computer vision system built into a self-driving car for example, it would be really unfortunate if the car doesn't see the stop sign anymore, because of these stickers applied on top of it.

One last example, this one from a group of researchers at Google, is if you show a AI system this picture, it will say this is a banana. But what the researchers did was design a sticker, so that if you place it into the scene, it misclassifies this banana. Let me show you the section that the researchers made. Shown on the left is the classifier input and shown on the right is the classifier output, where it thinks is very likely a banana and maybe there's a small chance is a slug. Looks okay. Let's see what happens when you put a sticker or put a small patch into the scene. When the sticker is placed in the scene, the AI system now is almost certain that this picture is a picture of a toaster.

One interesting aspect of this work is that the authors of this paper cited at the bottom of this slide, actually published in their paper a picture of their sticker. So, that anyone in the world could hypothetically download their paper, print out the sticker, and stick it somewhere if they want to fool an AI system into thinking there's a toaster where there isn't. Now, I do not support anyone attacking AI systems to fool them into thinking that toasters were there or none, but this shows unfortunately how the ease with which one could hypothetically attack these AI systems. What can we do to defend against these adversarial attacks? Fortunately, the AI world has been working on new technologies to make them harder to attack.

The defenses tend to be very technical, but there are ways of modifying neural networks and other AI systems to make them somewhat harder to attack. One downside is that these defenses do incur some cost. For example, the AI system may run a little bit slower. But this is an area of ongoing research and we're far from heavy adversarial defenses that seem good enough for all of the important applications that we want to apply AI to. For many AI systems, there may be no incentive for anyone to try to attack it. For example, if you're running a automatic visual inspection system to check if coffee mugs have scratches in your factory. Maybe not that many people who have any incentive to try to fool your system into thinking a scratched coffee mug doesn't have a scratch on it.

But there are going to be AI applications where there will be attacks as well. For those applications, I think that similar to spam versus anti-spam, where spammers are trying to get the spam email through and spam filters are trying to stop them. I think there will be applications where we will be in an arms race, as a AI community is building up defenses and there is a community of attackers trying to fool our defenses. In my experience building AI systems, one of the few times I felt I was at total war with someone else was when I was leading anti-fraud teams fighting against forces. There is ,unfortunately, some amount of fraud on the Internet where people are trying to steal money and payments systems or create fraudulent accounts.

The times I worked on anti-fraud systems was one of the few times that it really felt like a zero-sum game, had an adversary, we would put up a defense and they would react. They would launch an attack, my teams had to react. Sometimes even hours to defend ourselves. So, I think over the next few years even as AI technologies evolves, there will be verticals like that, like spam, like fraud where teams will be at war. In what may feel like a zero-sum game against adversaries. Having said that, I also don't want to over-hype the potential damage for adversarial AI systems.

It is really important for some applications. But there are also plenty of AI applications which are less likely to be subject to adversarial attacks. Now, in addition to adversarial attacks, AI unfortunately can also be used for some adverse or some negative use cases. Let's take a look at some of them in the next section as well as what we should do to address them. Let's go on to the next section.