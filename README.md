<h1 align="center">
  <br>
  <a href="https://araekiel.netlify.app"><img src="https://github.com/araekiel/almanac-v1/blob/main/assets/images/almanac.png" alt="Araekiel's Almanac" width="200"></a>
  <br>
  Araekiel's Almanac (v1)
  <br>
</h1>

<h4 align="center">
  This repository contains the source code for my personal website built with <a href="https://jekyllrb.com/">Jekyll</a>.
</h4>

<p align="center">
  <a><img alt="MIT License" src="https://img.shields.io/apm/l/atomic-design-ui.svg?"></a>
  <a><img alt="Github Release" src="https://img.shields.io/badge/release-v1.0-blue"></a>
  <a href="https://app.netlify.com/sites/araekiel/deploys"><img alt="Netlify Status" src="https://api.netlify.com/api/v1/badges/e55d05c3-64c6-4f9f-ac79-4b5f369879f7/deploy-status"></a>
</p>

<p align="center">
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#build--run">Build & Run</a> •
  <a href="#structure">Structure</a> •
  <a href="#refs">Refs</a> •
  <a href="#authors">Authors</a> •
  <a href="#license">License</a>
</p>

<img alt="Gif" src="https://raw.githubusercontent.com/araekiel/almanac-v1/main/assets/images/almanac.gif" type="image/png">

## Prerequisites

### Ruby 

Download and install Ruby from this [link](https://www.ruby-lang.org/en/downloads/).

Run the following commands to confirm if the installation was successful:

```bash
$ ruby -v
$ gem -v
```

### Jekyll

Run the following command to install Jekyll:

```bash
$ gem install bundler jekyll
```

## Build & Run

Clone the repo and cd into the directory:

```bash
$ git clone https://github.com/araekiel/almanac-v1.git
$ cd almanac-v1
```

> Set the port in *_config.yml*

Run the site:

```bash
$ bundle exec jekyll serve
```

> Note: '**bundle exec**' is not required unless you are running the website for the first time.

Open a browser and type **localhost:_port_**

## Structure

### Directory Structure

   ```bash
   .
   ├── _data                      
   |   ├── binge.yml
   |   ├── navingation.yml          
   |   ├── projects.yml
   |   └── sketches.yml
   ├── _includes                      
   |   ├── footer.html
   |   ├── head.html
   |   ├── header.html
   |   └── scripts.html
   ├── _pages                       
   |   ├── 404.html
   |   ├── about.html
   |   ├── binge.html
   |   ├── journal.html
   |   ├── projects.html
   |   └── sketches.html
   ├── _posts
   ├── _site                        # => Auto generated
   ├── assets                      
   |   ├── images
   |   |   ├── binge
   |   |   ├── posts
   |   |   ├── sketches
   |   |   └── almanac.png
   |   └── styles
   ├── _config.yml                  # => Site's configuration
   ├── Gemfile
   └── Gemfile.lock
   ```

### _data/binge.yml

Example:
```yml
- title: Breaking Bad
  location: assets/images/binge/breaking_bad.jpg
```

### _data/projects.yml

Example:
```yml
- title: GitWiz
  desc: A singular portal to search for public repos from multiple version control platforms.
  tags:
    - name: Node.js
    - name: TypeScript
    - name: JavaScript
  url: https://gitwiz.herokuapp.com
```

### _data/sketches.yml

Example:
```yml
- title: The Mandalorian
  caption: "This is the way."
  location: ./assets/images/sketches/mandalorian.jpg
```

> Note: I would advise against relying on this repository. It will not be updated frequently since the website relies on a different repo(private). Also, you will encounter file not found errors upon execution since this repo does not contain images for 'binge' and 'sketches' pages.

## Refs

- The design is inspired by [aweekj](https://github.com/aweekj)'s [Kiko-plus](https://github.com/aweekj/Kiko-plus) jekyll theme.


## Authors

- araekiel - [Github](https://www.github.com/araekiel)

## License 

[MIT License](https://github.com/araekiel/almanac-v1/blob/master/LICENSE) | Copyright (c) 2022 Kumar Shashwat