*Doksanbir* means **91** in Turkish. Yes, really. No, there aren't 90 others. And no, it's not my birth year.

CTO at **[Emlakjet](https://www.emlakjet.com) & [Endeksa](https://www.endeksa.com)** by day, still shipping code by night. 15+ years of distributed systems, search, data platforms and, lately, convincing AI agents to do their homework.
### Currently

Running an engineering org where agents review PRs, test features before release and dig through production incidents, while humans keep the merge button.

```text
pull requests reviewed by an agent ....... 696 in 10 weeks
median time in QA ........................ 8.2h → 2.2h
tasks sent back for fixes ................ ~20%, same as humans
cost of a live root-cause run ............ 47 tool calls, $2.71
```

The agents are good. They are also very confident when they're wrong. That's what the fail-closed gates are for.

### Open source, a.k.a. fixing the tools I break

- **[openclaw](https://github.com/openclaw/openclaw)**: 30 merged PRs. I [found MCP processes that refused to die](https://github.com/openclaw/openclaw/pull/143433) and [replies that vanished mid-hot-reload](https://github.com/openclaw/openclaw/pull/145378).
- **[pr-agent](https://github.com/The-PR-Agent/pr-agent)**: 11 merged PRs. An AI reviewer, reviewed by me. [Large-diff chunking](https://github.com/The-PR-Agent/pr-agent/pull/3013), [webhook auth that actually checks](https://github.com/The-PR-Agent/pr-agent/pull/3027).
- **[java-design-patterns](https://github.com/iluwatar/java-design-patterns)**: Bulkhead, Load Shedding, Health Check. Patterns I learned the hard way, now with tests.
- Cameos in [t3code](https://github.com/pingdotgg/t3code/pull/9400) and [alibaba/open-code-review](https://github.com/alibaba/open-code-review/pull/1156).

### Things I believe

- A green CI check that doesn't run the tests is just a nice color.
- Every agent needs a test suite that isn't its own opinion.

### Find me

I write about agents in production, with receipts, at **[doksanbir.blog](https://doksanbir.blog/)**.
Start with [Beliefs, With Receipts](https://doksanbir.blog/beliefs-with-receipts.html) or [The Agents Joined the Chat](https://doksanbir.blog/the-agents-joined-the-chat.html).

[LinkedIn](https://www.linkedin.com/in/doksanbir/) · Trabzonspor, always.
