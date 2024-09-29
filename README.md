<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Search</title>
    <script defer src="script.js"></script>
</head>
<body>
    <h1>Google Books Search</h1>h1>
    <!-- Main Menu -->
    <nav>
        <a href="index.html">Home</a> |
        <a href="bookshelf.html">My Bookshelf</a>
    </nav>
    <!-- Search Form -->
    <div>
        <label for="searchTerm">Search Books:</label>
        <input type="text" id="searchTerm" placeholder="Enter book title, author, etc.">
        <button onclick="searchBooks()">Search</button>
    </div>
    <!-- Search Results Section -->
    <div id="results"></div>
    <!-- Pagination -->
    <div id="pagination"></div>
</body>
</html>
