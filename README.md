# Pre-work - *JackN's Blog*

Submitted by: **Ngô Tấn Phát**

Time spent: **5** hours spent in total

URL: **http://young-plains-4147.herokuapp.com/articles**

## User Stories

The following **required** functionality is complete:

* [x] User can create a new post, formatted using the Markdown language.
* [x] User can edit an existing post.
* [x] There is one post that introduces the App Creator with name, picture.

The following **optional** features are implemented:
* [x] User can delete stories, with an alert that asks the user to confirm.
* [ ] User can enter a search term and see all posts with titles that contain the search term.
* [ ] User can add "tags" to a post, and filter posts by tag. 
* [ ] There is a "navbar" that is responsive to window size similar to http://v4-alpha.getbootstrap.com/examples/navbar/. **NOTE**: This is currently buggy in Bootstrap v4 Alpha. For a workaround, look at the CodePen associater dhere: https://github.com/twbs/bootstrap/issues/18263. 
* [ ] User can see how many views a post has. 
* [ ] User can leave a comment on a post.

The following **additional** features are implemented:

- [x] Improve show page so user can see clearly as homepage!
- [x] Improve edit and create page!

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

![Video Walkthrough](http://s17.postimg.org/onksglibj/jackn_ruby.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

- Problem when install postgresql on Windows.
- Problem with app/views/layouts/application.html.erb => add "gem 'coffee-script-source', '1.8.0'"
- Problem connect postgresql DB, missing username and password.
- Problem when add gem 'bootstrap', '~> 4.0.0.alpha1', conflict sass version.
- This line "gem 'rails_12factor', group :production", missing :

## License

    Copyright [2015] [jackn]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
