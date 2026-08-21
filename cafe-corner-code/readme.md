1. Create a branch `feat/newsletter,` add a `newsletter.html` page, record it, publish it, and open a merge request into `main`. Have a review and merge it.

2. On a branch `feat/menu-update`, change a specific line in `menu.html`. Then, on `main`, change the **same line** in a different way. Publish both. Your merge request will now clash with `main`, inspect the differences between the two branches, then combine `main` into your feature branch and resolve the clash so both can live together.

3. Make a change to `gallery.html` and set it aside temporarily. Then discard that change entirely so your project returns to its last recorded state.

4. On main, make a change to `index.html` and commit it (e.g. an "opening hours" line). You then decide that commit was a mistake. Create a **new** commit that reverses that commit's changes (don't erase history), then publish and open a merge request. _(B3 – revert)_

5. Register a second publishing destination named `backup` (a different GitHub repo). Make a change to `index.html` and publish it to **both** destinations.

   https://github.com/kelia01/git-exercises.git
