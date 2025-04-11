
<img src="assets/images/4.jfif" width="400" alt="image">


// To remove branches locally:
 ** git branch -d dev
 ** git branch -d test

// To remove branches remotely:
 ** git push origin --delete dev
 ** git push origin --delete test
 
// Differences between (lightweight tag and annotated tag):

**Lightweight:
-Simple: It’s just a tag name pointing to a commit.
-No Metadata: Contains no extra information like author name, email, date, or tag message.
-Generally used for informal or temporary tagging.
-Creation ----->> git tag v1.7

**Annotated
-Richer Information: Includes metadata like author name, email, date, and a descriptive message.
-Stored as a separate object in the Git database.
-Typically used for official releases, detailed tags, or documentation.
-Creation ----->> git tag -a v1.7 -m "version 1.7"

// To list tags:
** git tag

//To delete tags locally:
** git tag -d v1.7

//To delete tags remotely:
** git push origin --d v1.7

// When to use Rebase
-When i want to clean up the commit history before sharing it with others.
-When i want to Synchronize my feature brances with the main branch.
-If i want to rewrite history if the branch has not yet pushed.
-When i want to avoid merge commits.
