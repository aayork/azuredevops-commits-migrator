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

### _2025-08-05 16:08:00_ **[Placez] Merged PR 6023: Remove useEffect warning** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/ad3a3bdacdc7d7633afbd918cc81cf0f550c8ac5))

### _2025-08-22 20:08:00_ **[Placez] Merged PR 6156: Partial invoice UI updates** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/525c6a282b3619a2af0068c413ed805c7bc35da1))

### _2025-08-27 19:08:00_ **[Placez] Merged PR 6201: Fix text overflowing/clipping** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/b457b34ea1fd02734bea0e88a588fdd96aaa31b9))

### _2025-09-04 13:09:00_ **[Placez] Merged PR 6247: Display Payment ID in event details payments tab** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/33f5f69ee36a083cba0a939fe17434bf7691b62c))

### _2025-09-04 14:09:00_ **[Placez] Merged PR 6152: Change Default Material to White and Change Lighting in Floorplan Editor for Color Accuracy** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/63ffd84ddec9c846880a68eedcf48569a8b962f4))

### _2025-09-05 19:09:00_ **[Placez] Merged PR 6251: remove remove material button** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/db6a9019a116862a1f9c47beeac75c5474189597))

### _2025-09-29 17:09:00_ **[Placez] Merged PR 6388: Fix save error on apply everywhere button** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/86c2349018c0d7dc5ca5640afe28078cfe42e024))

### _2025-09-29 17:09:00_ **[Placez] Merged PR 6455: Invoice Editor UI - Custom Line Items** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/3ae1143faf3d0e63e3256407e88c64b24dc4a829))

### _2025-10-09 18:10:00_ **[Placez] Merged PR 6524: More UI changes** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/2058dc39ff45a43d0d55c65ad2ff311dc678787c))

### _2025-10-30 13:10:00_ **[Placez] Merged PR 6667: Implement payments page** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/8390e405529cce57fc74c4da0366fce95de152d6))

### _2025-11-17 14:11:00_ **[Placez] Merged PR 6735: Create payment links/requests grid** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/612800fa54a4cf50a782eeadb98af6c42dc8602b))

### _2025-11-19 15:11:00_ **[Placez] Merged PR 6673: dont allow payment link/request to be sent if the payment value is zero** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/b618b9d172724201dc9e92d3b5cc1708a3add9f0))

### _2025-12-04 21:12:00_ **[Placez] Merged PR 6885: Payment Links Settings and Basic Wireup** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/9deeb3300e2f040f38e1f194b882e2ee72f656ec))

### _2025-12-08 16:12:00_ **[Placez] Merged PR 6886: Minor adjustments to payment requests UI** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/cef860839633fd1869157860368ba2e63ae62e26))

### _2025-12-09 15:12:00_ **[Placez] Merged PR 6926: Overhaul manual payment collection UI/UX** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/2c9f39310db81fcf489cd31c7e7cbfa9aa8b471e))

### _2025-12-15 22:12:00_ **[Placez] Merged PR 6997: wireup save cc in client settings** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/e37c977190f27110440722c979579169b65d3bec))

### _2025-12-15 22:12:00_ **[Placez] Merged PR 6999: Show saved ccs in manual payment modal** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/7f812fd307d0e61ec5a3e4c3627da55df6231d8e))

### _2025-12-22 14:12:00_ **[Placez] Merged PR 7068: Payment Setup UI** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/49068e209a7a4c6fa86ee505210501c31c6cc886))

### _2026-01-13 13:01:00_ **[Placez] Merged PR 7179: remove tax percentages from invoice table and venue settings** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/fd4036987fd803f940094e96c308f5758c97f0c4))

### _2026-01-13 14:01:00_ **[Placez] Merged PR 7226: Fix build** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/25cdc5596808d1dcc032c915392cfc83b2c997f9))

### _2026-01-13 14:01:00_ **[Placez] Merged PR 7228: fix build again** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/b6c3561b75484e6cf1844fef40a5ad611078a696))

