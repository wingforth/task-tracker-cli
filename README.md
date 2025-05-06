# Task Track CLI

Task tracker is a project used to track and manage your tasks. A simple command line interface (CLI) is built to track what you need to do, what you have done, and what you are currently working on.

## Features

- Add a new task.
- Update a task description.
- Delete a task.
- Mark a task as in progress, done or todo.
- List all tasks.
- List tasks that are done, to done, in progress or todo.

## Required

- python is needed to run this application.
- git is needed to download this application.

## Install

Use git to download this repo.

        git clone https://github.com/wingforth/task-tracker-cli.git

## Usage

- Add a task:

        python task_cli.py add <description>

- Update a task description:

        python task_cli.py update <id> <description>

- Delete a task:

        python task_cli.py delete <id>

- Mark a task on a status (todo, in-progress, done):

        python task_cli.py mark <id> <status>

- List all task:

        python task_cli.py list

- List task that on a status (todo, in-progress, done, not-done):

        python task_cli.py list <status>

## Project

This is a project from [Roadmap](https://roadmap.sh). For more information, please visit [Task Tracker](https://roadmap.sh/projects/task-tracker).
