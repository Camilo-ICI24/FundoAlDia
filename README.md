# FundoAlDia

Offline time, shift and pay management system for new and veteran seasonal workers, geared towards low-resource devices and weak signal locations.

---

## Index

- [1. Introduction](#1-introduction)
  - [1.1 The problem context](#11-the-problem-context)
  - [1.2 The proposed solution](#12-the-proposed-solution)
- [2. Team Members](#2-team-members)
- [3. Strategy Phase](#3-strategy-phase)
  - [3.1 Value Proposition Canvas](#31-value-proposition-canvas)
  - [3.2 UX Persona](#32-ux-persona)
- [4. Scope Phase](#4-scope-phase)
  - [4.1 Benchmarking](#41-benchmarking)
- [5. Structure Phase](#5-structure-phase)
  - [5.1 Navigation Flow](#51-navigation-flow)
- [6. Skeleton Phase](#6-skeleton-phase)
  - [6.1 Low-fidelity Wireframes](#61-low-fidelity-wireframes)
- [7. Surface Phase](#7-surface-phase)
  - [7.1 Interface Evolution](#71-interface-evolution)
  - [7.2. High-fidelity Wireframes](#72-high-fidelity-wireframes)
- [8. Heuristic Evaluation Process](#8-heuristic-evaluation-process)
  - [8.1. Text size issue](#81-text-size-issue)
  - [8.2. Navbar implemented incorrectly](#82-navbar-implemented-incorrectly)
  - [8.3. Non-static header](#83-non-static-header)
  - [8.4. Unjustified color palette](#84-unjustified-color-palette)
  - [8.5. Ambiguous visual element](#85-ambiguous-visual-element)
- [9. Accesibility](#9-accesibility)
---

## 1. Introduction

### 1.1 The problem context

Seasonal agricultural and forestry workers need to request permits, check hours, and view paychecks from basic cell phones, without access to a computer and with limited connectivity. The app must assume low digital literacy as a design requirement.

> *“As a seasonal worker at a fruit farm who doesn't have a computer, I need to request sick leave, check my monthly hours worked, and view my paycheck from my basic cell phone so I don't have to physically go to the office on my day off.”*

### 1.2 The proposed solution

FundoAlDia is a mobile application designed for checking and inquiring about hours worked, shifts completed, and payment dates for seasonal workers.

This service offers offline functionality due to the limited coverage in the area, and it also reduces travel and waiting times when conducting paperwork, decreasing the need for in-person visits.

---

## 2. Team Members

- Camilo Cifuentes: _Project Manager_
- Felipe Márquez: _Analyst_
- Nicolás Sandoval: _Designer_

---

## 3. Strategy Phase

### 3.1 Value Proposition Canvas

A visual representation of what users expect to solve and what the mobile application aims to provide. One of the most significant obstacles in this process is the low level of technological education—or literacy—among seasonal workers seeking a solution to their problem. Therefore, this service aims to provide information intuitively to avoid user frustration and confusion.

<img width="1920" height="1080" alt="Value Proposition FundoAlDia" src="https://github.com/user-attachments/assets/2978ae58-b113-40ae-a19b-8f595b85fb4d" />

---

### 3.2 UX Persona

With the aim of gaining a closer look at the problems that seasonal workers constantly face, and to facilitate the design of an appropriate solution, it was decided to address the problem with three main approaches:

- The veteran seasonal worker
- The novice seasonal worker
- The supervisor

#### Veteran seasonal worker: Rosa (41, Angol)
<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/9bdc6039-17c9-4075-84b9-0f5b6a597890" />


#### Novice seasonal worker: Juan (22, Temuco)
<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/1b977afc-1dbf-44bf-936f-192114de4d93" />


#### Supervisor: Carlos (36, Temuco)
<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/0a65e8e3-fd2d-4c26-b938-31a0db34b7d9" />


---


## 4. Scope Phase

### 4.1 Benchmarking

In order to obtain a better visual reference on the design of our product compared to existing applications on this market sector, an informative benchmark was carried out to identify main functionalities and characteristics that could be integrated into our project development.

For this benchmark, four platforms related to shift scheduling, payment management, and employee administration were selected. These platforms were analyzed considering aspects such as visual hierarchy, information organization, accessibility, navigation clarity, and online/offline functionality.

The selected platforms are the following:
- **Rex+**: Online portal for Human Resources management, centralized in the automation of key tasks for the company, such as salary calculation, electronic signing of documents, attendance control, among others. The public link for this service can be found [here](https://rexmas.com/).
- **Talana**: Cloud-based software designed to digitize and automate Human Resources management, allowing for the review of aspects such as payroll, attendance tracking, digital document signing, vacation scheduling, and performance evaluation. It is frequently offered as a mobile application, enabling employees to perform all the described actions directly from their phones. More information about this service can be found on their [website](https://web.talana.com/).
- **Breik**: Cloud-based software designed to automate and optimize work shift scheduling. It allows for the intelligent management of employee schedules, ensuring compliance with labor regulations. Features include smart calendars for displaying, modifying, and creating schedules, integration with current labor laws, real-time analytics, and push notifications for employees.
- **Buk**: Human Resources management platform that centralizes and automates processes associated with the employee lifecycle. It helps companies simplify administrative tasks and enhance talent development in one place. Features include payroll processing, an employee portal, and digital document signing. The public link to this site can be accesed from [here](https://www.buk.cl/).


<img width="863" height="479" alt="benchmark" src="https://github.com/user-attachments/assets/c17cca43-0a2d-4bb2-b28c-b37f83909a9b" />


---

## 5. Structure Phase

### 5.1 Navigation Flow

A visual diagram that illustrates how users navigate through the application and how the different screens and functionalities are connected.

<img width="789" height="479" alt="navigation_flow_definite" src="https://github.com/user-attachments/assets/b85a26fb-be49-4ce0-b172-454ed49aea3d" />

Additionally, as an implementation for the second phase, a separate navigation flow was developed for the administrator profile.

<img width="1641" height="958" alt="Navigation Flow - Admin - FundoAlDia" src="https://github.com/user-attachments/assets/9d31d5ba-53f8-4151-993a-91697e105c8d" />


---

## 6. Skeleton Phase

### 6.1 Low-fidelity Wireframes

Based on the navigation flow designed in the previous phase, the team developed an initial version of the core screens that the application would include in the form of low-fidelity wireframes.

These wireframes were created with the purpose of defining the general structure of the interface, the organization of information, and the interaction flow between screens before moving into high-fidelity design stages.

<img width="654" height="448" alt="Wireframes" src="https://github.com/user-attachments/assets/b6a39a50-85ce-4fb7-80ba-91e1419b9ede" />

The low-fidelity wireframes can be found in full detail on the first page of the related Figma file, at the following [link](https://www.figma.com/design/wuJbb1K24XtzBXkliPJkgB/FundoAlDia-Wireframes?node-id=0-1&t=y3gDiFBq6lAq6MmB-1).

In turn, all the low-fidelity wireframe screenshots can be found in a PDF file in the documents section, found [here](https://github.com/Camilo-ICI24/FundoAlDia/blob/c39ecd962da4ae921c586dc1c7ad91275e14bbbf/docs/FundoAlDia%20-%20Wireframes%20Lo-Fi.pdf).

---

## 7. Surface Phase

### 7.1. Interface Evolution

#### Screen Evolution

##### Removal of the Account Creation Screen

One of the first changes made was the removal of the “Crear cuenta” screen. This decision was taken because, in a real-world context, companies are usually responsible for internally registering their employees, making this functionality unnecessary within the main user flow.

##### General Navigation Changes

The header was redesigned to include:

* The current section title.
* A shortcut to the employee profile.
* A calendar component to allow easier navigation between months and years.

<img width="683" height="145" alt="image" src="https://github.com/user-attachments/assets/60adc601-5308-4b70-818d-a2784b7c2232" />
<img width="405" height="114" alt="image" src="https://github.com/user-attachments/assets/ffa39ba0-218b-4bb1-bced-b560f511433c" />


Additionally, the bottom navigation menu was redesigned using more representative icons and labels to improve usability and clarity.

<img width="812" height="121" alt="image" src="https://github.com/user-attachments/assets/5c7bc6ea-7e89-43bc-97a9-af8be386b0a5" />
<img width="859" height="134" alt="image" src="https://github.com/user-attachments/assets/dd05e11f-2d3b-4b29-aa2c-013891891ce8" />


#### “Mis turnos” Screen

The “Mis turnos” screen was redesigned because the original low-fidelity version felt visually crowded.

The main changes included:

* Improved shift visualization.
* Support for displaying multiple shifts within the same day.
* Relocating the calendar to the upper section of the screen.
* Replacing the “Semanal / Mensual” dropdown with direct action buttons in the header.

<img width="571" height="643" alt="image" src="https://github.com/user-attachments/assets/3e1be7a8-9645-4259-8e48-ac8ca2a545e2" />
<img width="316" height="759" alt="image" src="https://github.com/user-attachments/assets/a6167f8a-8e05-43e5-b0f4-d745c1e88746" />

In the monthly view, a legend indicating the presence of multi-shifts was also added.

<img width="483" height="469" alt="image" src="https://github.com/user-attachments/assets/a02bb737-d09e-45f8-a04f-7ce3d4724fcf" />
<img width="468" height="512" alt="image" src="https://github.com/user-attachments/assets/4c4d1445-8ea1-4efb-8f16-a29375f8099b" />


#### “Ver horas” Screen

The worked hours section was simplified to directly display the detected observations for the month, removing unnecessary elements such as:

* The option to view every single day.
* General issue indicators.

The redesign also:

* Kept the option to emit a “claim” in case the employee disagrees with an observation.
* Improved the visualization of worked hours and overtime hours.
* Added a status label indicating whether the month is still in progress or already completed.

<img width="375" height="694" alt="image" src="https://github.com/user-attachments/assets/5c3c4ccb-da92-4ac6-a2b9-cb7b77e3d960" />
<img width="363" height="664" alt="image" src="https://github.com/user-attachments/assets/7e0072c5-af24-4733-9f8c-1716ca615f0f" />


#### “Permisos” Screen

The permissions screen was redesigned by introducing:

* A search feature by permission type.
* Categorization by status:

  * Pendientes
  * Aprobados
  * Rechazados

Pending permissions were visually prioritized by placing them at the top of the screen.

Additionally, the “Pedir permiso nuevo” button was replaced with a floating “+” button, following common mobile application design patterns.

<img width="461" height="511" alt="image" src="https://github.com/user-attachments/assets/c4025185-0dd1-462c-82ae-b8e90a5345e2" />
<img width="334" height="780" alt="image" src="https://github.com/user-attachments/assets/46c31820-7712-48d0-b49c-1f5622849f69" />


#### Permission Request Flow

The permission request and confirmation flow remained mostly unchanged. However, the step indicator was redesigned, replacing the previous bars with connected circles to provide a clearer representation of progress.

<img width="333" height="103" alt="image" src="https://github.com/user-attachments/assets/caeccc23-db52-40b3-bfa5-843f75e12872" />
<img width="452" height="116" alt="image" src="https://github.com/user-attachments/assets/9c65e50d-3194-4517-85d9-1290da300257" />

#### “Mi liquidación” Screen

This screen received smaller improvements, including:

* Month navigation.
* Better categorization between earnings and deductions.
* Display of the payment transfer date.


<img width="443" height="485" alt="image" src="https://github.com/user-attachments/assets/1ba5a5d0-0a1a-4c69-922e-e63aed51bcad" />
<img width="362" height="812" alt="image" src="https://github.com/user-attachments/assets/76f737c3-9fdd-4811-955d-775b4e9611d8" />


#### Shift Change Screens

The screens related to shift changes were reorganized to improve comfort and readability for mobile users.

Additionally, in the accepted shift change screen, the message:

* “Has cambiado turno con...”

was replaced with:

* “Has aceptado la propuesta de...”
* “Pendiente de aprobación”

This better represents the real workflow, where supervisor approval is still required after the employee accepts the proposal.

<img width="411" height="536" alt="image" src="https://github.com/user-attachments/assets/08118213-bf0d-4681-a76a-e01fec054266" />
<img width="343" height="750" alt="image" src="https://github.com/user-attachments/assets/3417a63c-2cc7-4c09-bccd-ec8818ef2405" />


#### Home Screen

The Home screen was redesigned to prioritize the most relevant information for employees, including:

* Current day shifts.
* Monthly summary.
* Upcoming payment.
* Permissions.
* Shift changes.

Quick access buttons were also added for:

* Mis turnos
* Pedir permiso
* Mi liquidación


<img width="396" height="667" alt="image" src="https://github.com/user-attachments/assets/a0f6f53a-e520-4b27-ab0d-744e5ea00722" />
<img width="365" height="710" alt="image" src="https://github.com/user-attachments/assets/39ca27e7-42be-4025-8287-17b55e601107" />

---

### 7.2. High-fidelity Wireframes

After designing the low-fidelity wireframes, and following multiple iterations, revisions, and feedback sessions, the team developed the high-fidelity prototypes for the application. This process considered aspects such as visual identity, interface consistency, design uniformity, and the overall user experience across the application.

The prototypes include a color palette designed for the target users, as well as typography, icons, and interactive components, allowing for a clearer visualization of the final appearance of the proposed solution.

<img width="201" height="569" alt="Captura desde 2026-05-24 23-12-54" src="https://github.com/user-attachments/assets/7f77a549-1b74-47cf-b65d-7e7cb4480954" />
<img width="201" height="474" alt="Captura desde 2026-05-24 23-12-25" src="https://github.com/user-attachments/assets/a060bc12-263c-4b7b-a0e4-6c2ba4c16565" />
<img width="201" height="437" alt="Captura desde 2026-05-24 23-11-47" src="https://github.com/user-attachments/assets/e2b5d814-5ec5-4b71-b876-5588a32d4d02" />
<img width="201" height="557" alt="Captura desde 2026-05-24 23-10-43" src="https://github.com/user-attachments/assets/06eecf9b-acad-49e8-906b-39edbebb0268" />

The high-definition interfaces can be found in their entirety in a PDF file, the link to which is provided [here](https://github.com/Camilo-ICI24/FundoAlDia/blob/ef05199b51fa17fc30051e4a6b5a58698ee4c7bd/docs/Hi-Fi%20Wireframes.pdf).

Additionally, they can also be found in the same Figma project where the low-fi wireframes were designed, the link to which is provided in the previous section.

---

## 8. Heuristic Evaluation Process

The initial visual proposal for the solution was presented in a first progress phase for evaluation regarding usability and design for end users. This process identified several areas where the proposals lacked robustness, providing opportunities for improvement and iterations with the goal of delivering a better user experience.

The project's heuristic evaluation was conducted by an independent team, taking into account Nielsen's design principles. This involved identifying design problems in order of criticality and providing potential solutions as feedback. Based on the results, the team prioritized the five most severe problems for further iteration of the proposed solution. These changes are detailed below:

### 8.1. Text size issue

|  Problem | Description | Solution |
|---|---|---|
| Texts too small (no adjustment option). | Small text can cause frustration and anger, especially for people with vision problems. | Implement responsive typography with accessible minimum size (16px on mobile) and allow adjustment from system settings or internal font scale selector. |

<img width="411" height="825" alt="texto pequeño" src="https://github.com/user-attachments/assets/f5d8606a-8a99-4c0a-bb7f-b1555178675d" />
<img width="360" height="781" alt="image" src="https://github.com/user-attachments/assets/3100adb2-6720-4597-b6ad-1616008a3664" />

The issue was resolved by increasing the base font size and standardizing the typographic system across the application. This decision was made based on findings from both heuristic evaluation and early feedback, where users experienced difficulties reading small text, particularly in dense information screens. Small font sizes increased visual effort and reduced readability, especially in scenarios involving smaller screens or suboptimal viewing conditions. As a result, the interface was adjusted to ensure a minimum readable size that supports comfortable interaction without forcing users to zoom or strain visually.

In addition, a font scaling feature was implemented to support different user needs, particularly for users with low vision or reading difficulties. This enhances accessibility by allowing personalization of text size, ensuring that the interface adapts to the user rather than forcing a fixed layout.


### 8.2. Navbar implemented incorrectly

|  Problem | Description | Solution |
|---|---|---|
| Navbar is poorly implemented. | The navbar is located at the bottom of the screen, so it's not visible unless scrolling. | Convert the bottom navigation bar into a fixed and sticky component at the edge of the window, always visible without needing to scroll. |

<img width="381" height="714" alt="navbar" src="https://github.com/user-attachments/assets/56ae0df8-fbe0-44ee-9568-a0ceb2dc9ae3" />
<img width="401" height="802" alt="image" src="https://github.com/user-attachments/assets/a63102e3-4a0f-4cee-8017-245663ae737f" />

To resolve this issue, the team redesigned the navigation system in order to ensure the consistent visibility of key actions across all screens. This iteration was based on the results of a heuristic usability evaluation, which revealed that users experienced reduced efficiency due to the need to scroll to access navigation shortcuts, leading to frustration as they had to scroll to the bottom to find them.

By making the navbar a fixed and always-visible component, the interface reduces interaction cost and improves task efficiency, allowing users to navigate between sections more quickly and without losing context.


### 8.3. Non-static header.

|  Problem | Description | Solution |
|---|---|---|
| Non-static top bar. | When scrolling down, the top bar disappears. | Apply smooth scrolling with reappearing on scroll up or keep it fixed (sticky top) at all times, preventing the main controls from being out of the user's view. |

<img width="420" height="401" alt="topbar-se-va" src="https://github.com/user-attachments/assets/12d4b760-c882-4eb8-adbb-2bf80661dbf3" />
<img width="410" height="438" alt="image" src="https://github.com/user-attachments/assets/a17f4519-46db-4ec2-94ae-9d985bd21dfe" />

By ensuring persistent visibility of the top header across all screens, this problem was solved by aligning its behavior with usability principles related to navigation consistency and user orientation within the interface.

According to the results of the heuristic evaluation, the disappearance of the main controls during scrolling reduced usability and increased the cognitive effort required to navigate between sections. By implementing a sticky header, the interface retains contextual information and improves overall navigation efficiency.


### 8.4. Unjustified color palette

|  Problem | Description | Solution |
|---|---|---|
| Poor choice of colors. | The background uses an unusual color; red can cause anxiety in some people and contrasts poorly with other elements. | Replace red with neutral colors or highly legible institutional tones (i.e.: white, light gray, serenity blue), reserving red exclusively for error messages or warnings. Ensure a minimum contrast ratio of 4.5:1 between text and background according to WCAG. |

<img width="203" height="470" alt="mala eleccion de colores" src="https://github.com/user-attachments/assets/69d910f3-2a74-47c1-9756-b17078cec97e" />
<img width="358" height="782" alt="image" src="https://github.com/user-attachments/assets/95a14ef5-f086-48b4-8031-021f99421bf9" />

In order to address this issue, the team redefined the application’s color system to improve both readability and semantic clarity. The color palette is now used consistently with its intended functional meaning, particularly reserving red for error and warning states, which helps prevent ambiguity in user interpretation.

This iteration is based on, and follows WCAG accessibility guidelines related to color contrast and the principle that information should not rely solely on color to be understood. By that, the updated interface improves visual clarity, reduces potential cognitive load, and enhances accessibility for users with different visual conditions and device qualities.


### 8.5. Ambiguous visual element

|  Problem | Description | Solution |
|---|---|---|
| "Modificar Información" button or text; can't tell if it's a button or just text. | There is no typical box to signal to the user that this section is clickable. | Apply standard visual affordances: visible border, shaded or filled background, pointer cursor, and clear label (e.g., "Modify >" or pencil icon). Avoid making actionable elements appear as plain text without any distinguishing shape or shading. |

<img width="516" height="805" alt="MODIFICAR" src="https://github.com/user-attachments/assets/4c525cf5-98aa-4c5b-b939-56caafb965a4" /> 
<img width="360" height="783" alt="image" src="https://github.com/user-attachments/assets/d007cbe5-dd7d-4104-9ef6-8f0f83a902fd" />

The element was redesigned to improve its visual affordance and interactive clarity, introducing clearer button-like characteristics such as borders, improved contrast, and stronger visual hierarchy, enabling users to immediately recognize it as an actionable component.

This change improves usability by reducing ambiguity and increasing interaction discoverability, ensuring that users can confidently identify clickable elements without prior learning or guessing.

### 8.6. No administrator profile

|  Problem | Solution |
|---|---|
| Only the workers' perspective was presented; that is, the entire administrator's part was missing. | Develop a secondary navigation flow, focused on the main actions of the administrator within the application. |

<img width="377" height="827" alt="image" src="https://github.com/user-attachments/assets/eaad0155-29fb-448c-bfff-c60aacf05c7d" />
<img width="378" height="827" alt="image" src="https://github.com/user-attachments/assets/8c524179-6202-4209-83e2-97d30f8526da" />

During early project feedback, the lack of administrator view was highlighted, remarking that only the seasonal worker flow had been implemented, leaving the administrative role unaddressed or undefined.

To resolve this, a new set of screens was designed and implemented to support the administrator’s tasks, including access to worker performance information, contract status tracking, permit management, and shift coordination features. This iteration completes the system’s role-based structure and ensures that both user perspectives are properly supported within the application.

---

## 9. Accessibility

The accessibility improvements of the project focus on enhancing legibility, contrast, and overall usability for users with different visual conditions, with the goal of reducing interaction barriers and minimizing cognitive load throughout the system.

The following section describes the main accessibility decisions implemented during the design and development of the mobile application, all of which aim to improve readability, visual clarity, and interaction consistency across different devices and user conditions.

- **Font size adjustment option:** The system includes a configurable font size feature that allows users to increase or decrease text size based on their individual visual needs. This ensures better adaptability for users with low vision, reading difficulties, or personal preferences regarding text scaling.
- **Minimum font size and typographic hierarchy:** A minimum font size baseline was defined to improve readability across the interface. Primary content was standardized to a 16px base size, while secondary elements such as labels and helper text were adjusted to 14px. This typographic hierarchy helps maintain clarity while preserving visual structure, especially on smaller or low-end devices.
- **Color contrast improvements:** The color palette was refined to improve readability and visual separation between elements. Text-background combinations were adjusted to increase contrast and reduce strain during prolonged use. These changes follow WCAG accessibility principles, ensuring that content remains legible under different lighting conditions and screen qualities.
- **Clear and distinguishable interactive elements:** Interactive components such as buttons were redesigned to improve visual affordance. Styling adjustments (such as borders, spacing, and visual hierarchy) were applied to ensure that clickable elements are clearly distinguishable from static text, reducing ambiguity and improving overall usability.

---

*Course: User Experience Design | 2026*