### _2026-01-13 19:01:00_ **[Placez] Merged PR 7235: Wireup invoice settings** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/186a79d627739748fb98a1e65e5871075a283604))

### _2026-01-20 16:01:00_ **[Placez] Merged PR 7297: change invoice download button functionality** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/a22f6e45cd56fc6ec4df7ed7f2c8e0be4fcadadb))

### _2026-01-27 13:01:00_ **[Placez] Merged PR 7351: wireup business info + show in invoice download** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/a3bd52998fea823b6e0666e36a3e11694e8632ac))

### _2026-02-02 23:02:00_ **[Placez] Merged PR 7424: Invoice PDF download + minor Invoice bug fixes** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/9a0e7db820aaef3875b61b1dfd9706c7eac32bbc))

### _2026-02-09 14:02:00_ **[Placez] Merged PR 7474: update notes styling to be more consistent** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/b4de33f4cc8a4ef2eec15e406cc972d3e4f853b8))

### _2026-02-09 20:02:00_ **[Placez] Merged PR 7479: handle cases where subevent template venue returns null** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/85a5403ccf370770ff3335832355ba62f389c144))

### _2026-02-02 23:02:00_ **[Placez] Merged PR 7424: Invoice PDF download + minor Invoice bug fixes** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/9a0e7db820aaef3875b61b1dfd9706c7eac32bbc))

### _2026-02-09 14:02:00_ **[Placez] Merged PR 7474: update notes styling to be more consistent** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/b4de33f4cc8a4ef2eec15e406cc972d3e4f853b8))

### _2026-02-09 20:02:00_ **[Placez] Merged PR 7479: handle cases where subevent template venue returns null** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/85a5403ccf370770ff3335832355ba62f389c144))

### _2026-05-06 20:05:00_ **[Placez] Merged PR 8162: show annotations in screenshots** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/c4f93d94659274b554481b1c05043680bed10600))

### _2026-05-07 21:05:00_ **[Placez] Merged PR 8163: save new labels immediately and reflect change without refresh** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/24f295a55f29822467a34bbb5db71acd8ed10bc0))

### _2026-05-07 21:05:00_ **[Placez] Merged PR 8164: potential fix for notes returning to previous spot glitch** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/b43bc5fc1d88cd5ca17c267f75825976ba41082e))

### _2026-05-11 12:05:00_ **[Placez] Merged PR 8167: render item labels when in b&w shader mode** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/cba14f848836a0c319ae8da5ce840f75d8aed7c7))

### _2026-05-11 12:05:00_ **[Placez] Merged PR 8168: add a check to make sure copied items have a media asset id** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/8ac0bf2969e08210b3260c073ba30b91eb3e5ed2))

### _2026-05-11 22:05:00_ **[Placez] Merged PR 8172: Fix overlapping names bug** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/ea4761efc648c54420bca41c47447ba035cfe003))

### _2026-05-12 16:05:00_ **[Placez] Merged PR 8174: add payments to placez** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/85a54e7cffaa168d07cc300a719098622b4e9623))

### _2026-05-12 21:05:00_ **[Placez] Merged PR 8176: Fix annotation rotation bugs in subevent editor** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/8e54c4aa5d652b0e648180cc9b4d5593f05e0244))

### _2026-05-13 13:05:00_ **[Placez] Merged PR 8178: fix potential race condition in print modal** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/021a084fc7941ff299ac1a34e318aa2730d5a9f5))

### _2026-05-13 19:05:00_ **[Placez] Merged PR 8179: Fix copy paste issue** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/3eab092252c3fc0252aa25ea957af017fe525e42))

### _2026-05-15 12:05:00_ **[Placez] Merged PR 8183: fix issues with saving/screenshotting subevent layouts** ([link](https://dev.azure.com/HorizonBusinessServices/Placez/_git/Placez/commit/6af6d961dcfcd21f6c4055eccf6140a743db923f))

