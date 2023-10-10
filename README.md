# University schedule

# Deploy to GitHub pages

1. Install dependencies
    ```sh
    pnpm i
    ```
2. Build
    ```sh
    pnpm run build
    ```
3. Commit
    ```sh
    git add dist && git commit -m 'update dist'
    ```
4. Push
    ```sh
    git subtree push --prefix dist origin gh-pages
    ```
