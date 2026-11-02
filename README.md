# VCR Assignment Studio

A free, static, accessible faculty tool for preparing AI prompts that generate clinical written assignments using **Commit, Complicate, Calibrate (CCC)**.

## What it does

- Collects a **specific learning objective**, topic, student readiness, previously taught concepts, permitted resources, and assignment workload.
- Allows an instructor to choose the type of **Complicate** challenge and **Calibrate** uncertainty.
- Generates a detailed, editable prompt for an LLM to create a **one-paragraph clinical case**, student-facing CCC instructions, instructor notes, and learning follow-through.
- Copies or downloads the prompt. Opens ChatGPT in a separate tab (the user pastes the prompt).
- Includes a faculty clinical-accuracy and instructional-alignment checklist.

**It does not directly call an AI API.** This is intentional: the site works on GitHub Pages without accounts, a server, API fees, or exposing a secret API key. Users paste the generated prompt into their preferred LLM. No form data is transmitted by this website.

## Publish on GitHub Pages

1. Create a public GitHub repository, e.g. `vcr-assignment-studio`.
2. Upload `index.html`, `styles.css`, and `script.js` to the repository root (you may also upload this README and LICENSE).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**; select **main** and **/(root)**; save.
5. Once deployed, GitHub will display the site URL, typically `https://YOUR-USERNAME.github.io/vcr-assignment-studio/`.

To test locally, open `index.html` in a browser. No build step is required.

## Scope and limitations

VCR is an instructional design framework, **not a competency assessment**. Generated cases require faculty review for clinical accuracy, feasibility, case logic, and appropriateness to student readiness. The research supporting self-explanation, constructive engagement, and metacognition does not establish the effectiveness of VCR as a complete intervention.

## Customization

Edit colors and typography in `styles.css`. Edit the generator instructions and CCC variants in `script.js`. This repository contains no credentials or dependencies.

## License

MIT. See LICENSE.
