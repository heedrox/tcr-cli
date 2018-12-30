# tcr-cli

A TCR (Test Commit Revert) command line utility for making it easier to develop through tcr

# TCR

TCR (test, commit || revert), is a new way of developing, with similar basics to TDD. But with added constraints.

TCR forces you to make baby steps, through one constraint: every time tests fail, you must revert your code.

Learn more about this here:

https://medium.com/@kentbeck_7670/test-commit-revert-870bbd756864

https://twitter.com/bberrycarmen/status/1062421008261541888

# Usage

You can use it inside your node repo.
- `npm install --save-dev tcr-cli`
- Add scripts for test, commit, revert and push.
- Execute `tcr-cli`.

You can find an example here:

https://github.com/jmarti-theinit/test-commit-revert-node

 
