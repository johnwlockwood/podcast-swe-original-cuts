Software Engineering at Google: Original Cuts: static podcast feed (feed.xml, episodes.json, cover.jpg).
Audio lives in the shared Cloudflare R2 bucket (see podcast.json storage). Never commit audio.
Add: ./publish_episode.py add-remote --file NAME.mp3 --title T --description D [--date ISO]
(shared_storage: remove never deletes R2 objects; never pass --delete-file).
