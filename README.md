<p align="center">
  <img src="assets/portfolio-cover.svg" width="100%" alt="Sachin Kanna M. Full-stack, Android and applied AI. Computer Science Engineering at KPRIET.">
</p>

Hi, I’m Sachin. I study Computer Science Engineering at KPRIET and build software for the steps people actually take: buying a piece of art, checking in at a campus event, or telling an AI assistant that a preference has changed.

I’m looking for **software engineering internships**. I especially enjoy working where a user interface meets a tricky backend problem.

[LinkedIn](https://www.linkedin.com/in/sachinkanna12) · [Email me](mailto:sachinkannasankar@gmail.com) · [LeetCode](https://leetcode.com/u/sachinkanna12/) · [Browse my repositories](https://github.com/Sachinkanna07?tab=repositories)

## Pick a project

| Project | Something you can try |
| --- | --- |
| **[ContextOS](https://github.com/Sachinkanna07/ContextOS)** · Python, SQLite | Give an assistant a preference, change your mind, and inspect the memory it retrieves next. [Run the offline demo](https://github.com/Sachinkanna07/ContextOS/blob/main/docs/demo.md) |
| **[Giggle Gallery](https://github.com/Sachinkanna07/Giggle-Gallery)** · Next.js, PostgreSQL | Browse artists and artwork, then follow a piece from the storefront into checkout. Payments use test mode. [Visit the gallery](https://giggle-gallery-pi.vercel.app/) |
| **[Civora](https://github.com/Sachinkanna07/Civora)** · Kotlin, Jetpack Compose, Firebase | See how a campus event registration becomes a QR ticket on Android. [Open the ticket screen](https://github.com/Sachinkanna07/Civora/blob/master/demo/screenshots/07-event-ticket.png) |
| **[KISH](https://github.com/Sachinkanna07/Kish)** · React, TypeScript | Walk through a crop delivery in English or Tamil, from booking at a centre to receiving a sample receipt. [Open the demo](https://kish-app.vercel.app/) |

## Inside the code

<details>
<summary><strong>How does ContextOS handle a changed preference?</strong></summary>

The demo writes two versions of a preference to a temporary SQLite database. It then builds context for a model and lets you inspect the result. Once ContextOS is installed, you can reproduce the sequence locally.

```sh
contextos demo --json
```

[Follow the walkthrough](https://github.com/Sachinkanna07/ContextOS/blob/main/docs/demo.md) · [Read the demo implementation](https://github.com/Sachinkanna07/ContextOS/blob/main/src/contextos/demo.py)

</details>

<details>
<summary><strong>What happens if two buyers want the same artwork?</strong></summary>

In Giggle Gallery, adding a piece to a cart is only the first step. At checkout, the server locks the artwork rows and checks the available quantity and current price before creating the payment order.

[Read the checkout action](https://github.com/Sachinkanna07/Giggle-Gallery/blob/main/app/actions/checkout.ts) · [Explore the checkout tests](https://github.com/Sachinkanna07/Giggle-Gallery/blob/main/tests/unit/checkout.test.ts)

</details>

<details>
<summary><strong>What does the campus app look like on a phone?</strong></summary>

These screens come from Civora running on an Android emulator with fictional campus data. Open either image for a closer look.

<a href="https://github.com/Sachinkanna07/Civora/blob/master/demo/screenshots/06-events.png"><img src="https://raw.githubusercontent.com/Sachinkanna07/Civora/master/demo/screenshots/06-events.png" width="190" alt="Civora campus events screen on Android"></a>
<a href="https://github.com/Sachinkanna07/Civora/blob/master/demo/screenshots/07-event-ticket.png"><img src="https://raw.githubusercontent.com/Sachinkanna07/Civora/master/demo/screenshots/07-event-ticket.png" width="190" alt="Civora QR ticket for a fictional campus workshop"></a>

[View the full emulator walkthrough](https://github.com/Sachinkanna07/Civora/tree/master/demo)

</details>

## More from my workbench

- **[College Event Registration Portal](https://github.com/Sachinkanna07/college-event-registration-portal)** — a Java and MySQL coursework project that reserves event seats and lets students look up a confirmation code.
- **[Solvynk / BuildSocial](https://github.com/Sachinkanna07/solvynk)** — a clickable prototype for matching projects to real-world problems and exploring which requirements a project covers.
- **[Sachin AI Chat](https://github.com/Sachinkanna07/AI-app)** — an early Streamlit experiment that sends a single question to Gemini.
