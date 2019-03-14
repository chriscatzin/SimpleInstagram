# Project 3 - *SimpleInstagram*

**SimpleInstagram** is a photo sharing app similar to Instagram but using Parse as its backend.

Time spent: **27** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can view the last 20 posts submitted to "Instagram".
- [ ] User can pull to refresh the last 20 posts submitted to "Instagram".
- [x] The user should switch between different tabs - viewing all posts (feed view), capture (camera and photo gallery view) and profile tabs (posts made) using fragments and a Bottom Navigation View. (2 points)

The following **optional** features are implemented:

- [ ] Style the feed to look like the real Instagram feed.
- [x] User can load more posts once he or she reaches the bottom of the feed using infinite scrolling.
- [ ] Show the username and creation time for each post.
- [ ] User can tap a post to view post details, including timestamp and caption.
- [x] User Profiles
      - [ ] Allow the logged in user to add a profile photo
      - [ ] Display the profile photo with each post
- [ ] Tapping on a post's username or profile photo goes to that user's profile page and shows a grid view of the user's posts
- [ ] User can comment on a post and see all comments for each post in the post details screen.
- [ ] User can like a post and see number of likes for each post in the post details screen.
- [x] Run your app on your phone and use a custom camera view

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

## PART ONE GIF

<img src='https://github.com/chriscatzin/SimpleInstagram/blob/master/SimpleInstagram.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## PART TWO GIF

<img src='https://github.com/chriscatzin/SimpleInstagram/blob/master/SimpleInstagram-PartTwo.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## Notes

Describe any challenges encountered while building the app.

My app kept on crashing, so I ended up trying a new emulator. That new emulator seemed to have fixed the problem.
Also I had invalid session tokens when I was trying to run my app, turns out I was misspelling a word in one of
my tokens. Overall this was a well-learning project, and I learned so much that I did not know before!

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2019] [Christopher Catzin]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
