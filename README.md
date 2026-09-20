# Ahad Khan Portfolio

A single-page portfolio website for Ahad Khan, featuring projects, skills, experience, achievements, certifications, resume access, and a contact form.

## Run Locally

This is a static website and does not require a build step.

1. Open `index.html` directly in a browser, or serve the folder with any local static server.
2. Keep the `frames`, `js`, `Achievements_&_Certifications`, and resume files in their existing locations so all assets load correctly.

For a simple local server with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Contact Form

The contact form submits asynchronously to FormSubmit at `https://formsubmit.co/ajax/ahad998867@gmail.com`. After a successful response, the form resets and shows a confirmation dialog. The dialog can be closed with the Close button, by clicking outside it, or by pressing `Escape`.

Because delivery is handled by FormSubmit, the form must be tested through a browser and the endpoint may require email activation the first time it receives a submission.

## Main Assets

- `index.html`: Page markup, styles, and client-side interactions
- `frames/`: Scroll animation image frames
- `js/pdf.min.js` and `js/pdf.worker.min.js`: PDF preview support
- `Achievements_&_Certifications/`: Certificate and achievement documents
- `Ahad_Khan_Resume.pdf`: Downloadable resume
