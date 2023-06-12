# [Reddark](https://reddark.untone.uk/)
A website to watch subreddits go dark in realtime.

## Subreddits
Reddark pulls the list of participating subreddits from the [threads on r/ModCoord](https://reddit.com/r/ModCoord/comments/1401qw5/incomplete_and_growing_list_of_participating/). If you are the moderator of a sub that is going dark and that is not displayed on Reddark, you can comment in the thread directly to be automatically added:

> **SubManagerBot**:
>
> If you have already commented your sub below or your sub is already on the list and now going private, please do NOT send a modmail - if you comment here, your sub will be on the list.

## Technologies
This is using Express to host the frontend and Socket.io to serve data. Quite simple code, and not too hard to get your head around.
This is based on the [Original work of D4llo](https://github.com/D4llo/Reddark) with permission.
