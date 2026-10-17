# untilix-app.github.io (organization root site)

Only exists so iOS can verify Universal Links for shared countdowns
(https://untilix-app.github.io/untilix/e/#...). Apple reads
`/.well-known/apple-app-site-association` from the domain root, which a project
site (`/untilix/`) cannot serve.

Publish: create the GitHub repository `untilix-app/untilix-app.github.io`
(public, GitHub Pages from `main` / root) with these files. `.nojekyll` keeps
the `.well-known` folder from being skipped. Check after a few minutes:
https://untilix-app.github.io/.well-known/apple-app-site-association
