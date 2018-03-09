# Pandemic recipe for the TNU course handout

You will need [pandemic](https://www.npmjs.com/package/pandemic) and its dependencies installed.

## Install the Template

```bashrc
pandemic resource install recipe --as tnu-course  https://github.com/lionel-rigoux/pandemic-tnu-course.git
```

## Write your document in markdown

Create a markdown file with the following front matter:

```markdown
---
title: 'Spring Semester 2018 -- Exercice X'
date: 2018/XX/XX
pandemic:
  recipe: tnu-course
---

# Exercice 1

Lorem ipsum...
```

## Compile to pdf

```bashrc
pandemic publish myExercice.md
```
