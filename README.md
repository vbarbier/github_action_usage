# Github Action Usage

This project is a Python script made to gather informations regarding specific Github Actions usage in organization(s) you manage. You give it a list of actions, a list of organizations and it generates an excel file with details regarding how these actions are called in your organizations, retrieving last usage, call chains, and contributors to the repositories it is used in. The original purpose was to track actions usage and be able to massively contact people using specific actions.

## Optimizations

- Adding parallelization to make the process faster.

- Better error handling


## Roadmap

- Parallelization

- Small UI


## Run Locally

Clone the project

```bash
  git clone https://github.com/vbarbier/github_action_usage.git
```

Go to the project directory

```bash
  cd github_action_usage
```

Install dependencies

```bash
  pip install -r requirements.txt

```

Change variables under the "# Parameters to change" part, to suit your needs.

Run the script
```bash
  Python Public_action_usage.py
```


## License

[MIT](https://choosealicense.com/licenses/mit/)

