<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
        <link rel="icon" href="./assets/logo.png">
        <title>Spotify - Web Player: Music for everyone</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="spotify-clone(major-css-project).css">
    </head>
    <body>
        <div class="main">
            <div class="sidebar">
                <div class="nav">
                    <div class="nav-option" style="opacity: 1;">
                        <i class="fa-solid fa-house"></i>
                        <a href="*" >Home</a>
                    </div>
                    <div class="nav-option">
                        <i class="fa-solid fa-magnifying-glass"></i>
                        <a href="*">Search</a>
                    </div>
                </div>
                <div class="library">
                    <div class="options">
                        <div class="lib-option nav-option">
                            <img src="./assets/library_icon.png">
                            <a href="*">Your Library</a>
                        </div>
                        <div class="icons">
                            <i class="fa-solid fa-plus"></i>
                            <i class="fa-solid fa-arrow-right"></i>
                        </div>
                    </div>
                    <div class="lib-box">
                        <div class="box">
                            <p class="box-p1">Create your first playlist</p>
                            <p class="box-p2">It's easy, we'll help you</p>
                            <button class="badge">Create playlist</button>
                        </div>
                        <div class="box">
                            <p class="box-p1">Let's find some podcasts to follow</p>
                            <p class="box-p2">We'll keep you updated on new episodes</p>
                            <button class="badge">Browse podcasts</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="main-content">
                <div class="sticky-nav">
                    <div class="sticky-nav-icons">
                    <img src="./assets/backward_icon.png">
                    <img src="./assets/forward_icon.png" class="hide">
                </div>
                <div class="sticky-nav-options">
                    <button class="badge nav-item hide">Explore Premeium</button>
                    <button class="badge nav-item dark-badge"><i class="fa-regular fa-circle-down"></i>  Install App</button>
                    <i class="fa-regular fa-user nav-item"></i>
                </div>
                </div>
                
                <h2>Recently Played</h2>
                <div class="cards-container">
                    <div class="card">
                    <img src="./assets/card1img.jpeg" class="card-img">
                    <p class="card-title">Top 50-Global</p>
                    <p class="card-info">Your daily updates of most played tracks...</p>
                    </div>
                </div>
                <h2>Trending now near you</h2>
                <div class="cards-container">
                    <div class="card">
                    <img src="./assets/card2img.jpeg" class="card-img">
                    <p class="card-title">Top 50-Global</p>
                    <p class="card-info">Your daily updates of most played tracks...</p>
                    </div>

                    <div class="card">
                        <img src="./assets/card3img.jpeg" class="card-img">
                        <p class="card-title">Top 50-Global</p>
                        <p class="card-info">Your daily updates of most played tracks...</p>
                    </div>

                    <div class="card">
                        <img src="./assets/card4img.jpeg" class="card-img">
                        <p class="card-title">Top 50-Global</p>
                        <p class="card-info">Your daily updates of most played tracks...</p>
                    </div>
                    <div class="card">
                        <img src="./assets/pritam.png" class="card-img">
                        <p class="card-title">Daily Mix-1</p>
                        <p class="card-info">Pritam,Yo Yo Honey Singh...</p>
                    </div>

                    <div class="card">
                        <img src="./assets/aujla.png" class="card-img">
                        <p class="card-title">Daily Mix-2</p>
                        <p class="card-info">Karan aujla,Ninja,Shub...</p>
                    </div>
                    <div class="card">
                        <img src="./assets/mix-3.png" class="card-img">
                        <p class="card-title">Daily Mix-3</p>
                        <p class="card-info">Cheema Y,Inder chahal...</p>
                    </div>
                    <div class="card">
                        <img src="./assets/mix-4.png" class="card-img">
                        <p class="card-title">Daily Mix-4</p>
                        <p class="card-info">Glamtown,Guru Randhawa...</p>
                    </div>
                    <div class="card">
                        <img src="./assets/mix-5.png" class="card-img">
                        <p class="card-title">Daily Mix-5</p>
                        <p class="card-info">Pulkit Arora,Sumit Goswami...</p>
                    </div>
                    <div class="card">
                        <img src="./assets/ram.png" class="card-img">
                        <p class="card-title">Daily Mix-6</p>
                        <p class="card-info">Sachet-Parampara...</p>
                    </div>
                    <div class="card">
                        <img src="./assets/kisoriji.png" class="card-img">
                        <p class="card-title">Daily Mix-7</p>
                        <p class="card-info">Jassie Gill,Jaya Kishori...</p>
                    </div>
                </div>
                <h2>Featured charts</h2>
                <div class="cards-container">
                    <div class="card">
                    <img src="./assets/card5img.jpeg" class="card-img">
                    <p class="card-title">Top Songs-Global</p>
                    <p class="card-info">Your weekly update of the most played...</p>
                    </div>

                    <div class="card">
                        <img src="./assets/card6img.jpeg" class="card-img">
                        <p class="card-title">Top Songs-India</p>
                        <p class="card-info">Your weekly update of the most played...</p>
                        </div>

                        <div class="card">
                            <img src="./assets/card1img.jpeg" class="card-img">
                            <p class="card-title">Top 50-Global</p>
                            <p class="card-info">Your daily updates of most played tracks...</p>
                            </div>
                </div>
                <div class="footer">
                    <div class="line"></div>
                </div>
            </div>
            <div class="music-player">
                <div class="album">
                    <div class="album-image">
                        <img src="./assets/album_picture.jpeg">
                    </div>
                    <div class="album-info">
                        <p class="album-title">Daylight</p>
                        <p class="album-des">David Kushner</p>
                    </div>
                    <div class="album-icons">
                        <img src="./assets/album_icon1 (1).png" class="icon-1"></img>
                        <img src="./assets/album_icon2 (1).png" class="icon-2"></img>
                    </div>
                </div>
                <div class="player">
                    <div class="player-controls">
                        <img src="./assets/player_icon1.png" class="player-control-icon">
                        <img src="./assets/player_icon2.png" class="player-control-icon">
                        <img src="./assets/player_icon3 (1).png" class="player-control-icon" style="opacity: 1; height: 2rem;">
                        <img src="./assets/player_icon4 (1).png" class="player-control-icon">
                        <img src="./assets/player_icon5 (1).png" class="player-control-icon">
                    </div>
                    <div class="playback-bar">
                        <span class="curr-time">00:00</span>
                        <input type="range" min="0" max="100" class="progress-bar" step="1">
                        <span class="tot-time">03:33</span>
                    </div>
                </div>
                <div class="controls">
                    <div class="control-icon-1">
                        <img src="./assets/controls_icon1.png">
                    </div>
                    <div class="control-icon-2">
                        <img src="./assets/controld_icon2.png">
                    </div>
                    <div class="control-icon-3">
                        <img src="./assets/controls_icon3.png">
                    </div>
                    <div class="control-icon-4">
                        <img src="./assets/controls_icon4.png">
                    </div>
                    <div class="control-icon-5">
                        <img src="./assets/controls_icon5.png">
                    </div>
                    <div class="control-volume">
                        <input type="range" min="0" max="100" class="volume">
                    </div>
                </div>
            </div>
        </div>
    </body>
</html>
