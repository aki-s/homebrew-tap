# About

Applications what I want already exist in this world already.
I'm a patient person for inconvenience.
I thought somebody would create them as a OSS, but I found nobody has provided what I wanted.
I decided to create them by myself with the help of LLM Coding Agent.

## My private Cask of Homebrew

| `<cask>`                                                                  | Description                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [cat-switch](https://github.com/aki-s/CatSwitch-dist/blob/main/README.md) | Categorical Application Switcher of running apps for developers by reducing the cost of your brain's context switch. You NO MORE be at a loss in your parallel tasks like as you are working on a analog desk. This can be main app switcher to be used with cmd+tab (switch by recency) and Spotlight (launching a app). |
| [win-pin](https://github.com/aki-s/WinPin/)                               | Best-effort pinning of targeted application windows to the top. Useful for keeping focus on a meeting video while working, or bringing a specific window to the front among multiple windows of an app.                                                                                                                   |

## How to install and run these Cask

As of Homebrew 6.0.18.

```sh
brew tap aki-s/tap
brew trust aki-s/tap
brew install aki-s/tap/<$name> # e.g. replace $name with `cat-switch`
```

I'm not a member of Apple Developer Program.
If my Casks are in quarantine, please run the following.

```sh
xattr -dr com.apple.quarantine <path/to/$name.app>
```

```sh
open <path/to/$name.app>
```

## Exemption

1. I declare I never violate your privacy even if my applications are not open sourced.
   e.g. Some app uses the permission configurable at `System Settings.app > Privacy & Security > {Accessibility, Screen & System Audio Recording}` by its nature.
   I may develop more functions to opt-out using 'System Audio Recording' if I have time and money, but I cannot promise
   as of now.

2. MacOS and Homebrew are evolving.
   If the procedure depicted above didn't work, ask LLM or search on the internet.

## Contacts

If you have any question, new feature requests, or something you want to tell me,
please post an issue in this repo of GitHub.
While it may be difficult to address every inquiry, I sincerely appreciate your understanding and cooperation.

## Copyrights

I (https://github.com/aki-s) am the copyright holder of all contents distributed here.

