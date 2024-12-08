# Elixir Enum.reduce Unexpected Behavior

This repository demonstrates a potential issue with using `Enum.reduce` in Elixir when dealing with empty lists or lists where the condition for the sum is never met. The initial value of the accumulator may lead to unexpected outputs in these scenarios.

## Bug Report

The code in `bug.ex` shows a simple `Enum.reduce` operation.  While it functions as expected for most lists, it fails to handle cases where no element satisfies the condition or when the list is empty.