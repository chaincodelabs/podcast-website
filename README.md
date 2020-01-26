# Website for the Chaincode Podcast

## Building The Site Locally

To build the site, you need to go through a one-time installation
procedure that takes 15 to 30 minutes.  After that you can build the
site an unlimited number of times with no extra work.

##### Install The Dependencies

**Install RVM**

Install RVM using either the [easy instructions](https://rvm.io/) or the
[more secure instructions](https://rvm.io/rvm/security).

Read the instructions printed to your console during setup to enable the
`rvm` command in your shell.  After installation, you need to run the
following command:

    source ~/.rvm/scripts/rvm

**Install Ruby**

To install Ruby 2.6.4, simply run this command:

    rvm install 2.6.4

Sometimes this will find a pre-compiled Ruby package for your Linux
distribution, but sometimes it will need to compile Ruby from scratch
(which takes about 15 minutes).

After Ruby 2.6.4 is installed, make it your default Ruby:

    rvm alias create default ruby-2.6.4

And tell your system to use it:

    rvm use default

(Note: you can use a different default Ruby, but if you ever change
your default Ruby, you must re-run the `gem install bundle` command
described below before you can build the site. If you ever receive a
"eval: bundle: not found" error, you failed to re-run `gem install
bundle`.)

**Install Bundle**

When you used RVM to install Ruby, it also installed the `gem` program.
Use that program to install bundle:

    gem install bundle

**Install the Ruby dependencies**

Change directory to the top-level of your local repository (replace
`podcast-website` with the full path to your local repository clone):

    cd podcast-website

And install the necessary dependencies using Bundle:

    bundle install

Some of the dependencies can take a long time to install on some systems, so be
patient.

Once Bundle completes successfully, you can preview or build the site.

##### Preview The Site

To preview the website in your local browser, make sure you're in the
`podcast-website` directory and run the following command:

    make preview

This will build the site and then print a message like this:

    Server address: http://0.0.0.0:4000
    Server running... press ctrl-c to stop.

Visit the indicated URL in your browser to view the site.

##### Build The Site

To build the site exactly like we do for the deployment server, make
sure you're in the `podcast-website` directory and run:

    make

The resulting HTML for the entire site will be placed in the `_site`
directory and various tests will be run.

## Theme

This website is based on the [Basically
Basic](https://github.com/mmistakes/jekyll-theme-basically-basic#github-pages-method)
theme by Michael Rose. License is in Theme-license.txt.
