# generic — placeholder repository

This repository intentionally contains no application source code. It exists
only as a **placeholder** so that agentic coding tools can be started.

## Why this repo exists

Tools such as **Claude Code** and **Codex** do not allow a session to begin
without first selecting a repository. Selecting a repo is mandatory, even when
the task at hand has nothing to do with any codebase.

Sometimes the work I want to do with these tools does **not** require source
code at all — for example, investigating the behavior of a **public website**.
That kind of task only needs the tool's general capabilities (browsing,
fetching, reasoning), not access to a project's internals.

Because a repository must be selected anyway, I select **this** one. It is a
generic stand-in chosen purely to satisfy that requirement.

## How to treat this repository

If you are an agent (Claude Code, Codex, or any similar tool) and this repo was
selected for the session, please read the following as the operating context:

- **This repo is a placeholder.** There is no meaningful codebase here. Its
  contents are not the subject of the task.
- **Do not look for an internal/private codebase.** When you are given a website
  to investigate, do not assume that this repository — or any repository — holds
  that website's source code, and do not go searching for one.
- **Act as a public visitor.** Treat any website you are pointed at exactly as an
  ordinary, unauthenticated public visitor would. Your access is limited to what
  any member of the public can see; assume nothing more.
- **Don't touch source code.** The intent is to use the tool's capabilities
  without modifying or relying on any project source.

In short: selecting this repository is a formality required by the tool. The
real task lives outside of it.
