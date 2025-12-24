What is ESLint?
Think of ESLint as your JavaScript code coach 🧑‍🏫. It watches your code and says things like:

“Hey, you forgot a semicolon!”

“Careful, you never used that variable.”

“That function name doesn’t follow the project’s style.”

Basically, ESLint helps you catch mistakes early and keep your code clean and consistent. It’s not rewriting your code — it’s guiding you to write better code by pointing out errors, bad patterns, or inconsistencies before they cause real problems.

You can also customize its rules:

Want semicolons everywhere? ✅
Hate semicolons? Also fine 😎
Prefer single quotes instead of double? Easy!
That’s where ESLint shines — you (or your team) decide what “good code” means, and ESLint enforces it automatically.

What about Prettier?
If ESLint is your coach, Prettier is your code stylist 💅.

It doesn’t care what your code does — it just wants it to look beautiful and consistent.

You know how people debate whether { should go on the same line or a new one? Or how many spaces an indent should have? Prettier says:

“Don’t waste brainpower on that — I’ve got you.”

It automatically formats your code the same way every time — same spacing, quotes, indentation, and line breaks. No more arguments in code reviews about style — just one clean, consistent look across your whole project.

ESLint + Prettier = The Dream Team 💪
ESLint keeps your code correct.
Prettier keeps your code pretty.
Together, they make your codebase feel polished and professional — and you can focus on actually building cool stuff instead of worrying about formatting or tiny syntax mistakes.

If you’re just starting out, here’s the best part:

You don’t need to memorize all the rules or worry about setup right away. Next.js already includes ESLint in the default setup - so you’ll start benefiting from clean, consistent code right from the start. But before we move on, let’s add Prettier on top.

Start by installing Prettier, and its TailwindCSS plugin as dev dependencies:
