# How p5.js Works

Build generative art, shaders, interactive sketches, and 3D scenes with p5.js.

![Detailed systems blueprint for p5.js](../assets/system-blueprint.png)

## Stages

### 1. Define canvas size motion and interaction

**Primary surface:** `Sketch concept`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 2. Build the drawing loop and scene state

**Primary surface:** `p5.js canvas`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 3. Add geometry particles shader or 3D forms

**Primary surface:** `Drawing and shader code`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 4. Expose useful live controls

**Primary surface:** `Interactive controls`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 5. Run at multiple viewport sizes

**Primary surface:** `Browser-rendered artwork`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 6. Capture a deterministic seed and preview

**Primary surface:** `Browser-rendered artwork`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.

## Failure handling

- **Authorization failure:** do not probe credentials or broaden access; report the missing authority.
- **Target ambiguity:** stop before mutation and request the minimum identifying information.
- **Tool or service failure:** retain error evidence, retry only safe transient failures, and cap retries.
- **Verification failure:** classify the run as incomplete even when the preceding operation returned success.

## Completion evidence

The handoff should contain the original request, inspection state, preview or plan, exact execution result, direct verification, and a final receipt naming limitations and withheld actions.
