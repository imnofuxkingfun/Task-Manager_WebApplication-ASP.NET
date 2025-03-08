# Task Manager Web Application  

## Overview  
This is a task management web application built with ASP.NET Core 9. The platform allows users to create and manage projects, boards, organize tasks, and collaborate within teams. The application includes different user roles, project boards, and task assignments to streamline workflow management.  

## Features  

- **User Roles**  
  - Unregistered users can view the platform’s landing page and access login and registration forms.  
  - Registered users can be members, project organizers, or administrators.
  - Registration can be done through third-party organisations as well.  
  - Users who create a project automatically become that project's organizer.  
  - Administrators have full access to manage users, projects, boards and tasks.  

- **Project and Board Management**  
  - Projects contain boards, where tasks are organized.  
  - Project organizers can add or remove project members, assign organizers, create tasks, and assign them.  
  - Each board lists all tasks within a project.  

- **Task Management**  
  - Tasks include a title, description, status, start date, due date, and media content (text, images, embedded YouTube and TikTok videos).  
  - Tasks must have valid start and end dates.  
  - Organizers can add, edit, delete, and assign tasks to project members.  
  - Members can update task status and leave comments.  

- **Collaboration**  
  - Members can comment on assigned project tasks and edit or delete their own comments.  
  - Task statuses can be updated to **Not Started, In Progress, or Completed** by both members and organizers.  

- **Administrator Controls**  
  - Administrators have full control over projects, tasks, users, and teams.  
  - They can delete tasks, comments, and users, as well as manage user permissions.  

The application includes a structured database with sample data to simulate a real-world task management system.
