# Hi, I'm Agustín 👋

Full-stack developer at Mimiquate and Software Engineering student at [ORT University](https://www.ort.edu.uy/), in Uruguay 🇺🇾, wrapping up my final degree project.

I like building software that's actually useful. What I enjoy most is figuring out how to build it *with* AI agents, without lowering the bar.

### What I'm into

- **AI & agent engineering** — Skills, hooks, integrations and workflows that let agents do real work in a real codebase, not just demos.
- **Full-stack features** — From "what problem are we actually solving?" to the data model, the backend and the UI.
- **Asking why first** — I'd rather question an assumption early than ship the wrong thing fast.

### Open source

- [beam-community/jsonapi#474](https://github.com/beam-community/jsonapi/pull/474) — Malformed requests were crashing the deserializer. Now they get a proper 400.
- [joken-elixir/joken#458](https://github.com/joken-elixir/joken/pull/458) — A token whose `exp` wasn't a number never expired. Now non-numeric `exp` and `nbf` claims are rejected.
- [absinthe-graphql/absinthe#1471](https://github.com/absinthe-graphql/absinthe/pull/1471) — Map scalar default values showed up in introspection as Elixir code (`%{}`), so GraphQL clients failed to load the schema. Now they're rendered as GraphQL literals.
- [phoenixframework/phoenix#6912](https://github.com/phoenixframework/phoenix/pull/6912) — Path helpers and `~p` passed `"."` and `".."` params through, so the browser resolved the link to a different route. Now they raise.
- [nshkrdotcom/claude_agent_sdk#9](https://github.com/nshkrdotcom/claude_agent_sdk/pull/9) — A session id starting with `-` was parsed as a separate CLI flag, so callers could inject flags like `--dangerously-skip-permissions`. Now `--resume` and `--session-id` are passed as a single token.
- [nshkrdotcom/claude_agent_sdk#10](https://github.com/nshkrdotcom/claude_agent_sdk/pull/10) — CI was failing on every `main` run since the project moved to Elixir 1.19. Got it green again, with a follow-up in [#11](https://github.com/nshkrdotcom/claude_agent_sdk/pull/11) for the test Docker image and a stale test.
- [swoosh/swoosh#1255](https://github.com/swoosh/swoosh/pull/1255) — The Test adapter always delivered successfully, so testing a failed send meant mocking the mailer. Now `fail_next_delivery/2` makes the next deliveries fail.
- [stablyai/orca#28329](https://github.com/stablyai/orca/pull/28329) — Session search ignored the time zone in `--since`, so results could be off by up to 14 hours. Now any offset finds the same sessions.
- [stablyai/orca#37452](https://github.com/stablyai/orca/pull/37452) — When a branch had several PRs, Orca linked the newest one even if it was closed. Now it links the one that's still open.
- [stablyai/orca#41066](https://github.com/stablyai/orca/pull/41066) — Once an HTML document preview had focus, Orca's own shortcuts stopped working. Now the preview hands them back.
- [stablyai/orca#37939](https://github.com/stablyai/orca/pull/37939) — Plugin panels swallowed the sidebar and zoom shortcuts. Now they reach Orca.
- [stablyai/orca#37965](https://github.com/stablyai/orca/pull/37965) — Claude plugin UI frames leaked into the chat transcript as raw messages. Now they stay out of it (co-authored).
- [dashbitco/nimble_csv#93](https://github.com/dashbitco/nimble_csv/pull/93) — CI had been quietly dead for over a year. Brought it back.

### Tech I work with

<img src="https://skillicons.dev/icons?i=elixir,nodejs,react,js,ts,postgres,mongodb,redis" alt="Elixir, Node.js, React, JavaScript, TypeScript, PostgreSQL, MongoDB, Redis">

**AI:** Claude Code, MCP, custom skills, and the occasional hook that saves me an hour a day.

### A bit more about me

I work best with other people: sharing ideas, arguing about them (nicely), and ending up somewhere better than where any of us started. Off the keyboard, I'm fixing up classic cars, catching a football or rugby match, or looking for new music.

<details>
<summary>☕ Coffee or mate?</summary>
<br>
Both. Coffee to start the day, mate to get through it. 🧉
</details>

### Ask me about

Agent workflows, Elixir, or why your old car is making that noise.

🌐 [Portfolio](https://agustinvarela.dev/) · 💼 [LinkedIn](https://www.linkedin.com/in/avarela2606/) · 📫 [Email](mailto:agustinvarela2606@gmail.com)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="signature-dark.svg">
  <img src="signature-light.svg" width="200" alt="Agustín's signature">
</picture>
