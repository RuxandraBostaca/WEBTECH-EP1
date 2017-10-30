#Ruxandra Bostaca
#Manager videoclipuri favorite integrat cu Youtube

Componente:
1. List of Video playlists
2. Selected Video playlist - details
3. Video Search
4. Search results + add to playlist button
5. New playlist button
6. Remove playlist(s) button

User components:
View list of playlists
View specific playlist + Edit playlist (remove videos, reorder)
Search videos by name
Search results - add to playlist(s)
New playlist
Delete playlist(s)

Apeluri API:
GET /list
GET /list/:id/playlist
GET /videos?Search= (search API)
POST /playlist
PUT /playlist/:id
PUT /playlist/:videoid
...
