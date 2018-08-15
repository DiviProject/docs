<p align="center">
  <img src="/source/images/logo.png" alt="Divi Docs: Contribute to Divi Development" width="226">
</p>

<p align="center">Contribute to Divi's documentation using the instructions in this README.</p>

<p align="center"><em>This documentation was created with Slate. Check it out at <a href="https://lord.github.io/slate">lord.github.io/slate</a>.</em></p>

Getting Started
------------------------------

### Prerequisites

You're going to need:

 - **Linux or OS X** — Windows may work, but is unsupported.
 - **Ruby, version 2.3.1 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

1. Fork this repository on GitHub.
2. Clone *your forked repository* (not our original one) to your hard drive with `git clone https://github.com/YOURUSERNAME/docs.git`
3. `cd docs`
4. Initialize and start Slate. You can either do this locally, or with Vagrant:

```shell
# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

You can now see the docs at http://localhost:4567. Whoa! That was fast!

Now that Slate is all set up on your machine, you'll probably want to learn more about [editing Slate markdown](https://github.com/lord/slate/wiki/Markdown-Syntax).

### Note on JavaScript Runtime

For those who don't have JavaScript runtime or are experiencing JavaScript runtime issues with ExecJS, it is recommended to add the [rubyracer gem](https://github.com/cowboyd/therubyracer) to your gemfile and run `bundle` again.

### Contribute your updates/changes

After you are satisified with your changes create a pull request to this repository and one of the primary developers will take a look and pull it in.

Contributors
--------------------

Thank you to the folks who have contributed to the Divi Documetation!

- [@99darwin](https://github.com/99darwin) 
- [@geoffmccabe](https://github.com/geoffmccabe)