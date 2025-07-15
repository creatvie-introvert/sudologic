<p align="center">
  <img src="docs/icon-only-logo.png" alt="SudoLogic Logo" width="200">
</p>

<h1 align="center">SudoLogic</h1>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Project Overview
**SudoLogic** is a mobile-first online platform where users can play Sudoku puzzles of varying difficulties - including *Easy*, *Medium*, *Hard*, and *Expert* levels. Designed for accessibility and engagemnet, the platform offer both a classic experience and a *Daily Puzzle* mode that refreshes every 24 hours, encouraging users to return regularly and build a daily streak.

The app is aimed at a wide audience, including casual gamers, puzzle enthusiasts, and learners seekig to improve their logical thinking skills. The intuitive mobile-first layout ensures a seamless experience across all devices, while smart gameplay features such as error checking, hint mode, and daily progress tracking elevate it beyond basic web sudoku clones.

### Site Preview
_A full preview of the final design will be added here once development is complete._

_This section will include:_

_Screenshots of the live site on mobile, tablet, and desktop_

_A responsive mockup image showing the site across multiple devices

Visit the website: [SudoLogic]()

## Table fo Contents
- [Project Overview](#project-overview)
  - [Site Preview](#site-preview)
- [Project Goals](#project-goals)
  - [Business Goals](#business-goals)
  - [Call to Action (CTA)](#call-to-action-cta)
- [User Experience (UX)](#user-experience-ux)
  - [User Goals](#user-goals)
  - [User Stories](#user-stories)
  - [User Journey Overview](#user-journey-overview)
  - [Site Owner Goals](#site-owner-goals)
  - [Design Requirements](#design-requirements)
- [Design Process](#)
  - [Wireframes](#)
  - [Colour Scheme](#)
  - [Typography](#)
  - [Imagery](#)
- [Features](#)
  - [Existing Features](#)
  - [Future Enhancements](#)
- [Technologies Used](#)
- [Testing](#)
- [Deployment](#)
- [Credits](#)
- [Acknowledgements](#)

## Project Goals
The goal of **SudoLogic** is to provide a clean, distraction-free online platform where users of all ages can enjoy solving Sudoku puzzles. The site follows a mobile-first design philosophy to ensure maximum accessibility and ease of use across all devices.

### Business Goals
- Offer a free, high-quality Sudoku experience to attract and retain users.
- Encourage daily engagement through a new daily puzzles and user streak tracking.
- Establish the project as a portfolio-worthy demonstration of frontend development, responsive design, and user-centered thinking.

### Call to Action (CTA)
The primary call to action is" 
**"Play Today's Puzzle"** - prominently displayed on the homepage to encourage immmediate interaction with the latest Sudoku game.

Secondary CTAs include:
- **"Choose a Difficulty"** - allowing users to play puzzles at their preferred level (Easy, Medium, Hard, Expert).
- **"Track You Streak"** - encouraging repeat visitis through progress tracking (planned future feature).

## User Experience (UX)
SudoLogic was designed with a user-centred approach to ensure an engaging, accessible, and intuitive Sudoku experience. By following Jesse Jame Garrett's Five Planes of UX - **Strategy, Scope, Structure, Skeleton, and Surface** i the design and functionality of the site were carefully planned and executed to meet both the user and the business goals.

### User Goals
At the Strategy Plane, I focused on identifying and prioritising the core needs of our target users to ensure the app delivers a purposeful and engaging experience. These key goals include:
- Pay Sudoku easily on any device.
- Choose between a Daily Challenge or a new Random Puzzle.
- Access clear instructions both before and during gameplay.
- Use intuitive controls to input, erase, or pencil in numbers.
- Recieve optional feedback on mistakes or check answers manually.
- Track daily puzzle streaks and time-based performance.
- Save game progress automatically and resume later.
- Share results and celebrate completion with animations.
- Enjoy a fun and frustration-free experience with accessibility features.

### User Stories
User stories are fully detailed on the [GitHub Project Board](https://github.com/users/creatvie-introvert/projects/11/views/1), and have been written using a user-centred desgn approach aligned with the UX Strategy and Scope Planes.

**New and First-Time Users**
- As a new user, I want to choose between a Daily Puzzle and a Random Puzzle so I can get started quickly.
- As a user, I want to view clear instructions before or during the game so I can learn how to play.
- As a user, I want to select a difficulty level when starting a new puzzle so I can play at my preferred challenge level.
- As a user, I want the interface to be intuitive and responsive so I can play comfortably on any device.

**During Gameplay**
- As a user, I want to input numbers and use pencil marks so I can keep track of possible solutions.
- As a user, I want to toggle pencil mode so I can switch between notes and final answers.
- As a user, I want to undo, redo, or reset the puzzle so I can fix mistakes or start fresh.
- As a user, I want to request a hint so I can get help if I'm stuck.
- As a user, I want to toggle error highlighting so I can choose whether or not to see mistakes as I go.
- As a user, I want to check my answers manually so I can verify them, if error highlighting is turned off.
- As a user, I want to clear a single cell so I can update my inputs precisely.
- As a user, I want a timer to track how long I've been playing so I can measure my performance.
- As a user, I want the timer to pause if I leave the page or view the instructions so my time stays accurate.
- As a user, I want to access instructions during gameplay so I can get help if I forget something.

**After Gameplay**
- As a user, I want to see a celebration animation when I complete a puzzle so I feel rewarded.
- As a user, I want to view my score or stats after completing a puzzle so I can asses my performance.
- As a user, I want to share my results so I can celebrate or compete with friends.

**Returning Users and Long-Term Use**
- As a user, I want the game to autosave so I can return to it later without losing progress.
- As a user, I want to track my daily streak so I stay motivated to play regularly.
- As a user, I want a setting panel so I can control features like sound, contrast, or input modes.
- As a user, I want the interface to include accessibility options so I can play regardless of my needs.
- As a user, I want to recieve confirmation before resetting or starting a new game so I don't accidentally lose my progress.
- As a user, I want to contact support or provide feedback so I can get help or suggest improvements.

### User Journey Overview
At the Structure Plane, I planned clear and purposeful flow from start to finish, shaped around engagement, simplicity, and flow:
1. User lands on the homepage and selects either the Daily Puzzle or a Random Puzzle.
2. If a Random Puzzle is selected, they choose a difficulty level.
3. The game board loads with controls for pencil mode, hints, timer, and error feeedback.
4. Users can pause, reset, or undo actions during gameplay.
5. Upon completion, a celebration animation is triggered and results can be shared.
6. Progress is autosaved, and returning users can resume or start a new game.

### Site Owner Goals
SudoLogic was designed to meet the project criteria for a professional-grade front-end portfolio piece. At the strategy level, the project aims to:
- Demonstrate UX and front-end development proficiency.
- Deliver a polished, mobile-first web app with complex interactivity.
- Build a project that is visually engaging and code-review ready.
- Include a GitHub Project Board with full user stoories and workflow.
- Allow for feature expansion in future development phases (e.g. user profiles, stats dashboard, or leaderboard).
- Ensure accessibility compliance to provide an inclusive experience for all users.s, or saved stats.

### Design Requirements
Rooted in the skeleton and surface planes, the following design decisions were made to fulfil the needs identified in earlier phases:
- **Mobile-First Layout**: Optimised for touch interaction and responsive across all screen sizes.
- **Minimalist UI**: The Sudoku board remains central, with a clean distraction-free design.
- **Colour & Typography**: Accessible contrast levels, scalable font sizes, and consistent iconography.
- **Layout Consistency**: Familiar UI patterns, such as top navigation and sticky controls.
- **Feedback & Animation**: Micro-interactions on input, animated celebrations on completion.
- **Content Architecture**: Logical grouping of UI controls (e.g., hints, timer, reset, pencil mode).
- **Accessibility Standards**: WCAG-aligned features to ensure inclusive access.
- **Grid System & Layout Strategy**: Custom CSS grid is used to build a precise and consistent layout.
- **User Feedback Machanisms**: Visual cues such as highlights, hover states, disabled buttons, and confirmation modals guide the user experience.
- **Game Board Design**: Features include bold 3x3 sectioning, dynamic styling on input, and intuitive interaction zones.
- **Touch-Friendly Interactions**: Designed with large tap targets and adequate spacing for mobile users.
- **Accessibility Enhancements**: Includes logical tab order, aria labels, screen reader support, focus outlines, and support for prefers-reduced-motion.

By carefully considering all five planes SudoLogic aims to provide a seamless, enjoyable puzzle experience that balances functionality with emotional satsfaction.