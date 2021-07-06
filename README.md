# LTS Support with Tagging Magic

## Proving Out How Branching From Tags Could be Used

After a tag has been created on a `release/*` branch and pushed up to GH, you can checkout from it like:
```
git checkout -b release/v0.2.0 v0.1.0
```
where `v0.1.0` is the tag and persists after the release branch is pruned.
