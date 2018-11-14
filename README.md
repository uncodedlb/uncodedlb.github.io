# Uncoded.org website source code

### tl;dr

If you have `Git` & `Docker`, clone a copy of the repo, then run:  

    docker run -p 4000:4000 -v "$PWD:/site" bretfisher/jekyll-serve


##### Explanation

*  This simple one line command will use Docker to build and host Jekyll using the Docker project [jekyll-serve](https://github.com/bretfisher/jekyll-serve)  
*  Edit code  
*  To view, visit: [http://localhost:4000](http://localhost:4000)  
*  Repeat  


![divider](http://78.media.tumblr.com/6a0993ff440e03c7e5bbd0f3eac343c9/tumblr_nkbuy6Clg41twrbr9o1_r1_540.gif)  

---  

## About

[This is the repository](https://github.com/uncodedlb/uncodedlb.github.io) for [Uncoded.org](www.uncoded.org) and is built using [Jekyll](http://jekyllrb.com/).

[Github hosts Jekyll](https://help.github.com/articles/what-is-github-pages/) and static HTML websites for free. Our website can be viewed at [www.uncoded.org](http://www.uncoded.org) which, due to [CNAME](https://github.com/uncodedlb/uncodedlb.github.io/blob/master/CNAME) settings file, directs to this repository website [http://uncodedlb.github.io](http://uncodedlb.github.io/).


## Contribute

Helping is easy.  You don't even _need_ [Jekyll](http://jekyllrb.com/), but it helps.  Changes and [pull requests](https://github.com/uncodedlb/uncodedlb.github.io/pulls) are encouraged.  Want to fix a typo, link, or add some missing info?  Add a page, or more?  Please, go for it!  You just need to fork the repo and make changes.

Any Github user can [Create an Issue](https://github.com/uncodedlb/uncodedlb.github.io/issues/new) or [Pull Request](https://help.github.com/articles/creating-a-pull-request/).  In addition, we'll also allow anyone in our community to [join our team for direct access](https://github.com/uncodedlb/uncodedlb.github.io/issues/new).  We do ask that you adhere to [Uncoded  Policies](https://github.com/uncodedlb/uncoded-policies).



## General Workflow

1.  [Fork the repository](https://help.github.com/articles/fork-a-repo/)
1.  Make changes following [Github Flow](https://help.github.com/articles/github-flow/)
1.  Optionally, enable Travis for yourself on this repo: [https://travis-ci.org/profile/**username** (read more)](http://jekyllrb.com/docs/continuous-integration/)
1.  Create a `Pull Request` to share:  [How to create a Pull Request](https://help.github.com/articles/using-pull-requests/)


## Prerequisites

To help, you'll need to setup Github. A text editor (or IDE), and either Docker or Jekyll installed locally also makes it easier than working on Github directly.

1.  [Create a Github account](https://git-scm.com/book/en/v2/GitHub-Account-Setup-and-Configuration).
1.  [Fork the repository](https://help.github.com/articles/fork-a-repo/) & Make changes to this repo.
1.  Optional, for local development:
    1. [Setup Github SSH Access](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)
        -   [Video Tutorials](https://www.youtube.com/watch?v=noZnOSpcjYY&list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-): Using Github
        -   [Video Tutorials](https://www.youtube.com/watch?v=QfmYUiXMs2E&list=PLg7s6cbtAD168bAd2P4Z0bEUxYMUcyoq1): Github and IDE's (IntelliJ IDE's, Atom, Visual Studio, Github Desktop, Eclipse, Xcode)
    1.  Follow [Github Flow](https://help.github.com/articles/github-flow/) (Branch, Make Changes, Pull Request)
    1.  Option A: Helping with Docker: [Install Docker](https://docs.docker.com/install/)
    1.  Option B: Helping with Jekyll: [Install Jekyll](https://jekyllrb.com/docs/quickstart/)


#### Notes

1. If you're working on Github, you'll likely need to merge `master` with `gh-pages` [Read more](https://help.github.com/categories/github-pages-basics/) about Github pages. **Note:** Again, we're using Jekyll.  And your setup is likely for a user not an organization.
1. Optionally, view your github fork locally or on Github (`gh-pages` branch).  To find this, click your repo settings and look for the URL where it's published:  `https://github.com/**YOURUSERNAME**/uncodedlb.github.io/settings`
