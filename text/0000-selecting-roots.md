- Start Date: 2021-9-26
- RFC PR: (leave this empty)
- Svelte Issue: (leave this empty)

# Selecting Roots

## Summary

This RFC proposes a new feature that allows you to select what is the designated root of a svelte component.

```
<svelte:root>
</svelte:root>
```

> One paragraph explanation of the feature.

## Motivation

> Why are we doing this? What use cases does it support?

> Please provide specific examples. If you say "this would be more flexible" then
> give an example of something that becomes easier. If you say "this would be make
> it easier to do X" then give an example of what that looks like today and what's
> hard about it.

> Don't assume that others recognize the problem is one that needs to be solved
> Is there some concrete issue you cannot accomplish without this?
> What does it look like to accomplish some set of goals today and how could
> that be improved?
> Are there any workarounds that are necessary today?
> Are there open issues on Github where people would be helped by this?
> Will the change have performance impacts? Can you quantify them?

> Please focus on explaining the motivation so that if this RFC is not accepted,
> the motivation could be used to develop alternative solutions. In other words,
> enumerate the constraints you are trying to solve without coupling them too
> closely to the solution you have in mind.

The motivation of this arises from the current difficulties with stylizing, setting actions, transitions, animations onto child components.

## Detailed design

### Technical Background

> There are a lot of ways Svelte is used. It's hosted on different platforms;
> integrated with different libraries; built with different bundlers, etc. No one
> person knows everything about all the ways Svelte is used. What does someone who
> knows about Svelte but hasn't necessarily used anything outside of it need to
> know? Are there docs you can share?

> How do different libraries or frameworks implement this feature? We can take
> design inspiration from others who have done this well and improve upon the
> designs or make them better fit Svelte.

### Implementation

> Explain the design in enough detail for somebody familiar with the framework to
understand, and for somebody familiar with the implementation to implement. Any
> new terminology should be defined here.

> Explain not just the final design, but also how you arrived at it. What
> constraints did you face? Are there corner cases you've come up with solutions for?

> Explain how your design fits into the larger picture. Are the other open problems
> in this area you're familiar with? How does this design fit with potential
> solutions for those issues?

> Connect your design to the motivations you listed above. When describing a part of
> the design, it can be useful to share an example of what it would look like to
> utilize the implementation as solution to the problem.

## How we teach this

> What names and terminology work best for these concepts and why? How is this
idea best presented? As a continuation of existing Svelte patterns, or as a
wholly new one?

> Would the acceptance of this proposal mean the Svelte guides must be
re-organized or altered? Does it change how Svelte is taught to new users
at any level?

> How should this feature be introduced and taught to existing Svelte
users?

## Drawbacks

> Why should we *not* do this? Please consider the impact on teaching Svelte,
on the integration of this feature with other existing and planned features,
on the impact of the API churn on existing apps, etc.

> There are tradeoffs to choosing any path, please attempt to identify them here.

## Alternatives

> What other designs have been considered? What is the impact of not doing this?

> This section could also include prior art, that is, how other frameworks in the
> same domain have solved this problem differently.

## Unresolved questions

> Optional, but suggested for first drafts. What parts of the design are still TBD?
