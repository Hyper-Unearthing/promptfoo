# custom-provider-mjs (Custom Provider Mjs)

You can run this example with:

```bash
npx promptfoo@latest init --example custom-provider-mjs
```

This example uses a custom API provider in `customProvider.mjs`. It also uses CSV test cases.

Run:

```
promptfoo eval
```

Full command-line equivalent:

```
promptfoo eval --prompts prompts.txt --tests vars.csv --providers openai:chat --output output.json --providers customProvider.js
```
