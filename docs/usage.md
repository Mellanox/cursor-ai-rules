# Usage

To use the rules from this repository:

## Adding Rules

1. **Fork the Repository**: Fork this repository to your GitHub account.
2. **Create a Branch**: Create a new branch for your rule additions.
3. **Add Your Rule**: Navigate to the appropriate directory under `rules/` (`common/` or your team's directory) and add your rule file.
4. **Submit a Pull Request**: Commit your changes and submit a pull request with a detailed description.

## Applying Rules

To apply the rules in cursor-AI, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.
2. **Navigate to Rules Directory**: Go to the `rules/` directory and locate the rule you want to apply.
3. **Load the Rule in Cursor-AI**: Go to the settings in cursor-AI and navigate to the rules section. Upload or import the rule file you want to use.

## Cursor-AI Apply Settings

- **Always**: Always included in the model context.
- **Auto Attached**: Included when files matching a glob pattern are referenced.
- **Agent Requested**: Rule is available to the AI, which decides whether to include it. Must provide a description.
- **Manual**: Only included when explicitly mentioned using @ruleName.

## Contribution

We welcome contributions from all teams! Please see the `CONTRIBUTING.md` file for more information on how to contribute.

