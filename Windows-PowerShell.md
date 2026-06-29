# Windows PowerShell — Completed ✅

- **Room:** TryHackMe - Windows PowerShell
- **Date:** May 2, 2027
- **Day:** 5/300

## Overview
Day 5 of my 300-day cybersecurity commitment, and I completed the Windows PowerShell room on TryHackMe.

PowerShell is the second command-line utility built for Windows. Unlike CMD, which processes plain text, PowerShell works with objects, making it powerful for automation, system analysis, and cybersecurity operations.

---

## What I Learned

### PowerShell Basics
- Uses **cmdlets** following a **Verb-Noun** naming convention
- Can launch via:
  - Start Menu
  - Run dialog (`Win + R`)
  - Typing `powershell` inside CMD
- Cross-platform: Windows, macOS, Linux

### File System Operations
- `Get-ChildItem` → List directory contents
- `Set-Location` → Change directory
- `New-Item` → Create files/directories
- `Remove-Item` → Delete files/directories
- `Get-Content` → Read file contents

### Piping & Filtering
- `|` → Pipe output
- `Where-Object` → Filter objects
- `Sort-Object` → Sort output
- `Select-Object` → Select properties

#### Comparison Operators
- `-eq` → Equal
- `-ne` → Not Equal
- `-gt` → Greater Than
- `-ge` → Greater Than or Equal
- `-lt` → Less Than
- `-le` → Less Than or Equal

### System & Networking
- `Get-ComputerInfo`
- `Get-NetIPConfiguration`
- `Get-LocalUser`

### Real-Time Analysis
- `Get-Process`
- `Get-Service`
- `Get-NetTCPConnection`

### Scripting
- `Invoke-Command`
- Remote command execution
- Comparable to Bash scripting

---

## Problems I Faced

| Problem | Solution |
|---|---|
| Forgot `Where-Object` syntax | Used `Get-Command *-Object` |
| Too much TCP output | Used `Select-Object` |
| Hidden files not visible | Used `Get-ChildItem -Force` |

---

## Commands Practiced

```powershell
Get-Command
Get-Help
Get-ChildItem
Set-Location
New-Item
Remove-Item
Get-Content
Where-Object
Sort-Object
Select-Object
Get-ComputerInfo
Get-NetIPConfiguration
Get-Process
Get-Service
Get-NetTCPConnection
Get-FileHash
Invoke-Command
```

---

## Key Takeaway
PowerShell is much more powerful than CMD because it handles structured objects instead of plain text.

This room strengthened my Windows command-line and system analysis fundamentals.
