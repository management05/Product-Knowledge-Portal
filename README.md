ROHANIKA PRODUCT KNOWLEDGE PORTAL – one shared link, edited live
=================================================================
Files: index.html (the portal), products.json (all products + images)

PART 1 – PUT IT ONLINE (one time, ~10 minutes)
1. Sign in at github.com (create a free account if needed).
2. New repository -> name it  rohanika-portal  -> Create.
3. Click "uploading an existing file", drag in index.html and products.json, click Commit changes.
4. Settings -> Pages -> Source: "Deploy from a branch" -> Branch: main, folder: / (root) -> Save.
5. After 1-2 minutes your link is:  https://YOUR-USERNAME.github.io/rohanika-portal/
   Send this ONE link to all employees. They never need to download anything.

PART 2 – CREATE THE EDITOR TOKEN (each Editor, one time)
An Editor token is the "key" that lets the portal save changes to your repository.
1. GitHub -> your profile picture -> Settings -> Developer settings
   -> Personal access tokens -> Fine-grained tokens -> Generate new token.
2. Name: Rohanika portal. Expiration: up to 1 year (set a reminder to renew).
3. Repository access: "Only select repositories" -> choose rohanika-portal.
4. Permissions -> Repository permissions -> Contents: "Read and write". Generate token.
5. Copy the token (starts with github_pat_...). You only see it once.
   If a second Editor (e.g. the company owner) will edit: add them under the repository's
   Settings -> Collaborators, and they create their own token the same way. If GitHub does not
   list the repository for them, they can use Tokens (classic) with the "public_repo" scope
   (or "repo" if the repository is private).

PART 3 – EDIT PRODUCTS (Editors only)
1. Open the portal link -> scroll to the bottom -> click "Editor login".
2. Paste the token when asked (first time only; this browser remembers it).
3. The Editor bar appears. Open any product -> Edit this product / Delete. Or "+ Add product".
4. Click "Publish to everyone". Everyone who opens the link sees the change within 1-2 minutes.
Only people holding a valid token for your repository can publish. Employees without one
can only view and search - the portal checks this with GitHub itself.

TIPS
- "Reload latest" fetches the newest published version (use it if another Editor published first).
- "Log out" removes the token from that computer. Use Editor login only on your own computer.
- Never share your token in chat/e-mail. If it leaks, delete it in GitHub -> Developer settings.
- Every change is saved in the repository's history, so GitHub can restore an older version.

PRIVACY NOTE
Free GitHub Pages sites are readable by anyone with the link. Private-only Pages need a paid
GitHub plan (Team/Enterprise). Do not store prices or confidential data in the portal on a free plan.
