# MyOnCall

## Inspiration
During Elise's time as an administrative assistant in a family doctor's office, she witnessed firsthand the overwhelming workload physicians faced—not just with patient care, but with extensive paperwork and administrative duties. When she overheard discussions about the time-consuming process of manually creating complex schedules, she asked why they weren't using scheduling software. Their response revealed that no existing solutions addressed their specific needs. This insight inspired the creation of **MyOnCall**, a scheduling application designed specifically for family physicians.

## What it does
MyOnCall transforms the complex task of medical on-call scheduling into an automated, fair, and transparent process. The platform generates intelligent schedules that consider:
* **Physician availability**
* **Historical workload**
* **Clinic coverage needs**

It ensures equitable distribution of shifts (including holidays) while preventing conflicts and maintaining clear communication through comprehensive schedule visualization. By eliminating manual scheduling burdens, MyOnCall allows healthcare providers to focus on what matters most: **patient care**.

## How we built it
We developed MyOnCall using a modern tech stack focused on data processing and user experience:
* **Backend:** **Python** serves as our core language, leveraging its powerful libraries for algorithm development.
* **Database:** **MongoDB** provides a flexible schema design for storing physician profiles, scheduling data, and historical records.
* **Frontend:** **React** was used to create a responsive and intuitive interface.
* **Logic:** The priority-based assignment algorithm uses custom logic to weigh factors like shift history, holiday proximity, and time since last duty. We implemented a modular architecture to separate scheduling logic, conflict resolution, and data management.

## Challenges we ran into
We originally planned to be much more ambitious with our features, but due to time constraints, we had to scale back. At this moment, the project functions primarily as a **demo** of the core scheduling capabilities.

## Accomplishments that we're proud of
* **Fairness Algorithm:** Successfully developed a priority-based system that accounts for complex medical constraints.
* **Holiday Rotation:** Addressed a major pain point by automating holiday shift distribution.
* **Conflict Prevention:** Created a system that reduces overhead by stopping scheduling errors before they occur.
* **UI Design:** Built an intuitive interface that makes dense scheduling data easy to digest.

## What we learned
Through this project, we gained deep insights into the unique scheduling challenges faced by healthcare providers. We learned the importance of **stakeholder input** in developing domain-specific software and discovered that achieving true "fairness" in scheduling requires more nuanced considerations than we initially anticipated.
