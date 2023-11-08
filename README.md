# 25340-4

Test Details:

1. Create repo with two packages,  one with a label and one with none
2. Renovate the repo ... with old logic
3. Add new labels in config and renovate the repo ... this time with new logic
4. Expected: no new labels added to any update PR since they have been created with old logic 
