# Hubot Team

Create and manage the members of a team using Hubot.


## Installation

Add **hubot-team** to your `package.json` file:

```json
"dependencies": {
  ...
  "hubot-team": "latest"
}
```

Add **hubot-team** to your `external-scripts.json`:

```json
["hubot-team"]
```

Run `npm install hubot-team`


## Configuration

Some commands require an admin role to be run (i.e. `clear` team list). The
admins can be specified through the `HUBOT_TEAM_ADMIN` environment variable,
as a comma separated list of usernames.


## Commands

    hubot team +1                   # add me to the team
    hubot team -1                   # remove me from the team
    hubot team add (me|<user>)      # add me or <user> to team
    hubot team remove (me|<user>)   # remove me or <user> from team
    hubot team (list|show)          # list the people in the team
    hubot team (new|empty|clear)    # clear team list
    hubot team count                # list the current size of the team


## Contributing

If you are interested to make `hubot-team` better, fork this repository, check
the list of [open issues](https://github.com/hubot-scripts/hubot-team/issues?state=open)
(old issues list can be found [here](https://github.com/mihai/hubot-team/issues?state=open))
for some suggestions to get started, and submit a pull request.

Feel free to add yourself to the
[CONTRIBUTORS](https://github.com/hubot-scripts/hubot-team/blob/master/CONTRIBUTORS)
list while submitting a pull request.

## License
&copy; 2014 [Mihai Cîrlănaru](http://www.mihai-cirlanaru.com)

See [LICENSE](https://github.com/hubot-scripts/hubot-team/blob/master/LICENSE) for more details.
