# SRE SummerCamp 2023 Website

## Contribute

### 1. Install Hugo

This site is generated using the static site generator [Hugo](https://gohugo.io/).

Follow [these instructions](https://gohugo.io/getting-started/installing/) to install it on your computer.

### 2. Clone this repo

Clone this repo using:

```shell
git clone git@github.com:sre-summercamp/summercamp-2023.git
```

### 3. Start the Hugo server

Run the server:

```shell
hugo server -D
```
Navigate to the site at http://localhost:1313/.

### 4. Deploy changes

Changes are deployed using Github Actions this [workflow](.github/workflows/hugo.yml),
so you just need to open and merge a pull request to publish new changes.
