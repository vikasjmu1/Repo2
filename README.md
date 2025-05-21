on:
  push:
    branches:
      - main

jobs:
  execute:
  uses: Repo2/.github/workflows/blank.yml@main
  secrets: inherit
