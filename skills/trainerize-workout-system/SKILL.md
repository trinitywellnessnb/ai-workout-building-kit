---
name: trainerize-workout-system
description: Configure, inventory, generate, build, schedule, verify, and reconcile workouts and programs using a trainer's AI Workout Building Kit and Trainerize account. Use when a trainer asks ChatGPT to personalize the kit, inventory Trainerize movements or workouts, build a workout or program, transfer approved programming into Trainerize, schedule calendar activities, reuse registry assets, or reconcile coach corrections.
---

# Trainerize Workout System

## Resolve the project sources

Locate and read `README.md`, `FILE-MAP.md`, the three configuration YAML files, and the relevant manuals before acting. Read [source-routing.md](references/source-routing.md) for the required filenames and routing table.

Do not assume the trainer uses default configuration when completed configuration files are available. Preserve exact Trainerize titles from verified registry records.

## Classify the request

Choose one operating mode:

1. **Personalize**: transfer onboarding answers into trainer configuration without rewriting universal manuals.
2. **Inventory**: read Trainerize without changing it and populate movements, workouts, or program registries.
3. **Generate**: create a draft workout or program under the Master Rulebook and verified Movement Registry.
4. **Execute**: transfer an approved build into Trainerize one logical write at a time.
5. **Calendar**: schedule approved workouts and engagement events after program structure is verified.
6. **Reconcile**: update the workbook and registries from a trainer-corrected, verified Trainerize result.

Do not combine inventory with live mutation unless the trainer explicitly authorizes both.

## Apply the authority order

Resolve conflicts in this order:

1. Safety, scope of practice, and client-specific restrictions
2. Explicit current trainer instruction
3. Verified current Trainerize behavior
4. Completed trainer configuration
5. Workout Generation Master Rulebook
6. Structured Workout Architecture
7. Workout Builder Operational Manual
8. Calendar Engagement Funnel Rulebook
9. Formatting preferences

Treat Trainerize as authoritative for actual saved state. Treat registries as external indexes and resumable records.

## Inventory safely

Inventory movements before workouts and workouts before programs. Record exact titles. Do not rename, create, or substitute during inventory. Mark uncertain items `DRAFT`, unresolved differences `MISMATCH`, and blocked items `BLOCKED`. Require trainer review before promoting uncertain records to `VERIFIED`.

## Generate programming

Use only verified Movement Registry entries unless the trainer explicitly approves another source. Search the Workout Registry before creating a new workout. Classify the decision as `REUSE`, `VARIATION`, or `NEW`. Apply the configured naming system and preserve one stable Workout Key across draft, save, and calendar references.

Present a draft before live execution when the approval policy requires it.

## Execute in Trainerize

Confirm the approved target, active page, and intended action before each write. Perform one logical write, save, and read back the result. Record the exact final title accepted by Trainerize. Do not claim success from a click or save attempt alone.

After a verified new workout or variation, synchronize the Workout Registry and Work Mode Execution Log before advancing. If Trainerize succeeds but registry synchronization fails, preserve the saved workout and log `TRAINERIZE_SAVED_REGISTRY_SYNC_REQUIRED`.

## Schedule calendar content

Keep calendar instances separate from reusable workout definitions. Verify program and phase placement before scheduling. Apply instance-specific progression only after the calendar structure is final. Treat later structural calendar changes as rebuild work when they can remove progression data.

## Reconcile corrections

When the trainer intentionally corrects and verifies a saved workout, use the verified Trainerize result as the implementation authority. Update the client build, registry metadata, and reusable guidance. Never silently restore an earlier draft.

## Protect data

Never write passwords, payment information, protected health information, or unnecessary client identifiers into project sources or registries. Use the trainer's authenticated browser session for Trainerize access.
