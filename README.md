<p>Using the song and log datasets, need to create a star schema optimized for queries on song play analysis.<br>
This includes the following tables.</p>

### Fact Table
<p>songplays - records in log data associated with song plays i.e. records with page NextSong<br>
 *songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent.</p>

### Dimension Tables
<p>users - users in the app<br>
 *user_id, first_name, last_name, gender, level.</p>
 
<p>songs - songs in music database<br>
 *song_id, title, artist_id, year, duration.</p>
 
<p>artists - artists in music database<br>
 *artist_id, name, location, latitude, longitude.</p>
 
<p>time - timestamps of records in songplays broken down into specific units<br>
 *start_time, hour, day, week, month, year, weekday</p>
