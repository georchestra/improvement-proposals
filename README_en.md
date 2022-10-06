# geOrchestra Improvement Proposals

## Principes

One of the PSC roles is to make decisions regarding project management. This can include:

- community animation
- communication
- modifications to the codebase having a significant impact on a large share of the community, or affecting backwards compatibility, or affecting compatibility with third party products
- how contribution to the codebase works
- how the PSC works

The PSC is made of individuals involved in the project. Those individuals dont represent their employer or any other entity. An odd amount of members facilitates the voting process.


## Process

1. Anyone can propose a GIP (GeOrchestra Improvement Proposal), be it as an individual or an entity. The GIP has to be redacted by filing an issue in this repository - in the native' speaker language - and posted on the community's mailing-list (georchestra at georchestra.org). If that isnt in english, an english translation has to be provided.


2. To make it easier to examinate and adopt the GIP, it is preferred that the GIP has the following structure:
  - aim
  - expected benefits for the community
  - how it will be implemented
  - potential risks, and ways to work around them


3. Anyone is welcome to examine the GIP, ask questions, propose modifications on github or on the mailing list. The individual who proposed the GIP can account for those modifications by modifying the GIP in the issue tracker - This way modifications are tracked.


4. When the individual thinks the GIP is ready for review, they ask the PSC to examine it. The PSC then announces on the community's mailing-list that a voting process has started.


5. Every PSC member has 15 days (360 hours starting at the voting process announce) to vote. To do so, they comment on the issue tracker with:

  - `+1` : the PSC member supports the GIP
  - `+0` : mildly for, with positive support
  - `0` : mildly for
  - `-0` : mildly against, with negative support
  - `-1` : against, with detailed motives


6. A vote is definitive.


7. The complete voting process is archived on the issue tracker and stays public.


8. At the end of the period, PSC members who havent voted automatically vote with a `+0`.


9. If all the PSC members have voted, the voting period ends immediately.


10. Every PSC member can ask for a 15 days extension period for the voting period, as long as the period isnt over. The voting period can only be extended once.


11. Every PSC member that votes `-1` against a GIP must publicly explain the reasons of its vote.


12. If the GIP gets less that 30% of the PSC headcount `+1` votes, and if it gets no `-1`, then the GIP is **accepted**.


13. If the GIP gets at least 30% `+1` votes AND one or more `-1`, then it is **pending**. Every PSC member having voted `-1` must propose within two months an alternative making the GIP acceptable for them. The GIP's proponent is then free to modify its proposal then ask for a new voting process. If the PSC member having voted `-1` dont propose an alternative making the GIP acceptable for them, then the GIP is **accepted**.


14. No GIP breaking the manifesto can be accepted. If such a GIP is proposed, PSC members dont have to provide an alternative.


15. A GIP cant be proposed more than three times. If the GIP is rejected three times, or if it isnt reproposed, then the GIP is refused.
