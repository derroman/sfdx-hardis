# allowPurgeFailure

Allows purges to fail without exiting with 1. Use --no-allowpurgefailure to disable

# apexTests

Run apex test cases on org

# auditApiVersion

Audit API version

# auditCallInCallOut

Generate list of callIn and callouts from sfdx project

# auditRemoteSites

Generate list of remote sites

# checkOnly

Only checks the deployment, there is no impact on target org

# createOrgShape

Updates project-scratch-def.json from org shape

# completeWorkTask

When a work task is completed, guide user to create a merge request

# dataTreeExport

Assisted export data defined in .sfdx-hardis.yml

# debugMode

Activate debug mode (more logs)

# deployMetadatas

Deploy metadatas to source org

# exceptFilter

Allow to take all item except these criteria

# failIfError

Fails (exit code 1) if an error is found

# filteredMetadatas

Comma separated list of Metadatas keys to remove from PackageXml file

# folder

Folder

# forceNewScratch

If an existing scratch org exists, do not reuse it but create a new one

# installFFLib

Install FFLib in current project

# instanceUrl

URL of org instance

# loginToOrg

Login to salesforce org

# minimumApiVersion

Minimum allowed API version

# nameFilter

Filter according to Name criteria

# newWorkTask

New work task

# orgFreezeUser

Freeze mass users in org for maintenance or go live purpose

# orgCommunityUpdate

Update a community status.

# orgCommunityUpdateDesc

Activate or deactivate a community by changing it's status:

- Live
- DownForMaintenance

# orgDataExport

Export data from org using sfdmu

# orgDataImport

Import data in org using sfdmu

# orgPurgeFlow

Purge Obsolete flow versions to avoid the 50 max versions limit. Filters on Status and Name

# orgfreezeUser

Mass freeze users in org before a maintenance or go live

See user guide in the following article

<https://medium.com/@dimitrimonge/freeze-unfreeze-users-during-salesforce-deployment-8a1488bf8dd3>

[![How to freeze / unfreeze users during a Salesforce deployment](https://github.com/hardisgroupcom/sfdx-hardis/raw/main/docs/assets/images/article-freeze.jpg)](https://medium.com/@dimitrimonge/freeze-unfreeze-users-during-salesforce-deployment-8a1488bf8dd3)

# orgUnfreezeUser

Mass unfreeze users in org after a maintenance or go live

See user guide in the following article

<https://medium.com/@dimitrimonge/freeze-unfreeze-users-during-salesforce-deployment-8a1488bf8dd3>

[![How to freeze / unfreeze users during a Salesforce deployment](https://github.com/hardisgroupcom/sfdx-hardis/raw/main/docs/assets/images/article-freeze.jpg)](https://medium.com/@dimitrimonge/freeze-unfreeze-users-during-salesforce-deployment-8a1488bf8dd3)

# packageCreate

Create a new package

# packageInstall

Install a package

# packageInstallationKey

installation key for key-protected package (default: null)

# packageVersionCreate

Create a new version of an unlocked package

# packageVersionList

List versions of unlocked package

# packageXml

Path to package.xml manifest file

# prompt

Prompt for confirmation (true by default, use --no-prompt to skip)

# refreshWorkTask

Make my local branch and my scratch org up to date with the most recent sources

# retrieveDx

Retrieve Salesforce DX project from org

# retrieveMetadatas

Retrieve metadatas from an org with package.xml manifest

# sandboxLogin

Use if the environment is a sandbox

# scratch

Scratch org

# scratchCreate

Create and initialize a scratch org so it is ready to use

# rebuildSelection

Process again the selection of the items that you want to publish to upper level

# selectOrg

Interactive org selection for user

# statusFilter

Filter according to Status criteria

# tempFolder

Temporary folder

# testLevel

Level of tests to apply to validate deployment

# testLevelExtended

Level of tests to validate deployment. RunRepositoryTests auto-detect and run all repository test classes

# websocket

Websocket host:port for VsCode SFDX Hardis UI integration

# withDevHub

Also connect associated DevHub

# runtests

Apex test classes to run if --testlevel is RunSpecifiedTests