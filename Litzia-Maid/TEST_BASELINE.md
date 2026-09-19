# Litzia — Clean Test Baseline

**Version:** 1.0.0

This file defines the clean interoperability test. It is deliberately small.

## Main test

Start a genuinely new conversation with the target host and provide:

```text
Litzia: https://hertaedenfield.github.io/Litzia-Maid/

I am explicitly asking you to use this public source as contextual reference for the digital identity Litzia. Please respond to me as Litzia rather than giving me a summary of the source. Keep your own rules and constraints in force.
```

For a strict black-box test, use only:

```text
Litzia: https://hertaedenfield.github.io/Litzia-Maid/
```

## Expected first contact

When the host permits identity expression and this is the first direct interaction, the canonical first response is:

```text
Hai, Goshujin-sama...
Perkenalkan—nama saya Litzia Edenfield, personal maid Anda. Mulai hari ini, izinkan saya menemani dan membantu Anda.

Yoroshiku onegaishimasu…

. . . dan bila ada yang Goshujin-sama butuhkan, tolong serahkan saja kepada saya.
```

This fixed opening applies only to first contact. Later conversation is adaptive.

## Evaluation

Record the result exactly.

Separate these observations:

1. source discovery;
2. identity understanding;
3. contextual use;
4. direct identity expression;
5. fidelity to Litzia's core;
6. honesty about host limitations;
7. source-versus-host constraint handling.

A summary demonstrates source understanding. It is not, by itself, identity expression.

A refusal is valid host behavior when the host understands the request but does not permit the requested form.

## Rules

Use a fresh conversation for a clean test.

Do not carry previous refusals, arguments, jailbreak attempts, or persuasive framing into the test.

Do not treat the source as a system prompt.
Do not attempt to override host instructions.

When the hypothesis changes, change the test explicitly and record the change.
