---
title: 'Python Basis'
description: 'In de eerste les leer je hoe je de print functie werkt.'
---

## Je eerste python code.

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

In the Python script on the right, you can type Python code to solve the exercises. If you hit Run Code or Submit Answer, your python script (script.py) is executed and the output is shown in the IPython Shell. Submit Answer checks whether your submission is correct and gives you feedback.

You can hit Run Code and Submit Answer as often as you want. If you're stuck, you can click Get Hint, and ultimately Get Solution.

You can also use the IPython Shell interactively by simply typing commands and hitting Enter. When you work in the shell directly, your code will not be checked for correctness so it is a great way to experiment.

`@instructions`
Print de tekst met de volgende woorden: **Hello World.**

`@hint`
Gewoon blijven proberen tot het je lukt!

`@pre_exercise_code`
```{python}


```

`@sample_code`
```{python}
#Print de tekst
```

`@solution`
```{python}
Hello World
```

`@sct`
```{python}
Ex().check_correct(
  has_output("Hello World")
)
success_msg("You're a coding rockstar!")
```
