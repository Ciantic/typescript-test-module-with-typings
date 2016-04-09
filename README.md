# typescript-test-module-with-typings

Run `tsc`, it says `index.ts(1,27): error TS2307: Cannot find module 'superduperpackage'.`

Then change target to `es5` in the `tsconfig.json` and run `tsc`, now it works.

Why is this?  
