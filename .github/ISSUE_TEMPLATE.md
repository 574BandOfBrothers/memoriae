## Title

Titles of issues should be easily distinguishable and summarize the issue. Type of issue may be included to the title if it couldn't be labed. For example all spike tickets should be titled by prepending SPIKE: tag.

## Description

Descriptions should detaily describe the issue. It should be understanble to all readers, whether with a background for that issue or not.

### Task / Feature Issues

Required task / feature should be detailed in every aspect. If necessary requirements documents, design documents, relevant links should be included to the description.

### Bug Issues

Bugs should be explained detaily. All bug issues should include the following parts in addition to description

- Reproducing steps
  - What is expected
  - What happened
  - Error Output
  - If available screenshots
- Environment
- Browsers / Configurations

## Label

All issues should be labeled adequately. Issue may have multiple labels. Labeling is guided as following:
- **Feature**: Will be used for new features to the project
- **Bugfix**: Will be used for bug fixes, this is for development environment bugfixes.
- **Improvement**: Will be used for improvement tasks which are neither adds new features nor fixes a bug
- **Hotfix**: Will be used for critical bugfixes to the production environment which may not wait regular release cycle.
- **Task**: Will be used for tasks. It involves non code tasks.
- **Story**: Will be used for bigger features which may contain multiple smaller features. All smaller features should be created separately and linked to a story if necessary.
- **Epic**: Critical and big task which will effect multiple aspects of project. Epics can contain multiple stories and features.
- **Test**: Will be used for test related issues
- **Docs**: Will be used for documentation related issues

If necessary additional labels could be created.

## Project Assignment

Issues should be assigned to the Projects after creation and should be moved to Todo state. If the person ,s directly related to issue, opener of the issue may assign issue to a collabrator. Also, contributors may assign issues to themselves if they are going to work on that issue. If issue is a task, it should be assigned to only one contributor. If two person is needed for task it should be splitte into seperate tasks and main issue should be labeled as Story or Epic.
