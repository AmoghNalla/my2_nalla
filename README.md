# my2_nalla
# Amogh Reddy Nalla
###### Favorite vacation spot

My favorite vacation spot is anywhere at the beaches because of its waves or atmosphere over there give me **peaceful**, **joyful**, and a **pleasant** experience.
I really love to be that way
I feel very relaxing when I'm around there.

---

# List of activities I do at my vacation spot

1. Playing volley ball
2. Admiring the view
3. Eating

* Dishes of food I get at my vacation spot
    * Fried rice
    * Noodles
    * pizza and burgers

**[page](MyStats.md)** 

---

# Sports Table

In this section, I am going to talk about four sports that I personally recommend trying for several reasons. As each sport offers unique benefits and the experiences, it's one of the great ways to be fit and strong.

| Sport Name | Benefits | Hours |
| --- | --- | ---: |
| Cricket | Develops team work and strategy | 5-6 hours |
| Volley ball | Great for arms | 3-4 hours |
| Kho - Kho | Great way to improve running | 4-5 hours |
| Kabaddi | Sharpen your feet moment | 4-5 hours |

---

# Scientists Quotes

>"He who can listen to the music in the midst of noise can achieve great things."- *Heinlein*

>"Build a strong base. The journey to peaks of excellence requires a strong base camp."- *CNR Rao*

---

# Adding a code snippet

How do you connect to database with PHP?

<https://stackoverflow.com/questions/40332242/connection-to-database-php>

```
<?php

$hostname = 'localhost';
$user = 'username';
$pass = 'password';
$database = 'database_name';

$db_connection = new PDO( "mysql:host=" . $hostname . ";dbname=" . $database, $user, $pass );

$results = $db_connection->query( 'SELECT testimonial, author FROM recommendations WHERE 1 ORDER by rand() LIMIT 1' );

foreach ( $results as $row ) {
	echo '<p id="quote">' . $row['testimonial'] . '</p>';
	echo '<p id="author">&ndash;' . $row['author'] . '</p>';
}

// Close the connection
$db_connection = null;
```

<https://css-tricks.com/snippets/php/basic-database-connection-random-query-display-result/>


