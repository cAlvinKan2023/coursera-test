# coursera-test
Coursera test repository
<!DOCTYPE html>
<html>
<head>
	<title>Book Exchange</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<h1>Book Exchange</h1>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">Browse Books</a></li>
				<li><a href="#">Profile</a></li>
				<li><a href="#">Log Out</a></li>
			</ul>
		</nav>
	</header>

	<main>
		<section id="search-bar">
			<form>
				<input type="text" name="search" placeholder="Search for a book...">
				<button type="submit">Search</button>
			</form>
		</section>

		<section id="book-listings">
			<h2>Available Books</h2>
			<ul>
				<li>
					<img src="book-cover.jpg" alt="Book Cover">
					<h3>Title of Book</h3>
					<p>Author Name</p>
					<p>Description of Book</p>
					<button>Request Book</button>
					<button>Add to Wishlist</button>
				</li>
				<!-- Repeat for more books -->
			</ul>
		</section>
	</main>

	<footer>
		<p>&copy; 2021 Book Exchange. All rights reserved.</p>
	</footer>
</body>
</html>
