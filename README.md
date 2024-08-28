# Roadmap.sh Task Tracker

https://roadmap.sh/projects/task-tracker

## Description

This project is a simple cli tool written in python that allows you to track tasks

## Usage


### Run form the project directory

```bash
chmod +x task-cli
```

```bash
./task-cli
```

### Run from any directory

```bash
chmod +x task-cli
```

```bash
cp task-cli /usr/local/bin
```

> If permission denied, use `sudo`

```bash
sudo task-cli
```

```bash
task-cli
```

## Example

### Add a task

```bash
task-cli add "Buy milk"
```

### List all tasks

```bash
task-cli list
```

### List todo tasks

```bash
task-cli list todo
```

### Mark task as in progress

```bash
task-cli mark-in-progress 1
```

### List all tasks in progress

```bash
task-cli list in-progress
```

### Mark a task as done

```bash
task-cli mark-done 1
```

### Mark a task as done

```bash
task-cli list done
```

### Remove a task

```bash
task-cli delete 1
```