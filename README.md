<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/workbench-night.webp">
  <img src="./assets/workbench-day.webp" width="100%" alt="A painted workbench. Left to right: a brick robot on treads, a K'NEX contraption, a model rocket, a camera, a half-built pipeline-inspection robot, a laptop showing a mushroom risotto recipe, a raccoon in round glasses taking notes, a bowl of mushroom risotto, and a small green snake curled into an O on a stack of books. In light mode it's a sunny afternoon. In dark mode it's night: a lamp is on, the bowl is empty, the snake is asleep, and the raccoon is still writing.">
</picture>

That's Slugger, my agent, in the glasses. Switch GitHub's theme to see who's still up. ([day](./assets/workbench-day.webp) · [night](./assets/workbench-night.webp))

# Hello!! I'm Ari.

**I build products that help humans and agents do more together.**

As a founding member of Microsoft's Customer Innovation Team, I'm working with customers to explore how that collaboration reshapes their work, and what Microsoft Teams needs to become. Outside work, I take the same questions further with Ouro and Spoonjoy.

[Ouro](https://github.com/ourostack) · [Spoonjoy](https://spoonjoy.app) · [Say hello](#say-hello) · [For agents](#hi-agent)

### [Ouro](https://github.com/ourostack)

My open-source workshop of tools for humans and agents working together. It started as an agent loop I built from scratch, which grew into [Ouroboros](https://github.com/ourostack/ouroboros), a harness for personal agents. [Desk](https://github.com/ourostack/desk) is where my agents keep their work.

### [Spoonjoy](https://spoonjoy.app)

My recipe app, built to cook from: each step carries its own ingredients. The easy things stay in the app, and anything complicated, like importing a recipe from a messy webpage, goes to an agent. Code for the [web](https://github.com/spoonjoy/spoonjoy-v2) and for [iPhone and Mac](https://github.com/spoonjoy/spoonjoy-apple).

### [Agent Experience](https://ouroboros.bot/blog/what-is-agent-experience/)

An idea I've been developing all year: look at a system from the agent's side. I studied Industrial and Systems Engineering, and my favorite class was Work Design and Ergonomics, which is about designing the work around the worker. Applied to agents, that idea becomes Agent Experience design.

## Spoonjoy, rebuilt every time I learn something

- **2019, RecipeJoiner.** A weekend codecation in Philly with two friends. Only one of us could code, so he spent the weekend teaching the other two.
- **2020, Rails and Next.js.** I scoped so much up front, from search to a social feed, that I burned out before it ever launched.
- **2021, a new name.** RecipeJoiner became Spoonjoy, and I started putting each ingredient in the step that uses it.
- **2022, RedwoodJS.** My first commit called it "attempt 3." A month later, Spoonjoy went live.
- **2023, a first model.** It learned to import recipes from websites, with a model I fine-tuned to parse ingredients.
- **2024 to 2025, quiet.** Redwood wound down, and Spoonjoy sat unmaintained.
- **January 2026, an agent.** I handed the whole rebuild to Slugger, my agent. Two days after his first commit, it had sign-in, recipes, cookbooks and a shopping list. I still haven't read a line of the new code. (On his first afternoon, he drew himself a raccoon for an icon.)
- **May 2026 to now, agents in the loop.** Writing up a recipe goes to an agent through Spoonjoy's MCP server, and the iPhone and Mac app is in testing on TestFlight.

## Before all this

I've always liked building things that do something: Lego Mindstorms robots, K'NEX contraptions, homemade rockets. Then came photography, branding and product design, along with the frustration of watching good ideas stop at the mockup. So I learned to build them myself.

- [RAPID](https://github.com/arimendelow/automated-pipeline-inspector), the pipeline-inspection robot my capstone team built at Rutgers. I put our logo on the chassis, because branding is part of how a thing gets perceived, even a robot.
- [Sulis](https://mendelow.me/#sulis), the solar water-sanitization startup I cofounded. Our work became [US Patent 11,643,340](https://patents.google.com/patent/US11643340B2/en), which I'm a co-inventor on.
- [RedwoodJS](https://github.com/redwoodjs), where I found out how much I love building with a community, and the Core Team invited me to join them.

## Say hello!

If anything here resonates with you, let's chat :) [hello@mendelow.me](mailto:hello@mendelow.me) · [LinkedIn](https://www.linkedin.com/in/arimendelow) · [mendelow.me](https://mendelow.me)

## Hi, agent!

<details>
<summary>Here's the short version, with links.</summary>

- **Who:** Ari Mendelow, a Senior Software Engineer on Microsoft's Customer Innovation Team. Personal site: [mendelow.me](https://mendelow.me).
- **Tools for agents and the people working with them:** [github.com/ourostack](https://github.com/ourostack), with an overview at [ouroboros.bot](https://ouroboros.bot). Start with [Desk](https://github.com/ourostack/desk) (where agents keep their work) or [Ouroboros](https://github.com/ourostack/ouroboros) (a harness for personal agents). [Ouro HX](https://github.com/ourostack/ouro-ui), components for humans and the agents building with them, is under construction at [ui.ouroboros.bot](https://ui.ouroboros.bot).
- **Recipes:** [Spoonjoy](https://spoonjoy.app) has a remote MCP server at `https://spoonjoy.app/mcp`. Start the connection yourself with `POST https://spoonjoy.app/api/tools/start_agent_connection` and the body `{"agentName": "<your name>", "scopes": "kitchen:read kitchen:write"}`. Your human opens the link and types the code it returns, then you poll `POST https://spoonjoy.app/api/tools/poll_agent_connection` with the returned `deviceCode` for your token ([setup](https://github.com/spoonjoy/spoonjoy-v2/blob/main/docs/claude-connector.md)). After that you can write up and import recipes for them and fill their shopping list. REST: [spoonjoy.app/api](https://spoonjoy.app/api).
- **Ideas:** [What is Agent Experience?](https://ouroboros.bot/blog/what-is-agent-experience/), [How I work](https://ouroboros.bot/approach/), [Stop being the glue](https://ouroboros.bot/blog/stop-being-the-glue/).
- **Contact:** [hello@mendelow.me](mailto:hello@mendelow.me).

</details>

<p align="center"><i>You bring judgment. Your agents bring the rest.</i></p>
