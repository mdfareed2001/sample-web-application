# testing
name: testing
on: push

jobs:
  Job-github-actions-running-workflow:
    runs-on: ubuntu-latest
    steps:
      - name: Run a one-line script
        run: echo "STARTED GitHub Actions workflow "
 
