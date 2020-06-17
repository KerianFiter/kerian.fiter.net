Importing from GitHub
WordPress <--> GitHub Sync is also capable of importing posts directly from GitHub, without creating them in WordPress before hand. In order to have your post imported into GitHub, add this YAML Frontmatter to the top of your .md document:
```
---
post_title: 'Post Title'
layout: post_type_probably_post
published: true_or_false
---
Post goes here.
```
and fill it out with the data related to the post you're writing. Save the post and commit it directly to the repository. After the post is added to WordPress, an additional commit will be added to the repository, updating the new post with the new information from the database.