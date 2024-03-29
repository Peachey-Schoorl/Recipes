# Recipe Formats

Ever since people have been typing recipes into computers, developers have been
thinking about a format to store those recipes in. Over the years, the following
formats have evolved:

| Year | Name                    | Author(s)                  | Format(s)                  | Link(s) |
| ---- | ----------------------- | -------------------------- | -------------------------- | ------- |
| 1985 | RxOL                    | David A. Mundie            | Postfix                    | http://web.archive.org/web/20020621235055/http://www.anthus.com/Recipes/CompCook.html |
| 1998 | MealMaster              | Episoft Systems            | Formatted Text             | http://www.wedesoft.de/software/2020/07/07/mealmaster/ | 
| 2000 | RecipeML                | FormatData                 | XML                        | http://www.formatdata.com/recipeml/spec/ |
| 2004 | Tabular Recipe Notation | Michael Chu                | HTML                       | http://www.cookingforengineers.com/forums/viewtopic.php?t=120 |
| 2005 | REML                    | Gary Gocek                 | XML                        | http://reml.sourceforge.net/ |
| 2006 | CookML                  | Jochen 'Nunz' Herz         | XML                        | http://www.kalorio.de/index.php?SCa=../cml/CookML_EN https://cookml.3lands.ch/ |
| 2008 | h-recipe                | Berriman, Ward, Inkster    | Microformat                | http://microformats.org/wiki/h-recipe |
| 2011 | schema.org              | Brickley, Wallis, et al.   | JSON-LD, Microdata, RDFa   | https://schema.org/Recipe |
| 2011 | YumML                   | Paul Jenkins               | YAML                       | <li>https://github.com/vikingcode/vikingcode.github.io/blob/HEAD/_posts/2011-09-21-yumml-not-xml.md <li>https://gist.github.com/magarcia/5897a8078a0e816df04eb7b56f026b02 |
| 2013 | Open Recipe             | Joseph Hall                | YAML                       | https://open-recipe-format.readthedocs.io/ |
| 2015 | Pesto                   | Lars-Dominik Braun         | Formatted Text             | https://6xq.net/pesto/ |

Although they are all well though-out, they also each suffer from one or more
shortcomings. Any of these formats is hard to read, hard to write, or difficult
for machines to parse. They appear too detailed, or not detailed enough.

This has lead many developers to either despair at the current state of affairs
or just pick one and get on with things.

As always, all of these issues are a matter of perspective.

There seems to be a clear distinction between formats that are either human or 
computer friendly.

A format that is hard to write will not pose much of a problem if humans don't
write recipes directly but exclusively use a graphical user interface.

Likewise, a format that is too detailed for human taste, is a perfect fit for
a GUI that only allows users to pick items from predefined menu.

Most formats that are hard to read are not meant to be consumed as-is but expect
to be converted to a human-friendly output format.

So, unless one want to invent yet another format, the choice seems to be: human
or machine?

Of course, as the answer is rarely as binary as that, formats keep coming into
existence every couple of years as yet another developer tries to find the
sweet spot in the balance between those two extremes.

        Human *--------*--------*--------*--------*--------* Machine

So, which format lives where on that line? To answer that question,
we need to take a more detailed look at each format.

## Criteria

_**TK:** Write prose to explain criteria_


- Easy to type ↔️ Hard to type
- Easy to read ↔️ Hard to read
- Loose definitions ↔️ Strict definitions
   
## Formats

_**TK:** Write judgement of each format based on stated criteria_
 
```
    Easy to type  0----1----2----3----4----5----6----7----8 Hard to type
     Easy to read 0----1----2----3----4----5----6----7----8 Hard to read
Loose definitions 0----1----2----3----4----5----6----7----8 Strict definitions
```

### CookML

### h-recipe

### MealMaster

### Open Recipe

### Pesto

### RecipeML

### REML

### RxOL

### schema.org

Used by:

- [Google Search](https://developers.google.com/search/docs/data-types/recipe)
- Google Assistant / Google Home
  > “To enable your recipe for guidance with the Google Home and Google Assistant, make sure you add `recipeIngredient` and `recipeInstructions`. If your recipe doesn’t have these properties, the recipe isn’t eligible for guidance.”

### Tabular Recipe Notation

### YumML

## Conclusion

_**TK:** Write Conclusion once formats have been judged against criteria_

###### tags: `linked-data`, `solid-apps`

<sub>Kreet van [@potherca](https://github.com/potherca)</sub>