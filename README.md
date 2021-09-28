## Flix Part 2

### User Stories

#### REQUIRED (10pts)

- [x] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [x] Implement a shared element transition when user clicks into the details of a movie (1 point).
- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply data binding for views to help remove boilerplate code. (1 point)
- [x] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF

Here's a walkthrough of implemented user stories:

<img src='flixster_demo_2.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

### Notes

The shared element transition is used for the movie description. A challenge I faced was getting this transition to work from the recyclerview. Most documentation shows how to implement the transition from one activity to another, so getting the transition to work from the view took some additional research.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

# Unit 1 - *Flixster*

**Flixster** is an android app that allows users to view the currently playing films.

Submitted by: **Michal Szabla**

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API. (10 points)

The following **optional** features are implemented:

* [x] Views should be responsive for both landscape/portrait mode. (2 points)
* [ ] Display a nice default placeholder graphic for each image during loading (read more about Glide). If you're running your app on an emulator, you can change the network speed of the emulator to test this feature by following the guidance here. (1 point)
* [x] Improve the user interface through styling and coloring (1 to 5 points depending on the difficulty of UI improvements)
* [ ] For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones. (2 points)

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='flixster_demo.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Understanding and implementing the recycler view was the most challenging and time consuming portion of the assignment,
but the provided CodePath videos were a great resource that I will definitely be referring back to in the future.

## License

    Copyright 2021 Michal Szabla

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
