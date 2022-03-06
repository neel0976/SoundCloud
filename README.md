## Inspiration

Different people have different choices but one thing that binds them together is Music. Everyone loves to listen to music. The choice of music may be different for different people but the purpose solved is the same- to release everyone's stress and make everyone happy. That's why we decided to make a Music Player App through which people can listen to their favorite songs. This inspired us to make a personalized music API where there will be no ads, and the experience while listening to music will be great.

## What it does
- We can search for the song which we want to listen to. We can also make various playlists according to our choice. Users can search for any song. We use Spotify API to get a search result.
- Allows the user to add the current playing song as a favourite one and all the favourite songs can be accessed via navigating to the navigation drawer and clicking the Favourites. User can even remove a song from the favourites.
- A seek bar to quickly navigate to a particular timing of the song.
Play/Pause button to play/pause the song.

## How we built it

- We used pure HTML, CSS, JS, ajax call, and Spotify API.
- We have a flask backend running on IBM's Bluemix cloud hosting platform which performs all necessary requests and page serves.

## Challenges we ran into
- Creating a CockroachDB database for storing uploaded songs.
- Making a real-time music player in a web app.
- Handling the high volume of asynchronous HTTP requests required to go from a single soundcloud playlist URL to a set of recommended tracks required a great deal of research and testing.

## What we learned
Our team learned a lot about all of the frameworks involved, as well as SoundCloud's API. We also learned a lot about teamwork–how to collaborate to solve problems we couldn't deal with alone.

We learned about API call and about ajax working. 

## What's next for SoundCloud

Currently, our app has only some demo songs. We will add more songs that will be stored in our database. We will also add a search function in our app which will help people in finding their favorite songs. We will try our best to give users a good experience.
