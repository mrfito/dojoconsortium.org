---
title: Source Ownership
draft: true
aliases: [/tech-tips/source-ownership/]
weight: 1
---

**_Delivery and quality is being significantly impacted by teams sharing
ownership of the source code and adding process overhead to make sure everyone knows
what's happening in the code._**

## Recommended Practices

- Utilize automated pipelines to help validate that the product remains releasable before and after any code is merged to trunk.
- Limit ownership of a repository to a single "Two Pizza Team" that decides what code to merge.
- Give all developers on the team access to merge code to trunk. Give read access to everyone else.
- Use an innersourcing policy so that people outside of the team know how to contribute to your product.

## Tips

- Teams looking to create an [InnerSourcing](../innersource) policy can start by applying their Definition of Done to any external contributions.
- If any developer on the team does not have the ability to merge code, ask "Why?".

## Value

As a team we want to create a culture of source ownership so that we can increase our product understanding, code quality, and delivery speed.

## Acceptance Criteria

- No contributions to source bypass the team's approval.
- Automated pipelines validate that PRs from internal and external contributors conform to quality standards.
- All team members have access to merge to trunk.
- [InnerSourcing](../innersource) and/or external contributions **fork the repository they do not branch**.
- Teams no larger than 12 people per team.

## References

- Go check out the [CD Anti Patterns](../../continuous-delivery/cd-anti-patterns)
  page to learn about [Team Structure](../../continuous-delivery/cd-anti-patterns#team-structure)
  and many other anti-patterns to avoid in your journey.

---
