# Introduction
## What is the purpose of this project?
Keeping track of information that is changed rarely or mostly in one direction, such as vice, trauma, special abilities, and action ratings.

## What is _not_ the purpose of this project?
Keeping track of information that changes often or fluctuates, like XP, stress, or harm.

# How do I fill in a playbook?
## Playbook is already defined
1. Copy the contents of `character_sheets/Empty_Character.tex` to a new file `character_sheets/<first name>_<surname>_<class>.tex`
2. Change the value of `\Class` to the name of the playbook you want to use
3. Replace the placeholder entries for names, looks, heritage, background, and vice
4. Add a friend and an enemy/rival by adding their index to the `\Friend` and `\Enemy` variables
   * The topmost person in the friend/enemy/rival list corresponds to 0 and the bottommost to 4
5. Set stash to the correct amount
6. Set action ratings to the correct levels
   * Include the base rating for the respective class, i.e. a Cutter always starts with at least 2 skirmish and 1 command
8. Write the names of all chosen skills in the `\SpecialAbilities`-macro.

## Playbook is undefined
1. Define playbook on your own or ask Latte to do it for you and give him an edible reward during the next session
  1. Save the empty playbook as `base_imgs/<classname>.pdf`, most of the ones in use can be found at https://bladesinthedark.com/downloads
  2. Create a preamble `templates/preambles/<classname>.tex`
     * Look at a previously defined playbook preamble to understand what's needed to be done.
  3. Create a template `templates/<classname>.tex`,
     * Look at a previously defined playbook to understand what's needed to be done.
2. See section above
