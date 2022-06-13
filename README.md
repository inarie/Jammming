# Jammming :notes:

A web application, built with React, that allows users to search the Spotify library, create a custom playlist, and then save the playlist to their Spotify accounts. (Requires having a Spotify account for playlists to be saved.)

---

## Potential Features :zap:

- [ ] Pressing enter triggers a search
- [ ] Include preview samples for each track
- [ ] Only display songs not currently present in the playlist in the search results
- [ ] Add a loading screen while playlist is saving
- [ ] Update the access token logic to expire at exactly the right time, instead of setting expiration from when the user initiates their next search
- [ ] After user redirect on login, restoring the search term from before the redirect
- [ ] Ensure playlist information doesn’t get cleared if a user has to refresh their access token
- [ ] Provide a way to fetch and see all your existing playlists

---

## How To Use 🔧

From your command line, first clone Jammming:

```bash
# Clone this repository
$ git clone https://github.com/inarie/Jammming.git

# Go into the repository
$ cd Jammming

```

Then you can install the dependencies using NPM:

```bash
# Install dependencies
$ npm install

# Start development server
$ npm start
```

**NOTE**:
If your run into issues installing the dependencies with NPM, use this command:

```bash
# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root
```

Once your server has started, go to this url `http://localhost:3000/` and you will see the website running.

---
