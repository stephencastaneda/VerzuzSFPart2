# VerzuzCRUD Vanilla Script Project

# Exemplar

![Alt Text](https://github.com/stephencastaneda/VerzuzSFPart2/blob/main/Screen%20Recording%202021-08-03%20at%202.30.06%20AM%20(1).gif)

## User Story

Your artist is excited about the work you've done thus far on the app, but they are requesting a few improvements:

- As a user, they would like to be able to update a song.
- As a user, they would like to use an API to get a list of their top 100 songs.
- As a user, they would like to be able to search through this list of songs
- As a user, they would like some moderate styling done to the app.
- As a user, I would like this app to be deployed so I can use it on the go.

## Student Instructions

You have already completed the Read, Create, and Delete functionality for the app. Good news is you've gotten a good portion of the work done for your client, but there is room for some improvement. Some of the topics we will cover during today's lesson are:

- Update functionality in a CRUD application
- Web APIs
- JavaScript ASYNC/AWAIT
- Bootstrap Styling Library
- Responsive Design
- Deployment with Netlify

You will only need your previous Codesandbox Verzuz project to get started. 

## Resources

### UPDATE

#### Splice Array

* [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)

#### Remove Class

* [https://www.w3schools.com/howto/howto_js_remove_class.asp
](https://www.w3schools.com/howto/howto_js_remove_class.asp
)


#### Add Class

* [https://www.w3schools.com/howto/howto_js_add_class.asp](https://www.w3schools.com/howto/howto_js_add_class.asp)


#### Splice and Insert Object

* [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)

### NAVBAR

* [https://getbootstrap.com/](https://getbootstrap.com/)

#### Bootstrap Link & Script Tags

```
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    />

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script
      src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
      integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
      integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
      integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
      crossorigin="anonymous"
    ></script>

```

#### Bootstrap Navbar

```
 <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">
        <img
          src="https://uploads.cdn.triller.co/v1/avatars/60633816/1618505281_avatar.jpg"
          width="30"
          height="30"
          class="d-inline-block align-top"
          alt=""
        />
        Verzuz App
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-item nav-link" href="">Home</a>
          <a class="nav-item nav-link" href="">Song Search</a>
        </div>
      </div>
    </nav>
```
### LASTFM API

#### What is an API?

* [https://www.youtube.com/watch?v=s7wmiS2mSXY](https://www.youtube.com/watch?v=s7wmiS2mSXY)

#### LastFM API Account Setup

* [https://www.last.fm/api](https://www.last.fm/api)

#### Asynchronous Programming Explanation 

* [https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Concepts](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Concepts)

#### ASYNC Function

* [https://www.w3schools.com/js/js_async.asp](https://www.w3schools.com/js/js_async.asp)

#### Try/Catch Statement

* [https://www.w3schools.com/js/js_errors.asp](https://www.w3schools.com/js/js_errors.asp)

#### Fetch API

* [https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch
](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch
)

#### JSON Viewer Chrome Extension

* [https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh?hl=en&authuser=1
](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh?hl=en&authuser=1
)

#### Fetch URL

`https://ws.audioscrobbler.com/2.0/?method=artist.gettoptracks&artist={your-artist-name}&api_key={your-api-key}&limit=100&format=json`

### SEARCH

#### To Lowercase

* [https://www.w3schools.com/jsref/jsref_tolowercase.asp](https://www.w3schools.com/jsref/jsref_tolowercase.asp)

#### Filter Array

* [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

#### Includes Array

* [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)


### BOOTSTRAP STYLING

#### Bootstrap Card Docs

* [https://getbootstrap.com/docs/5.1/components/card/](https://getbootstrap.com/docs/5.1/components/card/)

##### Song List Bootstrap Cards - `index.js`

```
<div class="card flex-fill mb-3">
            <img class="card-img-top" src="${songs[songIndex].img}" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">${songs[songIndex].songName}</h5>
            </div>
            <ul class="list-group list-group-flush">
              <li class="list-group-item">Album Title: ${songs[songIndex].albumTitle}</li>
              <li class="list-group-item">Release Year: ${songs[songIndex].releaseYear}</li>
              <li class="list-group-item">Play Count: ${songs[songIndex].playCount}</li>
              <li class="list-group-item"><a href="${songs[songIndex].youTubeLink}" target="_blank">YouTube Video</a></li>
            </ul>
            <div class="card-body text-center">
              <button type="button" class="btn btn-danger deleteButton--${songIndex}">Delete</button>
              <button type="button" class="btn btn-secondary updateButton--${songIndex}">Update</button>
            </div>
```

#### Search List Bootstrap Cards - `search.js`

```
<div class="card" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title"></h5>
    <p class="card-text">Play Count: </p>
    <p class="card-text">Listeners: </p>
  </div>
</div>
```

#### Container Fluid

* [https://www.w3schools.com/bootstrap4/bootstrap_containers.asp
](https://www.w3schools.com/bootstrap4/bootstrap_containers.asp
)

#### FlexBox

* [https://css-tricks.com/snippets/css/a-guide-to-flexbox/
](https://css-tricks.com/snippets/css/a-guide-to-flexbox/
)

### APP DEPLOYMENT

* [https://www.netlify.com/](https://www.netlify.com/)




