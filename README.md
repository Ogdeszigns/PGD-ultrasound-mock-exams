# PGD Ultrasound Mock Exams

A professional web-based mock examination platform designed for **PGD Medical Ultrasound students** to practice, test their knowledge, and prepare for examinations.

The platform provides a centralized dashboard where students can access multiple ultrasound-related mock examinations through a clean, responsive medical-themed interface.

## Overview

**RearView Medical Learning — PGD Ultrasound Mock Exams**

The project currently contains **5 mock examinations** covering major areas of medical ultrasonography:

* Abdominal Sonography I
* Basic Physics of Ultrasound
* Gynaecological Sonography
* Obstetric Sonography
* Pathology I

The platform is designed to be expandable, allowing additional courses, modules, and examinations to be added without changing the overall dashboard structure.

## Features

* Professional medical-themed dashboard
* RearView branding
* Responsive desktop and mobile layout
* Centralized mock examination library
* Individual **Start Exam** buttons
* Search functionality
* Subject/category filtering
* Examination availability indicators
* Dashboard statistics
* Expandable course structure
* Direct links to individual HTML examinations
* No external frameworks required
* Runs entirely as a static website

## Current Mock Exams

| Subject                   | Module   | Exam                        |
| ------------------------- | -------- | --------------------------- |
| Abdominal Sonography      | Module I | Abdominal Sonography I      |
| Ultrasound Physics        | Module 1 | Basic Physics of Ultrasound |
| Gynaecological Sonography | Module 1 | Gynaecological Sonography   |
| Obstetric Sonography      | Module 1 | Obstetric Sonography        |
| Pathology                 | Module 1 | Pathology I                 |

## Project Structure

```text
PGD-ultrasound-mock-exams/
│
├── index.html
│
├── Abdominal_Sonography_I_Module_I_Mock_Exam.html
├── Basic_Physics_of_Ultrasound_Module1_Mock_Exam.html
├── Gynecological_Sonography_Module1_Mock_Exam.html
├── Obstetric_Sonography_Module1_Mock_Exam_1.html
├── Pathology_I_Module1_Mock_Exam.html
│
└── README.md
```

## Dashboard

The `index.html` file serves as the main dashboard.

It provides:

* RearView medical branding
* PGD Ultrasound overview
* Mock examination statistics
* Search and filtering
* Subject categories
* Examination cards
* Direct links to each mock examination

### Adding a New Examination

To add another examination:

1. Upload the new `.html` examination file to the repository.
2. Open `index.html`.
3. Add a new `.course-card`.
4. Set the appropriate `data-category`.
5. Add the correct filename to the **Start Exam** link.
6. Commit the changes.

Example:

```html
<article class="course-card" data-category="doppler">

    <div class="course-top">
        <div class="course-icon">
            ≋
        </div>

        <span class="status">
            AVAILABLE
        </span>
    </div>

    <h3>
        Doppler Ultrasound
    </h3>

    <p>
        Mock examination covering the principles and
        applications of Doppler ultrasonography.
    </p>

    <div class="course-meta">
        <span>MODULE 1</span>
        <span>DOPPLER</span>
    </div>

    <div class="course-footer">
        <a
            href="Doppler_Ultrasound_Module1_Mock_Exam.html"
            class="start-button"
        >
            Start Exam →
        </a>
    </div>

</article>
```

The existing search and filtering functionality will automatically include the new card.

## Technology

The project intentionally uses simple web technologies:

* **HTML5** — page structure
* **CSS3** — dashboard design and responsive layout
* **JavaScript** — search, filtering, and dynamic dashboard behavior
* **GitHub Pages** — website hosting

No external JavaScript frameworks or third-party libraries are required.

## Design

The interface uses a professional medical education visual style featuring:

* Blue medical color palette
* Clean dashboard layout
* Responsive cards
* Subject-specific icons
* Mobile-friendly navigation
* Accessible typography
* Minimal external dependencies

The design can be extended as the platform grows.

## Deployment

The project is designed to be hosted using **GitHub Pages**.

Repository:

**Ogdeszigns/PGD-ultrasound-mock-exams**

Live site:

**[https://ogdeszigns.github.io/PGD-ultrasound-mock-exams/](https://ogdeszigns.github.io/PGD-ultrasound-mock-exams/)**

To deploy through GitHub Pages:

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch.
5. Select `/ (root)` as the folder.
6. Save the configuration.
7. Wait for GitHub Pages to complete deployment.

The `index.html` file must remain in the root of the published directory.

## Direct Examination Links

Each examination can be accessed directly using the GitHub Pages base URL followed by its filename.

Example:

```text
https://ogdeszigns.github.io/PGD-ultrasound-mock-exams/Abdominal_Sonography_I_Module_I_Mock_Exam.html
```

This allows individual examinations to be shared independently while still being accessible from the main dashboard.

## Purpose

The project is intended to support **self-assessment and examination preparation** for students studying medical ultrasound.

It provides an organized environment for practicing subject-specific questions and accessing multiple mock examinations from a single location.

## Future Development

Planned or possible improvements include:

* Additional ultrasound courses
* More modules per subject
* Automatic question/exam statistics
* Student progress tracking
* Score history
* Completion indicators
* User accounts
* Randomized questions
* Question review mode
* Timed examination analytics
* Course-specific dashboards
* Improved accessibility
* Certificate generation
* Larger question banks

## Contribution

As the platform expands, new examinations should follow the existing naming and organizational structure.

When adding a new examination:

* Use descriptive filenames.
* Keep examination files in the appropriate directory.
* Ensure all internal CSS and JavaScript work correctly.
* Test the examination before deployment.
* Add the examination to the dashboard.
* Verify the GitHub Pages link after deployment.

## Disclaimer

This platform is intended for **educational practice and self-assessment**.

Mock examinations are not official professional licensing examinations and should not be considered a substitute for formal academic instruction, clinical training, or professional certification.

---

### RearView Medical Learning

**PGD Medical Ultrasound Mock Examination Platform**

Practice. Test. Improve.
