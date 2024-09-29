# Symbolic rules for mathematical problems
- Symbolic system, capturing all the rules in different mathematical subjects.
- Kind of a compound AI system - Excel.
- Easy since there are finite rules - BODMAS has 4 operators, that can only be arranged 4! ways, out of which only 1 is correct. We could map different distractors easily.
- Would also be easy to write the natural language sentiment from the rules.
# Approaches
- Contrastive Learning - create negative sample points
- This can be done as part of data pre-processing.
- Model could start by identifying correct answer for a problem. Then learn to identify the misconceptions.
- Misconceptions could be created by rule manipulation (permutations combinations or LM generation).
- Starting point - different notebooks, models, embedding approaches/tasks, maybe for different subjects, etc