# Chronos

TL;DR: Chronos is a course management platform that optimizes scheduling for students, teachers, and administrators by predicting and generating schedules based on preferences and availability, addressing course overbooking and streamlining the planning process.

Chronos is a cutting-edge course management platform designed to enhance the scheduling experience for students, teachers, and administrators. Chronos utilizes advanced algorithms to generate optimized course schedules based on student preferences, curriculum requirements, and instructor availability. By automating and streamlining the scheduling process, Chronos simplifies course planning and registration, offering a user-friendly interface that makes managing academic schedules efficient and straightforward.

## Motivation

We currently use banner for course registration and scheduling. However, the process is manual and time-consuming, often leading to scheduling conflicts, overbooked courses, and student dissatisfaction. By implementing Chronos, we aim to address these challenges by providing an intelligent and automated scheduling solution that optimizes course schedules based on student preferences, curriculum requirements, and instructor availability. Students and teachers should focus on learning and teaching, not on managing schedules.

## Features

### Course Planning

Student-Centric Planning: Students begin by selecting the courses they plan to take for the upcoming semester. This list of planned courses is essential for generating personalized schedules that fit the students' academic needs and preferences.

Curriculum Integration: The app has access to the full curriculum for all majors, ensuring that students are guided in selecting courses that align with their degree requirements and progression paths.

### Schedule Generation

Optimized Scheduling: The app uses the planned course selections to automatically generate potential schedules. It takes into account various constraints such as course prerequisites, time slots, and teacher availability.

Intelligent Algorithms: Advanced algorithms consider factors like avoiding time conflicts, optimizing course load distribution, and matching student preferences with available time slots.

### Teacher Authorization

Schedule Review: Once the schedules are generated, teachers have the opportunity to review, modify, and approve them. This step ensures that the schedules are feasible and meet the constraints and preferences of both teachers and students.

Constraint Management: Teachers can impose constraints or preferences, such as limiting the number of classes they teach in a day, which the app takes into account in future scheduling cycles.

### Student Confirmation

Approval Process: After teachers have authorized the schedules, students can review their proposed schedule. They can either accept the schedule or request changes if it doesn’t meet their needs.

Change Requests: The app facilitates an easy and transparent process for students to request adjustments, which are then subject to further review and approval.

### Administrative Tools

Course and Instructor Management: Administrators and teachers can easily create, update, and manage course offerings, instructor assignments, and other academic resources.

Reporting and Analytics: The app provides insights into course demand, student preferences, and scheduling efficiency, helping administrators make informed decisions for future semesters.

## Architecture

### Database

The app uses a combination of graph, relational, and document databases to handle the complex relationships between students, courses, and schedules, as well as to manage structured and unstructured data efficiently.

### Scheduling

The app’s core scheduling engine utilizes graph-based algorithms to traverse relationships between courses, students, and instructors, optimizing schedules to minimize conflicts and meet the constraints of all parties involved.

### User Experience

The app offers a user-friendly interface for students to plan their academic paths, for teachers to manage course offerings, and for administrators to oversee the entire process. Notifications and alerts keep all parties informed of important updates and deadlines.

## Use Cases

A large Universities: Where thousands of students need to register for hundreds of courses, the app can significantly reduce the administrative burden by automating and optimizing the scheduling process.

Specialized Programs: In programs with complex prerequisites or scheduling constraints, the app ensures that students can progress smoothly through their curriculum without unnecessary delays or conflicts.

Distance Learning: For institutions offering online or hybrid courses, the app can manage different time zones and asynchronous course offerings, ensuring that all students have access to the necessary courses.

## References

- [Course Scheduling Problem](https://en.wikipedia.org/wiki/Course_scheduling_problem)
- [Graph Algorithms](https://en.wikipedia.org/wiki/Graph_algorithm)
- [Database Management Systems](https://en.wikipedia.org/wiki/Database_management_system)
- [User Experience Design](https://en.wikipedia.org/wiki/User_experience_design)
- [Schedule of Classes, University of California, Berkeley](https://classes.berkeley.edu/)
- [ExploreCourses, Stanford University](https://explorecourses.stanford.edu/)
- [Course Catalog, Massachusetts Institute of Technology](https://catalog.mit.edu/)

## License

This project is licensed under the MIT License - see [LICENSE](./LICENSE) for details.