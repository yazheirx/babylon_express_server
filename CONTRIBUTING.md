# Contributing to Babylon Express Server

## Golden rules

**Babylon Express Server** is built upon 3 golden rules:

1. You cannot add code that will break backward compatibility
2. You cannot add code that will slow down the how quickly the project can be put to use
3. You cannot add code that will make things complex to use

### Backward compatibility

The first golden rule is a really important one because we want new Babylon.js users to have a simple way of using Babylon.js in a NodeJS environment. And when we need to introduce something that will break backward compatibility, we know that it will imply more work for our customers to switch to a new version. So even if something could be simpler to do by breaking the backward compatibility, we will not do it (exceptions may apply of course if there is a problem with performance or if this is related to a bug).

### Speed to Start

When wanting to explore a new idea it shoudl only take minutes, or if we can seconds, to get the foundation needed to start coding.

### Simplicity

A developer should be able to quickly and easily setup this foundation. 

Simplicity and a low barrier to entry are must-have features. If you have any second thoughts about the complexity of a design, it is almost always much better to cut the feature from the current release and spend more time to get the design right for the next release. 

You can always add to an API, you cannot ever remove anything from one. If the design does not feel right, and you ship it anyway, you are likely to regret having done so.

## Github issues

Please use the Github issues (after discussing them on the forum) **only** for:
- Bugs
- Feature requests

We will try to enforce these rules as we consider the forum is a better place for discussions and learnings.

## Pull requests

TBD
