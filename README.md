# continuum-payment-ack-outbound

Legacy standalone service scaffold for the outbound payment-acknowledgement slice of the Continuum payment-workflow family.

## Current Contents

This repository currently contains:

- Kotlin source under `src/main/kotlin`
- application configuration under `src/main/resources/application.yml`

The repository does **not** currently include a complete standalone Gradle build at the root, so it should not be represented as a fully runnable independent service.

## Continuum Relationship

The broader Continuum platform models deterministic, replayable workflows with evidence capture and validation gates. Payment-message primitives are consolidated in the `continuum-payments` repository rather than requiring every historical message-direction repository to remain a separate deployable.

## Status

Historical/incomplete service scaffold retained for source-history and module-boundary reference. Use `continuum-payments` for the current consolidated payment-workflow implementation.
