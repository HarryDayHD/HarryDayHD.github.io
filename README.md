# [harryday.net](harryday.net)
My personal website, for blog posts and resume.

Website made using [Hugo](https://gohugo.io/), a static site generator built in Go. 
Hosted here using [Github Pages](https://pages.github.com/), which is why the source/commits are public.
Current theme is [Kiera](https://themes.gohugo.io/hugo-kiera/).

## Build Instructions
Why would you build my own personal site?
If you want your site to look/act the same, its better to follow the [Hugo quick start](https://gohugo.io/getting-started/quick-start/) with the theme I list above.

If you want to ignore that advice:
1. Clone this project
2. Update the theme by initialising and updating the git submodule
3. `$ git submodule init`
4. `$ git submodule update`
5. Run hugo, your output static site folder is in `/docs`
6. `$ hugo`