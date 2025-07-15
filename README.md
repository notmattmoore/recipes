# Personal Recipes and Cookbook Index

This repository contains a collection of personal recipes and references to
recipes in various cookbooks. The document is built using LaTeX, and includes
custom commands and environments for typesetting recipes.

## Commands

| Command                    | Description                                                 |
| ---                        | ---                                                         |
| `\chapterrec{title}`       | chapter of recipes                                          |
| `\chaptertoc{title}`       | chapter of recipes with chapter table of contents           |
| `\recipe{title}`           | a single recipe                                             |
| `\erecipe{title}{source}`  | an external recipe, adds ToC entry only                     |
| `\itemNL`                  | item without label, but spaced consistent with other items  |
| `\namepageref[<s>]{label}` | typeset as "\<name\>\<s\>\<pg\>", s defaults to " on page " |
| `\degF`, `\about`          | cooking shorthand                                           |


## Environments

| Environment                                                                            | Description                                                           |
| ---                                                                                    | ---                                                                   |
| `\begin{ingredients}[alt title]`                                                       | list of ingredients, default title is "Ingredients"                   |
| `\begin{timeline}[alt title]`                                                          | timeline list, default title is "Timeline"                            |
| `\begin{IT}[<col ratio>]`                                                              | ingredients and timeline in two asymmetric columns                    |
| `\begin{directions}[alt title]`                                                        | list of directions in two even columns, default title is "Directions" |
| `\begin{directions1col}[alt title]`                                                    | list of directions in one column, default title is "Directions"       |
| `\begin{twocols}`                                                                      | shortcut for `\begin{multicols}{2}`                                   |
| `ingredientslist`, `timelinelist`, `directionslist`, `recipelist` `[enumitem options]` | enumitem list environments, self-explanatory                          |
