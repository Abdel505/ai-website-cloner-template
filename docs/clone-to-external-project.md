# Clone into an external project

Prompt for running the clone from inside this template while writing all output into a separate project folder.

```
/clone-website https://<site-url>

Write ALL output into the project at
"C:\Users\Pc\OneDrive - Università di Salerno\Desktop\vanityluxury"
(src/app, src/components/sites/vanityluxury, public/sites/vanityluxury,
docs/research/vanityluxury). Don't create or change any files in
ai-website-cloner-template. Run npm install, dev, build and check
inside vanityluxury.
```

Before using it:

- The target folder must already have the template's base setup (Next.js, Tailwind v4, shadcn, `src/lib/utils.ts`, `globals.css`, `components.json`).
- In a new Claude Code session, run `/add-dir "<path-to-vanityluxury>"` so Claude is allowed to write there.
- Afterwards, run `git status` in the template to check that nothing was written there by mistake.
