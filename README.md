# Building a financial system with Codex

When I point to a number in a financial report, I want to be able to follow it all the way back to the transactions that explain it. That expectation shaped how I built my own bookkeeping system.

While keeping the books and building my own system, I found that I had to teach Codex how to follow the money. Two records can describe one payment. A refund can arrive a month after the charge. A missing figure can look like a zero. Each case changes what belongs in the final report.

I turned those lessons into an eight-step skill that Codex can follow from the first bank transaction to the final reconciliation. If you're building a financial system of your own, I hope it gives you a useful place to start.

- [Bookkeeping workflow](SKILL.md) covers the eight steps in order.
- [Reconciliation and reporting checks](references/system.md) explains how to handle differences, possible duplicates, and missing records.

## Use the skill

Select **Code → Download ZIP** and extract the archive. Ask your assistant to read `SKILL.md` and follow the workflow for your chosen period. Keep the `references/` folder next to `SKILL.md` so the links work.

For a project that discovers skills in `.agents/skills/`, place the extracted folder at `.agents/skills/branch-finance-repair/`.

## Make it yours

You're welcome to use, modify, and share this skill under the [MIT License](LICENSE). If a step is unclear, a check is missing, or you've found a better way to handle a transaction, I'd love your input. Open an issue to discuss it, or fork the repository and send a pull request with your changes. Please use fictional details in public contributions.
