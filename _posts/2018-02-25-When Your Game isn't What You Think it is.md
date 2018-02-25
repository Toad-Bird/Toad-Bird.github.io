---
published: false
---
The project folder for Tumblefolk Tempest has always had the name “tornado”. This is a reference to a relatively minor mechanism in the game that we once thought to be its central feature. 

A tornado occurs when the player makes a chain of wind arrows loop back onto itself. It's effect is to rotate Tumblefolk around the chain, causing each Tumble to replace the one ahead of it.

![Tornado gif]({{site.baseurl}}/images/tornadoGIF4.gif)

This is mostly just a neat edge case behavior that can occasionally lead to a cool move. But for a long time all of our design decisions revolved around making tornados more interesting.

- Tumblefolk had resources they would drop during tornadoes.

- Ability tiles had to be recharged by tumblefolk that landed next to them after tornadoes.

- We had special units called “storm cores" which were created by encircling a portal with a tornado.

- Storm cores could only be moved by tornadoes.

- We tried giving the player 1 tornado per turn instead of 1 tether per turn.

- We had tornadoes recharge the portal.

- We had tornadoes cooldown ability tiles.

Most of these mechanisms either made the gameplay awkward, were ignored by the player, or just flatly rewarded the player for mindless tornadoes. Tornadoes just take too long to set up and are too hard to “aim” for them to be the player's primary way of getting things done. 

Instead the dominant way of doing things in Tumblefolk Tempest has always been what we thought was a secondary mechanism: moving things with wind tethers. This realization was painful at first because we had convinced ourselves that tornadoes were the most important part of the game, but now we're ready to embrace wind tethers as the real core mechanism.

## What's Next

Tornadoes are a tool for instantaneously moving Tumblefolk, whereas tethers are a tool for leading Tumblefolk along a path. So now that we know tethers matter more than tornadoes we plan to deemphasize the destination of the Tumblefolk, and emphasize the paths they take and the shape of their wind tethers. 

For example, we are changing ability tiles so that they can be activated at any time and will affect any wind chain going over them. This means that the shape of the wind tethers determines which abilities can affect them.

We're also introducing a new type of resource called seeds. Seeds will sit on a space until a Tumblefolk hits them. Depending on the combination of seed type and Tumblefolk tribe involved in the collision, the seed will either be added to the player's inventory or be destroyed. This means that the paths Tumblefolk take to their destinations determine which resources get collected.

---

*If you want to hear how these changes work out [follow us on Twitter](https://twitter.com/bird_toad)*

