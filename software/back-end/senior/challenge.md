##  Overview

Every player in Empire has a castle. To let players attack another player’s castle, we need you to create armies of randomly distributed troops (a troop is a formation of soldiers with the same skill, such as Spearmen, Swordsmen, Archers, etc.)

For example, we'll call your code telling it we need a random army that's 167 men strong. Assuming our available unit types to be,
for
example, Spearmen, Swordsmen and Archers, what we want from you is that you tell us what such a random army would look like,
e.g.

Our Input: 167

Example result:
63 Spearmen
57 Swordsmen
47 Archers

(The "text output" above is just an example; we need
this as structured data)

### Boundaries

• Each troop MUST be > 0

• The result MUST be different (non-deterministic) with each call. When we call your code 100 times with the same parameters, we
expect 100 different results.

• Obvious biases in the result are strongly discouraged. An obvious bias would be if e.g. one troop type always is the largest (or
smallest etc.)

• Downtime is the enemy. Once deployed, code updates are strongly discouraged. We want this to be deployed-and-forget while
still being future proof.

• We expect an O(n) solution
_______________________________________
“O(n) describes an algorithm which performance will grow linearly and in direct proportion to size of the input data.“

Remarks

• This is _your_ solution and you own it end to end. That is, you are free to decide the design, implementation, docs, etc. Just give
us your best.

• You are free to write this in your preferred language and environment.

• Invest a reasonable amount of time, no more and no less.

• Feel free to implement this as a function, a class, a library, a CLI tool, a microservice, a bot ... show us your mad skillz and
impress us.

• Your code must be correct and it is up to you to proof that it is actually working as intended (docs, testing and code coverage).

• We appreciate a smart algorithm. We’ll look at your general way of problem solving, how elegant your solution is, that is, how
well your solution performs with as few resources as possible (resources including CPU, memory, dependencies).

• We are looking for pragmatic solutions. It is a relatively simple problem and we are looking for a simple, pragmatic solution.

• We are looking for flexible solutions that can be easily extended and enhanced for future use cases.

• We are also looking for simple solutions over over-engineered ones.

• We also appreciate a good build and deployment setup.

• If you have questions please feel free to ask any time.
