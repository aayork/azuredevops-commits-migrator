# Azure DevOps to GitHub Migration Tool

Github profile is so boring when no activity is there when you work at a company that use Azure Devops.

This project helps users automate the migration of commits and Pull Requests (PRs) from an Azure DevOps repository to a GitHub repository. It uses a GitHub workflow to automate the migration process.


# Getting Started
1. Fork this repository\
  Click the Fork button in the top-right corner of this page to fork the master repository.

2. Go to forked repo in your repository

3. Add secrets:\
  settings -> Actions secrets and variables -> Repository secrets -> New repository secrets
  ![alt text](resources/image.png)

    ```bash
    PAT  # Your Azure PAT, you'll know how to get it below

    USER_EMAIL  # Your GITHUB user email

    USER_NAME # Your GITHUB user name

    AZURE_NAME  # YOUR username on Azure

    # Set this number to 1, unless you want to fetch all the previous history
    DAYS_LOOKUP

    # This is Github PAT, you'll know how to set below
    GH_WRITE_TOKEN

    # Your Azure DevOps Organization name (e.g. `dev.azure.com/abcd` abcd is the value)
    ORG
    
    # Your destination Github Repository e.g. `Iwan-LMX/azuredevops-commits-migrator` is the value, see below for setting it
    TRACKER_REPO
    ```
6. Run the workflow\
	Actions -> Sync commits with azure devops -> run workflow
	![alt text](resources/image2.png)

## Set Github PAT
Click your avatar in github, find settings -> Develop settings -> Personal access tokens (classic) / Fine-grained personal access tokens -> make sure the your target github repo is covered in the `Repository access`. [Add token](https://github.com/settings/personal-access-tokens).

## Set Azure PAT
user settings (in your project right top) -> Personal access tokens -> New token (Simply give all access)

## For the TRACKER_REPO
For this repo you can choose private or public as you want. But this default branch name should be `master`

<!-- Written by [Iwan Li](https://github.com/Iwan-LMX) -->### _2025-06-09 15:06:00_ **[Placez] Merged PR 5575: UI Fixes for Floorplan Favorite Notes** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/02b7d20ce20c1365e8fe1596878a4cf1dd31efc8))

### _2025-07-03 17:07:00_ **[Placez] Merged PR 5576: Add scrollbar to asset list** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/9500127c85e4a167d376f7c265d3db80a4826d9b))

### _2025-07-03 18:07:00_ **[Placez] Merged PR 5736: Adjust zoom on iframe to remove scrollbar** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/771bff9a6ae360fa841ef6c58c3c1de3458441f4))

### _2025-07-03 18:07:00_ **[Placez] Merged PR 5760: remove label size slider** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/7fdc118beaad05601c251d347e6b9520ed116e31))

### _2025-07-07 17:07:00_ **[Placez] Merged PR 5770: first floorplan selected when entering page** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/85218ad9bc06f79897b630505835822089a1558a))

### _2025-07-07 17:07:00_ **[Placez] Merged PR 5757: Make invoice item lines selectable** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/0aa5512b94d9da12709b160aa8a9423343984742))

### _2025-07-07 19:07:00_ **[Placez] Merged PR 5793: edit name without needing to add subevent** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/fc66db8ec2ca2dba27168a505c5ba7a2a0df2439))

### _2025-07-08 14:07:00_ **[Placez] Merged PR 5796: Fix type error** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/7a33ca85d171884ecdb1a7b09559ffa316d0a268))

### _2025-07-08 18:07:00_ **[Placez] Merged PR 5810: Fix build error** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/93b2b786461990665d5dab2b111bf83f336a2520))

### _2025-07-11 19:07:00_ **[Placez] Merged PR 5785: filter payments by event id** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/ce3ba41dd3c2d2c5fa476cc07f485bcef2913650))

### _2025-07-11 20:07:00_ **[Placez] Merged PR 5843: add group item tooltips** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/36cc75813aff8d1511bcbc58c871446b1190eea6))

### _2025-07-14 18:07:00_ **[Placez] Merged PR 5849: Changes to Floorplan Wall, Floor, and Height Editors** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/458a29b15e9a2213546fe2a5e28dbc1c8a17b0af))

### _2025-08-01 20:08:00_ **[Placez] Merged PR 5999: Show floorplan on creation of new venue** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/95448e36ccc4ed0bb7a736f812f0f99f5caf4216))

