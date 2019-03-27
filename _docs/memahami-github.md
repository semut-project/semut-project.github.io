# Account
Account dibuat dengan sign up. Setelah account jadi maka account mendapat URL sbb:
* `https://github.com/<nama-account>`. Ini adalah halaman muka account
* `https://<nama-account>.github.io`. Ini adalah halaman Github page.

Setiap account dapat membuat:
* organisasi. Organisasi shared account.
* repository. Repository adalah Wadah untuk menyimpan arterfact-artefact.
* project. Project adalah bentuk lain repository yang berfungsi untuk mengorganisasi proyek.
* page. Page adalah website account.
* gist. Gist Adalah bentuk lain dari repository yang berfungsi untuk share notes, code dan snippet.

## Account Page / Organization Page
The source files for User and Organization Pages sites live on the `master` branch in a dedicated *repository named with special naming scheme*:
* To create a User Pages site, name the repository using the naming scheme `<username>.github.io`.
* To create an Organization Pages site, name the repository using the naming scheme `<orgname>.github.io`.

# Repository
A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

# project
Project boards on GitHub help you organize and prioritize your work. You can create project boards for specific feature work, comprehensive roadmaps, or even release checklists. With project boards, you have the flexibility to create customized workflows that suit your needs.

Pada setiap project dapat dibuat:
* page.
* repository.


## Project Page
The source files for Project Pages sites live within the same repository as their project, and they are published from one of the following locations:

* The `master` branch
* The `gh-pages` branch
* A folder named "docs" located on the `master` branch

Project Page dapat di acu dengan
`https://<nama-account>.github.io/<nama-project>`
