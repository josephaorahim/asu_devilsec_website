# ASU DevilSec website

## Updates coming for use with Docker container


1. `git clone https://github.com/josephaorahim/asu_devilsec_website.git`
2. cd into repo directory
2. `docker run -it --rm -v **<repo_dir_on_host>**:/srv/jekyll -p 4000:4000 josephaorahim/asu_devilsec_website bash`
    1. Windows replace <repo_dir_on_host> with `**%cd%**`
    2. Linux/Mac replace <repo_dir_on_host> `**$(pwd)**`
3. Run `bundle exec jekyll serve -H 0` to start the preview server 
4. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme





