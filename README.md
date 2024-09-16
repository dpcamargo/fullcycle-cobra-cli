# Fullcycle-Cobra-CLI

1 - Install cobra ```go install github.com/spf13/cobra-cli@latest```

2 - Init ```cobra-cli init```

3 - Add commands ```cobra-cli add <command>```

4 - Edit ./cmd/<command>.go

5 - Add flags to init()

6 - Add child cmds:
    - ```cobra-cli add create -p '<fathercmd><command>'```

7 - Persistent flags: Flag is global from this command and it's children.

8 - Flag with P (VarP, StringP) have shorthand name

9 - VarP sets value to variable

10 - Hooks allow to 