## Data Menu - QA-Automation

### Project Overview
The Data Menu - QA-Automation project is designed specifically for RevenueRoll to scan client pages and identify whether they are utilizing particular HTML tags. This automation tool is developed and maintained by Data Menu [www.DataMenu.co.uk](https://www.datamenu.co.uk).

### Purpose
The primary purpose of the Data Menu - QA-Automation project is to automate the quality assurance process for RevenueRoll's client pages. By scanning the HTML of these pages, the tool identifies the presence or absence of specific tags, helping to ensure compliance with predefined standards or requirements.

### Features
- **Tag Detection**: The automation tool scans client pages to detect the presence of particular HTML tags.
- **Comprehensive Reporting**: Reports are generated (*csv*), highlighting which tags are present or missing on each scanned page.
- **Customizable Settings**: Users can customize the tags they want to check for, allowing flexibility in the QA process.
- **Scalability**: The tool is designed to handle scanning across a large number of client pages efficiently.

### Usage
To use the Data Menu - QA-Automation GitHub Action, include the following YAML in your workflow file:

```yaml
name: Data Menu QA-Automation

on:
  push:
    branches:
      - main

jobs:
  qa-automation:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v2

      - name: Run QA-Automation
        uses: node run.js

```

### Support and Feedback
For support or feedback regarding the Data Menu - QA-Automation project, please contact Data Menu at [corporate@datamenu.co.uk](mailto:corporate@datamenu.co.uk).

### License
This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it as per the terms of the license.

---
© 2024 Data Menu. All rights reserved.