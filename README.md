# INTRODUCTION
Jekyll is a static site generator framework to setup static sites with ease.
It is perfect for portfolio or blog like websites. For this site we have used Bootstrap 4 for styling.

# ToDO
A jekyll theme with this styling is in progress, which will be available shortly.

# STEPS TO SETUP THE BLOG
1. Clone the site into your local system
```
$ git clone https://github.com/evos-solutions
``` 
2. Install ruby if you don't have a version installed in your system.

3. Install the ruby package manager `bundler`:
```
$ gem install bundler
```

4. Install the gems:
```
$ bundle install
```

# RUN THE BLOG IN LOCAL
```
$ jekyll serve -b ''
```

# WRITE A BLOG POST
Blogposts reside in the directory `_posts` in jekyll by convention. Jekyll follows a particular filename structure for the particular posts you want to create. The structure should be `yyyy-mm-dd-title.md`. Please note the posts are markdown files. These blogs will have to be written in markdown syntax. To learn more about markdown syntax follow this site [https://daringfireball.net/projects/markdown/syntax](https://daringfireball.net/projects/markdown/syntax)

## FRONTMATTER
Every post that you write need to have certain frontmatter to start with. Frontmatter are the useful metadata for a post that are used by the jekyll engine to render the post. Example of a few metadata are:
- Title
- Author
- Thumbnail
These metadata are extremely important for the post to render correctly.

## ASSETS AND IMAGES
The thumbnail or images of a post need to be properly placed inside the `assets/images` folder. Create a new folder inside `assets/images` with foldername `yyyy-mm-dd-title`. All the images of a particular post must be placed inside this folder.

# ISSUES
Please raise any issue or additional feature requests in the issues tab of github.
