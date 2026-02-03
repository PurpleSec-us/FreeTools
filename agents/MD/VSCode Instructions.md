
# How to Add a `.agent.md` File to Your VSCode Environment

This guide explains how to add a custom `.agent.md` file for GitHub Copilot Chat, providing enhanced security guard rails.

## Option 1: Repo-Specific Agent

Add your agent file to your repository:

```
.github/assets/agents/PromptShield.agent.md
```

This makes the agent available only when working in that repository.

## Option 2: Profile-Wide Agent

To make your agent available across all VSCode environments, add it to your VSCode Profile folder. Learn more about profiles [here](https://code.visualstudio.com/docs/configure/profiles):

### Example:
```
C:\Users\<username>\AppData\Roaming\Code\User\assets\agents\PromptShield.agent.md
```

## Selecting Your Agent in VSCode

1. Open VSCode.
2. Open the Copilot Chat panel.
3. Click the agent selector at the top of the chat panel.
4. Choose your newly added agent from the list.

## What to Expect

Once selected, your custom agent will function as normal, but with additional security guard rails as defined by PurpleSec.
