# The Problem: Amazon Music

Amazon Music Unlimited is a premium music subscription service featuring tens of millions of songs available to our millions of customers. We currently provide expert curated, premade playlists, but customers have often requested the ability to create and manage their own custom playlists.

This design document describes the Amazon Music Playlist Service, a new AWS service that will provide the custom playlist functionality to meet our customers’ needs. It is designed to interact with the Amazon Music client and will return a list of song metadata associated with the playlist that the Amazon Music client can use to fetch the song file when playing.

This initial iteration will provide the minimum lovable product (MLP) defined by our product team including creating, retrieving, and updating a playlist, as well as adding to and retrieving a saved playlist’s list of songs.

## Project Mastery Tasks
#### Under each mastery task I have linked to parts of the project that are my code.
## [Mastery Task 1: Finish What We Started](tasks/project-mastery-tasks/MasteryTask01.md)

My Contributions:
- [Class Diagram](resources/mastery-task1-music-playlist-CD.puml)

- [CreatePlaylistActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/c638d6daabe0e4c63d8e2f4f65d0d3788389ea95#diff-a7937bf4c20dcfcbbc187a2dcdf946b229e8f2e7e3534b3ea2ac514cef092115)

- [ModelConverter](https://github.com/AbeKalovsky/music_playlist_service/commit/c638d6daabe0e4c63d8e2f4f65d0d3788389ea95#diff-4169855891e5fb77c2260a0d0e9930b682f7b333b9f3dc71dbe284fe4b72c42d)

- [PlaylistDao](https://github.com/AbeKalovsky/music_playlist_service/commit/c638d6daabe0e4c63d8e2f4f65d0d3788389ea95#diff-1c5d4eb763cfc93c0a7bdb156ecfec18e7b78d32d4f81d4eba77b857e56c6cad)

- [Playlist](https://github.com/AbeKalovsky/music_playlist_service/commit/c638d6daabe0e4c63d8e2f4f65d0d3788389ea95#diff-413ee09180108ae1dae00e691dec611c13b7e0c04d84a9be558175b2578ff2e8)


## [Mastery Task 2: I'll Give You an Exception This Time](tasks/project-mastery-tasks/MasteryTask02.md)
My Contributions:

- [UpdatePlaylistActivty](https://github.com/AbeKalovsky/music_playlist_service/commit/c638d6daabe0e4c63d8e2f4f65d0d3788389ea95#diff-fb3168254ba1ac2f8abc4f5d9721d58d994ec24a87d420220a9ebd3f6b68ba82)

- [InvalidAttributeChangeException](https://github.com/AbeKalovsky/music_playlist_service/commit/c638d6daabe0e4c63d8e2f4f65d0d3788389ea95#diff-fa784c95b3530ad5f0fa1e811978b52d095b91bf152ee7437891447f3b556cb9)

- [InvalidAttributeException](https://github.com/AbeKalovsky/music_playlist_service/commit/c638d6daabe0e4c63d8e2f4f65d0d3788389ea95#diff-8f4609d714dc79de9940b94658e5adc9f57a7acff0b921904e2bbc8c32effcb0)

- [InvalidAttributeValueException](https://github.com/AbeKalovsky/music_playlist_service/commit/c638d6daabe0e4c63d8e2f4f65d0d3788389ea95#diff-2ac9370008753a924692595822a7379e899cbd548c546db491db2469ccbb1608)


## [Mastery Task 3: Implement the Dagger framework]


My Contributions:

- [AddSongToPlaylistActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-66b360d37c60653172eca2824941919519a27587b974b9fe3461d25694afbac1)

- [CreatePlaylistActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-a7937bf4c20dcfcbbc187a2dcdf946b229e8f2e7e3534b3ea2ac514cef092115) 

- [GetPlaylistActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-e7c74fb8006ff5c947b64eb0d612429f634ca5372d2a55cb59596627738b94e7)

- [GetPlaylistSongsActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-a7637afd7182599ed5a2fe581d40ad78e04c4a0e1738acf5160a3842384f285e)

- [UpdatePlaylistActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-fb3168254ba1ac2f8abc4f5d9721d58d994ec24a87d420220a9ebd3f6b68ba82)

- [DaoModule](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-c616e433bbd0f3863899faffa50db0256992d87850a2213adf41b4330c98eb96)

- [ServiceComponent](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-3aae4a73cd29f5675986157714db554a378724ea4df37bc70b836d90b864fd36)

- [AlbumTrackDao](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-fe3a3d5bb57e6346a0b336a4419cc21ed07346743b0145a769181ee899b2d049)

- [PlaylistDao](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-1c5d4eb763cfc93c0a7bdb156ecfec18e7b78d32d4f81d4eba77b857e56c6cad)

- [AddSongToPlaylistActivityProvider](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-ba66a93262f8f97691bda8047775ac5efbb7fad958006a796766cb3cee1aefeb)

- [CreatePlaylistActivityProvider](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-98bc513d06e7b453c62f705679256ca832e457121e8b8406bb6f604d3c3b17b3)

- [GetPlaylistActivityProvider](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-fc10e56e74f5ef224c36256946d58a5b4863f4afe809af8c8375a169501c0339)

- [GetPlaylistSongsActivityProvider](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-3a63b62a02a6ae3cb08487245db36425e23073c2eceba600d79ce128c0035563)

- [UpdatePlaylistActivityProvider](https://github.com/AbeKalovsky/music_playlist_service/commit/b984fef33ea77e67224ff2c87c951cdd8ca80a88#diff-8ef03ce0f23ef37e3d73eecebe1beaaa18ed707964e6494cee3f7b87a916795f)

## [Mastery Task 4: Without Music, Life Would B-flat]
My Contributions:

- [CreatePlaylistActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/68539e0010f5438dc0599110ef5e94f6a53645f1#diff-a7937bf4c20dcfcbbc187a2dcdf946b229e8f2e7e3534b3ea2ac514cef092115)

- [ModelConverter](https://github.com/AbeKalovsky/music_playlist_service/commit/68539e0010f5438dc0599110ef5e94f6a53645f1#diff-4169855891e5fb77c2260a0d0e9930b682f7b333b9f3dc71dbe284fe4b72c42d)

- [AlbumTrack](https://github.com/AbeKalovsky/music_playlist_service/commit/68539e0010f5438dc0599110ef5e94f6a53645f1#diff-8a1da4c6a4aa14903edfea8fc9e0555e824299cfedc7e3b4a43b9a0e3ac3f361)

## [Mastery Task 5: Zoom, Enhance]
My Contributions:

- [AddSongToPlaylistActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/68539e0010f5438dc0599110ef5e94f6a53645f1#diff-66b360d37c60653172eca2824941919519a27587b974b9fe3461d25694afbac1)

- [GetPlaylistSongsActivity](https://github.com/AbeKalovsky/music_playlist_service/commit/68539e0010f5438dc0599110ef5e94f6a53645f1#diff-a7637afd7182599ed5a2fe581d40ad78e04c4a0e1738acf5160a3842384f285e)

- [Playlist](https://github.com/AbeKalovsky/music_playlist_service/commit/68539e0010f5438dc0599110ef5e94f6a53645f1#diff-413ee09180108ae1dae00e691dec611c13b7e0c04d84a9be558175b2578ff2e8)

## [Mastery Task 6: Create an API Gateway]

My Contributions:

- Built AWS API Gateway that maps HTTP requests to lambda functions.

note: This is a project adapted from Amazon Technical Academy by Bloomtech.
