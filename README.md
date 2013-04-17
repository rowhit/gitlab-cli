# _GitLab CLI Tool_

_Many people prefer to work from the CLI when possible. This tool aims to bring some of the GitLab functionality into the CLI to avoid repeated trips to the web UI. At this time the tool only allows interaction with snippets._

## Project Setup

_How do I get started?_ 

1. _Clone this repo._
2. _Make sure you have bundler installed. `gem install bundler`_
3. _Run `bundle install` in the root of the repository._
4. _Copy config.yml.sample to config.yml and edit the configuration as appropriate._
5. _Add the repo bin path to your environment PATH variable._

_How can I find the private token for my user?_

Login to your GitLab web UI, go to 'My Profile', and select the 'Account' tab.  Copy the private token from the box and paste into your config.  

_How can I add the repo bin path to my environment PATH variable?_

Place it in your ~/.bash_profile file.  You should end up with something like this:
`export PATH=$PATH:/path/to/gitlab-cli/repo/bin/`

## Issues

If you encounter issues with this project, please find help via one of these avenues.

1. _IRC: #gitlab on Freenode - nick dblessing_
2. _GitHub Issues: Open a new issue here on GitHub_

## Contributing changes

I welcome all contributions.  If you would like to include a new feature or bug fix, simply open a pull request and explain the problem or feature you contributed. I will review the contribution at that point.  If you want to discuss fixes or improvements before submitting a pull request, please find me on IRC #gitlab on Freenode or open a GitHub issue.

## License
Without all the official "legal" mumbo-jumbo, you are free to use this tool as you wish.  You can modify it, distribute it, or do anything else you want with it as long as you retain credit to any contributors.  Contributors include myself and any developers who provide fixes or improvements via pull requesets back to the original repository.
