<div align="center">

# Personal Website Cookiecutter

## Personal website cookiecutter allows a user to generate a simple landing page with relevant details such as a Github and Linkedin links deployed to Github Pages. Not only does it generate the website, but has a fully featured CLI tool to programtically enable github pages. We wanted to gut out as much GUI input.

### [Live Demo](https://vdoster.com) 

![Generated website](https://github.com/vladdoster/Personal-Website-Cookiecutter/blob/master/example.png)

</div>

### Features
- Automatic HTTPS
- Free
- Inline CSS

#### Stack
- HTML & CSS
- [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/)
- [Github Pages](https://pages.github.com/)

#### Usage

Pretend you want a simple personal landing page that points people towards relevant links and gives you a slice of the internet to call yours.

1. First, get Cookiecutter. Trust me, it's awesome:

`pip install "cookiecutter>=1.4.0"`

2. Run it against this repo:

`cookiecutter https://github.com/vladdoster/Personal-Website-Cookiecutter/`

3. You'll be prompted for some values. Provide them, then a website will be created for you.

Answer the prompts with your own desired options. For example:

```
Cloning into 'Personal-Website-Cookiecutter'...
remote: Counting objects: 550, done.
remote: Compressing objects: 100% (310/310), done.
remote: Total 550 (delta 283), reused 479 (delta 222)
Receiving objects: 100% (550/550), 127.66 KiB | 58 KiB/s, done.
Resolving deltas: 100% (283/283), done.
directory_name [personal-website]: slice-of-internet
email [mvdoster@gmail.com]: dosterm@wit.edu
github_username [vdoster]: vladdoster
html_title [MVD]: MVD
linkedin_url [https://www.linkedin.com/in/vdoster/]: linkedin.vdoster.com
name [Vlad Doster]: Martin V. Doster
short_personal_description [Free range code artisan]: I code with my bare hands

```

4. Create a git repo and push it there:

```
git init
git add .
git commit -m "Initial commit: A new website"
git remote add origin git@github.com:vladdoster/slice-of-internet.git
git push -u origin master
```

#### Ideas? 

If you want me to add something, [open an issue](https://github.com/vladdoster/Personal-Website-Cookiecutter/issues/new)
