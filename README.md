# Bot or human? A handoff playbook for crypto exchange support

**Live page:** https://mika-dulata.github.io/support-handoff-playbook/

On a crypto exchange a bot can answer most questions. The hard part is the few it must not touch: money moving right now, an account under review, a person being pushed by a scammer. This is how I decide who answers.

## What's inside

- **Trainer.** 16 synthetic tickets. For each one you pick who should answer (bot, agent, security or compliance), then see why, what to say and what never to say.
- **Five routing questions.** Asked in order, the first yes decides the route.
- **Handoff note builder.** Fill a few fields and copy a structured note into the ticket, so the agent never has to ask the user to repeat the story.

## The five questions

1. Is money or account access at risk right now? → Security, P1.
2. Is there a review, a legal request or a fraud report? → Compliance. Neutral reply, nothing disclosed.
3. Does the fix need someone to act in the back office? → Agent.
4. Is the person vulnerable, under pressure or making a formal complaint? → Senior agent.
5. Has the bot already failed twice? → Agent.

If all five are no, the bot answers from an article that has an owner and a review date.

## Notes

- Every ticket, name and amount is invented. The routes reflect how I think about the problem, not any company's internal policy.
- One HTML file, no build step, no tracking. Open `index.html` locally or use the live page.

Related: [Self-custody support lab](https://mika-dulata.github.io/support-lab/) · [Support KPI calculator](https://mika-dulata.github.io/support-kpi-calculator/) · [LinkedIn](https://www.linkedin.com/in/meruyert-nurkaliyeva)

MIT License · Meruyert Nurkaliyeva
