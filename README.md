1 - Install cobra
```go install github.com/spf13/cobra-cli@latest```

2 - Init
```cobra-cli init```

3 - Add commands
```cobra-cli add <command>````

4 - Edit ./cmd/<command>.go

5 - Add flags to init()

6 - Add child cmds:
    - ```cobra-cli add create -p '<fathercmd><command>'```

