# Inconsistent :focus-visible Behavior in CSS

This repository demonstrates an issue with the CSS `:focus-visible` pseudo-class.  The goal is to style elements only when they have keyboard focus, excluding programmatic focus changes (e.g., JavaScript focusing an element).  However, the behavior is inconsistent across different browsers and assistive technologies.

## Problem Description

The `bug.css` file contains CSS rules using `:focus-visible`.  In some browsers (or when using specific assistive technologies), the expected styling is not applied. This inconsistency makes it difficult to create an accessible and visually consistent user experience.

## Solution

The `bugSolution.css` file offers a potential solution or workaround to address the inconsistency.  It's important to note that there may not be a single perfect solution, and the best approach may depend on the specific context and browser/assistive technology support.