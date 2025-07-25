## rocketship run

Run rocketship tests

### Synopsis

Run rocketship tests from YAML files. Can run a single file or all tests in a directory.

```
rocketship run [flags]
```

### Options

```
  -a, --auto                      Automatically start and stop the local server for test execution
      --branch string             Git branch name (auto-detected if not specified)
      --commit string             Git commit SHA (auto-detected if not specified)
  -d, --dir string                Path to directory containing test files (will run all rocketship.yaml files recursively)
  -e, --engine string             Address of the rocketship engine (default "localhost:7700")
      --env-file string           Load environment variables from .env file
  -f, --file string               Path to a single test file (default: rocketship.yaml in current directory)
  -h, --help                      help for run
      --metadata stringToString   Additional metadata key=value pairs (default [])
      --project-id string         Project identifier for test run tracking
      --schedule-name string      Schedule name for scheduled runs
      --source string             Run source: cli-local, ci-branch, ci-main, scheduled
  -t, --timestamp                 Show timestamps in log output
      --trigger string            Trigger type: manual, webhook, schedule
  -v, --var stringToString        Set variables (can be used multiple times: --var key=value --var nested.key=value) (default [])
      --var-file string           Load variables from YAML file
```

### Options inherited from parent commands

```
      --debug   Enable debug logging
```

### SEE ALSO

* [rocketship](rocketship.md)	 - Rocketship CLI

###### Auto generated by spf13/cobra on 15-Jul-2025
