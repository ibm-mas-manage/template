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
	- Merge pull request

- Update your repo settings to publish content: (It is one time setting)
	- On left naviagation, select `Pages` 
	- Go to `Build and deployment` section on right side
	- Select `gh-pages`, `root` context and save.
    - It will take few seconds to publish your content.
	- https://ibm-mas-manage.github.io/reponame/
	- For example, https://ibm-mas-manage.github.io/template/
	- Update site and repo url in mkdocs.yml
	
- Your content will be publish automatically when pushed to master branch.
	
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

