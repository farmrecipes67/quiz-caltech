# 🎓 Caltech Insider Quiz

![Caltech Campus](https://drive.google.com/uc?export=view&id=1cX6QJSnmehOxoUg3Ugp4nw9aZu2dHkeU)

## About This Quiz

Think you know Caltech? This insider quiz tests your knowledge of campus traditions, history, famous alumni, hidden gems, and little-known facts that only true insiders would know.

**10 questions • 5 choices each • How well do you really know Caltech?**

## How to Use

### Questions
Check out [`questions.js`](./questions.js) for the full quiz with all 10 questions and their multiple-choice options.

### Answers
The answer key with explanations is in [`answers.js`](./answers.js) — no peeking until you're done! 👀

## Quick Start

```javascript
const { questions } = require('./questions');
const { answers } = require('./answers');

// Display a question
console.log(questions[0].question);
Object.entries(questions[0].choices).forEach(([key, val]) => {
  console.log(`  ${key}: ${val}`);
});

// Check answer
console.log(`Correct: ${answers[0].correct} - ${answers[0].explanation}`);
```

## Sample Question

> **When underclassmen ask seniors about the date of Ditch Day, what are seniors traditionally supposed to reply?**
> - **A.** Soon.
> - **B.** Ditch Day is tomorrow.
> - **C.** We don't talk about Ditch Day.
> - **D.** After finals.
> - **E.** When the cannon fires.

<details>
<summary>🔍 Click to reveal answer</summary>

**B** — The canonical line is 'Ditch Day is tomorrow'—until the real day arrives.

</details>

## Quiz Topics Covered

- 🏛️ Campus traditions & rituals
- 📜 University history & founding stories
- 🌟 Famous alumni & their connections
- 🗺️ Hidden spots & insider knowledge
- 🎯 Little-known facts & surprising trivia

---

<div align="center">

*Generated with 💜 by [Papersaurus](https://github.com/farmrecipes67) 🦕*

*Quiz content created using AI • Campus image generated with AI*

</div>

<!-- Open Graph Tags for Social Sharing -->
<!-- og:title: Caltech Insider Quiz -->
<!-- og:description: Think you know Caltech? Take this 10-question insider quiz covering campus traditions, history, famous alumni, and little-known facts! -->
<!-- og:image: https://drive.google.com/uc?export=view&id=1cX6QJSnmehOxoUg3Ugp4nw9aZu2dHkeU -->
<!-- og:type: website -->
