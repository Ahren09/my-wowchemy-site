# Ahren's Site

## Installation

Install [Hugo](https://gohugo.io/installation/macos/)

For example:

```
brew install hugo@0.104.3
```

Note: v0.104.3 is recommended as it is used for this site. 

```bash
CGO_ENABLED=1 go install -tags extended github.com/gohugoio/hugo@latest
hugo version
```

Clone the source code for the website, located at `https://github.com/Ahren09/my-wowchemy-site.git`, into `Ahren09.github.io/`

Clone `https://github.com/Ahren09/Ahren09.github.io.git` into `Ahren09.github.io/public/`

Run `hugo` in `Ahren09.github.io/` to compile and generate new versions of the website in the `public/` folder.


Remove the existing public directory from version control: If the public directory is already being tracked by Git, you'll need to remove it from version control (but not delete it) before you can add it as a submodule. Make sure to commit these changes.

```bash
git rm -r --cached public
git commit -m "Untrack the public directory"
```

Add the new repository as a submodule

```bash
git submodule add https://github.com/Ahren09/Ahren09_public.git public
```

Initialize and update the submodule:

```bash
git submodule update --init --recursive
```

Commit the changes to the source code and push.

```bash
git commit -m "Added public as a submodule"
git push origin master
```

Commit changes to `public/` and push.

```bash
cd public
git add .
git commit -m "Your commit message"
git push origin master
```

