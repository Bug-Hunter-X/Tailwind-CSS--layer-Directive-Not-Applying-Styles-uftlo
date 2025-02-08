# Tailwind CSS @layer Issue

This repository demonstrates a problem with the `@layer` directive in Tailwind CSS where custom styles defined within a layer are not being applied correctly. The bug and proposed solution are shown in `bug.css` and `bugSolution.css`, respectively. 

**Problem:** Custom styles defined using `@apply` within a `@layer` aren't being picked up by Tailwind. 

**Solution:** Ensures correct configuration and layer ordering within your Tailwind configuration file.