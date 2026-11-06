
name: MARKETRA DIGITAL Automation

on:
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  automation-test:
    name: First Automation Test
    runs-on: ubuntu-latest

    steps:
      - name: Checkout Repository
        uses: actions/checkout@v4

      - name: Welcome Message
        run: echo "Welcome to MARKETRA DIGITAL!"

      - name: Brand Tagline
        run: echo "POWERING DIGITAL GROWTH"

      - name: Automation Status
        run: echo "Your first automation is running successfully!"

      - name: Show Date
        run: date
