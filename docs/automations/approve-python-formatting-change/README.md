---
title: Automation - Approve Python Formatting Changes
description: Automatically approve PRs that only contain Python formatting changes.
---
# Approve Python Formatting Changes
Approve PRs that only contain formatting changes to Python files. 

<div class="automationImage" style="align:right" markdown="1">
![Approve Python Formatting Changes](approve_python_formatting_change.png)
</div>

<div class="automationDescription" markdown="1">
!!! info "Configuration Description"
    Conditions (all must be true):

    * All of the files end in `.py`.
    * All changes are non-functional

    Automation Actions:

    * Approve the PR
    * Apply a `code-formatting` label.
    * Post a comment that explains the automation.
</div>

!!! example "Approve Python Formatting Changes"
    ```yaml+jinja
    --8<-- "docs/downloads/automation-library/approve_python_formatting_change.cm"
    ```
    <div class="result" markdown>
      <span>
      [:octicons-download-24: Download this example as a CM file.](/downloads/automation-library/approve_python_formatting_change.cm){ .md-button }
      </span>
    </div>

## Additional Resources

--8<-- "docs/snippets/general.md"

**Related Automations**:

--8<-- "docs/snippets/safe-merge-automation.md::2"
--8<-- "docs/snippets/safe-merge-automation.md:4:"

--8<-- "docs/snippets/automation-footer.md"