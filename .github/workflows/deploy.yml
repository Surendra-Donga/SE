name: Test Self-Hosted Runner

on: [push, pull_request]

jobs:
  test-runner:
    runs-on: self-hosted
    steps:
      - name: Checkout Code
        uses: actions/checkout@v3

      - name: Print System Info
        run: uname -a

      - name: List Files
        run: ls -alh
