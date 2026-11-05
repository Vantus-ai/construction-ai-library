# Claude skills

Skills package a workflow into instructions Claude loads whenever the task comes up. Instead of pasting a prompt each time, you install the skill once and ask in plain language, for example "draft an RFI for the clash at gridline C4".

## Skills in this library

| Skill | Use it when you need to |
| --- | --- |
| [rfi-drafter](rfi-drafter/) | Raise a clear, answerable RFI |
| [early-warning-notice](early-warning-notice/) | Notify an NEC4 early warning and update the register |
| [cost-report-narrative](cost-report-narrative/) | Write the monthly cost report narrative |
| [quote-comparison](quote-comparison/) | Compare subcontractor quotes and find the gaps |
| [site-diary-summary](site-diary-summary/) | Turn site diaries into a weekly progress and issues report |
| [meeting-minutes](meeting-minutes/) | Produce minutes and an action log from notes or a transcript |

## Installing a skill

Each skill is a folder containing a SKILL.md file.

**Claude (claude.ai and the desktop app):** download the skill folder, compress it into a zip file and upload it in Settings under Capabilities, in the Skills section. Skills must be enabled for your account or organisation.

**Claude Code:** copy the skill folder into ~/.claude/skills/ for personal use, or into .claude/skills/ inside a project repository to share it with your team.

Once installed, just describe the task. Claude decides when to use the skill from its description.

## Writing your own

Copy any skill folder, rename it and edit SKILL.md. Keep the description specific about when the skill should be used, and keep the instructions to the steps a good practitioner would follow. See [CONTRIBUTING.md](../CONTRIBUTING.md) to share it back.
