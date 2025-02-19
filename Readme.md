# Features Implemented
- User and Admin Authentication with json web tokens
- Used Model, View and Controller as file structure, with custom middlware for route protection i.e. Authorization
- Used Context and local storage for easier data retreival even if a page is refreshed.
- Wasn't able to make an admin panel because of time constraints but above you can see few screenshots in which I have made admin backend api calls using POSTMAN
- Was able to retreive movies based on genre, language and theatre(based on city).
- Was able to choose date and showtime to watch movie in a particular city.
- Was able to book seats and pay 
- Tried to make sure that if a user selected the sits and didn't pay, then the seat should be blocked for them for 5 mins using redis but it caused some error, so I removed it.
- Wasn't able to host, but if you want to check I done various projects which are hosted live.

# Installation Setup (MERN+Vite)
1. run: npm i to download all the node_modules based on package.json
2. run server: cd server, npm run dev
3. run client: cd movie-ticket-management-system, npm run dev
