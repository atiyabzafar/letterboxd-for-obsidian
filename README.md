# Letterboxd for Obsidian

This project syncs your Letterboxd diary to a file in Obsidian with date-specific backlinks. This can help you keep track of movies you've seen as well as when you've seen them.

As Letterboxd's API is restrictive, this uses the [public RSS feeds](https://letterboxd.com/fleker/rss/) to get the data. As such, this only can pull the last 50 movies at a time. However, once this plugin is setup, it will continue merging diary entries going forward.

## Example

You open up the command palette and run the **Sync Letterboxd Diary** command. It then fetches data and places it in a file called `Letterboxd Diary.md` in a bulleted list.

```md
- Gave [4 stars to Ahsoka](https://letterboxd.com/fleker/film/ahsoka/) on [[2024-04-04]]
- Gave [4 stars to The Rising of the Moon](https://letterboxd.com/fleker/film/the-rising-of-the-moon/) on [[2024-03-30]]
- Gave [2 stars to Secret Invasion](https://letterboxd.com/fleker/film/secret-invasion/) on [[2024-03-21]]
- Gave [5 stars to Scavengers Reign](https://letterboxd.com/fleker/film/scavengers-reign/) on [[2024-03-20]]
- Gave [3 stars to Lessons in Chemistry](https://letterboxd.com/fleker/film/lessons-in-chemistry/) on [[2024-03-19]]
```

This plugin could use your feedback and help to make it a success!

## Usage:

### Add Last Watched Movie

This command will add the last watched movie in the present active editor. This will be done in a special block. For example:

```md
>[!Last Movie Logged]+ 
> [The Tragedy of Macbeth, 2021 - ★★★★](https://letterboxd.com/ati_zaf/film/the-tragedy-of-macbeth/) on 2024-08-16 
>  <p><img src="https://a.ltrbxd.com/resized/film-poster/5/1/9/0/5/2/519052-the-tragedy-of-macbeth-0-600-0-900-crop.jpg?v=2feba2c908"/></p> <p>Visually stunning. The use of light and shadow is remarkable in this movie. Denzel's monologue about the dagger was incredible.<br />Yet i felt something was amiss. Maybe it was acting by the rest of the cast. Can't put a pin on it.</p>   
```

### Add Last 2 Watched Movies

This works exactly like the one movie.

### Add Movies Watched Today

This command is designed to keep the daily journal, diary keepers. You can use this command to add all the movies you posted on letterboxd today. The day is counted from midnight. You can add this in your daily note to keep a diary for yourself. This will work for most users except for power users that end up tagging 50 movies in a single day. 
