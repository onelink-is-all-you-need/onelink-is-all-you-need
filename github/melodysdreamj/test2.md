# Description & How to use
A brief Description of the script. and how to use this script.

## Quick Run Link
- [OneClickAll Link](http://oneclickall.com/your-script)

## Script
```yaml
Config:
  project_folder: Test # only application type use this, if plugin type, leave this blank

Shell Script Code:
  Default:
    MacOS: | # if not use this OS, leave this blank
      Code to run this script on MacOS
    Windows: | # if not use this OS, leave this blank
      Code to run this script on Windows
    Linux: | # if not use this OS, leave this blank
      Code to run this script on Linux
  ReInstall:
    MacOS: | # if not use this OS, leave this blank
      Code to run this script on MacOS
    Windows: | # if not use this OS, leave this blank
      Code to run this script on Windows
    Linux: | # if not use this OS, leave this blank
      Code to run this script on Linux
  Launch:
    MacOS: | # if not use this OS, leave this blank
      Code to run this script on MacOS
    Windows: | # if not use this OS, leave this blank
      Code to run this script on Windows
    Linux: | # if not use this OS, leave this blank
      Code to run this script on Linux

User Input Format:
  Description: |
    (Description line 1)
    (Description line 2)
    (Description line 3)
    Test2
  Parameters:
    parameter1:
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        (default value of parameter1)
    parameter2:
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        (default value of parameter2)

Script Imports:
  - Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test5.md
    ActivationCondition:
      type: "onStart"
    TerminalID: "project1_own" # this is the instance where the script runs
    Parameters:
      parameter1:
        Type: "Text"
        Description: "Describe yourself:"
        Default: |
          value1
          value1 continued
      parameter2:
        Type: "Text"
        Description: "Describe yourself:"
        Default: |
          value2
          value2 continued

  - Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test6.md
    ActivationCondition:
      type: "onStart"
    TerminalID: "project2_own"
    Parameters:
      parameter1:
        Type: "Text"
        Description: "Describe yourself:"
        Default: |
          value3`
          value3 continued
      parameter2:
        Type: "Text"
        Description: "Describe yourself:"
        Default: |
          value4
          value4 continued


Document Version: v1 # do not edit this. this is for document parser

```

## Authors
[AuthName](http://oneclickall.com/your-script), ...