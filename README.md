# Southsea Cinema - Flutter Coursework

This repository contains the coursework starter project for students enrolled in the **Programming Applications and Programming Languages (M30235)** and **User Experience Design and Implementation (M32605)** modules at the University of Portsmouth.

## Overview

Your task is to recreate a mobile-friendly version of the Southsea Cinema website using Flutter. You must begin by forking this starter repository, then build your own version of the app step by step as you work through the weekly worksheets.

Reference website: [Southsea Cinema](https://southseacinema.savoysystems.co.uk/SouthseaCinema.dll/)

The starter app is deliberately minimal. It contains only a basic theme, an empty home page, a small drawer, and a default widget test. You are expected to add screens, widgets, data models, tests, persistence, and cloud services during the coursework.

## Getting Started

### Prerequisites

You need:

- A GitHub account
- A way to edit and run Flutter projects
- Git installed and connected to your GitHub account

You have three development options:

1. GitHub Codespaces (browser-based, no local install required)
2. University Windows computers
3. Your own computer

The worksheets on the [Flutter Course homepage](https://manighahrmani.github.io/sandwich_shop/) explain these options in more detail.

### Fork the Repository

Open this repository on GitHub and click **Fork**:

[https://github.com/manighahrmani/southsea_cinema/fork](https://github.com/manighahrmani/southsea_cinema/fork)

Do not change the repository name. Your fork should be called `southsea_cinema` and should have a URL like this:

```text
https://github.com/YOUR-USERNAME/southsea_cinema
```

Screenshot placeholder: `images/step1_fork_button.png`

Screenshot placeholder: `images/step1_create_fork.png`

### Clone Your Forked Repository

If you are using VS Code locally, open a terminal and run:

```bash
git clone https://github.com/YOUR-USERNAME/southsea_cinema.git
cd southsea_cinema
```

Replace `YOUR-USERNAME` with your GitHub username.

Screenshot placeholder: `images/step2_clone_repository.png`

Screenshot placeholder: `images/step2_open_in_vscode.png`

### Install Dependencies

Run:

```bash
flutter pub get
```

This downloads the Flutter packages needed by the starter app.

Screenshot placeholder: `images/step3_flutter_pub_get.png`

### Run the Application

This coursework targets Flutter Web. Use Chrome or Edge.

```bash
flutter run -d chrome
```

or:

```bash
flutter run -d edge
```

The app should open in your browser and show the Southsea Cinema starter home page.

Screenshot placeholder: `images/step4_run_app.png`

### Use Mobile View

The coursework should be designed mobile-first.

In Chrome or Edge:

1. Right-click the page and choose **Inspect**
2. Click the **Toggle device toolbar** button
3. Choose a phone-sized device preset

Screenshot placeholder: `images/step5_open_devtools.png`

Screenshot placeholder: `images/step5_mobile_view.png`

## Marking Criteria

This repository is the starting point for your Southsea Cinema coursework. You will be assessed through five practical demo checkpoints during the teaching block. Each demo checks:

- Functionality: what your app can do
- Quality: how well your code is organised
- Understanding: whether you can explain your own work

The full demo dates and requirements are listed on the [Flutter Course homepage](https://manighahrmani.github.io/sandwich_shop/).

## Submission

You will submit the link to your public forked repository on Moodle when instructed. You are not submitting a zip file or a copy of the source code.

Make sure your repository is public. Test this by opening your repository link in a private/incognito browser window.

## Demonstration

During each demo, you must be able to run your app and answer questions about your code.

Before attending a demo, check that the app runs from a clean clone:

```bash
flutter pub get
flutter run -d chrome
```

## Project Structure

The starter repository is intentionally small:

```text
southsea_cinema/
├── lib/
│   ├── constants.dart          # Shared colours, text styles, and app title
│   ├── main.dart               # Main app and route setup
│   ├── views/
│   │   └── home_view.dart      # Starter home page
│   └── widgets/
│       └── nav_drawer.dart     # Minimal starter drawer
├── test/
│   └── widget_test.dart        # Basic widget test
├── pubspec.yaml                # Project dependencies
└── README.md                   # This file
```

You will add more files and folders as the coursework develops.

## Help with Coursework

Use the worksheets on the [Flutter Course homepage](https://manighahrmani.github.io/sandwich_shop/) as your main guide.

If you get stuck:

- Ask for help in your practical session
- Use the module Discord channel
- Check that your app still runs before making more changes
- Commit your work regularly with clear commit messages

Use AI tools carefully. You are allowed to use them, but you must understand, review, and adapt any generated code before adding it to your coursework.

## Suggested Screenshots to Add Later

When preparing final screenshots for this README, capture:

1. GitHub fork button
2. GitHub create fork page
3. VS Code clone repository command
4. VS Code project open with `pubspec.yaml` visible
5. Terminal after `flutter pub get`
6. Terminal running `flutter run -d chrome`
7. Browser showing the starter app
8. Browser DevTools mobile view
