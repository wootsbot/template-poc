<!-- BEGIN:nextjs-agent-rules -->
# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` before writing any code. Heed deprecation notices.
<!-- END:nextjs-agent-rules -->

## Import aliases
- Use `#/` to import from src/ — NEVER use `@/` or relative paths
- Correct: `import { Button } from "#/components/ui/button"`
- Incorrect: `import { Button } from "@/components/ui/button"`
- Incorrect: `import { Button } from "../../components/ui/button"`

## Available UI components
Only use components that exist in `src/components/ui/`.

## Critical rules
- NEVER assume a component is installed without checking the list
- The correct alias is `#/` not `@/`
