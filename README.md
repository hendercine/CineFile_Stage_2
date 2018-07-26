# CineFile
An app to allow users to discover the most popular movies playing based on data from TheMovieDB API (themoviedb.org). Some of its features include a clickable poster grid that users can sort by ratings or popularity, a list of viewable trailers that updates from the network periodically, and responsive designs for tablets and phones. It uses movie, review and trailer POJOs, fetches and parses the JSON data from the API on the background thread using AsyncTask and then using the Parcelable library to parcel the data in bundles for display on the UI thread.