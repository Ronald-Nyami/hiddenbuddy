Both `Meteor` and `Ionic` took their platform to the next level in tooling.
Both provide CLI interface instead of bringing bunch of dependencies and configure build tools.
There is also differences between those tools, in this post we will focus on the `Ionic` CLI.

To start, let’s install `Ionic` with Npm. In your command line:

    $ npm install -g ionic

Now let’s create a new `Ionic` app with the tabs template:

    $ ionic start whatsapp tabs

Now inside the app’s folder, run:

    $ npm install
    $ bower install

Let’s run this default app, in the command line:

    $ ionic serve

to run inside browser, or:

    $ ionic emulate

to run inside a simulator.

It is also recommended to exclude the `libs` dir from git so irrelevant content won't be uploaded to github as we make progress with this tutorial. Just edit the `.gitignore` file like so:

{{{diff_step 0.1}}}
