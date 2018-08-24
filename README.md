# Acosys

Jekyll Project for the French version of the Acosys Consulting website.

### Powered by Jekyll

This website is powered by Jekyll, the simple, blog-aware static website generator.

https://jekyllrb.com/

### Hosted with Netlify

This website is currently hosted with Netlify, an all-in-one platform for building, deploying and managing modern web projects.

https://www.netlify.com/

### Content Management System (CMS)

The CMS for this website is provided by Netlify CMS.

https://www.netlifycms.org/

## Quick Steps to rebuild the website

1. Install Jekyll on your local dev environment
  - Install RVM with latest Ruby version (https://rvm.io/):
    - `gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB`
    - `\curl -sSL https://get.rvm.io | bash -s stable --ruby`
  - Install Jekyll and clone the repo (https://jekyllrb.com/docs/quickstart/)
    - `gem install jekyll bundler`
    - `mkdir website`
    - `cd website`
    - `git init`
    - `git clone {{URL OF THIS REPO}}`
  - Inside the directory for the code you just cloned, start up the Jekyll dev server!
    - `bundle install`
    - `jekyll serve`
  - Visit `http://localhost:4000/` in your browser - you are up and running. Happy coding.

## Quick steps to publish (deploy) the website

  1. You will need a hosting account with Netlify (https://www.netlify.com/) or any other JAMstack hosting provider. You will also need a Git (or GitLab, or Bitbucket) repo with your code.

  2. Assuming you signed up for Netlify, click on "New site from Git"

  3. Watch your website be deployed.

  4. You are done. Netlify is awesome.

  5. Anytime you need to make changes, push your new code to the Git repo and Netlify will recompile and serve it automatically.
