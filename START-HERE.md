# Start Here

This package helps a trainer configure ChatGPT Work Mode to design workouts, organize reusable workout assets, and transfer approved content into Trainerize. Complete setup before requesting a full program.

## Installation sequence

1. Create a dedicated ChatGPT Project for the trainer's workout-building system.
2. Keep Work Mode and project memory available when the account permits them.
3. Upload the contents of `manuals/`, `project-instructions/`, and the completed files from `configuration/` as project sources.
4. Upload `templates/Trainerize-System-Registry-Template.xlsx` or place it in the connected project folder.
5. Complete `onboarding/TRAINER-PERSONALIZATION-QUESTIONNAIRE.md`.
6. Ask ChatGPT to apply the questionnaire answers to the configuration files.
7. Sign in to Trainerize in the browser. Never paste the password into a manual or configuration file.
8. Inventory exercises first, saved workouts second, and programs third.
9. Review the generated registries for exact names and duplicate records.
10. Build and verify one test workout before beginning a large program.

## Initial prompts

Use these prompts in order.

### Personalize the package

> Read the personalization questionnaire, configuration files, project instructions, and source hierarchy. Update my private configuration files from my answers. Do not rewrite the universal manuals unless one of my preferences requires a documented override.

### Inventory movements

> Using Work Mode, inspect my Trainerize exercise library and populate the Movement Registry with exact saved titles and verified information. Do not create, rename, or substitute movements during inventory. Stop and report anything uncertain.

### Inventory workouts

> Inspect my saved Trainerize workouts and populate the Workout Registry. Preserve exact saved titles. Treat repeated screenshots or repeated appearances of the same exact title as one workout unless Trainerize shows distinct saved entities.

### Inventory programs

> Inspect my Trainerize programs and populate the Program Registry with program names, phases, duration, scheduling structure, and reusable workout relationships. Do not alter live programs during inventory.

### Calibration build

> Create one draft workout that follows my configuration, Movement Registry, Master Rulebook, and naming system. Present the build for approval before making any live Trainerize changes.

## Completion standard

Setup is complete only when the trainer profile is filled in, the registries have been reviewed, one calibration workout has been approved, and Trainerize read-back verification has succeeded.

