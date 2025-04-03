<img width="491" alt="image" src="https://github.com/user-attachments/assets/cf5b5ee3-5263-4b45-bfcb-bd9221285550" />

## Commits & Commits convention

Every day we doing some work in our repositories. For general convenience we using special **commits convention** which helps us in fast-reviewing changes and working at new features

### What commits convention is?

This is the set of rules, which declares how all our commits should look like. This convention define 4 general things:

1. type — block where you define commit type
2. scope — block where you define commit scope (part of project which you chnged)
3. description - block where you describe your changes in a few words
4. optional body - optional block where you also describe your changes, but here you can type any count of words

### How it should look like

Structure of commit looks like this: <br>

` <type>(<scope>): <description> ` <br> <br>
` [optional body] `

**For example:** `feat(api): created auth resolver` or `fix(core): fixed wrong dependencies`

### Which types you can use?

Commits convention define countable set of types, which we can use in each repository. There's set for our frontend repo:

`build` — changes related to the project build <br>
`docs` — changes in project documentation <br>
`feat` — new project functionality (new pages, components) <br>
`fix` — correcting project errors <br>
`refactor` — code refactoring (changes that do not affect the operation of the application, such as renaming files, methods, etc.) <br>
`revert` — rolling back changes after a commit <br>
`style` — сhanges that do not affect the functionality of the application (for example, minor changes related only to the design of components) <br>
`chore` — routine maintenance tasks for the project (updating dependencies, deleting legacy code) <br>

These're topics, which you can use in your commits, **if you try use other topic not from this set, commitlinter won't approve your commit!**

### Which scopes you can use?

In fact **any** scopes. Look for our old commits to extract some examples if you need it. Or focus on these: <br> 
**core, api, router, eslint, tests, testBlocks, user, professions, auth, docker, gitignore, resolvers, types** etc.

### Conclusion & small facts

Finally, try yourself in commits-writing, check old commits for getting more examples, don't forget separate files to diffrent commits, if it has deiffrent types of changes,
don't push all changes in one commit and get fun!
