# Go Map Access Panic

This repository demonstrates a common error in Go: panics caused by accessing map keys that don't exist.  The `bug.go` file contains the erroneous code, while `bugSolution.go` provides a corrected version.

## Problem

Accessing a map element with a key that doesn't exist will result in a runtime panic.  This can be particularly problematic in production environments.

## Solution

Always check if a key exists before attempting to access its value.  The `bugSolution.go` file shows how to correctly handle this using a conditional statement.