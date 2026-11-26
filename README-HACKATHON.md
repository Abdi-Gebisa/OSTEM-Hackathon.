# OSTEM — Hackathon Submission

**Explore Physics. Experiment. Learn. Verify.**

OSTEM is a mobile-first, offline-capable virtual Physics learning platform for Ethiopian secondary-school students. It addresses limited access to practical laboratory experiences by letting learners change experimental variables, observe visual models, inspect live measurements and graphs, and compare predictions with calculated outcomes.

## Problem
Many secondary-school learners have limited access to well-equipped Physics laboratories. Reading equations alone does not always build an intuitive understanding of motion, forces, waves, optics and electricity.

## Solution
OSTEM provides interactive, student-controlled Physics experiments with direct numeric input and synchronized sliders, live readouts, graphing, formula/theory notes, prediction and verification, EUEE practice, an offline study tutor, formula calculator, laboratory report builder and learning challenges. It is designed for mobile devices and can work offline after its first successful online load.

## What makes it distinctive
- Physics-first scope rather than shallow multi-subject coverage.
- Learners enter their own values and investigate how changing one variable affects a model.
- Local-first design for low-connectivity settings.
- Learning challenge can generate a local SHA-256 achievement proof using a fixed non-personal code.
- Optional Solana Anchor source prototype is included for future Devnet verification; it is not deployed or connected to the app in this build.

## Features included in this build
- 18 interactive Physics experiment models across mechanics, optics, waves, electricity and magnetism.
- Numeric inputs and sliders, animation controls, live measurements and graph, experiment notes, Predict & Verify and CSV export.
- Offline curated Physics Tutor (rule-based knowledge base; not a live generative AI model).
- Physics formula calculator and lab report builder.
- Original EUEE-style practice questions with explanations.
- Five Physics learning challenges and local SHA-256 proof.
- PWA offline cache, Android/Capacitor configuration and GitHub Actions APK workflow.

## Run locally
Use Node.js or Python to serve this folder as a static site. For example:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`. The app uses browser-native HTML, CSS, Canvas and JavaScript modules.

## Honest implementation status
- The Physics app, offline tutor, calculator, report builder, EUEE practice, challenges and local hash proof are implemented in the source.
- The local SHA-256 proof is not a blockchain transaction.
- `web3-prototype/solana-achievement/` contains Anchor program/client source as a starting point only. It has not been built, tested, audited, deployed or verified on Solana Devnet. The app does not submit a transaction.
- The Physics Tutor is an offline curated/rule-based assistant, not connected to a generative AI model. No API key or AI backend is included.
- The project has passed static syntax/structure checks in this package, but organizers/judges should be shown only features that have been tested on the actual demo device.

## Privacy and access principles
Learning content remains free and does not require a wallet. Do not store or publish student names, email addresses, schools, grades, scores or location on-chain. Wallet use and any future verification must be optional, testnet-only for demonstrations, and never require real funds for access to lessons. Never share a wallet recovery phrase or private key.

## Demo flow (3 minutes)
1. Open Home and explain the problem and OSTEM's Physics-only focus.
2. Open Projectile Motion. Change initial speed and launch angle using numeric inputs; show the animation, readout and graph.
3. Open Predict & Verify, enter a prediction, run the model and compare.
4. Open Physics Tutor and ask: “Explain Newton's second law with an example.” Clarify that this is an offline curated tutor.
5. Open EUEE Practice and answer one question.
6. Open Learning Challenges; complete the five questions and show the local proof only if a perfect score is achieved. State explicitly that this proof is local, not on-chain.
7. Finish with the vision: accessible practical Physics education for Ethiopian learners.

## Team / creator
Built by Abdi Gebisa.

## Contact
Email: abdigebisa035@gmail.com
Portfolio: https://abdi-gebisa.github.io/abdi-gebisa-nagasa.github.io/
Project website: https://abdi-gebisa.github.io/Oromia-snell-s/ (update after publishing this submission build).
