## Application:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| Barebones, developer UI with no error/touch feedback to the user. Generalised as error handling in the UI. | 0 |
| Functional UI, with error handling, and proper notifications (success/error) to the user. | 1 |
| Polished UI, with thought put into the user experience, and with nice transitions and animations. | 2 |

## Documentation:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| No documentation in the repository | 0 |
| Documentation with basic setup instructions or feature descriptions | 1 |
| Detailed documentation with setup, screenshots if required, configuration instructions, etc | 2 |

## Commit History:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| The repository has a few large commits (Exceptions are commits with auto-generated code by CLI (create react app))| 0 |
| The repository has some small-ish commits with clear (what the commit does) messages| 1 |
| The repository has many tiny, atomic commits with clear, descriptive (what the commit does and why, when appropriate) messages| 2 |

## Testing: (optional based on your exceptation, but I would recommend)

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| There are either no tests, or a few tests that aren't really that useful| 0 |
| Tests for business logic are present, but they are tested via UI tests| 1|
| Business logic is tested using unit tests. The tests need not be comprehensive as long as they are testing important code paths| 2 |

## Separation of concerns:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| Business, presentation, and implementation logic are all mixed together (everything in the Model/View/Controller)| 0|
| There is some separation of concerns (ex: component abstraction, utilities for querying data/making network calls)| 1|
| Candidate has used a standard architecture pattern (MV*/others)| 2 |

## Code maintainability:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| Names are unnecessarily short or meaningless. Ex: a, something, doWork, runQuery.| 0 |
| Names are mostly descriptive and indicative of the intent. Some names might occasionally be unclear without explanation| 1|
| Names are mostly descriptive and indicative of the intent. Unclear names have clear comments explaining the purpose of it| 2 |


**NOTE: Minimun score required is 6**

