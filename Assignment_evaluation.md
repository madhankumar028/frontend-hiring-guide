## Application:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| Barebones, developer UI with no error/touch feedback to the user | 0 |
| Functional UI, and with error feedback and/or touch feedback | 1 |
| Polished UI, with thought put into the user experience and/or with nice transitions and animations | 2 |

## Documentation:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| No documentation in the repository | 0 |
| Some documentation with basic setup instructions or feature descriptions | 1 |
| Detailed documentation with setup, screenshots, configuration instructions, etc | 2 |

## Commit History:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| The repository has a few large commits (Exceptions are commits with auto-generated code like Room schemas or the initial commit when initialising a project through an IDE or a CLI)| 0 |
| The repository has some small-ish commits with clear (what the commit does) messages| 1 |
| The repository has many tiny, atomic commits with clear, descriptive (what the commit does and why, when appropriate) messages| 2 |

## Testing:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| There are either no tests, or a few tests that aren't really that useful| 0 |
| Tests for business logic are present, but they are tested via UI tests| 1|
| Business logic is tested using unit tests. The tests need not be comprehensive as long as they are testing important code paths| 2 |

## Separation of concerns:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| Business, presentation, and implementation logic are all mixed together (everything in the Activity/View/Fragment)| 0|
| There is some separation of concerns (ex: separate interface and classes for querying data/making network calls)| 1|
| Candidate has used a standard architecture pattern (MV*/others) or a library (Mobius/MvRx/others). The candidate could also have rolled their own architecture as long as there is clear documentation on their custom solution| 2 |

## Code maintainability:

| Key | Score |
| :--------------------------------------------------------------- | :----------:  |
| Names are unnecessarily short or meaningless. Ex: a, something, doWork, runQuery. An exception to this rule would be something like the iteration variable in a for loop| 0 |
| Names are mostly descriptive and indicative of the intent. Some names might occasionally be unclear without explanation| 1|
| Names are mostly descriptive and indicative of the intent. Unclear names have clear comments explaining the purpose of the variable/function and the intent behind it| 2 |


**NOTE: Minimun score required is 6**
