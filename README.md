# Multithreaded Data Sorter (Server and Client)

______________

# Usage

Possible Client Inputs (sorter_client):
- ./sorter_client -c <column name> -h <hostname>.cs.rutgers.edu -p <port number>
- ./sorter_client -c <column name> -h <hostname>.cs.rutgers.edu -p <port number> -d <input directory> 
- ./sorter_client -c <column name> -h <hostname>.cs.rutgers.edu -p <port number> -o <output directory>
- ./sorter_client -c <column name> -h <hostname>.cs.rutgers.edu -p <port number> -d <input directory>  -o <output directory>

where <column name> may be any of the following fields:
- director_name, num_critic_for_reviews, duration, director_facebook_likes, actor_3_facebook_likes, actor_2_name, actor_1_facebook_likes, gross, genres, actor_1_name, movie_title, num_voted_users, cast_total_facebook_likes, actor_3_name, facenumber_in_poster, plot_keywords, movie_imdb_link, Num_user_for_reviews, language, country, content_rating , budget, title_year, actor_2_facebook_likes, imdb_score, aspect_ratio, movie_facebook_likes


Possible Server Inputs (sorter_server):
●	./sorter_server -p <port number>

______________

