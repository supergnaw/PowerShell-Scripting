# PowerShell-Scripting

*this is just a code block to test if syntax highlighting is available*

```PowerShell
# Define a function named Say-Hello
function Say-Hello {
    Write-Host "Hello from the PowerShell function!"
}

# Call the function
Say-Hello
```

## Course Goals

- Demystifying the command-line interface (CLI) for total beginners
- Build foundational PowerShell knowledge step-by-step
- Enable learners to read, write, and troubleshoot basic to intermediate scripts
- Apply scripting to practical tasks like file management, system monitoring, and automation

## Course Structure Overview

> Rough drafted as the modules are being fleshed out and absolutely will change. Ignore any numbers as those will also change

### 1.0 Intro to CLI & PowerShell

- 1.1 What is CLI
  - 1.1.1 Analogy: "text-based remote control"
  - 1.1.2 Comparison between GUI vs CLI
- 1.2 What is PowerShell 
  - 1.2.1 History and purpose
  - 1.2.2 Differences from Command Prompt
- 1.3 Launching PowerShell
  - 1.3.1 Permissions; admin vs non-admin
  - 1.3.2 Console vs Visual Studio Code vs ISE
- 1.4 Basic Navigation
  - 1.4.1 Directory Traversal
  - 1.4.2 Tab completion
  - 1.4.3 Command history
- 1.5 Help system
  - 1.5.1 Discovering with `Get-Help`, `Get-Command`, and `Get-Member`
  - 1.5.2 Parameters

### 2.0 Cmdlets & Syntax Basics

- 2.1 Cmdlet structure
- 2.2 Parameters
- 2.3 Aliases
- 2.4 Help system

### 3.0 Variables & Data Types

- 3.1 Declaring variables
- 3.2 Strings
- 3.3 Integers
- 3.4 Arrays
- 3.5 Hashtables

### 4.0 Operators & Logic

- 4.1 Comparison
- 4.2 Logical
- 4.3 Arithmetic operators

### 5.0 Loops & Conditionals

- 5.1 `if` and `else`
- 5.2 Switches
- 5.3 `for` and `foreach`
- 5.4 `while`

### 6.0 Functions & Script Files

- 6.1 Creating functions
- 6.2 Parameters
- 6.3 Saving `.ps1` files

### 7.0 Error Handling & Debugging

- 7.1 `try`, `catch`, and `finally`
- 7.2 Error action preference
- 7.3 `Write-Debug`

### 8.0 Working with the File System

- 8.1 `Get-Item`
- 8.2 `Copy-Item`
- 8.3 `Remove-Item`
- 8.4 `Test-Path`

### 9.0 Working with Objects & Pipelines

- 9.1 Object properties
- 9.2 `Select-Object`
- 9.3 `Sort-Object`
- 9.4 `Export-Csv`

### 10.0 Remote & Scheduled Tasks

- 10.1 `Invoke-Command`
- 10.2 `New-ScheduledTaskTrigger`
- 10.3 `Register-ScheduledTask`

### 11.0 Intermediate Script Analysis

- 11.1 Reading existing scripts
- 11.2 Understanding flow
- 11.3 Commenting

