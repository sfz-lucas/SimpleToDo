# SimpleTodo

SimpleTodo is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: Lucas Freeze

Time spent: 6 hours spent in total

The following **required** functionality is completed:

* [ ] User can **view a list of todo items**
* [ ] User can **successfully add and remove items** from the todo list
* [ ] User's **list of items persisted** upon modification and and retrieved properly on app restart

The following **optional** features are implemented:

* [ ] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/SaWndjXpZcK3b8ze9z/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

I ran into only a couple complications. Most of the mistakes I made were small, as in accidentally typing “onItemsClicked” instead of “onItemClicked”. Given the suggestions that java puts in, I didn’t notice this error until reviewing my app code. It most likely would not have been a problem, but I changed it in case there was a point where I typed it without the ‘s’. 
A second problem I ran into was with the “private” sections of MainActivity. These weren’t gone over in the video tutorial, but I put them in because I noticed the code in the instructors window. The error happened with the function “readLines” and “writeLines” within “FileUtils”. My code didn’t recognize these, and thus the app would not run. To solve this, I removed the private sections, and the code “loadItems” and “saveItems”. As a result of this bizarre coding problem, my app does not “retrieve its items properly on app restart”. 
The only other issue I ran into was the “Toast” functionality. Though coded correctly, no message temporarily appeared on my emulator when an activity was completed. 
Other than this, the app runs as required.

Update (01/12/22): These issues were solved and the app runs as expected.

## License

    Copyright [2022] [Lucas Freeze]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
