Brunch
---------------
If you would like to contribute - send pull request to dev branch.
Getting dev version of **Minify**:

    git clone git://github.com/coderaiser/minify.git
    git checkout dev

or by [link](https://github.com/coderaiser/minify/tree/dev "Dev version").

Commit
---------------
Format of the commit message: **type(scope): subject**

**Type**:
- feature
- fix (bug fix)
- docs (documentation)
- style (formatting, missing semi colons, …)
- refactor
- test (when adding missing tests)
- chore (maintain)

**Scope**:
Scope could be anything specifying place of the commit change.
For example util, console, view, edit, style etc...

**Subject text**:
- use imperative, present tense: “change” not “changed” nor “changes”
- don't capitalize first letter
- no dot (.) at the end
**Message body**:
- just as in <subject> use imperative, present tense: “change” not “changed” nor “changes”
- includes motivation for the change and contrasts with previous behavior

**Examples**:
- [fix(style) .name{width}: 37% -> 35%](https://github.com/coderaiser/cloudcmd/commit/94b0642e3990c17b3a0ee3efeb75f343e1e7c050)
- [fix(console) dispatch: focus -> mouseup](https://github.com/coderaiser/cloudcmd/commit/f41ec5058d1411e86a881f8e8077e0572e0409ec)

**Big change should be writed in ChangeLog like [this](https://github.com/coderaiser/cloudcmd/commit/e1893f77be09585decf8a260d45a42efc11c98e5).**