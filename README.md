## testhtmlpage

This is a simple repository with a single Rmarkdown file, to
test/illustrate the use of github to host Rmarkdown and the
corresponding compiled html page.

If you want to host the compiled version of an Rmarkdown file on the
web, the simplest thing is to commit the derived html file to the
repository, and then on Github, visit the repository page (here,
<https://github.com/kbroman/testhtmlpage>) and go to
Settings. There's a section "GitHub Pages". Under source, select
"master branch" and click "Save".

Your site will then be published at
`http://username.github.io/reponame`. For me, I have
`kbroman.github.io` aliased to `kbroman.org`, so the present
repository is published at <http://kbroman.org/testhtmlpage>.

I've not made a home page for the repository. (I could, by creating an
`index.md` markdown file.) But you can go directly to the derived html
file at <http://kbroman.org/testhtmlpage/testpage.html>.

An alternative, in Settings, is to choose "master branch /docs
folder". Then you'd create a `docs` subdirectory for your repository,
and put any derived html files there. An example of this is my
repository for a Plant Breeding seminar I'm teaching this semester, at
<https://github.com/kbroman/PBPG957_Sp2018>. The `docs/` folder in
that repository is published at <http://kbroman.org/PBPG957_Sp2018>.
