<div align="center">

# :sparkles: Special GitHub Files :sparkles:

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Unlicense License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

</div>

## Description

A collection of [GitHub](https://github.com) repo files with brief explinations and links to deeper learnings.

## Usage

- Read through this READMEs [Special Files](#special-files) section to discover each of their uses.
- Investigate the "Learn more" links to discover additional details.
- Copy/paste from the examples if needed.
- If you find this repo interesting :star: it for future reference.

## FAQ

<details>
  <summary>Are all these files necessary?</summary>

Nope. Just use what you need.

</details>

<details>
  <summary>When should I name the file ending in .md?</summary>

Whenever you want the file to be visually rendered using [Markdown](https://guides.github.com/features/mastering-markdown/) features like headings, sections, lists, code example syntax coloring, clickable links, bold, italic, ... you should use `.md`.

</details>

<details>
  <summary>Why are filenames in all caps?</summary>

To avoid confusion with other files and to make them more noticeable as a "special" file.

</details>

---

## Special Files

- [.gitignore](#gitignore)
- [.nojekyll](#page_facing_up-nojekyll)
- [ACKNOWLEDGMENTS.md](#page_facing_up-acknowledgmentsmd)
- [CHANGELOG.md](#page_facing_up-changelogmd)
- [CITATION.cff](#page_facing_up-citationcff)
- [CODEOWNERS](#page_facing_up-codeowners)
- [CODE_OF_CONDUCT.md](#page_facing_up-code_of_conductmd)
- [gitigCONTRIBUTINGnore.md](#contributingmd)
- [CONTRIBUTORS.md](#page_facing_up-contributorsmd)
- [ISSUE_TEMPLATE.md](#page_facing_up-issue_templatemd)
- [LICENSE](#page_facing_up-license)
- [README.md](#page_facing_up-readmemd)
- [SECURITY.md](#page_facing_up-securitymd)
- [SUPPORT.md](#page_facing_up-supportmd)
- [UPGRADING.md](#page_facing_up-upgradingmd)
- [.github/FUNDING.yml](#page_facing_up-githubfundingyml)
- [.github/ISSUE_TEMPLATE/bug_report.md](#page_facing_up-githubissue_templatebug_reportmd)
- [.github/ISSUE_TEMPLATE/feature_request.md](#page_facing_up-githubissue_templatefeature_requestmd)

---

## Folder Structure

<pre>
├── .github
│   ├── FUNDING.yml
│   └── ISSUE_TEMPLATE
│       ├── bug_report.md
│       └── feature_request.md
├── .gitignore
├── .nojekyll
├── ACKNOWLEDGMENTS.md
├── CHANGELOG.md
├── CITATION.cff
├── CODEOWNERS
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── CONTRIBUTORS.md
├── LICENSE
├── README.md
├── SECURITY.md
├── SUPPORT.md
└── UPGRADING.md
</pre>

---

### :page_facing_up: `.gitignore`

  This file is used to tell Git which files and folders to ignore.

  Typical files and directories to ignore are:

- System files like `.DS_Store`
- Generated files such as `dist/` and `node_modules/`
- Files containing API keys, passwords, secrets or other sensitive information
- Log files in a directory such as `logs/`
- Files that are not part of the project
- Files that you don't want to share

  You can add a .gitignore file in your repository's root directory or any other folder to tell Git which files and directories to ignore when you make a commit. To share the ignore rules with other users who clone the repository, commit the `.gitignore` file in to your repository.

  GitHub maintains an official list of recommended `.gitignore` files for many popular operating systems, environments, and languages in the [github/gitignore](https://github.com/github/gitignore) public repository. You can also use [gitignore.io](https://www.gitignore.io/) to create a .gitignore file for your operating system, programming language, or IDE.

If you want to ignore a file that is already checked in, you must untrack the file before you add a rule to ignore it. From your terminal, untrack the file.

```shell
$ git rm --cached FILENAME
```

[GitHub Docs: Configuring ignored files for all repositories on your computer](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files#configuring-ignored-files-for-all-repositories-on-your-computer)

You can also create a global .gitignore file to define a list of rules for ignoring files in every Git repository on your computer. For example, you might create the file at ~/.gitignore_global and add some rules to it.

Configure Git to use the exclude file ~/.gitignore_global for all Git repositories.

```shell
$ git config --global core.excludesfile ~/.gitignore_global
```

[GitHub Docs: Excluding local files without creating a .gitignore file](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files#excluding-local-files-without-creating-a-gitignore-file)]

If you don't want to create a .gitignore file to share with others, you can create rules that are not committed with the repository. You can use this technique for locally-generated files that you don't expect other users to generate, such as files created by your editor.

Use your favorite text editor to open the file called `.git/info/exclude` within the root of your Git repository. Any rule you add here will not be checked in, and will only ignore files for your local repository.

1. Open Terminal.
2. Navigate to the location of your Git repository.
3. Using your favorite text editor, open the file `.git/info/exclude`.

#### Learn more

- [GitHub Docs: Ignoring files](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files)
- [git-scm.com/docs/gitignore](https://git-scm.com/docs/gitignore)
- [github/gitignore](https://github.com/github/gitignore)
- [gitignore.io](https://www.gitignore.io/)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `.nojekyll`

GitHub Pages will use Jekyll to build your site by default. If you want to use a static site generator other than Jekyll, disable the Jekyll build process by creating an empty file called `.nojekyll` in the root of your publishing source, then follow your static site generator's instructions to build your site locally.

Prevents GitHub Pages from ignoring files that begin with an underscore.

#### Learn more

- [GitHub Docs: About GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `ACKNOWLEDGMENTS.md`

ACKNOWLEDGMENTS.md lists of all contributors to your project.

This file sometimes is sometimes used similar to a `CONTRIBUTING.md` file.

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `CHANGELOG.md`

CHANGELOG.md lists of all the changes to your project.

This file might also be named CHANGES, HISTORY, NEWS, RELEASES, VERSIONS, etc.

Examples

- https://github.com/conventional-changelog/conventional-changelog/blob/master/packages/conventional-changelog/CHANGELOG.md
#### Learn more

- https://keepachangelog.com/en/1.0.0/
- https://github.com/conventional-changelog/conventional-changelog
- https://github.com/github-changelog-generator/github-changelog-generator

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `CITATION.cff`

You can add a CITATION.cff file to the root of a repository to let others know how you would like them to cite your work. The citation file format is plain text with human- and machine-readable citation information.

#### Learn more

- [GitHub Docs: About CITATION files](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-citation-files)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `CODEOWNERS`

Repository administrators can define exactly which people and teams need to review projects using the CODEOWNERS file. This feature automatically assigns reviewers based on Code Owners when a pull request changes any owned files, using the same syntax as the .gitignore file.

Use the CODEOWNERS file to ensure that changes to specific areas of the codebase are always reviewed by those with the most expertise.

#### Learn more

- [GitHub Docs: About code owners](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-code-owners)
- [GitHub Docs: Managing code review assignment for your team](https://docs.github.com/en/organizations/organizing-members-into-teams/managing-code-review-assignment-for-your-team)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `CODE_OF_CONDUCT.md`

A code of conduct defines standards for how to engage in a community. It signals an inclusive environment that respects all contributions. It also outlines procedures for addressing problems between members of your project's community. For more information on why a code of conduct defines standards and expectations for how to engage in a community, see the [Open Source Guide](https://opensource.guide/code-of-conduct/).

#### Learn more

- [GitHub Docs: Adding a code of conduct to your project](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `CONTRIBUTING.md`

To help your project contributors do good work, you can add a file with contribution guidelines to your project repository's root, `docs`, or `.github` folder. When someone opens a pull request or creates an issue, they will see a link to that file. The link to the contributing guidelines also appears on your repository's `contribute` page.

For the repository owner, contribution guidelines are a way to communicate how people should contribute.

For contributors, the guidelines help them verify that they're submitting well-formed pull requests and opening useful issues.

For both owners and contributors, contribution guidelines save time and hassle caused by improperly created pull requests or issues that have to be rejected and re-submitted.

#### Examples

- [github/docs Contributing to this repository](https://github.com/github/docs/blob/main/CONTRIBUTING.md)
- [github/docs/contributing/ Contributing to github/docs](https://github.com/github/docs/tree/main/contributing)

#### Learn more

- [GitHub Docs: Setting guidelines for repository contributors](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
- [GitHub Docs: Encouraging helpful contributions to your project with labels](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/encouraging-helpful-contributions-to-your-project-with-labels)
- [GitHub Docs: About community management and moderation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-management-and-moderation)
- [GitHub Docs: Setting up your project for healthy contributions](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions)
- [GitHub Docs: Encouraging helpful contributions to your project with labels](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/encouraging-helpful-contributions-to-your-project-with-labels)
- [GitHub Docs: Moderating comments and conversations](https://docs.github.com/en/communities/moderating-comments-and-conversations)
- [Open Source Guides: Building Welcoming Communities](https://opensource.guide/building-community/)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `CONTRIBUTORS.md`

CONTRIBUTORS.md is a file that lists all the contributors to a project. It is a great way to show your community that you care about your project and its members.

#### Learn more

- https://allcontributors.org/

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `LICENSE`

You can include an open source license in your repository to make it easier for other people to contribute.

When you include a detectable license in your repository, people who visit your repository will see it in the top right of the repository page.

If you go to "Add file" dropdown in your repo to create a new file and start naming with "License", a button will appear to the right for you to select a license template.

#### Learn more

- [GitHub Docs: Adding a license to a repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)
- [GitHub Docs: Licensing a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/licensing-a-repository)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `README.md`

README.md is the main file for your project. It's the first thing people see when they visit your project's GitHub page.

#### Learn more

- [GitHub Docs: About READMEs](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-readmes)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `SECURITY.md`

You can give instructions for how to report a security vulnerability in your project by adding a security policy to your repository.

When someone creates an issue in your repository, they will see a link to your project's security policy.

#### Learn more

- [GitHub Docs: Adding a security policy to your repository](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)
- [GitHub Docs: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `SUPPORT.md`

You can create a SUPPORT file to let people know about ways to get help with your project.

When someone creates an issue in your repository, they will see a link to your project's SUPPORT file.

#### Learn more

- [GitHub Docs: Adding support resources to your project](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-support-resources-to-your-project)
- [GitHub Docs: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `UPGRADING.md`

In this file you can provide instructions for users on how to upgrade to the latest version of your project.

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `.github/FUNDING.yml`

FUNDING file displays a sponsor button in your repository to increase the visibility of funding options for your open source project.

#### Learn more

- [GitHub Docs: Displaying a sponsor button in your repository](https://docs.github.com/en/github/administering-a-repository/managing-repository-settings/displaying-a-sponsor-button-in-your-repository)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `.github/ISSUE_TEMPLATE/bug_report.md`

When you create an issue template for your repository using the issue template builder or with issue forms, contributors can select the appropriate template when they open new issues in the repository.

Issue templates are helpful when you want to provide guidance for opening issues while allowing contributors to specify the content of their issues. If you want contributors to provide specific, structured information when they open issues, issue forms help ensure that you receive your desired information.

#### Learn more

- [GitHub Docs: Configuring issue templates for your repository](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)
- [About issue and pull request templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

### :page_facing_up: `.github/ISSUE_TEMPLATE/feature_request.md`

See [.github/ISSUE_TEMPLATE/bug_report.md](#page_facing_up-githubissue_templatebug_reportmd)

---

<div align="right">
  <a href="#special-files">Back to Special Files list :point_up:</a>
</div>

[contributors-shield]: https://img.shields.io/github/contributors/danpoynor/special-github-files.svg?style=for-the-badge
[contributors-url]: https://github.com/danpoynor/special-github-files/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/danpoynor/special-github-files.svg?style=for-the-badge
[forks-url]: https://github.com/danpoynor/special-github-files/network/members
[stars-shield]: https://img.shields.io/github/stars/danpoynor/special-github-files.svg?style=for-the-badge
[stars-url]: https://github.com/danpoynor/special-github-files/stargazers
[issues-shield]: https://img.shields.io/github/issues/danpoynor/special-github-files.svg?style=for-the-badge
[issues-url]: https://github.com/danpoynor/special-github-files/issues
[license-shield]: https://img.shields.io/github/license/danpoynor/special-github-files.svg?style=for-the-badge
[license-url]: https://github.com/danpoynor/special-github-files/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/danpoynor