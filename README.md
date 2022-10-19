# The Problem: Amazon Music

Amazon Music Unlimited is a premium music subscription service featuring tens of millions of songs available to our millions of customers. We currently provide expert curated, premade playlists, but customers have often requested the ability to create and manage their own custom playlists.

This design document describes the Amazon Music Playlist Service, a new AWS service that will provide the custom playlist functionality to meet our customers’ needs. It is designed to interact with the Amazon Music client and will return a list of song metadata associated with the playlist that the Amazon Music client can use to fetch the song file when playing.

This initial iteration will provide the minimum lovable product (MLP) defined by our product team including creating, retrieving, and updating a playlist, as well as adding to and retrieving a saved playlist’s list of songs.

## Project Mastery Tasks
#### Under each mastery task I have linked to parts of the project that are my code.
## [Mastery Task 1: Finish What We Started](tasks/project-mastery-tasks/MasteryTask01.md)

My Contributions:

Class Diagram
CreatePlaylistActivity
ModelConverter
PlaylistDao
Playlist
Mastery Task 2: I'll Give You an Exception This Time
My Contributions:

UpdatePlaylistActivty
InvalidAttributeChangeException
InvalidAttributeException
InvalidAttributeValueException
Mastery Task 3: Implement the Dagger framework
My Contributions:

AddSongToPlaylistActivity

CreatePlaylistActivity

GetPlaylistActivity

GetPlaylistSongsActivity

UpdatePlaylistActivity

DaoModule

ServiceComponent

AlbumTrackDao

PlaylistDao

AddSongToPlaylistActivityProvider

CreatePlaylistActivityProvider

GetPlaylistActivityProvider

GetPlaylistSongsActivityProvider

UpdatePlaylistActivityProvider

Mastery Task 4: Without Music, Life Would B-flat
My Contributions:

AddSongToPlaylistActivity: V1, V2

CreatePlaylistActivity

GetPlaylistSongsActivity: V1, V2

ModelConverter: V1, V2

AlbumTrackDao

AlbumTrack

Playlist

Mastery Task 5: Zoom, Enhance
My Contributions:

AddSongToPlaylistActivity
GetPlaylistSongsActivity
ModelConverter
Playlist
Mastery Task 6: Create an API Gateway
My Contributions:

Built AWS API Gateway that maps HTTP requests to lambda functions.
Minor changes to codebase here
note: This is a project adapted from Amazon Technical Academy by Bloomtech.
