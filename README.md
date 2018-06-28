# artstor-frontend-standards
Purpose: Centralized repo for Artstor open source standards and repo info

## Artstor Repositories
[Arstor Image Workspace](/ithaka/aiw-ui)
[Artstor Admin Tool](/ithaka/ang-ui-admin)
[Ithaka Image Viewer](/ithaka/ng-artstor-viewer)

## Commit Standards

* Separate subject from body
    * git commit -m “subject” -m “body with more info”
* Limit the subject line to 50 characters
* Use the imperative mood in the subject line (tip: start with a verb!), eg:
    * Remove Adobe analytics events
    * Add filter icon
    * Refactor load user function
* Include component/area of app being modified, eg:
    * Search: Update to autocomplete
    * Asset Page: Show more metadata
    * Login: Add password requirements
* Indicate work in progress or commits that break builds with “WIP”
    * WIP Search: Add category facets
    * WIP Layout: Improve text line heights
* Indicate commits that include dependency changes with install command, eg:
    * [yarn install] Search: Add autocomplete package
* Use the body to explain what and why vs. how
    * “How” is in the code!
* Speak as if you are speaking on behalf of Ithaka, keep it clean
* Do not include any personal or company information
