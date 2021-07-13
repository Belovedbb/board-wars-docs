---
layout: default
title: Kanban Service
parent: User Guide
nav_order: 2
---

# Kanban

Kanban is an Agile based methodology which enables you to 
* Visualize the Workflow
* Limit Work in Progress (WIP)
* Manage Flow

Board Wars Kanban has Kanban board for managing workflow, visualizing tasks, columns across all projects.

## Project
A project is an umbrella for a sequence of tasks. It contains columns, tasks, subtasks.
* Mandatory
    * Name: Name of the project.
    * Status: If the status should be active or inactive.
    * Description: Description of project created.
    * Start Date: The start date is automatically generated as the day of creation.
    * End Date: Possibly project completion date.
* Optional 
    * Tag: Tags associated with the project.
    * User Management: Set of Individuals involved in the project. Either private or team based. 

## Column
Columns help to organize our tasks in a more logically packaged way. 
* Mandatory
    * Name: Unique Name of the column.
    * Description: Description of column created.
    * Task Limit: Limit of all task that a column can hold.
* Optional 
    * Color Code: Color code associated with the column.

## Task
A task is an activity that needs to be accomplished within a defined period of time. Tasks are created based on Project and Column selected.
* Mandatory
    * Title: Title of the task.
    * Description: HTML formatted description of the task created.
    * Assignee: The user name of the person the created task is being assigned to.
    * Start Date: The period in which the task officially starts.
    * End Date: Possibly task completion date.
    * Category: The section in which the task created belongs to. The following categories are listed in order of priority/intensity
        * Low
        * Subtle
        * Average
        * High
        * Danger
* Optional 
    * Tag: Tags associated with the task.
    
A task can be adjusted and critical information can be communicated to other team members about the task using a task comment.

Tasks can also be moved from a column to another within the project. This is an excellent way of showing the progression of the task since the point of creation.
