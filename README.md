# git-hooks

This repository contains git hooks to speed up/automate your work

> Hooks are programs you can place in a hooks directory to trigger actions at certain points in git’s execution.

To get more information about how git hooks works visit [documentation page](https://git-scm.com/docs/githooks)

## List of available hooks

1. **composer**
    1. ***post-checkout*** hook will run composer install if between two branches **composer.lock** was changed

## Install

Go to your project git hooks directory
    
    cd your_project_dir/.git/hooks

Download selected hook for example:

    wget https://raw.github.com/smajti1/git-hooks/master/composer/post-checkout

Make hook executable

    chmod +x post-checkout

## License

This project is licensed under the terms of the [MIT license](https://opensource.org/licenses/MIT)    