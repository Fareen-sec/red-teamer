# ATT&CK® Navigator

The ATT&CK Navigator is designed to provide basic navigation and annotation of [ATT&CK](https://attack.mitre.org) matrices, something that people are already doing today in tools like Excel.  We've designed it to be simple and generic - you can use the Navigator to visualize your defensive coverage, your red/blue team planning, the frequency of detected techniques or anything else you want to do.  The Navigator doesn't care - it just allows you to manipulate the cells in the matrix (color coding, adding a comment, assigning a numerical value, etc.).  We thought having a simple tool that everyone could use to visualize the matrix would help make it easy to use ATT&CK.

The principal feature of the Navigator is the ability for users to define layers - custom views of the ATT&CK knowledge base - e.g. showing just those techniques for a particular platform or highlighting techniques a specific adversary has been known to use. Layers can be created interactively within the Navigator or generated programmatically and then visualized via the Navigator.

## Usage

The ATT&CK Navigator is hosted live via GitHub Pages. [You can find a live instance of the current version of the Navigator here](https://mitre-attack.github.io/attack-navigator). You can read more about how to use the application itself in the [USAGE](/USAGE.md) document (which is mirrored in the in-app help page).

Version 4.0 of the ATT&CK Navigator supports all ATT&CK domains in a single instance of the application instead of requiring a different instance for each domain. It also sees the introduction of support for the ICS domain. See [the changelog](CHANGELOG.md) for more information.

Additionally, older versions of ATT&CK can now be loaded in the application. The ATT&CK Navigator supports ATT&CK versions 8, 7, 6, 5, and 4. Older versions do not work in the application since their data model is too outdated.

