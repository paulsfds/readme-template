# <App Name>

## How To Get Started

   1. git clone <repo>
   2. Install [Bundler](http://bundler.io/)
   3. Install [CocoaPods](http://cocoapods.org/): bundle install
   4. Install Pods: bundle exec pod install
   5. Open <name>.xcworkspace in XCode

## Development

### Adding Code
* Before writing code, please refer to the Coding Standards below.
* Create local development branch (generally labeled with current task ID in Jira).
* When committing code and writing the commit message, the first line should contain the JIRA ticket, and a short description; this line should be less than 80 characters so that it does not get truncated. If you need to add additional comments, you can add more below the first line. Here is an example:

> [APP-123] A short description here that doesn't exceed 80 chars

> Additional comments here if necessary.

* Assign pull request for code review.
* Reviewer reviews the code, and then gives a thumbs up.
* Developer addresses comments from the review (if there were any) and pushes the changes.
* Developer squashes commits before merging to master (up to the developer's discretion). Please refer to this if you need help [How to Merge Code and Rebase](https://github.com/paulsfds/git-merge-workflow).
* Developer merges pull request.
* Jira task is then moved in to the "Done" state.

## Coding Standards
* [Coding Standards Wiki Page](https://github.com/paulsfds/objective-c-style-guide)
* tl;dr - Install the ClangFormat XCode plugin and use the .clang-format file stored in the repository.
