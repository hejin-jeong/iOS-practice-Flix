# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="http://g.recordit.co/VfFpapClyQ.gif" width=250><br>

### Notes
- When I set the initial pointer to the Movies Navigation Controller, the page didn't show up on the simulator. However, when I changed the initial View Controller to the Tab Bar Controller, the Movies list was visible when I built the simulator.
- I wonder why the tab bar disappears when I scroll up to the top and bottom.
---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="http://g.recordit.co/chYH16qD1j.gif" width=250><br>

### Notes
- Since the data set is a JSON file, to access the properties of each movie, I had to tap into the file and again tap into each movie. However, at first I tapped into the file just once and tried to find the properties' names, which made an error. Therefore, I changed the variable to each movie item and tapped inside each item to find the property "titles" and got what I intended.
