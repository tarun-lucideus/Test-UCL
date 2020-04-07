# UCL - Unified Control List
The aim of the UCL is to provide the security analysts with the platform to maintain the repository of ever evolving cyber threats at one place. Moreover, the security assessment control checklist should always be in sync and updated with the latest controls to eliminate false negative results.

## Introduction

UCL is a unified list of security controls/vulnerabilities and test cases applicable on Web, Android and iOS application security. All the vulnerabilities are compliant to various global security standards such as OWASP, CWE etc.

Each and every vulnerability (test cases) in UCL contains the following:
* **Vulnerability ID** - Unique ID assigned to each vulnerability
* **Control Group** - High level vulnerability group such Authentication, Authorization etc.
* **Tentative Severity** - Risk rating of the vulnerability
* **Description** - Brief explanation of the identified vulnerability
* **Audit Guidelines** - Automated and Manual steps to check the presence of vulnerability
* **Impact** - Impact of the vulnerability on an individual, organisation or infrastructure
* **Recommendations** - Recommended patch to mitigate the vulnerability
* **Classification** - Vulnerability mapping to the security standards
* **References** - External links to provide more information about the vulnerability
* **Applicability** - Vulnerability applicability: Applications Traffic/Web Traffic/Android-Static/Android-Dynamic/iOS-Static/iOS-Dynamic
* **Verticals** - Vulnerability verticals: Applications/Web/Android/iOS/Network

Security analysts across teams can contribute to UCL in order to add/delete/modify the security controls. To know more, refer to the [UCL process document](Process.pdf)

## Reviewer Authority
For pull request in each practice, three reviewers are required. Out of these three reviewers, the mandatory two are mentioned below and the third one is optional.
* **iOS** - Sahil Pahwa & Vibhav Dudeja
* **Android** - Silky Choudhary & Rubal Jain
* **Traffic Analysis/Web** - Deepak Pawar & Rishu Ranjan

## Detailed Steps
*   [Create Github Account](#create-github-account)
*   [Fork the Repository](#fork-the-repository)
*   [Adding a New Control](#adding-a-new-control)
*   [Editing Existing Control](#editing-existing-control)
*   [Syncing Local Fork with Upstream](#syncing-local-fork-with-upstream)
*   [Making a Pull Request](#making-a-pull-request)
*   [Pull Request Review](#pull-request-review)
*   [Creating an Issue](#creating-an-issue)

### Create Github Account
---
1.  Go to [Github](https://github.com).
2.  Click on Sign Up.
3.  Enter all the details.

     <kbd><img src="assests/step_1_1.png" /></kbd>
    
4.  You are good to go now. Let’s contribute now.


### Fork the Repository
---
``A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the UCL​. Since all the changes made in the forked repository are not synced with the UCL, you will have to make a pull request to UCL in order to get your content approved and merged.``

1.  You will receive an email invite to join the organization. Join the organisation.

    <kbd><img src="assests/step_2_1.png" /></kbd>

2.  Go to the organisation’s repository.
3.  Click on ​**Fork**​ and select your username.

    <kbd><img src="assests/step_2_2.png" /></kbd>

4.  You can see the forked repository in your profile.

    <kbd><img src="assests/step_2_3.png" /></kbd>


### Adding a New Control
---
1.  Click on ​**Create new file**​ .

    <kbd><img src="assests/step_3_1.png" /></kbd>

2.  Use **"/"** to create directories and subdirectories and create a **main**(.md) file to add control details. e.g **Vulnerability-Class/Vulnerability-Name/main.md**. You can also create a new file at specific folder inside the path **Vulnerability-Class Vulnerability-Name/** for existing vulnerabilities.

    <kbd><img src="assests/step_3_2.png" /></kbd>

3.  Write the details of new controls.
4.  Commit the changes.

    <kbd><img src="assests/step_3_3.png" /></kbd>


### Editing Existing Control
---
1.  Browse through the repository to make changes to the file.

     <kbd><img src="assests/step_4_1.png" /></kbd>

2.  Click on the **Pencil**​ icon to edit the file.

    <kbd><img src="assests/step_4_2.png" /></kbd>

3.  Commit new changes with title and description.

    <kbd><img src="assests/step_4_3.png" /></kbd>


### Syncing Local Fork with Upstream
---
``When you create a ​ fork​ of a ​ repository​ you only have the versions of the files that are in the repository at that time. So if there are any changes in the original repository you may find that your version is out of sync.``

<kbd><img src="assests/step_5_1.png" /></kbd>

1.  Click on ​ **Compare**​.

    <kbd><img src="assests/step_5_2.png" /></kbd>

2.  We need to change the ​ **base repository**​ and ​ **head repository**​ to fetch from upstream(change the branch, if needed).

    <kbd><img src="assests/step_5_3.png" /></kbd>

3.  Change the ​ **head**​ fork to the upstream (original) repository (here, Test-ECS/Test-Unified-Control-List).
4.  Click on ​**compare across forks​**.

    <kbd><img src="assests/step_5_4.png" /></kbd>

5.  Change **base**​ repository to the forked (your) repository (here, swarnim-ecsiOS/Test-Unified-Control-List) and click on Create pull request.

    <kbd><img src="assests/step_5_5.png" /></kbd>

6.  **Create pull request**​ by adding title and description.

    <kbd><img src="assests/step_5_6.png" /></kbd>

7.  You will see the created **Pull request** under the ​Pull requests​ tab. Click on it.

    <kbd><img src="assests/step_5_7.png" /></kbd>

8.  Click on ​**Merge pull request​**.

    <kbd><img src="assests/step_5_8.png" /></kbd>

9.  Click on ​**Confirm merge**​ to sync your local fork.

    <kbd><img src="assests/step_5_9.png" /></kbd>

10. Your local fork will be synced with the upstream (original) repository.

    <kbd><img src="assests/step_5_10.png" /></kbd>


### Making a Pull Request
---
``Analysts must ensure to create separate PRs for every change made in the controls, instead of updating the current PR.``
1.  Check your git repo is up-to-date with unified control list repo and fetch upstream changes.
2.  Once confirmed that your git is up-to-date with the main UCL repo click on the ​ **New pull request​** under the ​ **Pull Requests**​ tab.

    <kbd><img src="assests/step_6_1.png" /></kbd>

3.  Compare the changes across the forks.
4.  Use the compare branch drop-down menu to choose the topic branch you made your changes in.
5.  Type a title and description for your pull request.
6.  Click on ​**Create pull request​**.

    <kbd><img src="assests/step_6_2.png" /></kbd>


### Pull Request Review
---
1.  Request a review in Reviewers option under Pull requests.

    <kbd><img src="assests/step_7_1.png" /></kbd>

2.  A reviewer can ​ **Comment**​, **Approve**​ or **Request changes**​ on a Pull request.

    <kbd><img src="assests/step_7_2.png" /></kbd>

3.  A reviewer can also add **​Labels**​ to the Pull requests.

    <kbd><img src="assests/step_7_3.png" /></kbd>

4.  Resolving all issues then a Pull request can be merged by clicking on the **Merge pull request**.

    <kbd><img src="assests/step_7_4.png" /></kbd>


### Creating an Issue
---
1.  Click on ​**Issues**.

    <kbd><img src="assests/step_8_1.png" /></kbd>

2.  Click on ​**New issue** ​under **Issues** ​tab.

     <kbd><img src="assests/step_8_2.png" /></kbd>

3.  Add Issue title and description. You can also mention the Pull request number. Click on ​ **Submit new issue** to create an Issue.

     <kbd><img src="assests/step_8_3.png" /></kbd>

