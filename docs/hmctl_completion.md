## hmctl completion

Generate completion script

### Synopsis

To load completions:

Bash:

  $ source <(hmctl completion bash)

  # To load completions for each session, execute once:
  # Linux:
  $ hmctl completion bash > /etc/bash_completion.d/hmctl
  # macOS:
  $ hmctl completion bash > /usr/local/etc/bash_completion.d/hmctl

Zsh:

  # If shell completion is not already enabled in your environment,
  # you will need to enable it.  You can execute the following once:

  $ echo "autoload -U compinit; compinit" >> ~/.zshrc

  # To load completions for each session, execute once:
  $ hmctl completion zsh > "${fpath[1]}/_hmctl"

  # You will need to start a new shell for this setup to take effect.

fish:

  $ hmctl completion fish | source

  # To load completions for each session, execute once:
  $ hmctl completion fish > ~/.config/fish/completions/hmctl.fish

PowerShell:

  PS> hmctl completion powershell | Out-String | Invoke-Expression

  # To load completions for every new session, run:
  PS> hmctl completion powershell > hmctl.ps1
  # and source this file from your PowerShell profile.


```
hmctl completion [bash|zsh|fish|powershell]
```

### Options

```
  -h, --help   help for completion
```

### Options inherited from parent commands

```
      --output-format string   Output format (default "pretty-print")
      --profile string         Configuration profile to use
```

### SEE ALSO

* [hmctl](hmctl.md)	 - 

###### Auto generated by spf13/cobra on 26-Sep-2022
