# Minimal git config action
This action sets global `config.user.name` and `config.user.email` with, respectively, the given username and the retrieved email (obtained by [evvanErb/get-github-email-by-username-action](https://github.com/evvanErb/get-github-email-by-username-action)).

# Inputs
| variable | required | default | description |
| --- | --- | --- | --- |
| username | false | github.triggering\_actor | The username of which the email is requested |
| token | false | | The github token to improve email retrieval |

# Outputs
| variable | description |
| --- | --- |
| email | The email retrieved. It is forwarded as output of this action from evvanErb/get-github-email-by-username-action |

