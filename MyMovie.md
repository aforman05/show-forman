# Andrea Forman

My favorite movie is the Sound of Music. I really like this movie because it is a musical and I used to sing and dance. I also like this movie because it is set in Austria and I am enamored by German/Austrian history.

![Julie Andrews](music.jpg)

---
The table below shows a list of actors who I think would be good in the main role of Maria in the Sound of Music. The table also gives a few reasons for why these actresses would good selections.
| Actor name | Reasoning | Age |
| --- | --- | ---: |
| Emily Blunt | Has been in musicals | 41 |
| Lin-Manuel Miranda | Musical genius | 45 |
| Amy Adams | Humor | 50 |
| Judy Garland | Beautiful voice | Deceased |

---
# Favorite Quotes

> The saints did not all begin well, but they ended well.
> *St. John Vianney*

> Be who God meant you to be and you will set the world on fire!
> *St. Catherine of Siena*

---
# Code Snippet

Creates an abstract base class to test if objects adhere to given specifications.
```
from abc import ABCMeta, abstractmethod


class BaseClass(metaclass=ABCMeta):
    @abstractmethod
    def foo(self):
        pass

    @abstractmethod
    def bar(self):
        pass


class ConcreteClass(BaseClass):
    def foo(self):
        pass

    def bar(self):
        pass


instance = ConcreteClass()
```
[Link to code snippet](https://code.pieces.app/collections/python)