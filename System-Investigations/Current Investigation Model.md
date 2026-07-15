### V0.3
- NOTE: Terminology will generally use "System" and "Investigation" interchangeably. Technically each folder is a "System Investigation" so I'm comfortable with this.
- Each System is in its own folder within the Investigations folder.
	- A System folder begins with I-XXX-(name)-SMVX.X
	- XXX is the investigation number (001, 002 etc)
	- (name) is the short, descriptive name of the system
	- SMVX.X is the System Model Version that the system was built with.
- Each System contains an XXX-README file
	- XXX is the system number, as stated in the Folder name.
	- The README file contains the simple question, and basic premise, of the investigation in a few sentences.
	- The README file contains Scope for the investigation: what should be included, and what should not be included.
	- The README file contains a Next Version Goal, or the required state for the model to move to its next version.
	- The README file contains a Current Status section, describing current phase and next action for the model.
- Each System contains a "notes" folder
	- This is a general catch-all for written notes. My takeaway from sources, my observations or connections between sources, etc.
	- For now, there is no strict rule on the notes in this folder: purely vibes-based.
	- A note is either an Observation or a Question. It should follow the given template.
- Each System contains a "diagrams" folder
	- This is for diagrams I have created to help illustrate concepts.
	- Again, for now, no restrictions on the diagrams themselves.
	- Base idea: try to use them for complex structures that are hard to keep in ones head.
- Each System contains a "sources" folder
	- Wherever possible this is not just links to sources: rather, this is downloaded, hard copies of the sources themselves. PDFs, copy-pasted text, saved images, whatever.
- Each System contains an "XXX-revisions.md" file. 
	- XXX is the system number
	- This is a changelog for adjustments to the model.
	- Each entry in this changelog should state the What (what was changed), Why (links to notes on reasoning), Confidence level of the change, and What would reverse this change?
- Each System contains an "XXX-current-model.md" file.
	- XXX is the current systems number.
	- This file contains the most basic version of my current model for the system.
	- The file should start with a version number for the model: starting at 0.1, iterating through "major" versions only when large milestones are achieved or changes are made.
	- When major changes are made to the model, do the following: 
		1) Note the changes to be made in the revisions.md file.
		2) increment either minor version number (after the decimal) or major version number (before the decimal) depending on magnitude of change
		3) add the changes