# minimal reproduction for astro-component-tester

Running `npm i` on this project produces the following error:

```bash
npm ERR! code ERESOLVE
npm ERR! ERESOLVE unable to resolve dependency tree
npm ERR!
npm ERR! While resolving: test@1.0.0
npm ERR! Found: astro@2.1.6
npm ERR! node_modules/astro
npm ERR!   astro@"^2.1.6" from the root project
npm ERR!
npm ERR! Could not resolve dependency:
npm ERR! peer astro@"^1.0.0-rc.1" from astro-component-tester@0.6.0
npm ERR! node_modules/astro-component-tester
npm ERR!   astro-component-tester@"^0.6.0" from the root project
npm ERR!
npm ERR! Fix the upstream dependency conflict, or retry
npm ERR! this command with --force, or --legacy-peer-deps
npm ERR! to accept an incorrect (and potentially broken) dependency resolution.
npm ERR!
npm ERR! See /Users/ayoayco/.npm/eresolve-report.txt for a full report.

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/ayoayco/.npm/_logs/2023-03-24T14_41_06_904Z-debug-0.log
```
