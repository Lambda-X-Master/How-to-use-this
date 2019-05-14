# Setup Github Organizations for Labs

## Step One - Create a new GitHub Organization

In the upper right corner, click the + button and choose `New organization`

<div align="center"><img src="./images/step.png" ></div>
<br>
<br>

## Step Two - Name the project

Provide the name of your team's project. Keep in mind the naming convention used: `labs(cohort)-project-name.` You need to add a billing email, but will not be billed for an open source team.

<div align="center"><img src="./images/step2.png" ></div>

Then click create organization

<div align="center"><img src="./images/step2_1.png" ></div>

</center>

## Step Three - Skip inviting members for now

Skip inviting members to the organization until the repos are setup.

<div align="center"><img src="./images/step3.png"></div>

## Step Four - Skip this step

No need to fill out the data on this page, scroll to the bottom and click "skip this step."

<div align="center"><img src="./images/step4.png"></div>

## Step Five - Create a new repository

Click Create a New Repository. Repeat this step for frontend, backend, and if applicable add Andriod, iOS, and data science.

<div align="center"><img src="./images/step5.png"></div>

<div align="center"><img src="./images/step5-1.png"></div>

## Step Six - Copy the master markdown files to the new repo

Navigate to the [Labs-Master organization](https://github.com/labs-master) and choose the repository you wish to duplicate.

<div align="center"><img src="./images/step6.png"></div>

Open the readme file and open the raw version

<div align="center"><img src="./images/step6-1.png"></div>

Select all then copy and paste the text into the readme of the organization using the edit option.

<div align="center"><img src="./images/step6-2.png"></div>

Commit the changes

<div align="center"><img src="./images/step6-3.png"></div>

#### Repeat this process for any other markdown files in the repo you are duplicating

## Step Seven - Add rules to master branch

In each separate repository go to settings -> branches and click `add rule.`

<div align="center"><img src="./images/step7.png"></div>

Branch name pattern = master

<div align="center"><img src="./images/step7-1.png"></div>

Check the following boxes and set the required approving reviews to two.

<div align="center"><img src="./images/step7-2.png"></div>

### `Make sure to do this for every repository in the organization.`

## Step Eight - Invite members to the team

One organization page click the people tab then `invite member.`

<div align="center"><img src="./images/step8.png"></div>

If they are a PM or higher, give them the role of `Owner.` Students get the role of `Member.`

<div align="center"><img src="./images/step8-1.png"></div>

## Step Nine - Give Members Write Access

In every repository in the organization go to settings -> member privileges and change the base permission from read to write.

<div align="center"><img src="./images/step9.png"></div>
