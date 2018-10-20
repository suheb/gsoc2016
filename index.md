### About The Project.
CTLK Webapp provides a modern reading environment classical languages. The data present in the CLTK corpora with the help of CTLK tools is used to display classical texts along with related metadata like translations, commentaries, definitions etc. 
The webapp consists of two parts:
* [CLTK API](https://github.com/cltk/cltk_api) - The flask based REST API that provides data from the CLTK corpora.
* [CLTK Frontend](https://github.com/cltk/cltk_frontend) - The frontend for the reading environment built with Meteor and React. It consumes the data provided by the API.

### Work Description
During the summer, I first worked on serving metadata like definitions, translations and commentaries though the CLTK API. The data exposed by the API was then ingested into MongoDB and rendered on the frontend. Next up was adding the functionality to enable the users to add annotations and bookmarks to text. Finally, I extended the user profile to add annotations and bookmarks views.

#### Main Features
* Providing definitions for text
    * CLTK API PRs
        * [Adding API endpoint for word definitions](https://github.com/cltk/cltk_api/pull/37)
        * [Adding definition api endpoint test and changing json file dir](https://github.com/cltk/cltk_api/pull/38)
    * CLTK Frontend PRs
        * [Feature/definitions](https://github.com/cltk/cltk_frontend/pull/74)
        * [Adding better word cleaning for definitions and removing unnecessary log statements](https://github.com/cltk/cltk_frontend/pull/75)


* Providing translations for text
    * CLTK API PRs
        * [Adding translation API ](https://github.com/cltk/cltk_api/pull/40)
    * CLTK Frontend PRs
        * [Translation sync and render](https://github.com/cltk/cltk_frontend/pull/76)


* Providing commentary for text
    * CLTK API PRs
        * [Adding commentary endpoint ](https://github.com/cltk/cltk_api/pull/41)
    * CLTK Frontend PRs
        * [Adding commentary sync and render functionality](https://github.com/cltk/cltk_frontend/pull/78)


* Functionality to add annotations and bookmarks to text documents
    * CLTK Frontend PRs
        * [Feature annotation & bookmark](https://github.com/cltk/cltk_frontend/pull/82)
        * [Feature/user accounts](https://github.com/cltk/cltk_frontend/pull/84)


#### Other contributions
* [All commits in CLTK Frontend](https://github.com/cltk/cltk_frontend/commits/develop?author=suheb)
* [All commits in CTLK API](https://github.com/cltk/cltk_api/commits/develop?author=suheb)

### Mentors
My official mentors for this project were Luke Hollis (@lukehollis), Christopher Morse (@christophermorse) and Rob Jenson (@ferthalangur). I really want to thank them for their support and guidance throughout the summer, especially Luke Hollis. A special thanks to Kyle P. Johnson (@kylepjohnson).
***

***

***