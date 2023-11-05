# Demonstrates impersonation and masquerading  

1. Manas being Krishnaneel

2. Manas being Mukherjee

# GPG Keys to verify my identity to GitHub

> *If you've allowed someone to push code to your repository, then at the first point, you trust that person. Now if the person tries to impersonate someone else who also has push access to the repository, and tries to make the commit by their name, that is because git was supposed to work that way. This is because many projects, such as Linux and Git, work on a patch basis with a maintainer who integrates patches from a variety of people. Therefore, being able to push data for any author is important. If you spoofed someone else's email address on a patch, they would be informed of that by receiving review comments that they had not solicited. Some projects also do not care very much about who wrote the patch, but instead about whether the patch is of good quality. The author and committer information is for attribution, not identity checking, and so the author is ultimately irrelevant to the project.*

> *Now GitHub has made some controls using GPG (GNU Privacy Guard) keys, so for every commit, if it is coming from someone with a valid signature, they will add a verified tag to the commit, and you can easily figure out which one is coming from the actual person. GitHub offers this as an option for repositories that you can use. However, it imposes some burden on other people to contribute, since it requires people to get GnuPG set up appropriately. If you're operating on a platform such as GitHub, you can also just refuse to accept pull requests if the user ID associated with the PR is not the same one as associated with the commits, which is a valid approach; this can even be done via CI.*

![The verified signature given by GitHub](https://docs.github.com/assets/cb-97945/mw-1440/images/help/settings/gpg-verified-with-expired-key.webp)

# Blogs regarding this issue

- [GitHub Bug Bounty for this issue](https://bounty.github.com/ineligible.html#impersonating_a_user_through_git_email_address)
- [Stackoverflow article explaining this issue](https://stackoverflow.com/questions/62333381/git-setting-anyones-email-address-in-gitconfig)
- [How to generate a new GPG Key](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key)
- [Adding a GPG Key to your GitHub account](https://docs.github.com/en/authentication/managing-commit-signature-verification/adding-a-gpg-key-to-your-github-account)

# Added GPG Key to my GitHub. Signing Off, Manas...