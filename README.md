# Intrustions to create repo and publish the content:
- Create your own repo
- Clone your repo to your local system
- Download the template repo zip and unzip into a local folder
- Copy the files from the unzip template folder
- Delete contents from README.md
- Update the index.md with your content
- Check-in into main branch:

```
cd your repo folder
git branch -M main
git add .
git commit -m "Initial commit"
git push -u origin main

```
- Create master branch in your repo.
- Create a PR to push your changes to master branch when you ready to publish.
	- Approve changes

- Update your repo settings to publish content
	- On left naviagation, select `Pages` 
	- Go to `Build and deployment` section on right side
	- Select `gh-pages`, `root` context and save.

# Sample markdown constructs:

# Sample

## Sample Manage
**Bold**

This is a sample document.

### Sub-heading
- This is a sample.


## Link Sample
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)


## Code Snippet
```
code snippet

```

## table
|name|description|value|
|----|-----|-----|
|sample1|This is a sample1|111|
|sample2|This is a sample2|222|

